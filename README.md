# Zach McCormick Resume

I resolved in 2018 that I would stop using Microsoft Word for my resume.
This is the culmination of that.

## Installation // Compilation Instructions

Build with [Tectonic](https://tectonic-typesetting.github.io/) (`brew install tectonic`), which runs BibTeX and the extra passes automatically:

```sh
tectonic -X compile zach_mccormick_resume.tex
```

Or with a full TeX distribution: run latex on the tex file once, then run bibtex on it, then run latex on it again.

## License
MIT license. Originally created by [Sourabh Bajaj](https://github.com/sb2nov/resume).
