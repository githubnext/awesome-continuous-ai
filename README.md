# Awesome Continuous AI

**[Continuous AI](https://githubnext.com/projects/continuous-ai/) is any use of automated AI to support software collaboration on any platform.** The term aligns with the established concept of Continuous Integration/Continuous Deployment (CI/CD). Just as CI/CD transformed software development by automating integration and deployment, Continuous AI covers the ways in which AI can be used to automate and enhance collaboration workflows.

> NOTE: this list is provided in the spirit of other "awesome" lists common on the Web. Inclusion of a link does not in any way mean endorsement or recommendation. Some of the links may be out-of-date, some may be demonstrators, some may be commercial products. All should be checked carefully for appropriateness, privacy, security, responsible AI and other key operational properties.

## Categories

### Continuous Triage

* [Ultralytics Actions](https://github.com/ultralytics/actions) comprehensive linting and formatting suite including AI labeling and summarization
* [Automattic Isue Triage](https://github.com/Automattic/jetpack/tree/f1b24e51a215eb85e17de7844794d0cb512bfc42/projects/github-actions/repo-gardening) - automatic issue labeling
* [Dosu Automated Issue Triage](https://dosu.dev/blog/automating-github-issue-triage) - automating GitHub issue triage
* [GenAI Issue Labeller](https://github.com/pelikhan/action-genai-issue-labeller) - a sample of using GenAIScript for automated labelling of issues
* [Detect Duplicate Issues, reusable action](https://github.com/pelikhan/action-genai-issue-dedup) - an example of a reusable action using using GitHub Actions, GitHub Models and GenAISCript for issue duplicate detection
* [Detect Duplicate Issues, micro sample](https://github.com/home-assistant/core/blob/dev/.github/workflows/detect-duplicate-issues.yml) - an example of using GitHub Actions+Models for adhoc duplicate detection
* [Detect Non-English Issues](https://github.com/home-assistant/core/blob/dev/.github/workflows/detect-non-english-issues.yml) - an example of using GitHub Actions+Models to detect issues in an unexpected language
* [Continuous AI Resolver](https://github.com/ashleywolf/continuous-ai-resolver) - Automatically resolve stale or already fixed GitHub issues and PRs powered by AI
* [GitHub Test Reporter](https://github.com/ctrf-io/github-test-reporter) - "Generate, publish and alert your team with detailed test results, including summaries, in-depth reports, failed test analyses, flaky test detection and AI analyses directly within your GitHub Actions CI/CD workflow and Pull Requests."
* [GitHub Action Investigator](https://microsoft.github.io/genaiscript/samples/gai/) - automatically analyze a GitHub Action Workflow Job logs and attempts to determine the root cause of the issue

### Continuous Documentation

* [Penify.dev](https://www.penify.dev/) - "Penify instantly generates and updates comprehensive documentation for your repository"
* [Dosu](https://dosu.dev/) - "You build. Dosu documents. Dosu turns your codebase into a living knowledge base that every team member can understand—from engineering to operations"
* [DeepWiki](https://deepwiki.com/) - "Automatically generates architecture diagrams, documentation, and links to source code to help you understand unfamiliar codebases quickly"
* [Continuous Architectural Decision Records (cADR)](https://github.com/YotpoLtd/cADR/) - AI-powered ADR generation - Automatically capture and document architectural decisions as you code
* [AI Translate Action](https://github.com/FidelusAleksander/ai-translate-action) - A GitHub Action that provides AI-powered text and file translation directly in your workflows.
* [Translate Docs](https://github.com/TanStack-dev/translate-docs-action) - Translate your documentation into multiple languages automatically
* [autodoc](https://github.com/context-labs/autodoc) - An experimental toolkit for auto-generating codebase documentation for git repositories
* [docAider](https://github.com/ucl-docaider/docAider) - Automate the process of generating and reviewing code documentation for your repository through a multi-agent approach
* [ReadmeAI](https://github.com/eli64s/readme-ai) - Automatically generates README files using a robust repository processing engine and LLMs
* [action-continuous-translation](https://github.com/pelikhan/action-continuous-translation) - custom GitHub Action to maintain a translation of markdown files

### Continuous Code Review

* [GitHub Copilot Code Review](https://docs.github.com/en/copilot/using-github-copilot/code-review/using-copilot-code-review) - Learn how to request a code review from GitHub Copilot.
* [CodeRabbit](https://www.coderabbit.ai/) - "Supercharge your team to ship faster with the most advanced AI code reviews"
* [Gemini Code Assist](https://developers.google.com/gemini-code-assist/docs/review-github-code) - "Review GitHub code using Gemini Code Assist"
* [Shippie](https://github.com/mattzcarey/shippie) - Code review, secrets detection, bug fixes and more. TypeScript + Bun.
* [Aetherr Agency DeepDive](https://github.com/Aetherr-Agency/DeepDive/) - "Analyze the quality of your test files, providing insightful feedback and suggestions for improvement."
- [Amazon Q Developer (/review)](https://aws.amazon.com/q/developer/build/) - "review your codebase for security vulnerabilities and code quality issues"

### Continuous Code Commenting

* [GenAI Code Commentor](https://github.com/pelikhan/action-genai-commentor/) - a sample of using GenAIScript for automated commenting of code using GitHub Actions and GitHub Models

### Continuous Code Optimization

* [CatchMetrics](https://landing.catchmetrics.io/mcp) - A RUM web performance data tool that connects real world web performance data to AI agents via MCP
* [CodeFlash](https://www.codeflash.ai/) ([GitHub App](https://github.com/marketplace/codeflash-ai)) - "CodeFlash finds the fastest version of your Python code through benchmarking with AI-powered optimization, verified for correctness every time"

### Continuous Test Improvement

* [SoftwareTesting AI](https://softwaretesting.ai/) - A code quality platform that identifies coverage gaps and suggests how to resolve them
* [DiffBlue](https://www.diffblue.com/ci-pipeline/) - Automate continuous unit testing at scale in CI

### Continuous Research

* [Open Journals: Find Similar Papers](https://github.com/openjournals/find-similar-papers) - Find similar journal articles using OpenAI embeddings

### Continuous Team Communication

* [Summarize issues with GitHub Actions](https://docs.github.com/en/github-models/github-models-at-scale/use-models-at-scale#example-use-github-models-with-github-actions-to-summarize-issues) - Use GitHub Models with GitHub Actions to summarize issues when they're closed
* [GenAI Pull Request Descriptor](https://github.com/pelikhan/action-genai-pull-request-descriptor/) - a sample GenAIScript action that updates a pull request description.
* [Video Asset Analyzer](https://github.com/pelikhan/action-genai-video-issue-analyzer) - a sample GenAIScript action that analyzes videos attached as assets to issues.
* [AI-Powered Release Social Media Posts](https://github.com/humanwhocodes/social-changelog) - automatically generate and post social media announcements for releases using OpenAI across multiple platforms (Twitter, Bluesky, Mastodon, LinkedIn) (see [workflow](https://github.com/humanwhocodes/mentoss/blob/76360205a545d22575bd11758f53cf11b6d95177/.github/workflows/release-please.yml#L57-L75))
* [Zine Meets Pull Requests](https://microsoft.github.io/genaiscript/blog/zine-prs/#zines) - the availability of new image generators like OpenAI gpt-image-1 opens the door to endless new ways to visualize and annotate software artifacts.

### Continuous Moderation

* [AI Community Moderator](https://github.com/benbalter/ai-community-moderator) - Analyze issues, pull requests, discussions, and comments for adherence to contribution guidelines and codes of conduct

### Continuous AI Engineering

* [Continuous alignment testing](https://github.com/thisisartium/continuous-alignment-testing) - A framework for implementing Continuous Alignment Testing (CAT) for LLM-based applications.
* [Using GitHub Models for continuous evals](https://docs.github.com/en/github-models/use-github-models/evaluating-ai-models) - Test and compare AI model outputs using evaluators and scoring metrics in GitHub Models
* [Continuous Claude](https://github.com/AnandChowdhary/continuous-claude): Automated workflow that orchestrates Claude Code in a continuous loop, creating PRs to incrementally tackle larger tasks 

### Continuous Security

* We have not yet included automated AI-powered security scanning and security code analysis in this list

## Platforms

On GitHub today, Continuous AI is supported in initial form by the combination of GitHub Actions and GitHub Models. The synergy between these features is at the core of Continuous AI at GitHub.

* [GitHub Actions](https://docs.github.com/en/actions)
* [GitHub Models](https://docs.github.com/en/github-models/)

## Agentic Frameworks

General-purpose software agents can be used as the basis for automated workflows:

* [Copilot Coding Agent](https://docs.github.com/copilot/using-github-copilot/coding-agent) - "Find out how Copilot can work on GitHub issues and raise pull requests for your to review"
* [Claude Code GitHub Actions](https://docs.anthropic.com/en/docs/claude-code/github-actions) - "Integrate Claude Code into your development workflow with GitHub Actions"
* [Amazon Q Developer](https://aws.amazon.com/q/developer/) - "An AI Code assistant that provides support across the software development lifecycle from coding, testing, and deploying to troubleshooting and modernizing applications", with GitHub integration
* [Continue](https://github.com/continuedev/continue) - Framework for building and running custom agents across your IDE, terminal, and CI
* [GitHub Agentic Workflows](https://github.com/githubnext/gh-aw) - Framework for creating AI-powered agentic workflows on GitHub

## Programming Frameworks

Any library that can invoke an LLM inference service could be used to create a workflow. Some of them have builtin support for GitHub Actions and/or GitHub Models.

###  YAML (GitHub Actions Yaml)

* [actions/ai-inference](https://github.com/actions/ai-inference): a standard GitHub Action for invoking LLMs direct from YAML
* [FidelusAleksander/prompt-action](https://github.com/FidelusAleksander/prompt-action): A GitHub Action that lets you Prompt AI directly in your workflows with support for structured outputs and prompt templating.


### Shell Scripting

* [llm](https://llm.datasette.io/) and [llm-github-models](https://github.com/tonybaloney/llm-github-models) to run LLMs in shell scripting
* [ast-grep](https://ast-grep.github.io/): A tool for analyzing and transforming code using abstract syntax trees (ASTs)

### Python Scripting

* [llm Python API](https://llm.datasette.io/en/stable/python-api.html) to run LLMs in Python scripts

### JavaScript/TypeScript

* [GenAIScript](https://microsoft.github.io/genaiscript/), a scripting language for GitHub Actions that simplifies the use of AI models and tools in workflows

### Markdown

* [shippie](https://github.com/mattzcarey/shippie), uses Markdown based rules to define LLM-powered code reviews
* [AWD CLI - Agentic Workflow Definitions](https://github.com/danielmeppiel/awd-cli), build, package, share, and run agentic prompts and workflows across any LLM runtime
* [action-awd-cli](https://github.com/danielmeppiel/action-awd-cli), GitHub Action wrapping AWD CLI to run agentic prompts packaged with AWD

## Utilities

* [Add Reaction](https://github.com/pelikhan/action-add-reaction/) - Adds `eyes` reaction to an issue, pull request, ... as soon as the action starts. Fun feedback to notify the user that something started.

## Similar Lists

* [Awesome Code AI](https://github.com/sourcegraph/awesome-code-ai)
* [Awesome-Ai-Analytics](https://github.com/Snowboard-Software/awesome-ai-analytics)
* [Awesome-Ai-Agents](https://github.com/e2b-dev/awesome-ai-agents)
* [Awesome-Ai-Tools](https://github.com/ikaijua/Awesome-AITools)
* [Awesome Ai DevTools](https://github.com/jamesmurdza/awesome-ai-devtools)
* [AI Native Developer Tools Landscape](https://landscape.ainativedev.io/)

