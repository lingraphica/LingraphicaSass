# LingraphicaSass
Stylesheets are located in vendor/assets/stylesheets

This repo can be imported as a Node Module or Ruby Gem. 

Projects that use these styles must also use Bootstrap version 4.0.0 + 

## Installation

### Ruby:

Add this line to your application's Gemfile:

```ruby
gem 'lingraphicaSass', '[version]', git: "https://github.com/lingraphica/LingraphicaSass.git"
```

And then execute:

    $ bundle

### NPM:

Add this line to your application's package.json: 

```javascript
"lingraphica-sass": "https://github.com/lingraphica/LingraphicaSass.git#[version]",
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

Import the stylesheet in any component that uses the sass styles

```javascript
@import "lingraphica-sass";
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

.navbar-lingraphica

