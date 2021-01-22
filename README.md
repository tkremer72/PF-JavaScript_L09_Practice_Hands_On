# L09 Practice Hands On

# Directions
For your Lesson 9 Practice Hands-On, you will be practicing your new skills. This Hands-On will not be graded, but we encourage you to complete it. The best way to become a great programmer is to practice! Once you have submitted your project, you will be able to access the solution on the next page.

Setup
Start off by downloading the starter project and unzipping it. The starter project will be in a folder named angular-L9-handson.

Starter Project

After unzipping, move the starter project folder to the FEFAngular folder located inside the FullStackWeb folder and rename it from angular-L9-handson to L09HandsOn.

Open up your terminal/command prompt.

Run the following to navigate to your Desktop

cd Desktop
Next, navigate to the FullStackWeb directory in your terminal.

cd FullStackWeb
Then, navigate to the FEFAngular directory in your terminal.

cd FEFAngular
Navigate into the L09HandsOn directory:

cd L09HandsOn
Now that you are in the L09HandsOn directory, run the following:

npm install
Next, run the following:

npm install typescript@2.8 --save-dev
Requirements
For this Hands-On, you will add a View button below the movie poster. When clicked, it will pass the image URL of the movie to the parent component, such that it can open it in a new window.

Step 1
Add a button named View to the display-movie HTML below the movie poster.
When clicked, it should target a method similar to the method for the Delete button.
This method must pass in the movie's image url.
Add a new @Output property that uses the EventEmitter to the DisplayMovieComponent class.
Hint! The EventEmitter will not be of type number. It will be the same type as the image's url in the model, since you will be passing the image url into the parent component.

Add the method from your View button into the display-movie ts file.
This method will need to use the necessary property and method.
Within the display-movies ts file, add a method that will handle opening a new window with the image url. Below, you can find code that will allow for a new window to open with the image url:
window.open(url);
Add the necessary code within the <app-display-movie> tag that will target the method within the display-movies component.
Make sure both servers are running. When the View button is clicked, it should take you to a new page where the movie's poster will be displayed.


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.1.0.

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
