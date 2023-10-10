# resume
The source code for my resume. 
Test

## Installation
My default resume requires the following fonts:
- Sans Serif
    - Arial
    - Helvetica Now as fallback font #1
    - [IBM Plex Sans](https://fonts.google.com/specimen/IBM+Plex+Sans) as fallback font #2 
- Monospace
    - [Cascadia Code](https://github.com/microsoft/cascadia-code/releases)
    
If you're forking your own version of this, you can change these to whichever fonts you want by modifying their respective variables in `src/style.scss`.

## Generating PDF
To generate a PDF version of the resume, run `yarn dev`, go to http://localhost:1234, and run your browser's print command (usually done by pressing Ctrl+P). Then, select "Save as PDF".
