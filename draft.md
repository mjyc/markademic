# Introduction

Wouldn't it be great if you can write academic papers using markdown instead of latex?
I present markademic, a pipeline for creating an academic paper-style pdf from a markdown file!

# Approach

1. Convert markdown to tex using [remark-latex](https://github.com/Paperist/remark-latex)
2. Convert tex to pdf using [pdflatex](https://www.tug.org/applications/pdftex/)
3. Update tex and pdf on-the-fly using [npm-watch](https://www.npmjs.com/package/npm-watch)

# Conclusion

Try writing your next paper with markademic!
