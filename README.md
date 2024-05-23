# automation-with-github-actions

Building Resilient CI/CD Pipelines and Automating Development Tasks with GitHub Actions [-->source](https://www.udemy.com/course/mastering-github-actions-beginner-to-expert/)

## Contents

### 01 GitHub Actions Building Blocks
* `01-building-blocks.yaml`

### 02 Event Triggers
* `02-workflow-events.yaml`

### 03 Workflow Runners
* `03-workflow-runners.yaml`

### 04 Using Actions
* `04-using-actions.yaml`

### 05 Event Filters and Activity Types
* `05-1-filters-activity-types.yaml`
* `05-2-filters-activity-types.yaml`

## How this repository is structured

- Only the most recently created workflow is kept in the .github/workflows directory to prevent unnecessary workflows from being triggered.
- Unused workflow YAML files are organized into folders named after them, along with their relevant files.
- To test a specific workflow, move its YAML file into the .github/workflows directory.
- If multiple workflows are added, they will run in parallel in their own isolated environments.


# Reference Material
* [GitHub Actions Documentation](https://docs.github.com/en/actions)
* [GitHub Actions Marketplace](https://github.com/marketplace?type=actions)
* [GitHub Actions Course Repository](https://github.com/udemy-lauromueller/github-actions-course)
* [GitHub Actions Course Example E2E Repository](https://github.com/udemy-lauromueller/github-actions-course-example-e2e)
* [YAML Tutorial](https://www.cloudbees.com/blog/yaml-tutorial-everything-you-need-get-started)
* [Cron expression generator](https://crontab.cronhub.io/)

-- delete me
-- delete me