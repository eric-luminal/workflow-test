# Codeline Management

This repository has been made to illustrate managing multiple releases of a 
product.

## Introduction

The overall strategy looks a lot like gitflow where we have a develop branch to
base new features off of, release branches to create, tests, and tag release 
candidates, and master to track the latests tagged releases. Where it seems that
this workflow will fail us, is when we need to track and support multiple 
releases and versions of a product. This is because stock gitflow dictates that
you will base a hotfix off of the head of master. If the master branch of a 
product is on version 3.1.1 and a customer finds a problem in version 2.5.1 we
cannot base a hotfix off of master without including new and probably api 
breaking changes to the desired hotfix of 2.5.2. The goal of this repository
is to provide a git workflow where we can safely and sanely support multiple
codelines of a single product and share hotfixes across versions where ever
possible.

## Definitions

*   Sprint

     A regular, repeatable work cycle in scrum methodology during which work is
     completed and made ready for review. Scrum sprints are basic units of
     development in the scrum methodology. Generally, scrum sprints are less
     than 30 days long.

*   Release

    Definition and description here

*   Version

    Definition and description here

*   Patch

    Definition and description here

## Starting a project

## Branches

*   Develop
*   Feature
*   Release
*   Master

## Branch Naming Format

*   Develop
*   Develop
*   Feature
*   Release
*   Master


## Version Management

## Change Log Management

## Hotfix/Patching Workflow

### Cherry-Pick vs Merge