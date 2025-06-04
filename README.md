# as

```python
classDiagram
    Set <|-- NumericSet
    Set <|-- StringSet
    Set : name
    Set : _elements
    Set : __init__()
    Set : add_element()
    Set : remove_element()
    Set : contains()
    Set : size()
    Set : is_empty()
    Set : to_list()
    Set : union()
    Set : intersection()
    Set : __str__()

    class NumericSet{
        name
        _elements
        get_sum()
        get_average()
    }
    class StringSet{
        name
        _elements
        to_uppercase()
    }
```
