# LaTeX Resume + Template

This repository contains a LaTeX resume template that is clean, professional, and highly customizable. The template is designed to be easily readable by both humans and applicant tracking systems (ATS). 

## Preview

![Resume Preview](https://media.discordapp.net/attachments/1103891059341275226/1281999724123000884/image.png?ex=66ddc2c8&is=66dc7148&hm=69e0e19853e6d487644e553ce26b9e33816b31ebb61943d34c9c7d7793d97bcc&=&format=webp&quality=lossless&width=469&height=607)  

## Features

- **Clean Design:** The template uses a minimalistic design with a focus on readability and a clear structure.
- **ATS-Friendly:** The use of standard LaTeX commands ensures that the resume can be easily parsed by ATS software.
- **Highly Customizable:** The template allows easy customization of sections, fonts, colors, and formatting.
- **Multicolumn Layout:** Sections such as "Relevant Courses" are neatly organized into multiple columns for a compact and organized look.
- **Technical Skills Section:** A dedicated section to highlight your programming and verbal languages, along with developer tools and frameworks.

## Prerequisites

Make sure you have a LaTeX distribution installed on your system. For instance:

- [TeX Live](https://www.tug.org/texlive/) (cross-platform)
- [MikTeX](https://miktex.org/) (Windows)
- [MacTeX](http://www.tug.org/mactex/) (MacOS)

You'll also need a text editor. Here are some popular options:

- [TeXShop](http://pages.uoregon.edu/koch/texshop/) (MacOS)
- [TeXworks](https://www.tug.org/texworks/) (Windows, Linux)
- [Overleaf](https://www.overleaf.com/) (Online LaTeX editor)

## Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/v5run/resumeTemplate.git
   cd resumeTemplate/
   
2. **Edit the Template:**
   Open the resume.tex file in your preferred LaTeX editor and modify it according to your needs. Sections are organized in the following order:

   - Heading: Includes your name and contact information (phone, email, LinkedIn, GitHub, and personal website).
   - Education: Add your education history, including degree, university, and expected graduation date.
   - Relevant Courses: List courses that are particularly relevant to the position you're applying for.
   - Projects: Highlight your key projects with technologies used and a brief description.
   - Work Experience: Include your professional experience with details on your role and achievements.
   - Technical Skills: Mention your programming languages, tools, frameworks, and verbal languages.
   
   To customize these sections:

   - **Edit the Content**: Under each section, the content is organized in \resumeItem or \resumeSubheading commands. Modify these commands to include your own details. Replace placeholders like 'Varun Pathak' with your own information.
   - Customize Appearance:

      - To change colors, modify the \usepackage[usenames,dvipsnames]{color} section.
      - To adjust fonts or sizes, you can modify the \titleformat and \renewcommand commands.
      - To change the layout, edit the \geometry package or the column settings in the multicol environment.

3. **Compile the Resume:**

   - Compile the LaTeX file (main.tex) using your LaTeX distribution.
   - This will generate the PDF output (resume.pdf) with your updated resume.

4. **View the PDF:**

   - Open the generated resume.pdf file to view your resume. Review the document to ensure that everything is formatted correctly and that all the information is accurate.
   
