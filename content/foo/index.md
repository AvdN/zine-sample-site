---
{
  "title": "Foo Page",
  "date": "2020-07-06T00:00:00",
  "author": "Sample Author",
  "layout": "page.html",
  "draft": false,
  "skip_subdirs": true,
  "custom": {
    "foo": 50
  }
}  
--- 
# Foo

Here's a code snippet with some Zig in it:

```zig 
const foo = @import("foo.zig");
```


Note: this markdown file sets `skip_subdirs` to `true`, which makes Zine ignore
any other markdown file and subdirectory contained in this directory.

In fact you will see that `hidden.md` doesn't get rendered.
