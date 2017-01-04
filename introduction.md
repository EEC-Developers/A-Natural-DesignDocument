# Introduction

## Purpose
To bring a moderately sized object-oriented framework to the Amiga-like platforms.  Microsoft has its .NET platform, Apple has Objective C and Linux has too many frameworks to count.  Amiga has MUI as its primary BOOPSI derived framework for the GUI but lacks general purpose data structures.  That is the gap this product is to fill.

## Scope
Since frameworks of this type generally grow quite large the aim is to limit the size to something that will run on a system with 16 Mebibytes or less.  Beyond the scope of this project will be garbage collected virtual machine architectures because this project will only contain the runtime libraries necessary to make application development easier on statically compiled languages like C++ and AmigaE.

## Overview
This document is intended to outline the most general aspects of the framework.  It will be divided into categories:

1. Data Structures
1. User Interface
1. Media Playback
1. Compiler Infrastructure
