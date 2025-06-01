# CursorRules 

[Cursor AI rules](https://docs.cursor.com/context/rules) let you define project-specific patterns, workflows, and preferences to guide how the editor writes and edits code. This helps the AI generate results that match your project and how you like to work.


In this repo, you’ll find rules I use across my own projects, along with a curated list of resources to help you discover or create rules that fit your workflow.


## 📁 How It Works

- Rules are written in .mdc files — Markdown with a frontmatter block.
- Each file includes plain-language instructions and optional metadata like file patterns (globs) or example references.
- You can place a `.cursor/rules` folder at the project root, or create scoped rules inside feature folders.
 
## ⚙️ Setting Up Project Rules

- Create the `.cursor/rules` directory
at the root of your repo. Cursor looks here automatically.

- Write one rule file per topic (e.g., api-guidelines.mdc, frontend-rules.mdc). Keep each focused and readable.

- Scope rules when needed
For monorepos or modular projects, add `.cursor/rules` folders to subdirectories. Cursor will apply those rules only when relevant files are involved.

## 📚 Resources

- [cursor directory](https://cursor.directory/)
- [awesome cursor rules](https://github.com/PatrickJS/awesome-cursorrules?tab=readme-ov-file#utilities)
