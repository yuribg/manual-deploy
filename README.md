# manual-deploy

Deploy Angular app to GitHub Pages manually

1. Create repository in github.

2. Clone repository locally.

3. Create new angular app.

```
ng new manual-deploy --directory ./
```

4. Check deploy path in angular.json

```
dist/manual-deploy
```

4. Build application to docs folder with base-href equal to GitHub repository name.

```
ng build --output-path docs --base-href /manual-deploy/
```

5. Add, Commit and Push changes to remote repository.

```
git add .
git commit -m "project init"
git push
```

# Angular CLI app commands

# ManualDeploy

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.0.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
