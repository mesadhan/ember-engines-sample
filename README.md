

# Ember Engines Agenda
- [x] - Create an Ember `Main  Application`
- [x] - Then, Install Ember Engines into `Main Application`
- [x] - Create `Child Application` into `Main Application`
- [x] - Ember Engine CLI Commands


> Setp1: Create an Ember `Main  Application`

    $ ember new ember-engines-sample
    $ cd ember-engines-sample

> Setp2: Install Ember Engines into `Main Application`

    $ ember install ember-engines

> Step3: Create `Child Application` into `Main Application`

    $ ember g in-repo-engine rms
    $ ember g in-repo-engine pom

> Step4: Ember Engine CLI Commands

    $ ember g route routeName
    $ ember g in-repo-engine rms route


# ember-engines-sample

This README outlines the details of collaborating on this Ember application.
A short introduction of this app could easily go here.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with npm)
* [Ember CLI](https://ember-cli.com/)
* [Google Chrome](https://google.com/chrome/)

## Installation

* `git clone <repository-url>` this repository
* `cd ember-engines-sample`
* `npm install`

## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).
* Visit your tests at [http://localhost:4200/tests](http://localhost:4200/tests).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Linting

* `npm run lint:hbs`
* `npm run lint:js`
* `npm run lint:js -- --fix`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

Specify what it takes to deploy your app.

## Further Reading / Useful Links

* [ember.js](https://emberjs.com/)
* [ember-cli](https://ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)
