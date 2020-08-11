---
title: 'Book Notes: Operating System: Three Easy Pieces'
subtitle: 'My personal notes on Operating System: Three Easy Pieces'
summary: 'My personal notes on Operating System: Three Easy Pieces'
authors:
- ifkarsyah
tags:
- Book Notes
- Operating System
categories:
- Computer Science
date: "2020-08-10T00:00:00Z"
lastmod: "2020-08-10T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 2
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

https://www.student.cs.uwaterloo.ca/~cs350/F14/reading.html


## Part 1: Virtualizing the CPU

Virtualizing the CPU means creating illusion such that each application think it has its own CPU to use, 
although there's only one.

* * *

### Ch 1: Process, Kernel, System Calls
* http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-intro.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-api.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-mechanisms.pdf

* * *

### Ch 2: Scheduling
* http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched.pdf 
* http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched-mlfq.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched-lottery.pdf

* * *


## Part 2: Virtualizing the Memory

* * *

### Ch 1: Virtual Memory
* http://pages.cs.wisc.edu/~remzi/OSTEP/vm-intro.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/vm-api.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/vm-mechanism.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/vm-segmentation.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/vm-paging.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/vm-tlbs.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/vm-smalltables.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/vm-beyondphys.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/vm-beyondphys-policy.pdf

* * *

## Part 3: Concurrency

* * *

### Ch1: Threads
* http://pages.cs.wisc.edu/~remzi/OSTEP/threads-intro.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/threads-api.pdf

* * * 
  
### Ch2: Synchronization
* http://pages.cs.wisc.edu/~remzi/OSTEP/threads-locks.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/threads-locks-usage.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/threads-cv.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/threads-sema.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/threads-bugs.pdf

* * *

## Part 4: Persistance

* * * 

### Ch 1: Filesystem
* http://pages.cs.wisc.edu/~remzi/OSTEP/file-intro.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/file-implementation.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/file-journaling.pdf

* * *

### Ch 2: IO
* http://pages.cs.wisc.edu/~remzi/OSTEP/file-devices.pdf
* http://pages.cs.wisc.edu/~remzi/OSTEP/file-disks.pdf

## Part 5: Security

