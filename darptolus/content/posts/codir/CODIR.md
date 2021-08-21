---
title: "CODIR"
date: 2021-05-20T15:30:32-04:00
draft: false
author: "Diego"
authorLink: "https://www.darptolus.com/"
description: "CODIR: Codelet Model Intermediate Representation"
resources:
- name: "CODDIR"
  src: "CODIR_pic.jpg"

tags: ["Compiler", "MLIR"]
categories: ["Projects"]
---

The **Codelet Model Intermediate Representation** (CODIR) is our proposed dialect to create a compiler and domain-specific language for the Codelet Model. 

<!--more-->

# CODIR: MLIR Dialect
The Codelet Model Intermediate Representation (CODIR) is our proposed dialect to create a compiler and domain-specific language for the Codelet Model. We believe MLIR is thecompiler infrastructure to build this upon due to its adoption across the industry and its design rationale matching our goals exactly. These types will have to emulate the same properties, respectively outlined in the Codelet Program Execution Model.