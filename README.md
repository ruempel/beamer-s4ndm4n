# s4ndm4n Dark Theme for LaTeX `beamer`
`beamer-s4ndm4n` is a dark theme to be used with LaTeX `beamer` for your presentation slides. Since it uses `fontspec`, it requires either XeLaTeX or LuaLaTeX. Beside the title page – being very plain and using the standard metadata such as title, subtitle, author, institute and date – the frames have a footline, which is divided into five boxes with different shades of gray. They contain the author's name, the presentation's title, the date, the current page number and the total page number.

## Usage
* Copy the `sty` file and the `gfx` directory to the directory of you current LaTeX `beamer` project.
* Add `\usepackage{beamer-s4ndm4n}` to your `tex` file with document class `beamer`.
* Use `block` elements to structure your content within the frames.
* There is an example slide deck `beamer-s4ndm4n-example.tex`. Get inspired by it.

## Configuration
* Change the *background picture* in the `sty` file.
* There is an *accent color* defined, which controls all accent color shades. Change it in the `sty` file.
