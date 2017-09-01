# NEXT

## Features

- []() Includes `webpack`, as it is referenced [Rails-5 Vue js How](https://mkdev.me/en/posts/rails-5-vue-js-how-to-stop-worrying-and-love-the-frontend) and uses [Vue.js](https://vuejs.org)  

  Following steps:

  1. add to Gemfile
  ```ruby
  # Gemfile
  gem 'webpacker'
  gem 'foreman'
  ```
  2. run:
  ```bash
  $ bundle
  $ bin/rails webpacker:install
  ```

  as base for usage of JS stuff, which can be handled by webpack

  3. use [Vue.js](https://vuejs.org):
  ```bash
    $ bin/rails webpacker:install:vue
    ```
