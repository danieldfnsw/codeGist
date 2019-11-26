1. HTML 文本超出宽度后实现自动截取

``` html
<style>
.substr{
  white-space:nowrap;
  overflow:hidden;
  text-overflow: ellipsis;
}
</style>
<div class="hello substr">
    hello world!
<div>
```

