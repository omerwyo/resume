# Resume
my resume in tex

## Build using Docker

#### Build Image
```sh
docker build -t latex .
```

#### Compile to PDF
```sh
docker run --rm -i -v "$PWD":/data latex pdflatex omer_resume.tex
```

## Credit

[Template by sb2nov](https://github.com/sb2nov/resume)