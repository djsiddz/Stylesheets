## Writing CSS at Homestayz ##

All the CSS/SASS is to be written for desktop (MD) by default. Use media queries for only those properties that need to be changed for proper display of content on the small screens (XS).

So basically only two breakpoints to be followed (MD and XS) as it will help in better structuring of the CSS.

Media queries will be basically used to adjust the font size, paddings and margins or just padding and margins if the fonts are handled to scale separately.


## General File Structure to be followed ##

stylesheets
- /base
  - _base.scss?
  - _typography.scss
  - _reset.scss?
- /components
  - _buttons.scss
  - _carousel.scss
  - _cover.scss
  - dropdown.scss
  - navigation.scss
- /helpers-or-utils
  - _variables.scss
  - _functions.scss
  - _mixins.scss
  - _helpers.scss
- /layouts
  - _grid.scss
  - _header.scss
  - _footer.scss
  - _sidebar.scss
  - _forms.scss
- /pages
  - _home.scss
  - _contact.scss
- /theme
  - _theme.scss
  - _admin.scss
- /vendors
  - _boostrap.scss
  - _jquery-ui.scss
- /plugins
  - /bourbon
    - _bourbon.scss
  - /neat
    - _neat.scss
- main.scss
