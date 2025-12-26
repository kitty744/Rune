# Rune Language

![Rune Logo](../../assets/logo/runeL.png)

Rune is a modern interpreted programming language inspired by **Go** and **Python**.  
It combines Go’s clear syntax and performance mindset with Python’s readability and ease of use.

---

## Key Features

- **Curly-brace syntax** `{}` with optional semicolons `;`
- **Variables** declared with `let`, e.g., `let x = 10`
- **Functions** defined with `fn`, e.g., `fn add(a, b) { return a + b }`
- **REPL-first development**, allowing you to interactively test code
- **RUN command** to execute scripts with `fn main()` as the entry point
- **Incremental feature growth**, making the language easy to expand safely

---

## Example Syntax

### Variable Declaration
\`\`\`bash
let x = 42
let name = "Rune"
\`\`\`

### Function Definition
\`\`\`rune
fn add(a, b) {
    return a + b
}
\`\`\`

### Conditional Statement
\`\`\`rune
fn main() {
    let score = 75
    if score >= 60 {
        print("Passed")
    } else {
        print("Failed")
    }
}
\`\`\`

---

## Language Philosophy

Rune is designed to be:

- **Readable**: Clear syntax inspired by Go and Python  
- **Safe**: Minimal surprises, consistent behavior  
- **Incrementally Extendable**: Append-only growth, each feature adds functionality without breaking existing code  
- **Tool-Friendly**: Easily integrated with REPL, scripts, and VS Code extensions  

---

## Getting Started

See [SETUP.md](./SETUP.md) for installation instructions and environment setup.

---

## Contribution Guidelines

- Follow **append-only development rules**: never remove or rewrite existing files  
- Add new features incrementally, one at a time  
- Maintain compatibility with existing examples and REPL behavior
