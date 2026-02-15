# Git Branching and Merging

## 1. Branching

**Branching** in Git allows you to create independent lines of development. Each branch is a copy of the project where you can make changes without affecting other branches.

### Example:
- You are working on a project called `website`.
- You want to add a new feature without affecting the main version.
- You create a branch called `feature-login`.
- All changes on `feature-login` do not appear on the `main` branch until you merge it.

### Benefits of Branches:
- Work on multiple features simultaneously.
- Protect the main code from errors while experimenting.
- Make collaboration easier (each team member works on their own branch).

---

## 2. Merging

**Merging** is the process of integrating changes from one branch into another (usually `main`).

### Example:
- You finished the login page on the branch `feature-login`.
- You merge it into `main`.
- All the new code is added to the main branch as if it was developed there from the start.

### Important Notes:
- If changes conflict in the same part of the code → **conflict** occurs.
- Git will ask you to resolve conflicts manually before completing the merge.

---

## 3. Branching vs Merging

| Operation     | Purpose                                | Simple Example |
|---------------|----------------------------------------|----------------|
| **Branching** | Create a new path for development without affecting the main branch | `feature-login` branch to develop login page |
| **Merging**   | Combine changes from one branch into another | Merge `feature-login` into `main` after finishing |

---

**Tips:**
- Use branches for every new feature or bug fix.
- Merge changes regularly to avoid large conflicts.
