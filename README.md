# X Post Summarizer 2026

This project summarizes a public figure's 2026 X posts using AI.

## Account Analyzed
- Handle: @llm_wizard

## Project Overview
This repository contains an AI-generated summary of @llm_wizard's 2026 posts on X (formerly Twitter). The project was built using a LangGraph agent that leverages GitHub MCP tools for repository operations and the X API v2 for retrieving posts.

## How It Works
- The LangGraph agent automates repository management and content updates.
- The X API v2 is used to fetch recent posts from the specified X account.
- AI processes the retrieved posts to generate summaries and metadata.

## Replicating the Process
To replicate this project for another X account, follow these steps:

1. Obtain an X API Bearer Token:
   - Sign up for a developer account at https://developer.x.com/
   - Create a project and generate a Bearer Token.

2. Set up your environment:
   - Export your Bearer Token as an environment variable:
     ```bash
     export X_BEARER_TOKEN='your_bearer_token_here'
     ```

3. Install Python dependencies:
   - This project requires the `requests` library.
   - Install it using pip:
     ```bash
     pip install requests
     ```

4. Run the search script:
   - Use the provided `x_search.py` script to fetch recent posts:
     ```bash
     python x_search.py <X_handle>
     ```
   - Replace `<X_handle>` with the desired account handle.

5. Use AI tools to generate summaries and update the repository accordingly.

---

This project demonstrates how to combine AI, GitHub automation, and the X API to analyze social media content efficiently.