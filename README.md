# Kazi+ Ed Workflow
Kazi+ Ed uses Github to manage the whole learning worflow. We mainly make use of *Github issues*, *branching*, *pull requests (PR)* and *reviews*.


### Workflow:

- Fork the given repository to your Github profile
- Each drill or checkpoint will be given out as a **Github issue**.
- For each issue (for example [this](https://github.com/kaziplused/workflow-intro/issues/1)), create a branch thus:
  
  ```
  <issue-number>-issue-tittle>
  e.g.
  1-hr-arraysum for the first issue on this repo.
  ```
- Your solutions should be put in a folder named `issue-<number>` (number padded with 0's) e.g. `issue-001`
- Work out your solution from the branch, then commit changes and push.
- Raise a PR against your `master` branch (not this project's master branch).
- Your PR will then be reviewed by your peers and merged appropriately

See example [here](https://github.com/ProfNandaa/upskilling-c-sharp/pull/1)


## Appendix

### Workflow Explained

Quick Git walkthrough:

- Fork the repo (click on the "Fork" button at the top-right).
- Clone your forked repo, e.g.
  
  ```
  git clone https://github.com/yourusername/workflow-intro.git
  ```
- Create a branch for your solution, e.g.
  
  ```
  git checkout -b 1-drill-0-sum-array
  ```
- After making changes, stage the changes:
  
  ```
  git add --all
  ```
- Commit the staged changes, e.g.
  
  ```
  git commit -m "solution: hackerrank sum-array"
  ```
- Push your changes, e.g.

  ```
  git push origin 1-hr-sum-array
  ```

**Making A pull request:**

**NOTE:** Make sure you choose your `master` branch as the _base_, and not the original repo's master branch.

<img width="1072" alt="screen shot 2017-02-10 at 10 25 15 am" src="https://cloud.githubusercontent.com/assets/261265/22818037/fdc35612-ef7b-11e6-9c3b-4d19287af4ae.png">

**Reviewing Code:**
Your mentor will review your code and give you feedback on what to improve on. If all looks good, they will merge your PR once your submission _meets expectations_.

<img width="1063" alt="screen shot 2017-02-10 at 10 26 10 am" src="https://cloud.githubusercontent.com/assets/261265/22817993/b241c660-ef7b-11e6-8ca4-4fe405c95b4d.png">

.....................................................................................
