## what is this ?
this is a web pagination plugin based on jquery.
## How to use ?
```markdown
<div class="pagination" data-index="2" data-num="1000"></div>

$('.pagination').page({
  index:2,//默认页
  counts:20, //每页显示多少条数据
  pre:'上一页',
  next:'下一页'
});
```
