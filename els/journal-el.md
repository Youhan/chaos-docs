# Journal Element

![](../.gitbook/assets/journal-el-1.png)

```text
<a href="#" class="journal-el set-bg">
  <img src="../../assets/img/publications/grid/03.jpg" class="set-me">
  <div class="contents">

    <div class="header">
      <h6>5 Sep 2015</h6>
    </div>

    <div class="footer">
      <h6 class="sub-title">Expo</h6>
      <h2 class="title">Postgraduate mixer at the Chelsea MA show</h2>
    </div>

  </div>
</a>
```

This element consists of two sections 1. `.header` which is used for metadata purpose and is positioned at the top 2. `.footer` which is used for the title

## Without cover

You should add an image with class of `.set-me` to the element and also add `.set-bg` class to book element

```text
<a href="#" class="journal-el">
  <div class="contents">

    <div class="header">
      <h6>5 Sep 2015</h6>
    </div>

    <div class="footer">
      <h6 class="sub-title">Expo</h6>
      <h2 class="title">Postgraduate mixer at the Chelsea MA show</h2>
    </div>

  </div>
</a>
```

## Color Skins

Add these classes to `.book-el`

* `.skin-blue`
* `.skin-green`
* `.skin-purple`
* `.skin-yellow`
* `.skin-red`
* `.skin-cyan`
* `.skin-lemon`

## Alternative Contents

There are some variations for content type:

![](../.gitbook/assets/journal-el-2.png)

The HTML markup will be

```text
<a href="#" class="journal-el set-bg">
  <img src="../assets/img/publications/grid/03.jpg" class="set-me">
  <div class="contents">

    <div class="header">
      <h6>5 Sep 2015</h6>
    </div>

    <div class="footer">
      <h6 class="author"><span>By</span> Jane Doe</h6>
      <h6 class="cat"><span>In</span> Students News</h6>
      <h2 class="title">Postgraduate mixer at the Chelsea MA show</h2>
    </div>

  </div>
</a>
```

