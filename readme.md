# Scss Utils (Mixins & Classes)
This is a collection of useful mixins and classes for scss projects.
It's _**framework independent**_ and can be used in any project even without the need of JavaScript.

### Requirements
- [Sass](http://sass-lang.com/)

### Usage

Install the package using [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
```
npm i scss-lub
```

Import/use the following file to load mixins and classes in your scss file:
```scss
@import 'main.scss';
```

If you want to use mixins directly in your scss files you can import the following file:
```scss
@use 'scss-lub/mixins.scss';
```

and then refer to the mixins like this:
```scss
@include mixins.padding(10px);
```

### Contributing

#### Roadmap

- [ ] Add more documentation
- [ ] Add SASS support
- [ ] Add more mixins and classes
- [ ] Split imports

If you want to contribute to this project, you can fork this repository and create a pull request.
Please keep in mind that this project is still in development and may contain bugs or missing parts.
Thank you for your contribution!

Any feedback or suggestions are welcome!

___

_Contact me: [hey@gabrieleb.it](mailto:hey@gabrieleb.it)_
