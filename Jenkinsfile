#!/usr/bin/groovy

@Library('github.com/fabric8io/fabric8-pipeline-library@master')

mavenNode(parameters: [mavenImage: 'piyushgarg/testnode']) {
    sh 'node --version'
    sh 'npm version'
}

