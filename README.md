# Bootstrap Media Object

Responsive Media objects built with the latest Bootstrap 5. Dedicated for highly repetitive components like blog comments, tweets, and the like.

Bootstrap 5 does not provide ready-to-use Media Objects (such as in Bootstrap 4), but their reconstruction is simple and the flexbox utilities are enough for it.

To learn more read [Flexbox Docs](https://mdbootstrap.com/docs/standard/layout/flexbox/).

## Basic example

```html
<!-- Media object -->
<div class="d-flex">
  <!-- Image -->
  <img
    src="https://mdbootstrap.com/img/new/avatars/2.jpg"
    alt="John Doe"
    class="me-3 rounded-circle"
    style="width: 60px; height: 60px;"
  />
  <!-- Body -->
  <div>
    <h5 class="fw-bold">
      John Doe
      <small class="text-muted">Posted on February 19, 2021</small>
    </h5>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
      incididunt ut labore et dolore magna aliqua.
    </p>
  </div>
</div>
<!-- Media object -->
```

#### Much more examples and a detailed description can be found at [📄 Media object documentation page](https://mdbootstrap.com/docs/standard/extended/media-object/)
