# Francesco Sannicola Resume

This repository contains a LaTeX-based resume template built with the [moderncv](https://www.ctan.org/pkg/moderncv) class. The template is customized for a professional resume/CV and includes several modifications to personalize the layout and design.

## Overview

The LaTeX source code in this repository:

- **Defines Custom Colors:** Uses a custom dark blue color for a consistent, professional look.
- **Applies a Custom Layout:** Adopts the "classic" moderncv style with right-aligned details and modifies header spacing and photo placement.
- **Uses Various Packages:** Includes packages such as `geometry`, `babel`, `gensymb`, `footmisc`, `xpatch`, and `lmodern` for enhanced typography and layout control.
- **Redefines Commands:**
  - The `\cventry` command is redefined for more flexibility in presenting work experiences.
  - Custom commands like `\mycvitem` and `\cvtag` are used to format technologies and skills neatly within boxes.
- **Includes Personal Data:** Contains sample personal data such as name, contact details, social media links (LinkedIn, GitHub), and a photo placeholder.
- **Showcases Professional Experience, Education, and Certifications:** The document outlines work history, academic background, and additional certifications using structured sections.

If you want to use this template, follow the prerequisites and customization instructions to tailor it to your needs.

## Prerequisites

Before compiling the template, ensure you have the following installed:

- **TeX Distribution:** A modern TeX distribution (e.g., [TeX Live](https://www.tug.org/texlive/) or [MiKTeX](https://miktex.org/)).
- **ModernCV Package:** The `moderncv` package must be available. It is usually included in most distributions.
- **Required Packages:** Make sure the following packages are installed:
  - `inputenc`
  - `geometry`
  - `babel`
  - `gensymb`
  - `footmisc`
  - `xpatch`
  - `lmodern`
  - Additionally, `tcolorbox` is used for custom technology tags.

## Compilation

To compile the resume, follow these steps:

1. **Download the Repository:** Clone or download the repository to your local machine.
2. **Compile with LaTeX:** Use your preferred LaTeX editor or compile via the command line. For example, run:
   ```bash
   pdflatex resume.tex
   ```
   Run the command twice to ensure all references are updated.

## Customization

Feel free to modify the following aspects of the template:

- **Personal Information:** Update your name, contact details, social media links, and photo path.
- **Content Sections:** Adjust the sections (Working Experience, Education, Certifications, etc.) according to your needs.
- **Design Elements:** Change colors, fonts, and layout by modifying the color definitions and command redefinitions at the beginning of the document.
- **Commands:**
  - **`\cventry`:** Redefined for a two-column layout with customizable spacing.
  - **`\mycvitem`:** Used to add bullet-point items with controlled spacing.
  - **`\cvtag`:** Creates styled tags for technologies and skills.

## Directory Structure

A suggested directory structure for the project might be:

```
.
├── resume.tex         % Main LaTeX file
├── README.md          % This file
├── images/            % (Optional) Folder for images (e.g., profile photo)
└── bibliography/      % (Optional) Folder for bibliographic files if needed
```

## Contributing

Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.

## Contact

For any inquiries or feedback, please reach out via:

- **Email:** [francescosannicola1997@gmail.com](mailto:francescosannicola1997@gmail.com)
- **LinkedIn:** [francesco-sannicola](https://www.linkedin.com/in/francesco-sannicola)
- **GitHub:** [francesco-s](https://github.com/francesco-s)
