# remote-pairing-and-git

## Pairing, git and github

## Pairing Roles

**Navigator**: Verbally communicates next steps.

**Driver**: Reason's through navigator's instructions. Asks questions. Implements instructions. 

Pairing will move between strict to fluid roles. During learning you will reach points where neither of you know what to do next. That's good. Disolve roles temporarily, until one of you generates an idea of what to try next. The person with the idea becomes the navigator, and verbally communicates next steps to the driver. The driver reasons through the steps, asks questions, and implements.

During learning, you may notice that one member of the pair has more prior knowledge. They will tend to navigate more, while the driver works to reason through their instructions, generating questions, and implement. In this arrangement, if at any point, the driver generates an intution about next steps, consider switching roles. The pair with less prior knowledge, but a current working intuition, becomes the navigator and instructs the pair with more prior knowledge through next steps. The pair with more prior knowledge reasons through those instructions, asks meaningful questions, and implements.

## git and Github

git and Github are fundamentally complex. Our goal is to always be able to reason through git and github from first principles from day 1, and use git and github to work together effectively as a pair.

From first principles git and github are:

1. Data(git repository, which is a collection of nodes connected in a graph)

2. Locations(your machine or github.com or your pair's machine)

3. Algorithms(which operate on collections of nodes, that exist on your machine or github or your pairs machine)

4. Agreements between engineers about how to use the data, locations and algorithms to get work together

## Goal

Use driver and navigator roles to get comfortable with git from first principles. This may get messy. That's ok.

## Specification

### Part 1

Navigator(verbally communicating) navigates driver(reasoning and implementing on machine) through the following

Use `git status`, `git log`, `git branch` and github.com to inspect the state of your repository as you work.
- [ ] Create a new directory on your machine
- [ ] Initialize that directory as a github repository
- [ ] Create a new text file in that repository with a one sentence note to the navigator
- [ ] Add that new file to your first commit
- [ ] Create your first commit, containing the new file
- [ ] Create a new empty repostiory at github.com
- [ ] Push your git data to the empty repository on github `git push <github-url> <data>`
- [ ] Inspect your repository at github.com
- [ ] Compare the commit histories of the repository on github.com and your local repository

Switch the driver and navigator roles; navigator verbally communicates, driver implements on their machine)

### Part 2

Use `git status`, `git log`, `git branch` and github.com to inspect the state of your repository as you work.
- [ ] Create a new directory on your machine
- [ ] Initialize that directory as a github repository
- [ ] Inspect your repository at github.com
- [ ] Compare the commit histories of the repository on github.com and your local repository
- [ ] Pull your git data at github.com to your empty repository `git pull <location> <data>`
- [ ] Compare the commit histories of the repository on github.com and your local repository
- [ ] Create a new text file in that repository with a one sentence note to the navigator
- [ ] Add that new file to your commit
- [ ] Create a new commit containing that file
- [ ] Compare the commit histories of the repository on github.com and your local repository
- [ ] Push your git data to the empty repository on github `git push <location> <data>` //[trigger a ping] 

### Part 3

Use this workflow to pair together on the following:
- [ ] Implement a function that takes an array as its only argument and returns that array. Name it `identity`. 
- [ ] Implement a function that takes an array as its only argument, and returns the first element of that array. Name it `first`.
- [ ] Implement a function that takes an array as its only argument, and returns the last element of that array. Name it `last`.
- [ ] Look at the result of your implementations of these functions when they're passed a string instead of an array.
