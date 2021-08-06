# CV

A repository for managing Kresimir Vukic's resume.

Usage:

 - Download MiKTeX from https://miktex.org/download
 - Download Perl from https://strawberryperl.com/ (MikTeX doesn't recognize ActiveState Perl)
 - Build with:
`
latexmk -synctex=1 -interaction=nonstopmode -file-line-error -lualatex {PATH_TO_REPO}/cv/kvukic-resume
`
