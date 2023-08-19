# View

The view data type is the core of BuckShot++, it can contains html, css and js properties and is a reusable object!

### Declaring new views

Here is how you create a view in bpp:

```
view MyFirstView{
    type = "h1"
    content = "This is an awesome title!"
    color = "red"
}
```

### Child views

Since bpp is Object Oriented, you can create new views based of the properties of an other parent view, if you do so, the new view will inehrit all the properties from the parent. Here is an example of how to do so:

```
view MyChildView:MyFirstView{
    content = "I have just changed the content of MyFirstView !"
}
```
