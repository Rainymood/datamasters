# Notes

## Menu headers can be found at 

`/config/_default/menus.toml`

## Can't run with hugo server after cloning?

If you clone this project

```bash
git clone https://github.com/Rainymood/datamasters
cd datamasters
```

And try to run it you will run into an error

```bash
➜  hugo server
Built in 14 ms
Error: Error building site: "/Users/janmeppe/Documents/Projects/datamasters/content/home/demo.md:69:1": failed to extract shortcode: template for shortcode "alert" not found
```

This is because you don't have the academic theme. Download it [here]
(https://github.com/gcushen/hugo-academic#install-with-git). Then extract the
files from `hugo-academic-master` and put them in `/themes/academic/`.