# Smallest Possible Dynamic Logging Project

This is small project that contains [Ammonite](http://ammonite.io/) and [Jbang](https://www.jbang.dev/documentation/guide/latest/index.html) that demonstrates how you can use [Echopraxia](com/tersesystems/echopraxia-plusscala) to control logging dynamically while the script is running.

The documentation for scripting is [here](https://github.com/tersesystems/echopraxia#dynamic-conditions-with-scripts).  The [watch service](https://github.com/tersesystems/echopraxia#watched-scripts) will monitor the tweakflow file and recompile if it sees it has been touched.

The script uses Tweakflow, which is a secure embedded language.  If you want to play around with Tweakflow, this is a good place to start.

* [Getting Started](https://twineworks.github.io/tweakflow/getting-started.html)
* [Reference Guide](https://twineworks.github.io/tweakflow/reference.html)
* [Standard Library](https://twineworks.github.io/tweakflow/modules/std.html)

## Scala CLI

To run, install [scala-cli](https://scala-cli.virtuslab.org/) and then `scala-cli ./script.sc` will print logs to console.

Then edit `tweakflow.tf` while the program is running to see output either on or off.

Using Visual Studio Code is recommended as you can run [`scala-cli setup-ide .`](https://scala-cli.virtuslab.org/docs/cookbooks/vscode) to set up configuration, and run [Metals](https://scala-cli.virtuslab.org/docs/guides/ide/#metals). 

There is also a [Tweakflow mode](https://marketplace.visualstudio.com/items?itemName=twineworks.tweakflow) for VS code.

## JBang

To run, install [JBang](https://www.jbang.dev/documentation/guide/latest/index.html) and then `jbang Script.java` will print logs to console.
