# Advanced merging strategies
Merging in Git is a tool which allows developed work in one branch to be merged back into the main line of development, or in general to merge work between two branches. There are several strategies for merging, which allow for different ways in which the algorithm will merge work across two branches. We cover some of the most popular merging strategies that come with Git.

## Contents

## Strategies
- [Strategies](#strategies)
    - [Recursive](#recursive)
        - [Fast forward](#fast-forward)
        - [No fast forward](#no-fast-forward)
    - [Resolve](#resolve)
    - [Octopus](#octopus)
    - [Ours](#ours)
    - [Subtree](#subtree)
  - [Sources](#sources)

### Recursive
Recursive is the default merging strategy in Git when pulling or merging one branch. After branching and making some commits on the feature branch, there are typically some new commits on the main branch. Thus when branching, git recurses over the branch and creates a new merge commit, which will continue to have two parents. 

<img src="merge-without-ff@2x.png" alt="Visualization" width="600"/>

#### Fast Forward

#### No Fast Forward

### Resolve

### Octopus

### Ours

### Subtree

## Sources
List of sources used to obtain the information provided in this repository:
- https://www.atlassian.com/git/tutorials/using-branches/merge-strategy
- https://git-scm.com/docs/git-merge
- https://www.geeksforgeeks.org/merge-strategies-in-git/
- https://www.workingsoftware.dev/which-git-merge-strategy-is-appropriate-for-our-team/
