# Repository Rules
To ensure a consistent, scalable, and efficient development process, this repository requires following some 
contribution rules for overall collaboration, commit messages, branches, forks, pull requests, and issues.

We align our rules with industry standards.

## 1. Overall Collaboration Process
Step 1: Fork the main branch of this repository. <br>
Step 2: Add your project in the forked repository. <br>
Step 3: Create a Pull Request, by using the ```Collaboration Request Template```. <br>
Step 4: After creating the Pull Request, send and email to ```code-for-humanity@networkinstitute.org```, which contains the link to the Pull Request. 
Step 5: We will reach out to you, schedule meeting, and align on the next steps. 

## 2. Github Issues & Branches
- [Feature Issue Template](.github/ISSUE_TEMPLATE/feature_issue.md)
- [Bug Report Issue Template](.github/ISSUE_TEMPLATE/bug_report_issue.md)

Use the appropriate Github Issue template, and link the issue name and to the branch name, as in the example below.

```
e.g., 
issue name: API Integration With Database
issue number: #18
 
--> branch name: 18-api-integration-with-database
```
#### Conventions
- in branch name, start with the issue number 
- in branch name, write the processed issue name, to the branch conventions
- in branch name, separate words only by ```-``` (hyphens)
- in branch name, use only lower case characters


Pushing on the main branch and force pushing (on any branch) is disabled from repository's settings.

## 3. Commit conventions
Each commit should have the following format:
```
<type>: <description>

[optional body]
```

Types: 
- ```feat``` (for commits that add new functionality), 
- ```fix``` (for commits that fix bugs/errors)

Description
- must be non-empty, under 256 characters

Body
- optional, yet recommended for larger commits
- a more detailed description of the commit
- up to 256 characters
- if a body is provided, it should be **added a blank line** in between the commit message and the body content


## 4. Pull Requests
- [Branch Pull Request Template](.github/PULL_REQUEST_TEMPLATE/branch_pull_request_template.md)
- [Collaboration Request Template](.github/PULL_REQUEST_TEMPLATE/collaboration_request_template.md)

We provide two pull requests templates
- template for in-repository-branches pull requests, where a branch is pulled into another branch from the same repository
- collaboration pull request template, used for requesting the merge of a branch from a forked repository, in our repository.
This serves as an initial collaboration message with the development team of Code for Humanity, and represents step 2
from ```§1. Overall Collaboration Process```

---

This activity is supported by the [Network Institute](https://networkinstitute.org/) under the Code for Humanity initiative.  


#### References:
[1] [Google Developers - Commit Message Guide, accessed July 14th, 2024](https://developers.google.com/blockly/guides/contribute/get-started/commits)