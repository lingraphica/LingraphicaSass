# LingraphicaSass
Stylesheets are located in vendor/assets/stylesheets

This repo can be imported as a Node Module or Ruby Gem. 

Projects that use these styles must also use Bootstrap version 4.0.0 + 

## Installation

### Ruby:

Add this line to your application's Gemfile:

```ruby
gem 'lingraphicaSass', '1.2.0', git: "https://github.com/lingraphica/LingraphicaSass.git"
```

And then execute:

    $ bundle

### NPM:

Add this line to your application's package.json: 

```javascript
"lingraphica-sass": "https://github.com/lingraphica/LingraphicaSass.git#1.2.0"
```

And then execute:

    npm install

## Usage

### Ruby:

In the application.scss file import the stylesheet

```ruby
@import "lingraphicaSass";
```

### Vue:

#### How to get access to LG styles in component's html templates

In main.js file import the stylesheet after the Booststrap imports

```javascript
import BootstrapVue from 'bootstrap-vue';
import "bootstrap/dist/css/bootstrap.min.css";
import "bootstrap-vue/dist/bootstrap-vue.css";
import 'lingraphica-sass';
```

#### How to get access to LG styles in component's stylesheet

Options 1: Import the stylesheet in any component that will use the LG styles in the stylesheet

```css
<style lang="scss">
@import "lingraphica-sass";
```

Option 2: Globally import the stylesheet using vue.config.js files

Steps
1. In the root of the project create a file called vue.config.js
2. add the following

```javascript
module.exports = {
  css: {
    loaderOptions: {
      sass: {
        data: `@import "lingraphica-sass";`
      }
    }
  }
};
```

### Colors

![#00adc6](https://placehold.it/15/00adc6/000000?text=+) `$lingraphica-blue` <br>
![#0089a5](https://placehold.it/15/0089a5/000000?text=+) `$lingraphica-dark-teal` <br>
![#ff9933](https://placehold.it/15/ff9933/000000?text=+) `$lingraphica-orange` <br>
![#000000](https://placehold.it/15/000000/000000?text=+) `$lingraphica-true-black` <br>
![#cc5700](https://placehold.it/15/cc5700/000000?text=+) `$lingraphica-pumpkin` <br>
![#76ced9](https://placehold.it/15/76ced9/000000?text=+) `$lingraphica-sky` <br>
![#808285](https://placehold.it/15/808285/000000?text=+) `$lingraphica-dark-gray` <br>
![#a7a9ac](https://placehold.it/15/a7a9ac/000000?text=+) `$lingraphica-light-gray` <br>
![#006a88](https://placehold.it/15/006a88/000000?text=+) `$lingraphica-peacock` <br>
![#8c6fad](https://placehold.it/15/8c6fad/000000?text=+) `$lingraphica-soft-purple` <br>
![#378436](https://placehold.it/15/378436/000000?text=+) `$lingraphica-grass` <br>
![#cc5700](https://placehold.it/15/cc5700/000000?text=+) `$lingraphica-burnt-orange` <br>
![#cb2026](https://placehold.it/15/cb2026/000000?text=+) `$lingraphica-true-red` <br>
![#f9f06d](https://placehold.it/15/f9f06d/000000?text=+) `$lingraphica-sunshine` <br>

### Button Classes

`.btn-lingraphica-blue` <br>
`.btn-lingraphica-dark-teal`<br>
`.btn-lingraphica-orange` <br>
`.btn-lingraphica-true-red` <br>

#### Example:
`<button class="btn btn-lingraphica-blue">Hello</button>`

### Navbar Class

`.navbar-lingraphica` <br>

#### Example:
`<nav class="navbar navbar-lingraphica navbar-expand-lg" role="navigation">`

