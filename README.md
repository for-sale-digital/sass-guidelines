# Sass Guidelines @ FSD

Basically we are creating CSS by using Sass - standardized by the **[Sass Guidlines](https://sass-guidelin.es/) by Hugo Giraudel**.

## Only Deviants

* For a better readability we are to **indent with four spaces**  - not only two ([Sass Guidelines > Syntax And Formatting](https://sass-guidelin.es/#syntax--formatting-1)).

* **Short hex code** is the first choice to declare a color ([Sass Guidelines > Color Formats](https://sass-guidelin.es/#color-formats)).
  * fastest way for browser
  * trendiest format for creatives

* **Comments are written inline** - not blockwise ([Sass Guidelines > Writing Comments](https://sass-guidelin.es/#writing-comments)).
  * prevents output in CSS

* We use directory name **"helpers" instead of "abstracts"** ([Sass Guidelines > The 7-1 Pattern](https://sass-guidelin.es/#the-7-1-pattern)).

* We use **placeholders instead of mixins without parameters** ([Sass Guidelines > Argument-Less Mixins](https://sass-guidelin.es/#argument-less-mixins)).

* **No usage of vendor prefixes** ([Sass Guidelines > Mixins And Vendor Prefixes](https://sass-guidelin.es/#mixins-and-vendor-prefixes)).
  * Autoprefixer will manage this automatically

## Warranty

Our Sass code is verified as valid by using `grunt-scss-lint` in our pre-processing task runner.

Check out [for-sale-digital/grunt-template](https://github.com/for-sale-digital/grunt-template) for more details.