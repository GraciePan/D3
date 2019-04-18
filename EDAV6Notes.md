EDAV6 Notes
================

Scales
=======
[EDAV6Lect-Scales.pdf](EDAV6Lect-Scales.pdf)

Practice creating an ordinal scale (function) in the Console:

``` js
var ordscale = d3.scaleBand()
  .domain([0, 1, 2, 3, 4])
  .range([0, 100])
  
ordscale(1);

ordscale(3);

ordscale(2.5);

ordscale(7);
```

Add inner padding and try again.

See diagram here: https://github.com/d3/d3-scale#band-scales

(Do not use `d3.scaleOrdinal()` for this purpose.)


Ordinal scale for x-axis

Simple example [ScaleBand.html](ScaleBand.html)

[EDAV5_4_scaleBand.html](EDAV5_4_scaleBand.html)

Linear scale for y-axis
[EDAV5_5_scaleLinear.html](EDAV5_5_scaleLinear.html)

Axes
=======
[EDAV6Lect-Axes.pdf](EDAV6Lect-Axes.pdf)

Margins [EDAV6_1_margins.html](EDAV6_1_margins.html)

y-axis [EDAV6_2_yaxis.html](EDAV6_2_yaxis.html)

Practice
=======
Add an x-axis to the previous file.
