# Parallax Backgrounds

## Background Image

In order to add a fixed background to an element\( mostly sections \) this will be the HTML you should use:

```text
<section data-img-src="../../assets/img/bg-dark.jpg" class="section set-bg"></section>
```

Notice that you shoul specify the image src as `data-img-src`. You can specify the image like this

```text
<section class="section set-bg">
  <img class="set-me" src="../../assets/img/bg-dark.jpg"/>
</section>
```

## Make it Parallax

Simply use `.parallax-layer` class

```text
<section data-img-src="../../assets/img/bg-dark.jpg" class="section parallax-layer"></section>
```

That will do the trick.

## Parallax attributes

### `data-bg-parallax-factor="0.1"`

This will change the parallax behaviour. It is recommended to keep this value between 0.05-0.5

### `data-parallax-mode="mode-1"`

Available Modes:

* mode-1
* mode-2
* mode-3
* mode-4
* mode-5
* mode-6

Example of usage:

```text
<section data-img-src="../../assets/img/bg-dark.jpg" data-parallax-mode="mode-1" class="section parallax-layer h-500"></section>
```

