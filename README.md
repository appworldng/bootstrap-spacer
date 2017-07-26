# bootstrap-spacer
A simple CSS library containing rules for spacing bootstrap rows and columns apart...

## CDN
The CDN is updated after the release is made public. Always, check the GitHub page for the latest release.
<ul>
  <li>
    <a href="https://cdn.rawgit.com/chigozieorunta/bootstrap-spacer/65b410d7/bootstrap-spacer.css">
      https://cdn.rawgit.com/chigozieorunta/bootstrap-spacer/65b410d7/bootstrap-spacer.css
    </a>
  </li>
  <li>
    <a href="https://cdn.rawgit.com/chigozieorunta/bootstrap-spacer/2d2bcb93/bootstrap-spacer.min.css">
      https://cdn.rawgit.com/chigozieorunta/bootstrap-spacer/2d2bcb93/bootstrap-spacer.min.css
    </a>
  </li>
</ul> 

### Usage
Bootstrap Spacer comes with standard classes which you can use to style spaces between rows (**row-spacer**) and columns (**row-col-spacer**).

#### Row Styling
The **row-spacer** class provides spacing between bootstrap rows by providing a default bottom margin of 3em when added.
```
<div class="row row-spacer">
  <div class="col-md-4">
  </div>
  <div class="col-md-4">
  </div>
  <div class="col-md-4">
  </div>
</div>
```

#### Column Styling
The **row-col-spacer** class provides spacing between bootstrap columns within a row by providing a default bottom margin of 3em to the columns.
```
<div class="row row-col-spacer">
  <div class="col-md-4">
  </div>
  <div class="col-md-4">
  </div>
  <div class="col-md-4">
  </div>
</div>
```

#### Combining Classes
The **row-spacer** and **row-col-spacer** classes can be combined to achieve spacing between rows and columns together.
```
<div class="row row-spacer row-col-spacer">
  <div class="col-md-4">
  </div>
  <div class="col-md-4">
  </div>
  <div class="col-md-4">
  </div>
</div>
```

#### Other Classes
The **xs**, **sm**, **md**, **lg** options can be used to modify spacing dimensions. By default, the **row-spacer-md** class's dimension is the default size utilized and is the same as the **row-spacer** default class.
```
<!--Row Spacer Classes-->
.row-spacer-xs
.row-spacer-sm
.row-spacer-md (default, same as .row-spacer)
.row-spacer-lg

<!--Row Column Spacer Classes-->
.row-col-spacer-xs
.row-col-spacer-sm
.row-col-spacer-md (default, same as .row-col-spacer)
.row-col-spacer-lg
```

### Contributions
Anyone and everyone is welcome to contribute. Make sure you're using the latest version of bootstrap-spacer before submitting an issue. 
