<steelsky>
{
  "title":"Bootstrap",
  "description":"Bootstrap usage example.",
  "tags":"#example"
}
</steelsky>

# Bootstrap

The simplest way to start using bootstrap is to include it in either the `header.html` or `footer.html` files like this:
```
<!-- CSS only -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">
```

Once you have that included it can be used in your layout files or in your converted markdown files (by using standard HTML).

## Examples

<button type="button" class="btn btn-primary">Button</button>

---

<div class="btn-group" role="group" aria-label="..." style="background:white">
  <button type="button" class="btn btn-default">Left</button>
  <button type="button" class="btn btn-default">Middle</button>
  <button type="button" class="btn btn-default">Right</button>
</div>

---

<div class="page-header">
  <h1>This is a page header <small>Subtext for header</small></h1>
</div>

---

<div class="jumbotron" style="background:grey">
  <h1>Hello, I'm a Jumbotron!</h1>
  <p>...</p>
  <p><a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a></p>
</div>
