[![Build Status](https://travis-ci.org/walkingdevs/tomee-war.svg?branch=master)](https://travis-ci.org/walkingdevs/tomee-war)
[![Download](https://api.bintray.com/packages/walkingdevs/mvn/tomee-war/images/download.svg)](https://bintray.com/walkingdevs/mvn/tomee-war/_latestVersion)

## What is it?
- Generic JEE 6 WAR template based on TomEE 1.7.x
- Profiles dev|staging|prod

## How to create a project?

CLI:

    mvn archetype:generate \
        -DarchetypeGroupId=walkingdevs \
        -DarchetypeArtifactId=tomee-war \
        -DarchetypeVersion=1.7.5 \
        -DarchetypeRepository=http://dl.bintray.com/walkingdevs/mvn \
        -DgroupId=test \
        -DartifactId=app \
        -Dversion=0

## Something wrong?

Let's discuss. I am a very discussful guy