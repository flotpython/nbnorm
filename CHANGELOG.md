# 0.4.1 2024 May 30

* add option -i to fill a default language_info if missing
* deprecated rise and extensions options
* use jupytext config file to read and write files
  should be more robust, and break endless change loops wrt
  pygments and similar long-running issues

# 0.3.2 2023 Jul 28

* bugfix, the default value for style_crumb was 'HTML(' and because
  of the open parenthesis it was failing as a regexp

# 0.3.1 2023 Jan 4

* bugfix, the crumbs provided for spotting ex- license or style cells needed
  to be lowercased

# 0.3.0 2022 Dec 21

* with the -L and -S options the caller can configure regexps that are used to
  determine if a cell is a license or style (resp.) cell

# 0.2.1 2022 Sep 29

* normalize licence and style files by ignoring ending newlines

# 0.2.0 2022 Sep 12

* new option -f in cooperation with -t
  to force title adoption if already present
* bugfix; invoking jupytext.read() on a file object
  does not work as expected

# 0.1.2 2022 Jul 21

* initial pip-installable release
* has been substantially reworked from
