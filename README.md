# CSCI 5828 - Fall 2016

## Homework 02

**Author:** Yue ZHANG

**Goal:** To get familiar with Git. Due by Lec 09 start.
commit 4
*Master branch:*

- git init
- vi README.md [Edit README.md]
- git add README.md
- git commit -m "Commit 0"
- vi README.md [Edit README.md]
- git add README.md
- git commit -m "Commit 1"
- vi README.md [Edit README.md]
- git add README.md
- git commit -m "Commit 2"
- git log
- git checkout 2f4503c2cc31b2d2f56043d5ef0902bf13390576

*Bug-fix branch:*

- git checkout -b bug-fix
- vi README.md [Edit README.md]
- git add README.md
- git commit -m "Commit 3"

- vi README.md [Edit README.md]
- git add README.md
- git commit -m "Commit 4"
- git merge master
- vi README.md [Edit README.md]
- git add README.md
- git commit -m "Commit 5 fix conflict"
- vi README.md [Edit README.md]
- git add README.md
- git commit -m "Commit 6"
- git log
- git checkout dc3997c180ae6ecd09194033fe4b36947d73d294


*Bug-fix-experimental branch:*

- git checkout -b bug-fix-experimental
- vi README.md [Edit README.md]
- git add README.md
- git commit -m "Commit 7"
- vi README.md [Edit README.md]
- git add README.md
- git commit -m "Commit 8"
- vi README.md [Edit README.md]
- git add README.md
- git commit -m "Commit 9"
- git checkout master

- git merge bug-fix-experimental [Commit 11]
- vi README.md [Edit README.md]
- git add README.md
