# resume
 **Source Repository: https://github.com/jsonresume/resume-cli**

To Validate resume format 
```
resume test
```

To install any theme (say kendall-fix)
```
npm install -g jsonresume-theme-kendall-fix
```
 
To view resume as html in browser (say kendall-fix)
```
resume serve -t kendall-fix
```
 
To export in html (pdf export is not good)
 ```
 resume export --format html --theme kendall-fix resume.html
 ```
 
 To convert html to pdf, visit  https://www.sejda.com/html-to-pdf (other websites' conversion isn't good)
 
 To crop the pdf (remove Volunteer section at the bottom), visit https://www.sejda.com/crop-pdf - volunteer section is not properly displayed for some reason. This is why one can find both resume.pdf and cropped_resume.pdf in the repo.
