# Extended backgrounds

If you want to extend the background of a column to the right of left, then you should read this page

Example:

![](../.gitbook/assets/exbg-1.png)

```text
<section class="section pad-0">
  <div class="container">

    <div class="row extend-bg-wrapper">

      <div class="col-md-6">
        <div class="extend-left set-bg">
        <img src="../../assets/img/backgrounds/12.jpg" class="set-me"></div>
      </div>

      <div class="col-md-5 col-md-offset-1 p-top-50 p-bottom-50">
        <div class="tb-vcenter-wrapper">
          <div class="vcenter">
            --- contents of right side ---
          </div>
        </div>
      </div>

    </div>

  </div>
</section>
```

* The section should get a `.pad-0` class to remove the paddings
* add `.extend-bg-wrapper` class to `.row` div
* use `.set-bg` asset to make the image at the background of the column
* add `.extend-left` \( alternative is `.extend-right`\) to extend the column to right
* add paddings to the column with your contetnt.
* The height of the section will be the same heigh of your content.

Alternatively, you can specify the height of the section

```text
<div class="row extend-bg-wrapper h-600">
```

