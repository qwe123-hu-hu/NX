# NXOpen.Drawings API 参考

> 共 200 个类 | C# (NXOpen .NET)

---

## 目录

- [NXOpen.Drawings.AddObjectsToRegionBuilder](#nxopen-drawings-addobjectstoregionbuilder)
- [NXOpen.Drawings.AddRemoveBoxViewBuilder](#nxopen-drawings-addremoveboxviewbuilder)
- [NXOpen.Drawings.AnnotationSettingsBuilder](#nxopen-drawings-annotationsettingsbuilder)
- [NXOpen.Drawings.AssociativeAngleBuilder](#nxopen-drawings-associativeanglebuilder)
- [NXOpen.Drawings.AutomationBookletBuilder](#nxopen-drawings-automationbookletbuilder)
- [NXOpen.Drawings.AutomationTemplateRegionBuilder](#nxopen-drawings-automationtemplateregionbuilder)
- [NXOpen.Drawings.BaseHalfSectionLine](#nxopen-drawings-basehalfsectionline)
- [NXOpen.Drawings.BasePointToPointSectionLine](#nxopen-drawings-basepointtopointsectionline)
- [NXOpen.Drawings.BaseSteppedSectionLine](#nxopen-drawings-basesteppedsectionline)
- [NXOpen.Drawings.BaseView](#nxopen-drawings-baseview)
- [NXOpen.Drawings.BaseViewBuilder](#nxopen-drawings-baseviewbuilder)
- [NXOpen.Drawings.BaseViewStyle](#nxopen-drawings-baseviewstyle)
- [NXOpen.Drawings.BorderAndZoneStyleBuilder](#nxopen-drawings-borderandzonestylebuilder)
- [NXOpen.Drawings.BordersAndZones](#nxopen-drawings-bordersandzones)
- [NXOpen.Drawings.BordersAndZonesBuilder](#nxopen-drawings-bordersandzonesbuilder)
- [NXOpen.Drawings.BordersAndZonesCollection](#nxopen-drawings-bordersandzonescollection)
- [NXOpen.Drawings.BrokenViewBuilder](#nxopen-drawings-brokenviewbuilder)
- [NXOpen.Drawings.CompareReportBuilder](#nxopen-drawings-comparereportbuilder)
- [NXOpen.Drawings.ConversionProcessSettingsBuilder](#nxopen-drawings-conversionprocesssettingsbuilder)
- [NXOpen.Drawings.ConvertDraftingContentsBuilder](#nxopen-drawings-convertdraftingcontentsbuilder)
- [NXOpen.Drawings.ConvertToPMIBuilderManager](#nxopen-drawings-converttopmibuildermanager)
- [NXOpen.Drawings.CustomViewSettingsBuilder](#nxopen-drawings-customviewsettingsbuilder)
- [NXOpen.Drawings.DetailView](#nxopen-drawings-detailview)
- [NXOpen.Drawings.DetailViewBuilder](#nxopen-drawings-detailviewbuilder)
- [NXOpen.Drawings.DraftingBody](#nxopen-drawings-draftingbody)
- [NXOpen.Drawings.DraftingBodyCollection](#nxopen-drawings-draftingbodycollection)
- [NXOpen.Drawings.DraftingComponentSelectionBuilder](#nxopen-drawings-draftingcomponentselectionbuilder)
- [NXOpen.Drawings.DraftingCurve](#nxopen-drawings-draftingcurve)
- [NXOpen.Drawings.DraftingCurveCollection](#nxopen-drawings-draftingcurvecollection)
- [NXOpen.Drawings.DraftingCurveInfo](#nxopen-drawings-draftingcurveinfo)
- [NXOpen.Drawings.DraftingDrawingSheet](#nxopen-drawings-draftingdrawingsheet)
- [NXOpen.Drawings.DraftingDrawingSheetBuilder](#nxopen-drawings-draftingdrawingsheetbuilder)
- [NXOpen.Drawings.DraftingDrawingSheetCollection](#nxopen-drawings-draftingdrawingsheetcollection)
- [NXOpen.Drawings.DraftingPoint](#nxopen-drawings-draftingpoint)
- [NXOpen.Drawings.DraftingPointCollection](#nxopen-drawings-draftingpointcollection)
- [NXOpen.Drawings.DraftingView](#nxopen-drawings-draftingview)
- [NXOpen.Drawings.DraftingViewCollection](#nxopen-drawings-draftingviewcollection)
- [NXOpen.Drawings.DrawingCompareSettingsBuilder](#nxopen-drawings-drawingcomparesettingsbuilder)
- [NXOpen.Drawings.DrawingFormatSheetBuilder](#nxopen-drawings-drawingformatsheetbuilder)
- [NXOpen.Drawings.DrawingRegion](#nxopen-drawings-drawingregion)
- [NXOpen.Drawings.DrawingRegionBuilder](#nxopen-drawings-drawingregionbuilder)
- [NXOpen.Drawings.DrawingRegionCollection](#nxopen-drawings-drawingregioncollection)
- [NXOpen.Drawings.DrawingRegionRulesBuilder](#nxopen-drawings-drawingregionrulesbuilder)
- [NXOpen.Drawings.DrawingSheet](#nxopen-drawings-drawingsheet)
- [NXOpen.Drawings.DrawingSheetBuilder](#nxopen-drawings-drawingsheetbuilder)
- [NXOpen.Drawings.DrawingSheetCollection](#nxopen-drawings-drawingsheetcollection)
- [NXOpen.Drawings.DrawingView](#nxopen-drawings-drawingview)
- [NXOpen.Drawings.DrawingViewBuilder](#nxopen-drawings-drawingviewbuilder)
- [NXOpen.Drawings.DrawingsPropertiesBuilder](#nxopen-drawings-drawingspropertiesbuilder)
- [NXOpen.Drawings.EditSectionLineSettingsBuilder](#nxopen-drawings-editsectionlinesettingsbuilder)
- [NXOpen.Drawings.EditViewLabelSettingsBuilder](#nxopen-drawings-editviewlabelsettingsbuilder)
- [NXOpen.Drawings.EditViewSettingsBuilder](#nxopen-drawings-editviewsettingsbuilder)
- [NXOpen.Drawings.FlatPatternObject](#nxopen-drawings-flatpatternobject)
- [NXOpen.Drawings.FlatPatternViewStyle](#nxopen-drawings-flatpatternviewstyle)
- [NXOpen.Drawings.GeneralViewStyle](#nxopen-drawings-generalviewstyle)
- [NXOpen.Drawings.GeneralWorkFlowBuilder](#nxopen-drawings-generalworkflowbuilder)
- [NXOpen.Drawings.HalfPictorialSectionLine](#nxopen-drawings-halfpictorialsectionline)
- [NXOpen.Drawings.HalfSectionLine](#nxopen-drawings-halfsectionline)
- [NXOpen.Drawings.HalfSectionLineBuilder](#nxopen-drawings-halfsectionlinebuilder)
- [NXOpen.Drawings.HiddenLinesViewStyle](#nxopen-drawings-hiddenlinesviewstyle)
- [NXOpen.Drawings.HiddenObjectsBuilder](#nxopen-drawings-hiddenobjectsbuilder)
- [NXOpen.Drawings.HingeLineBuilder](#nxopen-drawings-hingelinebuilder)
- [NXOpen.Drawings.InheritPmiViewStyle](#nxopen-drawings-inheritpmiviewstyle)
- [NXOpen.Drawings.MarkAsTemplateBuilder](#nxopen-drawings-markastemplatebuilder)
- [NXOpen.Drawings.MultipleViewPlacementBuilder](#nxopen-drawings-multipleviewplacementbuilder)
- [NXOpen.Drawings.OrderManager](#nxopen-drawings-ordermanager)
- [NXOpen.Drawings.OrientationViewStyle](#nxopen-drawings-orientationviewstyle)
- [NXOpen.Drawings.OrientedSectionLine](#nxopen-drawings-orientedsectionline)
- [NXOpen.Drawings.OrientedSectionLineBuilder](#nxopen-drawings-orientedsectionlinebuilder)
- [NXOpen.Drawings.OvtBuilder](#nxopen-drawings-ovtbuilder)
- [NXOpen.Drawings.ParentViewBuilder](#nxopen-drawings-parentviewbuilder)
- [NXOpen.Drawings.PerspectiveViewStyle](#nxopen-drawings-perspectiveviewstyle)
- [NXOpen.Drawings.PictorialSectionLine](#nxopen-drawings-pictorialsectionline)
- [NXOpen.Drawings.PointAndAngleSectionLine](#nxopen-drawings-pointandanglesectionline)
- [NXOpen.Drawings.PointAndAngleSectionLineBuilder](#nxopen-drawings-pointandanglesectionlinebuilder)
- [NXOpen.Drawings.PointToPointSectionLine](#nxopen-drawings-pointtopointsectionline)
- [NXOpen.Drawings.PointToPointSectionLineBuilder](#nxopen-drawings-pointtopointsectionlinebuilder)
- [NXOpen.Drawings.ProjectedView](#nxopen-drawings-projectedview)
- [NXOpen.Drawings.ProjectedViewBuilder](#nxopen-drawings-projectedviewbuilder)
- [NXOpen.Drawings.ProjectedViewOrientationBuilder](#nxopen-drawings-projectedvieworientationbuilder)
- [NXOpen.Drawings.ProjectedViewStyle](#nxopen-drawings-projectedviewstyle)
- [NXOpen.Drawings.RefineDisplayBuilder](#nxopen-drawings-refinedisplaybuilder)
- [NXOpen.Drawings.RemoveObjectsBuilder](#nxopen-drawings-removeobjectsbuilder)
- [NXOpen.Drawings.RenderSet](#nxopen-drawings-renderset)
- [NXOpen.Drawings.ReportBuilder](#nxopen-drawings-reportbuilder)
- [NXOpen.Drawings.RevolvedSectionLine](#nxopen-drawings-revolvedsectionline)
- [NXOpen.Drawings.RevolvedSectionLineBuilder](#nxopen-drawings-revolvedsectionlinebuilder)
- [NXOpen.Drawings.SecondaryGeometryInViewsBuilder](#nxopen-drawings-secondarygeometryinviewsbuilder)
- [NXOpen.Drawings.SectionInViewBuilder](#nxopen-drawings-sectioninviewbuilder)
- [NXOpen.Drawings.SectionLine](#nxopen-drawings-sectionline)
- [NXOpen.Drawings.SectionLineBuilder](#nxopen-drawings-sectionlinebuilder)
- [NXOpen.Drawings.SectionLineCollection](#nxopen-drawings-sectionlinecollection)
- [NXOpen.Drawings.SectionLineSegmentBuilder](#nxopen-drawings-sectionlinesegmentbuilder)
- [NXOpen.Drawings.SectionLineSegmentBuilderList](#nxopen-drawings-sectionlinesegmentbuilderlist)
- [NXOpen.Drawings.SectionLineSegmentPointBuilder](#nxopen-drawings-sectionlinesegmentpointbuilder)
- [NXOpen.Drawings.SectionLineSegmentPointListBuilder](#nxopen-drawings-sectionlinesegmentpointlistbuilder)
- [NXOpen.Drawings.SectionLineSegmentsBuilder](#nxopen-drawings-sectionlinesegmentsbuilder)
- [NXOpen.Drawings.SectionLineSettingsBuilder](#nxopen-drawings-sectionlinesettingsbuilder)
- [NXOpen.Drawings.SectionLineStyleBuilder](#nxopen-drawings-sectionlinestylebuilder)
- [NXOpen.Drawings.SectionView](#nxopen-drawings-sectionview)
- [NXOpen.Drawings.SectionViewBuilder](#nxopen-drawings-sectionviewbuilder)
- [NXOpen.Drawings.SectionViewStyle](#nxopen-drawings-sectionviewstyle)
- [NXOpen.Drawings.SelectDraftingView](#nxopen-drawings-selectdraftingview)
- [NXOpen.Drawings.SelectDraftingViewList](#nxopen-drawings-selectdraftingviewlist)
- [NXOpen.Drawings.SelectDrawingRegion](#nxopen-drawings-selectdrawingregion)
- [NXOpen.Drawings.SelectDrawingView](#nxopen-drawings-selectdrawingview)
- [NXOpen.Drawings.SelectDrawingViewList](#nxopen-drawings-selectdrawingviewlist)
- [NXOpen.Drawings.SelectModelViewBuilder](#nxopen-drawings-selectmodelviewbuilder)
- [NXOpen.Drawings.SelectRegionBuilder](#nxopen-drawings-selectregionbuilder)
- [NXOpen.Drawings.SelectSectionLine](#nxopen-drawings-selectsectionline)
- [NXOpen.Drawings.SettingsBuilder](#nxopen-drawings-settingsbuilder)
- [NXOpen.Drawings.ShadingViewStyle](#nxopen-drawings-shadingviewstyle)
- [NXOpen.Drawings.SheetBorderSettingsBuilder](#nxopen-drawings-sheetbordersettingsbuilder)
- [NXOpen.Drawings.SheetDraftingViewCollection](#nxopen-drawings-sheetdraftingviewcollection)
- [NXOpen.Drawings.SheetMarginSettingsBuilder](#nxopen-drawings-sheetmarginsettingsbuilder)
- [NXOpen.Drawings.SheetSectionLineCollection](#nxopen-drawings-sheetsectionlinecollection)
- [NXOpen.Drawings.SheetTemplateManager](#nxopen-drawings-sheettemplatemanager)
- [NXOpen.Drawings.SheetZoneReferenceBuilder](#nxopen-drawings-sheetzonereferencebuilder)
- [NXOpen.Drawings.SheetZoneSettingsBuilder](#nxopen-drawings-sheetzonesettingsbuilder)
- [NXOpen.Drawings.ShipDraftingViewLinesBuilder](#nxopen-drawings-shipdraftingviewlinesbuilder)
- [NXOpen.Drawings.ShipDraftingViewLinesBuilderList](#nxopen-drawings-shipdraftingviewlinesbuilderlist)
- [NXOpen.Drawings.ShipDraftingViewLinesViewStyle](#nxopen-drawings-shipdraftingviewlinesviewstyle)
- [NXOpen.Drawings.ShipGeneralArrangementViewLinesBuilder](#nxopen-drawings-shipgeneralarrangementviewlinesbuilder)
- [NXOpen.Drawings.ShipGeneralArrangementViewLinesBuilderList](#nxopen-drawings-shipgeneralarrangementviewlinesbuilderlist)
- [NXOpen.Drawings.ShipGeneralArrangementViewLinesViewStyle](#nxopen-drawings-shipgeneralarrangementviewlinesviewstyle)
- [NXOpen.Drawings.ShipbuildingLinesViewStyle](#nxopen-drawings-shipbuildinglinesviewstyle)
- [NXOpen.Drawings.SketchSectionLineBuilder](#nxopen-drawings-sketchsectionlinebuilder)
- [NXOpen.Drawings.SketchedHalfSectionLine](#nxopen-drawings-sketchedhalfsectionline)
- [NXOpen.Drawings.SketchedPointToPointSectionLine](#nxopen-drawings-sketchedpointtopointsectionline)
- [NXOpen.Drawings.SketchedSteppedSectionLine](#nxopen-drawings-sketchedsteppedsectionline)
- [NXOpen.Drawings.SmoothEdgesViewStyle](#nxopen-drawings-smoothedgesviewstyle)
- [NXOpen.Drawings.SpecifySectionLineBuilder](#nxopen-drawings-specifysectionlinebuilder)
- [NXOpen.Drawings.StandardViewsBuilder](#nxopen-drawings-standardviewsbuilder)
- [NXOpen.Drawings.SteppedSectionLine](#nxopen-drawings-steppedsectionline)
- [NXOpen.Drawings.SteppedSectionLineBuilder](#nxopen-drawings-steppedsectionlinebuilder)
- [NXOpen.Drawings.SvtBuilder](#nxopen-drawings-svtbuilder)
- [NXOpen.Drawings.ThreadsViewStyle](#nxopen-drawings-threadsviewstyle)
- [NXOpen.Drawings.TraceLinesViewStyle](#nxopen-drawings-tracelinesviewstyle)
- [NXOpen.Drawings.TrackDrawingChangesGeneralBuilder](#nxopen-drawings-trackdrawingchangesgeneralbuilder)
- [NXOpen.Drawings.TrackDrawingChangesReportFilterBuilder](#nxopen-drawings-trackdrawingchangesreportfilterbuilder)
- [NXOpen.Drawings.UpdateViewsBuilder](#nxopen-drawings-updateviewsbuilder)
- [NXOpen.Drawings.View2dOrientBuilder](#nxopen-drawings-view2dorientbuilder)
- [NXOpen.Drawings.ViewAlignment](#nxopen-drawings-viewalignment)
- [NXOpen.Drawings.ViewAlignmentBuilder](#nxopen-drawings-viewalignmentbuilder)
- [NXOpen.Drawings.ViewAlignmentCollection](#nxopen-drawings-viewalignmentcollection)
- [NXOpen.Drawings.ViewBoundaryBuilder](#nxopen-drawings-viewboundarybuilder)
- [NXOpen.Drawings.ViewBreak](#nxopen-drawings-viewbreak)
- [NXOpen.Drawings.ViewBreakBuilder](#nxopen-drawings-viewbreakbuilder)
- [NXOpen.Drawings.ViewBreakCollection](#nxopen-drawings-viewbreakcollection)
- [NXOpen.Drawings.ViewCenterCoordinateBuilder](#nxopen-drawings-viewcentercoordinatebuilder)
- [NXOpen.Drawings.ViewCommonViewLabelBuilder](#nxopen-drawings-viewcommonviewlabelbuilder)
- [NXOpen.Drawings.ViewCopyTo3dBuilder](#nxopen-drawings-viewcopyto3dbuilder)
- [NXOpen.Drawings.ViewCreationWizardBuilder](#nxopen-drawings-viewcreationwizardbuilder)
- [NXOpen.Drawings.ViewDetailLabelBuilder](#nxopen-drawings-viewdetaillabelbuilder)
- [NXOpen.Drawings.ViewLabelBuilder](#nxopen-drawings-viewlabelbuilder)
- [NXOpen.Drawings.ViewOrientationBuilder](#nxopen-drawings-vieworientationbuilder)
- [NXOpen.Drawings.ViewPlacementBuilder](#nxopen-drawings-viewplacementbuilder)
- [NXOpen.Drawings.ViewProjectedArrowSettingsBuilder](#nxopen-drawings-viewprojectedarrowsettingsbuilder)
- [NXOpen.Drawings.ViewProjectedLabelBuilder](#nxopen-drawings-viewprojectedlabelbuilder)
- [NXOpen.Drawings.ViewProjectedViewSettingsBuilder](#nxopen-drawings-viewprojectedviewsettingsbuilder)
- [NXOpen.Drawings.ViewProjectionBuilder](#nxopen-drawings-viewprojectionbuilder)
- [NXOpen.Drawings.ViewProjectionPlaneBuilder](#nxopen-drawings-viewprojectionplanebuilder)
- [NXOpen.Drawings.ViewScaleBuilder](#nxopen-drawings-viewscalebuilder)
- [NXOpen.Drawings.ViewSectionLabelBuilder](#nxopen-drawings-viewsectionlabelbuilder)
- [NXOpen.Drawings.ViewSectionLineBuilder](#nxopen-drawings-viewsectionlinebuilder)
- [NXOpen.Drawings.ViewSettingsBuilder](#nxopen-drawings-viewsettingsbuilder)
- [NXOpen.Drawings.ViewStyle](#nxopen-drawings-viewstyle)
- [NXOpen.Drawings.ViewStyleAECViewLinesBuilder](#nxopen-drawings-viewstyleaecviewlinesbuilder)
- [NXOpen.Drawings.ViewStyleAECViewLinesBuilderList](#nxopen-drawings-viewstyleaecviewlinesbuilderlist)
- [NXOpen.Drawings.ViewStyleBaseBuilder](#nxopen-drawings-viewstylebasebuilder)
- [NXOpen.Drawings.ViewStyleBuilder](#nxopen-drawings-viewstylebuilder)
- [NXOpen.Drawings.ViewStyleDetailBuilder](#nxopen-drawings-viewstyledetailbuilder)
- [NXOpen.Drawings.ViewStyleFPCalloutConfigBuilder](#nxopen-drawings-viewstylefpcalloutconfigbuilder)
- [NXOpen.Drawings.ViewStyleFPCalloutsBuilder](#nxopen-drawings-viewstylefpcalloutsbuilder)
- [NXOpen.Drawings.ViewStyleFPCurvesBuilder](#nxopen-drawings-viewstylefpcurvesbuilder)
- [NXOpen.Drawings.ViewStyleFrameBarBuilder](#nxopen-drawings-viewstyleframebarbuilder)
- [NXOpen.Drawings.ViewStyleGeneralBuilder](#nxopen-drawings-viewstylegeneralbuilder)
- [NXOpen.Drawings.ViewStyleHiddenLinesBuilder](#nxopen-drawings-viewstylehiddenlinesbuilder)
- [NXOpen.Drawings.ViewStyleInheritPmiBuilder](#nxopen-drawings-viewstyleinheritpmibuilder)
- [NXOpen.Drawings.ViewStyleOrientationBuilder](#nxopen-drawings-viewstyleorientationbuilder)
- [NXOpen.Drawings.ViewStylePerspectiveBuilder](#nxopen-drawings-viewstyleperspectivebuilder)
- [NXOpen.Drawings.ViewStyleProjectedBuilder](#nxopen-drawings-viewstyleprojectedbuilder)
- [NXOpen.Drawings.ViewStyleSecondaryComponentsBuilder](#nxopen-drawings-viewstylesecondarycomponentsbuilder)
- [NXOpen.Drawings.ViewStyleSectionBuilder](#nxopen-drawings-viewstylesectionbuilder)
- [NXOpen.Drawings.ViewStyleSectionConstraintsBuilder](#nxopen-drawings-viewstylesectionconstraintsbuilder)
- [NXOpen.Drawings.ViewStyleShadingBuilder](#nxopen-drawings-viewstyleshadingbuilder)
- [NXOpen.Drawings.ViewStyleShipbuildingLinesBuilder](#nxopen-drawings-viewstyleshipbuildinglinesbuilder)
- [NXOpen.Drawings.ViewStyleShipbuildingLinesBuilderList](#nxopen-drawings-viewstyleshipbuildinglinesbuilderlist)
- [NXOpen.Drawings.ViewStyleSmoothEdgesBuilder](#nxopen-drawings-viewstylesmoothedgesbuilder)
- [NXOpen.Drawings.ViewStyleThreadsBuilder](#nxopen-drawings-viewstylethreadsbuilder)
- [NXOpen.Drawings.ViewStyleTraceLinesBuilder](#nxopen-drawings-viewstyletracelinesbuilder)
- [NXOpen.Drawings.ViewStyleVirtualIntersectionsBuilder](#nxopen-drawings-viewstylevirtualintersectionsbuilder)
- [NXOpen.Drawings.ViewStyleVisibleLinesBuilder](#nxopen-drawings-viewstylevisiblelinesbuilder)
- [NXOpen.Drawings.ViewWorkflowBuilder](#nxopen-drawings-viewworkflowbuilder)
- [NXOpen.Drawings.ViewingDirectionArrow](#nxopen-drawings-viewingdirectionarrow)
- [NXOpen.Drawings.ViewingDirectionArrowLabel](#nxopen-drawings-viewingdirectionarrowlabel)
- [NXOpen.Drawings.VirtualIntersectionsViewStyle](#nxopen-drawings-virtualintersectionsviewstyle)
- [NXOpen.Drawings.VisibleAndHiddenLinesColorFontWidthBuilder](#nxopen-drawings-visibleandhiddenlinescolorfontwidthbuilder)
- [NXOpen.Drawings.VisibleLinesViewStyle](#nxopen-drawings-visiblelinesviewstyle)
- [NXOpen.Drawings.VisualDrawingComparePrefsBuilder](#nxopen-drawings-visualdrawingcompareprefsbuilder)

---

## NXOpen.Drawings.AddObjectsToRegionBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49392.html

Creates the builder for associating the symbols from library to the region

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetMasterSymbolFilePaths(string [] symbolPath)` | `unsafe void` | Set the master symbol pathsMore... |
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
| `SelectedRegion[get]` | `unsafeNXOpen.Drawings.SelectDrawingRegion` | Returns the get selected regionMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.AddRemoveBoxViewBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49396.html

This class is used to construct the add remove box view Builder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Mode[get, set]` | `unsafeNXOpen.Drawings.AddRemoveBoxViewBuilder.ModeType` | Returns or sets the mode typeMore... |
| `SelectedView[get, set]` | `unsafeNXOpen.ModelingView` | Returns or sets the selected viewMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.AnnotationSettingsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49400.html

Represents aDrawings.AnnotationSettingsBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SaveAnnotationType(NXOpen.Drawings.AnnotationSettingsBuilder.AnnotationTypeEnumannType, bool annValue)` | `unsafe void` | API used to save settings dataMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `ConvertToOriginalModelView[get, set]` | `unsafe bool` | Returns or sets the convert to original model viewMore... |
| `LinearDimensionTolerance[get, set]` | `unsafe double` | Returns or sets the linear dimension toleranceMore... |
| `PreserveDraftingLayer[get, set]` | `unsafe bool` | Returns or sets the preserve drafting layerMore... |
| `PreserveHiddenStatus[get, set]` | `unsafe bool` | Returns or sets the preserve hidden statusMore... |
| `ProcessObjectsHidden[get, set]` | `unsafe bool` | Returns or sets the process objects hiddenMore... |
| `Units[get, set]` | `unsafeNXOpen.Drawings.AnnotationSettingsBuilder.UnitsEnum` | Returns or sets the unitsMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.AssociativeAngleBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49404.html

This builder allows the user to create an associative or non-associative angle by measuring between a combination of two objects or vectors evaluated on a specified plane, or by an expression

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `AlternateAngle()` | `unsafe void` | The alternate angleMore... |
| `CreateScalarObject()` | `unsafe void` | Creates a scalar object for an associative angleMore... |
| `CreateScalarObjectFromData(NXOpen.ScalarscalarTag, double angleValue)` | `unsafe void` | Creates scalar object for an associative angle using data from existing scalar object or angle value.More... |
| `SetIsMeasure(bool isMeasure)` | `unsafe void` | Sets IsMeasure flag indicating angle is result of a measureMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Angle[get]` | `unsafeNXOpen.Expression` | Returns the angleMore... |
| `AngleValue[get, set]` | `unsafe double` | Returns or sets the angle valueMore... |
| `Associative[get, set]` | `unsafe bool` | Returns or sets the associative flagMore... |
| `EvaluationPlane[get, set]` | `unsafeNXOpen.Drawings.AssociativeAngleBuilder.EvaluationPlaneType` | Returns or sets the evaluation plane typeMore... |
| `FirstMapView[get, set]` | `unsafeNXOpen.View` | Returns or sets the first map viewMore... |
| `FirstObject[get]` | `unsafeNXOpen.SelectNXObject` | Returns the first objectMore... |
| `FirstObjectType[get, set]` | `unsafeNXOpen.Drawings.AssociativeAngleBuilder.ObjectType` | Returns or sets the first object typeMore... |
| `FirstVector[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the first vectorMore... |
| `Plane[get, set]` | `unsafeNXOpen.Plane` | Returns or sets the planeMore... |
| `ScalarObject[get, set]` | `unsafeNXOpen.Scalar` | Returns or sets the scalar objectMore... |
| `SecondMapView[get, set]` | `unsafeNXOpen.View` | Returns or sets the second map viewMore... |
| `SecondObject[get]` | `unsafeNXOpen.SelectNXObject` | Returns the second objectMore... |
| `SecondObjectType[get, set]` | `unsafeNXOpen.Drawings.AssociativeAngleBuilder.ObjectType` | Returns or sets the second object typeMore... |
| `SecondVector[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the second vectorMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.AutomationBookletBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49408.html

Represents aNXOpen.Drawings.AutomationBookletBuilder

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
| `HiddenLineColorFontWidth[get]` | `unsafeNXOpen.LineColorFontWidthBuilder` | Returns the hidden line color font widthMore... |
| `VisibleLineColorFontWidth[get]` | `unsafeNXOpen.LineColorFontWidthBuilder` | Returns the visible line color font widthMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.AutomationTemplateRegionBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49412.html

Represents aNXOpen.Drawings.AutomationTemplateRegionBuilder

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
| `DisplayRegionLabel[get, set]` | `unsafe bool` | Returns or sets the flag to indicate if the display region label should be displayedMore... |
| `DisplayTemplatePart[get, set]` | `unsafe bool` | Returns or sets the value that determines whether or not regions should be displayed in a non-template part.More... |
| `LineColorFontWidth[get]` | `unsafeNXOpen.LineColorFontWidthBuilder` | Returns the value that specifies the color font width of region objectslineMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.BaseHalfSectionLine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49416.html

Represents a Base Half Section Line


---

## NXOpen.Drawings.BasePointToPointSectionLine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49420.html

Represents a Base Point to Point Section Line


---

## NXOpen.Drawings.BaseSteppedSectionLine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49424.html

Represents a Base Stepped Section Line


---

## NXOpen.Drawings.BaseView

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49428.html

Represents a Base View


---

## NXOpen.Drawings.BaseViewBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49432.html

Represents aNXOpen.Drawings.BaseViewbuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `HiddenObjects[get]` | `unsafeNXOpen.Drawings.HiddenObjectsBuilder` | Returns the list of objects to not show in the viewMore... |
| `NonSectionedObjects[get]` | `unsafeNXOpen.Drawings.HiddenObjectsBuilder` | Returns the list of objects to not section in the viewMore... |
| `Placement[get]` | `unsafeNXOpen.Drawings.ViewPlacementBuilder` | Returns the view placementMore... |
| `Scale[get]` | `unsafeNXOpen.Drawings.ViewScaleBuilder` | Returns the view scaleMore... |
| `SecondaryComponents[get]` | `unsafeNXOpen.Drawings.DraftingComponentSelectionBuilder` | Returns the list of secondary objects in the viewMore... |
| `SelectModelView[get]` | `unsafeNXOpen.Drawings.SelectModelViewBuilder` | Returns the model viewMore... |
| `Style[get]` | `unsafeNXOpen.Drawings.ViewStyleBuilder` | Returns the view styleMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.BaseViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49436.html

Represents set of Base View Style Preferences applicable to drafting views

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `LoadModelFromPart(string loadPartName, bool loadPartToggle)` | `unsafe void` | To load the assemblies arrangement part file.More... |
| `SetAssemblyArrangement(string config)` | `unsafe void` | Sets the configuration for the arrangement in assembly after an arrangement part file is loaded.More... |
| `SetFacetedRepresentation(bool isFacetedRepresentation)` | `unsafe void` | The status of faceted representation, if True the clipping bounds are inherited, else the imported model view is placed on the drawing with an Automatic Rectangular Boundary.More... |
| `SetInheritClippingBoundary(bool isInheritClippingBoundary)` | `unsafe void` | The status of inherit clipping boundary, if True the model view's clipping boundary are inherited when model view is imported onto the drawing, else the imported model view is placed on the drawing with an Automatic Rectangular Boundary.More... |
| `SetTransferAnnotation(bool isTransferAnnotation)` | `unsafe void` | The status of transfer annotation controls whether or not annotations created in a model view are transferred to the drawing when a view is imported.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.BorderAndZoneStyleBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49440.html

Represents the Border and Zone Style Builder which manages all the style attributes related * to sheet borders, sheet margins and sheet zones

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `InheritSettingsFromCustomerDefault()` | `unsafe void` | Inherit settings from customer defaultMore... |
| `InheritSettingsFromPreferences()` | `unsafe void` | Inherit settings from preferenceMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `BorderAndZoneStandard[get, set]` | `unsafe int` | Returns or sets the borders and zones standardMore... |
| `SheetBorderSettingsStyle[get]` | `unsafeNXOpen.Drawings.SheetBorderSettingsBuilder` | Returns the drawing sheet border settings builderMore... |
| `SheetMarginSettingsStyle[get]` | `unsafeNXOpen.Drawings.SheetMarginSettingsBuilder` | Returns the drawing sheet margin settings builderMore... |
| `SheetZoneSettingsStyle[get]` | `unsafeNXOpen.Drawings.SheetZoneSettingsBuilder` | Returns the drawing sheet zone settings builderMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.BordersAndZones

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49444.html

Represents Borders and Zones


---

## NXOpen.Drawings.BordersAndZonesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49448.html

Builder for creating Borders and Zones

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `BorderAndZoneStyle[get]` | `unsafeNXOpen.Drawings.BorderAndZoneStyleBuilder` | Returns the border and zone style builderMore... |
| `BottomMargin[get, set]` | `unsafe double` | Returns or sets the bottom marginMore... |
| `CenteringMarkExtension[get, set]` | `unsafe double` | Returns or sets the centering mark extensionMore... |
| `CreateBorders[get, set]` | `unsafe bool` | Returns or sets the create bordersMore... |
| `CreateTrimmingMarks[get, set]` | `unsafe bool` | Returns or sets the create trimming marksMore... |
| `CreateZoneLabels[get, set]` | `unsafe bool` | Returns or sets the create zone labelsMore... |
| `CreateZoneMarking[get, set]` | `unsafe bool` | Returns or sets the create zone markingMore... |
| `HorizontalCenteringMark[get, set]` | `unsafeNXOpen.Drawings.BordersAndZonesBuilder.HorizontalCenteringMarkType` | Returns or sets the horizontal centering markMore... |
| `HorizontalSize[get, set]` | `unsafe double` | Returns or sets the horizontal size of the zonesMore... |
| `LabelFont[get, set]` | `unsafe int` | Returns or sets the label fontMore... |
| `LabelHeight[get, set]` | `unsafe double` | Returns or sets the label heightMore... |
| `LeftMargin[get, set]` | `unsafe double` | Returns or sets the left marginMore... |
| `MarkingHeight[get, set]` | `unsafe double` | Returns or sets the marking heightMore... |
| `Method[get, set]` | `unsafeNXOpen.Drawings.BordersAndZonesBuilder.ZoneMethod` | Returns or sets the method of creation of zonesMore... |
| `Origin[get, set]` | `unsafeNXOpen.Drawings.BordersAndZonesBuilder.ZoneOrigin` | Returns or sets the zone origin typeMore... |
| `RightMargin[get, set]` | `unsafe double` | Returns or sets the right marginMore... |
| `TopMargin[get, set]` | `unsafe double` | Returns or sets the top marginMore... |
| `TrimmingMarkLength[get, set]` | `unsafe double` | Returns or sets the trimming mark lengthMore... |
| `TrimmingMarkThickness[get, set]` | `unsafe double` | Returns or sets the trimming mark thicknessMore... |
| `VerticalCenteringMark[get, set]` | `unsafeNXOpen.Drawings.BordersAndZonesBuilder.VerticalCenteringMarkType` | Returns or sets the vertical centering markMore... |
| `VerticalSize[get, set]` | `unsafe double` | Returns or sets the vertical size of the zonesMore... |
| `Width[get, set]` | `unsafe double` | Returns or sets the width of the borderMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.BordersAndZonesCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49452.html

Represents a collection ofNXOpen.Drawings.BordersAndZonesobjects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateBordersAndZonesBuilder(NXOpen.Drawings.BordersAndZonesbordersAndZones)` | `unsafeNXOpen.Drawings.BordersAndZonesBuilder` | Creates a borders and zones builderMore... |
| `FindObject(string name)` | `unsafeNXOpen.Drawings.BordersAndZones` | Finds theNXOpen.Drawings.BordersAndZoneswith the given name.More... |
| `ToArray()` | `NXOpen.Drawings.BordersAndZones[]` | Returns an array ofNXOpen.Drawings.BordersAndZonesobjects.More... |
| `GetEnumerator()` | `IEnumerator` | Returns an enumerator that iterates through a collection.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |
| `EnumerateMoveNext(refTagcurrentTag, byte [] state)` | `override int` | Advances the enumerator to the next element of the collection.More... |
| `initialize()` | `new void` | <exclude>More... |
| `initialize()` | `void` | <exclude>More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.BrokenViewBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49456.html

This class is used to construct the broken view Builder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Amplitude[get]` | `unsafeNXOpen.Expression` | Returns the break line amplitudeMore... |
| `BreakLine1Anchor[get, set]` | `unsafeNXOpen.Point` | Returns or sets the object specifying the position of the first break lineMore... |
| `BreakLine1ModelAnchor[get, set]` | `unsafeNXOpen.Point` | Returns or sets the object specifying the position of the first break lineMore... |
| `BreakLine1Offset[get]` | `unsafeNXOpen.Expression` | Returns the offset from the object locating the first break lineMore... |
| `BreakLine2Anchor[get, set]` | `unsafeNXOpen.Point` | Returns or sets the object specifying the position of the second break line.More... |
| `BreakLine2ModelAnchor[get, set]` | `unsafeNXOpen.Point` | Returns or sets the object specifying the position of the second break line.More... |
| `BreakLine2Offset[get]` | `unsafeNXOpen.Expression` | Returns the offset from the object locating the second break line.More... |
| `BreakLineType[get, set]` | `unsafeNXOpen.Drawings.BrokenViewBuilder.BreakLineStyle` | Returns or sets the break line typeMore... |
| `BreakType[get, set]` | `unsafeNXOpen.Drawings.BrokenViewBuilder.TypeBreak` | Returns or sets the break typeMore... |
| `BreakVisibility[get, set]` | `unsafe bool` | Returns or sets the view break visibilitityMore... |
| `Color[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the break line colorMore... |
| `CrossHatch[get]` | `unsafeNXOpen.Annotations.HatchFillSettingsBuilder` | Returns the HatchFillSettingMore... |
| `DirectionType[get, set]` | `unsafeNXOpen.Drawings.BrokenViewBuilder.TypeDirection` | Returns or sets the direction typeMore... |
| `DirectionVector[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the direction vector.More... |
| `ExistingCurve[get]` | `unsafeNXOpen.ScCollector` | Returns the curve to use as existing curveMore... |
| `Extension1[get]` | `unsafeNXOpen.Expression` | Returns the break line extension (top/right) beyond geometryMore... |
| `Extension2[get]` | `unsafeNXOpen.Expression` | Returns the break line extension (bottom/left) beyond geometryMore... |
| `Gap[get]` | `unsafeNXOpen.Expression` | Returns the gap on the sheet between the two break linesMore... |
| `IsBreakLine1Associative[get, set]` | `unsafe bool` | Returns or sets the associative positionning of the first break lineMore... |
| `IsBreakLine2Associative[get, set]` | `unsafe bool` | Returns or sets the associative positionning of the second break line.More... |
| `MasterView[get]` | `unsafeNXOpen.Drawings.SelectDraftingView` | Returns the master viewMore... |
| `Repetition[get, set]` | `unsafe int` | Returns or sets the repetition of the break line patternMore... |
| `Suppress[get, set]` | `unsafe bool` | Returns or sets the view break suppress statusMore... |
| `Width[get, set]` | `unsafeNXOpen.Drawings.BrokenViewBuilder.LineWidth` | Returns or sets the curve width of the break lineMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.CompareReportBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49460.html

Represents aNXOpen.Drawings.CompareReportBuilderbuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetChangesSummary()` | `unsafe string []` | Returns the changes summary of reportMore... |
| `GetDetailSummary()` | `unsafe string []` | Returns the detail summary of reportMore... |
| `GetSummary()` | `unsafe string []` | Returns the summaryMore... |
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
| `SummaryStatusLine[get]` | `unsafe string` | Returns the report summary status lineMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ConversionProcessSettingsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49464.html

Represents aDrawings.ConversionProcessSettingsBuilder

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
| `ActionOnError[get, set]` | `unsafeNXOpen.Drawings.ConversionProcessSettingsBuilder.ActionOnErrorEnum` | Returns or sets the action on errorMore... |
| `ConfigurationFile[get, set]` | `unsafe string` | Returns or sets the configuration file browserMore... |
| `CreateInMasterModelPart[get, set]` | `unsafe bool` | Returns or sets the create in master model part optionMore... |
| `ErrorLimit[get, set]` | `unsafe int` | Returns or sets the error limit integerMore... |
| `JTGeometryTolerance[get, set]` | `unsafe double` | Returns or sets the geometry toleranceMore... |
| `JTPartNameAttribute[get, set]` | `unsafe string` | Returns or sets the JT part nameMore... |
| `LogFileLocation[get, set]` | `unsafe string` | Returns or sets the log file location folderMore... |
| `MultiCADAssembly[get, set]` | `unsafe bool` | Returns or sets the multi-CAD assemblyMore... |
| `SaveAsLocation[get, set]` | `unsafe string` | Returns or sets the save as file browserMore... |
| `SourcePartNameAttribute[get, set]` | `unsafe string` | Returns or sets the Source part nameMore... |
| `StoreLogFileInTeamCenter[get, set]` | `unsafe bool` | Returns or sets the store log file in teamcenterMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ConvertDraftingContentsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49468.html

Represents aDrawings.ConvertDraftingContentsBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetContextAssembly(string contextAssembly)` | `unsafe void` | Context assembly part file pathMore... |
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
| `ConfigurationFile[get, set]` | `unsafe string` | Returns or sets the configuration fileMore... |
| `OpenConvertedPmiDestinationPart[get, set]` | `unsafe bool` | Returns or sets the option to open converted pmi destination partMore... |
| `SelectDraftingSheet[get]` | `unsafeNXOpen.SelectViewList` | Returns the select drafting sheet block.More... |
| `SelectDraftingView[get]` | `unsafeNXOpen.Drawings.SelectDraftingViewList` | Returns the select drafting view blockMore... |
| `SelectionType[get, set]` | `unsafeNXOpen.Drawings.ConvertDraftingContentsBuilder.SelectConversionEntityType` | Returns or sets the selection typeMore... |
| `SelectObjectsToConvert[get]` | `unsafeNXOpen.SelectNXObjectList` | Returns the select objects to convertMore... |
| `SettingsBuilder[get]` | `unsafeNXOpen.Drawings.SettingsBuilder` | Returns the settingsMore... |
| `UseContextAssembly[get, set]` | `unsafe bool` | Returns or sets the use context assemblyMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ConvertToPMIBuilderManager

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49472.html

RepresentsNXOpen.Drawings.ConvertToPMIBuilderManager

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateConvertDraftingContentsBuilder()` | `unsafeNXOpen.Drawings.ConvertDraftingContentsBuilder` | Creator for Drawing to PMI BuilderMore... |
| `CreateReportBuilder()` | `unsafeNXOpen.Drawings.ReportBuilder` | Creator for Drawing to PMI Report BuilderMore... |
| `DeleteConversionReport(int reportIndex)` | `unsafe void` | API used to delete drawing to PMI conversion reportMore... |
| `DeleteConvertedData(int reportIndex)` | `unsafe void` | API used to delete drawing to PMI conversion dataMore... |
| `GetConversionReportsCount()` | `unsafe int` | API used to get count of drawing to PMI conversion reportsMore... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.CustomViewSettingsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49476.html

this class represents the "this class represents Drawings

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `DelayUpdateOnCreation[get, set]` | `unsafe bool` | Returns or sets the delay update on creationMore... |
| `DelayViewUpdate[get, set]` | `unsafe bool` | Returns or sets the delay view updateMore... |
| `HiddenLinesColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the hidden lines colorMore... |
| `HiddenLinesFont[get, set]` | `unsafeNXOpen.Drawings.CustomViewSettingsBuilder.Font` | Returns or sets the hidden lines fontMore... |
| `HiddenLinesWidth[get, set]` | `unsafeNXOpen.Drawings.CustomViewSettingsBuilder.Width` | Returns or sets the hidden line hidden fontMore... |
| `InterferingSolids[get, set]` | `unsafeNXOpen.Drawings.CustomViewSettingsBuilder.Interfering` | Returns or sets the interfering solidsMore... |
| `MinimumPitch[get, set]` | `unsafe double` | Returns or sets the minimum pitchMore... |
| `RenderTrueHiddenLine[get, set]` | `unsafe bool` | Returns or sets the render true hidden lineMore... |
| `ShowAdjacentBlends[get, set]` | `unsafe bool` | Returns or sets the show adjacent blendsMore... |
| `ShowCenterLines[get, set]` | `unsafe bool` | Returns or sets the show center linesMore... |
| `ShowCheckBoundaryStatus[get, set]` | `unsafe bool` | Returns or sets the show check boundary statusMore... |
| `ShowEdgesHiddenByEdges[get, set]` | `unsafe bool` | Returns or sets the show edges hidden by edgesMore... |
| `ShowHiddenLines[get, set]` | `unsafe bool` | Returns or sets the show hidden linesMore... |
| `ShowSelfHiddenLines[get, set]` | `unsafe bool` | Returns or sets the show self hidden linesMore... |
| `ShowSmoothEdgeEndGapsLock[get, set]` | `unsafe bool` | Returns or sets the show end gaps lockMore... |
| `ShowSmoothEdgeEndGapsValue[get, set]` | `unsafe double` | Returns or sets the show end gaps valueMore... |
| `ShowSmoothEdges[get, set]` | `unsafe bool` | Returns or sets the show smooth edgesMore... |
| `ShowTraceLines[get, set]` | `unsafe bool` | Returns or sets the show trace linesMore... |
| `ShowUVGrids[get, set]` | `unsafe bool` | Returns or sets the show uvgridsMore... |
| `ShowVIEndGapsLock[get, set]` | `unsafe bool` | Returns or sets the show end gaps lockMore... |
| `ShowVIEndGapsValue[get, set]` | `unsafe double` | Returns or sets the show end gaps valueMore... |
| `ShowVirtualIntersections[get, set]` | `unsafe bool` | Returns or sets the show virtual intersectionsMore... |
| `SmallFeatures[get, set]` | `unsafeNXOpen.Drawings.CustomViewSettingsBuilder.Features` | Returns or sets the small featuresMore... |
| `SmoothEdgeColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the smooth edge color pickMore... |
| `SmoothEdgeFont[get, set]` | `unsafeNXOpen.Drawings.CustomViewSettingsBuilder.Font` | Returns or sets the smooth edge line fontMore... |
| `SmoothEdgeWidth[get, set]` | `unsafeNXOpen.Drawings.CustomViewSettingsBuilder.Width` | Returns or sets the smooth edges line hidden fontMore... |
| `ThreadStandard[get, set]` | `unsafeNXOpen.Drawings.CustomViewSettingsBuilder.ThreadStandards` | Returns or sets the thread standardMore... |
| `TraceLineCreateGapsLock[get, set]` | `unsafe bool` | Returns or sets the trace line create gaps lockMore... |
| `TraceLineCreateGapsValue[get, set]` | `unsafe double` | Returns or sets the trace line create gaps valueMore... |
| `TraceLineHiddenColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the trace line hidden colorMore... |
| `TraceLineHiddenFont[get, set]` | `unsafeNXOpen.Drawings.CustomViewSettingsBuilder.Font` | Returns or sets the trace line hidden fontMore... |
| `TraceLineHiddenWidth[get, set]` | `unsafeNXOpen.Drawings.CustomViewSettingsBuilder.Width` | Returns or sets the trace line hidden WidthMore... |
| `TraceLineVisibleColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the trace line visible colorMore... |
| `TraceLineVisibleFont[get, set]` | `unsafeNXOpen.Drawings.CustomViewSettingsBuilder.Font` | Returns or sets the trace line visible fontMore... |
| `TraceLineVisibleWidth[get, set]` | `unsafeNXOpen.Drawings.CustomViewSettingsBuilder.Width` | Returns or sets the trace line visible fontMore... |
| `VirtualInterSectionColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the virtual inter section colorMore... |
| `VirtualInterSectionFont[get, set]` | `unsafeNXOpen.Drawings.CustomViewSettingsBuilder.Font` | Returns or sets the virtual inter section fontMore... |
| `VirtualInterSectionWidth[get, set]` | `unsafeNXOpen.Drawings.CustomViewSettingsBuilder.Width` | Returns or sets the virtual inter section widthMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.DetailView

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49480.html

Represents a Detail View

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `LogUpdate(int reason)` | `unsafe void` | Notify detail view update.More... |
| `ActivateForSketching()` | `unsafe void` | Sets this drafting view as the active sketch view.More... |
| `CalculateMinMaxBox(outNXOpen.Point3dminimumPoint, outNXOpen.Point3dmaximumPoint)` | `unsafe void` | Returns the absolute min-max box that contains all the entities in the view.More... |
| `CheckForInvalidParentModelView()` | `unsafe void` | Checks the view's validity by looking at the parent model viewMore... |
| `Commit()` | `unsafe void` | Commits and applies all the settings likeNXOpen.Drawings.ViewStyleto the View.More... |
| `GetBrokenViewDecoration()` | `unsafeNXOpen.Drawings.DraftingView` | Return the decoration view of a slave or a master view.More... |
| `GetBrokenViewInternalViews(outNXOpen.Drawings.DraftingView[] views)` | `unsafe void` | Returns an array of views representing the internal views of broken view.More... |
| `GetBrokenViewMaster()` | `unsafeNXOpen.Drawings.DraftingView` | Return the master view of a slave or a decoration view.More... |
| `GetDraftingSketches()` | `unsafeNXOpen.Sketch[]` | Returns all draftingNXOpen.Sketches of the view.More... |
| `GetDrawingReferencePoint()` | `unsafeNXOpen.Point3d` | Returns the view origin(location).More... |
| `GetToolMarkers(outNXOpen.Drawings.FlatPatternObject[] markers)` | `unsafe void` | Returns an array of pointers to objects representing the tool markers in the view.More... |
| `HideComponents(NXOpen.NXObject[] components)` | `unsafe void` | Hides the specified components in the view.More... |
| `HideViewBorder()` | `unsafe void` | Hide the view border of the broken view.More... |
| `MoveView(NXOpen.Point3ddrawingReferencePoint)` | `unsafe void` | Sets the view origin at the provided location.More... |
| `RestoreViewBorder()` | `unsafe void` | Restores the view border from the dashed line to the normal line for cut operationMore... |
| `SetDeleteSectionLine(bool deleteSectionLine)` | `unsafe void` | Set the section line delete option, If false section line will not be deleted with section viewMore... |
| `SetDrawingReferencePoint(NXOpen.Point3ddrawingReferencePoint)` | `unsafe void` | Sets the view origin at the provided location.More... |
| `ShowComponents(NXOpen.NXObject[] components)` | `unsafe void` | Shows the specified components in the view.More... |
| `ShowViewBorder()` | `unsafe void` | Show the view border of the broken view.More... |
| `Update()` | `unsafe void` | Updates the drawing member view on a drawing.More... |
| `UpdateAutomaticViewBound()` | `unsafe void` | Recalculates and updates the view boundary of a drawing member viewMore... |
| `UpdateAutomaticViewBound(bool updateDependent)` | `unsafe void` | Recalculates and updates the view boundary of a drawing member view and update the boundary dependent objectsMore... |
| `AskVisibleObjects()` | `unsafeNXOpen.DisplayableObject[]` | Returns an array of objects visible in a view.More... |
| `ChangePerspective(bool changeViewToPerspective)` | `unsafe void` | Changes a view from an orthographic view to a perspective view, or from a perspective view to an orthographic view.More... |
| `Concatenate(NXOpen.Point3dtranslation)` | `unsafe void` | Concatenates the given translation with the previous viewing transformation of the specified view.More... |
| `Concatenate(double scale)` | `unsafe void` | Concatenates the given scale with the previous viewing transformation of the specified view.More... |
| `Concatenate(NXOpen.Point3dtranslation, double scale)` | `unsafe void` | Concatenates the given translation and scale with the previous viewing transformation of the specified view.More... |
| `Concatenate(NXOpen.Point3dcenterOfRotation,NXOpen.Vector3drotationAxis, double angle)` | `unsafe void` | Concatenates the given rotation with the previous viewing transformation of the specified view.More... |
| `Concatenate(NXOpen.Point3dtranslation,NXOpen.Point3dcenterOfRotation,NXOpen.Vector3drotationAxis, double angle)` | `unsafe void` | Concatenates the given translation and rotation with the previous viewing transformation of the specified view.More... |
| `Concatenate(double scale,NXOpen.Point3dcenterOfRotation,NXOpen.Vector3drotationAxis, double angle)` | `unsafe void` | Concatenates the given scale and rotation with the previous viewing transformation of the specified view.More... |
| `Concatenate(NXOpen.Point3dtranslation, double scale,NXOpen.Point3dcenterOfRotation,NXOpen.Vector3drotationAxis, double angle)` | `unsafe void` | Concatenates the given translation, scale and rotation with the previous viewing transformation of the specified view.More... |
| `EnableNavigationFlyThrough(bool isEnable)` | `unsafe void` | Enables Fly-through by virtually placing you as a first-person observer in the view.More... |
| `Expand()` | `unsafe void` | Expands the specified view to fill as much of the layout which contains the view as possible, without changing the aspect ratio of the view.More... |
| `Fit()` | `unsafe void` | Adjusts the bounds of a given view so that it fully encompasses the extents of the model geometry.More... |
| `FitAfterShowOrHide(NXOpen.View.ShowOrHideTypetype)` | `unsafe void` | Adjusts the bounds of a given view conditionally so that it fully encompasses the extents of the model geometry.More... |
| `FitToObjects(NXOpen.IFitTo[] objects)` | `unsafe void` | Adjusts the bounds of a given view so that it fully encompasses the extents of the given objects.More... |
| `FlyToObjects(NXOpen.INXObject[] objects)` | `unsafe void` | Fly to the given objects.More... |
| `GetAxis(NXOpen.XYZAxisxYZAxis)` | `unsafeNXOpen.Vector3d` | Returns one of the view axes.More... |
| `GetExpandedScale()` | `unsafe double` | Returns the view scale, including any expansion factor.More... |
| `HasPreview()` | `unsafe bool` | Returns whether or not the given view has a preview.More... |
| `IsNavigationFlyThroughEnabled()` | `unsafe bool` | Returns whether or not Fly-through is enabled.More... |
| `MakeWork()` | `unsafe void` | Makes the given view the work view.More... |
| `NavigationFlyThrough(NXOpen.Point3dstartPoint,NXOpen.Point3dstartEnd)` | `unsafe void` | In Fly-through, fly from start point and ends at end point.More... |
| `NavigationFlyThroughWithScale(double relativeScale)` | `unsafe void` | In Fly-through, fly use relative scale.More... |
| `Orient(NXOpen.Matrix3x3matrix)` | `unsafe void` | Changes the view orientation relative to the specified absolute coordinate system.More... |
| `Orient(NXOpen.View.CannedviewName,NXOpen.View.ScaleAdjustmentviewScale)` | `unsafe void` | Changes the view orientation to a specified canned view.More... |
| `Orient(string viewName,NXOpen.View.ScaleAdjustmentviewScale)` | `unsafe void` | Changes the view orientation to a specified view.More... |
| `PanToObjects(NXOpen.INXObject[] objects)` | `unsafe void` | Pans and centers the view to the given objects.More... |
| `Regenerate()` | `unsafe void` | Regenerates the display of given view.More... |
| `Restore()` | `unsafe bool` | Restores a view to its last remembered rotation, scale and translation.More... |
| `RestoreNavigationHomeView()` | `unsafe void` | Restore and transitions from the current view to the home view.More... |
| `Rotate(NXOpen.Matrix3x3matrix)` | `unsafe void` | Rotates the view by concatenating the given matrix to the existing rotation matrix of the view.More... |
| `Rotate(NXOpen.Point3dorigin,NXOpen.Vector3dvector, double angle)` | `unsafe void` | Rotates the specified view using the specified origin of rotation and about the specified axis.More... |
| `SaveNavigationHomeView()` | `unsafe void` | Save the current view as the home view.More... |
| `SaveViewWithViewName(string replacementChar)` | `unsafeNXOpen.View` | Increment the name of given view with replacement character.More... |
| `SetOrigin(NXOpen.Point3dorigin)` | `unsafe void` | Moves the given position to the center of the view.More... |
| `SetRotationTranslationScale(NXOpen.Matrix3x3rotMatrix,NXOpen.Point3dtranslation, double scale)` | `unsafe void` | Sets the rotation, translation and scale of the specified view.More... |
| `SetScale(double scale)` | `unsafe void` | Sets the scale of the specified view to the desired scale factor.More... |
| `SnapToClosestCannedOrientation()` | `unsafe void` | Changes the orientation of the given view to the orientation of the canned view whose orientation is the closest to that of the given view.More... |
| `SnapToVariantCannedOrientation()` | `unsafe void` | Similar toNXOpen.View.SnapToClosestCannedOrientationexcept it changes the orientation of the given view to the orientation of some canned view "variant" based on I-deas's 'snapview' logic whose orientation is the closest to one of the six orthographic and eight flavors of trimetric views.More... |
| `UpdateCustomSymbols()` | `unsafe void` | Updates custom symbol in a drawing member view or drawing sheetMore... |
| `UpdateDisplay()` | `unsafe void` | Updates the display of given view, as needed.More... |
| `Zoom(NXOpen.View.ScaleFactorscaleFactor)` | `unsafe void` | Scales the specified view to a desired relative scale.More... |
| `ZoomAboutPoint(double relativeScale,NXOpen.Point3dscaleAboutPoint,NXOpen.Point3dviewCenter)` | `unsafe void` | Scales the specified view such that the given scale_about_point does not move.More... |
| `ZoomByRectangle(NXOpen.Point3dcorner1,NXOpen.Point3dcorner2)` | `unsafe void` | Scales the specified view such that the specified rectangle is as large as possible while being fully contained within the viewport.More... |
| `CreateAttributeIterator()` | `unsafeNXOpen.AttributeIterator` | Create an attribute iteratorMore... |
| `DeleteAllAttributesByType(NXOpen.NXObject.AttributeTypetype)` | `unsafe void` | Deletes all attributes of a specific type.More... |
| `DeleteAllAttributesByType(NXOpen.NXObject.AttributeTypetype,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes all attributes of a specific type with the option to update or not.More... |
| `DeleteAttributeByTypeAndTitle(NXOpen.NXObject.AttributeTypetype, string title)` | `unsafe void` | Deletes an attribute by type and title.More... |
| `DeleteAttributeByTypeAndTitle(NXOpen.NXObject.AttributeTypetype, string title,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes an attribute by type and title with the option to update or not.More... |
| `DeleteUserAttribute(NXOpen.NXObject.AttributeTypetype, string title, bool deleteEntireArray,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes the first attribute encountered with the given Type, Title.More... |
| `DeleteUserAttributes(NXOpen.AttributeIteratoriterator,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes the attributes on the object, if any, that satisfy the given iteratorMore... |
| `DeleteUserAttributes(NXOpen.NXObject.AttributeTypetype,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes the attributes encountered with the given Type with option to update or not.More... |
| `FindObject(string journalIdentifier)` | `unsafeNXOpen.INXObject` | Finds theNXOpen.NXObjectwith the given identifier as recorded in a journal.More... |
| `GetAttributeTitlesByType(NXOpen.NXObject.AttributeTypetype)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attribute titles of a specific type.More... |
| `GetBooleanUserAttribute(string title, int index)` | `unsafe bool` | Gets a boolean attribute by Title and array Index.More... |
| `GetComputationalTimeUserAttribute(string title, int index)` | `unsafeNXOpen.NXObject.ComputationalTime` | Gets a time attribute by Title and array Index.More... |
| `GetIntegerAttribute(string title)` | `unsafe int` | Gets an integer attribute by title.More... |
| `GetIntegerUserAttribute(string title, int index)` | `unsafe int` | Gets an integer attribute by Title and array Index.More... |
| `GetNextUserAttribute(NXOpen.AttributeIteratoriterator, outNXOpen.NXObject.AttributeInformationinfo)` | `unsafe bool` | Gets the next attribute encountered on the object, if any, that satisfies the given iterator.More... |
| `GetPdmReferenceAttributeValue(string attributeTitle)` | `unsafe string` | Gets the value of PDM Reference attribute for given object.More... |
| `GetRealAttribute(string title)` | `unsafe double` | Gets a real attribute by title.More... |
| `GetRealUserAttribute(string title, int index)` | `unsafe double` | Gets a real attribute by Title and array Index.More... |
| `GetReferenceAttribute(string title)` | `unsafe string` | Gets the reference string (not the calculated value) of a string attribute that uses a reference string.More... |
| `GetStringAttribute(string title)` | `unsafe string` | Gets a string attribute value by title.More... |
| `GetStringUserAttribute(string title, int index)` | `unsafe string` | Gets a string attribute by Title and array Index.More... |
| `GetTimeAttribute(NXOpen.NXObject.DateAndTimeFormatformat, string title)` | `unsafe string` | Gets a time attribute by title.More... |
| `GetTimeUserAttribute(string title, int index)` | `unsafe string` | Gets a time attribute by Title and array Index.More... |
| `GetUserAttribute(string title,NXOpen.NXObject.AttributeTypetype, int index)` | `unsafeNXOpen.NXObject.AttributeInformation` | Gets the first attribute encountered on the object, if any, with a given Title, Type and array Index.More... |
| `GetUserAttribute(string title, bool includeUnset, bool addStringValues,NXOpen.NXObject.AttributeTypetype)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets the first attribute (or attribute array) encountered on the object, if any, with a given Title and Type.More... |
| `GetUserAttributeAsString(string title,NXOpen.NXObject.AttributeTypetype, int index)` | `unsafe string` | Gets the first attribute encountered on the object, if any, with a given title, type and array index.More... |
| `GetUserAttributeCount(NXOpen.AttributeIteratoriterator)` | `unsafe int` | Gets the count of set attributes on the object, if any, that satisfy the given iterator.More... |
| `GetUserAttributeCount(NXOpen.AttributeIteratoriterator, bool countArrayAsOneAttribute)` | `unsafe int` | Gets the count of set attributes on the object, if any, that satisfy the given iterator.More... |
| `GetUserAttributeCount(NXOpen.NXObject.AttributeTypetype)` | `unsafe int` | Gets the count of set attributes on the object, if any, of the given type.More... |
| `GetUserAttributeCount(NXOpen.NXObject.AttributeTypetype, bool includeUnset, bool countArrayAsOneAttribute)` | `unsafe int` | Gets the count of attributes on the object, if any, of the given type.More... |
| `GetUserAttributeLock(string title,NXOpen.NXObject.AttributeTypetype)` | `unsafe bool` | Determine the lock of the given attribute.More... |
| `GetUserAttributes(NXOpen.AttributeIteratoriterator)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes that have been set on the given object, if any, that satisfy the given iterator.More... |
| `GetUserAttributes()` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes that have been set on the given object.More... |
| `GetUserAttributes(bool includeUnset)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes of the given object.More... |
| `GetUserAttributes(bool includeUnset, bool addStringValues)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes of the given object.More... |
| `GetUserAttributesAsStrings()` | `unsafe string []` | Gets all the attributes that have been set on the given object.More... |
| `GetUserAttributeSize(string title,NXOpen.NXObject.AttributeTypetype)` | `unsafe int` | Gets the size of the first attribute encountered on the object, if any, with a given Title and Type.More... |
| `GetUserAttributeSourceObjects()` | `unsafeNXOpen.NXObject[]` | Returns an array of objects from which this object presents attributes.More... |
| `HasUserAttribute(NXOpen.AttributeIteratoriterator)` | `unsafe bool` | Determines if an attribute exists on the object, that satisfies the given iteratorMore... |
| `HasUserAttribute(string title,NXOpen.NXObject.AttributeTypetype, int index)` | `unsafe bool` | Determines if an attribute with the given Title, Type and array Index is present on the object Unset attributes will not be detected by this function, as its purpose is to test for the actual presence of the attribute on the object.More... |
| `Print()` | `unsafe void` | Prints a representation of this object to the system log file.More... |
| `SetAttribute(string title, int value)` | `unsafe void` | Creates or modifies an integer attribute.More... |
| `SetAttribute(string title, int value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies an integer attribute with the option to update or not.More... |
| `SetAttribute(string title, double value)` | `unsafe void` | Creates or modifies a real attribute.More... |
| `SetAttribute(string title, double value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a real attribute with the option to update or not.More... |
| `SetAttribute(string title, string value)` | `unsafe void` | Creates or modifies a string attribute.More... |
| `SetAttribute(string title, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a string attribute with the option to update or not.More... |
| `SetAttribute(string title)` | `unsafe void` | Creates or modifies a null attribute which is an attribute with a title and no value.More... |
| `SetAttribute(string title,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a null attribute with the option to update or not.More... |
| `SetBooleanUserAttribute(string title, int index, bool value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a boolean attribute with the option to update or not.More... |
| `SetName(string name)` | `unsafe void` | Sets the custom name of the object.More... |
| `SetPdmReferenceAttribute(string attributeTitle, string attributeValue)` | `unsafe void` | Sets the value of PDM Reference attribute on the object.More... |
| `SetReferenceAttribute(string title, string value)` | `unsafe void` | Creates or modifies a string attribute which uses a reference string.More... |
| `SetReferenceAttribute(string title, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a string attribute which uses a reference string, with the option to update or not.More... |
| `SetTimeAttribute(string title, string value)` | `unsafe void` | Creates or modifies a time attribute.More... |
| `SetTimeAttribute(string title, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a time attribute with the option to update or not.More... |
| `SetTimeUserAttribute(string title, int index, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a time attribute with the option to update or not.More... |
| `SetTimeUserAttribute(string title, int index,NXOpen.NXObject.ComputationalTimevalue,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a time attribute with the option to update or not.More... |
| `SetUserAttribute(NXOpen.NXObject.AttributeInformationinfo,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies an attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index, int value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies an integer attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index, double value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a real attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a string attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a null attribute with the option to update or not.More... |
| `SetUserAttributeLock(string title,NXOpen.NXObject.AttributeTypetype, bool @lock)` | `unsafe void` | Lock or unlock the given attribute.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |


---

## NXOpen.Drawings.DetailViewBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49484.html

Represents aNXOpen.Drawings.DetailView

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Associative[get, set]` | `unsafe bool` | Returns or sets the associative toggle If view is associative and set associative to false, the view will be converted to independent detail view.More... |
| `BoundaryPoint1[get, set]` | `unsafeNXOpen.Point` | Returns or sets the first boundary point.More... |
| `BoundaryPoint2[get, set]` | `unsafeNXOpen.Point` | Returns or sets the second boundary point.More... |
| `HiddenObjects[get]` | `unsafeNXOpen.Drawings.HiddenObjectsBuilder` | Returns the list of objects to not show in the viewMore... |
| `LabelOnParent[get, set]` | `unsafeNXOpen.Drawings.DetailViewBuilder.LabelOnParentType` | Returns or sets the label on parentMore... |
| `NonSectionedObjects[get]` | `unsafeNXOpen.Drawings.HiddenObjectsBuilder` | Returns the list of objects to not section in the viewMore... |
| `Origin[get]` | `unsafeNXOpen.Drawings.ViewPlacementBuilder` | Returns the originMore... |
| `Parent[get]` | `unsafeNXOpen.Drawings.ParentViewBuilder` | Returns the parent viewMore... |
| `Scale[get]` | `unsafeNXOpen.Drawings.ViewScaleBuilder` | Returns the scaleMore... |
| `SecondaryComponents[get]` | `unsafeNXOpen.Drawings.DraftingComponentSelectionBuilder` | Returns the list of secondary components in the viewMore... |
| `Style[get]` | `unsafeNXOpen.Drawings.ViewStyleBuilder` | Returns the styleMore... |
| `Type[get, set]` | `unsafeNXOpen.Drawings.DetailViewBuilder.Types` | Returns or sets the typeMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.DraftingBody

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49488.html

Represents a drafting body

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `DraftingCurves[get]` | `NXOpen.Drawings.DraftingCurveCollection` | Returns the DraftingCurveCollectionMore... |
| `DraftingPoints[get]` | `NXOpen.Drawings.DraftingPointCollection` | Returns the DraftingPointCollectionMore... |
| `Color[get, set]` | `unsafe int` | Returns or sets the color of the object.More... |
| `IsBlanked[get]` | `unsafe bool` | Returns the blank status of this object.More... |
| `Layer[get, set]` | `unsafe int` | Returns or sets the layer that the object is in.More... |
| `LineFont[get, set]` | `unsafeNXOpen.DisplayableObject.ObjectFont` | Returns or sets the line font of the object.More... |
| `LineWidth[get, set]` | `unsafeNXOpen.DisplayableObject.ObjectWidth` | Returns or sets the line width of the object.More... |
| `NameLocation[get]` | `unsafeNXOpen.Point3d` | Returns the location of the object's name.More... |
| `IsOccurrence[get]` | `unsafe bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `unsafe string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Name[get]` | `unsafe string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `unsafeNXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `unsafeNXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `unsafeNXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |
| `IsOccurrence[get]` | `bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Name[get]` | `string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `NXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `NXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `NXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |


---

## NXOpen.Drawings.DraftingBodyCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49492.html

Represents a collection ofNXOpen.Drawings.DraftingBodys

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `FindObject(string journalIdentifier)` | `unsafeNXOpen.Drawings.DraftingBody` | Finds theNXOpen.Drawings.DraftingBodywith the given identifier as recorded in a journal.More... |
| `ToArray()` | `NXOpen.Drawings.DraftingBody[]` | Returns an array ofNXOpen.Drawings.DraftingBodyobjects.More... |
| `GetEnumerator()` | `IEnumerator` | Returns an enumerator that iterates through a collection.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |
| `EnumerateMoveNext(refTagcurrentTag, byte [] state)` | `override int` | Advances the enumerator to the next element of the collection.More... |
| `initialize()` | `new void` | <exclude>More... |
| `initialize()` | `void` | <exclude>More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.DraftingComponentSelectionBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49496.html

This builder allows the user to select a view in which component objects can be designated as primary or secondary geometry

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `ClearSecondaryComponentList()` | `unsafe void` | Clears the secondary component list.More... |
| `InitializeListFromObject(NXOpen.NXObjectinputObject)` | `unsafe void` | Initialize list of components from the input object's components list.More... |
| `ResetListToGlobal()` | `unsafe void` | Reset list of components to those specified by Properties->Drawings->Secondary GeometryMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Objects[get]` | `unsafeNXOpen.SelectNXObjectList` | Returns the selected objects (part occurrences) based on current object typeMore... |
| `ObjectType[get, set]` | `unsafeNXOpen.Drawings.DraftingComponentSelectionBuilder.Geometry` | Returns or sets the object typeMore... |
| `Part[get, set]` | `unsafeNXOpen.Part` | Returns or sets the part to use for populating the primary and secondary components object listMore... |
| `PartForKF[get]` | `unsafeNXOpen.Part` | Returns the part to use for populating the primary and secondary components object listMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.DraftingCurve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49500.html

Represents a Drafting VD Curve

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetDraftingCurveInfo()` | `unsafeNXOpen.Drawings.DraftingCurveInfo` | Creates new DraftingCurveInfo objectMore... |
| `GetLength()` | `unsafe double` | Returns the length of the objectMore... |
| `GetLocations()` | `unsafeNXOpen.GeometricUtilities.CurveLocation[]` | Finds the locations associated with this curveMore... |
| `IsDraftingCurve()` | `unsafe bool` | Checks if an object is a Drafting CurveMore... |
| `Blank()` | `unsafe void` | Blanks the object.More... |
| `Highlight()` | `unsafe void` | Highlights the object.More... |
| `RedisplayObject()` | `unsafe void` | Redisplays the object in all views.More... |
| `RemoveViewDependency()` | `unsafe void` | Remove dependency on all views from an object.More... |
| `SetNameLocation(NXOpen.Point3dlocation)` | `unsafe void` | Sets the location of the object's name.More... |
| `Unblank()` | `unsafe void` | Unblanks the object.More... |
| `Unhighlight()` | `unsafe void` | Unhighlights the object.More... |
| `CreateAttributeIterator()` | `unsafeNXOpen.AttributeIterator` | Create an attribute iteratorMore... |
| `DeleteAllAttributesByType(NXOpen.NXObject.AttributeTypetype)` | `unsafe void` | Deletes all attributes of a specific type.More... |
| `DeleteAllAttributesByType(NXOpen.NXObject.AttributeTypetype,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes all attributes of a specific type with the option to update or not.More... |
| `DeleteAttributeByTypeAndTitle(NXOpen.NXObject.AttributeTypetype, string title)` | `unsafe void` | Deletes an attribute by type and title.More... |
| `DeleteAttributeByTypeAndTitle(NXOpen.NXObject.AttributeTypetype, string title,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes an attribute by type and title with the option to update or not.More... |
| `DeleteUserAttribute(NXOpen.NXObject.AttributeTypetype, string title, bool deleteEntireArray,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes the first attribute encountered with the given Type, Title.More... |
| `DeleteUserAttributes(NXOpen.AttributeIteratoriterator,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes the attributes on the object, if any, that satisfy the given iteratorMore... |
| `DeleteUserAttributes(NXOpen.NXObject.AttributeTypetype,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes the attributes encountered with the given Type with option to update or not.More... |
| `FindObject(string journalIdentifier)` | `unsafeNXOpen.INXObject` | Finds theNXOpen.NXObjectwith the given identifier as recorded in a journal.More... |
| `GetAttributeTitlesByType(NXOpen.NXObject.AttributeTypetype)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attribute titles of a specific type.More... |
| `GetBooleanUserAttribute(string title, int index)` | `unsafe bool` | Gets a boolean attribute by Title and array Index.More... |
| `GetComputationalTimeUserAttribute(string title, int index)` | `unsafeNXOpen.NXObject.ComputationalTime` | Gets a time attribute by Title and array Index.More... |
| `GetIntegerAttribute(string title)` | `unsafe int` | Gets an integer attribute by title.More... |
| `GetIntegerUserAttribute(string title, int index)` | `unsafe int` | Gets an integer attribute by Title and array Index.More... |
| `GetNextUserAttribute(NXOpen.AttributeIteratoriterator, outNXOpen.NXObject.AttributeInformationinfo)` | `unsafe bool` | Gets the next attribute encountered on the object, if any, that satisfies the given iterator.More... |
| `GetPdmReferenceAttributeValue(string attributeTitle)` | `unsafe string` | Gets the value of PDM Reference attribute for given object.More... |
| `GetRealAttribute(string title)` | `unsafe double` | Gets a real attribute by title.More... |
| `GetRealUserAttribute(string title, int index)` | `unsafe double` | Gets a real attribute by Title and array Index.More... |
| `GetReferenceAttribute(string title)` | `unsafe string` | Gets the reference string (not the calculated value) of a string attribute that uses a reference string.More... |
| `GetStringAttribute(string title)` | `unsafe string` | Gets a string attribute value by title.More... |
| `GetStringUserAttribute(string title, int index)` | `unsafe string` | Gets a string attribute by Title and array Index.More... |
| `GetTimeAttribute(NXOpen.NXObject.DateAndTimeFormatformat, string title)` | `unsafe string` | Gets a time attribute by title.More... |
| `GetTimeUserAttribute(string title, int index)` | `unsafe string` | Gets a time attribute by Title and array Index.More... |
| `GetUserAttribute(string title,NXOpen.NXObject.AttributeTypetype, int index)` | `unsafeNXOpen.NXObject.AttributeInformation` | Gets the first attribute encountered on the object, if any, with a given Title, Type and array Index.More... |
| `GetUserAttribute(string title, bool includeUnset, bool addStringValues,NXOpen.NXObject.AttributeTypetype)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets the first attribute (or attribute array) encountered on the object, if any, with a given Title and Type.More... |
| `GetUserAttributeAsString(string title,NXOpen.NXObject.AttributeTypetype, int index)` | `unsafe string` | Gets the first attribute encountered on the object, if any, with a given title, type and array index.More... |
| `GetUserAttributeCount(NXOpen.AttributeIteratoriterator)` | `unsafe int` | Gets the count of set attributes on the object, if any, that satisfy the given iterator.More... |
| `GetUserAttributeCount(NXOpen.AttributeIteratoriterator, bool countArrayAsOneAttribute)` | `unsafe int` | Gets the count of set attributes on the object, if any, that satisfy the given iterator.More... |
| `GetUserAttributeCount(NXOpen.NXObject.AttributeTypetype)` | `unsafe int` | Gets the count of set attributes on the object, if any, of the given type.More... |
| `GetUserAttributeCount(NXOpen.NXObject.AttributeTypetype, bool includeUnset, bool countArrayAsOneAttribute)` | `unsafe int` | Gets the count of attributes on the object, if any, of the given type.More... |
| `GetUserAttributeLock(string title,NXOpen.NXObject.AttributeTypetype)` | `unsafe bool` | Determine the lock of the given attribute.More... |
| `GetUserAttributes(NXOpen.AttributeIteratoriterator)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes that have been set on the given object, if any, that satisfy the given iterator.More... |
| `GetUserAttributes()` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes that have been set on the given object.More... |
| `GetUserAttributes(bool includeUnset)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes of the given object.More... |
| `GetUserAttributes(bool includeUnset, bool addStringValues)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes of the given object.More... |
| `GetUserAttributesAsStrings()` | `unsafe string []` | Gets all the attributes that have been set on the given object.More... |
| `GetUserAttributeSize(string title,NXOpen.NXObject.AttributeTypetype)` | `unsafe int` | Gets the size of the first attribute encountered on the object, if any, with a given Title and Type.More... |
| `GetUserAttributeSourceObjects()` | `unsafeNXOpen.NXObject[]` | Returns an array of objects from which this object presents attributes.More... |
| `HasUserAttribute(NXOpen.AttributeIteratoriterator)` | `unsafe bool` | Determines if an attribute exists on the object, that satisfies the given iteratorMore... |
| `HasUserAttribute(string title,NXOpen.NXObject.AttributeTypetype, int index)` | `unsafe bool` | Determines if an attribute with the given Title, Type and array Index is present on the object Unset attributes will not be detected by this function, as its purpose is to test for the actual presence of the attribute on the object.More... |
| `Print()` | `unsafe void` | Prints a representation of this object to the system log file.More... |
| `SetAttribute(string title, int value)` | `unsafe void` | Creates or modifies an integer attribute.More... |
| `SetAttribute(string title, int value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies an integer attribute with the option to update or not.More... |
| `SetAttribute(string title, double value)` | `unsafe void` | Creates or modifies a real attribute.More... |
| `SetAttribute(string title, double value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a real attribute with the option to update or not.More... |
| `SetAttribute(string title, string value)` | `unsafe void` | Creates or modifies a string attribute.More... |
| `SetAttribute(string title, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a string attribute with the option to update or not.More... |
| `SetAttribute(string title)` | `unsafe void` | Creates or modifies a null attribute which is an attribute with a title and no value.More... |
| `SetAttribute(string title,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a null attribute with the option to update or not.More... |
| `SetBooleanUserAttribute(string title, int index, bool value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a boolean attribute with the option to update or not.More... |
| `SetName(string name)` | `unsafe void` | Sets the custom name of the object.More... |
| `SetPdmReferenceAttribute(string attributeTitle, string attributeValue)` | `unsafe void` | Sets the value of PDM Reference attribute on the object.More... |
| `SetReferenceAttribute(string title, string value)` | `unsafe void` | Creates or modifies a string attribute which uses a reference string.More... |
| `SetReferenceAttribute(string title, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a string attribute which uses a reference string, with the option to update or not.More... |
| `SetTimeAttribute(string title, string value)` | `unsafe void` | Creates or modifies a time attribute.More... |
| `SetTimeAttribute(string title, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a time attribute with the option to update or not.More... |
| `SetTimeUserAttribute(string title, int index, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a time attribute with the option to update or not.More... |
| `SetTimeUserAttribute(string title, int index,NXOpen.NXObject.ComputationalTimevalue,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a time attribute with the option to update or not.More... |
| `SetUserAttribute(NXOpen.NXObject.AttributeInformationinfo,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies an attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index, int value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies an integer attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index, double value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a real attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a string attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a null attribute with the option to update or not.More... |
| `SetUserAttributeLock(string title,NXOpen.NXObject.AttributeTypetype, bool @lock)` | `unsafe void` | Lock or unlock the given attribute.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `IsReference[get]` | `unsafe bool` | Returns the reference state of a curveMore... |
| `Color[get, set]` | `unsafe int` | Returns or sets the color of the object.More... |
| `IsBlanked[get]` | `unsafe bool` | Returns the blank status of this object.More... |
| `Layer[get, set]` | `unsafe int` | Returns or sets the layer that the object is in.More... |
| `LineFont[get, set]` | `unsafeNXOpen.DisplayableObject.ObjectFont` | Returns or sets the line font of the object.More... |
| `LineWidth[get, set]` | `unsafeNXOpen.DisplayableObject.ObjectWidth` | Returns or sets the line width of the object.More... |
| `NameLocation[get]` | `unsafeNXOpen.Point3d` | Returns the location of the object's name.More... |
| `IsOccurrence[get]` | `unsafe bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `unsafe string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Name[get]` | `unsafe string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `unsafeNXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `unsafeNXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `unsafeNXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |
| `IsOccurrence[get]` | `bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Name[get]` | `string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `NXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `NXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `NXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |
| `IsReference[get]` | `bool` | Returns the reference state of a curveMore... |


---

## NXOpen.Drawings.DraftingCurveCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49504.html

Represents a collection ofNXOpen.Drawings.DraftingCurves

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `FindObject(string journalIdentifier)` | `unsafeNXOpen.Drawings.DraftingCurve` | Finds theNXOpen.Drawings.DraftingCurvewith the given identifier as recorded in a journal.More... |
| `ToArray()` | `NXOpen.Drawings.DraftingCurve[]` | Returns an array ofNXOpen.Drawings.DraftingCurveobjects.More... |
| `GetEnumerator()` | `IEnumerator` | Returns an enumerator that iterates through a collection.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |
| `EnumerateMoveNext(refTagcurrentTag, byte [] state)` | `override int` | Advances the enumerator to the next element of the collection.More... |
| `initialize()` | `new void` | <exclude>More... |
| `initialize()` | `void` | <exclude>More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.DraftingCurveInfo

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49508.html

Represents Drafting Curve Info

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetParents()` | `unsafeNXOpen.NXObject[]` | Returns the parents for input drafting curveMore... |
| `Dispose()` | `void` | Frees the object from memory.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `new string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |
| `FreeResource()` | `override void` | Frees the object from memory.More... |
| `initialize()` | `void` | <exclude>More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CurveType[get]` | `unsafeNXOpen.Drawings.DraftingCurveInfo.DraftingCurveType` | Returns the drafting curve typeMore... |
| `Handle[get]` | `IntPtr` | Handle of the internal object represented by this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.DraftingDrawingSheet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49512.html

Represents a drafting drawing sheet


---

## NXOpen.Drawings.DraftingDrawingSheetBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49516.html

Represents a Builder for creatingNXOpen.Drawings.DraftingDrawingSheets


---

## NXOpen.Drawings.DraftingDrawingSheetCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49520.html

Represents a collection ofNXOpen.Drawings.DraftingDrawingSheets

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateDraftingDrawingSheetBuilder(NXOpen.Drawings.DraftingDrawingSheetdraftingDrawingSheet)` | `unsafeNXOpen.Drawings.DraftingDrawingSheetBuilder` | Creates aNXOpen.Drawings.DraftingDrawingSheetBuilderMore... |
| `FindObject(string journalIdentifier)` | `unsafeNXOpen.Drawings.DraftingDrawingSheet` | Finds theNXOpen.Drawings.DraftingDrawingSheetwith the given identifier as recorded in a journal.More... |
| `InsertSheet(string drawingName,NXOpen.Drawings.DrawingSheet.UnitdrawingUnits, double width, double height, double numerator, double denominator,NXOpen.Drawings.DrawingSheet.ProjectionAngleTypeprojectionAngle)` | `unsafeNXOpen.Drawings.DraftingDrawingSheet` | Inserts a drafting drawing sheet into a part.More... |
| `InsertSheet(string drawingName,NXOpen.Drawings.DrawingSheet.StandardSheetSizesheetSize, double numerator, double denominator,NXOpen.Drawings.DrawingSheet.ProjectionAngleTypeprojectionAngle)` | `unsafeNXOpen.Drawings.DraftingDrawingSheet` | Inserts a sheet into a part.More... |
| `ToArray()` | `NXOpen.Drawings.DraftingDrawingSheet[]` | Returns an array ofNXOpen.Drawings.DraftingDrawingSheetobjects.More... |
| `GetEnumerator()` | `IEnumerator` | Returns an enumerator that iterates through a collection.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |
| `EnumerateMoveNext(refTagcurrentTag, byte [] state)` | `override int` | Advances the enumerator to the next element of the collection.More... |
| `initialize()` | `new void` | <exclude>More... |
| `initialize()` | `void` | <exclude>More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CurrentDrawingSheet[get]` | `unsafeNXOpen.Drawings.DraftingDrawingSheet` | Returns the currently opened drafting drawing sheet.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.DraftingPoint

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49524.html

Represents a Drafting VD Point

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetDraftingPointInfo()` | `unsafeNXOpen.Drawings.DraftingCurveInfo` | Creates new DraftingCurveInfo objectMore... |
| `SetCoordinates(NXOpen.Point3dcoordinates)` | `unsafe void` | Sets the coordinates of the pointMore... |
| `SetPointOnCurveTParameterFixed(bool isFixed)` | `unsafe void` | Sets the T parameter of the point created using point on curve methodMore... |
| `Evaluate()` | `unsafe void` | Evaluate a smart object.More... |
| `ProtectFromDelete()` | `unsafe void` | Protects the SmartObject from being deleted if any referencing objects are deleted.More... |
| `ReleaseDeleteProtection()` | `unsafe void` | Removes delete protection from the SmartObject.More... |
| `RemoveParameters()` | `unsafe void` | Removes the smart object parameters.More... |
| `ReplaceParameters(NXOpen.SmartObjectotherSo)` | `unsafe void` | Edit a smart object by replacing its parameters using parameters of other smart object of the same class.More... |
| `SetVisibility(NXOpen.SmartObject.VisibilityOptionvisibility)` | `unsafe void` | Sets the visibility.More... |
| `Blank()` | `unsafe void` | Blanks the object.More... |
| `Highlight()` | `unsafe void` | Highlights the object.More... |
| `RedisplayObject()` | `unsafe void` | Redisplays the object in all views.More... |
| `RemoveViewDependency()` | `unsafe void` | Remove dependency on all views from an object.More... |
| `SetNameLocation(NXOpen.Point3dlocation)` | `unsafe void` | Sets the location of the object's name.More... |
| `Unblank()` | `unsafe void` | Unblanks the object.More... |
| `Unhighlight()` | `unsafe void` | Unhighlights the object.More... |
| `CreateAttributeIterator()` | `unsafeNXOpen.AttributeIterator` | Create an attribute iteratorMore... |
| `DeleteAllAttributesByType(NXOpen.NXObject.AttributeTypetype)` | `unsafe void` | Deletes all attributes of a specific type.More... |
| `DeleteAllAttributesByType(NXOpen.NXObject.AttributeTypetype,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes all attributes of a specific type with the option to update or not.More... |
| `DeleteAttributeByTypeAndTitle(NXOpen.NXObject.AttributeTypetype, string title)` | `unsafe void` | Deletes an attribute by type and title.More... |
| `DeleteAttributeByTypeAndTitle(NXOpen.NXObject.AttributeTypetype, string title,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes an attribute by type and title with the option to update or not.More... |
| `DeleteUserAttribute(NXOpen.NXObject.AttributeTypetype, string title, bool deleteEntireArray,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes the first attribute encountered with the given Type, Title.More... |
| `DeleteUserAttributes(NXOpen.AttributeIteratoriterator,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes the attributes on the object, if any, that satisfy the given iteratorMore... |
| `DeleteUserAttributes(NXOpen.NXObject.AttributeTypetype,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes the attributes encountered with the given Type with option to update or not.More... |
| `FindObject(string journalIdentifier)` | `unsafeNXOpen.INXObject` | Finds theNXOpen.NXObjectwith the given identifier as recorded in a journal.More... |
| `GetAttributeTitlesByType(NXOpen.NXObject.AttributeTypetype)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attribute titles of a specific type.More... |
| `GetBooleanUserAttribute(string title, int index)` | `unsafe bool` | Gets a boolean attribute by Title and array Index.More... |
| `GetComputationalTimeUserAttribute(string title, int index)` | `unsafeNXOpen.NXObject.ComputationalTime` | Gets a time attribute by Title and array Index.More... |
| `GetIntegerAttribute(string title)` | `unsafe int` | Gets an integer attribute by title.More... |
| `GetIntegerUserAttribute(string title, int index)` | `unsafe int` | Gets an integer attribute by Title and array Index.More... |
| `GetNextUserAttribute(NXOpen.AttributeIteratoriterator, outNXOpen.NXObject.AttributeInformationinfo)` | `unsafe bool` | Gets the next attribute encountered on the object, if any, that satisfies the given iterator.More... |
| `GetPdmReferenceAttributeValue(string attributeTitle)` | `unsafe string` | Gets the value of PDM Reference attribute for given object.More... |
| `GetRealAttribute(string title)` | `unsafe double` | Gets a real attribute by title.More... |
| `GetRealUserAttribute(string title, int index)` | `unsafe double` | Gets a real attribute by Title and array Index.More... |
| `GetReferenceAttribute(string title)` | `unsafe string` | Gets the reference string (not the calculated value) of a string attribute that uses a reference string.More... |
| `GetStringAttribute(string title)` | `unsafe string` | Gets a string attribute value by title.More... |
| `GetStringUserAttribute(string title, int index)` | `unsafe string` | Gets a string attribute by Title and array Index.More... |
| `GetTimeAttribute(NXOpen.NXObject.DateAndTimeFormatformat, string title)` | `unsafe string` | Gets a time attribute by title.More... |
| `GetTimeUserAttribute(string title, int index)` | `unsafe string` | Gets a time attribute by Title and array Index.More... |
| `GetUserAttribute(string title,NXOpen.NXObject.AttributeTypetype, int index)` | `unsafeNXOpen.NXObject.AttributeInformation` | Gets the first attribute encountered on the object, if any, with a given Title, Type and array Index.More... |
| `GetUserAttribute(string title, bool includeUnset, bool addStringValues,NXOpen.NXObject.AttributeTypetype)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets the first attribute (or attribute array) encountered on the object, if any, with a given Title and Type.More... |
| `GetUserAttributeAsString(string title,NXOpen.NXObject.AttributeTypetype, int index)` | `unsafe string` | Gets the first attribute encountered on the object, if any, with a given title, type and array index.More... |
| `GetUserAttributeCount(NXOpen.AttributeIteratoriterator)` | `unsafe int` | Gets the count of set attributes on the object, if any, that satisfy the given iterator.More... |
| `GetUserAttributeCount(NXOpen.AttributeIteratoriterator, bool countArrayAsOneAttribute)` | `unsafe int` | Gets the count of set attributes on the object, if any, that satisfy the given iterator.More... |
| `GetUserAttributeCount(NXOpen.NXObject.AttributeTypetype)` | `unsafe int` | Gets the count of set attributes on the object, if any, of the given type.More... |
| `GetUserAttributeCount(NXOpen.NXObject.AttributeTypetype, bool includeUnset, bool countArrayAsOneAttribute)` | `unsafe int` | Gets the count of attributes on the object, if any, of the given type.More... |
| `GetUserAttributeLock(string title,NXOpen.NXObject.AttributeTypetype)` | `unsafe bool` | Determine the lock of the given attribute.More... |
| `GetUserAttributes(NXOpen.AttributeIteratoriterator)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes that have been set on the given object, if any, that satisfy the given iterator.More... |
| `GetUserAttributes()` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes that have been set on the given object.More... |
| `GetUserAttributes(bool includeUnset)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes of the given object.More... |
| `GetUserAttributes(bool includeUnset, bool addStringValues)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes of the given object.More... |
| `GetUserAttributesAsStrings()` | `unsafe string []` | Gets all the attributes that have been set on the given object.More... |
| `GetUserAttributeSize(string title,NXOpen.NXObject.AttributeTypetype)` | `unsafe int` | Gets the size of the first attribute encountered on the object, if any, with a given Title and Type.More... |
| `GetUserAttributeSourceObjects()` | `unsafeNXOpen.NXObject[]` | Returns an array of objects from which this object presents attributes.More... |
| `HasUserAttribute(NXOpen.AttributeIteratoriterator)` | `unsafe bool` | Determines if an attribute exists on the object, that satisfies the given iteratorMore... |
| `HasUserAttribute(string title,NXOpen.NXObject.AttributeTypetype, int index)` | `unsafe bool` | Determines if an attribute with the given Title, Type and array Index is present on the object Unset attributes will not be detected by this function, as its purpose is to test for the actual presence of the attribute on the object.More... |
| `Print()` | `unsafe void` | Prints a representation of this object to the system log file.More... |
| `SetAttribute(string title, int value)` | `unsafe void` | Creates or modifies an integer attribute.More... |
| `SetAttribute(string title, int value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies an integer attribute with the option to update or not.More... |
| `SetAttribute(string title, double value)` | `unsafe void` | Creates or modifies a real attribute.More... |
| `SetAttribute(string title, double value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a real attribute with the option to update or not.More... |
| `SetAttribute(string title, string value)` | `unsafe void` | Creates or modifies a string attribute.More... |
| `SetAttribute(string title, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a string attribute with the option to update or not.More... |
| `SetAttribute(string title)` | `unsafe void` | Creates or modifies a null attribute which is an attribute with a title and no value.More... |
| `SetAttribute(string title,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a null attribute with the option to update or not.More... |
| `SetBooleanUserAttribute(string title, int index, bool value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a boolean attribute with the option to update or not.More... |
| `SetName(string name)` | `unsafe void` | Sets the custom name of the object.More... |
| `SetPdmReferenceAttribute(string attributeTitle, string attributeValue)` | `unsafe void` | Sets the value of PDM Reference attribute on the object.More... |
| `SetReferenceAttribute(string title, string value)` | `unsafe void` | Creates or modifies a string attribute which uses a reference string.More... |
| `SetReferenceAttribute(string title, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a string attribute which uses a reference string, with the option to update or not.More... |
| `SetTimeAttribute(string title, string value)` | `unsafe void` | Creates or modifies a time attribute.More... |
| `SetTimeAttribute(string title, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a time attribute with the option to update or not.More... |
| `SetTimeUserAttribute(string title, int index, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a time attribute with the option to update or not.More... |
| `SetTimeUserAttribute(string title, int index,NXOpen.NXObject.ComputationalTimevalue,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a time attribute with the option to update or not.More... |
| `SetUserAttribute(NXOpen.NXObject.AttributeInformationinfo,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies an attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index, int value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies an integer attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index, double value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a real attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a string attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a null attribute with the option to update or not.More... |
| `SetUserAttributeLock(string title,NXOpen.NXObject.AttributeTypetype, bool @lock)` | `unsafe void` | Lock or unlock the given attribute.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |


---

## NXOpen.Drawings.DraftingPointCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49528.html

Represents a collection ofNXOpen.Drawings.DraftingPoints

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `FindObject(string journalIdentifier)` | `unsafeNXOpen.Drawings.DraftingPoint` | Finds theNXOpen.Drawings.DraftingPointwith the given identifier as recorded in a journal.More... |
| `ToArray()` | `NXOpen.Drawings.DraftingPoint[]` | Returns an array ofNXOpen.Drawings.DraftingPointobjects.More... |
| `GetEnumerator()` | `IEnumerator` | Returns an enumerator that iterates through a collection.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |
| `EnumerateMoveNext(refTagcurrentTag, byte [] state)` | `override int` | Advances the enumerator to the next element of the collection.More... |
| `initialize()` | `new void` | <exclude>More... |
| `initialize()` | `void` | <exclude>More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.DraftingView

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49532.html

Represents a drafting view

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `ActivateForSketching()` | `unsafe void` | Sets this drafting view as the active sketch view.More... |
| `CalculateMinMaxBox(outNXOpen.Point3dminimumPoint, outNXOpen.Point3dmaximumPoint)` | `unsafe void` | Returns the absolute min-max box that contains all the entities in the view.More... |
| `CheckForInvalidParentModelView()` | `unsafe void` | Checks the view's validity by looking at the parent model viewMore... |
| `Commit()` | `unsafe void` | Commits and applies all the settings likeNXOpen.Drawings.ViewStyleto the View.More... |
| `GetBrokenViewDecoration()` | `unsafeNXOpen.Drawings.DraftingView` | Return the decoration view of a slave or a master view.More... |
| `GetBrokenViewInternalViews(outNXOpen.Drawings.DraftingView[] views)` | `unsafe void` | Returns an array of views representing the internal views of broken view.More... |
| `GetBrokenViewMaster()` | `unsafeNXOpen.Drawings.DraftingView` | Return the master view of a slave or a decoration view.More... |
| `GetDraftingSketches()` | `unsafeNXOpen.Sketch[]` | Returns all draftingNXOpen.Sketches of the view.More... |
| `GetDrawingReferencePoint()` | `unsafeNXOpen.Point3d` | Returns the view origin(location).More... |
| `GetToolMarkers(outNXOpen.Drawings.FlatPatternObject[] markers)` | `unsafe void` | Returns an array of pointers to objects representing the tool markers in the view.More... |
| `HideComponents(NXOpen.NXObject[] components)` | `unsafe void` | Hides the specified components in the view.More... |
| `HideViewBorder()` | `unsafe void` | Hide the view border of the broken view.More... |
| `MoveView(NXOpen.Point3ddrawingReferencePoint)` | `unsafe void` | Sets the view origin at the provided location.More... |
| `RestoreViewBorder()` | `unsafe void` | Restores the view border from the dashed line to the normal line for cut operationMore... |
| `SetDeleteSectionLine(bool deleteSectionLine)` | `unsafe void` | Set the section line delete option, If false section line will not be deleted with section viewMore... |
| `SetDrawingReferencePoint(NXOpen.Point3ddrawingReferencePoint)` | `unsafe void` | Sets the view origin at the provided location.More... |
| `ShowComponents(NXOpen.NXObject[] components)` | `unsafe void` | Shows the specified components in the view.More... |
| `ShowViewBorder()` | `unsafe void` | Show the view border of the broken view.More... |
| `Update()` | `unsafe void` | Updates the drawing member view on a drawing.More... |
| `UpdateAutomaticViewBound()` | `unsafe void` | Recalculates and updates the view boundary of a drawing member viewMore... |
| `UpdateAutomaticViewBound(bool updateDependent)` | `unsafe void` | Recalculates and updates the view boundary of a drawing member view and update the boundary dependent objectsMore... |
| `AskVisibleObjects()` | `unsafeNXOpen.DisplayableObject[]` | Returns an array of objects visible in a view.More... |
| `ChangePerspective(bool changeViewToPerspective)` | `unsafe void` | Changes a view from an orthographic view to a perspective view, or from a perspective view to an orthographic view.More... |
| `Concatenate(NXOpen.Point3dtranslation)` | `unsafe void` | Concatenates the given translation with the previous viewing transformation of the specified view.More... |
| `Concatenate(double scale)` | `unsafe void` | Concatenates the given scale with the previous viewing transformation of the specified view.More... |
| `Concatenate(NXOpen.Point3dtranslation, double scale)` | `unsafe void` | Concatenates the given translation and scale with the previous viewing transformation of the specified view.More... |
| `Concatenate(NXOpen.Point3dcenterOfRotation,NXOpen.Vector3drotationAxis, double angle)` | `unsafe void` | Concatenates the given rotation with the previous viewing transformation of the specified view.More... |
| `Concatenate(NXOpen.Point3dtranslation,NXOpen.Point3dcenterOfRotation,NXOpen.Vector3drotationAxis, double angle)` | `unsafe void` | Concatenates the given translation and rotation with the previous viewing transformation of the specified view.More... |
| `Concatenate(double scale,NXOpen.Point3dcenterOfRotation,NXOpen.Vector3drotationAxis, double angle)` | `unsafe void` | Concatenates the given scale and rotation with the previous viewing transformation of the specified view.More... |
| `Concatenate(NXOpen.Point3dtranslation, double scale,NXOpen.Point3dcenterOfRotation,NXOpen.Vector3drotationAxis, double angle)` | `unsafe void` | Concatenates the given translation, scale and rotation with the previous viewing transformation of the specified view.More... |
| `EnableNavigationFlyThrough(bool isEnable)` | `unsafe void` | Enables Fly-through by virtually placing you as a first-person observer in the view.More... |
| `Expand()` | `unsafe void` | Expands the specified view to fill as much of the layout which contains the view as possible, without changing the aspect ratio of the view.More... |
| `Fit()` | `unsafe void` | Adjusts the bounds of a given view so that it fully encompasses the extents of the model geometry.More... |
| `FitAfterShowOrHide(NXOpen.View.ShowOrHideTypetype)` | `unsafe void` | Adjusts the bounds of a given view conditionally so that it fully encompasses the extents of the model geometry.More... |
| `FitToObjects(NXOpen.IFitTo[] objects)` | `unsafe void` | Adjusts the bounds of a given view so that it fully encompasses the extents of the given objects.More... |
| `FlyToObjects(NXOpen.INXObject[] objects)` | `unsafe void` | Fly to the given objects.More... |
| `GetAxis(NXOpen.XYZAxisxYZAxis)` | `unsafeNXOpen.Vector3d` | Returns one of the view axes.More... |
| `GetExpandedScale()` | `unsafe double` | Returns the view scale, including any expansion factor.More... |
| `HasPreview()` | `unsafe bool` | Returns whether or not the given view has a preview.More... |
| `IsNavigationFlyThroughEnabled()` | `unsafe bool` | Returns whether or not Fly-through is enabled.More... |
| `MakeWork()` | `unsafe void` | Makes the given view the work view.More... |
| `NavigationFlyThrough(NXOpen.Point3dstartPoint,NXOpen.Point3dstartEnd)` | `unsafe void` | In Fly-through, fly from start point and ends at end point.More... |
| `NavigationFlyThroughWithScale(double relativeScale)` | `unsafe void` | In Fly-through, fly use relative scale.More... |
| `Orient(NXOpen.Matrix3x3matrix)` | `unsafe void` | Changes the view orientation relative to the specified absolute coordinate system.More... |
| `Orient(NXOpen.View.CannedviewName,NXOpen.View.ScaleAdjustmentviewScale)` | `unsafe void` | Changes the view orientation to a specified canned view.More... |
| `Orient(string viewName,NXOpen.View.ScaleAdjustmentviewScale)` | `unsafe void` | Changes the view orientation to a specified view.More... |
| `PanToObjects(NXOpen.INXObject[] objects)` | `unsafe void` | Pans and centers the view to the given objects.More... |
| `Regenerate()` | `unsafe void` | Regenerates the display of given view.More... |
| `Restore()` | `unsafe bool` | Restores a view to its last remembered rotation, scale and translation.More... |
| `RestoreNavigationHomeView()` | `unsafe void` | Restore and transitions from the current view to the home view.More... |
| `Rotate(NXOpen.Matrix3x3matrix)` | `unsafe void` | Rotates the view by concatenating the given matrix to the existing rotation matrix of the view.More... |
| `Rotate(NXOpen.Point3dorigin,NXOpen.Vector3dvector, double angle)` | `unsafe void` | Rotates the specified view using the specified origin of rotation and about the specified axis.More... |
| `SaveNavigationHomeView()` | `unsafe void` | Save the current view as the home view.More... |
| `SaveViewWithViewName(string replacementChar)` | `unsafeNXOpen.View` | Increment the name of given view with replacement character.More... |
| `SetOrigin(NXOpen.Point3dorigin)` | `unsafe void` | Moves the given position to the center of the view.More... |
| `SetRotationTranslationScale(NXOpen.Matrix3x3rotMatrix,NXOpen.Point3dtranslation, double scale)` | `unsafe void` | Sets the rotation, translation and scale of the specified view.More... |
| `SetScale(double scale)` | `unsafe void` | Sets the scale of the specified view to the desired scale factor.More... |
| `SnapToClosestCannedOrientation()` | `unsafe void` | Changes the orientation of the given view to the orientation of the canned view whose orientation is the closest to that of the given view.More... |
| `SnapToVariantCannedOrientation()` | `unsafe void` | Similar toNXOpen.View.SnapToClosestCannedOrientationexcept it changes the orientation of the given view to the orientation of some canned view "variant" based on I-deas's 'snapview' logic whose orientation is the closest to one of the six orthographic and eight flavors of trimetric views.More... |
| `UpdateCustomSymbols()` | `unsafe void` | Updates custom symbol in a drawing member view or drawing sheetMore... |
| `UpdateDisplay()` | `unsafe void` | Updates the display of given view, as needed.More... |
| `Zoom(NXOpen.View.ScaleFactorscaleFactor)` | `unsafe void` | Scales the specified view to a desired relative scale.More... |
| `ZoomAboutPoint(double relativeScale,NXOpen.Point3dscaleAboutPoint,NXOpen.Point3dviewCenter)` | `unsafe void` | Scales the specified view such that the given scale_about_point does not move.More... |
| `ZoomByRectangle(NXOpen.Point3dcorner1,NXOpen.Point3dcorner2)` | `unsafe void` | Scales the specified view such that the specified rectangle is as large as possible while being fully contained within the viewport.More... |
| `CreateAttributeIterator()` | `unsafeNXOpen.AttributeIterator` | Create an attribute iteratorMore... |
| `DeleteAllAttributesByType(NXOpen.NXObject.AttributeTypetype)` | `unsafe void` | Deletes all attributes of a specific type.More... |
| `DeleteAllAttributesByType(NXOpen.NXObject.AttributeTypetype,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes all attributes of a specific type with the option to update or not.More... |
| `DeleteAttributeByTypeAndTitle(NXOpen.NXObject.AttributeTypetype, string title)` | `unsafe void` | Deletes an attribute by type and title.More... |
| `DeleteAttributeByTypeAndTitle(NXOpen.NXObject.AttributeTypetype, string title,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes an attribute by type and title with the option to update or not.More... |
| `DeleteUserAttribute(NXOpen.NXObject.AttributeTypetype, string title, bool deleteEntireArray,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes the first attribute encountered with the given Type, Title.More... |
| `DeleteUserAttributes(NXOpen.AttributeIteratoriterator,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes the attributes on the object, if any, that satisfy the given iteratorMore... |
| `DeleteUserAttributes(NXOpen.NXObject.AttributeTypetype,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes the attributes encountered with the given Type with option to update or not.More... |
| `FindObject(string journalIdentifier)` | `unsafeNXOpen.INXObject` | Finds theNXOpen.NXObjectwith the given identifier as recorded in a journal.More... |
| `GetAttributeTitlesByType(NXOpen.NXObject.AttributeTypetype)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attribute titles of a specific type.More... |
| `GetBooleanUserAttribute(string title, int index)` | `unsafe bool` | Gets a boolean attribute by Title and array Index.More... |
| `GetComputationalTimeUserAttribute(string title, int index)` | `unsafeNXOpen.NXObject.ComputationalTime` | Gets a time attribute by Title and array Index.More... |
| `GetIntegerAttribute(string title)` | `unsafe int` | Gets an integer attribute by title.More... |
| `GetIntegerUserAttribute(string title, int index)` | `unsafe int` | Gets an integer attribute by Title and array Index.More... |
| `GetNextUserAttribute(NXOpen.AttributeIteratoriterator, outNXOpen.NXObject.AttributeInformationinfo)` | `unsafe bool` | Gets the next attribute encountered on the object, if any, that satisfies the given iterator.More... |
| `GetPdmReferenceAttributeValue(string attributeTitle)` | `unsafe string` | Gets the value of PDM Reference attribute for given object.More... |
| `GetRealAttribute(string title)` | `unsafe double` | Gets a real attribute by title.More... |
| `GetRealUserAttribute(string title, int index)` | `unsafe double` | Gets a real attribute by Title and array Index.More... |
| `GetReferenceAttribute(string title)` | `unsafe string` | Gets the reference string (not the calculated value) of a string attribute that uses a reference string.More... |
| `GetStringAttribute(string title)` | `unsafe string` | Gets a string attribute value by title.More... |
| `GetStringUserAttribute(string title, int index)` | `unsafe string` | Gets a string attribute by Title and array Index.More... |
| `GetTimeAttribute(NXOpen.NXObject.DateAndTimeFormatformat, string title)` | `unsafe string` | Gets a time attribute by title.More... |
| `GetTimeUserAttribute(string title, int index)` | `unsafe string` | Gets a time attribute by Title and array Index.More... |
| `GetUserAttribute(string title,NXOpen.NXObject.AttributeTypetype, int index)` | `unsafeNXOpen.NXObject.AttributeInformation` | Gets the first attribute encountered on the object, if any, with a given Title, Type and array Index.More... |
| `GetUserAttribute(string title, bool includeUnset, bool addStringValues,NXOpen.NXObject.AttributeTypetype)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets the first attribute (or attribute array) encountered on the object, if any, with a given Title and Type.More... |
| `GetUserAttributeAsString(string title,NXOpen.NXObject.AttributeTypetype, int index)` | `unsafe string` | Gets the first attribute encountered on the object, if any, with a given title, type and array index.More... |
| `GetUserAttributeCount(NXOpen.AttributeIteratoriterator)` | `unsafe int` | Gets the count of set attributes on the object, if any, that satisfy the given iterator.More... |
| `GetUserAttributeCount(NXOpen.AttributeIteratoriterator, bool countArrayAsOneAttribute)` | `unsafe int` | Gets the count of set attributes on the object, if any, that satisfy the given iterator.More... |
| `GetUserAttributeCount(NXOpen.NXObject.AttributeTypetype)` | `unsafe int` | Gets the count of set attributes on the object, if any, of the given type.More... |
| `GetUserAttributeCount(NXOpen.NXObject.AttributeTypetype, bool includeUnset, bool countArrayAsOneAttribute)` | `unsafe int` | Gets the count of attributes on the object, if any, of the given type.More... |
| `GetUserAttributeLock(string title,NXOpen.NXObject.AttributeTypetype)` | `unsafe bool` | Determine the lock of the given attribute.More... |
| `GetUserAttributes(NXOpen.AttributeIteratoriterator)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes that have been set on the given object, if any, that satisfy the given iterator.More... |
| `GetUserAttributes()` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes that have been set on the given object.More... |
| `GetUserAttributes(bool includeUnset)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes of the given object.More... |
| `GetUserAttributes(bool includeUnset, bool addStringValues)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes of the given object.More... |
| `GetUserAttributesAsStrings()` | `unsafe string []` | Gets all the attributes that have been set on the given object.More... |
| `GetUserAttributeSize(string title,NXOpen.NXObject.AttributeTypetype)` | `unsafe int` | Gets the size of the first attribute encountered on the object, if any, with a given Title and Type.More... |
| `GetUserAttributeSourceObjects()` | `unsafeNXOpen.NXObject[]` | Returns an array of objects from which this object presents attributes.More... |
| `HasUserAttribute(NXOpen.AttributeIteratoriterator)` | `unsafe bool` | Determines if an attribute exists on the object, that satisfies the given iteratorMore... |
| `HasUserAttribute(string title,NXOpen.NXObject.AttributeTypetype, int index)` | `unsafe bool` | Determines if an attribute with the given Title, Type and array Index is present on the object Unset attributes will not be detected by this function, as its purpose is to test for the actual presence of the attribute on the object.More... |
| `Print()` | `unsafe void` | Prints a representation of this object to the system log file.More... |
| `SetAttribute(string title, int value)` | `unsafe void` | Creates or modifies an integer attribute.More... |
| `SetAttribute(string title, int value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies an integer attribute with the option to update or not.More... |
| `SetAttribute(string title, double value)` | `unsafe void` | Creates or modifies a real attribute.More... |
| `SetAttribute(string title, double value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a real attribute with the option to update or not.More... |
| `SetAttribute(string title, string value)` | `unsafe void` | Creates or modifies a string attribute.More... |
| `SetAttribute(string title, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a string attribute with the option to update or not.More... |
| `SetAttribute(string title)` | `unsafe void` | Creates or modifies a null attribute which is an attribute with a title and no value.More... |
| `SetAttribute(string title,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a null attribute with the option to update or not.More... |
| `SetBooleanUserAttribute(string title, int index, bool value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a boolean attribute with the option to update or not.More... |
| `SetName(string name)` | `unsafe void` | Sets the custom name of the object.More... |
| `SetPdmReferenceAttribute(string attributeTitle, string attributeValue)` | `unsafe void` | Sets the value of PDM Reference attribute on the object.More... |
| `SetReferenceAttribute(string title, string value)` | `unsafe void` | Creates or modifies a string attribute which uses a reference string.More... |
| `SetReferenceAttribute(string title, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a string attribute which uses a reference string, with the option to update or not.More... |
| `SetTimeAttribute(string title, string value)` | `unsafe void` | Creates or modifies a time attribute.More... |
| `SetTimeAttribute(string title, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a time attribute with the option to update or not.More... |
| `SetTimeUserAttribute(string title, int index, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a time attribute with the option to update or not.More... |
| `SetTimeUserAttribute(string title, int index,NXOpen.NXObject.ComputationalTimevalue,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a time attribute with the option to update or not.More... |
| `SetUserAttribute(NXOpen.NXObject.AttributeInformationinfo,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies an attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index, int value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies an integer attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index, double value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a real attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a string attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a null attribute with the option to update or not.More... |
| `SetUserAttributeLock(string title,NXOpen.NXObject.AttributeTypetype, bool @lock)` | `unsafe void` | Lock or unlock the given attribute.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `DraftingBodies[get]` | `NXOpen.Drawings.DraftingBodyCollection` | Returns the DraftingBodyCollectionMore... |
| `IsActiveForSketching[get]` | `unsafe bool` | Returns true if this view is the active sketch view.More... |
| `IsBroken[get]` | `unsafe bool` | Returns the status on whether thisNXOpen.Drawings.DraftingViewis broken.More... |
| `IsDecoration[get]` | `unsafe bool` | Returns the status on whether thisNXOpen.Drawings.DraftingViewis decoration.More... |
| `IsOutOfDate[get]` | `unsafe bool` | Returns the status on whether thisNXOpen.Drawings.DraftingViewis out of date.More... |
| `IsSlave[get]` | `unsafe bool` | Returns the status on whether thisNXOpen.Drawings.DraftingViewis slave.More... |
| `Style[get]` | `NXOpen.Drawings.ViewStyle` | Returns object to View StyleMore... |
| `ViewBreaks[get]` | `NXOpen.Drawings.ViewBreakCollection` | Returns the ViewBreakCollection instance belonging to this viewMore... |
| `AbsoluteOrigin[get]` | `unsafeNXOpen.Point3d` | Returns the view origin in absolute space.More... |
| `DependentDisplay[get]` | `NXOpen.ViewDependentDisplayManager` | Returns an object to perform all view dependent display operationsMore... |
| `DisclosurePurpose[get, set]` | `unsafe string` | Returns or sets the Disclosure Purpose.More... |
| `IsDisclosed[get]` | `unsafe bool` | Returns the disclosure status of the view.More... |
| `LockRotations[get, set]` | `unsafe bool` | Returns or sets the "Lock Rotations" toggle state of a view.More... |
| `Matrix[get]` | `unsafeNXOpen.Matrix3x3` | Returns the view matrix.More... |
| `Origin[get]` | `unsafeNXOpen.Point3d` | Returns the view origin.More... |
| `RenderingStyle[get, set]` | `unsafeNXOpen.View.RenderingStyleType` | Returns or sets the rendering style of the view.More... |
| `Scale[get]` | `unsafe double` | Returns the view scale.More... |
| `SyncViews[get, set]` | `unsafe bool` | Returns or sets the "Synchronized Views" toggle state of a view.More... |
| `TriadVisibility[get, set]` | `unsafe bool` | Returns or sets the visibility of the view triad in the view.More... |
| `VisualizationSpecialEffectsPreferences[get]` | `NXOpen.Preferences.ViewVisualizationSpecialEffects` | Returns an object to perform all visualization Special Effects related preferences settingsMore... |
| `VisualizationVisualPreferences[get]` | `NXOpen.Preferences.ViewVisualizationVisual` | Returns an object to perform all visualization related preferences settingsMore... |
| `WcsVisibility[get, set]` | `unsafe bool` | Returns or sets the visibility of the WCS in the view.More... |
| `IsOccurrence[get]` | `unsafe bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `unsafe string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Name[get]` | `unsafe string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `unsafeNXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `unsafeNXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `unsafeNXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |
| `IsOccurrence[get]` | `bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Name[get]` | `string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `NXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `NXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `NXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |


---

## NXOpen.Drawings.DraftingViewCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49536.html

Represents a collection ofNXOpen.Drawings.DraftingViews

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `ConvertLegacyViewsToLightweight(NXOpen.Drawings.DraftingView[] views)` | `unsafe void` | Converts legacy views to lightweight.More... |
| `CreateAddRemoveBoxViewBuilder(NXOpen.Drawings.DraftingViewactiveView)` | `unsafeNXOpen.Drawings.AddRemoveBoxViewBuilder` | Creates aNXOpen.Drawings.AddRemoveBoxViewBuilderMore... |
| `CreateBaseViewBuilder(NXOpen.Drawings.BaseViewview)` | `unsafeNXOpen.Drawings.BaseViewBuilder` | Creates the Base View BuilderMore... |
| `CreateBrokenViewBuilder(NXOpen.Drawings.ViewBreakviewbreak)` | `unsafeNXOpen.Drawings.BrokenViewBuilder` | Creates aNXOpen.Drawings.BrokenViewBuilderMore... |
| `CreateCopyTo3dBuilder()` | `unsafeNXOpen.Drawings.ViewCopyTo3dBuilder` | Creates aNXOpen.Drawings.ViewCopyTo3dBuilderMore... |
| `CreateCustomViewSettingsBuilder()` | `unsafeNXOpen.Drawings.CustomViewSettingsBuilder` | Creates aNXOpen.Drawings.CustomViewSettingsBuilderMore... |
| `CreateDetailViewBuilder(NXOpen.Drawings.DetailViewview)` | `unsafeNXOpen.Drawings.DetailViewBuilder` | Creates aNXOpen.Drawings.DetailViewBuilderMore... |
| `CreateDrawingViewBuilder(NXOpen.Drawings.DrawingViewdrawingview)` | `unsafeNXOpen.Drawings.DrawingViewBuilder` | Creates a DrawingViewBuilderMore... |
| `CreateProjectedViewBuilder(NXOpen.Drawings.ProjectedViewview)` | `unsafeNXOpen.Drawings.ProjectedViewBuilder` | Creates the Projected View BuilderMore... |
| `CreateRefineDisplayBuilder()` | `unsafeNXOpen.Drawings.RefineDisplayBuilder` | Creates aNXOpen.Drawings.RefineDisplayBuilderMore... |
| `CreateSecondaryGeometryInViewsBuilder()` | `unsafeNXOpen.Drawings.SecondaryGeometryInViewsBuilder` | Creates aNXOpen.Drawings.SecondaryGeometryInViewsBuilderMore... |
| `CreateSectionInViewBuilder()` | `unsafeNXOpen.Drawings.SectionInViewBuilder` | Creates the Section In View BuilderMore... |
| `CreateSectionViewBuilder(NXOpen.NXObjectsectionViewOrSectionLine)` | `unsafeNXOpen.Drawings.SectionViewBuilder` | Creates the Section View BuilderMore... |
| `CreateShipbuildingLineBuilder()` | `unsafeNXOpen.Drawings.ViewStyleShipbuildingLinesBuilder` | Creates aNXOpen.Drawings.ViewStyleShipbuildingLinesBuilderMore... |
| `CreateStandardViewsBuilder()` | `unsafeNXOpen.Drawings.StandardViewsBuilder` | Creates a StandardViewsBuilderMore... |
| `CreateUpdateViewsBuilder()` | `unsafeNXOpen.Drawings.UpdateViewsBuilder` | Creates the Update Views BuilderMore... |
| `CreateViewCreationWizardBuilder()` | `unsafeNXOpen.Drawings.ViewCreationWizardBuilder` | Creates aNXOpen.Drawings.ViewCreationWizardBuilderMore... |
| `CreateViewProjectionBuilder()` | `unsafeNXOpen.Drawings.ViewProjectionBuilder` | Creates aNXOpen.Drawings.ViewProjectionBuilderMore... |
| `DeleteViewsInOriginalPart(NXOpen.Drawings.DraftingView[] views)` | `unsafe void` | Deletes views in original partMore... |
| `FindObject(string journalIdentifier)` | `unsafeNXOpen.Drawings.DraftingView` | Finds theNXOpen.Drawings.DraftingViewwith the given identifier as recorded in a journal.More... |
| `GetParentOfView(NXOpen.Viewview)` | `unsafeNXOpen.ModelingView` | Find the parent cut (sectioned) model view of a drawing member view.More... |
| `MoveViewsToDrawing(NXOpen.Drawings.DraftingView[] views,NXOpen.Drawings.DrawingSheetdrawing)` | `unsafe void` | Move views to drawingMore... |
| `PasteViews(NXOpen.Drawings.DrawingSheetdrawing,NXOpen.Drawings.DraftingView[] views,NXOpen.Drawings.DraftingViewCollection.ViewCopyDetailOptiondetailOption,NXOpen.Drawings.DraftingViewCollection.ViewCopyAnnotOptionannotOption, outNXOpen.Drawings.DraftingView[] newViews)` | `unsafe void` | Paste viewsMore... |
| `RestoreViewBreaks(NXOpen.Drawings.DraftingViewview)` | `unsafe void` | Restore all view breaks of the view suppressed byDrawings.DraftingViewCollection.SuppressViewBreaksMore... |
| `SuppressViewBreaks(NXOpen.Drawings.DraftingViewview)` | `unsafe void` | Suppress all view breaks of the view.More... |
| `ToArray()` | `NXOpen.Drawings.DraftingView[]` | Returns an array ofNXOpen.Drawings.DraftingViewobjects.More... |
| `UpdateSheetsAndViews(NXOpen.NXObject[] inputViews)` | `unsafe void` | Updates the drawing sheets and drafting views.More... |
| `UpdateViewBreaks(NXOpen.Drawings.DraftingViewview)` | `unsafe void` | Log all view breaks of the view for updateMore... |
| `UpdateViews(NXOpen.Drawings.DraftingViewCollection.ViewUpdateOptionupdateOption)` | `unsafe void` | Updates drafting views in the part determined by an update option.More... |
| `UpdateViews(NXOpen.Drawings.DraftingViewCollection.ViewUpdateOptionupdateOption,NXOpen.Drawings.DrawingSheetdrawing)` | `unsafe void` | Updates drafting views in a sheet determined by an update option.More... |
| `UpdateViews(NXOpen.Drawings.DraftingView[] views)` | `unsafe void` | Updates the drafting views.More... |
| `GetEnumerator()` | `IEnumerator` | Returns an enumerator that iterates through a collection.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |
| `EnumerateMoveNext(refTagcurrentTag, byte [] state)` | `override int` | Advances the enumerator to the next element of the collection.More... |
| `initialize()` | `new void` | <exclude>More... |
| `initialize()` | `void` | <exclude>More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.DrawingCompareSettingsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49540.html

Represents aNXOpen.Drawings.DrawingCompareSettingsBuilderbuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `BaselineForComparison[get, set]` | `unsafeNXOpen.Drawings.DrawingCompareSettingsBuilder.ComparisonBaseline` | Returns or sets the baseline for comparisonMore... |
| `CenterlineCompare[get, set]` | `unsafe bool` | Returns or sets the centerline compareMore... |
| `Color[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the colorMore... |
| `CompareTolerance[get, set]` | `unsafe double` | Returns or sets the compare toleranceMore... |
| `CrosshatchAreaFillsCompare[get, set]` | `unsafe bool` | Returns or sets the crosshatch area fills compareMore... |
| `DatumFeatureSymbolCompare[get, set]` | `unsafe bool` | Returns or sets the datum feature symbol compareMore... |
| `DatumFeatureSymbolLeaderTerminatorCompare[get, set]` | `unsafe bool` | Returns or sets the datum feature symbol leader info compareMore... |
| `DatumFeatureSymbolOriginCompare[get, set]` | `unsafe bool` | Returns or sets the datum feature symbol origin compareMore... |
| `DatumFeatureSymbolRetainedStatusCompare[get, set]` | `unsafe bool` | Returns or sets the datum feature symbol retained status compareMore... |
| `DatumFeatureSymbolTextCompare[get, set]` | `unsafe bool` | Returns or sets the datum feature symbol text compareMore... |
| `DatumTargetCompare[get, set]` | `unsafe bool` | Returns or sets the datum target compareMore... |
| `DatumTargetLeaderTerminatorCompare[get, set]` | `unsafe bool` | Returns or sets the datum target leader info compareMore... |
| `DatumTargetOriginCompare[get, set]` | `unsafe bool` | Returns or sets the datum target origin compareMore... |
| `DatumTargetRetainedStatusCompare[get, set]` | `unsafe bool` | Returns or sets the datum target retained status compareMore... |
| `DatumTargetTextCompare[get, set]` | `unsafe bool` | Returns or sets the datum target text compareMore... |
| `DimCompare[get, set]` | `unsafe bool` | Returns or sets the dim compareMore... |
| `DimOriginCompare[get, set]` | `unsafe bool` | Returns or sets the dim origin compareMore... |
| `DimRetainedStatusCompare[get, set]` | `unsafe bool` | Returns or sets the dim retained status compareMore... |
| `DimSizeCompare[get, set]` | `unsafe bool` | Returns or sets the dim size compareMore... |
| `DisplayChangeSymbol[get, set]` | `unsafe bool` | Returns or sets the display change symbolMore... |
| `FcfCompare[get, set]` | `unsafe bool` | Returns or sets the fcf compareMore... |
| `FcfLeaderTerminatorCompare[get, set]` | `unsafe bool` | Returns or sets the fcf leader info compareMore... |
| `FcfOriginCompare[get, set]` | `unsafe bool` | Returns or sets the fcf origin compareMore... |
| `FcfRetainedStatusCompare[get, set]` | `unsafe bool` | Returns or sets the fcf retained status compareMore... |
| `FcfTextCompare[get, set]` | `unsafe bool` | Returns or sets the fcf text compareMore... |
| `NoteCompare[get, set]` | `unsafe bool` | Returns or sets the note compareMore... |
| `NoteLeaderTerminatorCompare[get, set]` | `unsafe bool` | Returns or sets the note leader info compareMore... |
| `NoteOriginCompare[get, set]` | `unsafe bool` | Returns or sets the note origin compareMore... |
| `NoteRetainedStatusCompare[get, set]` | `unsafe bool` | Returns or sets the note retained status compareMore... |
| `NoteTextCompare[get, set]` | `unsafe bool` | Returns or sets the note text compareMore... |
| `PartListCompare[get, set]` | `unsafe bool` | Returns or sets the part list compareMore... |
| `RestartNumbers[get, set]` | `unsafe bool` | Returns or sets the restart numbersMore... |
| `SheetCompare[get, set]` | `unsafe bool` | Returns or sets the sheet compareMore... |
| `SymbolCompare[get, set]` | `unsafe bool` | Returns or sets the symbol compareMore... |
| `SymbolFont[get, set]` | `unsafeNXOpen.Drawings.DrawingCompareSettingsBuilder.FontType` | Returns or sets the symbol fontMore... |
| `SymbolLeaderTerminatorCompare[get, set]` | `unsafe bool` | Returns or sets the symbol leader info compareMore... |
| `SymbolOriginCompare[get, set]` | `unsafe bool` | Returns or sets the symbol origin compareMore... |
| `SymbolRetainedStatusCompare[get, set]` | `unsafe bool` | Returns or sets the symbol retained status compareMore... |
| `SymbolSize[get, set]` | `unsafe double` | Returns or sets the symbol sizeMore... |
| `SymbolTextCompare[get, set]` | `unsafe bool` | Returns or sets the symbol text compareMore... |
| `SymbolType[get, set]` | `unsafeNXOpen.Drawings.DrawingCompareSettingsBuilder.ChangeSymbolType` | Returns or sets the symbol typeMore... |
| `SymbolWidth[get, set]` | `unsafeNXOpen.Drawings.DrawingCompareSettingsBuilder.WidthType` | Returns or sets the symbol widthMore... |
| `TableCompare[get, set]` | `unsafe bool` | Returns or sets the table compareMore... |
| `ViewCompare[get, set]` | `unsafe bool` | Returns or sets the view compareMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.DrawingFormatSheetBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49544.html

Represents aNXOpen.Drawings.DrawingFormatSheetBuilder

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
| `InitialSecondarySheetNumber[get, set]` | `unsafe string` | Returns or sets the initial secondary sheet numberMore... |
| `InitialSheetNumber[get, set]` | `unsafe string` | Returns or sets the initial sheet numberMore... |
| `SecondaryNumberDelimiter[get, set]` | `unsafe string` | Returns or sets the secondary number delimiterMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.DrawingRegion

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49548.html

Represents a Drawing Region


---

## NXOpen.Drawings.DrawingRegionBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49552.html

Represents a Drawing Region Builder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetNextLinkedRegion(NXOpen.Drawings.DrawingRegionnextLinkedRegion)` | `unsafe void` | Set the next linked regionsMore... |
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
| `DrawingRegionRulesBuilder[get]` | `unsafeNXOpen.Drawings.DrawingRegionRulesBuilder` | Returns the DrawingRegionRules builderMore... |
| `Gap[get, set]` | `unsafe double` | Returns or sets the gapMore... |
| `GrowthDirection[get, set]` | `unsafeNXOpen.Drawings.DrawingRegionBuilder.RegionGrowthDirection` | Returns or sets the growth direction (this is forNXOpen.Annotations.CustomSymbolandNXOpen.Annotations.Note)More... |
| `Height[get]` | `unsafeNXOpen.Expression` | Returns the heightMore... |
| `HorizontalGrowthDirection[get, set]` | `unsafeNXOpen.Drawings.DrawingRegionBuilder.RegionHorizontalGrowthDirection` | Returns or sets the horizantal growth directionMore... |
| `Length[get]` | `unsafeNXOpen.Expression` | Returns the lengthMore... |
| `MoveContent[get, set]` | `unsafeNXOpen.Drawings.DrawingRegionBuilder.ContentToMove` | Returns or sets the move contentMore... |
| `Name[get, set]` | `unsafe string` | Returns or sets the nameMore... |
| `ObjectType[get, set]` | `unsafeNXOpen.Drawings.DrawingRegionBuilder.RegionDraftingObjectType` | Returns or sets the typeMore... |
| `Origin[get, set]` | `unsafeNXOpen.Point` | Returns or sets the originMore... |
| `Priority[get, set]` | `unsafe int` | Returns or sets the priorityMore... |
| `SpecifyContinuation[get, set]` | `unsafeNXOpen.Drawings.DrawingRegionBuilder.RegionContinuation` | Returns or sets the continuationMore... |
| `VerticalGrowthDirection[get, set]` | `unsafeNXOpen.Drawings.DrawingRegionBuilder.RegionVerticalGrowthDirection` | Returns or sets the vertical growth directionMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.DrawingRegionCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49556.html

Represents a collection of drawing regions

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateAddObjectsToRegionBuilder()` | `unsafeNXOpen.Drawings.AddObjectsToRegionBuilder` | Creates add objects to region builderMore... |
| `CreateDrawingRegionBuilder(NXOpen.Drawings.DrawingRegion@object)` | `unsafeNXOpen.Drawings.DrawingRegionBuilder` | Creates the DrawingRegion builderMore... |
| `CreateRemoveObjectsBuilder()` | `unsafeNXOpen.Drawings.RemoveObjectsBuilder` | Creates remove objects builderMore... |
| `CreateSelectRegionBuilder()` | `unsafeNXOpen.Drawings.SelectRegionBuilder` | Creates select region builderMore... |
| `FindObject(string name)` | `unsafeNXOpen.Drawings.DrawingRegion` | Finds theNXOpen.Drawings.DrawingRegionwith the given name.More... |
| `ToArray()` | `NXOpen.Drawings.DrawingRegion[]` | Returns an array ofNXOpen.Drawings.DrawingRegionobjects.More... |
| `GetEnumerator()` | `IEnumerator` | Returns an enumerator that iterates through a collection.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |
| `EnumerateMoveNext(refTagcurrentTag, byte [] state)` | `override int` | Advances the enumerator to the next element of the collection.More... |
| `initialize()` | `new void` | <exclude>More... |
| `initialize()` | `void` | <exclude>More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.DrawingRegionRulesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49560.html

Represents a Drawing region rules builder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetRules()` | `unsafe string []` | Get RulesMore... |
| `RemoveRules(string [] rules)` | `unsafe void` | Remove RulesMore... |
| `SetRules(string [] rules)` | `unsafe void` | Set RulesMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |


---

## NXOpen.Drawings.DrawingSheet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49564.html

Represents a drawing sheet

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `ActivateForSketching()` | `unsafe void` | Sets this drawingsheet's view as the active sketch view.More... |
| `GetDraftingSketches()` | `unsafeNXOpen.Sketch[]` | Returns all draftingNXOpen.Sketches on a sheet.More... |
| `GetDraftingViews()` | `unsafeNXOpen.Drawings.DraftingView[]` | Returns theNXOpen.Drawings.DraftingViews on a sheet.More... |
| `GetScale(out double numerator, out double denominator)` | `unsafe void` | Returns the scale of the drawing sheet.More... |
| `GetSheetZoneReference(NXOpen.Drawings.DraftingViewviewTag)` | `unsafe string` | Returns the sheet and zone location or reference of the view if sheet zones are defined.More... |
| `GetZoneReference(NXOpen.Drawings.DraftingViewviewTag)` | `unsafe string` | Returns the zone location or reference of the view if sheet zones are defined.More... |
| `Open()` | `unsafe void` | Displays and activates the drawing sheet so that it can be edited.More... |
| `ResetActiveForSketching()` | `unsafe void` | Resets active for sketching view in given drawing.More... |
| `SetParameters(double height, double length, double numerator, double denominator,NXOpen.Drawings.DrawingSheet.Unitunits,NXOpen.Drawings.DrawingSheet.ProjectionAngleTypeprojectionAngle, outNXOpen.Drawings.DraftingView[] associatedViews)` | `unsafe void` | Sets the parameters of the drawing sheet.More... |
| `CreateAttributeIterator()` | `unsafeNXOpen.AttributeIterator` | Create an attribute iteratorMore... |
| `DeleteAllAttributesByType(NXOpen.NXObject.AttributeTypetype)` | `unsafe void` | Deletes all attributes of a specific type.More... |
| `DeleteAllAttributesByType(NXOpen.NXObject.AttributeTypetype,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes all attributes of a specific type with the option to update or not.More... |
| `DeleteAttributeByTypeAndTitle(NXOpen.NXObject.AttributeTypetype, string title)` | `unsafe void` | Deletes an attribute by type and title.More... |
| `DeleteAttributeByTypeAndTitle(NXOpen.NXObject.AttributeTypetype, string title,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes an attribute by type and title with the option to update or not.More... |
| `DeleteUserAttribute(NXOpen.NXObject.AttributeTypetype, string title, bool deleteEntireArray,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes the first attribute encountered with the given Type, Title.More... |
| `DeleteUserAttributes(NXOpen.AttributeIteratoriterator,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes the attributes on the object, if any, that satisfy the given iteratorMore... |
| `DeleteUserAttributes(NXOpen.NXObject.AttributeTypetype,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes the attributes encountered with the given Type with option to update or not.More... |
| `FindObject(string journalIdentifier)` | `unsafeNXOpen.INXObject` | Finds theNXOpen.NXObjectwith the given identifier as recorded in a journal.More... |
| `GetAttributeTitlesByType(NXOpen.NXObject.AttributeTypetype)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attribute titles of a specific type.More... |
| `GetBooleanUserAttribute(string title, int index)` | `unsafe bool` | Gets a boolean attribute by Title and array Index.More... |
| `GetComputationalTimeUserAttribute(string title, int index)` | `unsafeNXOpen.NXObject.ComputationalTime` | Gets a time attribute by Title and array Index.More... |
| `GetIntegerAttribute(string title)` | `unsafe int` | Gets an integer attribute by title.More... |
| `GetIntegerUserAttribute(string title, int index)` | `unsafe int` | Gets an integer attribute by Title and array Index.More... |
| `GetNextUserAttribute(NXOpen.AttributeIteratoriterator, outNXOpen.NXObject.AttributeInformationinfo)` | `unsafe bool` | Gets the next attribute encountered on the object, if any, that satisfies the given iterator.More... |
| `GetPdmReferenceAttributeValue(string attributeTitle)` | `unsafe string` | Gets the value of PDM Reference attribute for given object.More... |
| `GetRealAttribute(string title)` | `unsafe double` | Gets a real attribute by title.More... |
| `GetRealUserAttribute(string title, int index)` | `unsafe double` | Gets a real attribute by Title and array Index.More... |
| `GetReferenceAttribute(string title)` | `unsafe string` | Gets the reference string (not the calculated value) of a string attribute that uses a reference string.More... |
| `GetStringAttribute(string title)` | `unsafe string` | Gets a string attribute value by title.More... |
| `GetStringUserAttribute(string title, int index)` | `unsafe string` | Gets a string attribute by Title and array Index.More... |
| `GetTimeAttribute(NXOpen.NXObject.DateAndTimeFormatformat, string title)` | `unsafe string` | Gets a time attribute by title.More... |
| `GetTimeUserAttribute(string title, int index)` | `unsafe string` | Gets a time attribute by Title and array Index.More... |
| `GetUserAttribute(string title,NXOpen.NXObject.AttributeTypetype, int index)` | `unsafeNXOpen.NXObject.AttributeInformation` | Gets the first attribute encountered on the object, if any, with a given Title, Type and array Index.More... |
| `GetUserAttribute(string title, bool includeUnset, bool addStringValues,NXOpen.NXObject.AttributeTypetype)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets the first attribute (or attribute array) encountered on the object, if any, with a given Title and Type.More... |
| `GetUserAttributeAsString(string title,NXOpen.NXObject.AttributeTypetype, int index)` | `unsafe string` | Gets the first attribute encountered on the object, if any, with a given title, type and array index.More... |
| `GetUserAttributeCount(NXOpen.AttributeIteratoriterator)` | `unsafe int` | Gets the count of set attributes on the object, if any, that satisfy the given iterator.More... |
| `GetUserAttributeCount(NXOpen.AttributeIteratoriterator, bool countArrayAsOneAttribute)` | `unsafe int` | Gets the count of set attributes on the object, if any, that satisfy the given iterator.More... |
| `GetUserAttributeCount(NXOpen.NXObject.AttributeTypetype)` | `unsafe int` | Gets the count of set attributes on the object, if any, of the given type.More... |
| `GetUserAttributeCount(NXOpen.NXObject.AttributeTypetype, bool includeUnset, bool countArrayAsOneAttribute)` | `unsafe int` | Gets the count of attributes on the object, if any, of the given type.More... |
| `GetUserAttributeLock(string title,NXOpen.NXObject.AttributeTypetype)` | `unsafe bool` | Determine the lock of the given attribute.More... |
| `GetUserAttributes(NXOpen.AttributeIteratoriterator)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes that have been set on the given object, if any, that satisfy the given iterator.More... |
| `GetUserAttributes()` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes that have been set on the given object.More... |
| `GetUserAttributes(bool includeUnset)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes of the given object.More... |
| `GetUserAttributes(bool includeUnset, bool addStringValues)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes of the given object.More... |
| `GetUserAttributesAsStrings()` | `unsafe string []` | Gets all the attributes that have been set on the given object.More... |
| `GetUserAttributeSize(string title,NXOpen.NXObject.AttributeTypetype)` | `unsafe int` | Gets the size of the first attribute encountered on the object, if any, with a given Title and Type.More... |
| `GetUserAttributeSourceObjects()` | `unsafeNXOpen.NXObject[]` | Returns an array of objects from which this object presents attributes.More... |
| `HasUserAttribute(NXOpen.AttributeIteratoriterator)` | `unsafe bool` | Determines if an attribute exists on the object, that satisfies the given iteratorMore... |
| `HasUserAttribute(string title,NXOpen.NXObject.AttributeTypetype, int index)` | `unsafe bool` | Determines if an attribute with the given Title, Type and array Index is present on the object Unset attributes will not be detected by this function, as its purpose is to test for the actual presence of the attribute on the object.More... |
| `Print()` | `unsafe void` | Prints a representation of this object to the system log file.More... |
| `SetAttribute(string title, int value)` | `unsafe void` | Creates or modifies an integer attribute.More... |
| `SetAttribute(string title, int value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies an integer attribute with the option to update or not.More... |
| `SetAttribute(string title, double value)` | `unsafe void` | Creates or modifies a real attribute.More... |
| `SetAttribute(string title, double value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a real attribute with the option to update or not.More... |
| `SetAttribute(string title, string value)` | `unsafe void` | Creates or modifies a string attribute.More... |
| `SetAttribute(string title, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a string attribute with the option to update or not.More... |
| `SetAttribute(string title)` | `unsafe void` | Creates or modifies a null attribute which is an attribute with a title and no value.More... |
| `SetAttribute(string title,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a null attribute with the option to update or not.More... |
| `SetBooleanUserAttribute(string title, int index, bool value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a boolean attribute with the option to update or not.More... |
| `SetName(string name)` | `unsafe void` | Sets the custom name of the object.More... |
| `SetPdmReferenceAttribute(string attributeTitle, string attributeValue)` | `unsafe void` | Sets the value of PDM Reference attribute on the object.More... |
| `SetReferenceAttribute(string title, string value)` | `unsafe void` | Creates or modifies a string attribute which uses a reference string.More... |
| `SetReferenceAttribute(string title, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a string attribute which uses a reference string, with the option to update or not.More... |
| `SetTimeAttribute(string title, string value)` | `unsafe void` | Creates or modifies a time attribute.More... |
| `SetTimeAttribute(string title, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a time attribute with the option to update or not.More... |
| `SetTimeUserAttribute(string title, int index, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a time attribute with the option to update or not.More... |
| `SetTimeUserAttribute(string title, int index,NXOpen.NXObject.ComputationalTimevalue,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a time attribute with the option to update or not.More... |
| `SetUserAttribute(NXOpen.NXObject.AttributeInformationinfo,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies an attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index, int value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies an integer attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index, double value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a real attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a string attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a null attribute with the option to update or not.More... |
| `SetUserAttributeLock(string title,NXOpen.NXObject.AttributeTypetype, bool @lock)` | `unsafe void` | Lock or unlock the given attribute.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `BordersAndZones[get, set]` | `unsafeNXOpen.Drawings.BordersAndZones` | Returns or sets the borders and zones object if presentMore... |
| `Height[get]` | `unsafe double` | Returns the height of the drawing sheet.More... |
| `IsActiveForSketching[get]` | `unsafe bool` | Returns true if this drawing sheet's view is the active sketch view.More... |
| `IsOutOfDate[get]` | `unsafe bool` | Returns the status on whether thisNXOpen.Drawings.DrawingSheetis out of date.More... |
| `Length[get]` | `unsafe double` | Returns the length of the drawing sheet.More... |
| `ProjectionAngle[get]` | `unsafeNXOpen.Drawings.DrawingSheet.ProjectionAngleType` | Returns the projection angle of the drawing sheet.More... |
| `SheetDraftingViews[get]` | `NXOpen.Drawings.SheetDraftingViewCollection` | Returns the SheetDraftingViewCollection instance belonging to this drawing sheetMore... |
| `SheetSectionLines[get]` | `NXOpen.Drawings.SheetSectionLineCollection` | Returns the SheetSectionLineCollection instance belonging to this drawing sheetMore... |
| `Units[get]` | `unsafeNXOpen.Drawings.DrawingSheet.Unit` | Returns the units of the drawing sheet.More... |
| `View[get]` | `unsafeNXOpen.View` | Returns theNXOpen.Viewthat represents this drawing sheet.More... |
| `IsOccurrence[get]` | `unsafe bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `unsafe string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Name[get]` | `unsafe string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `unsafeNXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `unsafeNXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `unsafeNXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |
| `IsOccurrence[get]` | `bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Name[get]` | `string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `NXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `NXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `NXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |


---

## NXOpen.Drawings.DrawingSheetBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49568.html

Represents aNXOpen.Drawings.DrawingSheetBuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AutoStartBaseView[get, set]` | `unsafe bool` | Returns or sets the setting that controls whether or not the Add Base View command is automatically started after inserting a sheet that has no views on it.More... |
| `AutoStartViewCreation[get, set]` | `unsafe bool` | Returns or sets the setting that controls whether or not the Add View creation is automatically started after inserting a sheet that has no views on it.More... |
| `BaseordrawingView[get, set]` | `unsafeNXOpen.Drawings.DrawingSheetBuilder.SheetBaseordrawingView` | Returns or sets the option of base view or drawing viewMore... |
| `EnglishSheetTemplateLocation[get, set]` | `unsafe string` | Returns or sets the location of the english drawing sheet template to be added to the part fileMore... |
| `Height[get, set]` | `unsafe double` | Returns or sets the custom or standard height for the drawing sheetMore... |
| `Length[get, set]` | `unsafe double` | Returns or sets the custom or standard length to be used for the drawing to be created or edited.More... |
| `MetricSheetTemplateLocation[get, set]` | `unsafe string` | Returns or sets the location of the metric drawing sheet template to be added to the part fileMore... |
| `Name[get, set]` | `unsafe string` | Returns or sets the name of the drawing sheet to be created or editedMore... |
| `Number[get, set]` | `unsafe string` | Returns or sets the number of the drawing sheet to be created or editedMore... |
| `Option[get, set]` | `unsafeNXOpen.Drawings.DrawingSheetBuilder.SheetOption` | Returns or sets the option to be used to create the drawing sheetMore... |
| `ProjectionAngle[get, set]` | `unsafeNXOpen.Drawings.DrawingSheetBuilder.SheetProjectionAngle` | Returns or sets the projection_angle optionMore... |
| `Revision[get, set]` | `unsafe string` | Returns or sets the revision of the drawing sheet to be created or editedMore... |
| `ScaleDenominator[get, set]` | `unsafe double` | Returns or sets the denominator of a custom scaleMore... |
| `ScaleNumerator[get, set]` | `unsafe double` | Returns or sets the numerator of a custom scaleMore... |
| `SecondaryNumber[get, set]` | `unsafe string` | Returns or sets the secondary number of the drawing sheet to be created or editedMore... |
| `StandardEnglishScale[get, set]` | `unsafeNXOpen.Drawings.DrawingSheetBuilder.SheetStandardEnglishScale` | Returns or sets the standard English drawing scaleMore... |
| `StandardMetricScale[get, set]` | `unsafeNXOpen.Drawings.DrawingSheetBuilder.SheetStandardMetricScale` | Returns or sets the standard Metric drawing scaleMore... |
| `Units[get, set]` | `unsafeNXOpen.Drawings.DrawingSheetBuilder.SheetUnits` | Returns or sets the units for the drawing sheetMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.DrawingSheetCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49572.html

Represents a collection of drawing sheets

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `DrawingSheetBuilder(NXOpen.Drawings.DrawingSheetsheet)` | `unsafeNXOpen.Drawings.DrawingSheetBuilder` | Create a drawing Sheet builderMore... |
| `FindObject(string journalIdentifier)` | `unsafeNXOpen.Drawings.DrawingSheet` | Finds theNXOpen.Drawings.DrawingSheetwith the given identifier as recorded in a journal.More... |
| `InsertSheet(string drawingName,NXOpen.Drawings.DrawingSheet.UnitdrawingUnits, double width, double height, double numerator, double denominator,NXOpen.Drawings.DrawingSheet.ProjectionAngleTypeprojectionAngle)` | `unsafeNXOpen.Drawings.DrawingSheet` | Inserts a sheet into a part.More... |
| `InsertSheet(string drawingName,NXOpen.Drawings.DrawingSheet.StandardSheetSizesheetSize, double numerator, double denominator,NXOpen.Drawings.DrawingSheet.ProjectionAngleTypeprojectionAngle)` | `unsafeNXOpen.Drawings.DrawingSheet` | Inserts a sheet into a part.More... |
| `PasteDrawingSheets(NXOpen.Drawings.DrawingSheet[] dwgSheets, outNXOpen.Drawings.DrawingSheet[] newPastedDwgSheets)` | `unsafe void` | Paste drawing sheetsMore... |
| `RefreshCurrentSheet()` | `unsafe void` | Refresh the current SheetMore... |
| `ToArray()` | `NXOpen.Drawings.DrawingSheet[]` | Returns an array ofNXOpen.Drawings.DrawingSheetobjects.More... |
| `GetEnumerator()` | `IEnumerator` | Returns an enumerator that iterates through a collection.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |
| `EnumerateMoveNext(refTagcurrentTag, byte [] state)` | `override int` | Advances the enumerator to the next element of the collection.More... |
| `initialize()` | `new void` | <exclude>More... |
| `initialize()` | `void` | <exclude>More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CurrentDrawingSheet[get]` | `unsafeNXOpen.Drawings.DrawingSheet` | Returns the currently opened drawing sheet.More... |
| `SheetTemplates[get]` | `NXOpen.Drawings.SheetTemplateManager` | Returns the Sheet Template Manager for partMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.DrawingView

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49580.html

Drawing View - an empty view created without any geometric objects


---

## NXOpen.Drawings.DrawingViewBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49584.html

This builder allows the user to create a Drawing View

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CenterCoordinate[get]` | `unsafeNXOpen.Drawings.ViewCenterCoordinateBuilder` | Returns the center coordinateMore... |
| `MultipleViewPlacement[get]` | `unsafeNXOpen.Drawings.MultipleViewPlacementBuilder` | Returns the multiple view placementMore... |
| `Scale[get]` | `unsafeNXOpen.Drawings.ViewScaleBuilder` | Returns the view scaleMore... |
| `TwodOrientation[get]` | `unsafeNXOpen.Drawings.View2dOrientBuilder` | Returns the view orientation in 2DMore... |
| `ViewBoundary[get]` | `unsafeNXOpen.Drawings.ViewBoundaryBuilder` | Returns the view boundary.More... |
| `ViewPlacement[get]` | `unsafeNXOpen.Drawings.ViewPlacementBuilder` | Returns the view placement.More... |
| `ViewStyle[get]` | `unsafeNXOpen.Drawings.ViewStyleBuilder` | Returns the view styleMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.DrawingsPropertiesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49576.html

Represents anNXOpen.Drawings.DrawingsPropertiesBuilderto be used for marking the component as secondary geometry

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `SecondaryComponent[get, set]` | `unsafeNXOpen.Drawings.DrawingsPropertiesBuilder.SecondaryComponentOptions` | Returns or sets the secondary geometry state.More... |
| `SelectedObjects[get]` | `unsafeNXOpen.Assemblies.SelectComponentList` | Returns the selected object(s) list.More... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.EditSectionLineSettingsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49588.html

Represents aNXOpen.Drawings.EditSectionLineSettingsBuilderbuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `InheritSettingsFromCustomerDefault()` | `unsafe void` | Inherit Settings From Customer DefaultMore... |
| `InheritSettingsFromPreferences()` | `unsafe void` | Inherit Settings From PreferenceMore... |
| `InheritSettingsFromSelectedObjects(NXOpen.Drawings.SectionLineselectedObject)` | `unsafe void` | Inherit Settings From Selected ObjectsMore... |
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
| `ViewCommonViewLabel[get]` | `unsafeNXOpen.Drawings.ViewCommonViewLabelBuilder` | Returns the view common label builderMore... |
| `ViewSectionLine[get]` | `unsafeNXOpen.Drawings.ViewSectionLineBuilder` | Returns the view section line builderMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.EditViewLabelSettingsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49592.html

Represents aNXOpen.Drawings.EditViewLabelSettingsBuilderbuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `InheritSettingsFromCustomerDefault()` | `unsafe void` | Inherit Settings From Customer DefaultMore... |
| `InheritSettingsFromPreferences()` | `unsafe void` | Inherit Settings From PreferenceMore... |
| `InheritSettingsFromSelectedObjects(NXOpen.NXObjectselectedObject)` | `unsafe void` | Inherit Settings From Selected ObjectsMore... |
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
| `AnnotationStyle[get]` | `unsafeNXOpen.Annotations.StyleBuilder` | Returns the annotation style builderMore... |
| `ViewCommonViewLabel[get]` | `unsafeNXOpen.Drawings.ViewCommonViewLabelBuilder` | Returns the view common view label builderMore... |
| `ViewDetailLabel[get]` | `unsafeNXOpen.Drawings.ViewDetailLabelBuilder` | Returns the view detail label builderMore... |
| `ViewLabel[get]` | `unsafeNXOpen.Drawings.ViewLabelBuilder` | Returns the view label builderMore... |
| `ViewProjectedLabel[get]` | `unsafeNXOpen.Drawings.ViewProjectedLabelBuilder` | Returns the view projected label builderMore... |
| `ViewSectionLabel[get]` | `unsafeNXOpen.Drawings.ViewSectionLabelBuilder` | Returns the view section label builderMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.EditViewSettingsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49596.html

Represents aNXOpen.Drawings.EditViewSettingsBuilderbuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `InheritSettingsFromCustomerDefault()` | `unsafe void` | Inherit Settings From Customer DefaultMore... |
| `InheritSettingsFromPreferences()` | `unsafe void` | Inherit Settings From PreferenceMore... |
| `InheritSettingsFromSelectedObjects(NXOpen.Drawings.DraftingViewselectedObject)` | `unsafe void` | Inherit Settings From Selected ObjectsMore... |
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
| `ViewDetailLabel[get]` | `unsafeNXOpen.Drawings.ViewDetailLabelBuilder` | Returns the view detail label builderMore... |
| `ViewLabel[get]` | `unsafeNXOpen.Drawings.ViewLabelBuilder` | Returns the view label builderMore... |
| `ViewProjectedLabel[get]` | `unsafeNXOpen.Drawings.ViewProjectedLabelBuilder` | Returns the view projected label builderMore... |
| `ViewSectionLabel[get]` | `unsafeNXOpen.Drawings.ViewSectionLabelBuilder` | Returns the view section label builderMore... |
| `ViewStyle[get]` | `unsafeNXOpen.Drawings.ViewStyleBuilder` | Returns the view style builderMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.FlatPatternObject

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49600.html

Provides an interface to the data available for flat pattern objects on drawing views

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetDirections(outNXOpen.Vector3dxDirection, outNXOpen.Vector3dyDirection)` | `unsafe void` | Returns the X and Y direction vectors that correspond to the flattened datum csys feature object.More... |
| `GetFlatSolidObject()` | `unsafeNXOpen.CartesianCoordinateSystem` | Returns the point object containing the attributes the user put on the original datum CSYS feature.More... |
| `GetOrigin()` | `unsafeNXOpen.Point3d` | Returns the origin of the marker object (the point on the drawing).More... |
| `Dispose()` | `void` | Frees the object from memory.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `new string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |
| `FreeResource()` | `override void` | Frees the memory of the underlying classMore... |
| `initialize()` | `void` | <exclude>More... |


---

## NXOpen.Drawings.FlatPatternViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49604.html

Provides access to object and callout properties for sheet-metal data in flat pattern views on drawings

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Commit()` | `unsafe void` | Commits and applies all the settings done with set_callout_type_display and set_object_type_display.More... |
| `GetPropertiesObject()` | `unsafeNXOpen.SheetMetal.FlatPatternSettings` | Returns the properties object for the view's flat pattern style settings.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.GeneralViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49608.html

Represents set of General View Styles Preferences applicable to drafting views

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetCenterlines(bool centerlines)` | `unsafe void` | The status of center line, if true automatically creates linear, cylindrical, and bolt circle centerlines (with a circular instance set) for views where the hole or pin axis is perpendicular or parallel to the plane of the drawing view.More... |
| `SetFramebarHorizontal(bool framebarHorizontal)` | `unsafe void` | The status of framebar horizontal, if true automatically creates horizontal framebar for views where the view axis match with ship axis.More... |
| `SetFramebarVertical(bool framebarVertical)` | `unsafe void` | The status of framebar vertical, if true automatically creates vertical framebar for views where the view axis match with ship axis.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Angle[get, set]` | `unsafe double` | Returns or sets the value of angle of a member view.More... |
| `AngleDecimalPointFormat[get, set]` | `unsafeNXOpen.Preferences.DecimalPointCharacter` | Returns or sets the decimal point character to use for view angle display.More... |
| `AngleFormat[get, set]` | `unsafeNXOpen.Preferences.AngleFormat` | Returns or sets the format to use for view angle display.More... |
| `AnglePrecision[get, set]` | `unsafe int` | Returns or sets the precision to use for view angle display.More... |
| `AssociativeAngle[get, set]` | `unsafeNXOpen.Scalar` | Returns or sets the value of angle of a member view.More... |
| `AutomaticAnchorPoint[get, set]` | `unsafe bool` | Returns or sets the status of Automatic Anchor Point.More... |
| `AutomaticUpdate[get, set]` | `unsafe bool` | Returns or sets the status of Automatic update, if true then position, hidden lines, silhouettes, view bounds, section views, and section view details updated after a model change else the above items are not updated after a model change.More... |
| `BoundaryStatus[get, set]` | `unsafe bool` | Returns or sets the boundary status.More... |
| `DisplayId[get, set]` | `unsafeNXOpen.Preferences.GeneralDisplayIdOption` | Returns or sets the display identifier option for a member view.More... |
| `ExpressionForScale[get, set]` | `unsafeNXOpen.Expression` | Returns or sets the expression for scaleMore... |
| `ExtractedEdges[get, set]` | `unsafeNXOpen.Preferences.GeneralExtractedEdgesOption` | Returns or sets the extracted edge, that provides an alternative way to display model geometry in a drawing view.More... |
| `LegacyView[get, set]` | `unsafe bool` | Returns or sets the leagcy view toggle on the GENERAL tab of the View Style DialogMore... |
| `LightweightView[get, set]` | `unsafe bool` | Returns or sets the view representation enum on the GENERAL tab of the View Style DialogMore... |
| `LockmethodView[get, set]` | `unsafeNXOpen.Preferences.GeneralViewLockmethodOption` | Returns or sets the lock method setting on the Configuration tab of the View Style DialogMore... |
| `Reference[get, set]` | `unsafe bool` | Returns or sets the status of reference, that toggles a view from active to reference.More... |
| `RenderCount[get, set]` | `unsafe int` | Returns or sets the render count.More... |
| `Scale[get, set]` | `unsafe double` | Returns or sets the scale of a member view.More... |
| `ScaleLabel[get, set]` | `unsafe bool` | Returns or sets the display of scale label.More... |
| `ShowAngleLeadingZeros[get, set]` | `unsafe bool` | Returns or sets the status of leading zeros display in view angle.More... |
| `ShowAngleTrailingZeros[get, set]` | `unsafe bool` | Returns or sets the status of trailing zeros display in view angle.More... |
| `Silhouettes[get, set]` | `unsafe bool` | Returns or sets the status of silhouettes curves, if true silhouettes for selected drawing member views added else silhouettes removed from the selected member views.More... |
| `SnapshotView[get, set]` | `unsafe bool` | Returns or sets the snapshot toggle on the GENERAL tab of the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `Tolerance[get, set]` | `unsafe double` | Returns or sets the value of tolerance, that specifies a chord height tolerance value for silhouette and hidden line generation in a given drawing view.More... |
| `UvGrid[get, set]` | `unsafe bool` | Returns or sets the status of UV grid, if true, grid curves for selected drawing member views are added else the grid curves are removed from the selected member views.More... |
| `ViewLabel[get, set]` | `unsafe bool` | Returns or sets the display of view label.More... |
| `ViewQuality[get, set]` | `unsafeNXOpen.Preferences.GeneralViewQualityOption` | Returns or sets the view quality, that provides an alternative way to display model geometry in a drawing view.More... |
| `ViewRepresentation[get, set]` | `unsafeNXOpen.Preferences.GeneralViewRepresentationOption` | Returns or sets the view representation enum on the GENERAL tab of the View Style DialogMore... |
| `WireframeColorSource[get, set]` | `unsafeNXOpen.Preferences.GeneralWireframeColorSourceOption` | Returns or sets the source of the wireframe color for a member view.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.GeneralWorkFlowBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49612.html

Represents aNXOpen.Drawings.GeneralWorkFlowBuilder

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
| `CreateDraftingComponent[get, set]` | `unsafe bool` | Returns or sets the flag indicating whether to creates a drafting component when creating a view of the master model partMore... |
| `GridSettings[get, set]` | `unsafeNXOpen.Drawings.GeneralWorkFlowBuilder.GridSettingsType` | Returns or sets the option that indicates the grid settingsMore... |
| `ModelBasedAlwaysStart[get, set]` | `unsafeNXOpen.Drawings.GeneralWorkFlowBuilder.ModelBasedAlwaysStartType` | Returns or sets the option that indicates action to be taken after inserting a sheet with no viewsMore... |
| `ModelBasedInsertSheet[get, set]` | `unsafe bool` | Returns or sets the flag indicating whether to automatically starts the insert sheet command when entering the drafting application if no drawing sheets existMore... |
| `ModelBasedProjectedView[get, set]` | `unsafe bool` | Returns or sets the flag indicating whether to automatically start the projected view command after inserting a model view.More... |
| `SettingsOrigination[get, set]` | `unsafeNXOpen.Drawings.GeneralWorkFlowBuilder.SettingsOrientationType` | Returns or sets the option that indicates the settings originationMore... |
| `StandAloneInsertSheet[get, set]` | `unsafe bool` | Returns or sets the flag indicating whether to automatically starts the insert sheet command when entering the drafting application if no drawing sheets exist.More... |
| `StandAloneProjectedView[get, set]` | `unsafe bool` | Returns or sets the flag indicating whether to automatically starts the projected view command after inserting a drawing view.More... |
| `StandAloneProjectToView[get, set]` | `unsafe bool` | Returns or sets the flag indicating whether to automatically starts the projected view command after inserting a projected drawing view.More... |
| `StandAloneViewCreation[get, set]` | `unsafe bool` | Returns or sets the flag indicating whether to automatically starts the drawing view command after inserting a sheet with no views.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.HalfPictorialSectionLine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49616.html

Half Pictorial Section Line is used to create a pictorial view with half of the part sectioned and the other half un-sectioned


---

## NXOpen.Drawings.HalfSectionLine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49620.html

Half Section Line is used to create a view with half of the part sectioned and the other half un-sectioned


---

## NXOpen.Drawings.HalfSectionLineBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49624.html

Represents aNXOpen.Drawings.HalfSectionLineBuilder

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
| `BendLocation[get, set]` | `unsafeNXOpen.Point` | Returns or sets the bend locationMore... |
| `CutLocation[get, set]` | `unsafeNXOpen.Point` | Returns or sets the cut locationMore... |
| `EndLocation1[get, set]` | `unsafeNXOpen.Point` | Returns or sets the arrow locationMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.HiddenLinesViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49628.html

Represents set of Hidden Lines View Style Preferences applicable to drafting views

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `EdgesHiddenByEdges[get, set]` | `unsafe bool` | Returns or sets the staus of edges hidden by edges.More... |
| `Hiddenline[get, set]` | `unsafe bool` | Returns or sets the status of hiddenline.More... |
| `HiddenlineColor[get, set]` | `unsafe int` | Returns or sets the color of hiddenline.More... |
| `HiddenlineFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the font of hiddenlineMore... |
| `HiddenlineWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the width of hiddenlineMore... |
| `IncludeModelCurves[get, set]` | `unsafe bool` | Returns or sets the status of include model curvesMore... |
| `InterferingSolids[get, set]` | `unsafe bool` | Returns or sets the status of interfering solids.More... |
| `InterferingSolidsOption[get, set]` | `unsafeNXOpen.Preferences.HiddenLineInterferingSolidsOption` | Returns or sets the status of interfering solids.More... |
| `ReferenceEdgesOnly[get, set]` | `unsafe bool` | Returns or sets the status of reference edges only.More... |
| `SelfHidden[get, set]` | `unsafe bool` | Returns or sets the status of self hidden.More... |
| `SmallFeature[get, set]` | `unsafeNXOpen.Preferences.HiddenLineSmallFeatureOption` | Returns or sets the small feature option.More... |
| `SmallFeaturesTolerance[get, set]` | `unsafe double` | Returns or sets the value of small features tolerance.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.HiddenObjectsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49632.html

This builder allows the user to select a view in which component objects can be designated as hidden or shown

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
| `Objects[get]` | `unsafeNXOpen.SelectNXObjectList` | Returns the objectsMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.HingeLineBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49636.html

Represents a Drawings

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
| `Associative[get, set]` | `unsafe bool` | Returns or sets the infer associative settingMore... |
| `ReverseDirection[get, set]` | `unsafe bool` | Returns or sets the reverse direction settingMore... |
| `SpecifyVector[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the direction for the hinge lineMore... |
| `VectorOption[get, set]` | `unsafeNXOpen.Drawings.HingeLineBuilder.Hingeline` | Returns or sets the vector option: Inferred or DefinedMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.InheritPmiViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49640.html

Represents set of InheritPmiViewStyle applicable to drafting views

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetCrosshatchPmiLwsv(bool crosshatch)` | `unsafe void` | Controls whether the cut faces of an inherited PMI Lightweight section view are cross-hatched or not.More... |
| `SetInheritGdt(NXOpen.Preferences.GdtOptiongdtOption)` | `unsafe void` | Inherit GD and T option,that let you inherit GD and T display instances onto the drawing plane or into a drawing member view.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CrosshatchPmiLwsv[get]` | `unsafe bool` | Returns the cross-hatch setting for the current inherited PMI Lightweight Section ViewMore... |
| `InheritPmiMode[get, set]` | `unsafeNXOpen.Preferences.PmiOption` | Returns or sets the Inherit pmi mode.More... |
| `InheritPmiToDrawing[get, set]` | `unsafe bool` | Returns or sets the status of pmi inherited to drawing.More... |
| `InheritPmiTypeMask[get, set]` | `unsafe int` | Returns or sets the Inherit pmi type mask.More... |
| `PmiDimensionFromRevolved[get, set]` | `unsafe bool` | Returns or sets the status of pmi inherited to drawing.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.MarkAsTemplateBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49644.html

Represents aNXOpen.Drawings.MarkAsTemplateBuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `ActionType[get, set]` | `unsafeNXOpen.Drawings.MarkAsTemplateBuilder.ActionTypeEnum` | Returns or sets the action type of the part.More... |
| `Description[get, set]` | `unsafe string` | Returns or sets the detailed description for each template.More... |
| `ItemType[get, set]` | `unsafeNXOpen.Drawings.MarkAsTemplateBuilder.ItemTypeEnum` | Returns or sets the item type of the part.More... |
| `ItemTypeString[get, set]` | `unsafe string` | Returns or sets the item type string of the part.More... |
| `PaxFileName[get, set]` | `unsafe string` | Returns or sets the PAX file to be updated or created if it does not exist.More... |
| `PresentationName[get, set]` | `unsafe string` | Returns or sets the presentation name of the template that will be displayed in the File->New dialog.More... |
| `RelationType[get, set]` | `unsafeNXOpen.Drawings.MarkAsTemplateBuilder.RelationTypeEnum` | Returns or sets the relation type is required only for the managed mode.More... |
| `TemplateType[get, set]` | `unsafeNXOpen.Drawings.MarkAsTemplateBuilder.TemplateTypeEnum` | Returns or sets the template Type will be one of the following: Sheet To save it as Sheet template.More... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.MultipleViewPlacementBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49648.html

This builder allows the user to create a Multiple View Placement

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
| `AssociativeAlignment[get, set]` | `unsafe bool` | Returns or sets the associative alignment toggleMore... |
| `OptionType[get, set]` | `unsafeNXOpen.Drawings.MultipleViewPlacementBuilder.Option` | Returns or sets the placement optionMore... |
| `ViewPlacementCenter[get]` | `unsafeNXOpen.Drawings.ViewPlacementBuilder` | Returns the view placement block for the center optionMore... |
| `ViewPlacementFirstCorner[get]` | `unsafeNXOpen.Drawings.ViewPlacementBuilder` | Returns the view placement block for the first cornerMore... |
| `ViewPlacementSecondCorner[get]` | `unsafeNXOpen.Drawings.ViewPlacementBuilder` | Returns the view placement block for the second cornerMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.OrderManager

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49656.html

Represents an object that manages orders

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `ApplyOrder(NXOpen.SketchparentObject, string orderName)` | `unsafe void` | Applies the order matching the specified nameMore... |
| `CreateNewOrder(NXOpen.SketchparentObject, string newOrderName,NXOpen.Layout2d.Component[] objectsInOrder)` | `unsafe void` | Creates an order of the 2D Components provided in the listMore... |
| `DeleteOrder(NXOpen.SketchparentObject, string newOrderName)` | `unsafe void` | Delete the order matching the specified nameMore... |
| `GetAvailableOrdersNames(NXOpen.SketchparentObject, out string [] ordersNames)` | `unsafe void` | Gets all available orders names for specified sketch parentMore... |
| `GetCurrentOrderName(NXOpen.SketchparentObject)` | `unsafe string` | Gets the current applied order nameMore... |
| `IsSystemOrder(NXOpen.SketchparentObject, string orderName)` | `unsafe bool` | Validates the order matching the specified name is system orderMore... |
| `RenameOrder(NXOpen.SketchparentObject, string orderName, string newOrderName)` | `unsafe void` | Renames the order matching the specified name with the new name providedMore... |
| `Reorder(NXOpen.SketchparentObject,NXOpen.Layout2d.Component[] objectsInOrder)` | `unsafe void` | Updates the current order based on the provided list of 2D components if the order is user-defined, and creates a new order otherwideMore... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.OrientationViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49660.html

Represents set of Orientation View Style Preferences applicable to drafting views

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `OrientView(NXOpen.Matrix3x3matrix)` | `unsafe void` | Orients the view.More... |
| `Restore()` | `unsafe void` | Removes the associativity to the defined plane (if it existed) and returns the member view to its orientation with the model with respect to the Absolute Coordinate System.More... |
| `ReverseHingeLine()` | `unsafe void` | Reverse the hinge line.More... |
| `ReverseRotationVector()` | `unsafe void` | Reverse the rotation vector.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `HingeLine[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the hinge line for an existing auxillary view.More... |
| `RotationPlane[get, set]` | `unsafeNXOpen.Xform` | Returns or sets the rotation plane.More... |
| `RotationXDirection[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the rotation in x-direction for the drawing member view which stays parallel to the x-axis drawing coordinate.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.OrientedSectionLine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49664.html

Represents a Oriented Section Line


---

## NXOpen.Drawings.OrientedSectionLineBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49668.html

Represents aNXOpen.Drawings.OrientedSectionLineBuilder

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
| `CutLocation3D[get, set]` | `unsafeNXOpen.Point` | Returns or sets the 3D cut locationMore... |
| `EndLocation1[get, set]` | `unsafeNXOpen.Point` | Returns or sets the end location 1 which determines the position of the first arrow segment in the section line.More... |
| `EndLocation2[get, set]` | `unsafeNXOpen.Point` | Returns or sets the end location 2 which determines the position of the second arrow segment in the section lineMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.OvtBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49672.html

Represents aNXOpen.Drawings.OvtBuilder

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
| `AssociativeOrientation[get, set]` | `unsafe bool` | Returns or sets the associative orientation that specifies whether or not the view will be associative to the specified plane and/or X directionMore... |
| `NormalDirection[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the vector that represents the normal direction for the view to be created or editedMore... |
| `XDirection[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the x direction vector for the view to be created or editedMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ParentViewBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49676.html

Represents aNXOpen.Drawings.ParentViewBuilder

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
| `View[get]` | `unsafeNXOpen.Drawings.SelectDraftingView` | Returns the parent viewMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.PerspectiveViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49680.html

Represents set of PerspectiveViewStyle applicable to drafting views

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `BackClipping[get, set]` | `unsafe bool` | Returns or sets the status of back clippingMore... |
| `BackClippingDistance[get, set]` | `unsafe double` | Returns or sets the value of back clipping distanceMore... |
| `FrontClipping[get, set]` | `unsafe bool` | Returns or sets the status of front clippingMore... |
| `FrontClippingDistance[get, set]` | `unsafe double` | Returns or sets the value of front clipping distanceMore... |
| `Perspective[get, set]` | `unsafe bool` | Returns or sets the status of perspectiveMore... |
| `PerspectiveDistance[get, set]` | `unsafe double` | Returns or sets the value of perspective distanceMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.PictorialSectionLine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49684.html

A Pictorial Simple or Pictorial Stepped Section Line


---

## NXOpen.Drawings.PointAndAngleSectionLine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49688.html

Point and Angle Section Line lets you create a view with multiple segment cuts with no bends


---

## NXOpen.Drawings.PointAndAngleSectionLineBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49692.html

Represents aNXOpen.Drawings.PointAndAngleSectionLineBuilder

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
| `EndLocation1[get, set]` | `unsafeNXOpen.Point` | Returns or sets the end location 1 which determines the position of the first arrow segment in the section line.More... |
| `EndLocation2[get, set]` | `unsafeNXOpen.Point` | Returns or sets the end location 2 which determines the position of the second arrow segment in the section lineMore... |
| `Leg1[get]` | `unsafeNXOpen.Drawings.SectionLineSegmentBuilderList` | Returns the list of cut segments.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.PointToPointSectionLine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49696.html

Point to Point Section Line lets you create a view with multiple segment cuts with no bends


---

## NXOpen.Drawings.PointToPointSectionLineBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49700.html

Represents aNXOpen.Drawings.PointToPointSectionLineBuilder

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
| `EndLocation1[get, set]` | `unsafeNXOpen.Point` | Returns or sets the end location 1 which determines the position of the first arrow segment in the section line.More... |
| `EndLocation2[get, set]` | `unsafeNXOpen.Point` | Returns or sets the end location 2 which determines the position of the second arrow segment in the section lineMore... |
| `Leg1[get]` | `unsafeNXOpen.Drawings.SectionLineSegmentBuilderList` | Returns the list of cut segments.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ProjectedView

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49704.html

Represents a Projected View


---

## NXOpen.Drawings.ProjectedViewBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49708.html

Represents aNXOpen.Drawings.ProjectedViewbuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `HiddenObjects[get]` | `unsafeNXOpen.Drawings.HiddenObjectsBuilder` | Returns the list of objects to not show in the viewMore... |
| `NonSectionedObjects[get]` | `unsafeNXOpen.Drawings.HiddenObjectsBuilder` | Returns the list of objects to not section in the viewMore... |
| `Parent[get]` | `unsafeNXOpen.Drawings.ParentViewBuilder` | Returns the parent viewMore... |
| `Placement[get]` | `unsafeNXOpen.Drawings.ViewPlacementBuilder` | Returns the view positionMore... |
| `SecondaryComponents[get]` | `unsafeNXOpen.Drawings.DraftingComponentSelectionBuilder` | Returns the list of secondary components in the viewMore... |
| `Style[get]` | `unsafeNXOpen.Drawings.ViewStyleBuilder` | Returns the view styleMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ProjectedViewOrientationBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49712.html

Represents aNXOpen.Drawings.ProjectedViewOrientationBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Restore()` | `unsafe void` | Removes the associativity to the defined plane and x direction vector and restores the member view to its default orientation.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `NormalDirection[get, set]` | `unsafeNXOpen.Xform` | Returns or sets the xform that represents the orthographic projected view settings to be editedMore... |
| `XDirection[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the x direction vector for the orthographic projected view settings to be editedMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ProjectedViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49716.html

Represents set of Projected View Style Preferences applicable to drafting views

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.RefineDisplayBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49720.html

Represents aNXOpen.Drawings.RefineDisplayBuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `BoundaryPoint1[get, set]` | `unsafeNXOpen.Point` | Returns or sets the boundary point1 in drawing coordinates.More... |
| `BoundaryPoint2[get, set]` | `unsafeNXOpen.Point` | Returns or sets the boundary point2 in drawing coordinates.More... |
| `View[get]` | `unsafeNXOpen.Drawings.SelectDraftingView` | Returns the view to refine.More... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.RemoveObjectsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49724.html

Creates the builder for removing associated objects from the region

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetRegion(NXOpen.Drawings.DrawingRegionregion)` | `unsafe void` | Set the regionMore... |
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
| `Selection[get]` | `unsafeNXOpen.SelectNXObjectList` | Returns the selectionMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.RenderSet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49728.html

Represents a RenderSet


---

## NXOpen.Drawings.ReportBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49732.html

Represents aDrawings.ReportBuilder


---

## NXOpen.Drawings.RevolvedSectionLine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49736.html

Revolved Section Line is used to create section views which are revolved about an axis


---

## NXOpen.Drawings.RevolvedSectionLineBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49740.html

Represents aNXOpen.Drawings.RevolvedSectionLineBuilder

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
| `EndLocation1[get, set]` | `unsafeNXOpen.Point` | Returns or sets the end location 1 which determines the position of the first arrow segment in the section line.More... |
| `EndLocation2[get, set]` | `unsafeNXOpen.Point` | Returns or sets the end location 2 which determines the position of the second arrow segment in the section lineMore... |
| `Leg1[get]` | `unsafeNXOpen.Drawings.SectionLineSegmentBuilderList` | Returns the list of cut and bend segments for the first leg.More... |
| `Leg2[get]` | `unsafeNXOpen.Drawings.SectionLineSegmentBuilderList` | Returns the list of cut and bend segments for the second leg.More... |
| `RotationPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the rotation point.More... |
| `SingleLeg[get, set]` | `unsafe bool` | Returns or sets the single leg indicator.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SecondaryGeometryInViewsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49744.html

This builder allows the user to select existing view(s) in which component objects can be designated as secondary or primary

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Components[get]` | `unsafeNXOpen.Drawings.DraftingComponentSelectionBuilder` | Returns the componentsMore... |
| `Views[get]` | `unsafeNXOpen.Drawings.SelectDraftingViewList` | Returns the viewsMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SectionInViewBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49748.html

This builder allows the user to select a view in which component or solid body objects can be designated as section, non-sectioned, or neither

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `EditObjects[get]` | `unsafeNXOpen.Drawings.HiddenObjectsBuilder` | Returns the objectsMore... |
| `EditType[get, set]` | `unsafeNXOpen.Drawings.SectionInViewBuilder.EditSxtype` | Returns or sets the typeMore... |
| `Views[get]` | `unsafeNXOpen.Drawings.SelectDraftingViewList` | Returns the viewsMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SectionLine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49752.html

Represents a Section Line

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `IsRetained[get]` | `unsafe bool` | Returns a flag indicating whether the section line is retainedMore... |
| `Color[get, set]` | `unsafe int` | Returns or sets the color of the object.More... |
| `IsBlanked[get]` | `unsafe bool` | Returns the blank status of this object.More... |
| `Layer[get, set]` | `unsafe int` | Returns or sets the layer that the object is in.More... |
| `LineFont[get, set]` | `unsafeNXOpen.DisplayableObject.ObjectFont` | Returns or sets the line font of the object.More... |
| `LineWidth[get, set]` | `unsafeNXOpen.DisplayableObject.ObjectWidth` | Returns or sets the line width of the object.More... |
| `NameLocation[get]` | `unsafeNXOpen.Point3d` | Returns the location of the object's name.More... |
| `IsOccurrence[get]` | `unsafe bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `unsafe string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Name[get]` | `unsafe string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `unsafeNXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `unsafeNXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `unsafeNXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |
| `IsOccurrence[get]` | `bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Name[get]` | `string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `NXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `NXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `NXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |


---

## NXOpen.Drawings.SectionLineBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49756.html

Represents aNXOpen.Drawings.SectionLineBuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `ArrowDirection[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the arrow direction.More... |
| `CutDirection[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the cut direction.More... |
| `Half[get]` | `unsafeNXOpen.Drawings.HalfSectionLineBuilder` | Returns the half section line data.More... |
| `HalfPictorial[get]` | `unsafeNXOpen.Drawings.HalfSectionLineBuilder` | Returns the half pictorial section line data.More... |
| `HingeDirection[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the hinge direction.More... |
| `Oriented[get]` | `unsafeNXOpen.Drawings.OrientedSectionLineBuilder` | Returns the simple 3D section line data.More... |
| `ParentView[get]` | `unsafeNXOpen.Drawings.ParentViewBuilder` | Returns the parent view.More... |
| `Pictorial[get]` | `unsafeNXOpen.Drawings.SteppedSectionLineBuilder` | Returns the pictorial section line data.More... |
| `PointAndAngle[get]` | `unsafeNXOpen.Drawings.PointAndAngleSectionLineBuilder` | Returns the point and angle section line data.More... |
| `PointToPoint[get]` | `unsafeNXOpen.Drawings.PointToPointSectionLineBuilder` | Returns the point to point section line data.More... |
| `Revolved[get]` | `unsafeNXOpen.Drawings.RevolvedSectionLineBuilder` | Returns the revolved section line data.More... |
| `SimpleOrStepped[get]` | `unsafeNXOpen.Drawings.SteppedSectionLineBuilder` | Returns the simple or stepped section line data.More... |
| `Style[get]` | `unsafeNXOpen.Drawings.SectionLineStyleBuilder` | Returns the style.More... |
| `Type[get, set]` | `unsafeNXOpen.Drawings.SectionLineBuilder.Types` | Returns or sets the section line typeMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SectionLineCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49760.html

Represents a collection ofNXOpen.Drawings.SectionLines

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateSectionLineBuilder(NXOpen.Drawings.SectionLinesectionLine)` | `unsafeNXOpen.Drawings.SectionLineBuilder` | Creates the section line builderMore... |
| `CreateSectionLineSegmentBuilder()` | `unsafeNXOpen.Drawings.SectionLineSegmentBuilder` | Creates the section line segment builderMore... |
| `CreateSectionLineStyleBuilder(NXOpen.Drawings.SectionLinesectionline)` | `unsafeNXOpen.Drawings.SectionLineStyleBuilder` | Creates the Section Line Style BuilderMore... |
| `CreateSketchSectionLineBuilder(NXOpen.Drawings.SectionLinesectionLine)` | `unsafeNXOpen.Drawings.SketchSectionLineBuilder` | Creates the Sketch Section Line builderMore... |
| `GenerateSectionLineLabelAttribute(NXOpen.Annotations.BaseNotenote)` | `unsafe string` | Generates a parametric text attribute that is similar to the current section line label but contains the section line segment information.More... |
| `ToArray()` | `NXOpen.Drawings.SectionLine[]` | Returns an array ofNXOpen.Drawings.SectionLineobjects.More... |
| `GetEnumerator()` | `IEnumerator` | Returns an enumerator that iterates through a collection.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |
| `EnumerateMoveNext(refTagcurrentTag, byte [] state)` | `override int` | Advances the enumerator to the next element of the collection.More... |
| `initialize()` | `new void` | <exclude>More... |
| `initialize()` | `void` | <exclude>More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SectionLineSegmentBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49764.html

Represents aNXOpen.Drawings.SectionLineSegmentBuilder

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
| `Angle[get]` | `unsafeNXOpen.Expression` | Returns the angle.More... |
| `Point[get, set]` | `unsafeNXOpen.Point` | Returns or sets the pointMore... |
| `Type[get, set]` | `unsafeNXOpen.Drawings.SectionLineSegmentBuilder.Types` | Returns or sets the section line segment typeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SectionLineSegmentBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49768.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.Drawings.SectionLineSegmentBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.Drawings.SectionLineSegmentBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.Drawings.SectionLineSegmentBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.Drawings.SectionLineSegmentBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.Drawings.SectionLineSegmentBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.Drawings.SectionLineSegmentBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.Drawings.SectionLineSegmentBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.Drawings.SectionLineSegmentBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.Drawings.SectionLineSegmentBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.Drawings.SectionLineSegmentBuilderobject1,NXOpen.Drawings.SectionLineSegmentBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.Drawings.SectionLineSegmentPointBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49772.html

Represents Section Line Segment Point Builder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Point[get, set]` | `unsafeNXOpen.Point` | Returns or sets the section line segmentNXOpen.PointMore... |
| `SegmentType[get, set]` | `unsafeNXOpen.Drawings.SectionLineSegmentPointBuilder.SegmentTypes` | Returns or sets the segment typeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SectionLineSegmentPointListBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49776.html

Represents SectionLineSegmentPointListBuilder class

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `AddCutSegment(NXOpen.Pointlocation)` | `unsafeNXOpen.Drawings.SectionLineSegmentPointBuilder` | Creates a newNXOpen.Drawings.SectionLineSegmentPointBuilderobjectMore... |
| `AddCutSegment(NXOpen.Pointlocation,NXOpen.Drawings.SectionLineSegmentPointBuilderreferencedCutSegment)` | `unsafeNXOpen.Drawings.SectionLineSegmentPointBuilder` | Creates a newNXOpen.Drawings.SectionLineSegmentPointBuilderIn case of point to point section line ,new segment is added at location prior to reference cut segment specified.More... |
| `Append(NXOpen.Drawings.SectionLineSegmentPointBuilderpointData)` | `unsafe void` | AppendsNXOpen.Drawings.SectionLineSegmentPointBuilderobject to the end of the listMore... |
| `Clear()` | `unsafe void` | Deletes allNXOpen.Drawings.SectionLineSegmentPointBuilderobjects from the listMore... |
| `CreateSectionLineSegmentPointBuilder()` | `unsafeNXOpen.Drawings.SectionLineSegmentPointBuilder` | Creates a newNXOpen.Drawings.SectionLineSegmentPointBuilderobjectMore... |
| `Delete(NXOpen.Drawings.SectionLineSegmentPointBuilderpoint)` | `unsafe void` | Deletes a givenNXOpen.Drawings.SectionLineSegmentPointBuilderobject from the listMore... |
| `Delete(int index)` | `unsafe void` | DeletesNXOpen.Drawings.SectionLineSegmentPointBuilderobject of a certain index from the listMore... |
| `FindItem(int index)` | `unsafeNXOpen.Drawings.SectionLineSegmentPointBuilder` | ReturnsNXOpen.Drawings.SectionLineSegmentPointBuilderobject at the input index.More... |
| `GetContents()` | `unsafeNXOpen.Drawings.SectionLineSegmentPointBuilder[]` | Queries all theNXOpen.Drawings.SectionLineSegmentPointBuilderobjectsMore... |
| `GetIndex(NXOpen.Drawings.SectionLineSegmentPointBuilderpoint)` | `unsafe int` | Finds index ofNXOpen.Drawings.SectionLineSegmentPointBuilderobject in the listMore... |
| `Insert(int insertBeforeIndex,NXOpen.Drawings.SectionLineSegmentPointBuilderpoint)` | `unsafe void` | InsertsNXOpen.Drawings.SectionLineSegmentPointBuilderobject in the list before a given positionMore... |
| `MoveSegment(NXOpen.Drawings.SectionLineSegmentPointBuilderpoint,NXOpen.Pointpointspecified)` | `unsafe void` | Moves a givenNXOpen.Drawings.SectionLineSegmentPointBuilderobject from the listMore... |
| `SetContents(NXOpen.Drawings.SectionLineSegmentPointBuilder[] points)` | `unsafe void` | Sets array ofNXOpen.Drawings.SectionLineSegmentPointBuilderobjects in the list.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Length[get]` | `unsafe int` | Returns the number ofNXOpen.Drawings.SectionLineSegmentPointBuilderobjects in the listMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SectionLineSegmentsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49780.html

Represents a class Drawings

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `UpdateAfterParentViewMove()` | `unsafe void` | Update the section line segments builder in case of parent view moveMore... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `RotationPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the rotation pointMore... |
| `SectionLineOnlyPlacementOrigin[get, set]` | `unsafeNXOpen.Point3d` | Returns or sets the section line only placement origin center in inferred modeMore... |
| `SegmentLocation[get]` | `unsafeNXOpen.Drawings.SectionLineSegmentPointListBuilder` | Returns the segment locationMore... |
| `SegmentLocationForSecondLeg[get]` | `unsafeNXOpen.Drawings.SectionLineSegmentPointListBuilder` | Returns the segment location to add segments to revolved section line second legMore... |
| `SingleLeg[get, set]` | `unsafe bool` | Returns or sets the single legMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SectionLineSettingsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49784.html

Represents the Section Line Settings Builder (Drawings

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `InheritSettingsFromCustomerDefault()` | `unsafe void` | Inherit Settings From Customer DefaultMore... |
| `InheritSettingsFromPreferences()` | `unsafe void` | Inherit Settings From PreferenceMore... |
| `InheritSettingsFromSelectedObjects(NXOpen.Drawings.SectionLineselectedObject)` | `unsafe void` | Inherit Settings From Selected ObjectsMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `ViewCommonViewLabel[get]` | `unsafeNXOpen.Drawings.ViewCommonViewLabelBuilder` | Returns the view Common View label builderMore... |
| `ViewSectionLine[get]` | `unsafeNXOpen.Drawings.ViewSectionLineBuilder` | Returns the Section Line builderMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SectionLineStyleBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49788.html

Represents a Drawings

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetColor()` | `unsafeNXOpen.NXColor` | Returns the colorMore... |
| `SetColor(NXOpen.NXColorcolor)` | `unsafe void` | Sets the colorMore... |
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
| `ArrowheadAngle[get, set]` | `unsafe double` | Returns or sets the arrowhead angleMore... |
| `ArrowheadLength[get, set]` | `unsafe double` | Returns or sets the arrowhead lengthMore... |
| `ArrowheadStyle[get, set]` | `unsafeNXOpen.Drawings.SectionLineStyleBuilder.ArrowheadStyleType` | Returns or sets the arrowhead styleMore... |
| `ArrowLength[get, set]` | `unsafe double` | Returns or sets the arrow lengthMore... |
| `BorderToArrowDistance[get, set]` | `unsafe double` | Returns or sets the border to arrow distanceMore... |
| `CreateSectionLine[get, set]` | `unsafeNXOpen.Drawings.SectionLineStyleBuilder.CreateSectionLineType` | Returns or sets a value that indicates whether or not to create a view for the section lineMore... |
| `DisplayJisrotationLetter[get, set]` | `unsafe bool` | Returns or sets the display jisrotation letterMore... |
| `DisplayLabel[get, set]` | `unsafe bool` | Returns or sets the display labelMore... |
| `Font[get, set]` | `unsafeNXOpen.Drawings.SectionLineStyleBuilder.FontStyle` | Returns or sets the fontMore... |
| `LabelLocation[get, set]` | `unsafeNXOpen.Drawings.SectionLineStyleBuilder.LabelLocationStyle` | Returns or sets the label locationMore... |
| `Letter[get, set]` | `unsafe string` | Returns or sets the letterMore... |
| `LineLength[get, set]` | `unsafe double` | Returns or sets the line lengthMore... |
| `Offset[get, set]` | `unsafe double` | Returns or sets the offsetMore... |
| `SelectLetter[get]` | `unsafeNXOpen.SelectTaggedObject` | Returns the selected note for jisrotation letterMore... |
| `Standard[get, set]` | `unsafeNXOpen.Drawings.SectionLineStyleBuilder.StandardStyle` | Returns or sets the standardMore... |
| `StubLength[get, set]` | `unsafe double` | Returns or sets the stub lengthMore... |
| `UseOffset[get, set]` | `unsafe bool` | Returns or sets the use offsetMore... |
| `Width[get, set]` | `unsafeNXOpen.Drawings.SectionLineStyleBuilder.WidthStyle` | Returns or sets the widthMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SectionView

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49792.html

Represents a Section View


---

## NXOpen.Drawings.SectionViewBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49796.html

Represents aNXOpen.Drawings.SectionViewbuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CreateFolded[get, set]` | `unsafe bool` | Returns or sets the create foldedMore... |
| `HiddenObjects[get]` | `unsafeNXOpen.Drawings.HiddenObjectsBuilder` | Returns the hidden objectsMore... |
| `NonSectionedObjects[get]` | `unsafeNXOpen.Drawings.HiddenObjectsBuilder` | Returns the non sectioned objectsMore... |
| `ParentView[get]` | `unsafeNXOpen.Drawings.ParentViewBuilder` | Returns the selected parent viewMore... |
| `SecondaryComponents[get]` | `unsafeNXOpen.Drawings.DraftingComponentSelectionBuilder` | Returns the list of secondary objects in the viewMore... |
| `SectionLine[get]` | `unsafeNXOpen.Drawings.SpecifySectionLineBuilder` | Returns the section LineMore... |
| `SectionLineSegments[get]` | `unsafeNXOpen.Drawings.SectionLineSegmentsBuilder` | Returns the section line segment builderMore... |
| `SectionViewMode[get, set]` | `unsafeNXOpen.Drawings.SectionViewBuilder.SectionViewModeType` | Returns or sets the section line modeMore... |
| `SectionViewTool[get]` | `unsafeNXOpen.Drawings.SvtBuilder` | Returns the section view toolMore... |
| `SectionViewType[get, set]` | `unsafeNXOpen.Drawings.SectionViewBuilder.SectionLineType` | Returns or sets the section line typeMore... |
| `ViewOrientation[get]` | `unsafeNXOpen.Drawings.ViewOrientationBuilder` | Returns the view orientationMore... |
| `ViewPlacement[get]` | `unsafeNXOpen.Drawings.ViewPlacementBuilder` | Returns the view placementMore... |
| `ViewStyle[get]` | `unsafeNXOpen.Drawings.ViewStyleBuilder` | Returns the view styleMore... |
| `ViewUnfolded[get, set]` | `unsafe bool` | Returns or sets the view unfolded toggleMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SectionViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49800.html

Represents set of Section View Style Preferences applicable to drafting views

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AssemblyCrossHatching[get, set]` | `unsafe bool` | Returns or sets the status of assembly cross hatching.More... |
| `Background[get, set]` | `unsafe bool` | Returns or sets the status of background.More... |
| `Bendlines[get, set]` | `unsafe bool` | Returns or sets the status of bendlinesMore... |
| `CrossHatch[get, set]` | `unsafe bool` | Returns or sets the status of cross hatch.More... |
| `CrosshatchAdjacencyTolarance[get, set]` | `unsafe double` | Returns or sets the value of crosshatch adjacency tolarance.More... |
| `DisplaySectionLine[get, set]` | `unsafe bool` | Returns or sets the status of display section line.More... |
| `Foreground[get, set]` | `unsafe bool` | Returns or sets the status of foregroundMore... |
| `HiddenLineHatching[get, set]` | `unsafe bool` | Returns or sets the status of hidden line hatching.More... |
| `RestrictCrosshatchAngle[get, set]` | `unsafe bool` | Returns or setsMore... |
| `SectionSheetBodies[get, set]` | `unsafe bool` | Returns or sets the status of section sheet bodies.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SelectDraftingView

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49804.html

Represents a single object selection

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetValue(outNXOpen.Drawings.DraftingViewselection, outNXOpen.Viewview, outNXOpen.Point3dpoint)` | `unsafe void` | The object being selected with the object's view and point.More... |
| `GetValue(outNXOpen.InferSnapType.SnapTypesnapType, outNXOpen.Drawings.DraftingViewselection1, outNXOpen.Viewview1, outNXOpen.Point3dpoint1, outNXOpen.Drawings.DraftingViewselection2, outNXOpen.Viewview2, outNXOpen.Point3dpoint2)` | `unsafe void` | The object being selected with the objects view and point and snap information.More... |
| `GetValue(outNXOpen.CaeObjectType.CaeSubTypecaeSubType, out int caeSubId)` | `unsafeNXOpen.Drawings.DraftingView` | The object being selected with CAE set object information.More... |
| `SetValue(NXOpen.Drawings.DraftingViewselection,NXOpen.Viewview,NXOpen.Point3dpoint)` | `unsafe void` | The object being selected with the object's view and object's pointMore... |
| `SetValue(NXOpen.InferSnapType.SnapTypesnapType,NXOpen.Drawings.DraftingViewselection1,NXOpen.Viewview1,NXOpen.Point3dpoint1,NXOpen.Drawings.DraftingViewselection2,NXOpen.Viewview2,NXOpen.Point3dpoint2)` | `unsafe void` | The object being selected with the objects view and objects point and snap information.More... |
| `SetValue(NXOpen.Drawings.DraftingViewselection,NXOpen.CaeObjectType.CaeSubTypecaeSubType, int caeSubId)` | `unsafe void` | The object being selected with CAE set object information.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Value[get, set]` | `unsafeNXOpen.Drawings.DraftingView` | Returns or sets the object being selectedMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SelectDraftingViewList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49808.html

Represents a list of objects on a selection list

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Add(NXOpen.Drawings.DraftingView@object)` | `unsafe bool` | Adds an object to the listMore... |
| `Add(NXOpen.Drawings.DraftingView[] objects)` | `unsafe bool` | Adds a set of objects to the listMore... |
| `Add(NXOpen.SelectionMethodinputSelectionMethod)` | `unsafe bool` | Adds the objects from a SelectionMethod to the listMore... |
| `Add(NXOpen.Drawings.DraftingViewselection,NXOpen.Viewview,NXOpen.Point3dpoint)` | `unsafe bool` | Adds the object with the objects view and objects pointMore... |
| `Add(NXOpen.InferSnapType.SnapTypesnapType,NXOpen.Drawings.DraftingViewselection1,NXOpen.Viewview1,NXOpen.Point3dpoint1,NXOpen.Drawings.DraftingViewselection2,NXOpen.Viewview2,NXOpen.Point3dpoint2)` | `unsafe bool` | The object being selected with the objects view and objects point and snap information.More... |
| `Add(NXOpen.Drawings.DraftingViewselection,NXOpen.CaeObjectType.CaeSubTypecaeSubType, int caeSubId)` | `unsafe bool` | The object being selected with CAE set object information.More... |
| `AddWithViews(NXOpen.Drawings.DraftingView[] objects,NXOpen.View[] views)` | `unsafe bool` | Adds a set of objects with views to the listMore... |
| `Clear()` | `unsafe void` | Removes all items from the list.More... |
| `Contains(NXOpen.Drawings.DraftingView@object)` | `unsafe bool` | Returns whether the specified object is already in the list or not.More... |
| `GetArray()` | `unsafeNXOpen.Drawings.DraftingView[]` | Returns the list of objects in the selection list.More... |
| `GetSelectObjectArray()` | `unsafeNXOpen.SelectObject[]` | Returns the list of SelectObjects in the selection list.More... |
| `Remove(NXOpen.Drawings.DraftingView@object)` | `unsafe bool` | Remove specified object from list.More... |
| `Remove(NXOpen.Drawings.DraftingView@object,NXOpen.Viewview)` | `unsafe bool` | Remove specified object from list.More... |
| `Remove(NXOpen.InferSnapType.SnapTypesnapType,NXOpen.Drawings.DraftingViewselection1,NXOpen.Viewview1,NXOpen.Point3dpoint1,NXOpen.Drawings.DraftingViewselection2,NXOpen.Viewview2,NXOpen.Point3dpoint2)` | `unsafe bool` | Remove specified object from list.More... |
| `Remove(NXOpen.SelectionMethodinputSelectionMethod)` | `unsafe bool` | Removes the objects from a SelectionMethod from the listMore... |
| `RemoveArray(NXOpen.Drawings.DraftingView[] objects)` | `unsafe bool` | Remove specified objects from list.More... |
| `SetArray(NXOpen.Drawings.DraftingView[] objects)` | `unsafe void` | Sets the list of objects in the selection list.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `DuplicatesAllowed[get]` | `unsafe bool` | Returns whether duplicate objects are allowed in the selection list.More... |
| `Size[get]` | `unsafe int` | Returns the number of objects in the list.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SelectDrawingRegion

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49812.html

Represents a single object selection

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetValue(outNXOpen.Drawings.DrawingRegionselection, outNXOpen.Viewview, outNXOpen.Point3dpoint)` | `unsafe void` | The object being selected with the object's view and point.More... |
| `GetValue(outNXOpen.InferSnapType.SnapTypesnapType, outNXOpen.Drawings.DrawingRegionselection1, outNXOpen.Viewview1, outNXOpen.Point3dpoint1, outNXOpen.Drawings.DrawingRegionselection2, outNXOpen.Viewview2, outNXOpen.Point3dpoint2)` | `unsafe void` | The object being selected with the objects view and point and snap information.More... |
| `GetValue(outNXOpen.CaeObjectType.CaeSubTypecaeSubType, out int caeSubId)` | `unsafeNXOpen.Drawings.DrawingRegion` | The object being selected with CAE set object information.More... |
| `SetValue(NXOpen.Drawings.DrawingRegionselection,NXOpen.Viewview,NXOpen.Point3dpoint)` | `unsafe void` | The object being selected with the object's view and object's pointMore... |
| `SetValue(NXOpen.InferSnapType.SnapTypesnapType,NXOpen.Drawings.DrawingRegionselection1,NXOpen.Viewview1,NXOpen.Point3dpoint1,NXOpen.Drawings.DrawingRegionselection2,NXOpen.Viewview2,NXOpen.Point3dpoint2)` | `unsafe void` | The object being selected with the objects view and objects point and snap information.More... |
| `SetValue(NXOpen.Drawings.DrawingRegionselection,NXOpen.CaeObjectType.CaeSubTypecaeSubType, int caeSubId)` | `unsafe void` | The object being selected with CAE set object information.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Value[get, set]` | `unsafeNXOpen.Drawings.DrawingRegion` | Returns or sets the object being selectedMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SelectDrawingView

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49816.html

Represents a single object selection

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetValue(outNXOpen.Drawings.DrawingViewselection, outNXOpen.Viewview, outNXOpen.Point3dpoint)` | `unsafe void` | The object being selected with the object's view and point.More... |
| `GetValue(outNXOpen.InferSnapType.SnapTypesnapType, outNXOpen.Drawings.DrawingViewselection1, outNXOpen.Viewview1, outNXOpen.Point3dpoint1, outNXOpen.Drawings.DrawingViewselection2, outNXOpen.Viewview2, outNXOpen.Point3dpoint2)` | `unsafe void` | The object being selected with the objects view and point and snap information.More... |
| `GetValue(outNXOpen.CaeObjectType.CaeSubTypecaeSubType, out int caeSubId)` | `unsafeNXOpen.Drawings.DrawingView` | The object being selected with CAE set object information.More... |
| `SetValue(NXOpen.Drawings.DrawingViewselection,NXOpen.Viewview,NXOpen.Point3dpoint)` | `unsafe void` | The object being selected with the object's view and object's pointMore... |
| `SetValue(NXOpen.InferSnapType.SnapTypesnapType,NXOpen.Drawings.DrawingViewselection1,NXOpen.Viewview1,NXOpen.Point3dpoint1,NXOpen.Drawings.DrawingViewselection2,NXOpen.Viewview2,NXOpen.Point3dpoint2)` | `unsafe void` | The object being selected with the objects view and objects point and snap information.More... |
| `SetValue(NXOpen.Drawings.DrawingViewselection,NXOpen.CaeObjectType.CaeSubTypecaeSubType, int caeSubId)` | `unsafe void` | The object being selected with CAE set object information.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Value[get, set]` | `unsafeNXOpen.Drawings.DrawingView` | Returns or sets the object being selectedMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SelectDrawingViewList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49820.html

Represents a list of objects on a selection list

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Add(NXOpen.Drawings.DrawingView@object)` | `unsafe bool` | Adds an object to the listMore... |
| `Add(NXOpen.Drawings.DrawingView[] objects)` | `unsafe bool` | Adds a set of objects to the listMore... |
| `Add(NXOpen.SelectionMethodinputSelectionMethod)` | `unsafe bool` | Adds the objects from a SelectionMethod to the listMore... |
| `Add(NXOpen.Drawings.DrawingViewselection,NXOpen.Viewview,NXOpen.Point3dpoint)` | `unsafe bool` | Adds the object with the objects view and objects pointMore... |
| `Add(NXOpen.InferSnapType.SnapTypesnapType,NXOpen.Drawings.DrawingViewselection1,NXOpen.Viewview1,NXOpen.Point3dpoint1,NXOpen.Drawings.DrawingViewselection2,NXOpen.Viewview2,NXOpen.Point3dpoint2)` | `unsafe bool` | The object being selected with the objects view and objects point and snap information.More... |
| `Add(NXOpen.Drawings.DrawingViewselection,NXOpen.CaeObjectType.CaeSubTypecaeSubType, int caeSubId)` | `unsafe bool` | The object being selected with CAE set object information.More... |
| `AddWithViews(NXOpen.Drawings.DrawingView[] objects,NXOpen.View[] views)` | `unsafe bool` | Adds a set of objects with views to the listMore... |
| `Clear()` | `unsafe void` | Removes all items from the list.More... |
| `Contains(NXOpen.Drawings.DrawingView@object)` | `unsafe bool` | Returns whether the specified object is already in the list or not.More... |
| `GetArray()` | `unsafeNXOpen.Drawings.DrawingView[]` | Returns the list of objects in the selection list.More... |
| `GetSelectObjectArray()` | `unsafeNXOpen.SelectObject[]` | Returns the list of SelectObjects in the selection list.More... |
| `Remove(NXOpen.Drawings.DrawingView@object)` | `unsafe bool` | Remove specified object from list.More... |
| `Remove(NXOpen.Drawings.DrawingView@object,NXOpen.Viewview)` | `unsafe bool` | Remove specified object from list.More... |
| `Remove(NXOpen.InferSnapType.SnapTypesnapType,NXOpen.Drawings.DrawingViewselection1,NXOpen.Viewview1,NXOpen.Point3dpoint1,NXOpen.Drawings.DrawingViewselection2,NXOpen.Viewview2,NXOpen.Point3dpoint2)` | `unsafe bool` | Remove specified object from list.More... |
| `Remove(NXOpen.SelectionMethodinputSelectionMethod)` | `unsafe bool` | Removes the objects from a SelectionMethod from the listMore... |
| `RemoveArray(NXOpen.Drawings.DrawingView[] objects)` | `unsafe bool` | Remove specified objects from list.More... |
| `SetArray(NXOpen.Drawings.DrawingView[] objects)` | `unsafe void` | Sets the list of objects in the selection list.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `DuplicatesAllowed[get]` | `unsafe bool` | Returns whether duplicate objects are allowed in the selection list.More... |
| `Size[get]` | `unsafe int` | Returns the number of objects in the list.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SelectModelViewBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49824.html

Represents a Select Model View builder that selects a model view

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
| `SelectedView[get, set]` | `unsafeNXOpen.ModelingView` | Returns or sets the selected viewMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SelectRegionBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49828.html

Creates the builder for associating the objects from the screen

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetAssociatedObjects(NXOpen.NXObject[] associateObject)` | `unsafe void` | Set the associated objectMore... |
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
| `SelectedRegion[get]` | `unsafeNXOpen.Drawings.SelectDrawingRegion` | Returns the get selected regionMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SelectSectionLine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49832.html

Represents a single object selection

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetValue(outNXOpen.Drawings.SectionLineselection, outNXOpen.Viewview, outNXOpen.Point3dpoint)` | `unsafe void` | The object being selected with the object's view and point.More... |
| `GetValue(outNXOpen.InferSnapType.SnapTypesnapType, outNXOpen.Drawings.SectionLineselection1, outNXOpen.Viewview1, outNXOpen.Point3dpoint1, outNXOpen.Drawings.SectionLineselection2, outNXOpen.Viewview2, outNXOpen.Point3dpoint2)` | `unsafe void` | The object being selected with the objects view and point and snap information.More... |
| `GetValue(outNXOpen.CaeObjectType.CaeSubTypecaeSubType, out int caeSubId)` | `unsafeNXOpen.Drawings.SectionLine` | The object being selected with CAE set object information.More... |
| `SetValue(NXOpen.Drawings.SectionLineselection,NXOpen.Viewview,NXOpen.Point3dpoint)` | `unsafe void` | The object being selected with the object's view and object's pointMore... |
| `SetValue(NXOpen.InferSnapType.SnapTypesnapType,NXOpen.Drawings.SectionLineselection1,NXOpen.Viewview1,NXOpen.Point3dpoint1,NXOpen.Drawings.SectionLineselection2,NXOpen.Viewview2,NXOpen.Point3dpoint2)` | `unsafe void` | The object being selected with the objects view and objects point and snap information.More... |
| `SetValue(NXOpen.Drawings.SectionLineselection,NXOpen.CaeObjectType.CaeSubTypecaeSubType, int caeSubId)` | `unsafe void` | The object being selected with CAE set object information.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Value[get, set]` | `unsafeNXOpen.Drawings.SectionLine` | Returns or sets the object being selectedMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SettingsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49836.html

Represents aDrawings.SettingsBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SaveConfigurationFile(string saveAsFile)` | `unsafe void` | API used to save settings dataMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AnnotationSettings[get]` | `unsafeNXOpen.Drawings.AnnotationSettingsBuilder` | Returns the Annotation settings builder which stores the annotation settingsMore... |
| `ConversionSettings[get]` | `unsafeNXOpen.Drawings.ConversionProcessSettingsBuilder` | Returns the Component settings builder which stores the component settingsMore... |
| `ViewSettings[get]` | `unsafeNXOpen.Drawings.ViewSettingsBuilder` | Returns the View settings builder which stores the view settingsMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ShadingViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49840.html

Represents set of Shading View style applicable to drafting views

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CustomAngleTolerance[get, set]` | `unsafe double` | Returns or sets the custom angle tolerance.More... |
| `CustomEdgeTolerance[get, set]` | `unsafe double` | Returns or sets the custom edge tolerance.More... |
| `CustomFaceTolerance[get, set]` | `unsafe double` | Returns or sets the custom face tolerance.More... |
| `OverrideHiddenWireframeColor[get, set]` | `unsafe int` | Returns or sets the hidden wireframe override color.More... |
| `OverrideVisibleWireframeColor[get, set]` | `unsafe int` | Returns or sets the visible wireframe override color.More... |
| `RenderingStyle[get, set]` | `unsafeNXOpen.Preferences.ShadingRenderingStyleOption` | Returns or sets the rendering style.More... |
| `ShadedCutFaceColor[get, set]` | `unsafe int` | Returns or sets the shaded cut face color.More... |
| `ShadingTolerance[get, set]` | `unsafeNXOpen.Preferences.ShadingToleranceOption` | Returns or sets the shading tolerance.More... |
| `Shininess[get, set]` | `unsafe double` | Returns or sets the shininess tolerance.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `TwoSidedLight[get, set]` | `unsafe bool` | Returns or sets the two sided light toggle data.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SheetBorderSettingsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49844.html

Represents aNXOpen.Drawings.SheetBorderSettingsBuilder

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
| `ArrowAngle[get, set]` | `unsafe double` | Returns or sets the arrow angleMore... |
| `ArrowDirection[get, set]` | `unsafeNXOpen.Drawings.ArrowDirectionType` | Returns or sets the arrow directionMore... |
| `ArrowHeadTail[get, set]` | `unsafe double` | Returns or sets the arrowhead tailMore... |
| `ArrowLength[get, set]` | `unsafe double` | Returns or sets the arrow lengthMore... |
| `ArrowStyle[get, set]` | `unsafeNXOpen.Drawings.ArrowStyleType` | Returns or sets the arrow styleMore... |
| `BorderLineWidth[get, set]` | `unsafe double` | Returns or sets the border line widthMore... |
| `CenteringMarkLength[get, set]` | `unsafe double` | Returns or sets the centering mark lengthMore... |
| `CenteringMarksColorWidth[get]` | `unsafeNXOpen.LineColorFontWidthBuilder` | Returns the centering marks color widthMore... |
| `CenteringMarksExtension[get, set]` | `unsafe double` | Returns or sets the centering marks extensionMore... |
| `CenteringMarksHorizontal[get, set]` | `unsafeNXOpen.Drawings.HorizontalCenteringMarkType` | Returns or sets the centering marks horizontalMore... |
| `CenteringMarksVertical[get, set]` | `unsafeNXOpen.Drawings.VerticalCenteringMarkType` | Returns or sets the centering marks verticalMore... |
| `CreateBorders[get, set]` | `unsafe bool` | Returns or sets the create bordersMore... |
| `CreateTrimmingMarks[get, set]` | `unsafe bool` | Returns or sets the create trimming marksMore... |
| `DisplaySheetSizeInBorder[get, set]` | `unsafe bool` | Returns or sets the display sheet size in borderMore... |
| `DistanceFromInnerBorder[get, set]` | `unsafe double` | Returns or sets the distance from inner borderMore... |
| `InnerLineCFW[get]` | `unsafeNXOpen.LineColorFontWidthBuilder` | Returns the inner border line's color, font and widthMore... |
| `Method[get, set]` | `unsafeNXOpen.Drawings.Method` | Returns or sets the methodMore... |
| `OuterLineCFW[get]` | `unsafeNXOpen.LineColorFontWidthBuilder` | Returns the outer border line's color, font and widthMore... |
| `TrimmingMarkColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the trimming mark colorMore... |
| `TrimmingMarkLength[get, set]` | `unsafe double` | Returns or sets the trimming mark lengthMore... |
| `TrimmingMarkStyle[get, set]` | `unsafeNXOpen.Drawings.TrimmingMarkStyleType` | Returns or sets the trimming mark styleMore... |
| `TrimmingMarkWidth[get, set]` | `unsafe double` | Returns or sets the trimming mark widthMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SheetDraftingViewCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49848.html

Represents a collection ofNXOpen.Drawings.DraftingViews

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateBaseView(NXOpen.ModelingViewmodelView,NXOpen.Point3ddrawingReferencePoint, double viewScale, bool inheritClippingBoundry)` | `unsafeNXOpen.Drawings.BaseView` | For the selected part adds the base view as well as returns the reference toNXOpen.Drawings.DraftingView.More... |
| `CreateProjectedView(NXOpen.Drawings.DraftingViewparentView,NXOpen.Point3ddrawingReferencePoint)` | `unsafeNXOpen.Drawings.ProjectedView` | Lets you add a projected view (Orthoraphic View) for the selected parent view.More... |
| `CreateProjectedView(NXOpen.Drawings.DraftingViewparentView,NXOpen.Point3ddrawingReferencePoint,NXOpen.DirectionhingeLine)` | `unsafeNXOpen.Drawings.ProjectedView` | Lets you add a projected view (A View) for the selected parent view.More... |
| `CreateProjectedView(NXOpen.Drawings.DraftingViewparentView,NXOpen.Point3ddrawingReferencePoint, bool reverseDirection)` | `unsafeNXOpen.Drawings.ProjectedView` | Lets you add a projected view (A View) for the selected parent view.More... |
| `DeleteView(NXOpen.Drawings.DraftingViewcurrentView)` | `unsafe void` | Lets you delete the viewMore... |
| `FindObject(string journalIdentifier)` | `unsafeNXOpen.Drawings.DraftingView` | Finds theNXOpen.Drawings.DraftingViewwith the given identifier as recorded in a journal.More... |
| `ToArray()` | `NXOpen.Drawings.DraftingView[]` | Returns an array ofNXOpen.Drawings.DraftingViewobjects.More... |
| `GetEnumerator()` | `IEnumerator` | Returns an enumerator that iterates through a collection.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |
| `EnumerateMoveNext(refTagcurrentTag, byte [] state)` | `override int` | Advances the enumerator to the next element of the collection.More... |
| `initialize()` | `new void` | <exclude>More... |
| `initialize()` | `void` | <exclude>More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SheetMarginSettingsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49852.html

Represents the Drawing Sheet Margins Style Builder

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
| `BottomTrimmedMargin[get, set]` | `unsafe double` | Returns or sets the bottom marginMore... |
| `BottomUntrimmedMargin[get, set]` | `unsafe double` | Returns or sets the bottom untrimmed marginMore... |
| `CreateUntrimmedMargins[get, set]` | `unsafe bool` | Returns or sets the create untrimmed marginsMore... |
| `LeftTrimmedMargin[get, set]` | `unsafe double` | Returns or sets the left marginMore... |
| `LeftUntrimmedMargin[get, set]` | `unsafe double` | Returns or sets the left untrimmed marginMore... |
| `MarginLineColorFontWidth[get]` | `unsafeNXOpen.LineColorFontWidthBuilder` | Returns the margin line color, font and widthMore... |
| `RightTrimmedMargin[get, set]` | `unsafe double` | Returns or sets the right marginMore... |
| `RightUntrimmedMargin[get, set]` | `unsafe double` | Returns or sets the right untrimmed marginMore... |
| `TopTrimmedMargin[get, set]` | `unsafe double` | Returns or sets the top marginMore... |
| `TopUntrimmedMargin[get, set]` | `unsafe double` | Returns or sets the top untrimmed marginMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SheetSectionLineCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49856.html

Represents a collection ofNXOpen.Drawings.SectionLines

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `ToArray()` | `NXOpen.Drawings.SectionLine[]` | Returns an array ofNXOpen.Drawings.SectionLineobjects.More... |
| `GetEnumerator()` | `IEnumerator` | Returns an enumerator that iterates through a collection.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |
| `EnumerateMoveNext(refTagcurrentTag, byte [] state)` | `override int` | Advances the enumerator to the next element of the collection.More... |
| `initialize()` | `new void` | <exclude>More... |
| `initialize()` | `void` | <exclude>More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SheetTemplateManager

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49860.html

Represents a manager ofNXOpen.Drawings.DraftingViews

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Create(string pathToPartName)` | `unsafe void` | Creates drawings via the sheet template, given a path to sheet templateMore... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SheetZoneReferenceBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49864.html

builder for creating sheet zone refernce control strings based on the selected attribute and view

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `SelectView[get]` | `unsafeNXOpen.Drawings.SelectDraftingView` | Returns the select viewMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SheetZoneSettingsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49868.html

Represents the Drawing Sheet Zone Setting Style Builder

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
| `ContinueZoneIndexingAcrossSheets[get, set]` | `unsafe bool` | Returns or sets the continue zone indexing across sheetsMore... |
| `CornerZoneModification[get, set]` | `unsafe double` | Returns or sets the corner zone modificationMore... |
| `CreateZoneLabels[get, set]` | `unsafe bool` | Returns or sets the create zone labelsMore... |
| `CreateZoneMarkings[get, set]` | `unsafe bool` | Returns or sets the create zone markingsMore... |
| `CreateZones[get, set]` | `unsafe bool` | Returns or sets the create zonesMore... |
| `HorizontalSize[get, set]` | `unsafe double` | Returns or sets the horizontal sizeMore... |
| `LabelColor[get, set]` | `unsafe int` | Returns or sets the labels colorMore... |
| `LabelFont[get, set]` | `unsafe int` | Returns or sets the labels fontMore... |
| `LabelHeight[get, set]` | `unsafe double` | Returns or sets the label heightMore... |
| `LabelItalicized[get, set]` | `unsafe bool` | Returns or sets the labels font styleMore... |
| `LabelsToSkip[get, set]` | `unsafe string` | Returns or sets the labels to skipMore... |
| `LabelWidth[get, set]` | `unsafe int` | Returns or sets the labels widthMore... |
| `MarkingHeight[get, set]` | `unsafe double` | Returns or sets the marking heightMore... |
| `MarkingLineColorWidth[get]` | `unsafeNXOpen.LineColorFontWidthBuilder` | Returns the marking line color widthMore... |
| `Origin[get, set]` | `unsafeNXOpen.Drawings.ZoneOrigin` | Returns or sets the originMore... |
| `VerticalSize[get, set]` | `unsafe double` | Returns or sets the vertical sizeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ShipDraftingViewLinesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49876.html

Represents a ship view lines block Default values

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `NonSectionedHiddenColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the non-sectioned hidden color on the Ship Structure LinesMore... |
| `NonSectionedHiddenFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the non-sectioned hidden font on the Ship Structure LinesMore... |
| `NonSectionedHiddenWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the non-sectioned hidden width on the Ship Structure LinesMore... |
| `NonSectionedSecondaryHiddenColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the Secondary non-sectioned hidden color on the Ship Structure LinesMore... |
| `NonSectionedSecondaryHiddenFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the Secondary non-sectioned hidden font on the Ship Structure LinesMore... |
| `NonSectionedSecondaryHiddenWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the Secondary non-sectioned hidden width on the Ship Structure LinesMore... |
| `NonSectionedSecondaryVisibleColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the Secondary non-sectioned visible color on the Ship Structure LinesMore... |
| `NonSectionedSecondaryVisibleFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the Secondary non-sectioned visible font on the Ship Structure LinesMore... |
| `NonSectionedSecondaryVisibleWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the Secondary non-sectioned visible width on the Ship Structure LinesMore... |
| `NonSectionedVisibleColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the non-sectioned visible color on the Ship Structure LinesMore... |
| `NonSectionedVisibleFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the non-sectioned visible font on the Ship Structure LinesMore... |
| `NonSectionedVisibleWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the non-sectioned visible width on the Ship Structure LinesMore... |
| `SectionedHiddenColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the sectioned hidden color on the Ship Structure LinesMore... |
| `SectionedHiddenFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the sectioned hidden font on the Ship Structure LinesMore... |
| `SectionedHiddenWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the sectioned hidden width on the Ship Structure LinesMore... |
| `SectionedSecondaryHiddenColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the Secondary sectioned hidden color on the Ship Structure LinesMore... |
| `SectionedSecondaryHiddenFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the Secondary sectioned hidden font on the Ship Structure LinesMore... |
| `SectionedSecondaryHiddenWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the Secondary sectioned hidden width on the Ship Structure LinesMore... |
| `SectionedSecondaryVisibleColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the Secondary sectioned visible color on the Ship Structure LinesMore... |
| `SectionedSecondaryVisibleFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the Secondary sectioned visible font on the Ship Structure LinesMore... |
| `SectionedSecondaryVisibleWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the Secondary sectioned visible width on the Ship Structure LinesMore... |
| `SectionedVisibleColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the sectioned visible color on the Ship Structure LinesMore... |
| `SectionedVisibleFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the sectioned visible font on the Ship Structure LinesMore... |
| `SectionedVisibleWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the sectioned visible width on the Ship Structure LinesMore... |
| `SingleLineRepresentation[get, set]` | `unsafe bool` | Returns or sets the single line representation toggleMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ShipDraftingViewLinesBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49880.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.Drawings.ShipDraftingViewLinesBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.Drawings.ShipDraftingViewLinesBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.Drawings.ShipDraftingViewLinesBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.Drawings.ShipDraftingViewLinesBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.Drawings.ShipDraftingViewLinesBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.Drawings.ShipDraftingViewLinesBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.Drawings.ShipDraftingViewLinesBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.Drawings.ShipDraftingViewLinesBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.Drawings.ShipDraftingViewLinesBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.Drawings.ShipDraftingViewLinesBuilderobject1,NXOpen.Drawings.ShipDraftingViewLinesBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.Drawings.ShipDraftingViewLinesViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49884.html

Represents set of Ship Drafting Lines View Style applicable to drafting views

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetColor(string featureName,NXOpen.Drawings.ShipDraftingViewLinesViewStyle.LineslinesType)` | `unsafeNXOpen.NXColor` | Gets line color.More... |
| `GetFont(string featureName,NXOpen.Drawings.ShipDraftingViewLinesViewStyle.LineslinesType)` | `unsafeNXOpen.Preferences.Font` | Gets line font.More... |
| `GetShipDrawingObject(string featureName)` | `unsafe bool` | Get ship drawing object status.More... |
| `GetWidth(string featureName,NXOpen.Drawings.ShipDraftingViewLinesViewStyle.LineslinesType)` | `unsafeNXOpen.Preferences.Width` | Gets line widthMore... |
| `SetColor(string featureName,NXOpen.Drawings.ShipDraftingViewLinesViewStyle.LineslinesType,NXOpen.NXColorcolor)` | `unsafe void` | The color of ship line.More... |
| `SetFont(string featureName,NXOpen.Drawings.ShipDraftingViewLinesViewStyle.LineslinesType,NXOpen.Preferences.Fontfont)` | `unsafe void` | The font type of ship line.More... |
| `SetShipDrawingObject(string featureName, bool singleLine)` | `unsafe void` | Note: The initial values are set based on the file NX_ShipAttribute.More... |
| `SetWidth(string featureName,NXOpen.Drawings.ShipDraftingViewLinesViewStyle.LineslinesType,NXOpen.Preferences.Widthwidth)` | `unsafe void` | The width of ship line.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ShipGeneralArrangementViewLinesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49888.html

Represents a ship view lines block

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AttributeName[get, set]` | `unsafe string` | Returns or sets the attribute nameMore... |
| `AttributeValue[get, set]` | `unsafe string` | Returns or sets the attribute valueMore... |
| `HiddenColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the hidden color on the Ship General Arrangement LinesMore... |
| `HiddenFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the hidden font on the Ship General Arrangement LinesMore... |
| `HiddenWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the hidden width on the Ship General Arrangement LinesMore... |
| `VisibleColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the visible color on the General Arrangement View LinesMore... |
| `VisibleFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the nvisible font on the Ship General Arrangement LinesMore... |
| `VisibleWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the visible width on the Ship General Arrangement LinesMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ShipGeneralArrangementViewLinesBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49892.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.Drawings.ShipGeneralArrangementViewLinesBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.Drawings.ShipGeneralArrangementViewLinesBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.Drawings.ShipGeneralArrangementViewLinesBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.Drawings.ShipGeneralArrangementViewLinesBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.Drawings.ShipGeneralArrangementViewLinesBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.Drawings.ShipGeneralArrangementViewLinesBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.Drawings.ShipGeneralArrangementViewLinesBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.Drawings.ShipGeneralArrangementViewLinesBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.Drawings.ShipGeneralArrangementViewLinesBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.Drawings.ShipGeneralArrangementViewLinesBuilderobject1,NXOpen.Drawings.ShipGeneralArrangementViewLinesBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.Drawings.ShipGeneralArrangementViewLinesViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49896.html

Represents set of Ship General Arrangement Lines View Style applicable to drafting views

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetAttributeName(string viewPlan, string displayName)` | `unsafe string` | Get the attribute name of the line type in general arrangement view.More... |
| `GetAttributeValue(string viewPlan, string displayName)` | `unsafe string` | Get the attribute value of the line type in general arrangement view.More... |
| `GetColor(string viewPlan, string displayName,NXOpen.Drawings.ShipGeneralArrangementViewLinesViewStyle.LineslinesType)` | `unsafeNXOpen.NXColor` | Gets line color.More... |
| `GetFont(string viewPlan, string displayName,NXOpen.Drawings.ShipGeneralArrangementViewLinesViewStyle.LineslinesType)` | `unsafeNXOpen.Preferences.Font` | Gets line font.More... |
| `GetWidth(string viewPlan, string displayName,NXOpen.Drawings.ShipGeneralArrangementViewLinesViewStyle.LineslinesType)` | `unsafeNXOpen.Preferences.Width` | Gets line widthMore... |
| `SetAttributeName(string viewPlan, string displayName, string attributeName)` | `unsafe void` | Set the attribute name of the line type in general arrangement view.More... |
| `SetAttributeValue(string viewPlan, string displayName, string attributeValue)` | `unsafe void` | Set the attribute value of the line type in general arrangement view.More... |
| `SetColor(string viewPlan, string displayName,NXOpen.Drawings.ShipGeneralArrangementViewLinesViewStyle.LineslinesType,NXOpen.NXColorcolor)` | `unsafe void` | The color of ship general arrangement line.More... |
| `SetFont(string viewPlan, string displayName,NXOpen.Drawings.ShipGeneralArrangementViewLinesViewStyle.LineslinesType,NXOpen.Preferences.Fontfont)` | `unsafe void` | The font type of ship line.More... |
| `SetWidth(string viewPlan, string displayName,NXOpen.Drawings.ShipGeneralArrangementViewLinesViewStyle.LineslinesType,NXOpen.Preferences.Widthwidth)` | `unsafe void` | The width of ship line.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ShipbuildingLinesViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49872.html

Represents set of Shipbuilding Lines View Style applicable to drafting views

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetColor(string featureName,NXOpen.Drawings.ShipbuildingLinesViewStyle.LineslinesType)` | `unsafe int` | Get line colorMore... |
| `GetFont(string featureName,NXOpen.Drawings.ShipbuildingLinesViewStyle.LineslinesType)` | `unsafeNXOpen.Preferences.Font` | Get line fontMore... |
| `GetSingleLineRepresentation(NXOpen.Drawings.ShipbuildingLinesViewStyle.ShipbuildingLinesfeatureType, string featureName)` | `unsafe bool` | Get single line statusMore... |
| `GetWidth(string featureName,NXOpen.Drawings.ShipbuildingLinesViewStyle.LineslinesType)` | `unsafeNXOpen.Preferences.Width` | Get line widthMore... |
| `SetColor(string featureName,NXOpen.Drawings.ShipbuildingLinesViewStyle.LineslinesType, int color)` | `unsafe void` | The color of ship line.More... |
| `SetFont(string featureName,NXOpen.Drawings.ShipbuildingLinesViewStyle.LineslinesType,NXOpen.Preferences.Fontfont)` | `unsafe void` | The font type of ship line.More... |
| `SetSingleLineRepresentation(NXOpen.Drawings.ShipbuildingLinesViewStyle.ShipbuildingLinesfeatureType, string featureName, bool singleLine)` | `unsafe void` | Note: The initial values are set based on the customer defaults depending on whether the feature is a Profile or a Plate.More... |
| `SetWidth(string featureName,NXOpen.Drawings.ShipbuildingLinesViewStyle.LineslinesType,NXOpen.Preferences.Widthwidth)` | `unsafe void` | The width of hidden line or edges.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SketchSectionLineBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49912.html

Represents aDrawings.SectionLinebuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetSketch(NXOpen.Sketchsketch)` | `unsafe void` | Set the sketchMore... |
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
| `AssociateToSketch[get, set]` | `unsafe bool` | Returns or sets the associate to sketchMore... |
| `FoldedToggle[get, set]` | `unsafe bool` | Returns or sets the folded toggleMore... |
| `ParentView[get]` | `unsafeNXOpen.Drawings.ParentViewBuilder` | Returns the parent viewMore... |
| `ReverseDirection[get, set]` | `unsafe bool` | Returns or sets the reverse directionMore... |
| `SectionLineType[get, set]` | `unsafeNXOpen.Drawings.SketchSectionLineBuilder.SectionLineTypes` | Returns or sets the section line typeMore... |
| `SectionType[get, set]` | `unsafeNXOpen.Drawings.SketchSectionLineBuilder.Type` | Returns or sets the section typeMore... |
| `Settings[get]` | `unsafeNXOpen.Drawings.SectionLineSettingsBuilder` | Returns the settingsMore... |
| `SketchSection[get]` | `unsafeNXOpen.Section` | Returns the sketch sectionMore... |
| `SourceView[get]` | `unsafeNXOpen.Drawings.SelectDraftingView` | Returns the source viewMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SketchedHalfSectionLine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49900.html

Sketched Half Section Line is sketch based section line


---

## NXOpen.Drawings.SketchedPointToPointSectionLine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49904.html

Sketched Point to Point Section Line is sketch based section line


---

## NXOpen.Drawings.SketchedSteppedSectionLine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49908.html

A Sketched Simple or Stepped Section Line is sketch based section line


---

## NXOpen.Drawings.SmoothEdgesViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49916.html

Represents set of Smooth Edges View Style Preferences applicable to drafting views

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `SmoothEdge[get, set]` | `unsafe bool` | Returns or sets the status of smooth edge.More... |
| `SmoothEdgeColor[get, set]` | `unsafe int` | Returns or sets the color of smooth edge.More... |
| `SmoothEdgeEndGaps[get, set]` | `unsafe bool` | Returns or sets the status of smooth edge end gaps.More... |
| `SmoothEdgeEndGapsData[get, set]` | `unsafe double` | Returns or sets the value of smooth edge end gaps.More... |
| `SmoothEdgeFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the font of smooth edge.More... |
| `SmoothEdgeTolerance[get, set]` | `unsafe bool` | Returns or sets the status of smooth edge angle tolerance.More... |
| `SmoothEdgeToleranceData[get, set]` | `unsafe double` | Returns or sets the value of smooth edge angle tolerance in degrees.More... |
| `SmoothEdgeWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the width of smooth edge.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SpecifySectionLineBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49920.html

Select a section line

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
| `SectionLine[get]` | `unsafeNXOpen.Drawings.SelectSectionLine` | Returns the section lineMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.StandardViewsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49924.html

This builder allows the user to create a Drawing View

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Autoscale[get, set]` | `unsafe bool` | Returns or sets the autoscale mode for base view creationMore... |
| `Coordinate[get]` | `unsafeNXOpen.Drawings.ViewCenterCoordinateBuilder` | Returns the center coordinateMore... |
| `FirstCorner[get]` | `unsafeNXOpen.Drawings.ViewPlacementBuilder` | Returns the first corner view placementMore... |
| `HiddenObjects[get]` | `unsafeNXOpen.Drawings.HiddenObjectsBuilder` | Returns the list of objects to not show in the viewMore... |
| `LayoutType[get, set]` | `unsafeNXOpen.Drawings.StandardViewsBuilder.Type` | Returns or sets the Layout typeMore... |
| `MarginBetweenViews[get, set]` | `unsafe double` | Returns or sets the margin between viewsMore... |
| `MarginToBorder[get, set]` | `unsafe double` | Returns or sets the margin to borderMore... |
| `MultipleViewPlacement[get]` | `unsafeNXOpen.Drawings.MultipleViewPlacementBuilder` | Returns the multiple view placementMore... |
| `NonSectionedObjects[get]` | `unsafeNXOpen.Drawings.HiddenObjectsBuilder` | Returns the list of objects to not section in the viewMore... |
| `Part[get, set]` | `unsafeNXOpen.Part` | Returns or sets the part to use for base viewsMore... |
| `PlacementType[get, set]` | `unsafeNXOpen.Drawings.StandardViewsBuilder.Placement` | Returns or sets the Placement typeMore... |
| `Scale[get]` | `unsafeNXOpen.Drawings.ViewScaleBuilder` | Returns the view scaleMore... |
| `SecondaryComponents[get]` | `unsafeNXOpen.Drawings.DraftingComponentSelectionBuilder` | Returns the list of secondary objects in the viewMore... |
| `SecondCorner[get]` | `unsafeNXOpen.Drawings.ViewPlacementBuilder` | Returns the second corner view placementMore... |
| `ViewPlacement[get]` | `unsafeNXOpen.Drawings.ViewPlacementBuilder` | Returns the view placementMore... |
| `ViewStyle[get]` | `unsafeNXOpen.Drawings.ViewStyleBuilder` | Returns the view styleMore... |
| `ViewType[get, set]` | `unsafeNXOpen.Drawings.StandardViewsBuilder.View` | Returns or sets the view typeMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SteppedSectionLine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49928.html

A Simple or Stepped Section Line


---

## NXOpen.Drawings.SteppedSectionLineBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49932.html

Represents aNXOpen.Drawings.SteppedSectionLineBuilder

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
| `EndLocation1[get, set]` | `unsafeNXOpen.Point` | Returns or sets the end location 1 which determines the position of the first arrow segment in the section line.More... |
| `EndLocation2[get, set]` | `unsafeNXOpen.Point` | Returns or sets the end location 2 which determines the position of the second arrow segment in the section lineMore... |
| `Leg1[get]` | `unsafeNXOpen.Drawings.SectionLineSegmentBuilderList` | Returns the list of cut and bend segments.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.SvtBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49936.html

Represents aNXOpen.Drawings.SvtBuilder

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
| `BackgroundFaces[get]` | `unsafeNXOpen.SelectFaceList` | Returns the background faces that are to be shown in the section view.More... |
| `NormalDirection[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the vector that represents the normal direction for the view to be created or edited.More... |
| `Orientation[get, set]` | `unsafe bool` | Returns or sets the orientation flag that indicates whether or not the Section View Tool view should be used to orient the section view when it is placedMore... |
| `XDirection[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the x direction vector for the view to be created or edited.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ThreadsViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49940.html

Represents set of Threads View Style Preferences applicable to drafting views

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `MinimumPitchField[get, set]` | `unsafe double` | Returns or sets the minimum pitch field.More... |
| `OverrideVisibleThreadColor[get, set]` | `unsafe int` | Returns or sets the visible thread override color.More... |
| `RenderTrueHiddenLine[get, set]` | `unsafe bool` | Returns or sets the status of render true hidden lineMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `ThreadsStandardOptionData[get, set]` | `unsafe int` | Returns or sets the threads standard optionMore... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.TraceLinesViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49944.html

Represents interface for Trace Lines View Style Preferences applicable to drafting views

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CreateGapsStatus[get, set]` | `unsafe bool` | Returns or sets the status of create gapsMore... |
| `GapSize[get, set]` | `unsafe double` | Returns or sets the gap sizeMore... |
| `HiddenColor[get, set]` | `unsafe int` | Returns or sets the hidden color.More... |
| `HiddenFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the hidden fontMore... |
| `HiddenWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the hidden widthMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `VisibleColor[get, set]` | `unsafe int` | Returns or sets the visible color.More... |
| `VisibleFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the visible fontMore... |
| `VisibleWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the visible widthMore... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.TrackDrawingChangesGeneralBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49948.html

Represents aNXOpen.Drawings.TrackDrawingChangesGeneralBuilder

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
| `BaselineOfComparison[get, set]` | `unsafeNXOpen.Drawings.TrackDrawingChangesGeneralBuilder.BaselineOfComparisonType` | Returns or sets the baseline of comparisonMore... |
| `ChangeSymbolLineColorFontWidth[get]` | `unsafeNXOpen.LineColorFontWidthBuilder` | Returns the change symbol line color font widthMore... |
| `ChangeSymbolSize[get, set]` | `unsafe double` | Returns or sets the change symbol sizeMore... |
| `ChangeSymbolType[get, set]` | `unsafeNXOpen.Drawings.TrackDrawingChangesGeneralBuilder.SymbolType` | Returns or sets the change symbol typeMore... |
| `CompareMethod[get, set]` | `unsafeNXOpen.Drawings.TrackDrawingChangesGeneralBuilder.CompareMethodType` | Returns or sets the compare methodMore... |
| `CompareTolerance[get, set]` | `unsafe double` | Returns or sets the compare toleranceMore... |
| `CreateOverlayDataWithSnapshotData[get, set]` | `unsafe bool` | Returns or sets the create overlay data with snapshot dataMore... |
| `DisplayChangeSymbol[get, set]` | `unsafe bool` | Returns or sets the display change symbolMore... |
| `IncrementIDNumberPerReport[get, set]` | `unsafe bool` | Returns or sets the increment id number per reportMore... |
| `PreserveChangeSymbolDisplay[get, set]` | `unsafe bool` | Returns or sets the preserve Change Symbol DisplayMore... |
| `RestartIDNumbersWithNewReport[get, set]` | `unsafe bool` | Returns or sets the restart id numbers with new reportMore... |
| `SnapshotDataToUse[get, set]` | `unsafeNXOpen.Drawings.TrackDrawingChangesGeneralBuilder.SnapshotDataToUseType` | Returns or sets the snapshot data to useMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.TrackDrawingChangesReportFilterBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49952.html

Represents aDrawings.TrackDrawingChangesReportFilterBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetReportFilterStatus(NXOpen.Drawings.TrackDrawingChangesReportFilterBuilder.FilterreportFilterType)` | `unsafe bool` | Returns report filter statusMore... |
| `SetReportFilterStatus(NXOpen.Drawings.TrackDrawingChangesReportFilterBuilder.FilterreportFilterType, bool reportFilterStatus)` | `unsafe void` | Sets report filter statusMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |


---

## NXOpen.Drawings.UpdateViewsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49956.html

Represents aNXOpen.Drawings.UpdateViewsBuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Views[get]` | `unsafeNXOpen.SelectObjectList` | Returns the selected viewsMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.View2dOrientBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49960.html

Represents the View 2D Orientation (Drawings

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetCustomNormalX()` | `unsafe double` | Returns the X component of the custom view-normal vectorMore... |
| `GetCustomNormalY()` | `unsafe double` | Returns the Y component of the custom view-normal vectorMore... |
| `GetCustomNormalZ()` | `unsafe double` | Returns the Z component of the custom view-normal vectorMore... |
| `GetCustomPrimaryX()` | `unsafe double` | Returns the X component of the custom view-primary vectorMore... |
| `GetCustomPrimaryY()` | `unsafe double` | Returns the Y component of the custom view-primary vectorMore... |
| `GetCustomPrimaryZ()` | `unsafe double` | Returns the Z component of the custom view-primary vectorMore... |
| `GetInferredPrimary()` | `unsafe bool` | Returns the option to infer the direction view X vector in 3D spaceMore... |
| `SetCustomNormalX(double component)` | `unsafe void` | Sets the X component of the custom view-normal vectorMore... |
| `SetCustomNormalY(double component)` | `unsafe void` | Sets the Y component of the custom view-normal vectorMore... |
| `SetCustomNormalZ(double component)` | `unsafe void` | Sets the Z component of the custom view-normal vectorMore... |
| `SetCustomPrimaryX(double component)` | `unsafe void` | Sets the X component of the custom view-primary vectorMore... |
| `SetCustomPrimaryY(double component)` | `unsafe void` | Sets the Y component of the custom view-primary vectorMore... |
| `SetCustomPrimaryZ(double component)` | `unsafe void` | Sets the Z component of the custom view-primary vectorMore... |
| `SetInferredPrimary(bool inferred)` | `unsafe void` | Sets the option to infer the direction view X vector in 3D spaceMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CustomOrientationMethod[get, set]` | `unsafeNXOpen.Drawings.View2dOrientBuilder.CustomMethod` | Returns or sets the custom orientation methodMore... |
| `CustomXAngle[get, set]` | `unsafe double` | Returns or sets the orientation angle around the X axisMore... |
| `CustomYAngle[get, set]` | `unsafe double` | Returns or sets the orientation angle around the Y axisMore... |
| `CustomZAngle[get, set]` | `unsafe double` | Returns or sets the orientation angle around the Z axisMore... |
| `OrientationType[get, set]` | `unsafeNXOpen.Drawings.View2dOrientBuilder.Type` | Returns or sets the orientation typeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewAlignment

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49964.html

View Alignment object


---

## NXOpen.Drawings.ViewAlignmentBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49968.html

Represents aNXOpen.Drawings.ViewAlignmentBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `DeleteCurrentAlignment()` | `unsafe void` | Deletes a view alignment that is stored as the current alignment in the builderMore... |
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
| `CandidateView[get, set]` | `unsafeNXOpen.Drawings.DraftingView` | Returns or sets the candidate view in builderMore... |
| `InEditMode[get, set]` | `unsafe bool` | Returns or sets the builder edit mode flag.More... |
| `Placement[get]` | `unsafeNXOpen.Drawings.ViewPlacementBuilder` | Returns the view placement componentMore... |
| `SelectedAlignment[get, set]` | `unsafeNXOpen.Drawings.ViewAlignment` | Returns or sets the selected alignment in builder.More... |
| `View[get]` | `unsafeNXOpen.Drawings.SelectDraftingView` | Returns the select drafting view componentMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewAlignmentCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49972.html

Represents a collection ofNXOpen.Drawings.ViewAlignments

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateViewAlignmentBuilder()` | `unsafeNXOpen.Drawings.ViewAlignmentBuilder` | Creates aNXOpen.Drawings.ViewAlignmentBuilderMore... |
| `FindObject(string journalIdentifier)` | `unsafeNXOpen.Drawings.ViewAlignment` | Finds theNXOpen.Drawings.ViewAlignmentwith the given identifier as recorded in a journal.More... |
| `ToArray()` | `NXOpen.Drawings.ViewAlignment[]` | Returns an array ofNXOpen.Drawings.ViewAlignmentobjects.More... |
| `GetEnumerator()` | `IEnumerator` | Returns an enumerator that iterates through a collection.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |
| `EnumerateMoveNext(refTagcurrentTag, byte [] state)` | `override int` | Advances the enumerator to the next element of the collection.More... |
| `initialize()` | `new void` | <exclude>More... |
| `initialize()` | `void` | <exclude>More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewBoundaryBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49976.html

Represents the View Boundary (Drawings

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
| `BoundaryPoint1[get, set]` | `unsafeNXOpen.Point` | Returns or sets the first corner pointMore... |
| `BoundaryPoint2[get, set]` | `unsafeNXOpen.Point` | Returns or sets the second corner pointMore... |
| `BoundaryType[get, set]` | `unsafeNXOpen.Drawings.ViewBoundaryBuilder.Type` | Returns or sets the orientation typeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewBreak

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49980.html

ViewBreak - defines the portion of a view that gets hidden to produce a broken view

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetViewBreakDisplayableObjectsAndOffsets(outNXOpen.DisplayableObject[] displayObjects)` | `unsafeNXOpen.Vector3d[]` | Returns an array of displayable object and theirs offsets representing the view break in the view.More... |
| `CreateAttributeIterator()` | `unsafeNXOpen.AttributeIterator` | Create an attribute iteratorMore... |
| `DeleteAllAttributesByType(NXOpen.NXObject.AttributeTypetype)` | `unsafe void` | Deletes all attributes of a specific type.More... |
| `DeleteAllAttributesByType(NXOpen.NXObject.AttributeTypetype,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes all attributes of a specific type with the option to update or not.More... |
| `DeleteAttributeByTypeAndTitle(NXOpen.NXObject.AttributeTypetype, string title)` | `unsafe void` | Deletes an attribute by type and title.More... |
| `DeleteAttributeByTypeAndTitle(NXOpen.NXObject.AttributeTypetype, string title,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes an attribute by type and title with the option to update or not.More... |
| `DeleteUserAttribute(NXOpen.NXObject.AttributeTypetype, string title, bool deleteEntireArray,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes the first attribute encountered with the given Type, Title.More... |
| `DeleteUserAttributes(NXOpen.AttributeIteratoriterator,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes the attributes on the object, if any, that satisfy the given iteratorMore... |
| `DeleteUserAttributes(NXOpen.NXObject.AttributeTypetype,NXOpen.Update.Optionoption)` | `unsafe void` | Deletes the attributes encountered with the given Type with option to update or not.More... |
| `FindObject(string journalIdentifier)` | `unsafeNXOpen.INXObject` | Finds theNXOpen.NXObjectwith the given identifier as recorded in a journal.More... |
| `GetAttributeTitlesByType(NXOpen.NXObject.AttributeTypetype)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attribute titles of a specific type.More... |
| `GetBooleanUserAttribute(string title, int index)` | `unsafe bool` | Gets a boolean attribute by Title and array Index.More... |
| `GetComputationalTimeUserAttribute(string title, int index)` | `unsafeNXOpen.NXObject.ComputationalTime` | Gets a time attribute by Title and array Index.More... |
| `GetIntegerAttribute(string title)` | `unsafe int` | Gets an integer attribute by title.More... |
| `GetIntegerUserAttribute(string title, int index)` | `unsafe int` | Gets an integer attribute by Title and array Index.More... |
| `GetNextUserAttribute(NXOpen.AttributeIteratoriterator, outNXOpen.NXObject.AttributeInformationinfo)` | `unsafe bool` | Gets the next attribute encountered on the object, if any, that satisfies the given iterator.More... |
| `GetPdmReferenceAttributeValue(string attributeTitle)` | `unsafe string` | Gets the value of PDM Reference attribute for given object.More... |
| `GetRealAttribute(string title)` | `unsafe double` | Gets a real attribute by title.More... |
| `GetRealUserAttribute(string title, int index)` | `unsafe double` | Gets a real attribute by Title and array Index.More... |
| `GetReferenceAttribute(string title)` | `unsafe string` | Gets the reference string (not the calculated value) of a string attribute that uses a reference string.More... |
| `GetStringAttribute(string title)` | `unsafe string` | Gets a string attribute value by title.More... |
| `GetStringUserAttribute(string title, int index)` | `unsafe string` | Gets a string attribute by Title and array Index.More... |
| `GetTimeAttribute(NXOpen.NXObject.DateAndTimeFormatformat, string title)` | `unsafe string` | Gets a time attribute by title.More... |
| `GetTimeUserAttribute(string title, int index)` | `unsafe string` | Gets a time attribute by Title and array Index.More... |
| `GetUserAttribute(string title,NXOpen.NXObject.AttributeTypetype, int index)` | `unsafeNXOpen.NXObject.AttributeInformation` | Gets the first attribute encountered on the object, if any, with a given Title, Type and array Index.More... |
| `GetUserAttribute(string title, bool includeUnset, bool addStringValues,NXOpen.NXObject.AttributeTypetype)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets the first attribute (or attribute array) encountered on the object, if any, with a given Title and Type.More... |
| `GetUserAttributeAsString(string title,NXOpen.NXObject.AttributeTypetype, int index)` | `unsafe string` | Gets the first attribute encountered on the object, if any, with a given title, type and array index.More... |
| `GetUserAttributeCount(NXOpen.AttributeIteratoriterator)` | `unsafe int` | Gets the count of set attributes on the object, if any, that satisfy the given iterator.More... |
| `GetUserAttributeCount(NXOpen.AttributeIteratoriterator, bool countArrayAsOneAttribute)` | `unsafe int` | Gets the count of set attributes on the object, if any, that satisfy the given iterator.More... |
| `GetUserAttributeCount(NXOpen.NXObject.AttributeTypetype)` | `unsafe int` | Gets the count of set attributes on the object, if any, of the given type.More... |
| `GetUserAttributeCount(NXOpen.NXObject.AttributeTypetype, bool includeUnset, bool countArrayAsOneAttribute)` | `unsafe int` | Gets the count of attributes on the object, if any, of the given type.More... |
| `GetUserAttributeLock(string title,NXOpen.NXObject.AttributeTypetype)` | `unsafe bool` | Determine the lock of the given attribute.More... |
| `GetUserAttributes(NXOpen.AttributeIteratoriterator)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes that have been set on the given object, if any, that satisfy the given iterator.More... |
| `GetUserAttributes()` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes that have been set on the given object.More... |
| `GetUserAttributes(bool includeUnset)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes of the given object.More... |
| `GetUserAttributes(bool includeUnset, bool addStringValues)` | `unsafeNXOpen.NXObject.AttributeInformation[]` | Gets all the attributes of the given object.More... |
| `GetUserAttributesAsStrings()` | `unsafe string []` | Gets all the attributes that have been set on the given object.More... |
| `GetUserAttributeSize(string title,NXOpen.NXObject.AttributeTypetype)` | `unsafe int` | Gets the size of the first attribute encountered on the object, if any, with a given Title and Type.More... |
| `GetUserAttributeSourceObjects()` | `unsafeNXOpen.NXObject[]` | Returns an array of objects from which this object presents attributes.More... |
| `HasUserAttribute(NXOpen.AttributeIteratoriterator)` | `unsafe bool` | Determines if an attribute exists on the object, that satisfies the given iteratorMore... |
| `HasUserAttribute(string title,NXOpen.NXObject.AttributeTypetype, int index)` | `unsafe bool` | Determines if an attribute with the given Title, Type and array Index is present on the object Unset attributes will not be detected by this function, as its purpose is to test for the actual presence of the attribute on the object.More... |
| `Print()` | `unsafe void` | Prints a representation of this object to the system log file.More... |
| `SetAttribute(string title, int value)` | `unsafe void` | Creates or modifies an integer attribute.More... |
| `SetAttribute(string title, int value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies an integer attribute with the option to update or not.More... |
| `SetAttribute(string title, double value)` | `unsafe void` | Creates or modifies a real attribute.More... |
| `SetAttribute(string title, double value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a real attribute with the option to update or not.More... |
| `SetAttribute(string title, string value)` | `unsafe void` | Creates or modifies a string attribute.More... |
| `SetAttribute(string title, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a string attribute with the option to update or not.More... |
| `SetAttribute(string title)` | `unsafe void` | Creates or modifies a null attribute which is an attribute with a title and no value.More... |
| `SetAttribute(string title,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a null attribute with the option to update or not.More... |
| `SetBooleanUserAttribute(string title, int index, bool value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a boolean attribute with the option to update or not.More... |
| `SetName(string name)` | `unsafe void` | Sets the custom name of the object.More... |
| `SetPdmReferenceAttribute(string attributeTitle, string attributeValue)` | `unsafe void` | Sets the value of PDM Reference attribute on the object.More... |
| `SetReferenceAttribute(string title, string value)` | `unsafe void` | Creates or modifies a string attribute which uses a reference string.More... |
| `SetReferenceAttribute(string title, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a string attribute which uses a reference string, with the option to update or not.More... |
| `SetTimeAttribute(string title, string value)` | `unsafe void` | Creates or modifies a time attribute.More... |
| `SetTimeAttribute(string title, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a time attribute with the option to update or not.More... |
| `SetTimeUserAttribute(string title, int index, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a time attribute with the option to update or not.More... |
| `SetTimeUserAttribute(string title, int index,NXOpen.NXObject.ComputationalTimevalue,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a time attribute with the option to update or not.More... |
| `SetUserAttribute(NXOpen.NXObject.AttributeInformationinfo,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies an attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index, int value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies an integer attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index, double value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a real attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index, string value,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a string attribute with the option to update or not.More... |
| `SetUserAttribute(string title, int index,NXOpen.Update.Optionoption)` | `unsafe void` | Creates or modifies a null attribute with the option to update or not.More... |
| `SetUserAttributeLock(string title,NXOpen.NXObject.AttributeTypetype, bool @lock)` | `unsafe void` | Lock or unlock the given attribute.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |


---

## NXOpen.Drawings.ViewBreakBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49984.html

Represents aNXOpen.Drawings.ViewBreakBuilder

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
| `AddForeshorteningSymbol[get, set]` | `unsafe bool` | Returns or sets the foreshortening symbol additionMore... |
| `BreakGap[get, set]` | `unsafe double` | Returns or sets the break gapMore... |
| `BreakLineAmplitude[get, set]` | `unsafe double` | Returns or sets the break line amplitudeMore... |
| `BreakLineColorWidth[get]` | `unsafeNXOpen.LineColorFontWidthBuilder` | Returns the break line color widthMore... |
| `BreakLineExtension[get, set]` | `unsafe double` | Returns or sets the break line extensionMore... |
| `BreakLineStyle[get, set]` | `unsafeNXOpen.Drawings.ViewBreakBuilder.Viewbreaklinestyle` | Returns or sets the break line styleMore... |
| `PropagateViewBreak[get, set]` | `unsafe bool` | Returns or sets the propagate view breakMore... |
| `ShowBreakLines[get, set]` | `unsafe bool` | Returns or sets the show break linesMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewBreakCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49988.html

Represents a collection ofNXOpen.Drawings.ViewBreaks

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `FindObject(string journalIdentifier)` | `unsafeNXOpen.Drawings.ViewBreak` | Finds theNXOpen.Drawings.DraftingViewwith the given identifier as recorded in a journal.More... |
| `ToArray()` | `NXOpen.Drawings.ViewBreak[]` | Returns an array ofNXOpen.Drawings.ViewBreakobjects.More... |
| `GetEnumerator()` | `IEnumerator` | Returns an enumerator that iterates through a collection.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |
| `EnumerateMoveNext(refTagcurrentTag, byte [] state)` | `override int` | Advances the enumerator to the next element of the collection.More... |
| `initialize()` | `new void` | <exclude>More... |
| `initialize()` | `void` | <exclude>More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewCenterCoordinateBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49992.html

Represents the View center coodinate (Drawings

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
| `XCoordinate[get, set]` | `unsafe double` | Returns or sets the X center coordinateMore... |
| `XCoordinateExp[get]` | `unsafeNXOpen.Expression` | Returns the expression for the X coordinateMore... |
| `YCoordinate[get, set]` | `unsafe double` | Returns or sets the Y center coordinateMore... |
| `YCoordinateExp[get]` | `unsafeNXOpen.Expression` | Returns the expression for the Y coordinateMore... |
| `ZCoordinate[get, set]` | `unsafe double` | Returns or sets the Z center coordinateMore... |
| `ZCoordinateExp[get]` | `unsafeNXOpen.Expression` | Returns the expression for the Z coordinateMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewCommonViewLabelBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a49996.html

Represents aNXOpen.Drawings.ViewCommonViewLabelBuilder

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
| `Letter[get, set]` | `unsafe string` | Returns or sets the letterMore... |
| `SecondaryAlignment[get, set]` | `unsafeNXOpen.Drawings.ViewCommonViewLabelBuilder.SecondaryAlignmentType` | Returns or sets the secondary alignmentMore... |
| `SecondaryIndexing[get, set]` | `unsafeNXOpen.Drawings.ViewCommonViewLabelBuilder.SecondaryIndexingType` | Returns or sets the secondary indexingMore... |
| `SubscriptSizeFactor[get, set]` | `unsafe double` | Returns or sets the subscript size factorMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewCopyTo3dBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50000.html

Represents aNXOpen.Drawings.ViewCopyTo3dBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Commit(double offset, bool curves, bool sketches, int option)` | `unsafe void` | The copy of the selected view to modelingMore... |
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
| `BoundingBox[get, set]` | `unsafeNXOpen.Drawings.ViewCopyTo3dBuilder.BoundingBoxOption` | Returns or sets the type of bounding boxMore... |
| `BoundingViews[get]` | `unsafeNXOpen.Drawings.SelectDrawingViewList` | Returns the select views in the placement groupMore... |
| `CreateSketches[get, set]` | `unsafe bool` | Returns or sets the flag indicating to create sketches in ModelingMore... |
| `Curves[get]` | `unsafeNXOpen.SelectNXObjectList` | Returns the select curves for source groupMore... |
| `DestinationPart[get, set]` | `unsafe string` | Returns or sets the path to the destination partMore... |
| `DistanceFromViewPlane[get, set]` | `unsafeNXOpen.Drawings.ViewCopyTo3dBuilder.DistanceFromViewPlaneOption` | Returns or sets the option specifying the distance from the view planeMore... |
| `ExtrudeSolidBody[get, set]` | `unsafe bool` | Returns or sets the flag that indicates whether to extrude solidMore... |
| `Offset[get]` | `unsafeNXOpen.Expression` | Returns the expression of clearanceMore... |
| `Output[get, set]` | `unsafeNXOpen.Drawings.ViewCopyTo3dBuilder.OutputOption` | Returns or sets the option of output in the setting groupMore... |
| `ProcessSketchCurves[get, set]` | `unsafe bool` | Returns or sets the flag indicating to process sketch curvesMore... |
| `ProcessViewCurves[get, set]` | `unsafe bool` | Returns or sets the flag indicating to process view curvesMore... |
| `RepositionGeometry[get, set]` | `unsafe bool` | Returns or sets the flag that indicates whether to automatically reposition geometryMore... |
| `Type[get, set]` | `unsafeNXOpen.Drawings.ViewCopyTo3dBuilder.Types` | Returns or sets the type of copyMore... |
| `View[get]` | `unsafeNXOpen.Drawings.SelectDrawingView` | Returns the selected view for previous single view selectionMore... |
| `Views[get]` | `unsafeNXOpen.Drawings.SelectDrawingViewList` | Returns the selected views for multiple views selectionMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewCreationWizardBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50004.html

This builder allows the user to create a Drawing View

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AssociativeAlignment[get, set]` | `unsafe bool` | Returns or sets the associative alignment toggleMore... |
| `AutoScale[get, set]` | `unsafe bool` | Returns or sets the auto scaleMore... |
| `BackView[get, set]` | `unsafe bool` | Returns or sets the back viewMore... |
| `BaseView[get, set]` | `unsafe string` | Returns or sets the base viewMore... |
| `BottomView[get, set]` | `unsafe bool` | Returns or sets the bottom viewMore... |
| `CenterLines[get, set]` | `unsafe bool` | Returns or sets the center linesMore... |
| `CrosshatchInheritedSectionViews[get, set]` | `unsafe bool` | Returns or sets the crosshatch inherited section viewsMore... |
| `CustomViewSettingsBuilder[get]` | `unsafeNXOpen.Drawings.CustomViewSettingsBuilder` | Returns theNXOpen.Drawings.CustomViewSettingsBuilderobjectMore... |
| `ExtractedEdges[get, set]` | `unsafe bool` | Returns or sets the extracted edges optionMore... |
| `FrontView[get, set]` | `unsafe bool` | Returns or sets the front viewMore... |
| `HiddenLineColor[get, set]` | `unsafe int` | Returns or sets the hidden line colorMore... |
| `HiddenLineFont[get, set]` | `unsafe int` | Returns or sets the hidden line fontMore... |
| `HiddenLines[get, set]` | `unsafe bool` | Returns or sets the hidden linesMore... |
| `HiddenLineWidth[get, set]` | `unsafe int` | Returns or sets the hidden line widthMore... |
| `IgnoreTitleBlock[get, set]` | `unsafe bool` | Returns or sets the ignore title blockMore... |
| `InheritPMI[get, set]` | `unsafe int` | Returns or sets the inherit pmiMore... |
| `InheritPmiOntoDrawing[get, set]` | `unsafe bool` | Returns or sets the inherit pmi onto drawingMore... |
| `IsometricView[get, set]` | `unsafe bool` | Returns or sets the isometric viewMore... |
| `LeftView[get, set]` | `unsafe bool` | Returns or sets the left viewMore... |
| `LockMethod[get, set]` | `unsafeNXOpen.Preferences.GeneralViewLockmethodOption` | Returns or sets the lock method optionMore... |
| `MarginBetweenViews[get, set]` | `unsafe double` | Returns or sets the margin between viewsMore... |
| `MarginToBorder[get, set]` | `unsafe double` | Returns or sets the margin to borderMore... |
| `MultipleViewPlacement[get]` | `unsafeNXOpen.Drawings.MultipleViewPlacementBuilder` | Returns the multiple view placementMore... |
| `OptimizeSettings[get, set]` | `unsafe bool` | Returns or sets the optimize view settingsMore... |
| `OrientViewTool[get]` | `unsafeNXOpen.Drawings.OvtBuilder` | Returns the orient view toolMore... |
| `Part[get, set]` | `unsafeNXOpen.Part` | Returns or sets the partMore... |
| `PlacementOption[get, set]` | `unsafeNXOpen.Drawings.ViewCreationWizardBuilder.Option` | Returns or sets the placement optionMore... |
| `PmiDimensionFromRevolved[get, set]` | `unsafe bool` | Returns or sets the inherit pmi from revolved sketchesMore... |
| `PmiTypes[get, set]` | `unsafe int` | Returns or sets the pmi typesMore... |
| `Resolution[get, set]` | `unsafeNXOpen.Drawings.ViewCreationWizardBuilder.ResolutionOption` | Returns or sets the display quality optionMore... |
| `RightView[get, set]` | `unsafe bool` | Returns or sets the right viewMore... |
| `Silhouettes[get, set]` | `unsafe bool` | Returns or sets the silhouettesMore... |
| `SnapShot[get, set]` | `unsafe bool` | Returns or sets the snapshot optionMore... |
| `SpecialBaseView[get, set]` | `unsafe bool` | Returns or sets the special base viewMore... |
| `Tolerance[get, set]` | `unsafe double` | Returns or sets the tolerance optionMore... |
| `TopView[get, set]` | `unsafe bool` | Returns or sets the top viewMore... |
| `TrimetricView[get, set]` | `unsafe bool` | Returns or sets the trimetric viewMore... |
| `ViewBoundary[get, set]` | `unsafeNXOpen.Drawings.ViewCreationWizardBuilder.ViewBoundaryOption` | Returns or sets the view boundary optionMore... |
| `ViewLabels[get, set]` | `unsafe bool` | Returns or sets the view labelsMore... |
| `ViewRepresentation[get, set]` | `unsafeNXOpen.Drawings.ViewCreationWizardBuilder.ViewRepresentations` | Returns or sets the view representation stateMore... |
| `ViewScale[get]` | `unsafeNXOpen.Drawings.ViewScaleBuilder` | Returns the view scaleMore... |
| `ViewStyle[get]` | `unsafeNXOpen.Drawings.ViewStyleBuilder` | Returns the view styleMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewDetailLabelBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50008.html

Represents aNXOpen.Drawings.ViewDetailLabelBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetCustomizedViewLabelText()` | `unsafe string []` | Returns the customized view label textMore... |
| `SetCustomizedViewLabelText(string [] customizedText)` | `unsafe void` | Sets the customized view label textMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CustomizedViewLabel[get, set]` | `unsafe bool` | Returns or sets the customized view labelMore... |
| `IncludeParentheses[get, set]` | `unsafe bool` | Returns or sets the include parenthesesMore... |
| `LabelCharacterHeightFactor[get, set]` | `unsafe double` | Returns or sets the section vw label letter size factorMore... |
| `LabelParentDisplay[get, set]` | `unsafeNXOpen.Drawings.ViewDetailLabelBuilder.LabelParentDisplayTypes` | Returns or sets the label parent displayMore... |
| `LabelPosition[get, set]` | `unsafeNXOpen.Drawings.LabelPositionTypes` | Returns or sets the label positionMore... |
| `LabelPrefix[get, set]` | `unsafe string` | Returns or sets the label prefixMore... |
| `LetterFormat[get, set]` | `unsafeNXOpen.Drawings.LetterFormatTypes` | Returns or sets the letter formatMore... |
| `ParentLabelPrefix[get, set]` | `unsafe string` | Returns or sets the parent label prefixMore... |
| `PrefixCharacterHeightFactor[get, set]` | `unsafe double` | Returns or sets the prefix character height factorMore... |
| `ReferenceToShow[get, set]` | `unsafeNXOpen.Drawings.ReferenceShowTypes` | Returns or sets the reference to showMore... |
| `ScaleCharacterHeightFactor[get, set]` | `unsafe double` | Returns or sets the scale character height factorMore... |
| `ScalePosition[get, set]` | `unsafeNXOpen.Drawings.ScalePositionTypes` | Returns or sets the scale positionMore... |
| `ScalePrefix[get, set]` | `unsafe string` | Returns or sets the scale prefixMore... |
| `ShowViewLabel[get, set]` | `unsafe bool` | Returns or sets the show view labelMore... |
| `ShowViewScale[get, set]` | `unsafe bool` | Returns or sets the show view scaleMore... |
| `TextGapFactor[get, set]` | `unsafe double` | Returns or sets the text gap factorMore... |
| `TextPlacement[get, set]` | `unsafeNXOpen.Drawings.ViewDetailLabelBuilder.LabelParentTextPlacement` | Returns or sets the text placementMore... |
| `ValueFormat[get, set]` | `unsafeNXOpen.Drawings.ScaleValueFormatTypes` | Returns or sets the value formatMore... |
| `ViewLabelOption[get, set]` | `unsafeNXOpen.Drawings.ViewLabelTypes` | Returns or sets the view label optionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewLabelBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50020.html

Represents aNXOpen.Drawings.ViewLabelBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetCustomizedViewLabelText()` | `unsafe string []` | Returns the customized view label textMore... |
| `SetCustomizedViewLabelText(string [] customizedText)` | `unsafe void` | Sets the customized view label textMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CustomizedViewLabel[get, set]` | `unsafe bool` | Returns or sets the customized view labelMore... |
| `IncludeParentheses[get, set]` | `unsafe bool` | Returns or sets the include parenthesesMore... |
| `IncludeRotationAngle[get, set]` | `unsafe bool` | Returns or sets the include rotation angleMore... |
| `IncludeRotationSymbol[get, set]` | `unsafe bool` | Returns or sets the include rotation symbolMore... |
| `LabelCharacterHeightFactor[get, set]` | `unsafe double` | Returns or sets the label character height factorMore... |
| `LabelPosition[get, set]` | `unsafeNXOpen.Drawings.LabelPositionTypes` | Returns or sets the label positionMore... |
| `LabelPrefix[get, set]` | `unsafe string` | Returns or sets the label prefixMore... |
| `LetterFormat[get, set]` | `unsafeNXOpen.Drawings.LetterFormatTypes` | Returns or sets the letter formatMore... |
| `PrefixCharacterHeightFactor[get, set]` | `unsafe double` | Returns or sets the prefix character height factorMore... |
| `ReferenceToShow[get, set]` | `unsafeNXOpen.Drawings.ReferenceShowTypes` | Returns or sets the reference to showMore... |
| `RotationSymbolType[get, set]` | `unsafeNXOpen.Drawings.RotationSymbolTypes` | Returns or sets the rotation symbol typeMore... |
| `ScaleCharacterHeightFactor[get, set]` | `unsafe double` | Returns or sets the scale character height factorMore... |
| `ScalePosition[get, set]` | `unsafeNXOpen.Drawings.ScalePositionTypes` | Returns or sets the scale positionMore... |
| `ScalePrefix[get, set]` | `unsafe string` | Returns or sets the scale prefixMore... |
| `ShowViewLabel[get, set]` | `unsafe bool` | Returns or sets the show view labelMore... |
| `ShowViewScale[get, set]` | `unsafe bool` | Returns or sets the show view scaleMore... |
| `ValueFormat[get, set]` | `unsafeNXOpen.Drawings.ScaleValueFormatTypes` | Returns or sets the value formatMore... |
| `ViewLabelOption[get, set]` | `unsafeNXOpen.Drawings.ViewLabelTypes` | Returns or sets the view label optionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewOrientationBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50024.html

Represents a ViewOrientationBuilder

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
| `OrientationType[get, set]` | `unsafeNXOpen.Drawings.ViewOrientationBuilder.Orientation` | Returns or sets the orientation typeMore... |
| `SelectView[get]` | `unsafeNXOpen.SelectView` | Returns the select viewMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewPlacementBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50028.html

Represents aNXOpen.Drawings.ViewPlacementBuilder

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
| `AlignmentMethod[get, set]` | `unsafeNXOpen.Drawings.ViewPlacementBuilder.Method` | Returns or sets the alignment methodMore... |
| `AlignmentOption[get, set]` | `unsafeNXOpen.Drawings.ViewPlacementBuilder.Option` | Returns or sets the alignment option used to indicate what points in the views to align.More... |
| `AlignmentPoint[get]` | `unsafeNXOpen.SelectTaggedObject` | Returns the point to align to.More... |
| `AlignmentVector[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the vector to align along.More... |
| `AlignmentView[get]` | `unsafeNXOpen.Drawings.SelectDraftingView` | Returns the view to align to.More... |
| `Associative[get, set]` | `unsafe bool` | Returns or sets the flag used to create a persistent alignmentMore... |
| `CandidatePoint[get]` | `unsafeNXOpen.SelectTaggedObject` | Returns the point to align in the view being edited.More... |
| `LockOffset[get, set]` | `unsafe bool` | Returns or sets the lock offset flag.More... |
| `Offset[get, set]` | `unsafe double` | Returns or sets the offset.More... |
| `Placement[get]` | `unsafeNXOpen.SelectNXObject` | Returns the placement location.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewProjectedArrowSettingsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50032.html

Represents aNXOpen.Drawings.ViewProjectedArrowSettingsBuilder

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
| `ArrowHeadAngle[get, set]` | `unsafe double` | Returns or sets the arrow head angleMore... |
| `ArrowHeadLength[get, set]` | `unsafe double` | Returns or sets the arrow head lengthMore... |
| `ArrowHeadStyle[get, set]` | `unsafeNXOpen.Drawings.ViewProjectedArrowSettingsBuilder.DimensionsStyleType` | Returns or sets the arrow head styleMore... |
| `ArrowLineDistanceToGeometry[get, set]` | `unsafe double` | Returns or sets the arrow line distance to geometryMore... |
| `ArrowLineLength[get, set]` | `unsafe double` | Returns or sets the arrow line lengthMore... |
| `DisplayLabel[get, set]` | `unsafeNXOpen.Drawings.ViewProjectedArrowSettingsBuilder.DispalyLabelType` | Returns or sets the display labelMore... |
| `LineColorFontWidth[get]` | `unsafeNXOpen.LineColorFontWidthBuilder` | Returns the line color font width0More... |
| `SizeFactor[get, set]` | `unsafe double` | Returns or sets the size factorMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewProjectedLabelBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50036.html

Represents aNXOpen.Drawings.ViewProjectedLabelBuilder


---

## NXOpen.Drawings.ViewProjectedViewSettingsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50040.html

Represents aNXOpen.Drawings.ViewProjectedViewSettingsBuilder

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
| `DisplayArrowOnParentView[get, set]` | `unsafeNXOpen.Drawings.ViewProjectedViewSettingsBuilder.DisplayArrowOnParentViewType` | Returns or sets the display arrow on parent viewMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewProjectionBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50044.html

Represents aNXOpen.Drawings.ViewProjectionBuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CurvePoints[get]` | `unsafeNXOpen.Section` | Returns the curve and pointsMore... |
| `CurveTypeEdges[get, set]` | `unsafeNXOpen.Drawings.ViewProjectionBuilder.CurveType` | Returns or sets the curve type edges in the setting groupMore... |
| `CurveTypePlane1[get, set]` | `unsafeNXOpen.Drawings.ViewProjectionBuilder.CurveType` | Returns or sets the curve type plane 1 in the setting groupMore... |
| `CurveTypePlane2[get, set]` | `unsafeNXOpen.Drawings.ViewProjectionBuilder.CurveType` | Returns or sets the curve type plane 2 in the setting group , if the type is set to one plane, the second plane information is ignoredMore... |
| `FromView[get, set]` | `unsafeNXOpen.View` | Returns or sets the from viewMore... |
| `Plane1[get]` | `unsafeNXOpen.Drawings.ViewProjectionPlaneBuilder` | Returns the plane 1More... |
| `Plane2[get]` | `unsafeNXOpen.Drawings.ViewProjectionPlaneBuilder` | Returns the plane 2, if the type is set to one plane, the second plane information is ignoredMore... |
| `ToViews[get]` | `unsafeNXOpen.Drawings.SelectDraftingViewList` | Returns the to viewsMore... |
| `Type[get, set]` | `unsafeNXOpen.Drawings.ViewProjectionBuilder.Types` | Returns or sets the type of the view projectionMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewProjectionPlaneBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50048.html

Represents the View Projection Plane (Drawings

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
| `Axis[get, set]` | `unsafeNXOpen.Axis` | Returns or sets the axis, define the vector and the point from which to infer the planeMore... |
| `DepthValue[get]` | `unsafeNXOpen.Expression` | Returns the depth valueMore... |
| `PlaneOption[get, set]` | `unsafeNXOpen.Drawings.ViewProjectionPlaneBuilder.PlaneOptions` | Returns or sets the plane option, decide how to get the planeMore... |
| `View[get]` | `unsafeNXOpen.Drawings.SelectDraftingView` | Returns the select view.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewScaleBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50052.html

Represents the View Scale (Drawings

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
| `Denominator[get, set]` | `unsafe double` | Returns or sets the scale denominatorMore... |
| `Expression[get, set]` | `unsafeNXOpen.Expression` | Returns or sets the scale expressionMore... |
| `Numerator[get, set]` | `unsafe double` | Returns or sets the scale numeratorMore... |
| `ScaleType[get, set]` | `unsafeNXOpen.Drawings.ViewScaleBuilder.Type` | Returns or sets the scale typeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewSectionLabelBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50056.html

Represents aNXOpen.Drawings.ViewSectionLabelBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetCustomizedViewLabelText()` | `unsafe string []` | Returns the customized view label textMore... |
| `SetCustomizedViewLabelText(string [] customizedText)` | `unsafe void` | Sets the customized view label textMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CustomizedViewLabel[get, set]` | `unsafe bool` | Returns or sets the customized view labelMore... |
| `IncludeParentheses[get, set]` | `unsafe bool` | Returns or sets the include parenthesesMore... |
| `IncludeRotationAngle[get, set]` | `unsafe bool` | Returns or sets the include rotation angleMore... |
| `IncludeRotationSymbol[get, set]` | `unsafe bool` | Returns or sets the include rotation symbolMore... |
| `LabelCharacterHeightFactor[get, set]` | `unsafe double` | Returns or sets the label character height factorMore... |
| `LabelPosition[get, set]` | `unsafeNXOpen.Drawings.LabelPositionTypes` | Returns or sets the label positionMore... |
| `LabelPrefix[get, set]` | `unsafe string` | Returns or sets the label prefixMore... |
| `LetterFormat[get, set]` | `unsafeNXOpen.Drawings.LetterFormatTypes` | Returns or sets the letter formatMore... |
| `PrefixCharacterHeightFactor[get, set]` | `unsafe double` | Returns or sets the prefix character height factorMore... |
| `ReferenceToShow[get, set]` | `unsafeNXOpen.Drawings.ReferenceShowTypes` | Returns or sets the reference to showMore... |
| `RotationSymbolType[get, set]` | `unsafeNXOpen.Drawings.RotationSymbolTypes` | Returns or sets the rotation symbol typeMore... |
| `ScaleCharacterHeightFactor[get, set]` | `unsafe double` | Returns or sets the scale character height factorMore... |
| `ScalePosition[get, set]` | `unsafeNXOpen.Drawings.ScalePositionTypes` | Returns or sets the scale positionMore... |
| `ScalePrefix[get, set]` | `unsafe string` | Returns or sets the scale prefixMore... |
| `ShowViewLabel[get, set]` | `unsafe bool` | Returns or sets the show view labelMore... |
| `ShowViewScale[get, set]` | `unsafe bool` | Returns or sets the show view scaleMore... |
| `ValueFormat[get, set]` | `unsafeNXOpen.Drawings.ScaleValueFormatTypes` | Returns or sets the section vw label scale value formatMore... |
| `ViewLabelOption[get, set]` | `unsafeNXOpen.Drawings.ViewLabelTypes` | Returns or sets the view label optionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewSectionLineBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50060.html

Represents aNXOpen.Drawings.ViewSectionLineBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `InheritSettingsFromCustomerDefault()` | `unsafe void` | Inherit Settings From Customer DefaultMore... |
| `InheritSettingsFromPreferences()` | `unsafe void` | Inherit Settings From PreferenceMore... |
| `InheritSettingsFromSelectedObjects(NXOpen.NXObjectselectedObject)` | `unsafe void` | Inherit Settings From Selected ObjectsMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `ArrowheadAngle[get, set]` | `unsafe double` | Returns or sets the included angle for the arrowheadMore... |
| `ArrowheadLength[get, set]` | `unsafe double` | Returns or sets the arrowhead lengthMore... |
| `ArrowLength[get, set]` | `unsafe double` | Returns or sets the arrow lengthMore... |
| `BendAndEndSegmentWidthFactor[get, set]` | `unsafe double` | Returns or sets the section line bend and end segment width factorMore... |
| `BorderToArrowDistance[get, set]` | `unsafe double` | Returns or sets the border to arrow distanceMore... |
| `Display[get, set]` | `unsafe bool` | Returns or sets the displayMore... |
| `DisplayLettersOnBends[get, set]` | `unsafe bool` | Returns or sets the display letters on bendsMore... |
| `DisplayRotationLetter[get, set]` | `unsafe bool` | Returns or sets the display rotation letterMore... |
| `Gap[get, set]` | `unsafe double` | Returns or sets the gapMore... |
| `LabelLocation[get, set]` | `unsafeNXOpen.Drawings.ViewSectionLineBuilder.LocationType` | Returns or sets the label locationMore... |
| `LineColorFontWidth[get]` | `unsafeNXOpen.LineColorFontWidthBuilder` | Returns the line color font widthMore... |
| `LineLength[get, set]` | `unsafe double` | Returns or sets the length of the end of the ESKD section lineMore... |
| `Overhang[get, set]` | `unsafe double` | Returns or sets the stub lengthMore... |
| `SelectRotationLetter[get]` | `unsafeNXOpen.SelectTaggedObject` | Returns the selected objected should be note type only which is the desired location of the rotation point of the section line specifiedMore... |
| `ShowSectionLine[get, set]` | `unsafeNXOpen.Drawings.ViewSectionLineBuilder.ShowSectionLineType` | Returns or sets the value to show section line with or without viewMore... |
| `Style[get, set]` | `unsafeNXOpen.Drawings.ViewSectionLineBuilder.StyleType` | Returns or sets the section line arrowhead styleMore... |
| `TypeStandard[get, set]` | `unsafeNXOpen.Drawings.ViewSectionLineBuilder.DisplayType` | Returns or sets the section line symbol displayMore... |
| `UseLineLength[get, set]` | `unsafe bool` | Returns or sets the use line length in case of ESKD section lineMore... |
| `UseOffset[get, set]` | `unsafe bool` | Returns or sets the use offsetMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewSettingsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50064.html

Represents aDrawings.ViewSettingsBuilder

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
| `AddSheetName[get, set]` | `unsafe bool` | Returns or sets the add sheet nameMore... |
| `AddSheetNumber[get, set]` | `unsafe bool` | Returns or sets the add sheet numberMore... |
| `ApplyCrosshatchToSectionView[get, set]` | `unsafe bool` | Returns or sets the apply crosshatch To section viewMore... |
| `ConvertAnnotation[get, set]` | `unsafe bool` | Returns or sets the convert annotationMore... |
| `Prefix[get, set]` | `unsafe string` | Returns or sets the prefix stringMore... |
| `RenderingStyle[get, set]` | `unsafeNXOpen.Drawings.ViewSettingsBuilder.RenderingStyleEnum` | Returns or sets the rendering styleMore... |
| `SectionGeometryTolerance[get, set]` | `unsafe double` | Returns or sets the section geometry toleranceMore... |
| `Separator[get, set]` | `unsafe string` | Returns or sets the separator stringMore... |
| `UseAssemblyCrosshatch[get, set]` | `unsafe bool` | Returns or sets the use assembly crosshatchMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50068.html

Represents set of style applicable to drafting views

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `BaseView[get]` | `NXOpen.Drawings.BaseViewStyle` | Returns object for doing View style settings applicable to BasedataMore... |
| `FlatPattern[get]` | `NXOpen.Drawings.FlatPatternViewStyle` | Returns object for doing View style settings applicable to Flat Pattern Views.More... |
| `General[get]` | `NXOpen.Drawings.GeneralViewStyle` | Returns object for doing View style settings applicable to GeneralMore... |
| `HiddenLines[get]` | `NXOpen.Drawings.HiddenLinesViewStyle` | Returns object for doing View style settings applicable to HiddenLinesMore... |
| `InheritPmi[get]` | `NXOpen.Drawings.InheritPmiViewStyle` | Returns object for doing View style settings applicable to InheritPmiMore... |
| `Orientation[get]` | `NXOpen.Drawings.OrientationViewStyle` | Returns object for doing View style settings applicable to OrientationMore... |
| `Perspective[get]` | `NXOpen.Drawings.PerspectiveViewStyle` | Returns object for doing View style settings applicable to PerspectiveMore... |
| `Projected[get]` | `NXOpen.Drawings.ProjectedViewStyle` | Returns object for doing View style settings applicable to ProjectedMore... |
| `Section[get]` | `NXOpen.Drawings.SectionViewStyle` | Returns object for doing View style settings applicable to SectionMore... |
| `Shading[get]` | `NXOpen.Drawings.ShadingViewStyle` | Returns object for doing View style settings applicable to ShadingMore... |
| `ShipbuildingLines[get]` | `NXOpen.Drawings.ShipbuildingLinesViewStyle` | Returns object for doing View style settings applicable to Ship Lines.More... |
| `ShipDraftingViewLines[get]` | `NXOpen.Drawings.ShipDraftingViewLinesViewStyle` | Returns object for doing View style settings applicable to Ship Drafting View Lines.More... |
| `ShipGeneralArrangementViewLines[get]` | `NXOpen.Drawings.ShipGeneralArrangementViewLinesViewStyle` | Returns object for doing View style settings applicable to Ship General Arrangement View Lines.More... |
| `SmoothEdges[get]` | `NXOpen.Drawings.SmoothEdgesViewStyle` | Returns object for doing View style settings applicable to SmoothEdgesMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `Threads[get]` | `NXOpen.Drawings.ThreadsViewStyle` | Returns object for doing View style settings applicable to ThreadsMore... |
| `TraceLines[get]` | `NXOpen.Drawings.TraceLinesViewStyle` | Returns object for doing View style settings applicable to TraceLinesMore... |
| `VirtualIntersections[get]` | `NXOpen.Drawings.VirtualIntersectionsViewStyle` | Returns object for doing View style settings applicable to VirtualIntersectionsMore... |
| `VisibleLines[get]` | `NXOpen.Drawings.VisibleLinesViewStyle` | Returns object for doing View style settings applicable to VisibleLinesMore... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleAECViewLinesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50072.html

Represents aNXOpen.Drawings.ViewStyleAECViewLinesBuilderbuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `HiddenColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the hidden color on the AEC Structure LinesMore... |
| `HiddenFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the hidden font on the AEC Structure LinesMore... |
| `HiddenWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the hidden width on the AEC Structure LinesMore... |
| `ShowMultipleBodies[get, set]` | `unsafe bool` | Returns or sets the flag to indicate whether or not to show multiple bodies.More... |
| `VisibleColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the visible color on the AEC Structure LinesMore... |
| `VisibleFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the visible font on the AEC Structure LinesMore... |
| `VisibleWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the visible width on the AEC Structure LinesMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleAECViewLinesBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50076.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.Drawings.ViewStyleAECViewLinesBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.Drawings.ViewStyleAECViewLinesBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.Drawings.ViewStyleAECViewLinesBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.Drawings.ViewStyleAECViewLinesBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.Drawings.ViewStyleAECViewLinesBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.Drawings.ViewStyleAECViewLinesBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.Drawings.ViewStyleAECViewLinesBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.Drawings.ViewStyleAECViewLinesBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.Drawings.ViewStyleAECViewLinesBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.Drawings.ViewStyleAECViewLinesBuilderobject1,NXOpen.Drawings.ViewStyleAECViewLinesBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.Drawings.ViewStyleBaseBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50080.html

Represents the BASE tab on the View Style Dialog (Drawings

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
| `Arrangement[get]` | `unsafeNXOpen.Assemblies.ArrangementsBuilder` | Returns the arrangement on the BASE tab of the View Style DialogMore... |
| `ArrangementName[get, set]` | `unsafe string` | Returns or sets the arrangement name on the BASE tab of the View Style DialogMore... |
| `FacetedRepresentation[get, set]` | `unsafe bool` | Returns or sets the faceted representation toggle on the BASE tab of the View Style DialogMore... |
| `InheritClippingBoundary[get, set]` | `unsafe bool` | Returns or sets the inherit clipping boundary toggle on the BASE tab of the View Style DialogMore... |
| `Part[get, set]` | `unsafeNXOpen.Part` | Returns or sets the part on the BASE tab of the View Style DialogMore... |
| `PartName[get, set]` | `unsafe string` | Returns or sets the part name on the BASE tab of the View Style DialogMore... |
| `TransferAnnotation[get, set]` | `unsafe bool` | Returns or sets the transfer annotation toggle on the BASE tab of the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50084.html

Represents the View Style Builder (Drawings

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateAECViewLinesBuilder()` | `unsafeNXOpen.Drawings.ViewStyleAECViewLinesBuilder` | Creates aNXOpen.Drawings.ViewStyleAECViewLinesBuilderMore... |
| `FindAECViewLinesBuilderByName(string structureName)` | `unsafeNXOpen.Drawings.ViewStyleAECViewLinesBuilder` | Gets theNXOpen.Drawings.ViewStyleAECViewLinesBuilderwith the given view plan and display nameMore... |
| `FindShipDraftingViewLinesBuilderByName(string featureName, string featureSubName)` | `unsafeNXOpen.Drawings.ShipDraftingViewLinesBuilder` | Gets theNXOpen.Drawings.ShipDraftingViewLinesBuilderwith the given FeatureName and FeatureSubNameMore... |
| `FindShipGeneralArrangementViewLinesBuilderByName(string viewPlan, string displayName)` | `unsafeNXOpen.Drawings.ShipGeneralArrangementViewLinesBuilder` | Gets theNXOpen.Drawings.ShipGeneralArrangementViewLinesBuilderwith the given view plan and display nameMore... |
| `GetAllViewStyleFPCallouts()` | `unsafeNXOpen.Drawings.ViewStyleFPCalloutsBuilder[]` | Retrieves all the Callouts on the Flat Pattern Tab on the View Style DialogMore... |
| `GetAllViewStyleFPCurves()` | `unsafeNXOpen.Drawings.ViewStyleFPCurvesBuilder[]` | Retrieves all the Curves on the Flat Pattern Tab on the View Style DialogMore... |
| `GetViewStyleFPCallout(string type)` | `unsafeNXOpen.Drawings.ViewStyleFPCalloutsBuilder` | Retrieves a specified Callout on the Flat Pattern Tab on the View Style DialogMore... |
| `GetViewStyleFPCalloutConfig()` | `unsafeNXOpen.Drawings.ViewStyleFPCalloutConfigBuilder` | Retrieves the callout configuration on the Flat Pattern Tab on the View Style DialogMore... |
| `GetViewStyleFPCurve(NXOpen.SheetMetal.FlatPatternSettings.FlatPatternObjectTypetype)` | `unsafeNXOpen.Drawings.ViewStyleFPCurvesBuilder` | Retrieves a specified Curve on the Flat Pattern Tab on the View Style DialogMore... |
| `InheritSettingsFromCustomerDefault()` | `unsafe void` | Inherit Settings From Customer DefaultMore... |
| `InheritSettingsFromPreferences()` | `unsafe void` | Inherit Settings From PreferenceMore... |
| `InheritSettingsFromSelectedObjects(NXOpen.NXObjectselectedObject)` | `unsafe void` | Inherit Settings From Selected ObjectsMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `ProjectedViewOrientation[get]` | `unsafeNXOpen.Drawings.ProjectedViewOrientationBuilder` | Returns the projected view orientation builderMore... |
| `SecondaryComponents[get]` | `unsafeNXOpen.Drawings.ViewStyleSecondaryComponentsBuilder` | Returns the secondary components style builder of the view style builder which represents the secondary geometry tab on the View Style DialogMore... |
| `ViewCommonViewLabel[get]` | `unsafeNXOpen.Drawings.ViewCommonViewLabelBuilder` | Returns the view common label builderMore... |
| `ViewProjectedArrowSettings[get]` | `unsafeNXOpen.Drawings.ViewProjectedArrowSettingsBuilder` | Returns the projected Arrow Settings builderMore... |
| `ViewProjectedViewSettings[get]` | `unsafeNXOpen.Drawings.ViewProjectedViewSettingsBuilder` | Returns the projected View Settings builderMore... |
| `ViewSectionLineStyleBuilder[get]` | `unsafeNXOpen.Drawings.ViewSectionLineBuilder` | Returns the view section line builderMore... |
| `ViewStyleAecViewLinesList[get]` | `unsafeNXOpen.Drawings.ViewStyleAECViewLinesBuilderList` | Returns the AEC View lines builder of the view style builder which represents the AEC drafting view lines on the View Style DialogMore... |
| `ViewStyleBase[get]` | `unsafeNXOpen.Drawings.ViewStyleBaseBuilder` | Returns the Base style builder of the view style builder which represents the base tab on the View Style DialogMore... |
| `ViewStyleDetail[get]` | `unsafeNXOpen.Drawings.ViewStyleDetailBuilder` | Returns the Detail style builder of the view style builder which represents the detail tab on the View Style DialogMore... |
| `ViewStyleGeneral[get]` | `unsafeNXOpen.Drawings.ViewStyleGeneralBuilder` | Returns the General style builder of the view style builder which represents the general tab on the View Style DialogMore... |
| `ViewStyleHiddenLines[get]` | `unsafeNXOpen.Drawings.ViewStyleHiddenLinesBuilder` | Returns the Hidden Lines style builder of the view style builder which represents the hidden lines tab on the View Style DialogMore... |
| `ViewStyleInheritPmi[get]` | `unsafeNXOpen.Drawings.ViewStyleInheritPmiBuilder` | Returns the Inherit PMI style builder of the view style builder which represents the inherit PMI tab on the View Style DialogMore... |
| `ViewStyleOrientation[get]` | `unsafeNXOpen.Drawings.ViewStyleOrientationBuilder` | Returns the Orientation style builder of the view style builder which represents the orientation tab on the View Style DialogMore... |
| `ViewStylePerspective[get]` | `unsafeNXOpen.Drawings.ViewStylePerspectiveBuilder` | Returns the Perspective style builder of the view style builder which represents the perspective tab on the View Style DialogMore... |
| `ViewStyleProjected[get]` | `unsafeNXOpen.Drawings.ViewStyleProjectedBuilder` | Returns the projected style builder of the view style builder which represents the projected tab on the View Style DialogMore... |
| `ViewStyleSection[get]` | `unsafeNXOpen.Drawings.ViewStyleSectionBuilder` | Returns the Section style builder of the view style builder which represents the section tab on the View Style DialogMore... |
| `ViewStyleSectionConstraints[get]` | `unsafeNXOpen.Drawings.ViewStyleSectionConstraintsBuilder` | Returns the Section Constraints style builder of the view style builder which represents the section constraints tab on the View Style DialogMore... |
| `ViewStyleShading[get]` | `unsafeNXOpen.Drawings.ViewStyleShadingBuilder` | Returns the Shading style builder of the view style builder which represents the shading tab on the View Style DialogMore... |
| `ViewStyleShipDraftingViewLinesList[get]` | `unsafeNXOpen.Drawings.ShipDraftingViewLinesBuilderList` | Returns the Ship Drafting View lines builder of the view style builder which represents the ship drafting view lines on the View Style DialogMore... |
| `ViewStyleShipGeneralArrangementViewLinesList[get]` | `unsafeNXOpen.Drawings.ShipGeneralArrangementViewLinesBuilderList` | Returns the Ship General Arrangement View lines builder of the view style builder which represents the ship drafting view lines on the View Style DialogMore... |
| `ViewStyleSingleLineList[get]` | `unsafeNXOpen.Drawings.ViewStyleShipbuildingLinesBuilderList` | Returns the Ship building lines style builder of the view style builder which represents the ship building lines tab on the View Style DialogMore... |
| `ViewStyleSmoothEdges[get]` | `unsafeNXOpen.Drawings.ViewStyleSmoothEdgesBuilder` | Returns the Smooth Edges style builder of the view style builder which represents the smooth edges tab on the View Style DialogMore... |
| `ViewStyleThreads[get]` | `unsafeNXOpen.Drawings.ViewStyleThreadsBuilder` | Returns the Threads style builder of the view style builder which represents the threads tab on the View Style DialogMore... |
| `ViewStyleTraceLines[get]` | `unsafeNXOpen.Drawings.ViewStyleTraceLinesBuilder` | Returns the Trace lines style builder of the view style builder which represents the trace lines tab on the View Style DialogMore... |
| `ViewStyleVirtualIntersections[get]` | `unsafeNXOpen.Drawings.ViewStyleVirtualIntersectionsBuilder` | Returns the Virtual intersections style builder of the view style builder which represents the virtual intersections tab on the View Style DialogMore... |
| `ViewStyleVisibleLines[get]` | `unsafeNXOpen.Drawings.ViewStyleVisibleLinesBuilder` | Returns the Visible lines style builder of the view style builder which represents the visible lines tab on the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleDetailBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50088.html

Represents the DETAIL tab on the View Style Dialog (Drawings

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
| `Align[get, set]` | `unsafe bool` | Returns or sets the align toggle on the DETAIL tab of the View Style DialogMore... |
| `Circular[get, set]` | `unsafe bool` | Returns or sets the circular toggle on the DETAIL tab of the View Style DialogMore... |
| `ClipViewBoundary[get, set]` | `unsafe bool` | Returns or sets the clip boundary toggle on the DETAIL tab of the View Style DialogMore... |
| `CreateIndependentDetailView[get, set]` | `unsafe bool` | Returns or sets the create independent detail view toggle on the DETAIL tab of the View Style DialogMore... |
| `Offset[get, set]` | `unsafe bool` | Returns or sets the offset toggle on the DETAIL tab of the View Style DialogMore... |
| `Orient[get, set]` | `unsafe bool` | Returns or sets the orient toggle on the DETAIL tab of the View Style DialogMore... |
| `Scale[get, set]` | `unsafe bool` | Returns or sets the scale toggle on the DETAIL tab of the View Style DialogMore... |
| `Sheet[get, set]` | `unsafe bool` | Returns or sets the sheet toggle on the DETAIL tab of the View Style DialogMore... |
| `ViewBoundaryColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the view boundary color on the DETAIL tab of the View Style DialogMore... |
| `ViewBoundaryFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the view boundary font on the DETAIL tab of the View Style DialogMore... |
| `ViewBoundaryWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the view boundary width on the DETAIL tab of the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleFPCalloutConfigBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50092.html

Represents the Callout section of the Flat Pattern tab on the View Style Dialog (Drawings

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetContents(string calloutType)` | `unsafe string []` | Returns the contents for a Flat Pattern callout typeMore... |
| `GetOrientationType()` | `unsafeNXOpen.Drawings.ViewStyleFPCalloutConfigBuilder.OrientationType` | Returns the orientation type for flat pattern callouts.More... |
| `SetContents(string calloutType, string [] contents)` | `unsafe void` | Sets the contents for a Flat Pattern callout typeMore... |
| `SetOrientationType(NXOpen.Drawings.ViewStyleFPCalloutConfigBuilder.OrientationTypeorientation)` | `unsafe void` | Sets the orientation type for flat pattern callouts.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |


---

## NXOpen.Drawings.ViewStyleFPCalloutsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50096.html

Represents the Callout section of the Flat Pattern tab on the View Style Dialog (Drawings

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
| `State[get, set]` | `unsafe bool` | Returns or sets the state toggle on the Callout section of the Flat Pattern tab of the View Style DialogMore... |
| `Type[get]` | `unsafe string` | Returns the type of Flat Pattern CalloutMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleFPCurvesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50100.html

Represents the Curve section of the Flat Pattern tab on the View Style Dialog (Drawings

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
| `Color[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the color on the Curve section of the Flat Pattern tab of the View Style DialogMore... |
| `Font[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the font on the Curve section of the Flat Pattern tab of the View Style DialogMore... |
| `State[get, set]` | `unsafe bool` | Returns or sets the state toggle on the Curve section of the Flat Pattern tab of the View Style DialogMore... |
| `Type[get]` | `unsafeNXOpen.SheetMetal.FlatPatternSettings.FlatPatternObjectType` | Returns the type of Flat Pattern CurveMore... |
| `Width[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the width on the Curve section of the Flat Pattern tab of the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleFrameBarBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50104.html

Represents view style frame bar builder (Drawings

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
| `Horizontal[get, set]` | `unsafe bool` | Returns or sets the status of horizontal framebar.More... |
| `HorizontalDistance[get, set]` | `unsafe double` | Returns or sets the horizontal distanceMore... |
| `HorizontalPosition[get, set]` | `unsafeNXOpen.Annotations.BaseFrameBarBuilder.HorizontalPositionType` | Returns or sets the horizontal positionMore... |
| `Vertical[get, set]` | `unsafe bool` | Returns or sets the status of vertical framebar.More... |
| `VerticalDistance[get, set]` | `unsafe double` | Returns or sets the vertical distanceMore... |
| `VerticalPosition[get, set]` | `unsafeNXOpen.Annotations.BaseFrameBarBuilder.VerticalPositionType` | Returns or sets the vertical positionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleGeneralBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50108.html

Represents view style general builder (Drawings

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetRenderSet()` | `unsafeNXOpen.Drawings.RenderSet[]` | Gets the render sets on the GENERAL tab of the View Style DialogMore... |
| `SetRenderSet(NXOpen.Drawings.RenderSet[] renderSets)` | `unsafe void` | Sets the render sets on the GENERAL tab of the View Style DialogMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AngleDecimalPointCharacter[get, set]` | `unsafeNXOpen.Preferences.DecimalPointCharacter` | Returns or sets the decimal point character to use for view angle display.More... |
| `AngleFormat[get, set]` | `unsafeNXOpen.Preferences.AngleFormat` | Returns or sets the format to use for view angle display.More... |
| `AnglePrecision[get, set]` | `unsafe int` | Returns or sets the precision to use for view angle display.More... |
| `AngleSetting[get]` | `unsafeNXOpen.Drawings.AssociativeAngleBuilder` | Returns the angle value on the GENERAL tab of the View Style DialogMore... |
| `AngleShowLeadingZeros[get, set]` | `unsafe bool` | Returns or sets the status of leading zeros display in view angle.More... |
| `AngleShowTrailingZeros[get, set]` | `unsafe bool` | Returns or sets the status of trailing zeros display in view angle.More... |
| `AngleValue[get, set]` | `unsafe double` | Returns or sets the angle value on the GENERAL tab of the View Style DialogMore... |
| `AutomaticAnchorPoint[get, set]` | `unsafe bool` | Returns or sets the automatic anchor point toggle on the GENERAL tab of the View Style DialogMore... |
| `AutomaticUpdate[get, set]` | `unsafe bool` | Returns or sets the automatic update toggle on the GENERAL tab of the View Style DialogMore... |
| `BoundaryStatus[get, set]` | `unsafe bool` | Returns or sets the boundary status toggle on the GENERAL tab of the View Style DialogMore... |
| `Centerlines[get, set]` | `unsafe bool` | Returns or sets the centerlines toggle on the GENERAL tab of the View Style DialogMore... |
| `DisplayId[get, set]` | `unsafeNXOpen.Preferences.GeneralDisplayIdOption` | Returns or sets the display identifier option on the GENERAL tab of the View Style Dialog, it controls whether the orientation or the name of the view is displayed in the graphic windowMore... |
| `ExtractedEdges[get, set]` | `unsafeNXOpen.Preferences.GeneralExtractedEdgesOption` | Returns or sets the extracted edges option on the GENERAL tab of the View Style DialogMore... |
| `FramebarHorizontal[get, set]` | `unsafe bool` | Returns or sets the horizontal framebar toggle on the GENERAL tab of the View Style DialogMore... |
| `FramebarVertical[get, set]` | `unsafe bool` | Returns or sets the vertical framebar toggle on the GENERAL tab of the View Style DialogMore... |
| `LegacyView[get, set]` | `unsafe bool` | Returns or sets the leagcy view toggle on the GENERAL tab of the View Style DialogMore... |
| `LightweightView[get, set]` | `unsafe bool` | Returns or sets the view representation enum on the GENERAL tab of the View Style DialogMore... |
| `LockmethodView[get, set]` | `unsafeNXOpen.Preferences.GeneralViewLockmethodOption` | Returns or sets the lock method setting on the Configuration tab of the View Style DialogMore... |
| `Reference[get, set]` | `unsafe bool` | Returns or sets the reference toggle on the GENERAL tab of the View Style DialogMore... |
| `Scale[get]` | `unsafeNXOpen.Drawings.ViewScaleBuilder` | Returns the scale definition on the GENERAL tab of the View Style DialogMore... |
| `ScaleLabel[get, set]` | `unsafe bool` | Returns or sets the scale label toggle on the GENERAL tab of the View Style DialogMore... |
| `Silhouettes[get, set]` | `unsafe bool` | Returns or sets the silhouettes toggle on the GENERAL tab of the View Style DialogMore... |
| `SnapshotView[get, set]` | `unsafe bool` | Returns or sets the snapshot toggle on the GENERAL tab of the View Style DialogMore... |
| `Tolerance[get, set]` | `unsafeNXOpen.Preferences.GeneralToleranceOption` | Returns or sets the tolerance option on the GENERAL tab of the View Style DialogMore... |
| `ToleranceValue[get, set]` | `unsafe double` | Returns or sets the tolerance value on the GENERAL tab of the View Style DialogMore... |
| `UVGrid[get, set]` | `unsafe bool` | Returns or sets the uvgrid toggle on the GENERAL tab of the View Style DialogMore... |
| `ViewLabel[get, set]` | `unsafe bool` | Returns or sets the view label toggle on the GENERAL tab of the View Style DialogMore... |
| `ViewQuality[get, set]` | `unsafeNXOpen.Preferences.GeneralViewQualityOption` | Returns or sets the view quality option on the GENERAL tab of the View Style DialogMore... |
| `ViewRepresentation[get, set]` | `unsafeNXOpen.Preferences.GeneralViewRepresentationOption` | Returns or sets the view representation option on the GENERAL tab of the View Style DialogMore... |
| `ViewStyleFrameBar[get]` | `unsafeNXOpen.Drawings.ViewStyleFrameBarBuilder` | Returns the frame bar builderMore... |
| `WireframeColorSource[get, set]` | `unsafeNXOpen.Preferences.GeneralWireframeColorSourceOption` | Returns or sets the wireframe color source option on the GENERAL tab of the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleHiddenLinesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50112.html

Represents the HIDDEN LINES tab on the View Style Dialog (Drawings

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
| `Color[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the color on the HIDDEN LINES tab of the View Style DialogMore... |
| `EdgesHiddenByEdges[get, set]` | `unsafe bool` | Returns or sets the edges hidden by edges toggle on the HIDDEN LINES tab of the View Style DialogMore... |
| `Font[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the font on the HIDDEN LINES tab of the View Style DialogMore... |
| `HiddenLine[get, set]` | `unsafe bool` | Returns or sets the hidden line toggle on the HIDDEN LINES tab of the View Style DialogMore... |
| `IncludeModelCurves[get, set]` | `unsafe bool` | Returns or sets the include model curves toggle on the HIDDEN LINES tab of the View Style DialogMore... |
| `IncludeModelCurvesOption[get, set]` | `unsafeNXOpen.Preferences.IncludeModelCurvesOption` | Returns or sets the include model curves option on the HIDDEN LINES tab of the View Style DialogMore... |
| `InterferingSolids[get, set]` | `unsafeNXOpen.Preferences.HiddenLineInterferingSolidsOption` | Returns or sets the interfering solids toggle on the HIDDEN LINES tab of the View Style DialogMore... |
| `ReferenceEdgesOnly[get, set]` | `unsafe bool` | Returns or sets the reference edges only toggle on the HIDDEN LINES tab of the View Style DialogMore... |
| `SelfHidden[get, set]` | `unsafe bool` | Returns or sets the self hidden toggle on the HIDDEN LINES tab of the View Style DialogMore... |
| `SmallFeature[get, set]` | `unsafeNXOpen.Preferences.HiddenLineSmallFeatureOption` | Returns or sets the small feature option on the HIDDEN LINES tab of the View Style DialogMore... |
| `SmallFeaturesTolerance[get, set]` | `unsafe double` | Returns or sets the small features tolerance on the HIDDEN LINES tab of the View Style DialogMore... |
| `Width[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the width on the HIDDEN LINES tab of the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleInheritPmiBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50116.html

Represents the INHERIT PMI tab on the View Style Dialog (Drawings

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
| `CrosshatchPmiLwsv[get, set]` | `unsafe bool` | Returns or sets the cross-hatch setting for the current inherited PMI Lightweight Section ViewMore... |
| `Gdt[get, set]` | `unsafeNXOpen.Preferences.GdtOption` | Returns or sets the gdt option on the INHERIT PMI tab of the View Style DialogMore... |
| `Pmi[get, set]` | `unsafeNXOpen.Preferences.PmiOption` | Returns or sets the pmi option on the INHERIT PMI tab of the View Style DialogMore... |
| `PmiFromRevolved[get, set]` | `unsafe bool` | Returns or sets the 'Show PMI Dimensions from Revolved Sketches' toggle on the INHERIT PMI tab of the View Style DialogMore... |
| `PmiToDrawing[get, set]` | `unsafe bool` | Returns or sets the 'pmi to drawing' toggle on the INHERIT PMI tab of the View Style DialogMore... |
| `PmiTypeMask[get, set]` | `unsafe int` | Returns or sets the type mask on the INHERIT PMI tab of the View Style DialogMore... |
| `ReferenceSetBehavior[get, set]` | `unsafeNXOpen.Preferences.ReferenceSetBehavior` | Returns or sets the reference set optionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleOrientationBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50120.html

Represents the ORIENTATION tab on the View Style Dialog (Drawings

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
| `HingeLine[get]` | `unsafeNXOpen.Drawings.HingeLineBuilder` | Returns the view hinge line definition on the ORIENTATION tab of the View Style DialogMore... |
| `Ovt[get]` | `unsafeNXOpen.Drawings.OvtBuilder` | Returns the view orientation definition on the ORIENTATION tab of the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStylePerspectiveBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50124.html

Represents the PERSPECTIVE tab on the View Style Dialog (Drawings

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
| `BackClip[get, set]` | `unsafe bool` | Returns or sets the back clip toggle on the PERSPECTIVE tab of the View Style DialogMore... |
| `BackClipDistance[get, set]` | `unsafe double` | Returns or sets the back clip distance data on the PERSPECTIVE tab of the View Style DialogMore... |
| `FrontClip[get, set]` | `unsafe bool` | Returns or sets the front clip toggle on the PERSPECTIVE tab of the View Style DialogMore... |
| `FrontClipDistance[get, set]` | `unsafe double` | Returns or sets the front clip distance data on the PERSPECTIVE tab of the View Style DialogMore... |
| `Perspective[get, set]` | `unsafe bool` | Returns or sets the perspective toggle on the PERSPECTIVE tab of the View Style DialogMore... |
| `PerspectiveDistance[get, set]` | `unsafe double` | Returns or sets the perspective distance data on the PERSPECTIVE tab of the View Style DialogMore... |
| `ViewOrigin[get, set]` | `unsafeNXOpen.Point3d` | Returns or sets the perspective view origin on the PERSPECTIVE tab of the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleProjectedBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50128.html

Represents the PROJECTED tab on the View Style Dialog (Drawings

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
| `Align[get, set]` | `unsafe bool` | Returns or sets the projected view style align toggle on the PROJECTED tab of the View Style DialogMore... |
| `Gdt[get, set]` | `unsafe bool` | Returns or sets the projected view style gdt toggle on the PROJECTED tab of the View Style DialogMore... |
| `Offset[get, set]` | `unsafe bool` | Returns or sets the projected view style offset toggle on the PROJECTED tab of the View Style DialogMore... |
| `Orient[get, set]` | `unsafe bool` | Returns or sets the projected view style orient toggle on the PROJECTED tab of the View Style DialogMore... |
| `Scale[get, set]` | `unsafe bool` | Returns or sets the projected view style scale toggle on the PROJECTED tab of the View Style DialogMore... |
| `Sheet[get, set]` | `unsafe bool` | Returns or sets the projected view style sheet toggle on the PROJECTED tab of the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleSecondaryComponentsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50132.html

Represents the Secondary Geometry tab on the View Style Dialog (Drawings

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
| `PrimaryHiddenBySecondaryCFW[get]` | `unsafeNXOpen.Drawings.VisibleAndHiddenLinesColorFontWidthBuilder` | Returns the visible and hidden lines color, font, and width of primary geometry that is hidden by secondary geometry.More... |
| `ProcessPrimaryHiddenBySecondary[get, set]` | `unsafe bool` | Returns or sets the Primary Geometry Hidden by Secondary Geometry toggle on Secondary Geometry tab of View Style Dialog.More... |
| `ProcessSecondaryComponents[get, set]` | `unsafe bool` | Returns or sets the Secondary Geometry toggle on Secondary Geometry tab of View Style Dialog.More... |
| `ProcessSecondaryHiddenByPrimary[get, set]` | `unsafe bool` | Returns or sets the Secondary Geometry Hidden by Primary Geometry toggle on Secondary Geometry tab of View Style Dialog.More... |
| `SecondaryComponentsCFW[get]` | `unsafeNXOpen.Drawings.VisibleAndHiddenLinesColorFontWidthBuilder` | Returns the visible and hidden lines color, font, and width of secondary geometry.More... |
| `SecondaryHiddenByPrimaryCFW[get]` | `unsafeNXOpen.Drawings.VisibleAndHiddenLinesColorFontWidthBuilder` | Returns the visible and hidden lines color, font, and width of secondary geometry that is hidden by primary geometry.More... |
| `ShowSmoothEdges[get, set]` | `unsafe bool` | Returns or sets the Show Smooth Edges toggle on Secondary Geometry tab of View Style Dialog.More... |
| `ShowVirtualIntersections[get, set]` | `unsafe bool` | Returns or sets the Show Virtual Intersections toggle on Secondary Geometry tab of View Style Dialog.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleSectionBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50136.html

Represents the SECTION tab on the View Style Dialog (Drawings

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
| `AdjacencyToleranceData[get, set]` | `unsafe double` | Returns or sets the adjacency tolerance on the SECTION tab of the View Style DialogMore... |
| `AssemblyTolerance[get, set]` | `unsafe bool` | Returns or sets the assembly tolerance toggle on the SECTION tab of the View Style DialogMore... |
| `Background[get, set]` | `unsafe bool` | Returns or sets the background toggle on the SECTION tab of the View Style DialogMore... |
| `Bendlines[get, set]` | `unsafe bool` | Returns or sets the bendlines toggle on the SECTION tab of the View Style DialogMore... |
| `Crosshatch[get, set]` | `unsafe bool` | Returns or sets the crosshatch toggle on the SECTION tab of the View Style DialogMore... |
| `DisplaySectionLine[get, set]` | `unsafe bool` | Returns or sets the display section line toggle on the SECTION tab of the View Style DialogMore... |
| `Foreground[get, set]` | `unsafe bool` | Returns or sets the foreground toggle on the SECTION tab of the View Style DialogMore... |
| `HiddenLineHatching[get, set]` | `unsafe bool` | Returns or sets the hidden line hatching toggle on the SECTION tab of the View Style DialogMore... |
| `RestrictCrosshatchAngle[get, set]` | `unsafe bool` | Returns or sets the restrict crosshatch angle toggle on the SECTION tab of the View Style DialogMore... |
| `SheetBodies[get, set]` | `unsafe bool` | Returns or sets the sheet bodies toggle on the SECTION tab of the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleSectionConstraintsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50140.html

Represents the SECTION CONSTRAINTS tab on the View Style Dialog (Drawings

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
| `Align[get, set]` | `unsafe bool` | Returns or sets the align toggle on the SECTION CONSTRAINTS tab of the View Style DialogMore... |
| `Offset[get, set]` | `unsafe bool` | Returns or sets the offset toggle on the SECTION CONSTRAINTS tab of the View Style DialogMore... |
| `Orient[get, set]` | `unsafe bool` | Returns or sets the orient toggle on the SECTION CONSTRAINTS tab of the View Style DialogMore... |
| `Scale[get, set]` | `unsafe bool` | Returns or sets the scale toggle on the SECTION CONSTRAINTS tab of the View Style DialogMore... |
| `Sheet[get, set]` | `unsafe bool` | Returns or sets the sheet toggle on the SECTION CONSTRAINTS tab of the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleShadingBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50144.html

Represents the SHADING tab on the View Style Dialog (Drawings

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
| `AngleTolerance[get, set]` | `unsafe double` | Returns or sets the angle tolerance data on the SHADING tab of the View Style DialogMore... |
| `CutFaceColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the cut face color on the SHADING tab of the View Style DialogMore... |
| `EdgeTolerance[get, set]` | `unsafe double` | Returns or sets the edge tolerance data on the SHADING tab of the View Style DialogMore... |
| `FaceTolerance[get, set]` | `unsafe double` | Returns or sets the face tolerance data on the SHADING tab of the View Style DialogMore... |
| `HiddenWireframeColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the hidden wireframe color on the SHADING tab of the View Style DialogMore... |
| `RenderingStyle[get, set]` | `unsafeNXOpen.Preferences.ShadingRenderingStyleOption` | Returns or sets the rendering style option on the SHADING tab of the View Style DialogMore... |
| `ShadeTolerance[get, set]` | `unsafeNXOpen.Preferences.ShadingToleranceOption` | Returns or sets the shade tolerance option on the SHADING tab of the View Style DialogMore... |
| `ShininessScale[get, set]` | `unsafe double` | Returns or sets the shininess scale data on the SHADING tab of the View Style DialogMore... |
| `TwoSidedLight[get, set]` | `unsafe bool` | Returns or sets the two sided light toggle on the SHADING tab of the View Style DialogMore... |
| `VisibleWireframeColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the visible wireframe color on the SHADING tab of the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleShipbuildingLinesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50148.html

Represents the Shipbuilding LINES tab on the View Style Dialog (Drawings

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
| `HiddenColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the hidden line color on the SHIPBUILDING LINES tab of the View Style DialogMore... |
| `HiddenFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the hidden line font on the SHIPBUILDING LINES tab of the View Style DialogMore... |
| `HiddenWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the hidden line width on the SHIPBUILDING LINES tab of the View Style DialogMore... |
| `SingleLineRepresentation[get, set]` | `unsafe bool` | Returns or sets the Shipbuilding line toggle on the SHIPBUILDING LINES tab of the View Style DialogMore... |
| `VisibleColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the visible line color on the SHIPBUILDING LINES tab of the View Style DialogMore... |
| `VisibleFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the visible line font on the SHIPBUILDING LINES tab of the View Style DialogMore... |
| `VisibleWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the visible line width on the SHIPBUILDING LINES tab of the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleShipbuildingLinesBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50152.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.Drawings.ViewStyleShipbuildingLinesBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.Drawings.ViewStyleShipbuildingLinesBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.Drawings.ViewStyleShipbuildingLinesBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.Drawings.ViewStyleShipbuildingLinesBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.Drawings.ViewStyleShipbuildingLinesBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.Drawings.ViewStyleShipbuildingLinesBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.Drawings.ViewStyleShipbuildingLinesBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.Drawings.ViewStyleShipbuildingLinesBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.Drawings.ViewStyleShipbuildingLinesBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.Drawings.ViewStyleShipbuildingLinesBuilderobject1,NXOpen.Drawings.ViewStyleShipbuildingLinesBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.Drawings.ViewStyleSmoothEdgesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50156.html

Represents the SMOOTH EDGES tab on the View Style Dialog (Drawings

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
| `Color[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the color on the SMOOTH EDGES tab of the View Style DialogMore... |
| `EndGaps[get, set]` | `unsafe bool` | Returns or sets the end gaps toggle on the SMOOTH EDGES tab of the View Style DialogMore... |
| `EndGapsDistance[get, set]` | `unsafe double` | Returns or sets the end gaps data on the SMOOTH EDGES tab of the View Style DialogMore... |
| `Font[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the font on the SMOOTH EDGES tab of the View Style DialogMore... |
| `SmoothEdge[get, set]` | `unsafe bool` | Returns or sets the smooth edge toggle on the SMOOTH EDGES tab of the View Style DialogMore... |
| `Tolerance[get, set]` | `unsafe bool` | Returns or sets the angle tolerance toggle on the SMOOTH EDGES tab of the View Style DialogMore... |
| `ToleranceValue[get, set]` | `unsafe double` | Returns or sets the angle tolerance data on the SMOOTH EDGES tab of the View Style DialogMore... |
| `Width[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the width on the SMOOTH EDGES tab of the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleThreadsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50160.html

Represents the THREADS tab on the View Style Dialog (Drawings

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
| `MinimumPitchFieldData[get, set]` | `unsafe double` | Returns or sets the minimum pitch field on the THREADS tab of the View Style DialogMore... |
| `OverrideVisibleThreadColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the override thread color on the THREADS tab of the View Style DialogMore... |
| `StandardData[get, set]` | `unsafe int` | Returns or sets the standard option data on the THREADS tab of the View Style DialogMore... |
| `TrueHiddenLine[get, set]` | `unsafe bool` | Returns or sets the true hidden line toggle on the THREADS tab of the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleTraceLinesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50164.html

Represents the TRACE LINES tab on the View Style Dialog (Drawings

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
| `CreateGaps[get, set]` | `unsafe bool` | Returns or sets the create gaps toggle on the TRACE LINES tab of the View Style DialogMore... |
| `GapSize[get, set]` | `unsafe double` | Returns or sets the gap size on the TRACE LINES tab of the View Style DialogMore... |
| `HiddenColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the hidden color on the TRACE LINES tab of the View Style DialogMore... |
| `HiddenFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the hidden font on the TRACE LINES tab of the View Style DialogMore... |
| `HiddenWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the hidden width on the TRACE LINES tab of the View Style DialogMore... |
| `VisibleColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the visible color on the TRACE LINES tab of the View Style DialogMore... |
| `VisibleFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the visible font on the TRACE LINES tab of the View Style DialogMore... |
| `VisibleWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the visible width on the TRACE LINES tab of the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleVirtualIntersectionsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50168.html

Represents the VIRTUAL INTERSECTIONS tab on the View Style Dialog (Drawings

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
| `AdjacentBlends[get, set]` | `unsafe bool` | Returns or sets the adjacent blends toggle on the VIRTUAL INTERSECTIONS tab of the View Style DialogMore... |
| `Color[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the color on the VIRTUAL INTERSECTIONS tab of the View Style DialogMore... |
| `EndGaps[get, set]` | `unsafe bool` | Returns or sets the end gaps toggle on the VIRTUAL INTERSECTIONS tab of the View Style DialogMore... |
| `EndGapsDistance[get, set]` | `unsafe double` | Returns or sets the end gaps data on the VIRTUAL INTERSECTIONS tab of the View Style DialogMore... |
| `Font[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the font on the VIRTUAL INTERSECTIONS tab of the View Style DialogMore... |
| `VirtualIntersections[get, set]` | `unsafe bool` | Returns or sets the virtual intersections toggle on the VIRTUAL INTERSECTIONS tab of the View Style DialogMore... |
| `Width[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the width on the VIRTUAL INTERSECTIONS tab of the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewStyleVisibleLinesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50172.html

Represents the VISIBLE LINES tab on the View Style Dialog (Drawings

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
| `VisibleColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the visible color on the VISIBLE LINES tab of the View Style DialogMore... |
| `VisibleFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the visible font on the VISIBLE LINES tab of the View Style DialogMore... |
| `VisibleWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the visible width on the VISIBLE LINES tab of the View Style DialogMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewWorkflowBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50176.html

Represents aNXOpen.Drawings.ViewWorkflowBuilder

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
| `ActiveSketchViewColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the active views border colorMore... |
| `AssociativeAlignment[get, set]` | `unsafe bool` | Returns or sets the associative alignment enable alignement between viewsMore... |
| `BorderColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the border color of viewMore... |
| `CursorTracking[get, set]` | `unsafe bool` | Returns or sets the cursor tracking enable XC/YC coordinates in dynamic input boxes when placing a view on a drawingMore... |
| `DisplayBorders[get, set]` | `unsafe bool` | Returns or sets the display view borders on the the drawingMore... |
| `EnableSmoothEdgesForLWView[get, set]` | `unsafe bool` | Returns or sets the setting is not needed anymore because the smooth edges are correctly supported now for smart lightweight views.More... |
| `FaceDisplay[get, set]` | `unsafeNXOpen.Drawings.ViewWorkflowBuilder.Display` | Returns or sets the face display provides options in an extracted edge view that are available for selectionMore... |
| `HandlingBodies[get, set]` | `unsafeNXOpen.Drawings.ViewWorkflowBuilder.Handlingbodies` | Returns or sets the handling bodies provides option for update view without lightweight dataMore... |
| `HandlingBodiesTypes[get, set]` | `unsafeNXOpen.Drawings.ViewWorkflowBuilder.HandlingBodiesType` | Returns or sets the handling bodies provides option for update view without lightweight dataMore... |
| `LargeAssemblyStepThreshold[get, set]` | `unsafe int` | Returns or sets the large assembly step threshold option establishes the minimum number of components (loaded or unloaded) a part may have to be considered a large assembly.More... |
| `LoadComponentsOnDemand[get, set]` | `unsafe bool` | Returns or sets whether or not to load the components on demand for smart lightweight viewsMore... |
| `OnLegacyViewUpdate[get, set]` | `unsafe bool` | Returns or sets the on legacy view update determines whether or not components should be loaded as needed to update lightweight viewsMore... |
| `OnViewSelection[get, set]` | `unsafe bool` | Returns or sets the on view selection determines whether or not components should be loaded as needed for selection in lightweight views for accurate dimensioningMore... |
| `PreviewStyle[get, set]` | `unsafeNXOpen.Drawings.ViewWorkflowBuilder.Style` | Returns or sets the style of the preview when adding a view to the drawingMore... |
| `SelectGeometryProjectedAsArcs[get, set]` | `unsafeNXOpen.Drawings.ViewWorkflowBuilder.Splarcs` | Returns or sets the Select Geometry Projected as Arcs provides options for selection of SPLARCs entity for centerlines and AnnotationsMore... |
| `ShowFacetEdges[get, set]` | `unsafe bool` | Returns or sets the show facet edges determines whether or not facet edges will be shown on shaded faces when displaying a drawing sheetMore... |
| `UseLineAntialiasing[get, set]` | `unsafe bool` | Returns or sets the use line antialiasingMore... |
| `UseTranslucency[get, set]` | `unsafe bool` | Returns or sets the use translucency determines translucency settings for faces when displaying a drawing sheetMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.ViewingDirectionArrow

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50012.html

This class represents a Drafting Viewing Direction Arrow


---

## NXOpen.Drawings.ViewingDirectionArrowLabel

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50016.html

This class represents a Drafting Viewing Direction Arrow Label


---

## NXOpen.Drawings.VirtualIntersectionsViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50180.html

Represents set of Virtual Intersections View Style Preferences applicable to drafting views

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AdjacentBlends[get, set]` | `unsafe bool` | Returns or sets the status of adjacent blends.More... |
| `AdjacentBlendsColor[get, set]` | `unsafe int` | Returns or sets the color of adjacent blends.More... |
| `AdjacentBlendsEndGaps[get, set]` | `unsafe bool` | Returns or sets the status of adjacent blends end gaps.More... |
| `AdjacentBlendsEndGapsData[get, set]` | `unsafe double` | Returns or sets the value of adjacent blends end gaps.More... |
| `AdjacentBlendsFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the font of adjacent blends.More... |
| `AdjacentBlendsWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the width of adjacent blends.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `VirtualIntersection[get, set]` | `unsafe bool` | Returns or sets the status of virtual intersection.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.VisibleAndHiddenLinesColorFontWidthBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50184.html

Represent aNXOpen.Drawings.VisibleAndHiddenLinesColorFontWidthBuilder

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
| `HiddenCFW[get]` | `unsafeNXOpen.LineColorFontWidthBuilder` | Returns the hidden lines color, font, and width.More... |
| `VisibleCFW[get]` | `unsafeNXOpen.LineColorFontWidthBuilder` | Returns the visible lines color, font, and width.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.VisibleLinesViewStyle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50188.html

Represents set of Visible Lines View Style Preferences applicable to drafting views

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `VisibleColor[get, set]` | `unsafe int` | Returns or sets the visible color.More... |
| `VisibleFont[get, set]` | `unsafeNXOpen.Preferences.Font` | Returns or sets the visible font.More... |
| `VisibleWidth[get, set]` | `unsafeNXOpen.Preferences.Width` | Returns or sets the visible width.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.Drawings.VisualDrawingComparePrefsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a50192.html

This class gets and sets components of Visual Overlay in Drafting Preferences

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
| `CompareMethodType[get, set]` | `unsafeNXOpen.Drawings.VisualDrawingComparePrefsBuilder.VisualDrawingComparePrefsMethodType` | Returns or sets the compare method typeMore... |
| `OverlayColor[get, set]` | `unsafeNXOpen.NXColor` | Returns or sets the overlay colorMore... |
| `OverlayDataToUse[get, set]` | `unsafeNXOpen.Drawings.VisualDrawingComparePrefsBuilder.VisualDrawingComparePrefsOverlayDataToUse` | Returns or sets the overlay data to useMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---
