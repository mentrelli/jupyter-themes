## Theme-ify your Jupyter Notebooks!

###Oceans16 Notebook
Oceans16 theme is a take on the popular Ocean Dark IPyNB theme ([Nikhil Sonnad](https://github.com/nsonnad/base16-ipython-notebook)).
![image](https://github.com/dunovank/jupyter-themes/blob/master/Screens/oceans16_nb.png?raw=true)

###Grade3 Notebook
Grade3 is a spinoff of the python syntax theme used by [nixCraft](http://www.cyberciti.biz/faq/python-sleep-command-syntax-example/)
![image](https://github.com/dunovank/jupyter-themes/blob/master/Screens/grade3_nb.png?raw=true)

###Oceans16 Syntax
![image](https://github.com/dunovank/jupyter-themes/blob/master/Screens/oceans16.png?raw=true)

###Oceans16-Bright Syntax
Bright variant of Oceans16 theme
![image](https://github.com/dunovank/jupyter-themes/blob/master/Screens/oceans-16-bright.png?raw=true)

###Grade3 Syntax
![image](https://github.com/dunovank/jupyter-themes/blob/master/Screens/grade3.png?raw=true)

[__Source Code Pro__](https://github.com/adobe/Source-Code-Pro) &  [__Hack__](https://github.com/chrissimpkins/Hack) fonts (.ttf) included in Fonts dir"

## install jupyter-themes

```sh
$ pip install git+https://github.com/dunovank/jupyter-themes.git
```

## Pick a theme and install

```sh
# list themes (located in ~/.jupyter-themes)
$ jupyter-theme -l

# install theme (-t) for jupyter nb
# theme names: oceans16 | oceans16-bright | grade3
$ jupyter-theme -t grade3

# install a theme (-t) with toolbar (-T) enabled
$ jupyter-theme -T -t grade3

# install a theme (-t) and set font-size (-f), default value is 12
$ jupyter-theme -f 10 -t grade3

# reset (-r) to default for jupyter theme
$ jupyter-theme -r
```
#### mmmm so theme-y...
