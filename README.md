Here's a little experiment to do publishing from emacs. Open resume.org and ~fabricate~ edit away. Run `(org-babel-tangle)` to get the css then `(org-html-export-to-html)` and open it up in a web browser. From there I play with the scaling and export to PDF. I'm a believer in the one-page resume so it doesn't need the capabilities of e.g. LaTeX to do typesetting.