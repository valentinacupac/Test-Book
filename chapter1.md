# First Chapter

GitBook allows you to organize your book into chapters, each chapter is stored in a separate file like this one.THISISsomething

``````NDHRBFJRNF
FTTT

```fdgfdgfdg```


```cs
string path = @"C:\path\to\some_file.csv";
string delimiter = ",";

List<string[]> records;
using (TextReader textReader = new StreamReader(path))
{
  StringDelimitedReader reader = new StringDelimitedReader(textReader, delimiter);
  records = reader.ReadToEnd();
}
```

```vba
Sub sbWriteIntoCellData()
  Cells(1, 1)="Hello World"
  'Here the first value is Row Value and the second one is column value 
  'Cells(1, 1) means first row first column
End Sub
```

| 0:0 | 1:0 |
| --- | --- |
| 0:2 | 1:2 |

## gfgfddgf Me heading

* fgfgf
* fdgfdg
* ggdffdf

$$x + y = 5$$

[Something](http://google.com)



Test math copied from https://www.npmjs.com/package/gitbook-plugin-mathjax 

When {% math %}a \ne 0{% endmath %}, there are two solutions to {% math %}\(ax^2 + bx + c = 0\){% endmath %} and they are {% math %}x = {-b \pm \sqrt{b^2-4ac} \over 2a}.{% endmath %}

When $$a \ne 0$$, there are two solutions to $$(ax^2 + bx + c = 0)$$ and they are $$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$



![](2014-08-07 08.44.49.jpg)


This is a [link](https://www.google.rs "Some title")
