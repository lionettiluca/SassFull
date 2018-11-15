## Documentation for sheet: _utility

How to use ?
------
```
@import '~sassfull/scss/utility';
```

This file include:
```
_border.scss
_colors.scss
_floating.scss
_padding.scss
_scroll.scss
_text.scss
_button.scss
_display.scss
_margin.scss
_positions.scss
_size.scss
_transform.scss
```

##### Border
```
.b-b-0 {
  border-bottom: 0;
}

.b-l-0 {
  border-left: 0;
}

.b-r-0 {
  border-right: 0;
}

.b-t-0 {
  border-top: 0;
}

.b-x-0 {
  border-left: 0;
  border-right: 0;
}

.b-y-0 {
  border-bottom: 0;
  border-top: 0;
}
```

##### Margin
```
.m-b-0 {
  margin-bottom: 0;
}

.m-b-auto {
  margin-bottom: auto;
}

.m-l-0 {
  margin-left: 0;
}

.m-l-auto {
  margin-left: auto;
}

.m-r-0 {
  margin-right: 0;
}

.m-r-auto {
  margin-right: auto;
}

.m-t-0 {
  margin-top: 0;
}

.m-t-auto {
  margin-top: auto;
}

.m-x-0 {
  margin-left: 0;
  margin-right: 0;
}

.m-x-auto {
  margin-left: auto;
  margin-right: auto;
}

.m-y-0 {
  margin-bottom: 0;
  margin-top: 0;
}

.m-y-auto {
  margin-bottom: auto;
  margin-top: auto;
}
```

##### Padding
```
.p-b-0 {
  padding-bottom: 0;
}

.p-l-0 {
  padding-left: 0;
}

.p-r-0 {
  padding-right: 0;
}

.p-t-0 {
  padding-top: 0;
}

.p-x-0 {
  padding-left: 0;
  padding-right: 0;
}

.p-y-0 {
  padding-bottom: 0;
  padding-top: 0;
}
```

##### Button
```
.btn {
  cursor: pointer;
  border: 0;
  margin: 0;
  outline: none;
}

.btn:disabled {
  cursor: not-allowed;
}

.btn:focus,
.btn:hover,
.btn:active {
  border: 0;
  outline: none;
}
```

##### Display
```
.block {
  display: block;
}

.iblock {
  display: inline-block;
}

.flex {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
}

.none {
  display: none;
}
```

##### Settings
```
.t-r-90 {
  display: inline-block;
  -webkit-transform: rotate(90deg);
          transform: rotate(90deg);
}

.t-r-180 {
  display: inline-block;
  -webkit-transform: rotate(180deg);
          transform: rotate(180deg);
}

.t-r--90 {
  display: inline-block;
  -webkit-transform: rotate(-90deg);
          transform: rotate(-90deg);
}

.t-r--180 {
  display: inline-block;
  -webkit-transform: rotate(-180deg);
          transform: rotate(-180deg);
}
```

##### Text
```
.txt-center {
  text-align: center;
}

.txt-right {
  text-align: right;
}

.txt-left {
  text-align: left;
}

.txt-white {
  color: #fff;
}

.txt-black {
  color: #000;
}

.txt-extra-light {
  font-weight: 100;
}

.txt-light {
  font-weight: 200;
}

.txt-normal {
  font-weight: 400;
}

.txt-medium {
  font-weight: 500;
}

.txt-strong {
  font-weight: 700;
}

.txt-upper {
  text-transform: uppercase;
}

.txt-lower {
  text-transform: lowercase;
}

.white-space--nw {
  white-space: nowrap;
}

.word-wrap--b {
  word-wrap: break-word;
}

.word-wrap--n {
  word-wrap: none;
}
```

##### Colors
```
.txt-black,
.bg-black {
  color: black;
}

.txt-white,
.bg-white {
  color: white;
}

.txt-transparent,
.bg-transparent {
  color: transparent;
}

.txt-inh,
.bg-inh {
  color: inherit;
}
```

#### Positions
```
.p-rel {
  position: relative;
}

.p-abs {
  position: absolute;
}

.p-fix {
  position: fixed;
}

.p-sticky {
  position: -webkit-sticky;
  position: sticky;
}
```
