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

## To enable to hero widget

Go to `content/home/hero.md` and put `active` to `true`. 

## To change content in the hero widget

Simply edit the `.md` file.

## To find all icons

https://fontawesome.com/icons?d=gallery&q=check&s=regular,solido
https://sourcethemes.com/academic/docs/page-builder/#icons

## To disable enable dark mode

`config/_default/params.toml`

## Alignment of menu items

`config/_default/params.toml`

```toml
# Main menu alignment (l = left, c = center, r = right) and logo options.
main_menu = {align = "r", show_logo = true}
```

## To enable/disable search 

Under search header 

`config/_default/params.toml`

## Hero widget content

https://github.com/gcushen/hugo-academic/blob/c4b40faefaeca46d2249d0a4de0b2056ee3b6f86/layouts/partials/widgets/hero.html

From here: `hugo-academic/layouts/partials/widgets/hero.html`

## Our colour blue

#0547FF

#acc2ff

## Develop a new widget

https://sourcethemes.com/academic/docs/page-builder/#develop-a-new-widget

first create `layouts/partials/widgets/hero-left.html` dir stucture 

initialise with `.md` file

# modify font size 

You can modify the font size all the way from extra small to extra large using the font_size option in config/_default/params.toml.

# how to add users 

https://sourcethemes.com/academic/docs/page-builder/#people

First, create a user account for each user that your wish to display. (This can also be performed by duplicating the example content/authors/admin/ folder for each user and modifying its contents appropriately.)

* make new user in `content/authors/<USERNAME>`
* make usergroup in `people.md` component/widget

# how to overwrite the navbar

navbar can be found here: 

themes/academic/layouts/partials/navbar.html

fuck i find this shit here

https://sourcethemes.com/academic/docs/customization/#override-a-template

explained in the docs