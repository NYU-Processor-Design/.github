# Contributing to NYU Processor Design
- [Issues and Pull Requests](#issues-and-pull-requests)
- [Prefixes](#prefixes)
    - [General](#general)
    - [Issue-specific](#issue-specific)
- [Examples](#examples)
- [Behavioural Expectations](#behavioural-expectations)
- [Code Format and Style](#code-format-and-style)
- [Developer's Certificate of Origin 1.1](#developers-certificate-of-origin-11)

## Commits, Issues and Pull Requests
All commits, pull requests and issues must begin with one of the 
prefixes described below to provide context for maintainers.

This will help streamline the process of merging pull requests, 
with maintainers not having to write new commit messages, or, allow
people to effectively reply to an issue.

Beyond using the prefixes, contributors are also encouraged to use
parentheses after the prefix to give further context. For example:
- `docs(dn)` for design notebook
- `docs(git)` for git documentation
- `fix(decoder)` for a fix on a decoder
- `qn(ninja)` for a question about ninja

There are examples below for further clarification. 

## Prefixes
#### General
- docs: Relating to documentation
- fix: Fixes to something
- chore: Routine tasks unrelated to documentation or fixes 

#### Issue-specific
- bug: Report bugs
- qn: Questions regarding the repository

## Examples
1. Question about an onboarding lab
   - Browse current and past issues to see if your question 
     has been answered before to prevent duplicates
   - If not, open a new issue with the title:  
     `qn(CMake): variable usage through VSCode`
   - Elaborate on issue in the description, provide screenshots, 
     error messages, steps to reproduce, etc.
2. Design notebook pull request
   - Make changes to your fork
   - Create a pull request with the title:  
   `docs(dn): update \<name\> dn for week of october 10`
3. Bug report for the simulator
   - Browse open and closed issues to see if your bug has been 
     reported before to prevent duplicates
   - If not, open a new issue with the title:  
     `bug(amba): incorrect simulation of AHB decoder`
   - Elaborate on issue in the description, provide screenshots, 
     error messages, steps to reproduce, etc. 
4. Issue about the WSL development environment
   - Browse open and closed issues to see if your issue has been 
     already reported to prevent duplicates.
   - If not, open a new issue with the title:  
     `docs(wsl): missing documentation for WSL`
   - Elaborate on your issue issue in the description 
5. New documentation for the WSL development environment
   - Make changes to your fork
   - Create a pull request with the title:  
   `docs(wsl): create setup docs for WSL`

## Behavioral Expectations
The NYU Processor design team is part of NYU and every memeber is
expected to uphold the [University Student Conduct Policy](https://www.nyu.edu/about/policies-guidelines-compliance/policies-and-guidelines/university-student-conduct-policy.html).

Any violates to the University Student Conduct Policy will be
dealt with swiftly by VIP leadership. The policy extends to the git
repositories, commit messages, issues, pull requests, technical 
documentation, and all other communication. 

## Code Format and Style
Most repositories come with code format files such as `.clang-format`. 
Before pushing code, please ensure that you have formatted your code according to the provided code format file, unless otherwise specified.

## Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.
