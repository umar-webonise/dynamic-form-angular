# Dynamic Form Generation-AngularJS apps

This project is to generate dynamic forms from json data


## Getting Started

To get you started you can simply clone the dynamic-form-angular repository and install the dependencies:

### Prerequisites

You need git to clone the angular-seed repository. You can get git from
[http://git-scm.com/](http://git-scm.com/).

You must have node.js and its package manager (npm) installed.  You can get them from [http://nodejs.org/](http://nodejs.org/).

### Clone dynamic-form-angular

```
git clone https://github.com/umar-webonise/dynamic-form-angular.git
cd dynamic-form-angular
```

### Install Dependencies

We have two kinds of dependencies in this project: tools and angular framework code.  The tools help
us manage and test the application.

* We get the tools we depend upon via `npm`, the [node package manager][npm].
* We get the angular code via `bower`, a [client-side code package manager][bower].

For local development webserver run the following command. This will install the tool globally.
It is a node.js tool called [http-server][http-server].
```
sudo npm install -g http-server
```

For installing angular framework files run following command.
```
bower install
```
*`app/bower_components` - contains the angular framework files

*Note that the `bower_components` folder would normally be installed in the root folder but
dynamic-form-angular changes this location through the `.bowerrc` file.  Putting it in the app folder makes
it easier to serve the files by a webserver.*

### Run the Application
The project with a simple development web server.  The simplest way to start
this server is:

```
http-server -a localhost -p 8000
```
Now browse to the app at `http://localhost:8000/app/`.

Alternatively, you can choose to configure your own webserver, such as apache or nginx. Just
configure your server to serve the files under the `app/` directory.

## Contact

For more information on AngularJS please check out http://angularjs.org/

[git]: http://git-scm.com/
[bower]: http://bower.io
[npm]: https://www.npmjs.org/
[node]: http://nodejs.org
[http-server]: https://github.com/nodeapps/http-server
