# HSRM Internship Report

Template for internship reports in the DCSM department of RheinMain University of Applied Sciences (HSRM).  
This template provides a standardized layout and formatting base, and supports marking text sections by author.

## Features

- **Preconfigured formatting** according to known requirements of RheinMain University (including margins, line spacing, and fonts).
- **Multiple authors** with clear, visually distinct marking within the document.
- **Author legend** optionally displayed in the table of contents.
- **Covers key frontmatter elements** such as title, subtitle, author details, company and university information.
- **Placeholder logos** for both university and company, easily replaceable.

## Usage

1. **Initialize the project**  
   ```bash
   typst init @preview/hsrm-internship-report:0.0.1
   ```
2. **Edit `data.typ`**  
   - Title, subtitle  
   - Authors (name, short code, student ID, email, color)  
   - Logos (file paths and sizes)  
   - Supervisors at the university and company  
   - Fonts (`heading-font`, `text-font`)
3. **Mark author-specific content**  
   ```typst
   #author("RZ")[This is a text section written by author RZ.]
   ```
4. **Compile**  
   ```bash
   typst compile main.typ
   ```

## Files

- **`main.typ`** – Entry point, imports the template and data.
- **`data.typ`** – Contains personal information and project-specific configuration.
- **`template/template.typ`** – Defines the main layout and document structure.
- **`template/author-marker.typ`** – Implements the author marking functionality.
- **`generic-uni-logo.png`**, **`generic-company-logo.png`** – Generic placeholder logos.
- **`thumbnail.png`** – Preview image for Typst Universe.

## License

This package is licensed under the MIT License (see `LICENSE`).  
The included placeholder logos (`generic-uni-logo.png`, `generic-company-logo.png`) are generic and free to use.
