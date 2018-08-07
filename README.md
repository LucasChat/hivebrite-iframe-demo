# Hivebrite - responsive iFrame example

```
<div class="resp-container">
  <iframe class="resp-iframe" scrolling="yes" src="YOUR URL HERE" gesture="media"  allow="encrypted-media" allowfullscreen></iframe>
</div>
<style>
.resp-container {
  position: relative;
  overflow: hidden;
  padding-top: 75.25%;
}
.resp-iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 0;
}
@media (max-width: 44.9375em) {
  .resp-container {
    position: relative;
    overflow: hidden;
    padding-top: 155.25%;
  }
}
</style>
```
