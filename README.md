# wtf-bf

This is a small side project written in [Brainfuck](https://brainfuck.org/) – a
minimalist, esoteric programming language made up of just eight commands. While
Brainfuck is Turing-complete, it's mostly used for puzzles, experimentation, and
brain-twisting fun rather than practical applications.

I used it here purely for the challenge and enjoyment – as a creative exercise
to output the sentence that had been a brainfuck for me for years.

## Optimisation
Purely for the challenge, I've been trying to optimise bf programs to use as few commands as possible. Original 955 -> 383

```bash
$ brew install brainfuck
$ brainfuck wtf.bf
```

[windows](https://github.com/aapzu/bf-cli)
```bash
npm i -g bf-cli
bf-cli [<PATH_TO_FILE>] [<INPUT>]
npx bf-cli [<PATH_TO_FILE>] [<INPUT>]
```
