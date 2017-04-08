# venn-diagram-generator

we do it for #dataSci tech lulz

# future home of Venn Diagrams Designer

https://venn-diagrams.herokuapp.com/

# basic Venn Diagram Designer UX Sketch Idea

![alt tag](https://github.com/RandomFractals/venn-diagram-generator/blob/master/screens/vennDiagramsMemeGeneratorSketchIdea.jpg)

# Synopsis

The idea for this Venn diagram pics generator project came from sourcing a number of ineteresting posts from the data science community: new data scientist position posted, articles shared on medium, kdnuggets or elsewhere, and heavy use and abuse of Venn Diagrams pics for that purpose.

As a data viz specialist and practitioner, I've had it! A few other creative types decided if we can't beat them, we should join them, and create one stop shop app for you to gen those Venn Diagrams about what you fancy, and what unicorn intersection you are trying to find FTW.

Thus, the Venn Diagram generator idea was born: 

https://twitter.com/dataandme/status/848850426095120384

![alt tag](https://github.com/RandomFractals/venn-diagram-generator/blob/master/screens/vennDiagramsInTheWild.png)

## Ultimate Project Goal

Ideally, we'd like to create an app for you to gen Venn Diagrams like this:

https://twitter.com/BourseetTrading/status/848192200789942272

![alt tag](https://github.com/RandomFractals/venn-diagram-generator/blob/master/screens/epicDataSciVennDiagram.jpg)

or how to make your pancakes:

https://twitter.com/MrBenWard/status/836489614676353024

![alt tag](https://github.com/RandomFractals/venn-diagram-generator/blob/master/screens/pancakesVennDiagram.jpg)

Best bg story on how we ended up here is on kdnuggets:

http://www.kdnuggets.com/2016/10/battle-data-science-venn-diagrams.html


# App Dev Status

## day 1: Topic list UI prototype:

![alt tag](https://github.com/RandomFractals/venn-diagram-generator/blob/master/screens/vennDiagramTopicList3.png)

Also, the boilerplate angular4 jasmine tests are still passing. It's a good sign. 
I'll double down on that for the list comp. tomorrow.
One must have tests! for good karma and all :)

![alt tag](https://github.com/RandomFractals/venn-diagram-generator/blob/master/screens/vennDiagramsTestKarma2.png)

## day 2 dev plan:

&#10003; add delete topic and reorder topics feature to the topic list
&#10003; add diagram topic list updates tests

![alt tag](https://github.com/RandomFractals/venn-diagram-generator/blob/master/screens/vennDiagramTopicListEditor2.png)

![alt tag](https://github.com/RandomFractals/venn-diagram-generator/blob/master/screens/vennDiagramTopicListTests1.png)

## dey 3 dev plan:

- split app component into separate, app toolbar, app footer and topic list components
- add proper material UI CSS framework for buttons, toggles, topic list sidebar etc.
- add diagram name edit functionality
- stub out the actual Venn diagram d3 view component to render diagram topics
- add proper topic list UI tests

# App Build/Run Instructions

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.0.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class/module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Yarn Note

Run `ng set --global packageManager=yarn` to use Yarn package manager
