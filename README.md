# Driving Data Repository

## Introduction

This repository provides driving data, that are recorded by utilizing various GPS receiver equipped devices. This repository consists of driving data collected from n participants.

## Dataset Description

The `driving data` directory structure is as follows:

`driver <n> --- day <m> --- <traffic situation> --- <route>`, 

where n-th driver collected the data on m-th day, under light, moderate or heavy traffic situation. `<route>` part indicates type of a road employed during data collection.

Each terminal directory contains one pair of driving data (file.csv) and a 128-bit binary key file (file.bin) derived from the data. The driving data pair are collected by using two GPS-equipped devices in a same vehicle. Each driving data file is `Comma Separated Value` formatted.

## Dataset Description

At this point, we do not provide contact information for anonymization purpose.
