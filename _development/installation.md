---
title: "Installing the Convox CLI"
order: 50
---

We provide a `convox` command line tool that makes building, configuring, scaling, and securing your apps easy.

Here are some of the highlights:

* `convox start` - A single command to start your development environment
* `convox deploy` - A single command to deploy your application to a Rack
* `convox rack update` - A single command to deliver API and infrastructure improvements to a Rack

You can install it via the command line:

### OS X

#### Via Homebrew

    $ brew install convox

#### Manually

    $ curl -Ls https://convox.com/install/osx.zip > /tmp/convox.zip
    $ unzip /tmp/convox.zip -d /usr/local/bin

### Windows

Windows users can download the installer [here](https://dl.equinox.io/convox/convox/stable).

### Linux

    $ curl -Ls https://convox.com/install/linux.zip > /tmp/convox.zip
    $ unzip /tmp/convox.zip -d /usr/local/bin

### CentOS

CentOS users can download the .rpm [here](https://dl.equinox.io/convox/convox/stable).

## Logging in to the CLI

After installing Convox, you'll need to log in:

    $ convox login console.convox.com
    Password: <your Console API key>
    Logged in successfully.

## Updating the CLI

    $ convox update
    Updating convox/proxy: OK
    Updating convox: OK, 20161111173317
