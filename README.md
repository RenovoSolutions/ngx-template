# ngx-template-seed
### Seed project for creating redistributable Angular modules

## Getting started

* clone the repo to your local machine
* Run `npm install` in the root directory.
* Run `npm run new [Insert Plugin Name Here]` _(only run this once when cloning the template repo)_
* Enjoy.

## Development:

### Work flow

* Clone repository to your machine.
* Live edit mode with `npm run serve`. _(goes into the project director and run's `ng serve`)_
* Run tests with watcher with `npm run test`. _(goes into the project director and run's `ng test`)_
* Prepare for distrabution with `npm run prepare.dist` after which you can publish to npm with run `npm publish`
* Test a demo project using the exported ngModule with `npm run demo`  _(prepares the project for distrabution and then goes into the demo directory and runs `ng serve`)_

* Run `npm run setup` to prepare the project. _(runs npm install in the demo and main project directory)_

* *Optionally* you can use https://github.com/angular-buch/angular-cli-ghpages to publish the demo install to github pages. by first running `npm run demo` then going into your demo directory with `cd demo` and from their you can copy and past the two commands to publish to github pages. 
    ```
    ng build --prod --aot --base-href "https://USERNAME.github.io/YOUR-REPO-NAME/"
    ```
    then
    ```
    ngh --repo=https://github.com/USERNAME/YOUR-REPO-NAME.git
    ```

### Requirements

* angular-cli 1.0.0 rc.0 or higher
* node 6.9.0 or higher

### Contributors

[<img alt="TheOriginalJosh" src="https://avatars.githubusercontent.com/u/1486275?v=3&s=117" width="117">](https://github.com/TheOriginalJosh) | [<img alt="jbeck8176" src="https://avatars.githubusercontent.com/u/7142382?v=3&s=117" width="117">](https://github.com/jbeck8176) |
:---: |:---: |
[Josh Sommer](https://github.com/TheOriginalJosh) |[Jeff Beck](https://github.com/jbeck8176) |


