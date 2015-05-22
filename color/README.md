sass-color
==========

Color Contrast and Equalizer for Sass


#### Usage

    $color-threshold: 3;

    @if color-contrast($color, $bg) < $color-threshold {

        @warn "Color contrast #{color-contrast($color, $bg)} is less than threshold #{$color-threshold}";
  
    }
