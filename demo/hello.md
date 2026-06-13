# Hello Page

This is my first test page. It contains some text, a code block, and an
embedded Draw.io diagram loaded from the same folder.

## Some code

```python
def greet(name: str) -> str:
    return f"Hello, {name}!"
```

## The diagram

The HTML file lives next to this `.md` at `docs/demo/diagram.html`. The
iframe `src` **must be the absolute raw GitHub URL** (relative paths don't
work inside iframes).

<iframe
  src="https://raw.githubusercontent.com/Dharaneesh0745/docs/master/demo/diagram.html"
  title="Hello diagram"
  height="320"
/>

<iframe
  src="https://raw.githubusercontent.com/Dharaneesh0745/docs/master/demo/interactive.html"
  title="Interactive chart"
  height="420"
/>


That's it — push and refresh.
