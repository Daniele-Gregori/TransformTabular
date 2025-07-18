# TransformTabular
Transform simultaneously all columns of a tabular or a selection of them

basic examples...

```wl
tabInt = With[{cols = Alphabet[][[1 ;; 10]]}, \
Tabular[Table[AssociationThread[cols, Table[RandomInteger[100], \
Length[cols]]], 4]]]
```

![image](https://www.wolframcloud.com/obj/c565201a-b3f2-45d5-a685-26df0f3abd72)
