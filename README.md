# You Don't Know JS (book series)

Fork from https://github.com/getify/You-Dont-Know-JS

# Pandoc: Export Markdown to PDF

```bash
pandoc -s ch1.md ch2.md ch3.md -o UpAndGoing.pdf

pandoc -s ch1.md ch2.md ch3.md ch4.md ch5.md -o ScopeAndClosures.pdf

pandoc -s ch1.md ch2.md ch3.md ch4.md ch5.md ch6.md -o ThisAndObjectPrototypes.pdf

pandoc -s ch1.md ch2.md ch3.md ch4.md ch5.md -o TypesAndGrammar.pdf --pdf-engine=xelatex

pandoc -s ch1.md ch2.md ch3.md ch4.md ch5.md ch6.md -o AsyncAndPerformance.pdf

pandoc -s ch1.md ch2.md ch3.md ch4.md ch5.md ch6.md ch7.md ch8.md -o Es6AndBeyond.pdf --pdf-engine=xelatex
```

# Pandoc: Export Markdown to ePub

```bash
pandoc -s ch1.md ch2.md ch3.md -o UpAndGoing.epub --metadata title="Up And Going"
```