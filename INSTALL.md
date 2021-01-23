### [Matplotlib](https://matplotlib.org)

#### Install using Git


If you are a git user, you can install the theme and keep up to date by cloning the repo:

    $ git clone https://github.com/dracula/matplotlib.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/matplotlib/archive/master.zip) option and unzip them.

#### Activating theme

1. copy `dracula.mplstyle` to `~/.config/matplotlib/stylelib/dracula.mplstyle`
2. You can use the style with `matplotlib.pyplot.style.use('dracula')`
3. if you want dracula to be the default style, append the contents of `dracula.mplstyle` to `~/.config/matplotlib/matplotlibrc` (creating it if it does not already exist)
