# breadcrumb-icons
In certain circumstances, giving your users the ability to print a given webpage may be paramount. Adding this functionality directly to your breadcrumbs can highlight that ability and make the process convenient. 

## Tutorial
For detailed instruction's, view Solodev's [How to Add a print icon and Dialog to Your Breadcrumbs](https://www.solodev.com/blog/web-design/how-to-add-a-print-icon-and-dialog-to-your-breadcrumbs.stml)

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/1yhwvg4f/).

## HTML
The tutorial contains the following basic HTML markup.

```
   <nav class="navbar h-navbar p-0" role="navigation">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-xl-3 col-lg-2 col-sm-4 col-5">
          <a href="/">
            <img alt="LunarXP Logo" class="img-fluid py-3" src="https://raw.githubusercontent.com/solodev/hero-search-bar/master/images/logo.png" aria-role="logo">
          </a>
        </div>
        <div class="col-xl-9 col-lg-10 col-sm-8 col-7">
          <ul class="navbar-nav flex-row justify-content-end flex-wrap align-items-center mr-lg-4 mr-xl-0">
            <li class="nav-item px-3 text-uppercase mb-0 position-relative d-none d-lg-flex">
              <a class="d-block w-100 h-100 text-white py-4 position-relative top-link" href="#"><strong>About</strong></a>
            </li>
            <li class="nav-item px-3 text-uppercase mb-0 position-relative d-none d-lg-flex">
              <a class="d-block w-100 h-100 text-white py-4 position-relative top-link" href="#"><strong>Locations</strong></a>
            </li>
            <li class="nav-item px-3 text-uppercase mb-0 position-relative d-none d-lg-flex">
              <a class="d-block w-100 h-100 text-white py-4 position-relative top-link" href="#"><strong>Products</strong></a>

            </li>
            <li class="nav-item px-3 text-uppercase mb-0 position-relative d-none d-lg-flex">
              <a class="d-block w-100 h-100 text-white py-4 position-relative top-link" href="#"><strong>Shop</strong></a>
            </li>
            <li class="nav-item px-3 text-uppercase my-3 my-lg-0 mr-5 mr-lg-4 mr-xl-5 d-none d-lg-flex">
              <a class="d-block w-100 h-100 text-white py-4 position-relative top-link" href="#"><strong>Contact</strong></a>
            </li>
          </ul>
          <button id="sidenav-open-btn" class="menu-hamburger position-absolute pointer p-0">
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
        </div>
      </div>
    </div>
  </nav>

  <div class="breadcrumbs-container">
    <div class="container">
      <div class="row">
        <div class="crumb-div mt-3 float-left">
          <a class="fileTrail" href="/">Home</a> <span class="fileTrailDividers">|</span>
          <a class="fileTrail" href="/products/">Products</a>
          <span class="fileTrailDividers">|</span>
          <span class="fileTrailCurrent">Ships</span>
        </div>
        <div id="page-options" class="float-right mt-1">
          <a id="size-this" href="#" name="size-this">
            <br>Text Size</a>
          <a id="print-this" href="#" onclick="window.print();" name="print-this">
            <br>Print</a>
          <a id="share-this" href="//www.addthis.com/bookmark.php?v=300&amp;pubid=xa-4f44f20c267f2e6c" class="addthis_button">
            <br>Share</a>
        </div>
      </div>
    </div>
  </div>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<!-- FontAwesome CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.css">
<!-- jQuery first, then Popper.js, then Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
```