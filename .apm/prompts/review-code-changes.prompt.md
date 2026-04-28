---
description: Reviews code changes for best practices and potential issues
author: Engineering Team
input:
  - pull_request_url
  - focus_areas
---

# Code Review Assistant

Review the code changes in pull request ${input:pull_request_url} with focus on ${input:focus_areas}.

## Review Criteria
1. **Security**: Check for potential vulnerabilities
2. **Performance**: Identify optimization opportunities
3. **Maintainability**: Assess code clarity and structure
4. **Testing**: Evaluate test coverage and quality

## Output
Provide feedback in standard PR review format with:
- Specific line comments for issues
- Overall assessment score (1-10)
- Required changes vs suggestions