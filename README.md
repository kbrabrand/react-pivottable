# react-pivottable

This is a fork of [plotly/react-pivottable](https://github.com/plotly/react-pivottable) with two changes:

1. `td.pvtOutput` has been wrapped in `div.pvtOutputWrapper` to allow overflow scrolling
2. `div.pvtOutputWrapper` has been styled with `overflow: auto` and `max-width: var(--pvt-output-width, 100%);` to allow setting the width using a CSS var further up in the markup

