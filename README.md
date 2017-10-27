<a href=""><img src="" alt="TheBlackshirt" /></a>
<a href="https://travis-ci.org/WSPgC/theblackshirt"><img align="right" src="https://travis-ci.org/WSPgC/theblackshirt.svg?branch=master" alt="Build status" /></a>

This is the repository for the Waukesha South High School Newspaper, The Blackshirt.
Feel free to contribute and improve The Blackshirt.

**NOTE: If you’re stuck, just open an issue or email someone on The Blackshirt Team**

## Built With
  - <strong>Backend:</strong> Node.js
  - <strong>Client:</strong> Ember.js, Handlebars

![Wallpaper](insert wallpaper url)

# Installation

Fetch dependencies:

    npm install

Launch Server (nodemon):

    nodemon
    
## API

#### GET /posts/
The posts endpoint allows you to browse all published posts on The Blackshirt

JQuery.ajax:

    {{#get "posts"}}
      {{#foreach posts}}
        // do something
      {{/foreach}}
    {{/get}}
    
#### GET /posts/:id/
This endpoint allows you to read a specific post based on its id.

Handlebars:

    {{#get "posts" id="5" }}{{/get}}
    
#### GET /users/
The users endpoint allows you to browse all active members on The Blackshirt.

Handlebars:

    {{#get "users"}}{{/get}}
    
#### GET /users/:id
The users endpoint allows you to browse all active members on The Blackshirt.

Handlebars:

    {{#get "users" id="1"}}{{/get}}
    

# License

The Blackshirt Team - Released under the [MIT license](LICENSE).
