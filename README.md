# bootstrap-spacer
A simple CSS library containing rules for spacing bootstrap rows and columns apart...

### Usage
Bootstrap Spacer comes with standard classes which you can use to style spaces between rows (**row-spacer**) and columns (**row-col-spacer**).

#### Rows Styling
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

#### Columns Styling
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
<div class="row rows-spacer row-col-spacer">
  <div class="col-md-4">
  </div>
  <div class="col-md-4">
  </div>
  <div class="col-md-4">
  </div>
</div>
```

#### Other Classes
The **row-spacer** and **row-col-spacer** classes can be combined to achieve spacing between rows and columns together.
```
<!--Row Spacer Classes-->
.row-spacer-xs
.row-spacer-sm
.row-spacer-lg

<!--Row Column Spacer Classes-->
.row-col-spacer-xs
.row-col-spacer-sm
.row-col-spacer-lg
```
