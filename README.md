# Markdown Template

Dead-simple client-side rendering of markdown using [marked](https://github.com/chjj/marked).

### Usage

`index.html`:

```html
<!doctype html><html><head><title>TITLE IN HERE!</title><script src="marked.js"></script><style>body{margin:0 auto;max-width:750px;padding:30px}a{color:#696}a:hover{text-decoration:none}em{color:#666}pre{white-space:pre-wrap}code{background:#ececec}hr{border:1px solid #ddd}</style></head><body><div id="s">
```
```
# Put markdown here. 

Easy as

* 1
* 2
* 3
```
```html
</div><script>var s=document.getElementById('s');s.innerHTML=marked(s.innerHTML);</script></body></html>
```
