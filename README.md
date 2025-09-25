# wtf-bf

This is a small side project written in [Brainfuck](https://brainfuck.org/) – a
minimalist, esoteric programming language made up of just eight commands. While
Brainfuck is Turing-complete, it's mostly used for puzzles, experimentation, and
brain-twisting fun rather than practical applications.

I used it here purely for the challenge and enjoyment – as a creative exercise
to output the sentence that had been a brainfuck for me for years.

## Optimisation

Purely for the challenge, I've been trying to optimise bf programs to use as few commands as possible.  
By using 5 cells and setting them to 81 35 45 99 121, my program moves between the cells updating them and outputting them to save commands (955 -> 383).  
[Thread tracking google sheets](https://docs.google.com/spreadsheets/d/1s3TCjMd1w4ilogoOm2GPqcNs1qAnNV2JhbNGIictsCw/edit?gid=0#gid=0)  

## Usage

[macos](https://formulae.brew.sh/formula/brainfuck)
```bash
$ brew install brainfuck
$ brainfuck wtf.bf
```

[windows](https://github.com/aapzu/bf-cli)
```bash
npm i -g bf-cli
bf-cli wtf.bf

npx bf-cli wtf.bf
```
