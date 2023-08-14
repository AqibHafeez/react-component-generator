# React Composer CLI 🚀🚀 [![npm version](https://badge.fury.io/js/react-component-generator.svg)](https://badge.fury.io/js/react-component-generator)


Create React components effortlessly with React Composer CLI! This open-source package offers a command-line interface (CLI) for generating React components, making it easier and faster to kickstart your React projects. While it's the initial release and there is a lot more coming to enhance your component generator, such as different component templates, TypeScript support, styling options, tests, and more. This tool is designed to simplify component creation and boost your productivity as you contribute to the React community.

# Why React Composer CLI?

As a React developer, you might have noticed the lack of a built-in CLI for generating components similar to Angular. React Component Generator fills this gap by providing you with the following key features:

* Rapidly generate functional or class components with a single command.
* Simple and intuitive CLI for component generation.
* Customizable component templates for future expansions.
* Saves you valuable time by automating the boilerplate code.
* A perfect companion for your React projects.

## Installation and Usage

 #### Install the package globally

```sh
npm install -g react-composer-cli
```
* Generate Functional Component
```sh
react-composer-cli generate {{YOUR COMPONENT NAME}} --functional
```
* Generate Class-Based Component
```sh
react-composer-cli generate {{YOUR COMPONENT NAME}} --class
```
* Generate Component with styling
```sh
react-composer-cli generate {{YOUR COMPONENT NAME}} --functional --style
```

 #### Using 'npx' to Run Without Global Installation:


* Generate Functional Component
``` sh
npx react-composer-cli generate {{YOUR COMPONENT NAME}} --functional
```

* Generate Class-Based Component
```sh
npx react-composer-cli generate {{YOUR COMPONENT NAME}} --class
```
* Generate Component with styling
```sh
npx react-composer-cli generate {{YOUR COMPONENT NAME}} --functional --style
```


## What's incoming next?
* Typescript support
* Tests
* Customs Paths
* Much More

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.



## License

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
