---
sidebar_position: 1
---

# Introduction

Quill is an **AI agent specialized in Git**. It inspects your staged changes and generates **concise, conventional and contextual** commit messages, boosting your project’s documentation and traceability.

## Getting Started
To start using Quill, follow these steps:
1. Clone the Quill repository:
```bash
git clone https://github.com/davibs22/quill.git
```
2. Install dependencies:
```bash
go mod tidy
```
3. Build Quill:
```bash
go build -o quill
```
4. Run quill:
```bash
./quill
```

## Usage
To use Quill, follow these steps:
1. Stage your changes:
```bash
git add .
```
2. Run Quill:
```bash
./quill
```
3. Output:
```bash
feat(): add new feature
```
4. Commit your changes:
```bash
git commit -m "feat(): add new feature"
```
