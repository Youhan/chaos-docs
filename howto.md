# How To Questions

In this section we will provide quick answers to some of general question that you will probably face while using Chaos.

## How to edit Chaos?

Chaos is a HTML template and you can edit it with any text editor. However we recommend Sublime Text or Dreamweaver. Editing a file would be same as editing a text file but using HTML markup.

## How to change logo?

Logo image can be found inside the `.logo-wrapper` wrapper element. Here is the markup:

```text
<div class="logo-wrapper">
    <a href="target">
        <img src="../../assets/img/logo/logo-light.png" alt="CHAOS HTML Template" class="logo-light ol-retina">
        <img src="../../assets/img/logo/logo-dark.png" alt="CHAOS HTML Template" class="logo-dark ol-retina">
    </a>
</div>
```

**Note:** As you probably noticed there are two images for logo. This is because in Chaos we have many header variations including dark and light so we are using two logo images, one for light backgrounds and the other for dark ones.

If you only need one, you can delete the other.

Additionally, there is a `ol-retina` class on each image for showing a larger version of logo in retina devices. We are using the Apple syntax fo retina. For example, if your logo path is like:

`img/logo/logo-light.png`

On retina devices the code will try to replace it with:

`img/logo/logo-light@2x.png`

It will be only replaced if the retina version can be found.

## When should I ask for support?

Any time, but make sure you have read and searched your question in this documentation first. We try our best to support our customers to fix bugs and answer questions carefully and be aware that we don't normally provide customizations.

## How to Setup contact form?

You need a webserver with email functionality and PHP support. Also you should change the email at `php/contact.php` file to receive the emails. We don't provide any spam protection since there are various methods, you can use one as you want and integrate it with the current contact form.

## Where can I find css classes for a particular element to edit it?

We recommend using chrome developer tools. Learn to use basic inspections with chrome inspect element tool. There you can find which line of the css file is responsible for an specific part. Also there is a table of contents at the begining of the style.css file for convenience.

## Why comments are not working?

Because, comments are database driven features and they need a content management system to work with. We have just provided the design so you can integrate this with your own platform

## How to use blog? Is that supposed to work?

Like comments, Blog is also a database driven feature and you can't have a blog without any PHP or other programming languages managing and storing your content.

## How to change google map address?

To set the address simply include it in data-address attribute of map wrapper element. Here is an example:

```text
<div id="gmap" data-address="Footscray VIC 3011 Australia"></div>
```

