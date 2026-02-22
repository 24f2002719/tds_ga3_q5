# Q5: GitHub Actions Workflow with Status Badge

## Task

Add transparency to a project by displaying workflow status directly in the repository's README.

---

## Requirements

* Create a GitHub Actions workflow in the repository
* Ensure the workflow runs successfully (green checkmark)
* Add a status badge to the README.md file

---

## Approach

### 1. Identify Target Repository
Use the repository containing the scheduled GitHub action: `q5`

### 2. Configure Action
Ensure the action has a `.yml` file in the `.github/workflows/` directory.

### 3. Generate Badge
Use the GitHub UI to generate the markdown for the status badge, or manually construct the URL.

### 4. Embed Badge
Insert the generated markdown into the README.

---

## Execution

### Step 1: Status Badge Markdown

**Generated Badge:**

![CI](https://github.com/24f2002719/tds_ga3_q5/actions/workflows/daily-commit.yml/badge.svg)

```markdown
![CI](https://github.com/24f2002719/tds_ga3_q5/actions/workflows/daily-commit.yml/badge.svg)
```

### Step 2: Verification
Ensure the badge image renders correctly and displays a "passing" or successful status from the latest workflow run.

---

## Submission

**Your Answer:**
```
https://github.com/24f2002719/tds_ga3_q5
```

Submit the URL of the repository containing the working action and the status badge.