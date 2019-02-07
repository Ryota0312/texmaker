# TeX compile tool
## Install
1. Clone this repository 
```
$ cd <ANY_DIR>
$ git clone git@github.com:Ryota0312/texmaker.git
```

2. Export PATH
```
$ echo 'export PATH=<ANY_DIR>/texmaker:$PATH'
```

## How to use
### Simple Compile
```
$ pdfplatex YOUR_TEX_FILE
```

### Options
|Option|description|
|:-----|:----------|
|p     |Preview PDF after completion of compilation.|
|r     |Remove Intermediate file.|
|b     |Compile with `texsty/bib/mybibdata.bib`|
