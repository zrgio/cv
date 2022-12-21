# Curriculum Vitae

## Download | Descarga

[Curriculum Vitae Español](https://github.com/zrgio/cv/blob/main/sergio_ulloa_es.pdf)

[Curriculum Vitae English](https://github.com/zrgio/cv/blob/main/sergio_ulloa_en.pdf)

## Compiling it

Recompile on save

```sh
latexmk input.tex -xelatex -pvc -output-directory=./out; mv -f ./out/*.pdf .
```

Just recompile

```sh
latexmk input.tex -xelatex -output-directory=./out; mv -f ./out/*.pdf .
```

## Acknowledgements

`LaTeX` template written by [Zach Scrivena's](https://github.com/zachscrivena/simple-resume-cv)

[FiraCode](https://github.com/tonsky/FiraCode) font made by [Tonsky](https://github.com/tonsky)
