## Writing CSS at Homestayz ##

All the CSS/SASS is to be written for desktop (MD) by default. Use media queries for only those properties that need to be changed for proper display of content on the small screens (XS).

So basically only two breakpoints to be followed (MD and XS) as it will help in better structuring of the CSS.

Media queries will be basically used to adjust the font size, paddings and margins or just padding and margins if the fonts are handled to scale separately.


## General File Structure to be followed ##

stylesheets
- /base
  - _colors.scss
  - _typography.scss
  - _z-index.scss
- /components
  - _buttons.scss
  - _carousel.scss
  - _cover.scss
  - _dropdown.scss
  - _footer.scss
  - _forms.scss
  - _navigation.scss
- /helpers
  - _variables.scss
  - _loader.scss
  - _mixins.scss
- /layouts
  - _layout.scss
    - /owners-dashboard
      - _layout.scss
- /pages
  - _help.scss
  - _homestayz.scss
  - _owners.scss
  - _refer.scss
  - _houses.scss
  - /owners-dashboard
    - _home.scss
    - _key-updates.scss
    - _properties.scss
    - _settings.scss
    - _transactions.scss
- /vendors
    - /bootstrap
      - _boostrap.scss
    - /plugins
      - /bourbon
        - _bourbon.scss
- main.scss
