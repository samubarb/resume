# My Resume

## `checkout` other branches
Currently in `master` branch you can find a general resume which isn't oriented to a specific job position. There are other versions of the resume, with relative branches named after them, for positions such as *backend* or *research*. Checkout them with 

```
$ cd resume
$ git checkout <branch-name>
```

To see all available branches simply run `$ git branch -r`.

## Rendering LaTeX to PDF
In short, use [Overleaf](https://overleaf.com). Copy and paste the content of this repo in a new Overleaf project, then generate the PDF. Be aware of various branches on this repo, so choose the one you need.

### Overleaf as a git repository
An Overleaf project has a git link and can be treated as a repository, allowing some comfortable features. For example, when you push modifications, the PDF is *automagically* rendered inside the relative project's browser page.
