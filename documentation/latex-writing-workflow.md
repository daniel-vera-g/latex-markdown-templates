---
title: Latex writing workflow
authors: Daniel Vera Gilliard
left-header: Latex writing
right-header: \today
lang: en-GB
---

# Latex writing work flow

## Writing notes

* Automate every repetitive keystroke using vim `snippets`(In vim use UltiSnips)
* Create course specific snippets and load them on your `.vimrc` though a simlink: `set rtp+=~/current_course`
* Use vim `YouCompleteMe` to see the context of the snippets so they don't collide with the usual text. Also give them a context to for example only execute on an mathematical context(Latex math mode)
* Use a key binding to automatically correct spelling mistakes without interrupting the flow


Syntax:

```
snippet keyword "description" option
content
endsnippet
```

### Snippets

1. Use dynamic snippets with backticks: `...`
2. Use Python code: `!p...`
3. Use options like `b` for expanding at the end of the line or `A` to auto expand
4. Use variables for custom content with: `$1, $2, ...` and `$0` for the last one
5. Use RegEx to trigger snippets(Use python code)
6. Use `${VISUAL}` to select text in visual mode and apply snippet

### Math specific

1. Use `Sympy` and `Mathematica` to evaluate mathematical expressions

## Compiling notes

## Seeing notes

## Searching in notes

## Drawing figures

> Use Inkscape to draw figures

## TODO

* Every time one insert mode, the document gets compiled in the background.
* Inkscape work flow: <https://www.quora.com/Can-people-actually-keep-up-with-note-taking-in-Mathematics-lectures-with-LaTeX/answer/Gilles-Castel-1/comment/42822941>

## Resources

* <https://castel.dev/post/lecture-notes-1/>
* <https://github.com/lervag/vimtex>
* <https://github.com/SirVer/ultisnips>
* <https://www.quora.com/Can-people-actually-keep-up-with-note-taking-in-Mathematics-lectures-with-LaTeX/answer/Gilles-Castel-1#<Paste>
* <https://www.quora.com/Can-people-actually-keep-up-with-note-taking-in-Mathematics-lectures-with-LaTeX>
* Snippets: <https://gist.github.com/gillescastel/8da990dbc83c1c86f8ca048bc83624f0>
* <https://www.youtube.com/watch?v=10wGMzYgnqM>
* Good Ultisnips tutorial: <https://yufanlu.net/2016/10/30/ultisnips/>
* <https://codefor.life/ultisnips/>
* <https://gist.githubusercontent.com/gillescastel/8da990dbc83c1c86f8ca048bc83624f0/raw/442ae72c3c92295bf9afc6d038ed76d79e655b7a/Ultisnip%2520snippets>
