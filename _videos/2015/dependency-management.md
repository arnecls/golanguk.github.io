---
title: Dependency Management
metatitle: Dependency Management
speaker: William Kennedy
video-id: CdhucJShJU8
length: "0:51:10"
---
The "go get" tool is brilliant but the tool is also its own worse enemy. It is a major reason for the problems we have with dependency management. There is no clean way to fix the dependency problem and keep "go get". I believe solutions that wish to add or track a commit id or tag for the import url would actually create an even worse situation than we already have today. It is error prone and does not fix the inherent problem, a project needs to own and control its own consistent version of each dependency. Many agree that vendoring is the right solution, but how to vendor is the question. In this talk, I will show how vendoring is simplified and a consistent reproducible build is possible once you abandon “go get”.