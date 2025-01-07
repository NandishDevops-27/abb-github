# abb-github

Let's Start

Step-by-Step Guide
1. First Create a GitHub Repository
Go to GitHub: Open GitHub and log in.

Create a New Repository:

Click on the "+" icon in the upper-right corner and select "New repository."

Name your repository (in this case let say: abb-github), add a description (optional), choose visibility (public or private), and initialize it with a README file. Click "Create repository."

2. Clone the Repository into Locall
Clone the Repository:

Open your terminal/Gitbash and run the following command to clone the repository to your local machine:

git clone git@github.com:NandishDevops-27/abb-github.git

3. For Creating a Branching Strategy

After Cloning to your locall
cd abb-github (change to abb directory)
touch branching-strategy.md

markdown
# Branching Strategy

## Branch Types
- **master**: Stable code; production-ready or Release Branch
- **development**: Ongoing development; testings.
- **feature/{feature-name}**: Individual features.
- **hotfix/{issue-id}**: Urgent fixes.

## Workflow
1. Create a new branch from `development` for new features.
2. Implement changes and commit to the feature branch.
3. Push changes to GitHub and create a pull request to `development`.
4. Conduct code reviews, merge changes after approval.
5. Periodically merge `development` into `master` for releases.

Create and Switch to a New Branch:
git checkout -b feature/new-feature
Make Changes and Commit:

Make some changes, e.g., add a new file or modify branching-strategy.md.

git add .
git commit -m "Add/Update new feature" (commit message to understand)

Push the Branch to GitHub:
git push origin feature/new-feature else create with JIRA tkt number (eg, MART-5478)

5. Create a Pull Request
Go to your Repository on GitHub: Navigate to your repository on GitHub.

Compare & Pull Request:

You'll see a notification that you've pushed a branch. Click "Compare & pull request."

Add a title and description for your pull request and click "Create pull request."

6. Code Review
Assign Reviewers:

On the pull request page, assign reviewers by clicking on "Reviewers" on the right side.

Review and Comment:

Reviewers can now review the code changes, leave comments, request changes, or approve the pull request.

7. Merge the Pull Request
Merge the Pull Request:

Once approved, click the "Merge pull request" button on the pull request page and confirm the merge.