# AIURM Protocol Examples

This folder showcases practical implementations and integrations using the **AIURM Protocol**. Our examples primarily focus on demonstrating AIURM's capabilities when integrating with:

* **Large Language Models (LLMs):** General examples demonstrating core LLM interactions.
* **Specific LLM APIs:** Integrations with services like **OpenAI API**, **Google Gemini API**, and others.
* **LLM Frameworks:** Implementations within popular frameworks such as **LangChain**.
* **Agent Orchestration:** Demonstrations of building and managing intelligent agents using the protocol.

---

## Contributing Your Examples

Community contributions are highly welcome! We believe that diverse examples will help grow the AIURM ecosystem.

### How to Structure Your Example

To keep our examples organized and easy to navigate, please add your contribution within its own dedicated subfolder inside `examples/`. We suggest organizing first by the **primary LLM API or framework** used, and then by the specific example name.

**Suggested Structure:**

`examples/<LLM_API_OR_FRAMEWORK>/<YOUR_EXAMPLE_NAME>/`

**Examples:**

* `examples/openai-api/multi-step-workflow/`
* `examples/google-gemini/data-extraction-flow/`
* `examples/langchain/custom-tool-integration/`
* `examples/python/basic-llm-agent/` (for generic Python LLM examples not tied to a specific API/framework)

### What Each Example Folder Should Contain

Every example subfolder (`<YOUR_EXAMPLE_NAME>/`) should include:

* **`README.md`**: A detailed explanation of your example's purpose, what it demonstrates, how to set it up, and how to run it. Please list any prerequisites (e.g., Python version, required libraries) and necessary environment variables.
* **Source Code**: All code files required for your example to function (e.g., `.py`, `.js`, etc.).
* **Dependency Files**: (e.g., `requirements.txt` for Python, `package.json` for Node.js), if applicable.

### Security and Best Practices

* **NEVER include real credentials, API keys, or sensitive information directly in your code.** Always demonstrate how to load these securely (e.g., from environment variables).
* Use clear placeholders (e.g., `YOUR_API_KEY`) when it's absolutely necessary to show the format of a key.
* Examples should be concise and focused on demonstrating AIURM's integration. Avoid complex functionality that isn't central to the AIURM usage.

---

## Found a Security Vulnerability?

If you discover a potential security vulnerability within any example, please follow our [Security Policy](SECURITY.md) for private reporting.
