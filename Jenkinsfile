#!/usr/bin/env groovy
//Leave the above line alone.  It identifies this as a groovy script.
@Library('vs-build-tools') _Disable 2018 builds
dev/disable_2018_builds

def lvVersions = ['2019', '2020']

ni.vsbuild.PipelineExecutor.execute(this, 'vs_cd_build', lvVersions)
diffPipeline(lvVersions[0])
