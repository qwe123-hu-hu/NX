# NXOpen.Sketch API 参考

> 共 5 个类 | C# (NXOpen .NET)

---

## 目录

- [NXOpen.Sketch.ConstraintGeometry](#nxopen-sketch-constraintgeometry)
- [NXOpen.Sketch.ConstraintGeometryHelp](#nxopen-sketch-constraintgeometryhelp)
- [NXOpen.Sketch.CopyObjectData](#nxopen-sketch-copyobjectdata)
- [NXOpen.Sketch.DimensionGeometry](#nxopen-sketch-dimensiongeometry)
- [NXOpen.Sketch.SketchGeometry](#nxopen-sketch-sketchgeometry)

---

## NXOpen.Sketch.ConstraintGeometry

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a68772.html

Used by the create geometric constraint methods to indicate what geometry the constraint should be applied to

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `ConstraintGeometry(NXOpen.NXObjectGeometry,NXOpen.Sketch.ConstraintPointTypePointType, intSplineDefiningPointIndex)` | `` | Constructor for the ConstraintGeometry struct.More... |


---

## NXOpen.Sketch.ConstraintGeometryHelp

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a68796.html

Used by several constraint creation methods that need a help point or parameter to indicate how to create the constraint

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `ConstraintGeometryHelp(NXOpen.Sketch.ConstraintGeometryHelpTypeType,NXOpen.Point3dPoint, doubleParameter)` | `` | Constructor for the ConstraintGeometryHelp struct.More... |


---

## NXOpen.Sketch.CopyObjectData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a68800.html

This structure represents a map between the original object to be copied and the corresponding copied object

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CopyObjectData(NXOpen.NXObjectOrigObject,NXOpen.NXObjectCopiedObject)` | `` | Constructor for the CopyObjectData struct.More... |


---

## NXOpen.Sketch.DimensionGeometry

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a68788.html

Used in the dimension creation methods to indicate what geometry to create the dimension on


---

## NXOpen.Sketch.SketchGeometry

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a68780.html

Sketch operations can use an entire geometry, such as aNXOpen.Line, or a control point of the geometry, such as a start point or center point

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SketchGeometry(NXOpen.NXObjectGeometry,NXOpen.Sketch.PointTypePointType, intPointIndex)` | `` | Constructor for the SketchGeometry struct.More... |


---
