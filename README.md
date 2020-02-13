# latex

Full texlive distribution

## Build Docker Image for Local with Tag

```sh
$ docker build -t latex_docker . 
```

## Usage

```sh
$ docker run --rm -it -v $(pwd):/source latex_docker
```

Mount your local source folder to the container and run it inside the container.

#### Compiling a latex document

```sh
$ pdflatex my-document.tex
```

#### Compiling a xetex document

```sh
$ xelatex my-document.xtx
```
