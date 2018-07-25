## Documentation for sheet: _mixins

How to use ?
------
```
@import '~sassfull/scss/utility';
```

#### Animations
```
@include keyframes(your-animation-name){
    // your animation frames
};

@include animation(your-animation-name);
```

#### Background
```
@include bg_image($url, $repeat, $position_x, $position_y, $size);
@include bg_gradient($start_color, $end_color, $orientation ['vertical' || 'horizontal' || '']);
```

#### Media query
*mobile first*
```
@include in_tablet {
    // your responsive rules
};

@include in_smallDesktop {
    // your responsive rules
};

@include in_desktop {
    // your responsive rules
};
```

#### Position
```
@include setPosition($position, $top, $right, $bottom, $left);
```

#### Typography
```
@include truncateText($overflow ['clip', 'ellipsis', 'unset']);
@include calculateRem($size, $base_size: 14);
```
