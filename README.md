Combine `source1.pdf` and `source2.pdf` into `output.pdf` all in the current directory:

```
docker container run -v $(pwd):/pdfs training/pdfcombo:0.1 pdftk /pdfs/source1.pdf /pdfs/source2.pdf cat output /pdfs/output.pdf
```
