<steelsky>
{
  "title":"VueJS",
  "description":"VueJS usage example.",
  "tags":"#example"
}
</steelsky>

# VueJS

The simplest way to start using bootstrap is to include it in either the `header.html` or `footer.html` files like this:
```
<!-- development version, includes helpful console warnings -->
<script src="https://cdn.jsdelivr.net/npm/vue@2/dist/vue.js"></script>
```

Once you have that included it can be used in your layout files or in your converted markdown files (by using standard HTML).

## Example

---

<div id="app">
  {{ message }}
  <br>
  <input type="text" v-model="message">
  <br>
  <div v-for="item in list">
    - {{item.toUpperCase()}} -
  </div>
</div>
<script src="https://cdn.jsdelivr.net/npm/vue@2/dist/vue.js"></script>
<script>
var app = new Vue({
  el: '#app',
  data: {
    message: 'Change Me!',
    list:[
      'item1',
      'item2',
      'item3'
    ]
  }
})
</script>

---

### Source (`vuejs.md`)

```html
<div id="app">
  {{ message }}
  <br>
  <input type="text" v-model="message">
  <br>
  <div v-for="item in list">
    - {{item.toUpperCase()}} -
  </div>
</div>
<script src="https://cdn.jsdelivr.net/npm/vue@2/dist/vue.js"></script>
<script>
var app = new Vue({
  el: '#app',
  data: {
    message: 'Change Me!',
    list:[
      'item1',
      'item2',
      'item3'
    ]
  }
})
</script>
```