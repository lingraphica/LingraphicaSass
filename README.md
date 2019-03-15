# LingraphicaSass
Stylesheets are located in vendor/assets/stylesheets

This repo can be imported as a Node Module or Ruby Gem. 

## Installation

Ruby:

Add this line to your application's Gemfile:

```ruby
gem 'lingraphicaSass', '[version]', git: "https://github.com/lingraphica/LingraphicaSass.git"
```

And then execute:

    $ bundle

Node:

Add this line to your application's package.json: 

```javascript
"lingraphica-sass": "https://github.com/lingraphica/LingraphicaSass.git#[version]",
```

And then execute:

    npm install

## Usage

Ruby:

In the application.scss file import the stylesheet

```ruby
@import "lingraphicaSass";
```

Vue:

Import the stylesheet in any component that uses the sass styles

```javascript
@import "lingraphica-sass";
```


