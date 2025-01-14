# Regex Recipes

A web-based application for managing and applying regular expression patterns. This tool helps users store, organize, and apply commonly used regex patterns for text manipulation tasks.

## Features

- Save and manage regex patterns as reusable recipes
- Apply regex patterns with customizable flags
- Clean and modern web interface
- Pre-built recipes for common text cleaning tasks
- Real-time pattern testing and preview

## Project Structure

- `index.html` - Main application interface
- `replace-rules.json` - Storage for regex patterns and replacement rules
- `sof/` - Additional resources and utilities

## Getting Started

1. Clone the repository
2. Open `index.html` in your web browser
3. Start using the pre-built regex recipes or create your own

## Example Recipe

The application comes with some pre-built recipes, such as:

```json
{
  "name": "Clean Extra Whitespaces",
  "rules": [
    {
      "pattern": "\\s+",
      "replacement": " ",
      "flags": ""
    }
  ]
}
```

This recipe removes extra whitespace characters from text, replacing multiple spaces with a single space.

## Contributing

Feel free to contribute by adding new regex recipes or improving the existing ones. Submit a pull request with your changes. 