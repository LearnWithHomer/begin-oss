# OSS at Begin <!-- omit in toc -->

This document is here to help define and refine what creating Open Source Software (OSS) means at Begin. As software developers and software consumers, we all have had experience interacting with OSS and are familiar with the benefits (and sometimes drawbacks) it can bring. The guidelines in this document are an attempt to begin an outline of what it means to be creators and contributors of open sourced projects as Begin’s engineering team.

- [A Quick Definition](#a-quick-definition)
- [Prologue](#prologue)
- [Why have a guide at all?](#why-have-a-guide-at-all)
- [Should I Open Source X?](#should-i-open-source-x)
  - [1. Who do you see using this project outside of Begin?](#1-who-do-you-see-using-this-project-outside-of-begin)
  - [2. If you/your team isn’t around to maintain the project anymore, who will adopt it?](#2-if-youyour-team-isnt-around-to-maintain-the-project-anymore-who-will-adopt-it)
  - [3. What extra considerations/steps would this add to our development/build/test/deploy pipeline?](#3-what-extra-considerationssteps-would-this-add-to-our-developmentbuildtestdeploy-pipeline)
  - [4. Is there any sensitive information or IP that would be exposed by making this project public?](#4-is-there-any-sensitive-information-or-ip-that-would-be-exposed-by-making-this-project-public)
- [Licenses](#licenses)
- [Distribution Channels](#distribution-channels)
- [Code of Conduct](#code-of-conduct)
- [Ownership](#ownership)
- [Existing Projects](#existing-projects)
- [Potential projects](#potential-projects)


## A Quick Definition
When we talk about OSS, we are talking about software projects whose source code is openly available to the public. More importantly, OSS projects contain a license that allows free redistribution in both source and compiled form.

## Prologue

Why should we care about OSS at Begin?

**Higher Code Quality** - Pushing code to place that is visible to the public should inspire Engineers to write higher quality, better tested, and better documented code.

**Increased Code Modularity** - Creating isolated standalone projects means that our code will naturally be better decoupled. This is especially beneficial as we transition into a service-oriented world.

**Exposure** -  Any company or individual can throw up a public repo and brag about how they’re committed to OSS. However, if we maintain a credible standard, this can still be a great opportunity for us to show off our hard work as an engineering team. Making quality work public gives us a good chance of attracting other like-minded talent with a similar appreciation for quality.

**Good Karma** - There are many open source libraries and tools that we use at Begin to help us accomplish our mission. Given the opportunity, we should try to give something of quality back to the community where it might help others accomplish their missions.


## Why have a guide at all?

Written guidelines can be helpful for those of us making the first jump into open sourcing at Begin. For others, it can serve as a point of reference. This way individuals and teams won’t need to reinvent the wheel when it comes to issues such as: choosing a license, choosing a distribution channel, etc.

Having a written guideline can also help us set a standard that ensures we are always releasing consistent and quality work to the public.

In the beginning, this guide will be fairly sparse. The goal is to fill this out as we gain more experience open sourcing projects as an organization and begin learning from mistakes and setting precedents.

## Should I Open Source X?

### 1. Who do you see using this project outside of Begin?

Who and how someone might benefit from the project who is not a part of Begin? If nothing concrete comes to mind, it does not mean that you should cease considering open sourcing the project (you never know who might find it useful!).

### 2. If you/your team isn’t around to maintain the project anymore, who will adopt it?

Who else besides yourself has enough knowledge of the project to maintain it if you
decide to step down? What happens to the project if your team switches focus or you join a new team?

### 3. What extra considerations/steps would this add to our development/build/test/deploy pipeline?

### 4. Is there any sensitive information or IP that would be exposed by making this project public?

Anything in the commit history that might compromise member privacy or expose credentials? Anything that might compromise Begin’s core business model?.

## Licenses
Most projects here at Begin have been/will be released with the MIT License (https://opensource.org/licenses/MIT)

## Code of Conduct
To ensure that our projects foster a safe and inclusive environment, we have adopted the Contributor Covenant as outlined [here](http://contributor-covenant.org/). The active maintainers of any Begin OSS project should take a moment to read through the Contributor Covenant before including it in their projects.

## Ownership
Credit should be always be given where credit is due. There are always exceptions to the rule, but generally speaking projects that are created and maintained on company time should fall under Begin’s organizational ownership. And the opposite case holds true as well. Projects that are created and maintained in an individual’s personal time should fall under the ownership of the individual. There can (and will) be cases where the line is blurred (i.e. a personal project that Begin decides to use). If need be, these should be evaluated on a case-by-case basis.

## Existing Projects

- [SQL Dependency Graph](https://github.com/LearnWithHomer/sql_dependency_graph)
    - Simple dependency graph visualizer for sql files.
- ????

## Potential projects

- [Bird](https://github.com/LearnWithHomer/bird)
    - Data Vault and Data Mart in pyspark.

- ????
