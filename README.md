# Anki Flashcard Automation

A tool for automatically creating Anki flashcards based on AI rules using Claude Code and other AI tools.

## Overview

This project automates the generation of high-quality flashcards from learning materials, documentation, and educational content. It uses AI-powered rules and templates to create structured, well-formatted flashcard decks that can be imported into Anki or other spaced repetition systems.

## Features

- **AI-Powered Generation**: Uses Claude Code to intelligently extract key concepts and create flashcards
- **Structured Output**: Generates TSV (Tab-Separated Values) files compatible with Anki import
- **Deck Organization**: Supports hierarchical deck structures matching folder organization
- **Multiple Card Types**: Supports regular flashcards and cloze deletion cards
- **Quality Standards**: Enforces best practices for flashcard design (atomicity, clarity, context)
- **Batch Processing**: Handles large volumes of content in organized batches
- **Verification**: Uses Context7 MCP to verify facts against current documentation

## Project Structure

```
CURSOR_LEARNING/
├── .cursor/
│   └── rules/
│       └── flashcard-generation-rules/  # AI rules for flashcard generation
├── product-design/                      # Product design learning materials
├── product-requirements/               # Product requirements learning materials
└── web-dev/                            # Web development learning materials
    └── aws/
        └── s3/
            ├── old/                     # Original/outdated flashcards
            └── new/                     # AI-verified and updated flashcards
```

## How It Works

1. **Content Input**: Learning materials (markdown files, documentation, etc.)
2. **AI Processing**: Claude Code analyzes content using predefined rules
3. **Flashcard Generation**: Creates structured flashcards following best practices
4. **Verification**: Uses Context7 MCP to verify facts against current documentation
5. **Output**: Generates TSV files ready for Anki import

## Flashcard Format

Flashcards are generated in TSV format with the following structure:

- **Question**: The front side of the flashcard
- **Answer**: The back side with the correct response
- **Example**: Additional context, tips, and real-world applications
- **Deck**: Hierarchical deck path (e.g., `Web dev::Cloud Services::AWS::S3`)

## Usage

The tool is primarily used through Claude Code (Cursor AI assistant) with predefined rules located in `.cursor/rules/flashcard-generation-rules/`. These rules guide the AI to:

- Extract atomic concepts
- Create clear, unambiguous questions
- Provide valuable context in examples
- Organize cards into appropriate decks
- Verify facts against current documentation

## Technologies

- **Claude Code**: AI assistant for content analysis and flashcard generation
- **Context7 MCP**: Model Context Protocol for documentation verification
- **TypeScript**: MCP server implementation
- **Anki**: Target flashcard application

## Future Enhancements

- TypeScript MCP server for programmatic flashcard generation
- Web interface for flashcard management
- Integration with learning platforms
- Automated fact-checking and updates
- Multi-language support
