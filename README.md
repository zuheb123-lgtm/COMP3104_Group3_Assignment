# COMP3104_Group3_Assignment

## Group Members
- **Leader:** Zuheb Mohamud (101555019) - [GitHub](https://github.com/zuheb123-lgtm)
- **Member 2:** Teni Ogun (101568492) - [GitHub](https://github.com/teni-create)
- **Member 3:** Eseosa Travis Eweka (101583426) - [GitHub](https://github.com/Travis-bug)
- **Member 4:** Judene Brown (101503637) - [GitHub](https://github.com/judene-13)

## Project Description

This COMP3104 group assignment demonstrates a collaborative Git and
GitHub workflow. Each member works on a separate branch and creates
three text files covering George Brown College, COMP3104, and the
importance of DevOps in the software development life cycle.

Members record their progress through meaningful commits and submit
their contributions through pull requests to master. The repository
also includes a GitHub Actions workflow for automated CI checks.

## Setup Instructions
1. Clone the repository: `git clone https://github.com/zuheb123-lgtm/COMP3104_Group3_Assignment.git`
2. Move into the project folder: `cd COMP3104_Group3_Assignment`
3. Switch to your branch: `git checkout STUDENTID-Name`
4. Pull the latest changes before you start: `git pull origin master`
5. Make your changes, commit, push, and open a pull request into `master`.

## CI/CD Pipeline
This project uses GitHub Actions for continuous integration. The workflow is in `.github/workflows/ci.yml`.
It runs automatically on every push and pull request using an `ubuntu-latest` runner, checks out the code,
and prints messages to confirm the pipeline is working. A pull request is only merged once its checks pass.

## Branching Strategy
We used a per-developer branching strategy. Each member has their own branch named `STUDENTID-Name`
(for example, `101555019-Zuheb`). Nobody commits directly to `master`, which is protected by a ruleset
that requires a pull request. Each member pulls from `master` to stay up to date, then merges their work
through a pull request. Merge conflicts in `README.md` were resolved locally before merging.