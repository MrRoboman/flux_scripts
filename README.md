# flux_scripts

# Use

  1. Place flux_install in root of a new rails project and
     call ./flux_install in the terminal from the root of your rails project.
  OR
  2. Place flux_install in a bin file that's in your $PATH
     call flux_install in the terminal from the root of your rails project.

# Builds frontend

  - Create a package.json file
  - npm install
    - babel-core@6.1.4
    - babel-loader@6.1.0
    - babel-preset-es2015@6.6.0
    - babel-preset-react@6.1.4
    - flux@2.1.1
    - react@0.14.2
    - react-addons-linked-state-mixin@0.14.2
    - react-dom@0.14.2
    - react-router@2.0.0
    - webpack@1.12.4
  - Setup root route in routes.rb
  - Setup webpack.config.js
  - Add node_modules and bundle.js to .gitignore
  - generate a static_pages_controller
  - generate a static_pages/root.html
  - make directories
    - frontend
    - actions
    - components
    - constants
    - dispatcher
    - stores
    - utils
  - make files
    - entry.jsx
    - app.jsx
    - server_actions.js
    - client_actions.js
    - dispatcher.js
    - api_utils.js
