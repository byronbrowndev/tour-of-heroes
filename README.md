# TourOfHeroes

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.8.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Deployment 

### Using GH-Pages
I followed [Angular.io's deployment documentation](https://angular.io/guide/deployment#deploy-to-github-pages) with a slight modification

```ng build --prod --output-path docs --base-href "https://byronbrowndev.github.io/tour-of-heroes/"```

I used the repo url as the base-href instead of what they recommended. All the other instruction in that section were vebatim

#### Issues
I tried to use [angular-cli-ghpages](https://github.com/angular-schule/angular-cli-ghpages#usage) to no avail. I ran the build with the prescribed command ```ng build --prod --base-href "https://byronbrowndev.github.io/tour-of-heroes/"``` then. I ran the ngh command ```angular-cli-ghpages --dir=dist/tour-of-heroes``` also the variant ```ngh --dir=dist/tour-of-heroes``` only to recieve the same error each time.

![](./readme-assets/error.jpg)
