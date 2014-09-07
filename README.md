Ionic Contrib: Frosted Glass
===================

A reusable frosted-glass effect for adding this cool iOS effect to your Ionic apps. It looks like this:

<img src="http://ionicframework.com.s3.amazonaws.com/contrib/frost2.png" style="width: 319px; background-size: 100%">

### Use

To use, add the attribute `frost` to the element you want to blur. Then, you'll want to add an overlay to give a nice faded effect for content on top:

```html
<ion-pane frost>
</ion-pane>
<ion-pane class="my-overlay">
</ion-pane>
<style>
// Example dark overlay:
.my-overlay {
  background-color: #222;
  opacity: 0.8;
}
</style>
```

See `demo/index.html` for an example.

<p data-height="266" data-theme-id="3572" data-slug-hash="pmBch" data-default-tab="result" data-user="ionic" class='codepen'>See the Pen <a href='http://codepen.io/ionic/pen/pmBch/'>Ionic Contrib: Frost</a> by Ionic (<a href='http://codepen.io/ionic'>@ionic</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//codepen.io/assets/embed/ei.js"></script>
