# TACHYONS-HOVERS

http://tachyons.io

Work In Progress. Pull requests and open issues welcome.

## Install
```
npm install --save-dev tachyons-hovers
```
or download the css on github and include in your project.

## The Code
```

/*
  HOVER EFFECTS
*/

/* 
  
  Dim element on hover by adding the dim class.
*/

.dim {
  opacity: 1;
  -webkit-transition: opacity .15s ease-in;
          transition: opacity .15s ease-in;
}

.dim:hover,
.dim:focus {
  opacity: .5;
  -webkit-transition: opacity .15s ease-in;
          transition: opacity .15s ease-in;
}

.dim:active {
  opacity: .8;
  -webkit-transition: opacity .15s ease-out;
          transition: opacity .15s ease-out;
}

/*
  Hide child on hover:
  Put the hide-child class on a parent element and any nested element with the
  child class will be hidden and displayed on hover or focus.
  <div class="hide-child">
    <div class="child"> Hidden until hover or focus </div>
    <div class="child"> Hidden until hover or focus </div>
    <div class="child"> Hidden until hover or focus </div>
    <div class="child"> Hidden until hover or focus </div>
  </div>
*/

.hide-child .child {
  opacity: 0;
  -webkit-transition: opacity .15s ease-in;
          transition: opacity .15s ease-in;
}

.hide-child:hover  .child,
.hide-child:focus  .child,
.hide-child:active .child {
  opacity: 1;
  -webkit-transition: opacity .15s ease-in;
          transition: opacity .15s ease-in;
}

```

## Author

[mrmrs](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

