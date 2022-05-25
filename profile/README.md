# UTEC ML Group

Welcome to the GitHub organization for the Machine Learning group from Universidad de Ingenieria y Tecnologia (UTEC)! In UTEC ML we aim for scalable, reproducible research projects that allow for fast and flexible collaboration. For this reason, we consider a series of principles taken from the Git Flow development workflow, as they address these objectives by design. In the next section we provide a summary of the steps to follow to start a new project or contribute to existing one.

## How to contribute

### How to contribute to an existing project

1. **Fork the project’s repository and clone it to your computer**: A fork creates a copy of the repository on your account. You can make any updates on your copy without affecting the original repository. For this purpose, you should clone _your_ copy of the project’s repository to your local computer. In this way, you can first prepare your code on your copy and then make a request to pull those changes back to the original repository.
2. **For any update you have in mind, create a feature branch on your fork and pull it to your computer**: You can pull your now branch to your computer, make updates on it, commit, and push to _your_ copy of the project’s repository.
3. **When your set of updates is in good shape, make a pull request that merges the feature branch on you fork with the _develop_ branch on the original project’s repository**: This practice is encouraged to minimize the chance of introducing buggy code to the shared organization’s repository, because the code sent on the pull request can be reviewed by peers.
4. **If there the reviewer leaves any observation about the code on you pull request, make the necessary updates to meet the comments from the reviewer**: Any comment on your code is there to make sure your implementation is error-free and meets the focus of the overall research project, so make your best effort to adjust your code as required by the reviewer.

### How to create a new project

1. **After creating the project, add a branch named _develop_**: Branch _main_ will contain the latest stable version of the research project (with stable, we mean a version that can reproduce our research results without any errors). Branch _develop_, then, meets the function of being the branch in which any updates independently developed by collaborators are merged, making sure there are no issues with the resulting code before trying to take the updates to _main_.

### How to manage a project

1. **Check on the _issues_ section**: These are arguably the most important tasks to track.
2. **Accept collaborator’s _pull requests_ when the code is ready to be integrated into the project**: Most pull requests are actually desired code updates in the context of research-oriented projects, so most will probably end up being merged to the organization’s repository. However, be careful not to introduce bugs into the organization’s main code by taking a detailed look into the implementation details from each of the updates presented in the pull request.
