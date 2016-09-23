# \<barrakuda-editor\>

Simple Editor for Barrakuda

## Use
```
<barrakuda-editor theme="dracula" line-numbers> Init Text </barrakuda-editor>
...
<script>
 document.querySelector('barrakuda-editor').refresh();
</script>
```

### Properties:

* theme: Code Mirror theme to use, on missing property the default will be used
* line-numbers: Write this property to activate line numbers. 


### InnerHTML:

Insert here the inital text for the editor.

### Functions:

Method access via: `document.querySelector('barrakuda-editor').<functionName>()`

* refresh: Refresh the Editor to fix bad behavior
* getModel: Getter for the inner model text

## Install

### Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

### Viewing

```
$ polymer serve
```

### Building

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