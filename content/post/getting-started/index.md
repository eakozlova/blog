---
title: Git version control
subtitle: Today's our topic is git and the way it works.

# Summary for listings and search engines
summary: Git is open and free, easy to learn and has magnificent functionality
# Link this post with a project
projects: []

# Date published
date: '2020-12-13T00:00:00Z'

# Date updated
lastmod: '2020-12-13T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin
  - 吳恩達

tags:
  - Academic
  - 开源

categories:
  - Demo
  - 教程
---



## Git control version

In basic Version Control Systems (VSC) are used when several people work on one project. And usually, the main project tree is stored in a local or remote repository, to which access is configured for project participants. 
When making changes to the project content, the version control system allows you to fix them, combine changes made by different project participants, roll back to any earlier version of the project, if required.
 
Version control systems support the ability to track and resolve conflicts that may arise when several people work on a single file. You can merge (merge) changes made by different participants (automatically or manually), manually select the desired version, cancel the changes altogether or lock files for modification. Depending on the settings, the lock does not allow other users to get a working copy or prevents changing the working copy of the file by means of the OS file system, thus providing privileged access to only one user working with the file.

Version control systems can also provide additional, more flexible functionality. For example, they can support working with multiple versions of a single file, keeping a common history of changes up to the point of branching versions and their own change histories of each branch. In addition, information is usually available about which of the participants, when and what changes were made. Usually this kind of information is stored in the change log, access to which can be restricted.

Unlike the classical ones, in distributed version control systems, a central repository is not mandatory.
Among the classic VCS, the most famous are CVS, Subversion, and among the distributed ones — Git, Bazaar, Mercurial. The principles of their work are similar, they differ mainly in the syntax of the commands used in the work.

