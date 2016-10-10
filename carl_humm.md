#Branching

## What is branching

With GIT version control branches are essentially  moveable pointers that reference to the current working environment. The main branch is
called the master branch. Other branches can be created using the git checkout -b [name] command. When a new branch is checked out the HEAD branch ( a unique pointer)
references to it as the current working environment. This is beneficial as it essentially isolates the new branch from the master branch which allows a user
to freely experiment with new features without effecting / breaking the main project through pushing via the master branch.

## Why is it used
