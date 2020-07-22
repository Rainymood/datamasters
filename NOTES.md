# Notes

## Menu headers can be found at 

`/config/_default/menus.toml`

## Can't run with hugo server after cloning?

https://github.com/gcushen/hugo-academic/issues/1034

f you use Git to clone an Academic Kickstart repo created by Netlify, you will also need to use Git to init the Git submodule (Academic theme) or you will have a folder of website content without Academic itself installed.

The relevant steps are documented in the Installation Guide at https://github.com/gcushen/hugo-academic#install-with-git

In the root dir 

git clone https://github.com/sourcethemes/academic-kickstart.git .
