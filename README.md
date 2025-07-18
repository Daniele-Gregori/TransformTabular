# TransformTabular
Transform simultaneously all columns of a tabular or a selection of them

basic examples...

"```wl
tabInt = With[{cols = Alphabet[][[1 ;; 10]]}, \
Tabular[Table[AssociationThread[cols, Table[RandomInteger[100], \
Length[cols]]], 4]]]
```

\\!\\(\\*GraphicsBox[TagBox[RasterBox[..., {{0, 82.}, {301.5, 0}}, {0, \
255}, 
   ColorFunction -> RGBColor, ImageResolution -> 144.], \
BoxForm`ImageTag[\"Byte\", 
   ColorSpace -> \"RGB\", Interleaving -> True], Selectable -> False], \

 DefaultBaseStyle -> \"ImageGraphics\", ImageSizeRaw -> {301.5, 82.}, \

 PlotRange -> {{0, 301.5}, {0, 82.}}]\\)"
