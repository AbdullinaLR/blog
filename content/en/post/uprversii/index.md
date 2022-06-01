---
title: Version Control System
subtitle: Figuring out versioning

# Summary for listings and search engines
summary: Versioning

# Link this post with a project
projects: []

# Date published
date: '2022-05-03T00:00:00Z'

# Date updated
lastmod: '2022-05-03T00:00:00Z'

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

tags:
  - Academic
  - Education

categories:
  - Demo

---

## Versioning
Version control systems (Version Control System, VCS) are used when working with several many people on the same project. Typically, the main project tree is stored in the local or a remote repository to which access is configured for project participants. When making changes to the content of the project, the version control system allows them to fix, combine changes made by different project participants,rollback to any earlier version of the project, if required. Classical version control systems use a centralized model, assuming the existence of a single repository for storing files. Most of the version control functions are carried out by a special server. The project participant (user) before starting work through certain command gets the version of files it needs. After making changes, the user commits the new version to the repository. This does not remove previous versions. from the central repository and you can return to them at any time. The server can save an incomplete version of the modified files, and produce the so-called delta- compression—keep only changes between successive versions, which allows you to reduce the amount of stored data. Version control systems support traceability and resolution conflicts that may arise when several people work on one file. You can merge (merge) changes made by different participants (auto-mathically or manually), manually select the desired version, cancel the changes altogether or lock files for modification. Depending on the settings, blocking is not allows other users to obtain a working copy or prevents modification working copy of the file by means of the OS file system, thus providing privileged access to only one user working with the file. Version control systems can also provide additional, more flexible functionality. For example, they can support multiple versions of the same file, keeping a common history of changes up to the branch point
versions and each branch's own change histories.Information about which of the participants, when and what changes were made. kind of information is stored in the change log, access to which can be restricted. Unlike classical ones, in distributed version control systems, the centralthe repository is optional. Among the classic VCS, CVS, Subversion are the most famous, and among the distributed nyh - Git, Bazaar, Mercurial. The principles of their work are similar, they differ mainly the syntax of the commands used in the work.
