# NUnit Legacy Projects

This repository contains information about the mission, vision and governance of the NUnit Legacy organization.

## Our Mission

To provide continued __basic support__ to users of NUnit V2 while also assisting them in __preparing for conversion__ to NUnit 3.

## Background

With the release of NUnit 3.0, the __NUnit Project__ archived the code for NUnit V2 and announced that no further releases would be made. At the time, we believed that users would convert more rapidly to NUnit 3 than has turned out to be the case.

For various reasons, usually external to the software, some users must continue to use NUnit 2.6.4, the last release of V2, in spite of the advantages of the NUnit 3 platform. In some cases, this has to do with legacy software used by the applications they are testing. In other cases, the reasons for sticking with V2 are organizational in nature. In a few cases, problems with the newer releases affect them.

In order to move ahead, the __NUnit Project__ team, of which I remain a part, had to cut the cord and focus on the new NUnit releases. This organization and it's projects are intended to give some relief to users who most continue to work with NUnit V2.

## Vision

As indicated in the __Mission Statement__ the NUnit Legacy projects aim to do two things:

1. Provide __basic support__ to V2 users.
2. Assist those users to __prepare for conversion__ to NUnit 3.

### Basic Support

"Basic" support could mean a lot of things! Here, the intent is that we will fix bugs that have no easy workaround, provided that they can be fixed without making the major architectural changes that were essential to moving to NUnit 3.

In other words, for a bug to be fixed, it needs to have some serious affect on users and to be fixable in a relatively direct way, without re-design of the V2 framework or other programs.

We will also consider back-porting relatively small features from NUnit 3 to the V2 release under the same circumstances.

In both cases, users should file a bug report or feature request as an issue under the appropriate project.

### Preparing for Conversion

We will also provide guidance in how to convert projects to NUnit 3 and will support features in V2 that can make that conversion easier. Two sorts of features are envisioned along these lines:

1. Where an old attribute or method is going away in NUnit 3, to be replaced by a different interface, we will add the new attribute or method to NUnit V2.

2. We will provide reporting and other information about issues in the test code that require change in NUnit 3.

   _Note: The NUnit 2.6.5 release is almost entirely made up of features of this type._

### NUnit Programs Supported

Initially, the NUnit Legacy project will provide point releases of NUnit V2, consisting of the framework, core and runners.

In future, we may add other items, such as releases of the V2 NUnit VS adapter and the V2 framework driver for use under NUnit 3.

## Governance

A governance document is in preparation.

<hr>
<div align="right">
Charlie Poole<br>
April, 2018
</div>
