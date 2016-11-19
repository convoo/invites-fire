# Invites Fire

<p align="center">
  <img alt="invites-fire" src="InvitesFire400.png" width="200">
</p>

<p align="center">
Simple way to manage and encourage invites while controlling early access to your app.
</p>

<p align="center">
  <a href="https://beta.webcomponents.org/element/convoo/invites-fire"><img src="https://img.shields.io/badge/webcomponents.org-published-blue.svg"></a>
  <a href="https://gitter.im/convoo/general"><img src="https://img.shields.io/badge/gitter-join%20chat-brightgreen.svg"></a>
</p>


## \<invites-fire\>

The core element that returns whether a user has early access and if they do.

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="invites-fire.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<invites-fire user-id="{{user.uid}}" has-access="[[userHasAccess]]"></invites-fire>
```

## \<add-invites-fire\>

A form for users with access to invite others.

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="add-invites-fire.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<add-invites-fire user-id="{{user.uid}}"></add-invites-fire>
```


## \<admin-invites-fire\>

The admin interface for giving access to users requesting it.

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="invites-fire.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<admin-invites-fire></admin-invites-fire>
```

## Contributing

### Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

### Viewing Your Application

```
$ polymer serve
```

### Building Your Application

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

### Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
