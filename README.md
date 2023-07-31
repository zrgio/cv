# Curriculum Vitae

## Download | Descarga

[Curriculum Vitae Español](https://raw.githubusercontent.com/zrgio/cv/main/sergio_ulloa_es.pdf)

[Curriculum Vitae English](https://raw.githubusercontent.com/zrgio/cv/main/sergio_ulloa_en.pdf)

## Compiling it

Recompile on save:

```sh
latexmk input.tex -xelatex -pvc -outdir=out
```

Just compile:

```sh
latexmk input.tex -xelatex -outdir=out
```

Compile file and copy output PDF:

```sh
file=input; latexmk $file.tex -xelatex -outdir=out; cp -f out/$file.pdf .
```

## Acknowledgements

`LaTeX` template written by [Zach Scrivena's](https://github.com/zachscrivena/simple-resume-cv)

[FiraCode](https://github.com/tonsky/FiraCode) font made by [Tonsky](https://github.com/tonsky)
