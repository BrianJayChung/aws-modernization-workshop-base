---
title: "Module 1: LaunchDarkly Feature Flag"
chapter: true
draft: false
weight: 4
---

# YOUR FIRST LAUNCHDARKLY FEATURE FLAG

### Welcome

In this workshop we will learn to perform a "dark release" of a new feature in our demo application using AWS App Runner.

At your company, ABC, you are releasing a new custom dashboard and your mission is to deliver this new feature as reliably, quickly and safely as you can. Using a LaunchDarkly feature flag, you will be able to decouple release from deploy and dynamically manage this feature release through a feature flag.

![Source Service](/images/setup/module-1-new-feature.png)

This master will walk through deploying a demo application using AWS App Runner, and setting up a LaunchDarkly feature flag to control the release of the new feature through a feature flag

### Learning Objectives
- How small, measurable changes drive agility: Build, deploy and test multiple times a day instead of making large complex changes that are difficult to integrate and test
- How to deliver business value rapidly by releasing new features and functionality to customers faster
- How to set up configuration-as-code for your CI/CD tooling (CloudBees CI)
- How to templatize CI/CD pipelines to conform with best practices.  Providing CI/CD as a service for end users
- Ensuring governance and standardization while also empowering developer, security and operations teams by running Jenkins at scale