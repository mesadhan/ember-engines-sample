
# Ember Engines Agenda
- [x] - Create an Ember `Main  Application`
- [x] - Then, Install Ember Engines into `Main Application`
- [x] - Create `Child Application` into `Main Application`
- [x] - Ember Engine CLI Commands
- [x] - Run Application and then Visit Routes
- [x] - Referances


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

> Step5: Run Application and then Acess Routes

    $ ember serve

Open Browser then:
 
- Visit `Main Applicaiton` at [http://localhost:4200](http://localhost:4200)
- Visit `Child Applicaiton` at [http://localhost:4200](http://localhost:4200/rms)
- Visit `Child Applicaiton` at [http://localhost:4200](http://localhost:4200/pom)
  

> References:


- Official doc at [ember-engines](http://ember-engines.com/)
- Conpect Discussion at [ember-engines](https://www.bignerdranch.com/blog/is-your-ember-app-too-big-split-it-up-with-ember-engines/)
___

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


# Git Commands
> Working With Git Tag for  Tag Here, v1.1 is tagname

    git tag -a v1.1 -m "Project Version 1.1"
    git push origin v1.1


    git tag -d v1.1
    git push origin --delete v1.1

>This will create a new branch called `branchName` and check it out.

    $ git checkout -b branchName commitId


> This just creates the branch without checking it out.

    $ git branch branchName commitId

