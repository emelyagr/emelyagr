- 👋 Hi, I’m @emelyagr
- ✨ I’m interested in Information security and Steganography
- 🌱 I’m currently learning in Moscow Plekhanov Russian University of Economics
- 👀 (C) Emelyanov Grigory Andreevich. All rights reserved. Use (copying, collection, processing, storage, distribution, provision and other actions, and other reproduction in any form) of any materials, articles, books, courses, program codes, programs and all contained materials (and information) without full indication of the author and sources and/or permission of the author is prohibited. All works are protected by a digital watermark.
- ✨(С) Емельянов Григорий Андреевич. Все права защищены. Использование (копирование, сбор, обработка, хранение, распространение, предоставление и другие действия, и иное воспроизведение в какой бы то ни было форме) любых материалов, статей, книг, курсов, программных кодов, программ и всех содержащихся материалов (и информации) без полного указания автора и источников и/или разрешения автора запрещено. Все работы защищены ЦВЗ (цифровым водяным знаком).
<!---
emelyagr/emelyagr is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=emelyagr&theme=tokyonight&show_icons=true)](https://github.com/anuraghazra/github-readme-stats).

[![Star History Chart](https://api.star-history.com/svg?repos=emelyagr/emelyagr&type=Date)](https://www.star-history.com/#emelyagr/emelyagr&Date).

- uses: Platane/snk/svg-only@v3

  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    emelyagr: ${{ emelyagr }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9