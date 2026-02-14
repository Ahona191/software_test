# GitHub CI Assignment Demo

## What this project shows
- GitHub Actions running tests
- One test PASS
- One test FAIL (for demo)
- Test summary visible in Actions tab

## How to use

1. Upload this project to GitHub
2. Push to main branch
3. Go to Actions tab
4. You will see:
   - One test passed
   - One test failed

## Branch Protection Setup

Go to:
Settings → Branches → Add branch protection rule

Enable:
- Require a pull request before merging
- Require status checks to pass before merging
- Select the CI job as required check

Then direct push to main will be blocked.