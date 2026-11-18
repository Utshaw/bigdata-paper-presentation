# Phoenix Rebirth — class presentation

main.tex contains 14 presentation slides paced for about 10 minutes and 25 seconds, followed by 3 backup/reference slides. Speaker notes include timing and a speaking guide.

## Build
Run twice:

    pdflatex -interaction=nonstopmode -halt-on-error main.tex
    pdflatex -interaction=nonstopmode -halt-on-error main.tex

Or upload main.tex to Overleaf and select pdfLaTeX. No external images or bibliography files are required. Packages: beamer, fontenc, lmodern, booktabs, tikz.

To show the speaking guide, change `hide notes` to `show notes` in main.tex and rebuild. Keep hide notes for the class slides.

## Timing
1. Title — 0:25
2. Problem — 0:45
3. MapReduce — 0:50
4. NUMA — 0:50
5. Scheduling — 0:50
6. Sorted keys and hash buckets — 0:40
7. Value-array growth — 0:25
8. Reduce accesses across chips — 0:25
9. OS interactions — 0:55
10. Evaluation — 0:40
11. Results — 1:00
12. Remaining bottlenecks — 1:00
13. Critical assessment — 0:55
14. Takeaways — 0:45
Total: 10:25; questions additional.

## Source and status
Based on the supplied Phoenix Rebirth paper by Yoo, Romano, and Kozyrakis (2009), pp. 198–207. Numerical claims carry section/table/figure references in the slides. Schematics and word-count example are explanatory illustrations.

Intended repository: git@github.com:Utshaw/bigdata-paper-presentation.git
GitHub could not be reached from the creation environment, so no repository contents were inspected or modified and nothing was pushed. Copy these files into the repository after cloning it.

Compilation was attempted but the local MiKTeX installation could not initialize because Windows denied registry/configuration access. The PDF and rendered layout have therefore not been verified.
