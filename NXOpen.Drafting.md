# NXOpen.Drafting API 参考

> 共 21 个类 | C# (NXOpen .NET)

---

## 目录

- [NXOpen.Drafting.AnnotateViewsBuilder](#nxopen-drafting-annotateviewsbuilder)
- [NXOpen.Drafting.AttributeItemBuilder](#nxopen-drafting-attributeitembuilder)
- [NXOpen.Drafting.AttributeItemBuilderList](#nxopen-drafting-attributeitembuilderlist)
- [NXOpen.Drafting.AutomationManager](#nxopen-drafting-automationmanager)
- [NXOpen.Drafting.AutomationPreferencesBuilder](#nxopen-drafting-automationpreferencesbuilder)
- [NXOpen.Drafting.AutomationRuleBuilder](#nxopen-drafting-automationrulebuilder)
- [NXOpen.Drafting.BaseEditSettingsBuilder](#nxopen-drafting-baseeditsettingsbuilder)
- [NXOpen.Drafting.CutCopyPasteBuilder](#nxopen-drafting-cutcopypastebuilder)
- [NXOpen.Drafting.CutCopyPasteLeaderBuilder](#nxopen-drafting-cutcopypasteleaderbuilder)
- [NXOpen.Drafting.DistributeAnnotationsBuilder](#nxopen-drafting-distributeannotationsbuilder)
- [NXOpen.Drafting.DraftingApplicationManager](#nxopen-drafting-draftingapplicationmanager)
- [NXOpen.Drafting.DrawingAutomationWizard](#nxopen-drafting-drawingautomationwizard)
- [NXOpen.Drafting.DrawingCreationWizardBuilder](#nxopen-drafting-drawingcreationwizardbuilder)
- [NXOpen.Drafting.MoveToDrawingViewBuilder](#nxopen-drafting-movetodrawingviewbuilder)
- [NXOpen.Drafting.PreferencesBuilder](#nxopen-drafting-preferencesbuilder)
- [NXOpen.Drafting.PrimaryContentItemBuilder](#nxopen-drafting-primarycontentitembuilder)
- [NXOpen.Drafting.PrimaryContentItemBuilderList](#nxopen-drafting-primarycontentitembuilderlist)
- [NXOpen.Drafting.RulesBuilder](#nxopen-drafting-rulesbuilder)
- [NXOpen.Drafting.SettingsManager](#nxopen-drafting-settingsmanager)
- [NXOpen.Drafting.SmashDrawingViewBuilder](#nxopen-drafting-smashdrawingviewbuilder)
- [NXOpen.Drafting.SpecifyRuleBuilder](#nxopen-drafting-specifyrulebuilder)

---

## NXOpen.Drafting.AnnotateViewsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49292.html

This class is used to annotate views based on the knowledge fusion rules

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `ExistingAutomaticAnnotationOption[get, set]` | `unsafeNXOpen.Drafting.AnnotateViewsBuilder.ExistingAutomaticAnnotation` | Returns or sets the existing automatic annotation optionMore... |
| `Views[get]` | `unsafeNXOpen.Drawings.SelectDraftingViewList` | Returns the views to annotateMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.AttributeItemBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49296.html

Represents aNXOpen.Drafting.AttributeItemBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Title[get, set]` | `unsafe string` | Returns or sets the title.More... |
| `Value[get, set]` | `unsafe string` | Returns or sets the value.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.AttributeItemBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49300.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.Drafting.AttributeItemBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.Drafting.AttributeItemBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.Drafting.AttributeItemBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.Drafting.AttributeItemBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.Drafting.AttributeItemBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.Drafting.AttributeItemBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.Drafting.AttributeItemBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.Drafting.AttributeItemBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.Drafting.AttributeItemBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.Drafting.AttributeItemBuilderobject1,NXOpen.Drafting.AttributeItemBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Length[get]` | `unsafe int` | Returns the length of the listMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.AutomationManager

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49304.html

Represents aNXOpen.Drafting.AutomationManager

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateAnnotateViewsBuilder()` | `unsafeNXOpen.Drafting.AnnotateViewsBuilder` | Creates aNXOpen.Drafting.AnnotateViewsBuilderMore... |
| `CreateAttributeItemBuilder()` | `unsafeNXOpen.Drafting.AttributeItemBuilder` | Creates aNXOpen.Drafting.AttributeItemBuilderMore... |
| `CreateDistributeAnnotationsBuilder()` | `unsafeNXOpen.Drafting.DistributeAnnotationsBuilder` | Creates aNXOpen.Drafting.DistributeAnnotationsBuilderMore... |
| `CreateDrawingCreationWizardBuilder(bool isEditing)` | `unsafeNXOpen.Drafting.DrawingCreationWizardBuilder` | Creates aNXOpen.Drafting.DrawingCreationWizardBuilderMore... |
| `CreateDrawingCreationWizardBuilderFromRule(string className)` | `unsafeNXOpen.Drafting.DrawingCreationWizardBuilder` | Creates aNXOpen.Drafting.DrawingCreationWizardBuilderMore... |
| `CreatePreferencesBuilder()` | `unsafeNXOpen.Drafting.AutomationPreferencesBuilder` | Creates aNXOpen.Drafting.AutomationPreferencesBuilderMore... |
| `CreatePrimaryContentItemBuilder()` | `unsafeNXOpen.Drafting.PrimaryContentItemBuilder` | Creates aNXOpen.Drafting.PrimaryContentItemBuilderMore... |
| `CreateRulesBuilder()` | `unsafeNXOpen.Drafting.RulesBuilder` | Creates aNXOpen.Drafting.RulesBuilderMore... |
| `CreateSpecifyRuleBuilder()` | `unsafeNXOpen.Drafting.SpecifyRuleBuilder` | Creates aNXOpen.Drafting.SpecifyRuleBuilderMore... |
| `GetRemainingPartsOfBooklet(outNXOpen.Part[] remainingParts, out string [] remainingPartFileSpecs)` | `unsafe void` | Returns the remaining loaded parts and remaining unloaded parts full names from the bookletMore... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `DrawingRegions[get]` | `NXOpen.Drawings.DrawingRegionCollection` | Returns the RegionCollection instanceMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.AutomationPreferencesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49308.html

the builder for Drafting Automation Preferences

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetRulesList()` | `unsafe string []` | Get the ordered rules listMore... |
| `SetRulesList(string [] rules)` | `unsafe void` | Set the ordered rules listMore... |
| `Commit()` | `unsafeNXOpen.NXObject` | Commits any edits that have been applied to the builder.More... |
| `Destroy()` | `unsafe void` | Deletes the builder, and cleans up any objects created by the builder.More... |
| `GetCommittedObjects()` | `unsafeNXOpen.NXObject[]` | For builders that create more than one object, this method returns the objects that are created by commit.More... |
| `GetObject()` | `unsafeNXOpen.NXObject` | Returns the object currently being edited by this builder.More... |
| `ShowResults()` | `unsafe void` | Updates the model to reflect the result of an edit to the model for all builders that support showing results.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AllowFeetInchFractionForDimensionGreaterThan[get, set]` | `unsafe bool` | Returns or sets the determination of the feet inch fraction display for dimension greater thanMore... |
| `AllowInchFractionToNearest[get, set]` | `unsafe bool` | Returns or sets the determination of the display for inch fraction to nearestMore... |
| `AnnotationInsideGeometry[get, set]` | `unsafe bool` | Returns or sets the annotation inside geometryMore... |
| `DisplayRegion[get, set]` | `unsafe bool` | Returns or sets the display in non templateMore... |
| `DisplayRegionLabel[get, set]` | `unsafe bool` | Returns or sets the display region labelMore... |
| `DistanceBetweenAnnotations[get, set]` | `unsafe double` | Returns or sets the distance between annotationsMore... |
| `EqualDimensionCompareTolerance[get, set]` | `unsafe double` | Returns or sets the equal dimension compare toleranceMore... |
| `FeetInchFractionForDimensionGreaterThan[get, set]` | `unsafe double` | Returns or sets the feet inch fraction for dimension greater thanMore... |
| `HideFeetInchMark[get, set]` | `unsafe bool` | Returns or sets the hide feet inch markMore... |
| `InchFractionToNearest[get, set]` | `unsafe double` | Returns or sets the inch fraction to nearestMore... |
| `MaximumDistanceToGeometry[get, set]` | `unsafe double` | Returns or sets the maximum distance to geometryMore... |
| `MinimumDistanceToGeometry[get, set]` | `unsafe double` | Returns or sets the minimum distance to geometryMore... |
| `ReferenceGeometrySearchDistance[get, set]` | `unsafe double` | Returns or sets the reference geometry search distanceMore... |
| `RegionColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the region colorMore... |
| `RegionFont[get, set]` | `unsafeNXOpen.Preferences.PartDrafting.FontType` | Returns or sets the region fontMore... |
| `RegionWidth[get, set]` | `unsafeNXOpen.Preferences.PartDrafting.WidthType` | Returns or sets the region widthMore... |
| `SecondaryContentHiddenLineColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the secondary content hidden line colorMore... |
| `SecondaryContentHiddenLineFont[get, set]` | `unsafeNXOpen.Preferences.PartDrafting.FontType` | Returns or sets the secondary content hidden line fontMore... |
| `SecondaryContentHiddenLineWidth[get, set]` | `unsafeNXOpen.Preferences.PartDrafting.WidthType` | Returns or sets the secondary content hidden line widthMore... |
| `SecondaryContentVisibleLineColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the secondary content visible line colorMore... |
| `SecondaryContentVisibleLineFont[get, set]` | `unsafeNXOpen.Preferences.PartDrafting.FontType` | Returns or sets the secondary content visible line fontMore... |
| `SecondaryContentVisibleLineWidth[get, set]` | `unsafeNXOpen.Preferences.PartDrafting.WidthType` | Returns or sets the secondary content visible line widthMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.AutomationRuleBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49312.html

Represents aNXOpen.Drafting.AutomationRuleBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetRulesList()` | `unsafe string []` | The automation rules in the order of decreasing priorities.More... |
| `SetRulesList(string [] rules)` | `unsafe void` | The set of order listMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AllowInsideGeometry[get, set]` | `unsafe bool` | Returns or sets the allow inside geometry option allows annotation inside geometryMore... |
| `EqualDimensionTolerance[get, set]` | `unsafe double` | Returns or sets the equal dimension comparison toleranceMore... |
| `HideFeetAndInchMarks[get, set]` | `unsafe bool` | Returns or sets the hide feet and inch marks option Show/Hide feet and inch marks.More... |
| `Increment[get, set]` | `unsafe double` | Returns or sets the increment Display dimension value in inches and fractions to nearest specified valueMore... |
| `LowerThreshold[get, set]` | `unsafe double` | Returns or sets the lower threshold display dimension value in feet, inches and fractions if it is greater than the specified valueMore... |
| `MaximumGapToGeometry[get, set]` | `unsafe double` | Returns or sets the maximum gap from the view geometry to the annotationMore... |
| `MinimumGapBetweenAnnotations[get, set]` | `unsafe double` | Returns or sets the minimum gap between annotationsMore... |
| `MinimumGapToGeometry[get, set]` | `unsafe double` | Returns or sets the minimum gap from the view geometry to the annotationMore... |
| `ReferenceGeometryGapTolerance[get, set]` | `unsafe double` | Returns or sets the reference geometry search gap toleranceMore... |
| `RoundFeetAndInches[get, set]` | `unsafe bool` | Returns or sets the round feet and inches determine wheather or not to display dimension value in inches and fractions to nearest specified valueMore... |
| `UseFeetInchesAndFraction[get, set]` | `unsafe bool` | Returns or sets the use feet inches and fraction determine wheather or not to display dimension value in feet, inches and fractions if it is greater than the specified valueMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.BaseEditSettingsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49316.html

Represents aNXOpen.Drafting.BaseEditSettingsBuilder


---

## NXOpen.Drafting.CutCopyPasteBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49320.html

Represents a paste in Drafting

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetDefaultToPoint()` | `unsafeNXOpen.Point3d` | Get the default to point.More... |
| `InitPaste()` | `unsafe void` | Make the initial drop.More... |
| `SetDefaultToPoint(NXOpen.Point3ddropLocation)` | `unsafe void` | Set the default to point.More... |
| `SetMoveOnCommit(NXOpen.Matrix3x3rot,NXOpen.Vector3dtrans)` | `unsafe void` | Set the final motion from the drop location.More... |
| `Commit()` | `unsafeNXOpen.NXObject` | Commits any edits that have been applied to the builder.More... |
| `Destroy()` | `unsafe void` | Deletes the builder, and cleans up any objects created by the builder.More... |
| `GetCommittedObjects()` | `unsafeNXOpen.NXObject[]` | For builders that create more than one object, this method returns the objects that are created by commit.More... |
| `GetObject()` | `unsafeNXOpen.NXObject` | Returns the object currently being edited by this builder.More... |
| `ShowResults()` | `unsafe void` | Updates the model to reflect the result of an edit to the model for all builders that support showing results.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CutCopyPasteLeader[get]` | `unsafeNXOpen.Drafting.CutCopyPasteLeaderBuilder` | Returns the leader builder.More... |
| `DestinationView[get, set]` | `unsafeNXOpen.View` | Returns or sets the destination view.More... |
| `ObjectsToCopy[get]` | `unsafeNXOpen.SelectTaggedObjectList` | Returns the objects list to copy.More... |
| `Originals[get, set]` | `unsafeNXOpen.Drafting.CutCopyPasteBuilder.TypeOperation` | Returns or sets the operation type.More... |
| `OutputObjects[get]` | `unsafeNXOpen.SelectTaggedObjectList` | Returns the output ObjectsMore... |
| `PasteType[get, set]` | `unsafeNXOpen.Drafting.CutCopyPasteBuilder.TypePaste` | Returns or sets the paste typeMore... |
| `PlaneToRestrictMotion[get, set]` | `unsafeNXOpen.Plane` | Returns or sets the plane to restrict motionMore... |
| `Transform[get]` | `unsafeNXOpen.GeometricUtilities.ModlMotion` | Returns the motion from the default paste positionMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.CutCopyPasteLeaderBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49324.html

Represents a Drafting Paste, especially when reassociating a leader on paste

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetMoveOnCommit(NXOpen.Matrix3x3rot,NXOpen.Vector3dtrans)` | `unsafe void` | Set the final motion from the drop location.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `DestinationView[get, set]` | `unsafeNXOpen.View` | Returns or sets the destination view.More... |
| `IsLeaderSelection[get, set]` | `unsafe bool` | Returns or sets the variable of is leader selection or notMore... |
| `LeaderSelection[get]` | `unsafeNXOpen.SelectTaggedObject` | Returns the selection to reassociate single leaderMore... |
| `ReassociateLeader[get, set]` | `unsafe bool` | Returns or sets the flag to reassociate a leaderMore... |
| `Selection[get]` | `unsafeNXOpen.SelectTaggedObject` | Returns the selection to reassociate leaderMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.DistributeAnnotationsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49328.html

This class is used to distribute annotations associated to a view

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Views[get]` | `unsafeNXOpen.Drawings.SelectDraftingViewList` | Returns the views in which to distribute annotations.More... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.DraftingApplicationManager

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49332.html

Represents an object that manages drafting objects and member views

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateCutCopyPasteBuilder()` | `unsafeNXOpen.Drafting.CutCopyPasteBuilder` | Creates the CutCopyPaste builderMore... |
| `CreateMoveToDrawingViewBuilder()` | `unsafeNXOpen.Drafting.MoveToDrawingViewBuilder` | Creates aNXOpen.Drafting.MoveToDrawingViewBuilderMore... |
| `CreateSmashDrawingViewBuilder()` | `unsafeNXOpen.Drafting.SmashDrawingViewBuilder` | Creates aNXOpen.Drafting.SmashDrawingViewBuilderMore... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `TitleBlocks[get]` | `NXOpen.Annotations.TitleBlockCollection` | Returns the TitleBlockCollection belonging to this partMore... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.DrawingAutomationWizard

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49336.html

Represents callback data for the drawing automation wizard

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `FreeResource()` | `override void` | Free resources associated with the instance.More... |
| `initialize()` | `void` | <exclude>More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Builder[get, set]` | `unsafeNXOpen.Drafting.DrawingCreationWizardBuilder` | Returns or sets the drawing automation wizard builderMore... |
| `ContinueProcessing[get, set]` | `unsafe bool` | Returns or sets the flag denoting whether or not to create the booklet in the current sessionMore... |
| `ErrorCode[get, set]` | `unsafe int` | Returns or sets the error code to be returned from the callbackMore... |
| `Part[get, set]` | `unsafeNXOpen.Part` | Returns or sets the part from which the booklet drawings are createdMore... |
| `Handle[get]` | `IntPtr` | Handle of the internal object represented by this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.DrawingCreationWizardBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49340.html

Represents aNXOpen.Drafting.DrawingCreationWizardBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetSummary()` | `unsafe string []` | Returns the summary.More... |
| `SetObjectCreateBuilder(NXOpen.PDM.ObjectCreateBuilderobjectCreateBuilder)` | `unsafe void` | SetsNXOpen.PDM.ObjectCreateBuilderMore... |
| `SetSummary(string [] summary)` | `unsafe void` | Sets the summaryMore... |
| `Commit()` | `unsafeNXOpen.NXObject` | Commits any edits that have been applied to the builder.More... |
| `Destroy()` | `unsafe void` | Deletes the builder, and cleans up any objects created by the builder.More... |
| `GetCommittedObjects()` | `unsafeNXOpen.NXObject[]` | For builders that create more than one object, this method returns the objects that are created by commit.More... |
| `GetObject()` | `unsafeNXOpen.NXObject` | Returns the object currently being edited by this builder.More... |
| `ShowResults()` | `unsafe void` | Updates the model to reflect the result of an edit to the model for all builders that support showing results.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `ApplyTemplateToAll[get, set]` | `unsafe bool` | Returns or sets the flag which controls the behavior of settingNXOpen.Drafting.PrimaryContentItemBuilder.GeometryTemplateon an item inNXOpen.Drafting.DrawingCreationWizardBuilder.PrimaryContent.More... |
| `Attributes[get]` | `unsafeNXOpen.Drafting.AttributeItemBuilderList` | Returns the attributes.More... |
| `DetailID[get, set]` | `unsafe string` | Returns or sets the detail id.More... |
| `Discipline[get, set]` | `unsafe string` | Returns or sets the discipline.More... |
| `DrawingStyle[get, set]` | `unsafe string` | Returns or sets the drawing style.More... |
| `ExcludedContent[get]` | `unsafeNXOpen.Assemblies.SelectComponentList` | Returns the excluded content.More... |
| `Folder[get, set]` | `unsafe string` | Returns or sets the folder.More... |
| `IntroductoryTemplate[get, set]` | `unsafe string` | Returns or sets the introductory template.More... |
| `Name[get, set]` | `unsafe string` | Returns or sets the name.More... |
| `Number[get, set]` | `unsafe string` | Returns or sets the number.More... |
| `PrimaryContent[get]` | `unsafeNXOpen.Drafting.PrimaryContentItemBuilderList` | Returns the primary content.More... |
| `References[get]` | `unsafeNXOpen.SelectNXObjectList` | Returns the references.More... |
| `Revision[get, set]` | `unsafe string` | Returns or sets the revision.More... |
| `SecondaryContent[get]` | `unsafeNXOpen.Assemblies.SelectComponentList` | Returns the secondary content.More... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.MoveToDrawingViewBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49344.html

This builder allows the user to extract contents from a sheet and transfer them to a new Drawing view, also provide some other options for view creation

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `SelectObjects[get]` | `unsafeNXOpen.SelectTaggedObjectList` | Returns the select objects from the current sheetMore... |
| `SelectPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the select point to calculate the new created drawing view's reference pointMore... |
| `TwoDOrientation[get]` | `unsafeNXOpen.Drawings.View2dOrientBuilder` | Returns the view orientationMore... |
| `ViewScale[get]` | `unsafeNXOpen.Drawings.ViewScaleBuilder` | Returns the view scaleMore... |
| `ViewStyle[get]` | `unsafeNXOpen.Drawings.ViewStyleBuilder` | Returns the view styleMore... |
| `XCoordinate[get, set]` | `unsafe double` | Returns or sets the x coordinate to calculate the new created drawing view's reference pointMore... |
| `YCoordinate[get, set]` | `unsafe double` | Returns or sets the y coordinate to calculate the new created drawing view's reference pointMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.PreferencesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49352.html

Represents aNXOpen.Drafting.PreferencesBuilderbuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `InheritSettingsFromCustomerDefault()` | `unsafe void` | Inherit Settings From Customer DefaultMore... |
| `InheritSettingsFromPreferences()` | `unsafe void` | Inherit Settings From PreferenceMore... |
| `InheritSettingsFromSelectedObjects(NXOpen.NXObjectselectedObject)` | `unsafe void` | Inherit Settings From Selected ObjectsMore... |
| `SynchronizeFCFSymbolSequence()` | `unsafe void` | Synchronize fcf symbol sequenceMore... |
| `Commit()` | `unsafeNXOpen.NXObject` | Commits any edits that have been applied to the builder.More... |
| `Destroy()` | `unsafe void` | Deletes the builder, and cleans up any objects created by the builder.More... |
| `GetCommittedObjects()` | `unsafeNXOpen.NXObject[]` | For builders that create more than one object, this method returns the objects that are created by commit.More... |
| `GetObject()` | `unsafeNXOpen.NXObject` | Returns the object currently being edited by this builder.More... |
| `ShowResults()` | `unsafe void` | Updates the model to reflect the result of an edit to the model for all builders that support showing results.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AnnotationOriginAlignment[get]` | `unsafeNXOpen.Annotations.OriginAlignmentBuilder` | Returns the annotation origin alignmentMore... |
| `AnnotationStyle[get]` | `unsafeNXOpen.Annotations.StyleBuilder` | Returns the annotation style builderMore... |
| `AssemblyCreationSettingsBuilder[get]` | `unsafeNXOpen.Layout2d.AssemblyCreationSettingsBuilder` | Returns the assembly creation from 2d component builderMore... |
| `AutomationBooklet[get]` | `unsafeNXOpen.Drawings.AutomationBookletBuilder` | Returns the AutomationBookletBuilder builderMore... |
| `AutomationRule[get]` | `unsafeNXOpen.Drafting.AutomationRuleBuilder` | Returns the drafting automation rule builderMore... |
| `AutomationTemplateRegion[get]` | `unsafeNXOpen.Drawings.AutomationTemplateRegionBuilder` | Returns the AutomationTemplateRegion builderMore... |
| `BendTable[get]` | `unsafeNXOpen.Annotations.BendTableSettingsBuilder` | Returns the Bend table settings builderMore... |
| `BorderAndZoneStyle[get]` | `unsafeNXOpen.Drawings.BorderAndZoneStyleBuilder` | Returns the border and zone style builderMore... |
| `CommonWorkflow[get]` | `unsafeNXOpen.Annotations.CommonWorkflowBuilder` | Returns the common workflow builderMore... |
| `Component2dSettings[get]` | `unsafeNXOpen.Layout2d.ComponentSettingsBlockBuilder` | Returns the 2d component settings block builder, this builder stores the settings of the 2d componentMore... |
| `CreateComponentFrom3DSettingsBuilder[get]` | `unsafeNXOpen.Layout2d.CreateComponentFrom3DSettingsBuilder` | Returns the create component from 3d builderMore... |
| `DimensionOriginAlignment[get]` | `unsafeNXOpen.Annotations.OriginAlignmentBuilder` | Returns the dimension origin alignmentMore... |
| `DimensionWorkflow[get]` | `unsafeNXOpen.Annotations.DimensionWorkflowBuilder` | Returns the Dimension Workflow builderMore... |
| `DrawingFormatsheet[get]` | `unsafeNXOpen.Drawings.DrawingFormatSheetBuilder` | Returns the drawing format sheet builderMore... |
| `DrawingFormatTitle[get]` | `unsafeNXOpen.Annotations.DrawingFormatTitleBuilder` | Returns the drawing format title block builderMore... |
| `FramebarGeneral[get]` | `unsafeNXOpen.Annotations.ShipDraftingFramebarGeneralBuilder` | Returns the framebar general builderMore... |
| `GeneralLayoutPreferencesBuilder[get]` | `unsafeNXOpen.Layout2d.GeneralPreferencesBuilder` | Returns the general layout preferences builderMore... |
| `HoleTableContent[get]` | `unsafeNXOpen.Annotations.HoleTableSettingsContentBuilder` | Returns the Hole table settings content builderMore... |
| `HoleTableFormat[get]` | `unsafeNXOpen.Annotations.HoleTableSettingsFormatBuilder` | Returns the Hole table settings format builderMore... |
| `HoleTableHoleFilters[get]` | `unsafeNXOpen.Annotations.HoleTableSettingsHoleFiltersBuilder` | Returns the Hole table settings hole filters builderMore... |
| `HoleTableLabel[get]` | `unsafeNXOpen.Annotations.HoleTableSettingsLabelBuilder` | Returns the Hole table settings label builderMore... |
| `HoleTableWorkflow[get]` | `unsafeNXOpen.Annotations.HoleTableSettingsWorkflowBuilder` | Returns the Hole table settings workflow builderMore... |
| `PartFamilyTable[get]` | `unsafeNXOpen.Annotations.PartFamilyTableSettingsBuilder` | Returns the Part Family table settings builderMore... |
| `PartsList[get]` | `unsafeNXOpen.Annotations.PartsListBuilder` | Returns the parts list style builderMore... |
| `RetainedAnnotations[get]` | `unsafeNXOpen.Annotations.RetainedAnnotationsBuilder` | Returns the General Retained Annotations builderMore... |
| `SymbolWorkflow[get]` | `unsafeNXOpen.Annotations.SymbolWorkflowBuilder` | Returns the SymbolWorkflow builderMore... |
| `TableCellStyle[get]` | `unsafeNXOpen.Annotations.TableCellStyleBuilder` | Returns the table cell style builderMore... |
| `TableOriginAlignment[get]` | `unsafeNXOpen.Annotations.OriginAlignmentBuilder` | Returns the table origin alignmentMore... |
| `TableSection[get]` | `unsafeNXOpen.Annotations.TableSectionStyleBuilder` | Returns the table section style builderMore... |
| `TabularNoteStyle[get]` | `unsafeNXOpen.Annotations.TabularNoteStyleBuilder` | Returns the tabular note style builderMore... |
| `TrackDrawingChangesGeneral[get]` | `unsafeNXOpen.Drawings.TrackDrawingChangesGeneralBuilder` | Returns the track drawing changes general settings builderMore... |
| `TrackDrawingChangesReportFilter[get]` | `unsafeNXOpen.Drawings.TrackDrawingChangesReportFilterBuilder` | Returns the track drawing changes report filter builderMore... |
| `ViewBreak[get]` | `unsafeNXOpen.Drawings.ViewBreakBuilder` | Returns the view break builderMore... |
| `ViewDetailLabel[get]` | `unsafeNXOpen.Drawings.ViewDetailLabelBuilder` | Returns the view detail label builderMore... |
| `ViewLabel[get]` | `unsafeNXOpen.Drawings.ViewLabelBuilder` | Returns the view label builderMore... |
| `ViewProjectedLabel[get]` | `unsafeNXOpen.Drawings.ViewProjectedLabelBuilder` | Returns the view projected label builderMore... |
| `ViewSectionLabel[get]` | `unsafeNXOpen.Drawings.ViewSectionLabelBuilder` | Returns the view section label builderMore... |
| `ViewSectionLine[get]` | `unsafeNXOpen.Drawings.ViewSectionLineBuilder` | Returns the Section Line builderMore... |
| `ViewStyle[get]` | `unsafeNXOpen.Drawings.ViewStyleBuilder` | Returns the view style builderMore... |
| `ViewWorkflow[get]` | `unsafeNXOpen.Drawings.ViewWorkflowBuilder` | Returns the view workflow builderMore... |
| `VisualDrawingCompare[get]` | `unsafeNXOpen.Drawings.VisualDrawingComparePrefsBuilder` | Returns the visual drawing compare settings builderMore... |
| `Workflow[get]` | `unsafeNXOpen.Drawings.GeneralWorkFlowBuilder` | Returns the general workflow builderMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.PrimaryContentItemBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49356.html

Represents aNXOpen.Drafting.PrimaryContentItemBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Content[get]` | `unsafeNXOpen.Assemblies.SelectComponentList` | Returns the content.More... |
| `GeometryTemplate[get, set]` | `unsafe string` | Returns or sets the geometry template.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.PrimaryContentItemBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49360.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.Drafting.PrimaryContentItemBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.Drafting.PrimaryContentItemBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.Drafting.PrimaryContentItemBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.Drafting.PrimaryContentItemBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.Drafting.PrimaryContentItemBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.Drafting.PrimaryContentItemBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.Drafting.PrimaryContentItemBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.Drafting.PrimaryContentItemBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.Drafting.PrimaryContentItemBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.Drafting.PrimaryContentItemBuilderobject1,NXOpen.Drafting.PrimaryContentItemBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Length[get]` | `unsafe int` | Returns the length of the listMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.RulesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49364.html

This class is used to specify knowledge fusion rules in a drawing template

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `DimensionRule[get, set]` | `unsafe string` | Returns or sets the dimension ruleMore... |
| `NoteRule[get, set]` | `unsafe string` | Returns or sets the note ruleMore... |
| `SymbolRule[get, set]` | `unsafe string` | Returns or sets the symbol ruleMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.SettingsManager

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49368.html

Represents an object that manages drafting settings

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateAnnotationEditSettingsBuilder(NXOpen.DisplayableObject[] objects)` | `unsafeNXOpen.Annotations.EditSettingsBuilder` | Creates aNXOpen.Annotations.EditSettingsBuilderMore... |
| `CreateDrawingEditSectionLineSettingsBuilder(NXOpen.Drawings.SectionLine[] sectionLines)` | `unsafeNXOpen.Drawings.EditSectionLineSettingsBuilder` | Creates aNXOpen.Drawings.EditSectionLineSettingsBuilderMore... |
| `CreateDrawingEditViewLabelSettingsBuilder(NXOpen.DisplayableObject[] viewLabels)` | `unsafeNXOpen.Drawings.EditViewLabelSettingsBuilder` | Creates aNXOpen.Drawings.EditViewLabelSettingsBuilderMore... |
| `CreateDrawingEditViewSettingsBuilder(NXOpen.View[] views)` | `unsafeNXOpen.Drawings.EditViewSettingsBuilder` | Creates aNXOpen.Drawings.EditViewSettingsBuilderMore... |
| `CreateLayout2dEditComponentSettingsBuilder(NXOpen.Layout2d.Component[] components)` | `unsafeNXOpen.Layout2d.EditComponentSettingsBuilder` | Creates aNXOpen.Layout2d.EditComponentSettingsBuilderThis builder is the interface to edit the 2d component settings of layoutMore... |
| `CreatePreferencesBuilder()` | `unsafeNXOpen.Drafting.PreferencesBuilder` | Creates aNXOpen.Drafting.PreferencesBuilderMore... |
| `CreateTableEditSettingsBuilder(NXOpen.DisplayableObject[] objects)` | `unsafeNXOpen.Annotations.TableEditSettingsBuilder` | Creates aNXOpen.Annotations.TableEditSettingsBuilderMore... |
| `CreateTableRowSortingBuilder(NXOpen.DisplayableObject[] objects)` | `unsafeNXOpen.Annotations.TableRowSortingBuilder` | Creates aAnnotations.TableRowSortingBuilderMore... |
| `CreateTableRowSortingBuilder(NXOpen.Annotations.TabletableObject)` | `unsafeNXOpen.Annotations.TableRowSortingBuilder` | Creates aAnnotations.TableRowSortingBuilderfrom TableMore... |
| `ProcessForMultipleObjectsSettings(NXOpen.Drafting.BaseEditSettingsBuilder[] editSettingsBuilders)` | `unsafe void` | Process edit settings builders for multiple objects User must call this API for multiple object settings and pass all edit settings builders for selected objectsMore... |
| `ProcessForMutipleObjectsSettings(NXOpen.Drafting.BaseEditSettingsBuilder[] editSettingsBuilders)` | `unsafe void` | Process edit settings builders for mutiple objectsMore... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.SmashDrawingViewBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49372.html

This builder allows the user to break a Drawing View into its parts and delete the Drawing View

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `SelectView[get]` | `unsafeNXOpen.Drawings.SelectDraftingView` | Returns the select drawing views to smashMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drafting.SpecifyRuleBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49376.html

This class is used to specify knowledge fusion rule for a note object in a drawing template

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Note[get, set]` | `unsafeNXOpen.Annotations.Note` | Returns or sets the note to add rule toMore... |
| `Rule[get, set]` | `unsafe string` | Returns or sets the ruleMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---
