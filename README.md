# Reading Notes

## Intro to Software Development

**Git Branching**
Commit =  `git commit`

Checkout branch = `git checkout newImage`

Create branch and checkout = `git checkout -b [yourbranchname]`

Merge = `git merge`

- A commit records a snapshot of all tracked files, can compress a set of changes called 'delta'
- Git maintains history tracking on all commits
  - mentions ancestor commits above those
  > [git merge-base finds best common ancestor(s) between two commits to use in a three-way merge. One common ancestor is better than another common ancestor if the latter is an ancestor of the former. A common ancestor that does not have any better common ancestor is a best common ancestor, i.e. a merge base.](https://git-scm.com/docs/git-merge-base)
 - **Word to the wise: branch early, and branch often**
 - There is no storage or memory overhead, logically divide up your work!
 - A branch includes the work of this commit and all parent commits

## Foundations of Software Development
## Intermediate Software Development
## Advanced Software Development
