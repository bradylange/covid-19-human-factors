# NASA Space Apps Challenge: COVID-19 - Human Factors
NASA Space Apps hackathon on developing solutions to various COVID-19 topics,
our topic being human factors (05/30/2020 - 05/31/2020).

COVID-19 Human Factors: [1]
[1] https://covid19.spaceappschallenge.org/challenges/covid-challenges/human-factors/details

## Instructions:
### Clone Remote Repository Locally
*Download remote repository locally*

1. `git clone https://github.com/bradylange/covid-19-human-factors.git`

### Create Personal Feature Preprocess Branch
*Switch to feature master branch*

2. `git checkout feature-preprocess/master`

*Create and switch to personal feature branch off feature master branch*

3. `git checkout -b feature-preprocess/first_name-last_name`

*Push local branch to remote branch*

4. `git push origin feature-preprocess/first_name-last_name`

Branch Hierarchy:
```
master
    develop
        feature-preprocess/master
            feature-preprocess/first_name-last_name
```

### Create Personal Feature Analysis Branch
*Switch to feature master branch*

5. `git checkout feature-analysis/master`

*Create and switch to personal feature branch off feature master branch*

6. `git checkout -b feature-analysis/first_name-last_name`

*Push local branch to remote branch*

7. `git push origin feature-analysis/first_name-last_name`

Branch Hierarchy:
```
master
    develop
        feature-preprocess/master
            feature-preprocess/first_name-last_name
        feature-analysis/master
            feature-analysis/first_name-last_name
```

### Change Feature Branch
*Switch to appropriate feature branch*

8. `git checkout feature-preprocess/first_name-last_name`

The above commands will create a branch hierarchy of:
```
master
    develop
        feature-preprocess/master
            feature-preprocess/first_name-last_name
        feature-analysis/master
            feature-analysis/first_name-last_name
```

### Merge Branches ###
***Note:*** *Use when feature branch is ready to deploy*

*Switch to branch to merge into*

1. `git checkout feature-preprocess/master`

*Merge branch into current branch*

2. `git merge feature-preprocess/first_name-last_name`

*Push local merge changes to remote branch*

3. `git push origin feature-preprocess/master`

- GitHub repository: *https://github.com/bradylange/covid-19-human-factors.git*
- Git commands: *https://git-scm.com/docs*