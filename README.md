# A-Natural
## An Object-Oriented Framework for Amiga-like Operating Systems
Software Design Document

By Samuel D. Crow
samueldcrow@gmail.com
Started January 4, 2017
---

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

# System Overview

## Data Structures
This should include all the primitives found in the C++ Standard Template Library 2014 plus a few additions:
1. Compile-time type identification that makes run-time type information optional
1. Mandatory hash functions for all wrappers to the primitive types
1. Singly-linked lists for when there is just no need to walk backwards

## User Interface
MUI and its open-source counterpart, Zune, will be the basis for the graphical portion of the user interface.

## Media Playback
Datatypes will be supplied to perform all media playback.
