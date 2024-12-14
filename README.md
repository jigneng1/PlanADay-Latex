# CS SIT KMUTT TravelKit Thesis
CS SIT KMUTT Thesis with LaTeX

## Install Xetex

### Ubuntu
```
$ sudo apt install texlive-xetex
```

### Using TeXstudio on Mac

Download TeXstudio https://www.texstudio.org/

Download MacTex ```brew install --cask mactex```

### Windows

~~Dowload MiKTeX~~ https://miktex.org/download ❌

Or buy a Macbook https://www.apple.com/shop/buy-mac/macbook-pro ✅ and do the instruction for Mac above 👆🏻


## Install font TH Sarabun New
Font inside classes folder.

how -> http://ubuntuhandbook.org/index.php/2016/05/manually-install-fonts-ubuntu-16-04/

## Setting in VScode 

Install LaTeX Workshop (James Yu) extention.

Open setting.json then add this

```
"latex-workshop.latex.tools": [
        {
            "name": "xelatex",
            "command": "xelatex",
            "args": [
                // "-pdf",
                "%DOC%"
            ]
        }
    ],
"latex-workshop.latex.recipes": [
        {
            "name": "xelatex",
            "tools": [
                "xelatex"
            ]
        }
    ],
"latex-workshop.view.pdf.viewer": "tab"
```

## Example Page

![FrontPage](/readme/example_frontpage.png "FrontPage")
