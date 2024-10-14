# Nick's Resume

This is my resume, written using LaTeX. Currently a published pdf of
the resume is not available on this repository. To get a copy of my resume
you can either reach out to me at [npw1010@gmail.com](mailto:npw1010@gmail.com)
or by building my resume using XeLaTeX. Instructions for compiling my
resume on a MacBook are given below.

## Compilation

Prequresites for compilation include a full XeLaTex installation, the Iosevka
font, and the Helvetica font.

1. XeLaTeX installation on MacBook using Brew:

    ```sh
    brew install mactex-no-gui # install mactex, skip if already installed
    ```

2. Iosevka can be installed from their [website, located here](https://typeof.net/Iosevka/). Install *Iosevka* and *Iosevka Slab*.

3. Helvetica comes with MacOS, but can also be found online if needed.

Copy this repo (or just directly copy [main.tex](./main.tex)) to your local computer
to build the resume.

Once [main.tex](./main.tex) is on your local machine, compilation can be
accomplished by calling XeLaTeX from the command line. Adding
a output directory is optional, but makes a cleaner build folder.

**With Output Directory:**
```sh
mkdir pdf
xelatex -output-directory=pdf main.tex
```

**Without Output Directory:**
```sh
xelatex main.tex
```

Now you should have a PDF of my resume, located either at `pdf/main.pdf` or
`./main.pdf`. If you're interested in hiring me *and* you actually went through
this process I'm very interested in talking with you! Please reach out via the
contact information available on my resume.
