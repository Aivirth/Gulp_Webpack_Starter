# Caution : Still under active development

A simple starter configuration for gulp and webpack

- Gulp takes care of SASS compiling
- Webpack takes care of Javascript compiling
- Sass folders structure follows the 7-1 principle by default

## Installation

- Requires Node 6+ to run properly
- Global installation of gulp recommended

Run the following terminal commands in your project folder

```sh
npm install
```

> Optional, may require the `sudo` command as well on Linux and Mac

```sh
npm install -g gulp
```

# Gulp

### Features

- Compile both minified and normal stylesheet
- Creates a minified css map file
- Compiles all three files on changes through the `watch` command
- Paths configuration in `gulpconfig.json` file
- Doesn't crash on sass errors
- Autoprefix css properties
- Auto group media queries

### Commands

> On Linux and Mac it may be necessary to use the `sudo` command as well

**Compile normal stylesheet file**

```sh
gulp sass
```

**Compile minified stylesheet file**

```sh
gulp sassmin
```

**Watch changes and compiles normal, minified and map files**

```sh
gulp watch
```

# Webpack

## Coming Soon
