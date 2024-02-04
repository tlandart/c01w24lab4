# <span style="color:#ADD8E6"> Lab4 - Advanced Git Usage </span>

<div align="right"> </div>

## <span style="color:#ADD8E6">Table of Contents </span>

- [Description](#desc)
- [Prerequisites](#pre)
- [Implementing the App](#impl)
  - [Database](#db)
  - [Backend](#back)
  - [Frontend](#front)
    - [The UI](#ui)
    - [Fetching Data](#data)
- [Your Task](#task)

<a id="desc"></a>

## <span style="color:#ADD8E6"> Description </span>


In this lab, you are going to perfo

1. Everyone will create a branch
2. Everyone will make commits, pull requests, etc.
3. Everyone will recreate a git simulator and submit.


<a id="pre"></a>

## <span style="color:#ADD8E6"> Background </span>


Modifications to the codebase are represented as **commit** objects.
The git history is an immutable linked list of commits.

Git flow is a commonly used git branch structure where the master branch stores the official release history, and the develop branch is used to integrate the features.

Feature branches are merged into develop.
Once develop has been tested, develop is merged into master.

If there are issues with a feature, we can revert the feature branch in develop.
If there are issues with a release, we can revert the merge commit in master.


Typical Git Usage:





<a id="impl"></a>

## <span style="color:#ADD8E6"> Implementing the App </span>



<a id="db"></a>

### Database

