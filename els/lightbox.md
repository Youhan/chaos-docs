# lightbox

This template uses [Magnific Popup](http://dimsemenov.com/plugins/magnific-popup/) plugin, the library is included and you can use it however you want. We have added a wrapper above it to make it easy to use. Here is how.

## Single Light-box

It is represented by `.ol-lightbox` class and we need to declare an anchor for the div. Basic markup is like:

```text
<a href="../../assets/img/hovers/01.jpg" class="ol-lightbox">some text</a>
```

By clicking on the `some text` above a light-box will open showing the image declared at `href`

A more advanced example:

```text
<a href="../../assets/img/hovers/01.jpg" class="ol-hover hover-5 ol-lightbox">
  <img src="../../assets/img/hovers/01.jpg" alt="image hover">
  <div class="ol-overlay ov-light-alpha-80"></div>
  <div class="icons"><i class="fa fa-camera"></i></div>
</a>
```

![Single Light-boxs](../.gitbook/assets/single-light-boxs.png)

A light-box is capable of showing

* Image
* Youtube Video
* Vimeo Video
* Ifram

Examples:

* YouTube light-box

    The markup would be:

  ```text
  <div href="http://www.youtube.com/watch?v=0O2aH4XLbto" data-type="iframe" title="some title" class="ol-lightbox">
    ...
  </div>
  ```

* Vimeo light-box

    The markup would be:

  ```text
  <div href="https://vimeo.com/45830194" data-type="iframe" title="some title" class="ol-lightbox">
    ...
  </div>
  ```

* TED Talks

  ```text
  <div href="https://embed-ssl.ted.com/talks/christine_sun_kim_the_enchanting_music_of_sign_language.html" data-type="iframe" title="some title" class="ol-lightbox">
    ...
  </div>
  ```

  **Note** You can embed any embeddable medias including Sound-cloud items, Ted talks, ...

* Self hosted video

  ```text
  <div href="video/02/02.mp4" data-type="localvideo" title="some title" class="ol-lightbox">
  ```

## Light-box Gallery

A light-box gallery is a array of light-boxes that can be navigated once the light-box is viewd.

![Light-box Gallery](../.gitbook/assets/lightbox-gallery.png)

You just need to add `.ol-lightbox-gallery` to one of the parent nodes of the several `.ol-lightbox` elements.

```text
<div class="row ol-lightbox-gallery">

    <div class="col-sm-6">
      <a href="../../assets/img/hovers/01.jpg" class="ol-hover hover-5 ol-lightbox">
        <img src="../../assets/img/hovers/01.jpg" alt="image hover">
        <div class="ol-overlay ov-light-alpha-80"></div>
        <div class="icons"><i class="fa fa-camera"></i></div>
      </a>
    </div>

    ...

</div>
```

**Note**  
 You can use any of the light-box types\(i.e. image, video\) in the gallery.

