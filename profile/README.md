# Neurapath

Neurapath is a web-based learning platform designed for evidence-based effective studying. It implements proven methods such as spaced repetition (SM-2), interleaved practice, and incremental reading to optimize learning outcomes.

## Features

- **Spaced Repetition**: Implements the SM-2 algorithm for optimal review scheduling
- **Cloze Deletions**: Create flashcards by hiding parts of text
- **Image Occlusions**: Create flashcards from images by hiding parts of them
- **Incremental Reading**: Process large texts by extracting key information
- **Similar Content**: Automatically fetch related information from Oxford and Wikipedia APIs
- **Customizable Interface**: Dark mode, zen mode, and adjustable layouts
- **Keyboard Shortcuts**: Fully customizable keyboard shortcuts for efficient workflow
- **Data Export/Import**: Save and restore your learning database
- **Hierarchical Organization**: Folder-based structure for organizing learning materials

## Getting Started

### Prerequisites

- [Bun](https://bun.sh/) (package manager and runtime)
- Node.js (v18 or higher)

### Usage

1. **Creating an Account**
   - Visit the login page
   - Enter a username and password
   - The system will automatically create an account if it doesn't exist

2. **Creating Learning Items**
   - **Cloze Deletions**: Select text and press `Ctrl+C` (default)
   - **Text Extracts**: Select text and press `Ctrl+X` (default)
   - **Image Occlusions**: 
     1. Drag and drop an image into the main window
     2. Draw rectangles over areas to hide
     3. Press `Ctrl+Z` (default) to create the occlusion

3. **Learning Mode**
   - Click the "Engage!" button in the left sidebar
   - Review items using the spacebar to reveal answers
   - Rate your recall with `Ctrl+1` (very hard) to `Ctrl+5` (very easy)

4. **Organizing Content**
   - Right-click in the left sidebar to create folders
   - Drag and drop items to reorganize
   - Right-click items to rename or delete them


### License

This project is licensed under the Apache-2.0 license.

### Contact

For support, feature requests, or general questions:

- Discord: [Join our channel](https://discord.gg/2xkMPmcGZh)
- Report bugs in the bugs channel on Discord

### Acknowledgments

- Built with [SvelteKit](https://kit.svelte.dev/)
- Uses [Tailwind CSS](https://tailwindcss.com/) for styling
- Implements [Quill.js](https://quilljs.com/) for rich text editing
- Leverages [pdfjs-dist](https://mozilla.github.io/pdf.js/) for PDF processing
- Inspired by evidence-based learning research
