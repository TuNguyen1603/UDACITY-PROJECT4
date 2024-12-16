# Pipeline Process: GitHub and CircleCI

## GitHub

- A developer begins by creating a repository on GitHub.
- The code is added to the repository, and changes are committed.
- The repository is linked to CircleCI, which automatically triggers the pipeline whenever new changes are pushed.

### CircleCI

- To enable CircleCI, the .circleci/config.yml file must be located in the root directory of the repository.
- This configuration file allows CircleCI to perform its two core functions:
  `Build the project.`
  `Deploy both the backend and frontend.`
  The process is visually illustrated in the file: high-level-pipleline.jpg.
