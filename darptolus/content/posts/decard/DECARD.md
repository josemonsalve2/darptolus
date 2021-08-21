---
title: "DECARD"
date: 2021-05-20T15:30:47-04:00
draft: false
author: "Diego"
authorLink: "https://www.darptolus.com/"
description: "DECARD: Distributed Execution Codelet Accelerated Runtime for Dataflow"

featuredImage: "DECARD_CAM.jpg"

tags: ["Cluster", "3Dprinted"]
categories: ["Projects"]

lightgallery: true

---

The **Distributed Execution Codelet Accelerated Runtime for Dataflow** (DECARD), is an extension of the Codelet Model designed to handle distributed parallel computation.

<!--more-->

The Distributed Execution Codelet Accelerated Runtime for Dataflow (DECARD), is an extension of the Codelet Model designed to handle distributed parallel computation. In order to achieve this, two functional units are defined. The Node Manager (NMGR) makes the high-level decisions for Threaded Procedure (TP) scheduling and workload distribution across local and remote resources. The Node Communicator (NCOM) interfaces with other nodes and manages communications. The runtime is designed to automate the program management that is usually defined by the user and enforced by the system, including synchronization, data and control communication. The simple data structures and state machines defined for the NCOM and NMGR make it possible to generate RTL designs and port these elements to the embedded FPGA or VLSI.

