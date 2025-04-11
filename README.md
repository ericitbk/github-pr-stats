# GitHub PR Stats

A tool to analyze and visualize GitHub Pull Request statistics.

## Features

- Track PR review times and throughput
- Analyze team performance metrics
- Generate insightful visualizations
- Export data for further analysis

## Installation

```bash
npm install
```

## Usage

```bash
# Compile TypeScript to JavaScript
npx tsc main.ts

# Run the compiled JavaScript file
node main.js
```

The analysis typically takes 2-5 minutes to complete depending on repository size and GitHub API rate limits.

## Configuration

Create a `.env` file with your GitHub token:

GITHUB_TOKEN=your_personal_access_token

In your code, configure the following parameters:

```typescript
// Date range for the statistics
const startDate = "2024-01-01T00:00:00Z"; // start date range ISO 8601 format
const endDate = "2024-01-01T00:00:00Z"; // end date range ISO 8601 format

// GitHub owner (organization or individual username)
const owner = "your-organization-or-username";

// Array of repositories to analyze
const repositories = ["repo1", "repo2", "repo3"];
```

## License

MIT


