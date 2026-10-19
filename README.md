# Electric Wealth Specifications

This is the **specifications repo** for the **Electric Wealth** application. It holds the **requirements**, **solution**, and **implementation** specifications that define what the application should do, how it is designed, and how it is built.

It covers these repos:

- [`electric-wealth-workspace`](https://dev.azure.com/IntelliwareDev/AI_Knowledge_Repo/_git/electric-wealth-workspace): project configuration and tooling
- [`electric-wealth-db`](https://dev.azure.com/IntelliwareDev/AI_Knowledge_Repo/_git/electric-wealth-db): database
- [`electric-wealth-api`](https://github.com/adam-mccormick-em/electric-wealth-api): REST API
- [`electric-wealth-web`](https://dev.azure.com/IntelliwareDev/AI_Knowledge_Repo/_git/electric-wealth-web): web app

For reference material on how the application works today, see [`electric-wealth-knowledge-base`](https://dev.azure.com/IntelliwareDev/AI_Knowledge_Repo/_git/electric-wealth-knowledge-base).

## Nothing is committed to `main`

`main` stays as a clean starting point. Do your work on a branch, using the same branch name in every Electric Wealth repo:

```bash
git checkout main
git pull
git checkout -b <your-branch-name>
```
