# HGtoLua
Take that HG Repository and make it parseable for GMod... for whatever reason

## Requirements

- Python 2.X
- `python-hglib`

### Use Case

Honestly this won't be relevant for most people. The most this might be useful is as an example of how one might use hglib because I couldn't find much out there. We needed some way to automatically import the current build metadata for quick reference in-game, and this was it.

### Arguments

  - Path to folder containing .hg folder, string
  - Path to output the resulting file
  - Output file name and extension
  
### Example Use

`python trhg.py`

default parameters used, assumes current directory for both inputs

`python trhg.py "C:\Users\colin\Documents\TR" "C:\Users\colin\Desktop\" "output.lua"`

uses specified paths over current directory unless otherwise stated (".")
