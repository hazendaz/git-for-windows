# Git for Windows Distro #
--------------------------

[![Java CI](https://github.com/hazendaz/git-for-windows/workflows/Java%20CI/badge.svg)](https://github.com/hazendaz/git-for-windows/actions?query=workflow%3A%22Java+CI%22)
[![Maven central](https://maven-badges.herokuapp.com/maven-central/com.github.hazendaz.git/git-for-windows/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.hazendaz.git/git-for-windows)
[![LGPL v3](https://img.shields.io/badge/License-LGPL_v3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0)

![hazendaz](src/site/resources/images/hazendaz-banner.jpg)

This project takes git-for-windows distribution for distribution using maven central.

For more information on git-for-windows, please see [git-for-windows](https://github.com/git-for-windows/git)

# Motivation #

Git-for-Windows does not currently provide a maven central distribution of the project. This project aims to solve that by providing users an alternative location to pull distribution.

# Use Case #

Maven based storage of distribution in common location to offer more secure download location for maven projects.

This is useful for projects such as makeself-maven-plugin that utilize the portable distribution when platform ran on doesn't actually have git available.
