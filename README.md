# Latex Beamer Theme for LTDS
This is a beamer theme created to match the LTDS powerpoint scheme, edited by
the communication team.
> This theme is fully compliant with :  
- the powerpoint template
- the logo of the lab
- the colors of the graphical charter.

## Usage
All 4 __.sty__ latex style files are required in the __.tex__ file folder to successfully
compile.

The style is composed by 5 files :
- [R] __beamercolorthemeltds__ : color theme
- [N] __beamerfontthemeltds__ : font theme
- [R] __beamerinnerthemeltds__ : inner frame content theme
- [R] __beamerouterthemeltds__ : outer frame content theme
- [R] __beamerthemeltds__ : main file theme

> Legend :
- [R] = file requrired
- [N] = file not required

### Theme
The theme has an option :
* `debug` option : title page box visualization

---

All the presentation data are supported :
* title
* subtitle
* author (and institute)
* date

An additional data is supported : `\issue{subject}{type}`

---
In the main __.tex__ file, the minimum requirement are :
```
\documentclass{beamer}
\usetheme{ltds}

% Main text input
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}

\begin{document}
\end{document}
```
