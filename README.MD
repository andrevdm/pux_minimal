# Minial PUX example

Demo of a minimal PUX app and setup.

Based on counter example from https://github.com/alexmingoia/pux-starter-app


# PureScript

 1. Pulp: PureScript build tool
 1. bower: For managing purescript dependencies
 1. npm: For JS components e.g. react

# Setup
```
mkdir project_name
cd project_name
pulp init
npm init
```

# Install components

```
bower install purescript-prelude --save
bower install purescript-console --save
bower install purescript-pux --save
bower install purescript-react --save
bower install purescript-globals --save
bower install purescript-dom --save

npm install --save react
npm install --save react-dom
```

# Compile to JS

```
pulp browserify --optimise  > index.js
```

# Run

index.html loads index.js and pux code is auto-started
