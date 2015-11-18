# zxc #

```bundle exec``` for NodeJS

## Installation ##

```shell
npm install -g zxc
```

Note: zxc currently only works on Unix-based environments.  Sorry, Windows peoples.

## Usage ##

Let's say that our project installed ```babel-cli``` as a dev dependency.  We'd like to list out the help for this command.  So, Instead of doing this:

```shell
./node_modules/.bin/babel --help
```

We can just do this:

```shell
zxc babel --help
```

And, that's pretty much all there is to it.

## FAQ ##

#### What does 'zxc' mean? ###

Nothing.  It was just easy to type.

#### How is 'zxc' pronounced? ####

It's pronounced "bundle exec"...

Just kidding.  Why don't we all just agree to pronounce it as "zek"?  You know -- like the last half of the word "exec".

## TODO ##

* Provide better error handling for invalid / missing commands.
* Figure out how to support Windows.
