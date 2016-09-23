# \<barrakuda-editor\>

Simple Editor for Barrakuda

## Use
```
<barrakuda-editor theme="dracula"> Init Text </barrakuda-editor>
...
<script>
 document.querySelector('barrakuda-editor').refresh();
</script>
```

### Properties:

* theme: Code Mirror theme to use, on missing property the default will be used


### InnerHTML:

Insert here the inital text for the editor.

### Functions:

Method access via: `document.querySelector('barrakuda-editor').<functionName>()`

* refresh: Refresh the Editor to fix bad behavior
* getModel: Getter for the inner model text

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
