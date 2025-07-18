# TransformTabular
Transform simultaneously all columns of a tabular or a selection of them

basic examples...

```wl
tabInt = With[{cols = Alphabet[][[1 ;; 10]]}, Tabular[Table[AssociationThread[cols, Table[RandomInteger[100], Length[cols]]], 4]]]
```

![image](https://www.wolframcloud.com/obj/37238773-980c-4f85-9fe7-1d8d018f5907)
