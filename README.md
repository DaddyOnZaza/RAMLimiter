# RAM Limiter
RAM Limiter is a utility designed to optimise the RAM usage of any application through the process of Garbage Collection (GC).

## Overview
Now you can limit any application and as many applications.

RAM Limiter was developed to address the challenge of applications, like Discord, that tend to cache objects unnecessarily, leading to high RAM usage. It leverages the `GC.Collect` method for efficient garbage collection, thereby freeing up the memory that these applications consume.

This tool proves particularly useful for systems with limited RAM, where applications like Discord could use up to 1.3GB. By releasing these resources, it allows RAM-intensive games and other applications to run more smoothly.

The RAM Limiter is a standalone solution that eliminates the need for other software like Razer Cortex™. Moreover, it provides an updated and maintained alternative to the original version of this tool, which is no longer supported and has been outdated for over a year.

## Usage
RAM Limiter works by automatically freeing up the RAM that is being used by any application. This not only provides your device with more available memory but also results in less battery consumption.

Upon launching the application, you can choose the application you want to optimise - Chrome, Discord, or OBS. These are the applications that are known to consume significant RAM resources, but the tool can be used with any application.

## Inspiration
This tool is no longer maintained. It was found to consume more CPU resources than Discord itself, resulting in a trade-off between free CPU and free RAM. This not only led to increased power usage but also negated the purpose of freeing up RAM.


Our version of the RAM Limiter improves upon the original by focusing on efficient memory management without overutilising the CPU. Some parts of the code were reused from the original repository.
