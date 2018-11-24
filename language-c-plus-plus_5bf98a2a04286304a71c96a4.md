
*[Supported C++ versions](#supported-c++-versions)
*[Dependency Management](#dependency-management)
*[Environment variables](#environment-variables)
*[System dependencies](#system-dependencies)
*[A sample C project](#a-sample-c-project)


## Supported C++ versions

The following Semaphore 2.0 project selects a different `g++` version:


## Dependency Management

As there is no standard way to perform dependency management in C++, we will
skip that in this guide.

You can use the `cache` Semaphore 2.0 utility to store and load any files or
C++ libraries that you want to reuse in other jobs.

## Environment variables

Semaphore 2.0 does not set environment variables related to C++ so you will
have to define them on your own at the task level.

## System dependencies

C++ projects might need packages like database drivers. As you have full `sudo`
access on each Semaphore 2.0 MV, you are free to install all required packages.

## A sample C++ project

