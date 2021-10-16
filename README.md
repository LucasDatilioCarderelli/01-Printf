<div align="center">
	<a href="https://www.42sp.org.br/">
		<img src="https://github.com/LucasDatilioCarderelli/42Cursus/blob/master/img/42-saopaulo.png" height=200>
	</a>
</div>

<h1 align="center"> Printf </h1>

<h2 align="center">
	Project develop for <a href="https://github.com/LucasDatilioCarderelli/42Cursus"> 42Cursus </a>
</h2>

<p align="center">
  	<a href="https://www.linkedin.com/in/lucasdatiliocarderelli/">
    	<img alt="Linkedin" src="https://img.shields.io/badge/Lucas Datilio Carderelli-blue?style=flat&logo=Linkedin&logoColor=white" />
  	</a>
    <img src="https://img.shields.io/github/last-commit/LucasDatilioCarderelli/01-Printf?color=blue">
	<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/LucasDatilioCarderelli/01-Printf?color=blue" />
	<img alt="Number of lines of code" src="https://img.shields.io/tokei/lines/github/LucasDatilioCarderelli/01-Printf?color=blue" />
</p>

<div align="center">
	<a alt="get next line" href="https://github.com/LucasDatilioCarderelli/01-Printf">
		<img src="https://github.com/LucasDatilioCarderelli/42Cursus/blob/master/img/printf.png">
	</a>
</div>

## Goal
This project is pretty straightforward, you have to recode printf. You will learn what is and how to implement variadic functions. Once you validate it, you will reuse this function in your future projects.

## Description
The versatility of the printf function in C represents a great exercise in programming for
us. This project is of moderate difficulty. It will enable you to discover variadic functions
in C.
The key to a successful ft_printf is a well-structured and good extensible code.

### Objectives:
* `Unix logic`

### Skills:
* `Rigor`
* `Algorithms & AI`

### Brief
` Write a library that contains ft_printf, a function
that will mimic the real printf `

### Prototype
```c
int ft_printf(const char *, ...);
```

### External functs
```c
read(2)
malloc(3)
free(1)
write(1)
STDARG(3)
```

## A small description of the required conversion:
* `%c` print a single character.
* `%s` print a string of characters.
* `%p` The void * pointer argument is printed in hexadecimal.
* `%d` print a decimal (base 10) number.
* `%i` print an integer in base 10.
* `%u` print an unsigned decimal (base 10) number.
* `%x` print a number in hexadecimal (base 16), with lowercase.
* `%X` print a number in hexadecimal (base 16), with uppercase.
* `%%` print a percent sign.

