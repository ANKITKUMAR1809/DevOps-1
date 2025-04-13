# CI/CD with GitHub Actions

✅ Trigger on:
  - push to feature/*, dev, main
  - PR to dev or main

✅ Jobs:
- Checkout Code
- Set up Node.js
- Install Dependencies
- Run Tests

✅ Tools Used:
- actions/checkout@v3
- actions/setup-node@v3

✅ Commands:
mkdir -p .github/workflows
touch .github/workflows/main.yml
