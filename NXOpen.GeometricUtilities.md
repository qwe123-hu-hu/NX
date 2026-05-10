# NXOpen.GeometricUtilities API 参考

> 共 236 个类 | C# (NXOpen .NET)

---

## 目录

- [NXOpen.GeometricUtilities.AlignmentMethodBuilder](#nxopen-geometricutilities-alignmentmethodbuilder)
- [NXOpen.GeometricUtilities.AlongPathPattern](#nxopen-geometricutilities-alongpathpattern)
- [NXOpen.GeometricUtilities.AlongSpineBuilder](#nxopen-geometricutilities-alongspinebuilder)
- [NXOpen.GeometricUtilities.AnchorLocatorBuilder](#nxopen-geometricutilities-anchorlocatorbuilder)
- [NXOpen.GeometricUtilities.AngularLimits](#nxopen-geometricutilities-angularlimits)
- [NXOpen.GeometricUtilities.AngularPatternSpacing](#nxopen-geometricutilities-angularpatternspacing)
- [NXOpen.GeometricUtilities.BetweenLocationsData](#nxopen-geometricutilities-betweenlocationsdata)
- [NXOpen.GeometricUtilities.BlendLimitsData](#nxopen-geometricutilities-blendlimitsdata)
- [NXOpen.GeometricUtilities.BlendSetbackBuilder](#nxopen-geometricutilities-blendsetbackbuilder)
- [NXOpen.GeometricUtilities.BlendSetbackBuilderList](#nxopen-geometricutilities-blendsetbackbuilderlist)
- [NXOpen.GeometricUtilities.BlendStopshortBuilder](#nxopen-geometricutilities-blendstopshortbuilder)
- [NXOpen.GeometricUtilities.BlendStopshortBuilderCollection](#nxopen-geometricutilities-blendstopshortbuildercollection)
- [NXOpen.GeometricUtilities.BooleanOperation](#nxopen-geometricutilities-booleanoperation)
- [NXOpen.GeometricUtilities.BooleanRegionSelect](#nxopen-geometricutilities-booleanregionselect)
- [NXOpen.GeometricUtilities.BooleanToolBuilder](#nxopen-geometricutilities-booleantoolbuilder)
- [NXOpen.GeometricUtilities.BoundaryDefinitionBuilder](#nxopen-geometricutilities-boundarydefinitionbuilder)
- [NXOpen.GeometricUtilities.BoundaryDefinitionBuilderList](#nxopen-geometricutilities-boundarydefinitionbuilderlist)
- [NXOpen.GeometricUtilities.BoundingObjectBuilder](#nxopen-geometricutilities-boundingobjectbuilder)
- [NXOpen.GeometricUtilities.BoundingObjectBuilderList](#nxopen-geometricutilities-boundingobjectbuilderlist)
- [NXOpen.GeometricUtilities.BridgeCurveConnectivity](#nxopen-geometricutilities-bridgecurveconnectivity)
- [NXOpen.GeometricUtilities.CAMDataPrepManager](#nxopen-geometricutilities-camdataprepmanager)
- [NXOpen.GeometricUtilities.ChamferEdgeChainSetBuilder](#nxopen-geometricutilities-chamferedgechainsetbuilder)
- [NXOpen.GeometricUtilities.ChamferEdgeChainSetBuilderList](#nxopen-geometricutilities-chamferedgechainsetbuilderlist)
- [NXOpen.GeometricUtilities.ChamferEdgeManager](#nxopen-geometricutilities-chamferedgemanager)
- [NXOpen.GeometricUtilities.CircularCrossSection](#nxopen-geometricutilities-circularcrosssection)
- [NXOpen.GeometricUtilities.CircularFrameBuilder](#nxopen-geometricutilities-circularframebuilder)
- [NXOpen.GeometricUtilities.CircularPattern](#nxopen-geometricutilities-circularpattern)
- [NXOpen.GeometricUtilities.CollectorPairBuilder](#nxopen-geometricutilities-collectorpairbuilder)
- [NXOpen.GeometricUtilities.CollectorPairBuilderList](#nxopen-geometricutilities-collectorpairbuilderlist)
- [NXOpen.GeometricUtilities.CollectorPairListBuilder](#nxopen-geometricutilities-collectorpairlistbuilder)
- [NXOpen.GeometricUtilities.ColorCodedRegionBuilder](#nxopen-geometricutilities-colorcodedregionbuilder)
- [NXOpen.GeometricUtilities.CombOptionsBuilder](#nxopen-geometricutilities-comboptionsbuilder)
- [NXOpen.GeometricUtilities.ConicCrossSection](#nxopen-geometricutilities-coniccrosssection)
- [NXOpen.GeometricUtilities.Continuity](#nxopen-geometricutilities-continuity)
- [NXOpen.GeometricUtilities.ControlPoleManagerData](#nxopen-geometricutilities-controlpolemanagerdata)
- [NXOpen.GeometricUtilities.ConvertFeatureGroupsToModulesBuilder](#nxopen-geometricutilities-convertfeaturegroupstomodulesbuilder)
- [NXOpen.GeometricUtilities.CrayonSelectionData](#nxopen-geometricutilities-crayonselectiondata)
- [NXOpen.GeometricUtilities.CrayonSelectionData.EntityData](#nxopen-geometricutilities-crayonselectiondata-entitydata)
- [NXOpen.GeometricUtilities.CurveAlignedItemBuilder](#nxopen-geometricutilities-curvealigneditembuilder)
- [NXOpen.GeometricUtilities.CurveAlignedItemBuilderList](#nxopen-geometricutilities-curvealigneditembuilderlist)
- [NXOpen.GeometricUtilities.CurveAlignedListBuilder](#nxopen-geometricutilities-curvealignedlistbuilder)
- [NXOpen.GeometricUtilities.CurveExtendData](#nxopen-geometricutilities-curveextenddata)
- [NXOpen.GeometricUtilities.CurveExtensionBuilder](#nxopen-geometricutilities-curveextensionbuilder)
- [NXOpen.GeometricUtilities.CurveFitData](#nxopen-geometricutilities-curvefitdata)
- [NXOpen.GeometricUtilities.CurveFitJoin](#nxopen-geometricutilities-curvefitjoin)
- [NXOpen.GeometricUtilities.CurveFitOptions](#nxopen-geometricutilities-curvefitoptions)
- [NXOpen.GeometricUtilities.CurveLengthBuilder](#nxopen-geometricutilities-curvelengthbuilder)
- [NXOpen.GeometricUtilities.CurveLengthData](#nxopen-geometricutilities-curvelengthdata)
- [NXOpen.GeometricUtilities.CurveLimitsData](#nxopen-geometricutilities-curvelimitsdata)
- [NXOpen.GeometricUtilities.CurveLocation](#nxopen-geometricutilities-curvelocation)
- [NXOpen.GeometricUtilities.CurveOptions](#nxopen-geometricutilities-curveoptions)
- [NXOpen.GeometricUtilities.CurveRangeBuilder](#nxopen-geometricutilities-curverangebuilder)
- [NXOpen.GeometricUtilities.CurveSettings](#nxopen-geometricutilities-curvesettings)
- [NXOpen.GeometricUtilities.CurveShapingBuilder](#nxopen-geometricutilities-curveshapingbuilder)
- [NXOpen.GeometricUtilities.DegreesAndSegmentsOrPatchesBuilder](#nxopen-geometricutilities-degreesandsegmentsorpatchesbuilder)
- [NXOpen.GeometricUtilities.DepthSkewBuilder](#nxopen-geometricutilities-depthskewbuilder)
- [NXOpen.GeometricUtilities.DesignMeshBody](#nxopen-geometricutilities-designmeshbody)
- [NXOpen.GeometricUtilities.DesignMeshEdge](#nxopen-geometricutilities-designmeshedge)
- [NXOpen.GeometricUtilities.DesignMeshFace](#nxopen-geometricutilities-designmeshface)
- [NXOpen.GeometricUtilities.DesignMeshVertex](#nxopen-geometricutilities-designmeshvertex)
- [NXOpen.GeometricUtilities.DisplayResolutionBuilder](#nxopen-geometricutilities-displayresolutionbuilder)
- [NXOpen.GeometricUtilities.DistancePatternSpacing](#nxopen-geometricutilities-distancepatternspacing)
- [NXOpen.GeometricUtilities.DraftPointData](#nxopen-geometricutilities-draftpointdata)
- [NXOpen.GeometricUtilities.DraftVariableAngleData](#nxopen-geometricutilities-draftvariableangledata)
- [NXOpen.GeometricUtilities.EndHoleData](#nxopen-geometricutilities-endholedata)
- [NXOpen.GeometricUtilities.EntityUsageInfo](#nxopen-geometricutilities-entityusageinfo)
- [NXOpen.GeometricUtilities.EntityUsageInfoList](#nxopen-geometricutilities-entityusageinfolist)
- [NXOpen.GeometricUtilities.Extend](#nxopen-geometricutilities-extend)
- [NXOpen.GeometricUtilities.ExtrudeRevolveToolBuilder](#nxopen-geometricutilities-extruderevolvetoolbuilder)
- [NXOpen.GeometricUtilities.FaceChangeOverflowBehavior](#nxopen-geometricutilities-facechangeoverflowbehavior)
- [NXOpen.GeometricUtilities.FacePairingBuilder](#nxopen-geometricutilities-facepairingbuilder)
- [NXOpen.GeometricUtilities.FacePlaneSelectionBuilder](#nxopen-geometricutilities-faceplaneselectionbuilder)
- [NXOpen.GeometricUtilities.FacePlaneSelectionBuilderCollection](#nxopen-geometricutilities-faceplaneselectionbuildercollection)
- [NXOpen.GeometricUtilities.FacePlaneToolBuilder](#nxopen-geometricutilities-faceplanetoolbuilder)
- [NXOpen.GeometricUtilities.FaceSetData](#nxopen-geometricutilities-facesetdata)
- [NXOpen.GeometricUtilities.FaceSetDataCollection](#nxopen-geometricutilities-facesetdatacollection)
- [NXOpen.GeometricUtilities.FaceSetOffset](#nxopen-geometricutilities-facesetoffset)
- [NXOpen.GeometricUtilities.FaceSetOffsetCollection](#nxopen-geometricutilities-facesetoffsetcollection)
- [NXOpen.GeometricUtilities.FaceSetOffsetList](#nxopen-geometricutilities-facesetoffsetlist)
- [NXOpen.GeometricUtilities.FeatureOffset](#nxopen-geometricutilities-featureoffset)
- [NXOpen.GeometricUtilities.FeatureOptions](#nxopen-geometricutilities-featureoptions)
- [NXOpen.GeometricUtilities.FlowDirection](#nxopen-geometricutilities-flowdirection)
- [NXOpen.GeometricUtilities.FrameOnPathBuilder](#nxopen-geometricutilities-frameonpathbuilder)
- [NXOpen.GeometricUtilities.FtmFixedCurvesBuilder](#nxopen-geometricutilities-ftmfixedcurvesbuilder)
- [NXOpen.GeometricUtilities.FtmFixedCurvesBuilderList](#nxopen-geometricutilities-ftmfixedcurvesbuilderlist)
- [NXOpen.GeometricUtilities.FtmTransformCurvesBuilder](#nxopen-geometricutilities-ftmtransformcurvesbuilder)
- [NXOpen.GeometricUtilities.FtmTransformCurvesBuilderList](#nxopen-geometricutilities-ftmtransformcurvesbuilderlist)
- [NXOpen.GeometricUtilities.FtmTransformPointsBuilder](#nxopen-geometricutilities-ftmtransformpointsbuilder)
- [NXOpen.GeometricUtilities.FtmTransformPointsBuilderList](#nxopen-geometricutilities-ftmtransformpointsbuilderlist)
- [NXOpen.GeometricUtilities.GeneralPattern](#nxopen-geometricutilities-generalpattern)
- [NXOpen.GeometricUtilities.GeometryLocationData](#nxopen-geometricutilities-geometrylocationdata)
- [NXOpen.GeometricUtilities.GeometryLocationDataCollection](#nxopen-geometricutilities-geometrylocationdatacollection)
- [NXOpen.GeometricUtilities.HelixPattern](#nxopen-geometricutilities-helixpattern)
- [NXOpen.GeometricUtilities.HorizontalReference](#nxopen-geometricutilities-horizontalreference)
- [NXOpen.GeometricUtilities.IComponentBuilder](#nxopen-geometricutilities-icomponentbuilder)
- [NXOpen.GeometricUtilities.InstanceEditedExpressionItem](#nxopen-geometricutilities-instanceeditedexpressionitem)
- [NXOpen.GeometricUtilities.InstanceEditedExpressionItemList](#nxopen-geometricutilities-instanceeditedexpressionitemlist)
- [NXOpen.GeometricUtilities.InstanceEditedExpressionsList](#nxopen-geometricutilities-instanceeditedexpressionslist)
- [NXOpen.GeometricUtilities.InteractiveSectionBuilder](#nxopen-geometricutilities-interactivesectionbuilder)
- [NXOpen.GeometricUtilities.LatticeItemBuilder](#nxopen-geometricutilities-latticeitembuilder)
- [NXOpen.GeometricUtilities.LatticeItemBuilderList](#nxopen-geometricutilities-latticeitembuilderlist)
- [NXOpen.GeometricUtilities.LatticeItemListBuilder](#nxopen-geometricutilities-latticeitemlistbuilder)
- [NXOpen.GeometricUtilities.LawBuilder](#nxopen-geometricutilities-lawbuilder)
- [NXOpen.GeometricUtilities.LengthLimitPointBuilder](#nxopen-geometricutilities-lengthlimitpointbuilder)
- [NXOpen.GeometricUtilities.LengthLimitsListBuilder](#nxopen-geometricutilities-lengthlimitslistbuilder)
- [NXOpen.GeometricUtilities.Limits](#nxopen-geometricutilities-limits)
- [NXOpen.GeometricUtilities.LinearLimits](#nxopen-geometricutilities-linearlimits)
- [NXOpen.GeometricUtilities.LocalUntrimBuilder](#nxopen-geometricutilities-localuntrimbuilder)
- [NXOpen.GeometricUtilities.LocalUntrimManager](#nxopen-geometricutilities-localuntrimmanager)
- [NXOpen.GeometricUtilities.MatchSurfaceBuilder](#nxopen-geometricutilities-matchsurfacebuilder)
- [NXOpen.GeometricUtilities.MiddleHoleData](#nxopen-geometricutilities-middleholedata)
- [NXOpen.GeometricUtilities.MirrorPattern](#nxopen-geometricutilities-mirrorpattern)
- [NXOpen.GeometricUtilities.ModlAlongCurveAngle](#nxopen-geometricutilities-modlalongcurveangle)
- [NXOpen.GeometricUtilities.ModlDistanceAngle](#nxopen-geometricutilities-modldistanceangle)
- [NXOpen.GeometricUtilities.ModlMotion](#nxopen-geometricutilities-modlmotion)
- [NXOpen.GeometricUtilities.MovePoleBuilder](#nxopen-geometricutilities-movepolebuilder)
- [NXOpen.GeometricUtilities.MultiDraft](#nxopen-geometricutilities-multidraft)
- [NXOpen.GeometricUtilities.MultiTransitionLawBuilder](#nxopen-geometricutilities-multitransitionlawbuilder)
- [NXOpen.GeometricUtilities.NestModuleBuilder](#nxopen-geometricutilities-nestmodulebuilder)
- [NXOpen.GeometricUtilities.NonInflectingLawBuilder](#nxopen-geometricutilities-noninflectinglawbuilder)
- [NXOpen.GeometricUtilities.OmnicadManager](#nxopen-geometricutilities-omnicadmanager)
- [NXOpen.GeometricUtilities.OnPathDimWithValueBuilder](#nxopen-geometricutilities-onpathdimwithvaluebuilder)
- [NXOpen.GeometricUtilities.OnPathDimensionBuilder](#nxopen-geometricutilities-onpathdimensionbuilder)
- [NXOpen.GeometricUtilities.OnPathDistancePatternSpacing](#nxopen-geometricutilities-onpathdistancepatternspacing)
- [NXOpen.GeometricUtilities.OrientXpressBuilder](#nxopen-geometricutilities-orientxpressbuilder)
- [NXOpen.GeometricUtilities.OrientationMethodBuilder](#nxopen-geometricutilities-orientationmethodbuilder)
- [NXOpen.GeometricUtilities.ParentEquivalencyMap](#nxopen-geometricutilities-parentequivalencymap)
- [NXOpen.GeometricUtilities.ParentEquivalencyMapList](#nxopen-geometricutilities-parentequivalencymaplist)
- [NXOpen.GeometricUtilities.PartModuleInputBuilder](#nxopen-geometricutilities-partmoduleinputbuilder)
- [NXOpen.GeometricUtilities.PartModuleOutputBuilder](#nxopen-geometricutilities-partmoduleoutputbuilder)
- [NXOpen.GeometricUtilities.PartModuleOutputBuilder1](#nxopen-geometricutilities-partmoduleoutputbuilder1)
- [NXOpen.GeometricUtilities.PartModuleReferencesBuilder](#nxopen-geometricutilities-partmodulereferencesbuilder)
- [NXOpen.GeometricUtilities.PartModuleRelationshipBuilder](#nxopen-geometricutilities-partmodulerelationshipbuilder)
- [NXOpen.GeometricUtilities.PathLimits](#nxopen-geometricutilities-pathlimits)
- [NXOpen.GeometricUtilities.PatternClocking](#nxopen-geometricutilities-patternclocking)
- [NXOpen.GeometricUtilities.PatternClockingBuilder](#nxopen-geometricutilities-patternclockingbuilder)
- [NXOpen.GeometricUtilities.PatternDefinition](#nxopen-geometricutilities-patterndefinition)
- [NXOpen.GeometricUtilities.PatternFill](#nxopen-geometricutilities-patternfill)
- [NXOpen.GeometricUtilities.PatternIncrementItem](#nxopen-geometricutilities-patternincrementitem)
- [NXOpen.GeometricUtilities.PatternIncrementItemList](#nxopen-geometricutilities-patternincrementitemlist)
- [NXOpen.GeometricUtilities.PatternIncrementsBuilder](#nxopen-geometricutilities-patternincrementsbuilder)
- [NXOpen.GeometricUtilities.PatternIncrementsList](#nxopen-geometricutilities-patternincrementslist)
- [NXOpen.GeometricUtilities.PatternInstanceEditBuilder](#nxopen-geometricutilities-patterninstanceeditbuilder)
- [NXOpen.GeometricUtilities.PatternOrientation](#nxopen-geometricutilities-patternorientation)
- [NXOpen.GeometricUtilities.PatternReferencePointServiceBuilder](#nxopen-geometricutilities-patternreferencepointservicebuilder)
- [NXOpen.GeometricUtilities.PatternSpacing](#nxopen-geometricutilities-patternspacing)
- [NXOpen.GeometricUtilities.PatternSpacingsList](#nxopen-geometricutilities-patternspacingslist)
- [NXOpen.GeometricUtilities.PatternSpacingsListItem](#nxopen-geometricutilities-patternspacingslistitem)
- [NXOpen.GeometricUtilities.PatternSpacingsListItemList](#nxopen-geometricutilities-patternspacingslistitemlist)
- [NXOpen.GeometricUtilities.PlayButtonsBuilder](#nxopen-geometricutilities-playbuttonsbuilder)
- [NXOpen.GeometricUtilities.PointFacePlaneSelectionBuilder](#nxopen-geometricutilities-pointfaceplaneselectionbuilder)
- [NXOpen.GeometricUtilities.PointFacePlaneSelectionBuilderList](#nxopen-geometricutilities-pointfaceplaneselectionbuilderlist)
- [NXOpen.GeometricUtilities.PointSetAlignmentBuilder](#nxopen-geometricutilities-pointsetalignmentbuilder)
- [NXOpen.GeometricUtilities.PointsFromFileBuilder](#nxopen-geometricutilities-pointsfromfilebuilder)
- [NXOpen.GeometricUtilities.PolygonPattern](#nxopen-geometricutilities-polygonpattern)
- [NXOpen.GeometricUtilities.PolygonPatternSpacing](#nxopen-geometricutilities-polygonpatternspacing)
- [NXOpen.GeometricUtilities.ProjectionOptions](#nxopen-geometricutilities-projectionoptions)
- [NXOpen.GeometricUtilities.QuadrilateralFrameBuilder](#nxopen-geometricutilities-quadrilateralframebuilder)
- [NXOpen.GeometricUtilities.Rebuild](#nxopen-geometricutilities-rebuild)
- [NXOpen.GeometricUtilities.RectangularFrameBuilder](#nxopen-geometricutilities-rectangularframebuilder)
- [NXOpen.GeometricUtilities.RectangularPattern](#nxopen-geometricutilities-rectangularpattern)
- [NXOpen.GeometricUtilities.ReduceSurfaceRadiusBuilder](#nxopen-geometricutilities-reducesurfaceradiusbuilder)
- [NXOpen.GeometricUtilities.ReduceSurfaceRadiusFaceGroupBuilder](#nxopen-geometricutilities-reducesurfaceradiusfacegroupbuilder)
- [NXOpen.GeometricUtilities.ReduceSurfaceRadiusFaceGroupBuilderList](#nxopen-geometricutilities-reducesurfaceradiusfacegroupbuilderlist)
- [NXOpen.GeometricUtilities.ReferencePattern](#nxopen-geometricutilities-referencepattern)
- [NXOpen.GeometricUtilities.RefitControlBuilder](#nxopen-geometricutilities-refitcontrolbuilder)
- [NXOpen.GeometricUtilities.RegionTracker](#nxopen-geometricutilities-regiontracker)
- [NXOpen.GeometricUtilities.RenameLinkedPartModulePartBuilder](#nxopen-geometricutilities-renamelinkedpartmodulepartbuilder)
- [NXOpen.GeometricUtilities.RenewFeatureBuilder](#nxopen-geometricutilities-renewfeaturebuilder)
- [NXOpen.GeometricUtilities.ReplAsstBuilder](#nxopen-geometricutilities-replasstbuilder)
- [NXOpen.GeometricUtilities.ReplaceManager](#nxopen-geometricutilities-replacemanager)
- [NXOpen.GeometricUtilities.ReplaceManualMatchBuilder](#nxopen-geometricutilities-replacemanualmatchbuilder)
- [NXOpen.GeometricUtilities.ReplaceMatchListItem](#nxopen-geometricutilities-replacematchlistitem)
- [NXOpen.GeometricUtilities.ReplaceMatchListItemList](#nxopen-geometricutilities-replacematchlistitemlist)
- [NXOpen.GeometricUtilities.RodItemBuilder](#nxopen-geometricutilities-roditembuilder)
- [NXOpen.GeometricUtilities.RodItemBuilderList](#nxopen-geometricutilities-roditembuilderlist)
- [NXOpen.GeometricUtilities.RodItemListBuilder](#nxopen-geometricutilities-roditemlistbuilder)
- [NXOpen.GeometricUtilities.RotationSetBuilder](#nxopen-geometricutilities-rotationsetbuilder)
- [NXOpen.GeometricUtilities.RotationSetBuilderList](#nxopen-geometricutilities-rotationsetbuilderlist)
- [NXOpen.GeometricUtilities.SShapedLawBuilder](#nxopen-geometricutilities-sshapedlawbuilder)
- [NXOpen.GeometricUtilities.SaveConstraintsBuilder](#nxopen-geometricutilities-saveconstraintsbuilder)
- [NXOpen.GeometricUtilities.ScalingMethodBuilder](#nxopen-geometricutilities-scalingmethodbuilder)
- [NXOpen.GeometricUtilities.ScalingSetBuilder](#nxopen-geometricutilities-scalingsetbuilder)
- [NXOpen.GeometricUtilities.ScalingSetBuilderList](#nxopen-geometricutilities-scalingsetbuilderlist)
- [NXOpen.GeometricUtilities.SecondarySectionData](#nxopen-geometricutilities-secondarysectiondata)
- [NXOpen.GeometricUtilities.SectionPlaneData](#nxopen-geometricutilities-sectionplanedata)
- [NXOpen.GeometricUtilities.SelectDividingObjectBuilder](#nxopen-geometricutilities-selectdividingobjectbuilder)
- [NXOpen.GeometricUtilities.SelectionList](#nxopen-geometricutilities-selectionlist)
- [NXOpen.GeometricUtilities.SelectionListList](#nxopen-geometricutilities-selectionlistlist)
- [NXOpen.GeometricUtilities.ShapeFrameBuilder](#nxopen-geometricutilities-shapeframebuilder)
- [NXOpen.GeometricUtilities.SimpleDraft](#nxopen-geometricutilities-simpledraft)
- [NXOpen.GeometricUtilities.SmartVolumeProfileBuilder](#nxopen-geometricutilities-smartvolumeprofilebuilder)
- [NXOpen.GeometricUtilities.SnipIntoPatchesBuilder](#nxopen-geometricutilities-snipintopatchesbuilder)
- [NXOpen.GeometricUtilities.SpineDefinitionBuilder](#nxopen-geometricutilities-spinedefinitionbuilder)
- [NXOpen.GeometricUtilities.SpinePlaneBuilder](#nxopen-geometricutilities-spineplanebuilder)
- [NXOpen.GeometricUtilities.SpinePlaneBuilderList](#nxopen-geometricutilities-spineplanebuilderlist)
- [NXOpen.GeometricUtilities.SpinePointData](#nxopen-geometricutilities-spinepointdata)
- [NXOpen.GeometricUtilities.SpinePointDataCollection](#nxopen-geometricutilities-spinepointdatacollection)
- [NXOpen.GeometricUtilities.SpiralPattern](#nxopen-geometricutilities-spiralpattern)
- [NXOpen.GeometricUtilities.SplineExtensionBuilder](#nxopen-geometricutilities-splineextensionbuilder)
- [NXOpen.GeometricUtilities.StartHoleData](#nxopen-geometricutilities-startholedata)
- [NXOpen.GeometricUtilities.StepOptionBehavior](#nxopen-geometricutilities-stepoptionbehavior)
- [NXOpen.GeometricUtilities.StrokeGestureData](#nxopen-geometricutilities-strokegesturedata)
- [NXOpen.GeometricUtilities.StrokeGestureData.Point](#nxopen-geometricutilities-strokegesturedata-point)
- [NXOpen.GeometricUtilities.StyledSweepDoubleOnPathDimBuilder](#nxopen-geometricutilities-styledsweepdoubleonpathdimbuilder)
- [NXOpen.GeometricUtilities.StyledSweepDoubleOnPathDimBuilderList](#nxopen-geometricutilities-styledsweepdoubleonpathdimbuilderlist)
- [NXOpen.GeometricUtilities.StyledSweepReferenceMethodBuilder](#nxopen-geometricutilities-styledsweepreferencemethodbuilder)
- [NXOpen.GeometricUtilities.SupportPlaneData](#nxopen-geometricutilities-supportplanedata)
- [NXOpen.GeometricUtilities.SurfaceRangeBuilder](#nxopen-geometricutilities-surfacerangebuilder)
- [NXOpen.GeometricUtilities.TangentMagnitudeBuilder](#nxopen-geometricutilities-tangentmagnitudebuilder)
- [NXOpen.GeometricUtilities.TransformerData](#nxopen-geometricutilities-transformerdata)
- [NXOpen.GeometricUtilities.TransitionCurveBuilder](#nxopen-geometricutilities-transitioncurvebuilder)
- [NXOpen.GeometricUtilities.TransitionCurveBuilderList](#nxopen-geometricutilities-transitioncurvebuilderlist)
- [NXOpen.GeometricUtilities.TransitionLawNodeBuilder](#nxopen-geometricutilities-transitionlawnodebuilder)
- [NXOpen.GeometricUtilities.TransitionLawNodeBuilderList](#nxopen-geometricutilities-transitionlawnodebuilderlist)
- [NXOpen.GeometricUtilities.TriangularFrameBuilder](#nxopen-geometricutilities-triangularframebuilder)
- [NXOpen.GeometricUtilities.TrimCurveBoundingObjectBuilder](#nxopen-geometricutilities-trimcurveboundingobjectbuilder)
- [NXOpen.GeometricUtilities.TrimCurveBoundingObjectBuilderList](#nxopen-geometricutilities-trimcurveboundingobjectbuilderlist)
- [NXOpen.GeometricUtilities.TwoExpressionsCollectorSet](#nxopen-geometricutilities-twoexpressionscollectorset)
- [NXOpen.GeometricUtilities.TwoExpressionsCollectorSetList](#nxopen-geometricutilities-twoexpressionscollectorsetlist)
- [NXOpen.GeometricUtilities.TwoExpressionsSectionSet](#nxopen-geometricutilities-twoexpressionssectionset)
- [NXOpen.GeometricUtilities.TwoExpressionsSectionSetList](#nxopen-geometricutilities-twoexpressionssectionsetlist)
- [NXOpen.GeometricUtilities.UVMapping.MakeSymmetricParameterizationData](#nxopen-geometricutilities-uvmapping-makesymmetricparameterizationdata)
- [NXOpen.GeometricUtilities.UVMapping.ReverseUVParameterizationData](#nxopen-geometricutilities-uvmapping-reverseuvparameterizationdata)
- [NXOpen.GeometricUtilities.UVMapping.SelectUVMeshObjectData](#nxopen-geometricutilities-uvmapping-selectuvmeshobjectdata)
- [NXOpen.GeometricUtilities.UVMapping.TransformUVParameterizationData](#nxopen-geometricutilities-uvmapping-transformuvparameterizationdata)
- [NXOpen.GeometricUtilities.UVMapping.UVMappingCollection](#nxopen-geometricutilities-uvmapping-uvmappingcollection)
- [NXOpen.GeometricUtilities.UVMapping.UVMeshManipulatorData](#nxopen-geometricutilities-uvmapping-uvmeshmanipulatordata)
- [NXOpen.GeometricUtilities.UVMapping.UVMeshManipulatorData.ObjectSelectionData](#nxopen-geometricutilities-uvmapping-uvmeshmanipulatordata-objectselectiondata)
- [NXOpen.GeometricUtilities.UVMapping.UVParameterizationBuilder](#nxopen-geometricutilities-uvmapping-uvparameterizationbuilder)
- [NXOpen.GeometricUtilities.UnitCellBuilder](#nxopen-geometricutilities-unitcellbuilder)
- [NXOpen.GeometricUtilities.UnnestModuleBuilder](#nxopen-geometricutilities-unnestmodulebuilder)
- [NXOpen.GeometricUtilities.VoronoiItemBuilder](#nxopen-geometricutilities-voronoiitembuilder)
- [NXOpen.GeometricUtilities.VoronoiItemBuilderList](#nxopen-geometricutilities-voronoiitembuilderlist)
- [NXOpen.GeometricUtilities.VoronoiItemListBuilder](#nxopen-geometricutilities-voronoiitemlistbuilder)
- [NXOpen.GeometricUtilities.WaveLinkRepository](#nxopen-geometricutilities-wavelinkrepository)

---

## NXOpen.GeometricUtilities.AlignmentMethodBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57460.html

Represents aNXOpen.GeometricUtilities.AlignmentMethodBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `AddPoint(NXOpen.GeometricUtilities.OnPathDimensionBuilderalignPoint)` | `unsafe int` | Insert a given point, and create corresponding points on other sections.More... |
| `AddSection(int sectionIndex,NXOpen.Sectionsec)` | `unsafe void` | Add a section at the given index among existing sections.More... |
| `ComputeDefaultPoints()` | `unsafe void` | Calculate default alignment points on existing sections.More... |
| `CreateOnPathDimBuilder(NXOpen.Sectionsec,NXOpen.Point3dpnt)` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Set the sections.More... |
| `GetAllPoints(out int numSection)` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder[]` | Get all of the alignment points, returns as a single dimension arrayMore... |
| `GetPoint(int sectionIndex, int pointIndex)` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Gets an alignment point for a sectionMore... |
| `RemoveAllPoints()` | `unsafe void` | Remove all alignment points.More... |
| `RemovePoint(NXOpen.GeometricUtilities.OnPathDimensionBuilderalignPoint)` | `unsafe void` | Remove given point, also remove corresponding points on other sectionsMore... |
| `RemoveSection(NXOpen.Sectionsec)` | `unsafe void` | Find and delete the sectionMore... |
| `RemoveSectionAtIndex(int secIndex)` | `unsafe void` | Remove section at given indexMore... |
| `SetAlignPoints(NXOpen.GeometricUtilities.OnPathDimensionBuilder[] alignPoints)` | `unsafe void` | Set the Alignment Points when sections have been set up.More... |
| `SetSections(NXOpen.Section[] sections)` | `unsafe void` | Set the sections.More... |
| `UnloadSections()` | `unsafe void` | Unload sections held by the builderMore... |
| `UpdateSectionAtIndex(int secIndex)` | `unsafe void` | Update section at given indexMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AlignAxis[get, set]` | `unsafeNXOpen.Axis` | Returns or sets the alignment axisMore... |
| `AlignCurve[get]` | `unsafeNXOpen.Section` | Returns the align curveMore... |
| `AlignType[get, set]` | `unsafeNXOpen.GeometricUtilities.AlignmentMethodBuilder.Type` | Returns or sets the alignment typeMore... |
| `AlignVector[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the alignment vectorMore... |
| `EndAlignFillerSurfaceOption[get, set]` | `unsafeNXOpen.GeometricUtilities.AlignmentMethodBuilder.AlignFillerSurfaceType` | Returns or sets the end align filler surface optionMore... |
| `NumberOfPointsPerSection[get]` | `unsafe int` | Returns the number of alignment points in each section.More... |
| `NumberOfSections[get]` | `unsafe int` | Returns the number of section in the alignment point blockMore... |
| `StartAlignFillerSurfaceOption[get, set]` | `unsafeNXOpen.GeometricUtilities.AlignmentMethodBuilder.AlignFillerSurfaceType` | Returns or sets the start align filler surface optionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.AlongPathPattern

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57464.html

the AlongPath pattern definition

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
| `UseYDirectionToggle[get, set]` | `unsafe bool` | Returns or sets the UseYDirection toggle attribute.More... |
| `XOnPathSpacing[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDistancePatternSpacing` | Returns the on path instance spacing along the x pathMore... |
| `XPath[get, set]` | `unsafeNXOpen.Section` | Returns or sets the x pathMore... |
| `XPathOption[get, set]` | `unsafeNXOpen.GeometricUtilities.AlongPathPattern.PathOptions` | Returns or sets the x path optionsMore... |
| `YDirection[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the y axis, which can be any vector not parallel to the x axisMore... |
| `YDirectionOption[get, set]` | `unsafeNXOpen.GeometricUtilities.AlongPathPattern.YDirectionOptions` | Returns or sets the y direction optionsMore... |
| `YOnPathSpacing[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDistancePatternSpacing` | Returns the on path instance spacing along the y pathMore... |
| `YPath[get, set]` | `unsafeNXOpen.Section` | Returns or sets the y path, which can be any continuous sectionMore... |
| `YPathOption[get, set]` | `unsafeNXOpen.GeometricUtilities.AlongPathPattern.PathOptions` | Returns or sets the y path optionsMore... |
| `YSpacing[get]` | `unsafeNXOpen.GeometricUtilities.DistancePatternSpacing` | Returns the instance spacing along the y axisMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.AlongSpineBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57468.html

Represents aNXOpen.GeometricUtilities.AlongSpineBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateSpinePoint()` | `unsafeNXOpen.GeometricUtilities.OnPathDimWithValueBuilder` | Creates a new spine pointMore... |
| `GetSpinePoints(outNXOpen.GeometricUtilities.OnPathDimWithValueBuilder[] spPoints)` | `unsafe void` | Returns the all SpinePointData objectsMore... |
| `ResetSpine()` | `unsafe void` | Reset the spineMore... |
| `SetFeatureSpine(NXOpen.SectionfeatureSpine)` | `unsafe void` | Set the spine sent by the owning feature dynamically into builderMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `FeatureSpine[get]` | `unsafeNXOpen.Section` | Returns the Spine set by the owning feature of the lawMore... |
| `Spine[get]` | `unsafeNXOpen.Section` | Returns the SpineMore... |
| `SpineOption[get, set]` | `unsafeNXOpen.GeometricUtilities.AlongSpineBuilder.RetainSpineOption` | Returns or sets the spine option of the legacy features.More... |
| `SpinePointList[get]` | `unsafeNXOpen.ObjectList` | Returns the list of spine points.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.AnchorLocatorBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57472.html

Represents aNXOpen.GeometricUtilities.AnchorLocatorBuilder

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
| `Origin[get, set]` | `unsafeNXOpen.Point3d` | Returns or sets the origin of the planeMore... |
| `XAxis[get, set]` | `unsafeNXOpen.Vector3d` | Returns or sets the x-axis of the planeMore... |
| `YAxis[get, set]` | `unsafeNXOpen.Vector3d` | Returns or sets the y-axis of the planeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.AngularLimits

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57476.html

Represents a angular limts data

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Distance[get]` | `unsafe double` | Returns a computed distanceMore... |
| `EndExtend[get]` | `unsafeNXOpen.GeometricUtilities.Extend` | Returns the end extend builderMore... |
| `StartExtend[get]` | `unsafeNXOpen.GeometricUtilities.Extend` | Returns the start extend builderMore... |
| `SymmetricOption[get, set]` | `unsafe bool` | Returns or sets the symmetric optionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.AngularPatternSpacing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57480.html

defines the various ways pattern instances can be spaced within the pattern, particularly in the context of the PatternDefinition class

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `PitchAngle[get]` | `unsafeNXOpen.Expression` | Returns the angle for the spacing of the pattern from one instance to the next.More... |
| `PitchDistance[get]` | `unsafeNXOpen.Expression` | Returns the circumfrential distance for the spacing of the pattern from one instance to the next.More... |
| `SpanAngle[get]` | `unsafeNXOpen.Expression` | Returns the angle for the spacing of the pattern for the entire pattern.More... |
| `UsePitchOption[get, set]` | `unsafeNXOpen.GeometricUtilities.AngularPatternSpacing.UsePitchOptions` | Returns or sets the switch to use Pitch Distance or Pitch Angle.More... |
| `NCopies[get]` | `unsafeNXOpen.Expression` | Returns the number of copies the pattern will generated in this directionMore... |
| `Points[get]` | `unsafeNXOpen.Section` | Returns the section with points to be used in this directionMore... |
| `SpaceType[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternSpacing.SpacingType` | Returns or sets the type of spacing to be used by the patternMore... |
| `SpacingsList[get]` | `unsafeNXOpen.GeometricUtilities.PatternSpacingsList` | Returns the list of spacings (Expression or OnPathDimBuilder) to be used in this directionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.BetweenLocationsData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57484.html

Represents aNXOpen.GeometricUtilities.BetweenLocationsData

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
| `FromLocation[get]` | `unsafeNXOpen.GeometricUtilities.GeometryLocationData` | Returns the from locationMore... |
| `ToLocationList[get]` | `unsafeNXOpen.TaggedObjectList` | Returns the to location listMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.BlendLimitsData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57488.html

Represents aNXOpen.GeometricUtilities.BlendLimitsData

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
| `CapsList[get]` | `unsafeNXOpen.TaggedObjectList` | Returns the caps listMore... |
| `UserSelectedObjects[get, set]` | `unsafe bool` | Returns or sets the use plane cap blendMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.BlendSetbackBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57492.html

This class provides ability to define a setback curve on a blend face

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
| `Direction[get, set]` | `unsafeNXOpen.GeometricUtilities.BlendSetbackBuilder.Directions` | Returns or sets the direction typeMore... |
| `Face[get]` | `unsafeNXOpen.ScCollector` | Returns the blend face collector.More... |
| `HandlePoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the handle point for u/v direction.More... |
| `IsDirectionFlipped[get, set]` | `unsafe bool` | Returns or sets the flag indicating if the setback curve direction is flipped.More... |
| `Plane[get, set]` | `unsafeNXOpen.Plane` | Returns or sets the setback plane.More... |
| `SetbackPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the setback point for u/v direction.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.BlendSetbackBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57496.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.BlendSetbackBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.BlendSetbackBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.BlendSetbackBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.BlendSetbackBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.BlendSetbackBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.BlendSetbackBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.BlendSetbackBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.BlendSetbackBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.BlendSetbackBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.BlendSetbackBuilderobject1,NXOpen.GeometricUtilities.BlendSetbackBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.BlendStopshortBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57500.html

Represents aNXOpen.GeometricUtilities.BlendStopshortBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Destroy()` | `unsafe void` | Destructor forNXOpen.GeometricUtilities.BlendStopshortBuilderMore... |
| `FlipPath()` | `unsafe void` | Flip the builder path forNXOpen.GeometricUtilities.BlendStopshortBuilderMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Choice[get, set]` | `unsafeNXOpen.GeometricUtilities.BlendStopshortBuilder.Choices` | Returns or sets the Stopshort option choice.More... |
| `OnPath[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns theNXOpen.GeometricUtilities.BlendStopshortBuildersubobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.BlendStopshortBuilderCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57504.html

This class contains the factory methods for creating an BlendStopshortBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Create(NXOpen.GeometricUtilities.BlendStopshortBuilder.ChoicesmChoice,NXOpen.ExpressionmOnPathExp,NXOpen.EdgemPath, bool mIsFlipped,NXOpen.PointmThruPoint)` | `unsafeNXOpen.GeometricUtilities.BlendStopshortBuilder` | Creates an BlendStopshortBuilder.More... |
| `ToArray()` | `NXOpen.GeometricUtilities.BlendStopshortBuilder[]` | Returns an array ofNXOpen.GeometricUtilities.BlendStopshortBuilderobjects.More... |
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

## NXOpen.GeometricUtilities.BooleanOperation

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57508.html

Represents a boolean operation

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetBooleanOperationAndBody(outNXOpen.GeometricUtilities.BooleanOperation.BooleanTypetype, outNXOpen.BodytargetBody)` | `unsafe void` | Get the Boolean operation type and target bodyMore... |
| `GetTargetBodies()` | `unsafeNXOpen.Body[]` | Get the target bodiesMore... |
| `SetBooleanOperationAndBody(NXOpen.GeometricUtilities.BooleanOperation.BooleanTypetype,NXOpen.BodytargetBody)` | `unsafe void` | Set the Boolean operation type and target bodyMore... |
| `SetTargetBodies(NXOpen.Body[] targetBodies)` | `unsafe void` | Set the target bodiesMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Type[get, set]` | `unsafeNXOpen.GeometricUtilities.BooleanOperation.BooleanType` | Returns or sets the boolean operation typeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.BooleanRegionSelect

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57512.html

a class which defines boolean region select

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `AppendOneRegionTracker()` | `unsafeNXOpen.GeometricUtilities.RegionTracker` | Create empty region tracker object and register it on the boolean region select builderMore... |
| `AssignTargets(NXOpen.TaggedObject[] targets)` | `unsafe void` | Assigns the targets to be used for region selectionMore... |
| `ClearAllRegionTrackers()` | `unsafe void` | Clears all region trackers currently registered on the featureMore... |
| `ClearRegions()` | `unsafe void` | Clears all preview regions and the current region trackersMore... |
| `NotifyBodiesHaveChanged(NXOpen.ScCollectorbodySelectionList)` | `unsafe void` | Notify that the bodies have changedMore... |
| `RemoveOneRegionTracker(NXOpen.GeometricUtilities.RegionTrackerregionTracker)` | `unsafe void` | Remove one specific region tracker object and un-register it on the boolean region select builderMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `FindAutomaticRegions[get, set]` | `unsafe bool` | Returns or sets the boolean region option to find the automatic/default regions from the input sheet bodiesMore... |
| `KeepRemoveTargetMethod[get, set]` | `unsafeNXOpen.GeometricUtilities.BooleanRegionSelect.KeepRemoveOption` | Returns or sets the boolean region to keep/remove methodMore... |
| `KeepRemoveToolMethod[get, set]` | `unsafeNXOpen.GeometricUtilities.BooleanRegionSelect.KeepRemoveOption` | Returns or sets the boolean region to keep/remove methodMore... |
| `SelectMethod[get, set]` | `unsafeNXOpen.GeometricUtilities.BooleanRegionSelect.SelectOption` | Returns or sets the boolean region selection method methodMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.BooleanToolBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57516.html

a class which defines boolean tool builder

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
| `ExtrudeRevolveTool[get]` | `unsafeNXOpen.GeometricUtilities.ExtrudeRevolveToolBuilder` | Returns the ExtrudeRevolveTool builder.More... |
| `FacePlaneTool[get]` | `unsafeNXOpen.GeometricUtilities.FacePlaneToolBuilder` | Returns the FacePlaneTool Builder.More... |
| `ReverseDirection[get, set]` | `unsafe bool` | Returns or sets the boolean tool reverse direction optionMore... |
| `ToolOption[get, set]` | `unsafeNXOpen.GeometricUtilities.BooleanToolBuilder.BooleanToolType` | Returns or sets the boolean tool optionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.BoundaryDefinitionBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57520.html

Represents aNXOpen.GeometricUtilities.BoundaryDefinitionBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `AppendPoint(NXOpen.Point3dpoint, bool isKeyPoint)` | `unsafe void` | Appends a point to the boundary definitionMore... |
| `Close()` | `unsafe bool` | Closes the boundary by appending start point at the end of boundary definitionMore... |
| `DeleteAll()` | `unsafe void` | Deletes all the points in the boundary definitionMore... |
| `DeleteLastKeyPoint()` | `unsafe void` | Deletes last key point and all the points from last key point up to and excluding its previous key pointMore... |
| `GetPoints()` | `unsafeNXOpen.Point3d[]` | Queries all the boundary definition pointsMore... |
| `SetPlaneNormal(NXOpen.Vector3ddirection)` | `unsafe void` | Sets normal of the plane in which boundary is definedMore... |
| `Translate(NXOpen.Vector3dvector)` | `unsafe void` | Translates the boundary from its current position using the direction and the magnitude of a vector.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Depth[get]` | `unsafeNXOpen.Expression` | Returns the region depthMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.BoundaryDefinitionBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57524.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.BoundaryDefinitionBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.BoundaryDefinitionBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.BoundaryDefinitionBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.BoundaryDefinitionBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.BoundaryDefinitionBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.BoundaryDefinitionBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.BoundaryDefinitionBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.BoundaryDefinitionBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.BoundaryDefinitionBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.BoundaryDefinitionBuilderobject1,NXOpen.GeometricUtilities.BoundaryDefinitionBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.BoundingObjectBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57528.html

Represents aNXOpen.GeometricUtilities.BoundingObjectBuilder

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
| `BoundingCurve[get]` | `unsafeNXOpen.SelectDisplayableObject` | Returns the existing bounding curve.More... |
| `BoundingObjectMethod[get, set]` | `unsafeNXOpen.GeometricUtilities.BoundingObjectBuilder.Method` | Returns or sets the bounding object methodMore... |
| `BoundingPlane[get, set]` | `unsafeNXOpen.Plane` | Returns or sets the bounding plane.More... |
| `BoundingPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the bounding point.More... |
| `BoundingPoint1[get, set]` | `unsafeNXOpen.Point` | Returns or sets the bounding point1.More... |
| `BoundingPoint2[get, set]` | `unsafeNXOpen.Point` | Returns or sets the bounding point2.More... |
| `BoundingProjectPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the bounding project point.More... |
| `BoundingVector[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the bounding vector.More... |
| `IntersectionReference[get, set]` | `unsafeNXOpen.Point` | Returns or sets the intersection referenceMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.BoundingObjectBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57532.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.BoundingObjectBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.BoundingObjectBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.BoundingObjectBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.BoundingObjectBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.BoundingObjectBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.BoundingObjectBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.BoundingObjectBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.BoundingObjectBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.BoundingObjectBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.BoundingObjectBuilderobject1,NXOpen.GeometricUtilities.BoundingObjectBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.BridgeCurveConnectivity

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57536.html

Data offering connectivity controls forNXOpen.Features.BridgeCurveBuilderEx

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `EditUVPercentage(double uPercent, double vPercent)` | `unsafe void` | Edits parameter percentage of a representative point on faceMore... |
| `UpdateBasedOnLocationOnSection()` | `unsafe void` | Updates the data based onNXOpen.GeometricUtilities.BridgeCurveConnectivity.LocationOnSectionMore... |
| `UpdateOnDirectionAtPointReversal()` | `unsafe void` | Updates the data based onBridgeCurveConnectivity.DirectionAtPointsenseMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CanReverseDirection[get, set]` | `unsafe bool` | Returns or sets the flag indicating if tangent direction is to be reversedMore... |
| `Continuity[get]` | `unsafeNXOpen.GeometricUtilities.Continuity` | Returns the continuity levelMore... |
| `CurveDirectionOption[get, set]` | `unsafeNXOpen.GeometricUtilities.BridgeCurveConnectivity.CurveDirectionOptions` | Returns or sets the curve direction optionMore... |
| `DirectionAtPoint[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the direction at pointMore... |
| `FaceDirectionOption[get, set]` | `unsafeNXOpen.GeometricUtilities.BridgeCurveConnectivity.FaceDirectionOptions` | Returns or sets the face direction optionMore... |
| `LocationOnSection[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the location on sectionMore... |
| `PerpendicularFace[get]` | `unsafeNXOpen.SelectFace` | Returns the perpendicular faceMore... |
| `SectionAngle[get]` | `unsafeNXOpen.Expression` | Returns the section angle.More... |
| `UPercentage[get]` | `unsafeNXOpen.Expression` | Returns the U coordinate percentage indicating location on the face where bridge curve is connectedMore... |
| `VPercentage[get]` | `unsafeNXOpen.Expression` | Returns the V coordinate percentage indicating location on the face where bridge curve is connectedMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CAMDataPrepManager

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57540.html

Contains the create functions for builders

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateMatchSurfaceBuilder()` | `unsafeNXOpen.GeometricUtilities.MatchSurfaceBuilder` | Creates aNXOpen.GeometricUtilities.MatchSurfaceBuilderMore... |
| `CreateReduceSurfaceRadiusBuilder()` | `unsafeNXOpen.GeometricUtilities.ReduceSurfaceRadiusBuilder` | Creates aNXOpen.GeometricUtilities.ReduceSurfaceRadiusBuilderMore... |
| `CreateReduceSurfaceRadiusFaceGroupBuilder()` | `unsafeNXOpen.GeometricUtilities.ReduceSurfaceRadiusFaceGroupBuilder` | Creates aNXOpen.GeometricUtilities.ReduceSurfaceRadiusFaceGroupBuilderMore... |
| `CreateSnipIntoPatchesBuilder()` | `unsafeNXOpen.GeometricUtilities.SnipIntoPatchesBuilder` | Creates aNXOpen.GeometricUtilities.SnipIntoPatchesBuilderMore... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ChamferEdgeChainSetBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57544.html

a class which defines the list item in ChamferEdgeManager

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Angular[get]` | `unsafeNXOpen.Expression` | Returns the chamfer angleMore... |
| `CrossSectionOptions[get, set]` | `unsafeNXOpen.GeometricUtilities.ChamferEdgeChainSetBuilder.CrossSectionType` | Returns or sets the Chamfer cross section typeMore... |
| `Distance1[get]` | `unsafeNXOpen.Expression` | Returns the first distance for symmetric/asymmetric offsetMore... |
| `Distance2[get]` | `unsafeNXOpen.Expression` | Returns the second distance for asymmetric offsetMore... |
| `Edges[get, set]` | `unsafeNXOpen.ScCollector` | Returns or sets the edge collector of the edge set to do chamferMore... |
| `ReverseDirection[get, set]` | `unsafe bool` | Returns or sets the offset reverse statusMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ChamferEdgeChainSetBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57548.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.ChamferEdgeChainSetBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.ChamferEdgeChainSetBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.ChamferEdgeChainSetBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.ChamferEdgeChainSetBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.ChamferEdgeChainSetBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.ChamferEdgeChainSetBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.ChamferEdgeChainSetBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.ChamferEdgeChainSetBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.ChamferEdgeChainSetBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.ChamferEdgeChainSetBuilderobject1,NXOpen.GeometricUtilities.ChamferEdgeChainSetBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.ChamferEdgeManager

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57552.html

a class which defines edge manager for Apex Range Chamfer

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateChamferEdgeChainSetBuilder()` | `unsafeNXOpen.GeometricUtilities.ChamferEdgeChainSetBuilder` | Creates a Apex Range Chamfer Edge Chain Set builderMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `EdgeChainSetList[get]` | `unsafeNXOpen.GeometricUtilities.ChamferEdgeChainSetBuilderList` | Returns the list of edge chain set data to do chamferMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CircularCrossSection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57556.html

Represents a circular section data for face blend

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetLawControlConstantRadius(string radius)` | `unsafe void` | Sets a constant radius for the law control of the circular section with face blend.More... |
| `SetLawControlEndRadius(string radius)` | `unsafe void` | Sets a end radius for the law control of the circular section with face blend.More... |
| `SetLawControlStartRadius(string radius)` | `unsafe void` | Sets a start radius for the law control of the circular section with face blend.More... |
| `SetRadius(string radius)` | `unsafe void` | Sets a radius for the circular section with face blend.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `LawControl[get]` | `unsafeNXOpen.GeometricUtilities.LawBuilder` | Returns the Law builderMore... |
| `Radius[get]` | `unsafeNXOpen.Expression` | Returns the radius for the circular section with face blendMore... |
| `RadiusOption[get, set]` | `unsafeNXOpen.GeometricUtilities.RadiusMethod` | Returns or sets the radius option for the circular section with face blendMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CircularFrameBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57560.html

Represents aNXOpen.GeometricUtilities.CircularFrameBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetAngle(int index)` | `unsafe double` | Gets the i-th angle of the circular frameMore... |
| `GetRadius(int index)` | `unsafe double` | Gets the i-th radius of the circular frameMore... |
| `SetAngle(int index, double angle)` | `unsafe void` | Sets the i-th angle of the circular frameMore... |
| `SetRadius(int index, double radius)` | `unsafe void` | Sets the i-th radius of the circular frameMore... |
| `GetMidpointCoords(int index)` | `unsafeNXOpen.Point2d` | Gets the coordinates of the i-th midpoint of the frame with respect to the planeMore... |
| `GetVertexCoords(int index)` | `unsafeNXOpen.Point2d` | Gets the coordinates of the i-th vertex of the frame with respect to the planeMore... |
| `SetMidpointCoords(int index,NXOpen.Point2dcoords)` | `unsafe void` | Sets the coordinates of the i-th midpoint of the frame with respect to the planeMore... |
| `SetVertexCoords(int index,NXOpen.Point2dcoords)` | `unsafe void` | Sets the coordinates of the i-th vertex of the frame with respect to the planeMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Subtype[get, set]` | `unsafeNXOpen.GeometricUtilities.CircularFrameBuilder.Subtypes` | Returns or sets the subtypeMore... |
| `Anchor[get]` | `unsafeNXOpen.GeometricUtilities.AnchorLocatorBuilder` | Returns the anchor of the frameMore... |
| `AnchorAttachment[get, set]` | `unsafeNXOpen.GeometricUtilities.ShapeFrameBuilder.AnchorAttachmentType` | Returns or sets the anchor attachmentMore... |
| `NumberVertices[get]` | `unsafe int` | Returns the number of vertices of the frameMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CircularPattern

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57564.html

the circular pattern definition

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
| `AngularSpacing[get]` | `unsafeNXOpen.GeometricUtilities.AngularPatternSpacing` | Returns the angular spacing of the instances of the patternMore... |
| `CenterPoint[get]` | `unsafeNXOpen.SelectNXObject` | Returns the center point object for 2D mode.More... |
| `CreateLastStaggered[get, set]` | `unsafe bool` | Returns or sets the option to generate the last item in a staggered row.More... |
| `Flip[get, set]` | `unsafe bool` | Returns or sets the flip object for 2D mode.More... |
| `HorizontalRef[get]` | `unsafeNXOpen.GeometricUtilities.HorizontalReference` | Returns the horizontal referenceMore... |
| `IncludeSeedToggle[get, set]` | `unsafe bool` | Returns or sets the IncludeSeed toggle attribute.More... |
| `RadialSpacing[get]` | `unsafeNXOpen.GeometricUtilities.DistancePatternSpacing` | Returns the radial spacing of the instances of the patternMore... |
| `RotationAxis[get, set]` | `unsafeNXOpen.Axis` | Returns or sets the rotation axis for the pattern.More... |
| `RotationCenter[get, set]` | `unsafeNXOpen.Point` | Returns or sets the rotation center for the 2d pattern.More... |
| `StaggerType[get, set]` | `unsafeNXOpen.GeometricUtilities.CircularPattern.StaggerOptions` | Returns or sets the type of stagger to be used by the patternMore... |
| `UseRadialDirectionToggle[get, set]` | `unsafe bool` | Returns or sets the UseRadialDirection toggle attribute.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CollectorPairBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57568.html

Represents a Pair

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Destroy()` | `unsafe void` | Deletes a SI_collectorpairMore... |
| `PopulateSide2FacesFromSide1()` | `unsafe void` | Search the side 2 faces from side 1 using the search distance and create or update side 2 faces collectorMore... |
| `ReverseFacePair()` | `unsafe void` | Button used to determine whether or not to swap face pairsMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AutomaticPair[get, set]` | `unsafe bool` | Returns or sets the auto populate side two faces optionMore... |
| `AutoPopulateSideTwoOption[get, set]` | `unsafe bool` | Returns or sets the auto populate side two faces optionMore... |
| `First[get]` | `unsafeNXOpen.ScCollector` | Returns the side one faces for manual pairMore... |
| `OffsetOnlyOption[get, set]` | `unsafe bool` | Returns or sets the toggle used to determine neutral sheet creation modeMore... |
| `SearchDistance[get]` | `unsafeNXOpen.Expression` | Returns the search distance to be used when searching for side 2 facesMore... |
| `Second[get]` | `unsafeNXOpen.ScCollector` | Returns the side two faces for manual pairMore... |
| `TrimOption[get, set]` | `unsafe bool` | Returns or sets the toggle used to determine whether or not to trim neutral sheetsMore... |
| `UserDefinedMidSurfaceSelection[get]` | `unsafeNXOpen.SelectDisplayableObjectList` | Returns the replacement sheet body, face or datum planeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CollectorPairBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57572.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.CollectorPairBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.CollectorPairBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.CollectorPairBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.CollectorPairBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.CollectorPairBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.CollectorPairBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.CollectorPairBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.CollectorPairBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.CollectorPairBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.CollectorPairBuilderobject1,NXOpen.GeometricUtilities.CollectorPairBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.CollectorPairListBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57576.html

Represents a list ofNXOpen.GeometricUtilities.CollectorPairBuilderobjects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateCollectorPairBuilder()` | `unsafeNXOpen.GeometricUtilities.CollectorPairBuilder` | Creates one item of typeNXOpen.GeometricUtilities.CollectorPairBuilderand append it to the listMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CollectorPairList[get]` | `unsafeNXOpen.GeometricUtilities.CollectorPairBuilderList` | Returns the list of pairsMore... |
| `ShowAutomaticPairs[get, set]` | `unsafe bool` | Returns or sets the toggle used to show the automatically found face pairs from the solid to the listMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ColorCodedRegionBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57580.html

Represents aNXOpen.GeometricUtilities.ColorCodedRegionBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `BuildBodyColoredRegion(NXOpen.DisplayableObjectbody, int facetId, int localVertexId)` | `unsafe void` | Build Colored Region.More... |
| `BuildColoredRegion(NXOpen.Facet.FacetedBodyfacetBody, int facetId, int localVertexId)` | `unsafe void` | Build Colored Region.More... |
| `DeselectColoredRegion(int objIndex)` | `unsafe void` | Deselect Colored RegionMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AllSameColor[get, set]` | `unsafe bool` | Returns or sets the option to select all regions of the same colorMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CombOptionsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57584.html

Represents aNXOpen.GeometricUtilities.CombOptionsBuilder

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
| `AnalysisType[get, set]` | `unsafeNXOpen.GeometricUtilities.CombOptionsBuilder.AnalysisTypes` | Returns or sets the analysis typeMore... |
| `AutoScale[get, set]` | `unsafe bool` | Returns or sets the auto scale flagMore... |
| `Density[get, set]` | `unsafe int` | Returns or sets the densityMore... |
| `HasMaxNeedleLength[get, set]` | `unsafe bool` | Returns or sets the maximum needle flagMore... |
| `IntermediateDensity[get, set]` | `unsafe int` | Returns or sets the intermediate densityMore... |
| `IsMaximumLabelEnabled[get, set]` | `unsafe bool` | Returns or sets the value indicating if the maximum label is enabledMore... |
| `IsMinimumLabelEnabled[get, set]` | `unsafe bool` | Returns or sets the value indicating if the minimum label is enabledMore... |
| `IsNormalToGridPlane[get, set]` | `unsafe bool` | Returns or sets the normal to grid plane flagMore... |
| `MaxNeedleLength[get, set]` | `unsafe double` | Returns or sets the maximum needle lengthMore... |
| `ReverseNeedles[get, set]` | `unsafe bool` | Returns or sets the reverse needles flagMore... |
| `SampleDistance[get, set]` | `unsafe double` | Returns or sets the sample distanceMore... |
| `ScaleFactor[get, set]` | `unsafe double` | Returns or sets the scale factorMore... |
| `ShowNeedles[get, set]` | `unsafe bool` | Returns or sets the show needles flagMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ConicCrossSection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57588.html

Represents a conic section data for face blend

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetFirstOffset(string offset)` | `unsafe void` | Sets the first offset for the conic section with face blend.More... |
| `SetLawControlConstantDepth(string radius)` | `unsafe void` | Sets a constant radius for the depth law control of the conic section with face blend.More... |
| `SetLawControlConstantFirstOffset(string radius)` | `unsafe void` | Sets a constant radius for the first law control of the conic section with face blend.More... |
| `SetLawControlConstantRho(string radius)` | `unsafe void` | Sets a constant radius for the rho law control of the conic section with face blend.More... |
| `SetLawControlConstantSecondOffset(string radius)` | `unsafe void` | Sets a constant radius for the second law control of the conic section with face blend.More... |
| `SetLawControlConstantShapeSkew(string radius)` | `unsafe void` | Sets a constant radius for the shape skew law control of the conic section with face blend.More... |
| `SetLawControlDepthEndRadius(string radius)` | `unsafe void` | Sets a end radius for the depth law control of the conic section with face blend.More... |
| `SetLawControlDepthStartRadius(string radius)` | `unsafe void` | Sets a start radius for the depth law control of the conic section with face blend.More... |
| `SetLawControlFirstOffsetEndRadius(string radius)` | `unsafe void` | Sets a end radius for the first law control of the conic section with face blend.More... |
| `SetLawControlFirstOffsetStartRadius(string radius)` | `unsafe void` | Sets a start radius for the first law control of the conic section with face blend.More... |
| `SetLawControlRhoEndRadius(string radius)` | `unsafe void` | Sets a end radius for the rho law control of the conic section with face blend.More... |
| `SetLawControlRhoStartRadius(string radius)` | `unsafe void` | Sets a start radius for the rho law control of the conic section with face blend.More... |
| `SetLawControlSecondOffsetEndRadius(string radius)` | `unsafe void` | Sets a end radius for the second law control of the conic section with face blend.More... |
| `SetLawControlSecondOffsetStartRadius(string radius)` | `unsafe void` | Sets a start radius for the second law control of the conic section with face blend.More... |
| `SetLawControlShapeSkewEndRadius(string radius)` | `unsafe void` | Sets a end radius for the shape skew law control of the conic section with face blend.More... |
| `SetLawControlShapeSkewStartRadius(string radius)` | `unsafe void` | Sets a start radius for the shape skew law control of the conic section with face blend.More... |
| `SetRho(string rho)` | `unsafe void` | Sets a rho expression for the conic section with face blend.More... |
| `SetSecondOffset(string offset)` | `unsafe void` | Sets the second offset for the conic section with face blend.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `ConicMethod[get, set]` | `unsafeNXOpen.GeometricUtilities.ConicCrossSection.DefineMethod` | Returns or sets the conic method for the advanced symmetric conic section with face blendMore... |
| `Depth[get]` | `unsafeNXOpen.Expression` | Returns the depth expression for the conic section with face blendMore... |
| `DepthLawControl[get]` | `unsafeNXOpen.GeometricUtilities.LawBuilder` | Returns the Depth Law builderMore... |
| `DepthOption[get, set]` | `unsafeNXOpen.GeometricUtilities.ConicCrossSection.DepthMethod` | Returns or sets the depth option for the conic section with face blendMore... |
| `FirstConstraintCurveCollector[get, set]` | `unsafeNXOpen.ScCollector` | Returns or sets the first constraint curve collectorMore... |
| `FirstLawControl[get]` | `unsafeNXOpen.GeometricUtilities.LawBuilder` | Returns the First Offset Law builderMore... |
| `FirstOffset[get]` | `unsafeNXOpen.Expression` | Returns the first offset for the conic section with face blendMore... |
| `FirstOffsetOption[get, set]` | `unsafeNXOpen.GeometricUtilities.ConicCrossSection.OffsetMethod` | Returns or sets the first offset option for the conic section with face blendMore... |
| `OffsetSkewRatio[get]` | `unsafeNXOpen.Expression` | Returns the offset skew ratio expression for the conic section with face blendMore... |
| `Rho[get]` | `unsafeNXOpen.Expression` | Returns the rho expression for the conic section with face blendMore... |
| `RhoLawControl[get]` | `unsafeNXOpen.GeometricUtilities.LawBuilder` | Returns the Rho Law builderMore... |
| `RhoOption[get, set]` | `unsafeNXOpen.GeometricUtilities.ConicCrossSection.RhoMethod` | Returns or sets the rho option for the conic section with face blendMore... |
| `SecondConstraintCurveCollector[get, set]` | `unsafeNXOpen.ScCollector` | Returns or sets the second constraint curve collectorMore... |
| `SecondLawControl[get]` | `unsafeNXOpen.GeometricUtilities.LawBuilder` | Returns the Second Offset Law builderMore... |
| `SecondOffset[get]` | `unsafeNXOpen.Expression` | Returns the second offset for the conic section with face blendMore... |
| `SecondOffsetOption[get, set]` | `unsafeNXOpen.GeometricUtilities.ConicCrossSection.OffsetMethod` | Returns or sets the second offset option for the conic section with face blendMore... |
| `ShapeSkew[get]` | `unsafeNXOpen.Expression` | Returns the shape skew expression for the conic section with face blendMore... |
| `ShapeSkewLawControl[get]` | `unsafeNXOpen.GeometricUtilities.LawBuilder` | Returns the Shape Skew Law builderMore... |
| `ShapeSkewOption[get, set]` | `unsafeNXOpen.GeometricUtilities.ConicCrossSection.ShapeSkewMethod` | Returns or sets the shape skew option for the conic section with face blendMore... |
| `TransitionLinkFlag[get, set]` | `unsafe bool` | Returns or sets the flag to link multi-transition law typesMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.Continuity

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57592.html

Represents aNXOpen.GeometricUtilities.ContinuityAllows user to specify continuity constraint surface construction

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
| `ConstraintFaces[get]` | `unsafeNXOpen.ScCollector` | Returns the constraint face collector.More... |
| `ContinuityType[get, set]` | `unsafeNXOpen.GeometricUtilities.Continuity.ContinuityTypes` | Returns or sets the continuity type.More... |
| `IsFixed[get, set]` | `unsafe bool` | Returns or sets the value indicating if a continuity constraint is of fixed type.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ControlPoleManagerData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57596.html

This class manages the control poles for a set of surfaces or curves

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreatePolesGroup()` | `unsafe int` | Creates a new poles groupMore... |
| `DeletePolesGroup(int groupIndex)` | `unsafe void` | Deletes a group of polesMore... |
| `DeselectPoles(int groupIndex, int [] polesIndex,NXOpen.Point[] poles)` | `unsafe void` | Removes selected poleMore... |
| `GetIsUPeriodic(int groupIndex)` | `unsafe bool` | Queries periodicity in U direction of a group of polesMore... |
| `GetIsVPeriodic(int groupIndex)` | `unsafe bool` | Queries periodicity in V direction of a group of polesMore... |
| `GetPoles(int groupIndex, out int [] polesIndex, outNXOpen.Point[] poles)` | `unsafe void` | Gets poles of an entityMore... |
| `GetSelectedPoles(int groupIndex, out int [] polesIndex, outNXOpen.Point[] poles)` | `unsafe void` | Gets selected polesMore... |
| `GetUDimension(int groupIndex)` | `unsafe int` | Queries dimension in U direction of a group of polesMore... |
| `GetVDimension(int groupIndex)` | `unsafe int` | Queries dimension in V direction of a group of polesMore... |
| `SelectPoles(int groupIndex, int [] polesIndex,NXOpen.Point[] poles)` | `unsafe void` | Adds new selected poleMore... |
| `SetIsUPeriodic(int groupIndex, bool uPeriodicity)` | `unsafe void` | Sets periodicity in U direction of a group of polesMore... |
| `SetIsVPeriodic(int groupIndex, bool vPeriodicity)` | `unsafe void` | Sets periodicity in V direction of a group of polesMore... |
| `SetPoleGroupEntity(int groupIndex,NXOpen.Faceface)` | `unsafe void` | Sets face to control poles groupMore... |
| `SetPoleGroupEntity(int groupIndex,NXOpen.Curvecurve)` | `unsafe void` | Sets curve to control poles groupMore... |
| `SetPoles(int groupIndex, int [] polesIndex,NXOpen.Point[] poles)` | `unsafe void` | Sets new group polesMore... |
| `SetUDimension(int groupIndex, int uDimension)` | `unsafe void` | Sets dimension in U direction of a group of polesMore... |
| `SetVDimension(int groupIndex, int vDimension)` | `unsafe void` | Sets dimension in V direction of a group of polesMore... |
| `UpdatePolePositions(int groupIndex, int [] poleIndex,NXOpen.Point3d[] newPosition)` | `unsafe void` | Updates pole positionsMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |


---

## NXOpen.GeometricUtilities.ConvertFeatureGroupsToModulesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57600.html

Represents aNXOpen.GeometricUtilities.ConvertFeatureGroupsToModulesBuilderbuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `AddAll()` | `unsafe void` | Add all feature groups into convertible setMore... |
| `AddFeatureGroupIntoConvertibleSet(NXOpen.Features.FeatureGroup[] featureGroups)` | `unsafe void` | Add feature group into convertible setMore... |
| `RemoveAll()` | `unsafe void` | Remove all feature groups from convertible setMore... |
| `RemoveFeatureGroupFromConvertibleSet(NXOpen.Features.FeatureGroup[] featureGroups)` | `unsafe void` | Remove feature group from convertible setMore... |
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


---

## NXOpen.GeometricUtilities.CrayonSelectionData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57604.html

Represents aNXOpen.GeometricUtilities.CrayonSelectionData

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Clear()` | `unsafe void` | Clears all the selected entitiesMore... |
| `GetEntities()` | `unsafeNXOpen.GeometricUtilities.CrayonSelectionData.EntityData[]` | Queries all the selected entities.More... |
| `SelectEntities(NXOpen.GeometricUtilities.CrayonSelectionData.EntityData[] entities)` | `unsafe void` | Selects an array of entities and appends to currently selected entities.More... |
| `SelectEntity(NXOpen.GeometricUtilities.CrayonSelectionData.EntityDataentity)` | `unsafe void` | Selects an entity and appends to currently selected array of entities.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |


---

## NXOpen.GeometricUtilities.CrayonSelectionData.EntityData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57608.html

Structure representing selected entity data

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `EntityData(NXOpen.NXObjectEntity,NXOpen.Point3dPickPoint,NXOpen.ViewView)` | `` | Constructor for the EntityData struct.More... |


---

## NXOpen.GeometricUtilities.CurveAlignedItemBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57616.html

Represents a single item in the Curve Aligned List

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CurveAlignedSelection[get]` | `unsafeNXOpen.Section` | Returns the sc section which contains curves.More... |
| `CurveControl[get, set]` | `unsafeNXOpen.GeometricUtilities.CurveAlignedItemBuilder.CurveControlTypes` | Returns or sets the curve controlsMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CurveAlignedItemBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57620.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.CurveAlignedItemBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.CurveAlignedItemBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.CurveAlignedItemBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.CurveAlignedItemBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.CurveAlignedItemBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.CurveAlignedItemBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.CurveAlignedItemBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.CurveAlignedItemBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.CurveAlignedItemBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.CurveAlignedItemBuilderobject1,NXOpen.GeometricUtilities.CurveAlignedItemBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.CurveAlignedListBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57624.html

the builder for a list ofGeometricUtilities.CurveAlignedItemBuilderobjects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateCurveAlignedItemBuilder()` | `unsafeNXOpen.GeometricUtilities.CurveAlignedItemBuilder` | Creates aGeometricUtilities.CurveAlignedItemBuilderMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `List[get]` | `unsafeNXOpen.GeometricUtilities.CurveAlignedItemBuilderList` | Returns a list ofGeometricUtilities.CurveAlignedItemBuilderobjectsMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CurveExtendData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57628.html

Represents aNXOpen.GeometricUtilities.CurveExtendData

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
| `Distance[get]` | `unsafeNXOpen.Expression` | Returns the distanceMore... |
| `LimitOption[get, set]` | `unsafeNXOpen.GeometricUtilities.CurveExtendData.LimitOptions` | Returns or sets the limit optionMore... |
| `UntilSelectedObject[get]` | `unsafeNXOpen.SelectDisplayableObject` | Returns the until selected objectMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CurveExtensionBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57632.html

Spline extension builder class

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
| `EndExtensionOption[get, set]` | `unsafeNXOpen.GeometricUtilities.CurveExtensionBuilder.ExtensionOption` | Returns or sets the extension optionsMore... |
| `EndPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the point up to which end is extendedMore... |
| `EndValue[get]` | `unsafeNXOpen.Expression` | Returns the end valueMore... |
| `IsSymmetric[get, set]` | `unsafe bool` | Returns or sets the flag indicating if extension is symmetry.More... |
| `StartExtensionOption[get, set]` | `unsafeNXOpen.GeometricUtilities.CurveExtensionBuilder.ExtensionOption` | Returns or sets the extension optionsMore... |
| `StartPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the point up to which start is extendedMore... |
| `StartValue[get]` | `unsafeNXOpen.Expression` | Returns the start valueMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CurveFitData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57636.html

Represents the curve fitting methods options

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
| `AngleTolerance[get, set]` | `unsafe double` | Returns or sets the angle toleranceMore... |
| `CurveJoinMethod[get, set]` | `unsafeNXOpen.GeometricUtilities.CurveFitData.Join` | Returns or sets the curve join methodMore... |
| `Degree[get, set]` | `unsafe int` | Returns or sets the fitting degreeMore... |
| `FitMethod[get, set]` | `unsafeNXOpen.GeometricUtilities.CurveFitData.Method` | Returns or sets the fitting methodMore... |
| `IsAdvancedFit[get, set]` | `unsafe bool` | Returns or sets the advanced fitting optionMore... |
| `IsAlignShape[get, set]` | `unsafe bool` | Returns or sets the align shape optionMore... |
| `MaximumDegree[get, set]` | `unsafe int` | Returns or sets the maximum degreeMore... |
| `MaximumSegments[get, set]` | `unsafe int` | Returns or sets the maximum segmentsMore... |
| `MinimumDegree[get, set]` | `unsafe int` | Returns or sets the minimum degreeMore... |
| `Segments[get, set]` | `unsafe int` | Returns or sets the fitting segmentsMore... |
| `Tolerance[get, set]` | `unsafe double` | Returns or sets the toleranceMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CurveFitJoin

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57640.html

Represents the curve fit join data

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
| `CurveFitOptions[get]` | `unsafeNXOpen.GeometricUtilities.CurveFitOptions` | Returns the curve fit optionsMore... |
| `CurveJoinMethod[get, set]` | `unsafeNXOpen.GeometricUtilities.CurveFitJoin.JoinMethod` | Returns or sets the curve join methodMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CurveFitOptions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57644.html

Represents the curve fit data

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
| `FitOption[get, set]` | `unsafeNXOpen.GeometricUtilities.CurveFitOptions.FitMethod` | Returns or sets the curve fit methodMore... |
| `MaximumDegree[get, set]` | `unsafe int` | Returns or sets the maximum degree methodMore... |
| `MaximumSegments[get, set]` | `unsafe int` | Returns or sets the maximum segments methodMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CurveLengthBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57648.html

Represents aNXOpen.GeometricUtilities.CurveLengthBuilderbuilder

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
| `EndOffset0[get]` | `unsafeNXOpen.Expression` | Returns the end 1 lengthMore... |
| `EndOffset1[get]` | `unsafeNXOpen.Expression` | Returns the end 2 lengthMore... |
| `EndSelection0[get]` | `unsafeNXOpen.SelectDisplayableObjectList` | Returns the select object for end 1More... |
| `EndSelection1[get]` | `unsafeNXOpen.SelectDisplayableObjectList` | Returns the select object for end 2More... |
| `EndType0[get, set]` | `unsafeNXOpen.GeometricUtilities.CurveLengthBuilder.EndObjectType` | Returns or sets the end 1 typeMore... |
| `EndType1[get, set]` | `unsafeNXOpen.GeometricUtilities.CurveLengthBuilder.EndObjectType` | Returns or sets the end 2 typeMore... |
| `ReverseEndOffset0Direction[get, set]` | `unsafe bool` | Returns or sets the reverse endOffset0 direction flag.More... |
| `ReverseEndOffset1Direction[get, set]` | `unsafe bool` | Returns or sets the reverse endOffset1 direction flag.More... |
| `ReverseGuideCurveLoopDirection[get, set]` | `unsafe bool` | Returns or sets the reverse guide curve direction flag.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CurveLengthData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57652.html

Represents an CurveLength data

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetEndDistance(string endDistance)` | `unsafe void` | Set end distanceMore... |
| `SetStartDistance(string startDistance)` | `unsafe void` | Set start distanceMore... |
| `SetTotalLength(string totalLength)` | `unsafe void` | Set total lengthMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `EndDistance[get]` | `unsafeNXOpen.Expression` | Returns the end distanceMore... |
| `ExtensionDirection[get, set]` | `unsafeNXOpen.GeometricUtilities.ExtensionDirection` | Returns or sets the extension directionMore... |
| `ExtensionMethod[get, set]` | `unsafeNXOpen.GeometricUtilities.ExtensionMethod` | Returns or sets the total or incremental extension methodMore... |
| `ExtensionSide[get, set]` | `unsafeNXOpen.GeometricUtilities.ExtensionSide` | Returns or sets the extension side optionMore... |
| `StartDistance[get]` | `unsafeNXOpen.Expression` | Returns the start distanceMore... |
| `TotalLength[get]` | `unsafeNXOpen.Expression` | Returns the total lengthMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CurveLimitsData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57656.html

Represents aNXOpen.GeometricUtilities.CurveLimitsData

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `ComplementArc()` | `unsafe void` | Complements the arcMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `EndLimit[get]` | `unsafeNXOpen.GeometricUtilities.CurveExtendData` | Returns the end limitMore... |
| `FullCircle[get, set]` | `unsafe bool` | Returns or sets the full circleMore... |
| `StartLimit[get]` | `unsafeNXOpen.GeometricUtilities.CurveExtendData` | Returns the start limitMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CurveLocation

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57660.html

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CurveLocation(NXOpen.GeometricUtilities.CurveLocationTypeType,NXOpen.Point3dLocation)` | `` | Constructor for the CurveLocation struct.More... |


---

## NXOpen.GeometricUtilities.CurveOptions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57664.html

Represents the curve options data

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
| `Associative[get, set]` | `unsafe bool` | Returns or sets the associativity optionMore... |
| `InputCurveOption[get, set]` | `unsafeNXOpen.GeometricUtilities.CurveOptions.InputCurve` | Returns or sets the curve optionsMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CurveRangeBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57668.html

Represents the curve range and anchor builder

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
| `AnchorPosition[get, set]` | `unsafeNXOpen.GeometricUtilities.CurveRangeBuilder.AnchorPositionType` | Returns or sets the anchor positionMore... |
| `Center[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the centerMore... |
| `End[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the endMore... |
| `Start[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the startMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CurveSettings

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57672.html

Represents the curve settings data

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
| `CurveFitData[get]` | `unsafeNXOpen.GeometricUtilities.CurveFitData` | Returns the curve fit dataMore... |
| `InputCurvesOption[get]` | `unsafeNXOpen.GeometricUtilities.CurveOptions` | Returns the input curves optionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.CurveShapingBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57676.html

Represents aNXOpen.GeometricUtilities.CurveShapingBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `AddCurve(NXOpen.Curvecurve)` | `unsafe void` | Adds a curve for shapingMore... |
| `ApplyParameterValue(NXOpen.PointsourcePoint,NXOpen.Point[] destinationPoints)` | `unsafe void` | Applies parameter value from a key point to a group of key points without affecting curve shapeMore... |
| `Deform()` | `unsafe void` | Deforms curves based on active pointsMore... |
| `DeleteAllPoints(NXOpen.Splinecurve)` | `unsafe void` | Deletes all points on a curve.More... |
| `RemoveCurve(NXOpen.Curvecurve)` | `unsafe void` | Removes a curveMore... |
| `SetActivePoints(NXOpen.Point[] points,NXOpen.PointmasterPoint)` | `unsafe void` | Sets key points that are selected or will be movedMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CanMoveAlongCurve[get, set]` | `unsafe bool` | Returns or sets the value indicating if point should be moved along curve.More... |
| `ConstraintManager[get]` | `unsafeNXOpen.Features.GeometricConstraintDataManager` | Returns the constraint manager.More... |
| `EndContinuity[get, set]` | `unsafeNXOpen.GeometricUtilities.Continuity.ContinuityTypes` | Returns or sets the continuity at end of the curveMore... |
| `HasLinearTransition[get, set]` | `unsafe bool` | Returns or sets the value indicating if transition type is linearMore... |
| `InsertionMethod[get, set]` | `unsafeNXOpen.GeometricUtilities.CurveShapingBuilder.InsertionMethodOptions` | Returns or sets the point insertion methodMore... |
| `MovementMethod[get, set]` | `unsafeNXOpen.GeometricUtilities.CurveShapingBuilder.MovementMethodType` | Returns or sets the movement methodMore... |
| `MovementPlane[get, set]` | `unsafeNXOpen.Plane` | Returns or sets the movement planeMore... |
| `MovementVector[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the movement vectorMore... |
| `Number[get, set]` | `unsafe int` | Returns or sets the number of points to be insertedMore... |
| `OrientExpress[get]` | `unsafeNXOpen.GeometricUtilities.OrientXpressBuilder` | Returns the orient express objectMore... |
| `SelectCurves[get]` | `unsafeNXOpen.SelectSplineList` | Returns the curve selection for point insertionMore... |
| `SpecifyPoints[get]` | `unsafeNXOpen.SelectPointList` | Returns the specified points to define insertion point locationsMore... |
| `StartContinuity[get, set]` | `unsafeNXOpen.GeometricUtilities.Continuity.ContinuityTypes` | Returns or sets the continuity at start of the curveMore... |
| `WCSOption[get, set]` | `unsafeNXOpen.GeometricUtilities.CurveShapingBuilder.WCSOptionType` | Returns or sets the WCS optionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.DegreesAndSegmentsOrPatchesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57680.html

the DegreesAndSegmentsOrPatches builder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `FindObject(string journalIdentifier)` | `unsafeNXOpen.INXObject` | Finds theNXOpen.NXObjectwith the given identifier as recorded in a journal.More... |
| `Print()` | `unsafe void` | Prints a representation of this object to the system log file.More... |
| `SetName(string name)` | `unsafe void` | Sets the custom name of the object.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Degree[get, set]` | `unsafe int` | Returns or sets the degreeMore... |
| `IsOccurrence[get]` | `unsafe bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `unsafe string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Name[get]` | `unsafe string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `unsafeNXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `unsafeNXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `unsafeNXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |
| `SegmentsOrPatches[get, set]` | `unsafe int` | Returns or sets the patchesMore... |
| `UDegree[get, set]` | `unsafe int` | Returns or sets the u degreeMore... |
| `UPatches[get, set]` | `unsafe int` | Returns or sets the u patchesMore... |
| `VDegree[get, set]` | `unsafe int` | Returns or sets the v degreeMore... |
| `VPatches[get, set]` | `unsafe int` | Returns or sets the v patchesMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |
| `IsOccurrence[get]` | `bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Name[get]` | `string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `NXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `NXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `NXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |


---

## NXOpen.GeometricUtilities.DepthSkewBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57684.html

This class provides ability to specify a depth and a skew value

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
| `Depth[get]` | `unsafeNXOpen.Expression` | Returns the depthMore... |
| `Skew[get]` | `unsafeNXOpen.Expression` | Returns the skewMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.DesignMeshBody

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57688.html

Represents a faceted mesh

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetEdges()` | `unsafeNXOpen.GeometricUtilities.DesignMeshEdge[]` | Returns the edges in the mesh.More... |
| `GetFaces()` | `unsafeNXOpen.GeometricUtilities.DesignMeshFace[]` | Returns the faces in the mesh.More... |
| `GetVertices()` | `unsafeNXOpen.GeometricUtilities.DesignMeshVertex[]` | Returns the vertexes in the mesh.More... |
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

## NXOpen.GeometricUtilities.DesignMeshEdge

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57692.html

Represents a facet mesh edge

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetBody()` | `unsafeNXOpen.GeometricUtilities.DesignMeshBody` | Returns the mesh owning this edge.More... |
| `GetFaces(outNXOpen.GeometricUtilities.DesignMeshFaceface1, outNXOpen.GeometricUtilities.DesignMeshFaceface2)` | `unsafe void` | Returns the faces connected to the edge.More... |
| `GetVertices(outNXOpen.GeometricUtilities.DesignMeshVertexvertex1, outNXOpen.GeometricUtilities.DesignMeshVertexvertex2)` | `unsafe void` | Returns the vertexes of the edge.More... |
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

## NXOpen.GeometricUtilities.DesignMeshFace

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57696.html

Represents a facet mesh face

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetBody()` | `unsafeNXOpen.GeometricUtilities.DesignMeshBody` | Returns the mesh owning this face.More... |
| `GetEdges()` | `unsafeNXOpen.GeometricUtilities.DesignMeshEdge[]` | Returns the edges of the face.More... |
| `GetVertices()` | `unsafeNXOpen.GeometricUtilities.DesignMeshVertex[]` | Returns the vertexes of the face.More... |
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

## NXOpen.GeometricUtilities.DesignMeshVertex

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57700.html

Represents a facet mesh vertex

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetBody()` | `unsafeNXOpen.GeometricUtilities.DesignMeshBody` | Returns the mesh owning this vertex.More... |
| `GetCoordinates()` | `unsafeNXOpen.Point3d` | Returns the position of the vertex.More... |
| `GetEdges()` | `unsafeNXOpen.GeometricUtilities.DesignMeshEdge[]` | Returns the edges connected to the vertex.More... |
| `GetFaces()` | `unsafeNXOpen.GeometricUtilities.DesignMeshFace[]` | Returns the faces connected to the vertex.More... |
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

## NXOpen.GeometricUtilities.DisplayResolutionBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57704.html

Represents aNXOpen.GeometricUtilities.DisplayResolutionBuilder

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
| `AngleTolerance[get, set]` | `unsafe double` | Returns or sets the angle toleranceMore... |
| `EdgeTolerance[get, set]` | `unsafe double` | Returns or sets the edge toleranceMore... |
| `FaceTolerance[get, set]` | `unsafe double` | Returns or sets the face toleranceMore... |
| `Resolution[get, set]` | `unsafeNXOpen.Preferences.PartVisualizationShade.AdvViewToleranceType` | Returns or sets the resolutionMore... |
| `WidthTolerance[get, set]` | `unsafe double` | Returns or sets the width toleranceMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.DistancePatternSpacing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57708.html

defines the various ways pattern instances can be spaced within the pattern, particularly in the context of the PatternDefinition class

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `PitchDistance[get]` | `unsafeNXOpen.Expression` | Returns the distance for the spacing of the pattern from one instance to the next.More... |
| `SpanDistance[get]` | `unsafeNXOpen.Expression` | Returns the distance for the spacing of the pattern for the entire pattern.More... |
| `NCopies[get]` | `unsafeNXOpen.Expression` | Returns the number of copies the pattern will generated in this directionMore... |
| `Points[get]` | `unsafeNXOpen.Section` | Returns the section with points to be used in this directionMore... |
| `SpaceType[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternSpacing.SpacingType` | Returns or sets the type of spacing to be used by the patternMore... |
| `SpacingsList[get]` | `unsafeNXOpen.GeometricUtilities.PatternSpacingsList` | Returns the list of spacings (Expression or OnPathDimBuilder) to be used in this directionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.DraftPointData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57712.html

Represents a draft point data object

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetAngle()` | `unsafeNXOpen.Expression` | Returns the Angle valueMore... |
| `SetAngle(string angle)` | `unsafe void` | Sets the Angle valueMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Parameter[get, set]` | `unsafe double` | Returns or sets the point coordinatesMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.DraftVariableAngleData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57716.html

Represents data containing variable angle draft point data objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `AddDraftPoints(NXOpen.GeometricUtilities.DraftPointData[] points)` | `unsafe void` | AddsNXOpen.GeometricUtilities.DraftPointDataobjectsMore... |
| `GetDraftPoints()` | `unsafeNXOpen.GeometricUtilities.DraftPointData[]` | ReturnsNXOpen.GeometricUtilities.DraftPointDataobjectsMore... |
| `GetNumberOfDraftPoints()` | `unsafe int` | Returns number ofNXOpen.GeometricUtilities.DraftPointDataobjectsMore... |
| `RemoveDraftPoints(NXOpen.GeometricUtilities.DraftPointData[] points)` | `unsafe void` | RemovesNXOpen.GeometricUtilities.DraftPointDataobjectsMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |


---

## NXOpen.GeometricUtilities.EndHoleData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57720.html

Represents aNXOpen.GeometricUtilities.EndHoleData

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
| `BooleanOperation[get]` | `unsafeNXOpen.GeometricUtilities.BooleanOperation` | Returns the boolean operationMore... |
| `DepthOption[get, set]` | `unsafeNXOpen.GeometricUtilities.EndHoleData.HoleDepthOptions` | Returns or sets the hole depth optionMore... |
| `FitOption[get, set]` | `unsafe string` | Returns or sets the fit optionMore... |
| `FormOption[get, set]` | `unsafeNXOpen.GeometricUtilities.EndHoleData.FormOptions` | Returns or sets the form optionMore... |
| `HoleDepth[get]` | `unsafeNXOpen.Expression` | Returns the hole depthMore... |
| `HoleDepthLimitOption[get, set]` | `unsafeNXOpen.GeometricUtilities.EndHoleData.HoleDepthLimitOptions` | Returns or sets the hole depth limitMore... |
| `HoleDiameter[get]` | `unsafeNXOpen.Expression` | Returns the hole diameterMore... |
| `MatchDimOfStartHole[get, set]` | `unsafe bool` | Returns or sets the match dim of start holeMore... |
| `RadialEngageOption[get, set]` | `unsafe string` | Returns or sets the radial engage optionMore... |
| `ReliefChamferEnabled[get, set]` | `unsafe bool` | Returns or sets the threaded relief chamfer enabled - this is applicable for threaded hole typeMore... |
| `ScrewClearanceEndChamferAngle[get]` | `unsafeNXOpen.Expression` | Returns the screw clearance end chamfer angleMore... |
| `ScrewClearanceEndChamferEnabled[get, set]` | `unsafe bool` | Returns or sets the screw clearance end chamfer enabledMore... |
| `ScrewClearanceEndChamferOffset[get]` | `unsafeNXOpen.Expression` | Returns the screw clearance end chamfer offsetMore... |
| `ScrewClearanceStartChamferAngle[get]` | `unsafeNXOpen.Expression` | Returns the screw clearance start chamfer angleMore... |
| `ScrewClearanceStartChamferEnabled[get, set]` | `unsafe bool` | Returns or sets the screw clearance start chamfer enabledMore... |
| `ScrewClearanceStartChamferOffset[get]` | `unsafeNXOpen.Expression` | Returns the screw clearance start chamfer offsetMore... |
| `TapDrillDiameter[get]` | `unsafeNXOpen.Expression` | Returns the tap drill diameterMore... |
| `ThreadDepth[get]` | `unsafeNXOpen.Expression` | Returns the thread depthMore... |
| `ThreadedEndChamferAngle[get]` | `unsafeNXOpen.Expression` | Returns the threaded end chamfer angleMore... |
| `ThreadedEndChamferDiameter[get]` | `unsafeNXOpen.Expression` | Returns the threaded end chamfer offsetMore... |
| `ThreadedEndChamferEnabled[get, set]` | `unsafe bool` | Returns or sets the threaded end chamfer enabledMore... |
| `ThreadedReliefAngle[get]` | `unsafeNXOpen.Expression` | Returns the relief angle - this is applicable for threaded hole typeMore... |
| `ThreadedReliefChamferAngle[get]` | `unsafeNXOpen.Expression` | Returns the threaded relief chamfer angle - this is applicable for threaded hole typeMore... |
| `ThreadedReliefChamferOffset[get]` | `unsafeNXOpen.Expression` | Returns the threaded relief chamfer offset - this is applicable for threaded hole typeMore... |
| `ThreadedReliefDepth[get]` | `unsafeNXOpen.Expression` | Returns the threaded relief depth - this is applicable for threaded hole typeMore... |
| `ThreadedReliefDiameter[get]` | `unsafeNXOpen.Expression` | Returns the relief diameter - this is applicable for threaded hole typeMore... |
| `ThreadedReliefEnabled[get, set]` | `unsafe bool` | Returns or sets the threaded relief enabled - this is applicable for threaded hole typeMore... |
| `ThreadedStartChamferAngle[get]` | `unsafeNXOpen.Expression` | Returns the threaded start chamfer angleMore... |
| `ThreadedStartChamferDiameter[get]` | `unsafeNXOpen.Expression` | Returns the threaded start chamfer offsetMore... |
| `ThreadedStartChamferEnabled[get, set]` | `unsafe bool` | Returns or sets the threaded start chamfer enabledMore... |
| `ThreadLengthOption[get, set]` | `unsafeNXOpen.GeometricUtilities.EndHoleData.ThreadLengthOptions` | Returns or sets the thread length optionMore... |
| `ThreadRotation[get, set]` | `unsafeNXOpen.GeometricUtilities.EndHoleData.ThreadRotationOptions` | Returns or sets the thread rotationMore... |
| `ThreadSize[get, set]` | `unsafe string` | Returns or sets the thread sizeMore... |
| `TipAngle[get]` | `unsafeNXOpen.Expression` | Returns the tip angleMore... |
| `UntilSelectedTarget[get]` | `unsafeNXOpen.SelectFace` | Returns the until selected target - this is applicable for general hole and threaded hole typeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.EntityUsageInfo

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57724.html

Represents aNXOpen.GeometricUtilities.EntityUsageInfo

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetDependentFeatures(NXOpen.GeometricUtilities.EntityUsageInfo.StatustypeOfUsage, outNXOpen.Features.Feature[] dependentFeatures, out string [] detailedUsageInfo)` | `unsafe void` | Query the dependent features of this entity.More... |
| `GetOtherDependents(NXOpen.GeometricUtilities.EntityUsageInfo.StatustypeOfUsage, outNXOpen.NXObject[] otherDependents, out string [] detailedUsageInfo)` | `unsafe void` | Query other dependents of this entity.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Entity[get]` | `unsafeNXOpen.DisplayableObject` | Returns the important entity.More... |
| `UsageStatus[get]` | `unsafeNXOpen.GeometricUtilities.EntityUsageInfo.Status` | Returns the usage status of the corresponding entityMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.EntityUsageInfoList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57728.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.EntityUsageInfo[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.EntityUsageInfo@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.EntityUsageInfoobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.EntityUsageInfoobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.EntityUsageInfoobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.EntityUsageInfo` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.EntityUsageInfo[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.EntityUsageInfo@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.EntityUsageInfo[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.EntityUsageInfoobject1,NXOpen.GeometricUtilities.EntityUsageInfoobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.Extend

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57732.html

Represents an extend data

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetValue(string valueExpression)` | `unsafe void` | Set extend value for the following typeNXOpen.GeometricUtilities.Extend.ExtendType.Value.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Target[get, set]` | `unsafeNXOpen.DisplayableObject` | Returns or sets the extend target for the following typesNXOpen.GeometricUtilities.Extend.ExtendType.UntilSelected.More... |
| `TrimType[get, set]` | `unsafeNXOpen.GeometricUtilities.Extend.ExtendType` | Returns or sets the extend typeNXOpen.GeometricUtilities.Extend.ExtendType.More... |
| `Value[get]` | `unsafeNXOpen.Expression` | Returns the extend value for the following typeNXOpen.GeometricUtilities.Extend.ExtendType.Value.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ExtrudeRevolveToolBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57736.html

a class which is a sub-component of BooleanTool

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
| `ToolAxis[get, set]` | `unsafeNXOpen.Axis` | Returns or sets the tool axis used for doing revolveMore... |
| `ToolDirection[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the tool direction used for doing extrudeMore... |
| `ToolSection[get]` | `unsafeNXOpen.Section` | Returns the tool super sectionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.FaceChangeOverflowBehavior

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57740.html

Represents aNXOpen.GeometricUtilities.FaceChangeOverflowBehaviorIt provides several face change options for controlling behavior when a change face overflows an incident face

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
| `FaceChangeOption[get, set]` | `unsafeNXOpen.GeometricUtilities.FaceChangeOverflowBehavior.Option` | Returns or sets the face change option.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.FacePairingBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57744.html

a class which defines face pairing builder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `ExcludeFace(NXOpen.Faceface)` | `unsafe void` | Face that is explicitly selected by the user to be excluded in the search of possible face pairsMore... |
| `IncludeFace(NXOpen.Faceface)` | `unsafe bool` | Face that is explicitly selected by the user to be included in the search of possible face pairsMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AutomaticOffsetOnlyOption[get, set]` | `unsafe bool` | Returns or sets the option to force the creation the mid-surface using the offset method for all automatic face pairsMore... |
| `AutomaticTrimOption[get, set]` | `unsafe bool` | Returns or sets the option to trim all automatic face pairsMore... |
| `CollectorPairList[get]` | `unsafeNXOpen.GeometricUtilities.CollectorPairListBuilder` | Returns theGeometricUtilities.CollectorPairListBuilderfor manual pairingMore... |
| `InputSolidBodies[get]` | `unsafeNXOpen.ScCollector` | Returns the input solid bodies used to find the default face pairsMore... |
| `MergeAngleTolerance[get, set]` | `unsafe double` | Returns or sets the merge angle toleranceMore... |
| `PairingStrategy[get, set]` | `unsafeNXOpen.GeometricUtilities.FacePairingBuilder.PairingStrategyType` | Returns or sets the pairing strategy used by automatic pairsMore... |
| `ThicknessRatio[get, set]` | `unsafe double` | Returns or sets the thickness to solid diagonal length ratio used by the automatic face pair searchMore... |
| `ThicknessValue[get]` | `unsafeNXOpen.Expression` | Returns the thickness value when pairing strategy is set to ThicknessMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.FacePlaneSelectionBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57748.html

Represents aNXOpen.GeometricUtilities.FacePlaneSelectionBuilder

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
| `IsOk[get, set]` | `unsafe bool` | Returns or sets the data OK flagMore... |
| `LimitTopolSwitchFinFlag[get, set]` | `unsafe bool` | Returns or sets the limit edge switch fin flagMore... |
| `PlaneHelpPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the user plane cap help pointMore... |
| `SelectEdge[get]` | `unsafeNXOpen.ScCollector` | Returns the select limit edgeMore... |
| `SelectFace[get]` | `unsafeNXOpen.GeometricUtilities.FaceSetData` | Returns the select faceMore... |
| `SelectPlane[get, set]` | `unsafeNXOpen.Plane` | Returns or sets the select planeMore... |
| `TrimObject[get, set]` | `unsafeNXOpen.GeometricUtilities.FacePlaneSelectionBuilder.TrimObjectType` | Returns or sets the trim objectMore... |
| `UseFaceCapBlend[get, set]` | `unsafe bool` | Returns or sets the use face cap blend flagMore... |
| `UsePlaneCapBlend[get, set]` | `unsafe bool` | Returns or sets the use plane cap blendMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.FacePlaneSelectionBuilderCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57752.html

This class contains the factory methods for creating an FacePlaneSelectionBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Create()` | `unsafeNXOpen.GeometricUtilities.FacePlaneSelectionBuilder` | Creates an FacePlaneSelectionBuilder.More... |
| `Destroy(NXOpen.GeometricUtilities.FacePlaneSelectionBuilderentityBuilderData)` | `unsafe void` | Destroys an FacePlaneSelectionBuilder.More... |
| `ToArray()` | `NXOpen.GeometricUtilities.FacePlaneSelectionBuilder[]` | Returns an array ofNXOpen.GeometricUtilities.FacePlaneSelectionBuilderobjects.More... |
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

## NXOpen.GeometricUtilities.FacePlaneToolBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57756.html

a sub-component of BooleanToolBuilder

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
| `ToolFaces[get]` | `unsafeNXOpen.GeometricUtilities.FaceSetData` | Returns the sets of tool faces or datum planesMore... |
| `ToolPlane[get, set]` | `unsafeNXOpen.Plane` | Returns or sets the new plane created on the fly.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.FaceSetData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57760.html

Represents aNXOpen.GeometricUtilities.FaceSetData

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
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
| `FaceCollector[get]` | `unsafeNXOpen.ScCollector` | Returns the face set collectorMore... |
| `ReverseNormalFlag[get, set]` | `unsafe bool` | Returns or sets the face set reverse direction flagMore... |
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

## NXOpen.GeometricUtilities.FaceSetDataCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57764.html

This class contains the factory methods for creating an FaceSetData

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Create(NXOpen.ScCollectormFaceCollector, bool mReverseNormalFlag)` | `unsafeNXOpen.GeometricUtilities.FaceSetData` | Creates an FaceSetData.More... |
| `ToArray()` | `NXOpen.GeometricUtilities.FaceSetData[]` | Returns an array ofNXOpen.GeometricUtilities.FaceSetDataobjects.More... |
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

## NXOpen.GeometricUtilities.FaceSetOffset

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57768.html

This class represents a face set (collector) offset data

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `FlipDirection()` | `unsafe void` | Flip offset direction.More... |
| `SetOffset(string offsetValue)` | `unsafe void` | Sets the offset distanceMore... |
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
| `FaceCollector[get, set]` | `unsafeNXOpen.ScCollector` | Returns or sets the face collectorMore... |
| `Offset[get]` | `unsafeNXOpen.Expression` | Returns the offset distanceMore... |
| `Collector[get, set]` | `unsafeNXOpen.ScCollector` | Returns or sets the selectionMore... |
| `ItemFlipFlag[get, set]` | `unsafe bool` | Returns or sets the flip flagMore... |
| `ItemIndex[get, set]` | `unsafe int` | Returns or sets the index in the listMore... |
| `ItemValue[get]` | `unsafeNXOpen.Expression` | Returns the expressionMore... |
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

## NXOpen.GeometricUtilities.FaceSetOffsetCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57772.html

This class contains the factory methods for creating an face set offset

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateEmptyFaceSet()` | `unsafeNXOpen.GeometricUtilities.FaceSetOffset` | Creates an empty offset face set, with all parameters set to 0 or a null reference (Nothing in Visual Basic)More... |
| `CreateFaceSet(string offset,NXOpen.ScCollectorfaceCollector, bool flipValue, int index)` | `unsafeNXOpen.GeometricUtilities.FaceSetOffset` | Creates an offset face set.More... |
| `ToArray()` | `NXOpen.GeometricUtilities.FaceSetOffset[]` | Returns an array ofNXOpen.GeometricUtilities.FaceSetOffsetobjects.More... |
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

## NXOpen.GeometricUtilities.FaceSetOffsetList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57776.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.FaceSetOffset[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.FaceSetOffset@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.FaceSetOffsetobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.FaceSetOffsetobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.FaceSetOffsetobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.FaceSetOffset` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.FaceSetOffset[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.FaceSetOffset@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.FaceSetOffset[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.FaceSetOffsetobject1,NXOpen.GeometricUtilities.FaceSetOffsetobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.FeatureOffset

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57780.html

Represents a Offset

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetEndOffset(string valueExpression)` | `unsafe void` | The End OffsetMore... |
| `SetStartOffset(string valueExpression)` | `unsafe void` | The Start OffsetMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `EndOffset[get]` | `unsafeNXOpen.Expression` | Returns the End OffsetMore... |
| `Option[get, set]` | `unsafeNXOpen.GeometricUtilities.Type` | Returns or sets the Offset optionMore... |
| `StartOffset[get]` | `unsafeNXOpen.Expression` | Returns the Start OffsetMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.FeatureOptions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57784.html

Represents various options supported on features

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
| `BodyType[get, set]` | `unsafeNXOpen.GeometricUtilities.FeatureOptions.BodyStyle` | Returns or sets the body typeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.FlowDirection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57788.html

Represents aNXOpen.GeometricUtilities.FlowDirectionAllows user to specify different flow direction to control output surface shape

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
| `FlowDirectionType[get, set]` | `unsafeNXOpen.GeometricUtilities.FlowDirection.Type` | Returns or sets the flow direction type.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.FrameOnPathBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57792.html

Frame on path builder

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
| `AnchorLocation[get, set]` | `unsafeNXOpen.GeometricUtilities.FrameOnPathBuilder.AnchorLocationType` | Returns or sets the anchor locationMore... |
| `AnchorPosition[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the anchor positionMore... |
| `Height[get]` | `unsafeNXOpen.Expression` | Returns the heightMore... |
| `IsApexReversed[get, set]` | `unsafe bool` | Returns or sets the value indicating if apex point is reversedMore... |
| `Length[get]` | `unsafeNXOpen.Expression` | Returns the lengthMore... |
| `Offset[get]` | `unsafeNXOpen.Expression` | Returns the offsetMore... |
| `WScale[get, set]` | `unsafe double` | Returns or sets the width scaleMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.FtmFixedCurvesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57796.html

Represents aNXOpen.GeometricUtilities.FtmFixedCurvesBuilderbuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `UpdateContinuityOnClassAChange(bool classAOption)` | `unsafe void` | Update continuity when Class A option changesMore... |
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
| `FixedCurves[get]` | `unsafeNXOpen.Section` | Returns the fixed curves that define the fixed constraints on the product shapeMore... |
| `FixedCurvesContinuity[get, set]` | `unsafeNXOpen.GeometricUtilities.FtmFixedCurvesBuilder.FixedCurvesContinuityType` | Returns or sets the continuity option for the fixed curves used in the transformation or morphing calculationsMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.FtmFixedCurvesBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57800.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.FtmFixedCurvesBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.FtmFixedCurvesBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.FtmFixedCurvesBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.FtmFixedCurvesBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.FtmFixedCurvesBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.FtmFixedCurvesBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.FtmFixedCurvesBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.FtmFixedCurvesBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.FtmFixedCurvesBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.FtmFixedCurvesBuilderobject1,NXOpen.GeometricUtilities.FtmFixedCurvesBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.FtmTransformCurvesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57804.html

Represents aNXOpen.GeometricUtilities.FtmTransformCurvesBuilderbuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AlignBreakPoints[get, set]` | `unsafe bool` | Returns or sets the option for aligning break points used in the transformation or morphing calculationsMore... |
| `OppositeSense[get, set]` | `unsafe bool` | Returns or sets the option to reverse the OmniCAD pre-determined direction for the transformation start and end curvesMore... |
| `OppositeSide[get, set]` | `unsafe bool` | Returns or sets the option to change the displacements to the opposite side of the transformationMore... |
| `TransformCurvesContinuity[get, set]` | `unsafeNXOpen.GeometricUtilities.FtmTransformCurvesBuilder.TransformCurvesContinuityType` | Returns or sets the continuity option for the transformation start and end curves used in the transformation or morphing calculationsMore... |
| `TransformCurvesMagnitude[get]` | `unsafeNXOpen.Expression` | Returns the magnitude controlled by continuity for the transformation curvesMore... |
| `TransformEndCurves[get]` | `unsafeNXOpen.Section` | Returns the end or target constraint for the product shape in the form of curves used in the transformation or morphing calculationsMore... |
| `TransformStartCurves[get]` | `unsafeNXOpen.Section` | Returns the starting constraint for the product shape in the form of curves used in the transformation or morphing calculationsMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.FtmTransformCurvesBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57808.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.FtmTransformCurvesBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.FtmTransformCurvesBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.FtmTransformCurvesBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.FtmTransformCurvesBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.FtmTransformCurvesBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.FtmTransformCurvesBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.FtmTransformCurvesBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.FtmTransformCurvesBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.FtmTransformCurvesBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.FtmTransformCurvesBuilderobject1,NXOpen.GeometricUtilities.FtmTransformCurvesBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.FtmTransformPointsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57812.html

Represents aNXOpen.GeometricUtilities.FtmTransformPointsBuilderbuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `TransformEndPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the end point that defines the end or target point constraint on the product shapeMore... |
| `TransformStartPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the start point that defines the starting point constraint on the product shapeMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.FtmTransformPointsBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57816.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.FtmTransformPointsBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.FtmTransformPointsBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.FtmTransformPointsBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.FtmTransformPointsBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.FtmTransformPointsBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.FtmTransformPointsBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.FtmTransformPointsBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.FtmTransformPointsBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.FtmTransformPointsBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.FtmTransformPointsBuilderobject1,NXOpen.GeometricUtilities.FtmTransformPointsBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.GeneralPattern

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57820.html

the General pattern definition

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
| `FromLocationCsys2d[get]` | `unsafeNXOpen.SelectNXObject` | Returns the from location 2d csysMore... |
| `FromLocationCsys3d[get, set]` | `unsafeNXOpen.CoordinateSystem` | Returns or sets the from location 3d csysMore... |
| `FromLocationPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the from location pointMore... |
| `FromLocationType[get, set]` | `unsafeNXOpen.GeometricUtilities.GeneralPattern.FromLocationOptions` | Returns or sets the from location typeMore... |
| `ToCsysList[get]` | `unsafeNXOpen.SelectCoordinateSystemList` | Returns the to csys listMore... |
| `ToPoints[get]` | `unsafeNXOpen.Section` | Returns the to pointsMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.GeometryLocationData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57824.html

Represents aNXOpen.GeometricUtilities.GeometryLocationData

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
| `Csys[get]` | `unsafeNXOpen.SelectObject` | Returns the csysMore... |
| `EntityType[get, set]` | `unsafeNXOpen.GeometricUtilities.GeometryLocationData.EntityTypes` | Returns or sets the typeMore... |
| `Point[get, set]` | `unsafeNXOpen.Point` | Returns or sets the pointMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.GeometryLocationDataCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57828.html

This class contains the factory methods for creating GeometryLocationData

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateGeometryLocationData()` | `unsafeNXOpen.GeometricUtilities.GeometryLocationData` | Creates geometry location data.More... |
| `ToArray()` | `NXOpen.GeometricUtilities.GeometryLocationData[]` | Returns an array ofNXOpen.GeometricUtilities.GeometryLocationDataobjects.More... |
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

## NXOpen.GeometricUtilities.HelixPattern

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57832.html

the Helix pattern definition

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
| `AnglePitch[get]` | `unsafeNXOpen.Expression` | Returns the angle pitch expression for the Helix type patternMore... |
| `CountOfInstances[get]` | `unsafeNXOpen.Expression` | Returns the count of instances for the Helix type patternMore... |
| `DirectionType[get, set]` | `unsafeNXOpen.GeometricUtilities.HelixPattern.DirectionTypes` | Returns or sets the type of helix direction methodMore... |
| `DistancePitch[get]` | `unsafeNXOpen.Expression` | Returns the distance pitch expression for the Helix type patternMore... |
| `HelixPitch[get]` | `unsafeNXOpen.Expression` | Returns the helix pitch expression for the Helix type patternMore... |
| `HelixSpan[get]` | `unsafeNXOpen.Expression` | Returns the helix span expression for the Helix type patternMore... |
| `NumberOfTurns[get]` | `unsafeNXOpen.Expression` | Returns the number of turns for the Helix type patternMore... |
| `RotationAxis[get, set]` | `unsafeNXOpen.Axis` | Returns or sets the rotation axis for the pattern.More... |
| `SizeOption[get, set]` | `unsafeNXOpen.GeometricUtilities.HelixPattern.SizeOptions` | Returns or sets the Helix size optionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.HorizontalReference

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57836.html

the horizontal reference vector definition

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
| `Flip[get, set]` | `unsafe bool` | Returns or sets the 2D Selection flip attribute.More... |
| `HorizontalRefObject[get]` | `unsafeNXOpen.SelectNXObject` | Returns the direction object.More... |
| `HorizontalRefVector[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the horizontal reference vectorMore... |
| `RotationAngle[get]` | `unsafeNXOpen.Expression` | Returns the rotation angle wrt horizontal reference directionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.IComponentBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57840.html

Represents a component contained in a builder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Validate()` | `bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |


---

## NXOpen.GeometricUtilities.InstanceEditedExpressionItem

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57844.html

edited value of one master expression of the input object(s) being patterned

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
| `MasterExpression[get]` | `unsafeNXOpen.Expression` | Returns the master expressionMore... |
| `ValueExpression[get]` | `unsafeNXOpen.Expression` | Returns the edited value expression for the master expressionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.InstanceEditedExpressionItemList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57848.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.InstanceEditedExpressionItem[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.InstanceEditedExpressionItem@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.InstanceEditedExpressionItemobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.InstanceEditedExpressionItemobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.InstanceEditedExpressionItemobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.InstanceEditedExpressionItem` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.InstanceEditedExpressionItem[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.InstanceEditedExpressionItem@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.InstanceEditedExpressionItem[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.InstanceEditedExpressionItemobject1,NXOpen.GeometricUtilities.InstanceEditedExpressionItemobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.InstanceEditedExpressionsList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57852.html

list ofNXOpen.GeometricUtilities.InstanceEditedExpressionItemobjects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `EditInstanceExpression()` | `unsafeNXOpen.GeometricUtilities.InstanceEditedExpressionItem` | This is the default creator forNXOpen.GeometricUtilities.InstanceEditedExpressionItem.More... |
| `EditInstanceExpression(NXOpen.ExpressionmasterExpression,NXOpen.ExpressioninstanceExpression)` | `unsafeNXOpen.GeometricUtilities.InstanceEditedExpressionItem` | This is the creator forNXOpen.GeometricUtilities.InstanceEditedExpressionItemwhich should be used.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `List[get]` | `unsafeNXOpen.GeometricUtilities.InstanceEditedExpressionItemList` | Returns the list ofNXOpen.GeometricUtilities.InstanceEditedExpressionItemobjects.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.InteractiveSectionBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57856.html

Represents aNXOpen.GeometricUtilities.InteractiveSectionBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `AppendPlane(NXOpen.Point3dpoint1,NXOpen.Point3dpoint2,NXOpen.Point3dorigin,NXOpen.Vector3dnormal)` | `unsafe void` | Appends a planeMore... |
| `DeleteLast()` | `unsafe void` | Deletes last point or the plane createdMore... |
| `GetNthPlane(int index)` | `unsafeNXOpen.GeometricUtilities.SectionPlaneData` | Get the Nth planeMore... |
| `GetNumPlanes()` | `unsafe int` | Get the number of planesMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |


---

## NXOpen.GeometricUtilities.LatticeItemBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57860.html

This object contains each 3MF export option within the LatticeItemList

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Destroy()` | `unsafe void` | Destroys this GeometricUtilities.LatticeItemBuilderMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `ClippingBody[get]` | `unsafeNXOpen.SelectBodyList` | Returns the body being clipped with 3MF Export.More... |
| `ClippingMode[get, set]` | `unsafeNXOpen.GeometricUtilities.LatticeItemBuilder.ClippingModeTypes` | Returns or sets the clipping mode option for the lattice body in 3MF export.More... |
| `ExportMode[get, set]` | `unsafeNXOpen.GeometricUtilities.LatticeItemBuilder.ExportTypes` | Returns or sets the export mode for the lattice body in 3MF export.More... |
| `LatticeBodies[get]` | `unsafeNXOpen.SelectBodyList` | Returns this object contains the lattice bodies within the listMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.LatticeItemBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57864.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.LatticeItemBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.LatticeItemBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.LatticeItemBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.LatticeItemBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.LatticeItemBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.LatticeItemBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.LatticeItemBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.LatticeItemBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.LatticeItemBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.LatticeItemBuilderobject1,NXOpen.GeometricUtilities.LatticeItemBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.LatticeItemListBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57868.html

Represents a LatticeItemList

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateLatticeItemBuilder()` | `unsafeNXOpen.GeometricUtilities.LatticeItemBuilder` | Creates a GeometricUtilities.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `LatticeItemList[get]` | `unsafeNXOpen.GeometricUtilities.LatticeItemBuilderList` | Returns the section defining the lattice body options.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.LawBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57872.html

Represents a LawBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetSpineIntoBuilder(NXOpen.Sectionspine)` | `unsafe void` | Sets the spine dynamically into builderMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AlongSpineData[get]` | `unsafeNXOpen.GeometricUtilities.AlongSpineBuilder` | Returns the linear or cubic along spine law.More... |
| `BaseLine[get]` | `unsafeNXOpen.SelectLine` | Returns the base line.More... |
| `EndValue[get]` | `unsafeNXOpen.Expression` | Returns the end value.More... |
| `Function[get, set]` | `unsafe string` | Returns or sets the function.More... |
| `IsSimpleCubicAlongSpine[get, set]` | `unsafe bool` | Returns or sets a value indicating ifNXOpen.GeometricUtilities.LawBuilder.Type.CubicAlongSpineis using simple cubic interpolation.More... |
| `LawCurve[get]` | `unsafeNXOpen.Section` | Returns the law curve.More... |
| `LawCurveOption[get, set]` | `unsafeNXOpen.GeometricUtilities.LawBuilder.RetainLawCurveOption` | Returns or sets the option to retain law curve.More... |
| `LawType[get, set]` | `unsafeNXOpen.GeometricUtilities.LawBuilder.Type` | Returns or sets the law typeMore... |
| `MultiTransitionLaw[get]` | `unsafeNXOpen.GeometricUtilities.MultiTransitionLawBuilder` | Returns the multi transition law.More... |
| `NonInflectingLaw[get]` | `unsafeNXOpen.GeometricUtilities.NonInflectingLawBuilder` | Returns the non inflecting law.More... |
| `Parameter[get, set]` | `unsafe string` | Returns or sets the parameter.More... |
| `ReverseDirection[get, set]` | `unsafe bool` | Returns or sets the reverse direction.More... |
| `SShapedLaw[get]` | `unsafeNXOpen.GeometricUtilities.SShapedLawBuilder` | Returns the s-shaped law.More... |
| `StartValue[get]` | `unsafeNXOpen.Expression` | Returns the start value.More... |
| `Value[get]` | `unsafeNXOpen.Expression` | Returns the constant value.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.LengthLimitPointBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57876.html

Represents aNXOpen.GeometricUtilities.LengthLimitPointBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Destroy()` | `unsafe void` | Destructor forNXOpen.GeometricUtilities.LengthLimitPointBuilderMore... |
| `FlipPath(bool isStartOfEdge)` | `unsafe void` | Flip the builder path forNXOpen.GeometricUtilities.LengthLimitPointBuilderMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `OnPathDim[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns theNXOpen.GeometricUtilities.LengthLimitPointBuildersubobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.LengthLimitsListBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57880.html

Represents aNXOpen.GeometricUtilities.LengthLimitsListBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreatePointFacePlaneSelectionBuilder(NXOpen.TaggedObjectseed)` | `unsafeNXOpen.GeometricUtilities.PointFacePlaneSelectionBuilder` | Creates a FacePlaneSelectionBuilderMore... |
| `DestroyPointFacePlaneSelectionBuilder(NXOpen.GeometricUtilities.PointFacePlaneSelectionBuilderentityBuilderData)` | `unsafe void` | Destroys a FacePlaneSelectionBuilderMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CapsList[get]` | `unsafeNXOpen.GeometricUtilities.PointFacePlaneSelectionBuilderList` | Returns the list of lenght limit data objectsMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.Limits

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57884.html

Represents a limits data

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
| `EndExtend[get]` | `unsafeNXOpen.GeometricUtilities.Extend` | Returns the end extend builderMore... |
| `StartExtend[get]` | `unsafeNXOpen.GeometricUtilities.Extend` | Returns the start extend builderMore... |
| `SymmetricOption[get, set]` | `unsafe bool` | Returns or sets the symmetric optionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.LinearLimits

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57888.html

Represents a limits data


---

## NXOpen.GeometricUtilities.LocalUntrimBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57892.html

Represents aNXOpen.GeometricUtilities.LocalUntrimBuilderbuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CleanUpFeaturesCreated()` | `unsafe void` | Cleans up the features created by the selecting face call back.More... |
| `CreateCopyFace()` | `unsafe void` | Creates the extracted face when the flag of Edit a Copy is turned on or a solid body face is selected.More... |
| `CreateProductBoundingBox()` | `unsafe void` | Creates the product initial bounding box.More... |
| `SetCurrentFeature(NXOpen.Features.Feature@object)` | `unsafe void` | Records the current feature before constructing the dialog.More... |
| `SetInitialDistanceValue(double [] distanceValues)` | `unsafe void` | Sets the initial distance value.More... |
| `SetLimitChangeValue(int limitType)` | `unsafe void` | Sets the limit boundary handle type.More... |
| `SetOriginalFace(NXOpen.FaceoriginalFace)` | `unsafe void` | Sets the originally selected face.More... |
| `UpdateBoundingBox()` | `unsafe void` | Updates the bounding box when changing the distance value.More... |
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
| `EdgeCollector[get]` | `unsafeNXOpen.ScCollector` | Returns the edges on the face to delete.More... |
| `EditCopy[get, set]` | `unsafe bool` | Returns or sets the flag to indicate whether to edit a copied face or not.More... |
| `Face[get]` | `unsafeNXOpen.SelectFace` | Returns the tool object to split the target body.More... |
| `RemoveBoundary[get, set]` | `unsafe bool` | Returns or sets the flag to indicate whether to remove the face boundary or not.More... |
| `UEndDistance[get]` | `unsafeNXOpen.Expression` | Returns the U end distance.More... |
| `UEndLimit[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the region limit of U end.More... |
| `UStartDistance[get]` | `unsafeNXOpen.Expression` | Returns the U start distance.More... |
| `UStartLimit[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the region limit of U start.More... |
| `VEndDistance[get]` | `unsafeNXOpen.Expression` | Returns the V end distance.More... |
| `VEndLimit[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the region limit of V end.More... |
| `VStartDistance[get]` | `unsafeNXOpen.Expression` | Returns the V start distance.More... |
| `VStartLimit[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the region limit of V start.More... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.LocalUntrimManager

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57896.html

Provides create builder methods for LocalUntrimBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateBuilder()` | `unsafeNXOpen.GeometricUtilities.LocalUntrimBuilder` | Creates local untrim and extend builder.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.MatchSurfaceBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57900.html

Represents aNXOpen.GeometricUtilities.MatchSurfaceBuilderbuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AngleTolerance[get, set]` | `unsafe double` | Returns or sets the angle toleranceMore... |
| `Constraint[get, set]` | `unsafeNXOpen.GeometricUtilities.MatchSurfaceBuilder.MatchConstaint` | Returns or sets the continuity type for matchingMore... |
| `DistanceTolerance[get, set]` | `unsafe double` | Returns or sets the distance toleranceMore... |
| `EditEdge[get]` | `unsafeNXOpen.SelectEdge` | Returns the selected edge for matchingMore... |
| `EndToEnd[get, set]` | `unsafe bool` | Returns or sets the option to match end-to-end, between the end of edit edge and the reference egde or curveMore... |
| `KeepSheet[get, set]` | `unsafe bool` | Returns or sets the option to keep original sheetMore... |
| `MatchExact[get, set]` | `unsafe bool` | Returns or sets the option to match exact, between the end of edit edge and the reference egde or curveMore... |
| `Reference[get]` | `unsafeNXOpen.SelectEdge` | Returns the selected reference edge or curveMore... |
| `ReferenceFace[get]` | `unsafeNXOpen.SelectFace` | Returns the selected face for reference curveMore... |
| `RegionLimit[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the distance limit of deformation regionMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.MiddleHoleData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57904.html

Represents aNXOpen.GeometricUtilities.MiddleHoleData

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
| `BooleanOperation[get]` | `unsafeNXOpen.GeometricUtilities.BooleanOperation` | Returns the boolean operationMore... |
| `EndChamferAngle[get]` | `unsafeNXOpen.Expression` | Returns the end chamfer angleMore... |
| `EndChamferEnabled[get, set]` | `unsafe bool` | Returns or sets the end chamfer enabledMore... |
| `EndChamferOffset[get]` | `unsafeNXOpen.Expression` | Returns the end chamfer offsetMore... |
| `FitOption[get, set]` | `unsafe string` | Returns or sets the fit optionMore... |
| `HoleDiameter[get]` | `unsafeNXOpen.Expression` | Returns the hole diameterMore... |
| `MatchDimOfStartHole[get, set]` | `unsafe bool` | Returns or sets the match dim of start holeMore... |
| `StartChamferAngle[get]` | `unsafeNXOpen.Expression` | Returns the start chamfer angleMore... |
| `StartChamferEnabled[get, set]` | `unsafe bool` | Returns or sets the start chamfer enabledMore... |
| `StartChamferOffset[get]` | `unsafeNXOpen.Expression` | Returns the start chamfer offsetMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.MirrorPattern

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57908.html

the Mirror pattern definition

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
| `ExistingPlane[get]` | `unsafeNXOpen.SelectISurface` | Returns the Existing Mirror PlaneMore... |
| `NewPlane[get, set]` | `unsafeNXOpen.Plane` | Returns or sets the new planeMore... |
| `PlaneOption[get, set]` | `unsafeNXOpen.GeometricUtilities.MirrorPattern.PlaneOptions` | Returns or sets the plane optionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ModlAlongCurveAngle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57912.html

This classNXOpen.GeometricUtilities.ModlAlongCurveAnglerepresents motion type in ModlMotion

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
| `AlongCurve[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the value of transform.More... |
| `AlongCurveAngle[get]` | `unsafeNXOpen.Expression` | Returns the value of angular transform.More... |
| `Curve[get]` | `unsafeNXOpen.SelectCurve` | Returns the curve on which doing the transform.More... |
| `ReverseCurveDirection[get, set]` | `unsafe bool` | Returns or sets whether the direction of the curve to determine the transform should be reversed or not.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ModlDistanceAngle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57916.html

Represents aNXOpen.GeometricUtilities.ModlDistanceAngle

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
| `Angle[get]` | `unsafeNXOpen.Expression` | Returns the value of angular transform.More... |
| `AngularDirection[get, set]` | `unsafeNXOpen.Vector3d` | Returns or sets the direction of angular dimensions.More... |
| `Distance[get]` | `unsafeNXOpen.Expression` | Returns the distance of linear transform.More... |
| `LinearAxis[get, set]` | `unsafeNXOpen.Axis` | Returns or sets the linear axis of distance.More... |
| `OrientXpress[get]` | `unsafeNXOpen.GeometricUtilities.OrientXpressBuilder` | Returns the orientXpress.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ModlMotion

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57920.html

Represents aNXOpen.GeometricUtilities.ModlMotion

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetTransformation(out double [] transformation)` | `unsafe void` | The 4x4 transformation matrixMore... |
| `ResetMotionToThreeDimensions()` | `unsafe void` | Reset motion to three dimensionsMore... |
| `SetDependentView(NXOpen.Viewview)` | `unsafe void` | Set the view for view dependent drafting objectsMore... |
| `SetMotionToTwoDimensions(NXOpen.Planeplane)` | `unsafe void` | Set motion to two dimensions along the given planeMore... |
| `SetUpdateOption(NXOpen.SmartObject.UpdateOptionoption)` | `unsafe void` | Set the update option for defining the update behavior for the object.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AlignVector[get, set]` | `unsafeNXOpen.Axis` | Returns or sets the axis ofNXOpen.GeometricUtilities.ModlMotion.Options.AlignAxisVectormotion option.More... |
| `AlongCurveAngle[get]` | `unsafeNXOpen.GeometricUtilities.ModlAlongCurveAngle` | Returns the alongCurveAngle ofNXOpen.GeometricUtilities.ModlMotion.Options.AlongCurveAnglemotion option.More... |
| `Angle[get]` | `unsafeNXOpen.Expression` | Returns the angle ofNXOpen.GeometricUtilities.ModlMotion.Options.Anglemotion option.More... |
| `AngularAxis[get, set]` | `unsafeNXOpen.Axis` | Returns or sets the angular axis ofNXOpen.GeometricUtilities.ModlMotion.Options.Anglemotion option.More... |
| `DeltaEnum[get, set]` | `unsafeNXOpen.GeometricUtilities.ModlMotion.Delta` | Returns or sets the delta enumMore... |
| `DeltaX[get, set]` | `unsafe double` | Returns or sets the delta xMore... |
| `DeltaXc[get]` | `unsafeNXOpen.Expression` | Returns the delta xcMore... |
| `DeltaY[get, set]` | `unsafe double` | Returns or sets the delta yMore... |
| `DeltaYc[get]` | `unsafeNXOpen.Expression` | Returns the delta ycMore... |
| `DeltaZ[get, set]` | `unsafe double` | Returns or sets the delta zMore... |
| `DeltaZc[get]` | `unsafeNXOpen.Expression` | Returns the delta zcMore... |
| `DistanceAngle[get]` | `unsafeNXOpen.GeometricUtilities.ModlDistanceAngle` | Returns the distance-angle ofNXOpen.GeometricUtilities.ModlMotion.Options.DistanceAnglemotion option.More... |
| `DistanceBetweenPointsDistance[get]` | `unsafeNXOpen.Expression` | Returns the distance ofNXOpen.GeometricUtilities.ModlMotion.Options.DistanceBetweenPointsmotion option.More... |
| `DistanceBetweenPointsMeasurePoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the measure point ofNXOpen.GeometricUtilities.ModlMotion.Options.DistanceBetweenPointsmotion option.More... |
| `DistanceBetweenPointsOriginDistance[get]` | `unsafeNXOpen.Expression` | Returns the distance between origin point and face ofNXOpen.GeometricUtilities.ModlMotion.Options.DistanceBetweenPointsmotion option.More... |
| `DistanceBetweenPointsOriginPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the origin point ofNXOpen.GeometricUtilities.ModlMotion.Options.DistanceBetweenPointsmotion option.More... |
| `DistanceBetweenPointsVector[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the direction ofNXOpen.GeometricUtilities.ModlMotion.Options.DistanceBetweenPointsmotion option.More... |
| `DistanceValue[get]` | `unsafeNXOpen.Expression` | Returns the distance value ofNXOpen.GeometricUtilities.ModlMotion.Options.Distancemotion option.More... |
| `DistanceVector[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the direction ofNXOpen.GeometricUtilities.ModlMotion.Options.Distancemotion option.More... |
| `EndPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the end point ofNXOpen.GeometricUtilities.ModlMotion.Options.RotateByThreePointsmotion option.More... |
| `FromCsys[get, set]` | `unsafeNXOpen.CoordinateSystem` | Returns or sets the "from csys" ofNXOpen.GeometricUtilities.ModlMotion.Options.CsysToCsysmotion option .More... |
| `FromPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the "from point" ofNXOpen.GeometricUtilities.ModlMotion.Options.PointToPointmotion option.More... |
| `ManipulatorMatrix[get, set]` | `unsafeNXOpen.Matrix3x3` | Returns or sets the matrix of manipulator forNXOpen.GeometricUtilities.ModlMotion.Options.Dynamicmotion option.More... |
| `ManipulatorOrigin[get, set]` | `unsafeNXOpen.Point3d` | Returns or sets the origin point of manipulator forNXOpen.GeometricUtilities.ModlMotion.Options.Dynamicmotion option.More... |
| `MoveHandle[get, set]` | `unsafe bool` | Returns or sets the move handle toggle ofNXOpen.GeometricUtilities.ModlMotion.Options.Dynamicmotion option.More... |
| `Option[get, set]` | `unsafeNXOpen.GeometricUtilities.ModlMotion.Options` | Returns or sets the options.More... |
| `OrientXpress[get]` | `unsafeNXOpen.GeometricUtilities.OrientXpressBuilder` | Returns the orientXpress.More... |
| `RadialAxis[get, set]` | `unsafeNXOpen.Axis` | Returns or sets the axis ofNXOpen.GeometricUtilities.ModlMotion.Options.RadialDistancemotion option.More... |
| `RadialDistance[get]` | `unsafeNXOpen.Expression` | Returns the distance value ofNXOpen.GeometricUtilities.ModlMotion.Options.RadialDistancemotion option.More... |
| `RadialMeasurePoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the measure point ofNXOpen.GeometricUtilities.ModlMotion.Options.RadialDistancemotion option.More... |
| `RadialOriginDistance[get]` | `unsafeNXOpen.Expression` | Returns the distance between axis point and face ofNXOpen.GeometricUtilities.ModlMotion.Options.RadialDistancemotion option.More... |
| `RotateVector[get, set]` | `unsafeNXOpen.Axis` | Returns or sets the direction ofNXOpen.GeometricUtilities.ModlMotion.Options.RotateByThreePointsmotion option.More... |
| `StartPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the start point ofNXOpen.GeometricUtilities.ModlMotion.Options.RotateByThreePointsmotion option.More... |
| `TempManipulatorOrigin[get, set]` | `unsafeNXOpen.Point3d` | Returns or sets the temporary origin point of manipulator forNXOpen.GeometricUtilities.ModlMotion.Options.Dynamicmotion option.More... |
| `ToCsys[get, set]` | `unsafeNXOpen.CoordinateSystem` | Returns or sets the "to csys" where object is moved for motion optionNXOpen.GeometricUtilities.ModlMotion.Options.CsysToCsys.More... |
| `ToPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the point where object is moved for motion optionNXOpen.GeometricUtilities.ModlMotion.Options.PointToPointMore... |
| `ToVector[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the vector ofNXOpen.GeometricUtilities.ModlMotion.Options.AlignAxisVectormotion option.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.MovePoleBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57924.html

This class manages the control poles movements for a surface or curve

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
| `ControlPoleManager[get]` | `unsafeNXOpen.GeometricUtilities.ControlPoleManagerData` | Returns the control pole managerMore... |
| `DegreesAndPatches[get]` | `unsafeNXOpen.GeometricUtilities.DegreesAndSegmentsOrPatchesBuilder` | Returns the degrees and patchesMore... |
| `Entity[get, set]` | `unsafeNXOpen.NXObject` | Returns or sets the entityMore... |
| `MoveMethod[get, set]` | `unsafeNXOpen.GeometricUtilities.MovePoleBuilder.MoveMethodType` | Returns or sets the control pole move methodMore... |
| `Plane[get, set]` | `unsafeNXOpen.Plane` | Returns or sets the planeMore... |
| `Vector[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the vectorMore... |
| `WCSDirection[get, set]` | `unsafeNXOpen.GeometricUtilities.MovePoleBuilder.WCSDirectionType` | Returns or sets the fixed directionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.MultiDraft

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57928.html

Represents a multi-draft

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetAngleOption()` | `unsafeNXOpen.GeometricUtilities.MultiDraft.AngleOption` | Returns the draft angle optionMore... |
| `GetDrafts(NXOpen.Sectionsection)` | `unsafeNXOpen.Features.EmbossTaper[]` | Return all the draftsMore... |
| `SetAngleOption(NXOpen.GeometricUtilities.MultiDraft.AngleOptiontype)` | `unsafe void` | Sets the draft angle optionMore... |
| `SetDraftAngle(string draftAngle)` | `unsafe void` | Sets the draft angleMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `BackDraftAngle[get]` | `unsafeNXOpen.Expression` | Returns the back draft angle.More... |
| `DraftOption[get, set]` | `unsafeNXOpen.GeometricUtilities.SimpleDraft.SimpleDraftType` | Returns or sets the draft typeMore... |
| `FrontDraftAngle[get]` | `unsafeNXOpen.Expression` | Returns the front draft angle.More... |
| `DraftAngle[get]` | `unsafeNXOpen.Expression` | Returns the draft angleMore... |
| `DraftType[get, set]` | `unsafeNXOpen.GeometricUtilities.SimpleDraft.SimpleDraftType` | Returns or sets the simple draft typeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.MultiTransitionLawBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57932.html

Represents multiple transition law

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateNode()` | `unsafeNXOpen.GeometricUtilities.TransitionLawNodeBuilder` | Creates a new law nodeMore... |
| `UpdateSpine()` | `unsafe void` | Update the builder based on current spineMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `NodeList[get]` | `unsafeNXOpen.GeometricUtilities.TransitionLawNodeBuilderList` | Returns the list of law nodes.More... |
| `Spine[get]` | `unsafeNXOpen.Section` | Returns the spineMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.NestModuleBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57940.html

Represents aNXOpen.GeometricUtilities.NestModuleBuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `DestinationModule[get]` | `unsafeNXOpen.Features.SelectFeature` | Returns the destination moduleMore... |
| `ModuleToNest[get]` | `unsafeNXOpen.Features.SelectFeature` | Returns the module to nestMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.NonInflectingLawBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57944.html

Represents a non-inflecting law

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `UpdateSpine()` | `unsafe void` | Update the builder based on current spineMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `EndNode[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimWithValueBuilder` | Returns the end nodeMore... |
| `MiddleNode[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimWithValueBuilder` | Returns the middle nodeMore... |
| `Spine[get]` | `unsafeNXOpen.Section` | Returns the SpineMore... |
| `StartNode[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimWithValueBuilder` | Returns the start nodeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.OmnicadManager

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57948.html

Represents a manager for creating builder objects for OmniCAD Free Transformer

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateFtmFixedCurvesBuilder()` | `unsafeNXOpen.GeometricUtilities.FtmFixedCurvesBuilder` | Creates Free Transformer fixed curves builder.More... |
| `CreateFtmTransformCurvesBuilder()` | `unsafeNXOpen.GeometricUtilities.FtmTransformCurvesBuilder` | Creates Free Transformer transform curves builder.More... |
| `CreateFtmTransformPointsBuilder()` | `unsafeNXOpen.GeometricUtilities.FtmTransformPointsBuilder` | Creates Free Transformer transform points builder.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.OnPathDimWithValueBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57956.html

Represents aNXOpen.GeometricUtilities.OnPathDimWithValueBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `FindObject(string journalIdentifier)` | `unsafeNXOpen.INXObject` | Finds theNXOpen.NXObjectwith the given identifier as recorded in a journal.More... |
| `InheritLocation(NXOpen.GeometricUtilities.OnPathDimWithValueBuildersourceBuilder)` | `unsafe void` | Inherits location data of aNXOpen.GeometricUtilities.OnPathDimWithValueBuilderobjectMore... |
| `InheritValue(NXOpen.GeometricUtilities.OnPathDimWithValueBuildersourceBuilder)` | `unsafe void` | Inherits value of aNXOpen.GeometricUtilities.OnPathDimWithValueBuilderobjectMore... |
| `Print()` | `unsafe void` | Prints a representation of this object to the system log file.More... |
| `SetName(string name)` | `unsafe void` | Sets the custom name of the object.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `IsOccurrence[get]` | `unsafe bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `unsafe string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Location[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the location on pathMore... |
| `Name[get]` | `unsafe string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `unsafeNXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `unsafeNXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `unsafeNXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |
| `Value[get]` | `unsafeNXOpen.Expression` | Returns the value expressionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |
| `IsOccurrence[get]` | `bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Name[get]` | `string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `NXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `NXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `NXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |


---

## NXOpen.GeometricUtilities.OnPathDimensionBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57952.html

Builds an on-path dimension

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Update(NXOpen.GeometricUtilities.OnPathDimensionBuilder.UpdateReasonupdateReason)` | `unsafe void` | Updates this object if the path or through point location has changed.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Expression[get]` | `unsafeNXOpen.Expression` | Returns the expression for the value of the dimensionMore... |
| `IsFlipped[get, set]` | `unsafe bool` | Returns or sets a flag indicating whether the length along the path is evaluated starting from the end point of path instead of the start point of the pathMore... |
| `IsParameterUsed[get, set]` | `unsafe bool` | Returns or sets a flag indicating whether the expression is in terms of the mathematical parameter of the path (is_parameter_used = true) or in terms of its arclength (is_parameter_used = false).More... |
| `IsPercentUsed[get, set]` | `unsafe bool` | Returns or sets a flag indicating whether the expression represents the percentage along the path.More... |
| `Path[get]` | `unsafeNXOpen.SelectObject` | Returns the path that the dimension is evaluated on.More... |
| `ThroughPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the through pointMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.OnPathDistancePatternSpacing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57960.html

defines the various ways pattern instances can be spaced within the pattern, particularly in the context of the PatternDefinition class

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `OnPathPitchDistance[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the distance for the spacing of the pattern from one instance to the next.More... |
| `OnPathSpanDistance[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the distance for the spacing of the pattern for the entire pattern.More... |
| `NCopies[get]` | `unsafeNXOpen.Expression` | Returns the number of copies the pattern will generated in this directionMore... |
| `Points[get]` | `unsafeNXOpen.Section` | Returns the section with points to be used in this directionMore... |
| `SpaceType[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternSpacing.SpacingType` | Returns or sets the type of spacing to be used by the patternMore... |
| `SpacingsList[get]` | `unsafeNXOpen.GeometricUtilities.PatternSpacingsList` | Returns the list of spacings (Expression or OnPathDimBuilder) to be used in this directionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.OrientXpressBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57968.html

Represent the OrientXpress block

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AxisOption[get, set]` | `unsafeNXOpen.GeometricUtilities.OrientXpressBuilder.Axis` | Returns or sets the orientXpress active axis optionMore... |
| `Csys[get, set]` | `unsafeNXOpen.CoordinateSystem` | Returns or sets the orientXpress reference csys when reference option is set to csysMore... |
| `FixedCsys[get, set]` | `unsafeNXOpen.NXObject` | Returns or sets the orientXpress fixed csys when reference option is set to fixed csysMore... |
| `PlaneOption[get, set]` | `unsafeNXOpen.GeometricUtilities.OrientXpressBuilder.Plane` | Returns or sets the orientXpress active plane optionMore... |
| `ProgramDefinedCsys[get, set]` | `unsafeNXOpen.NXObject` | Returns or sets the orientXpress program defined csys when reference option is set to program defined csysMore... |
| `ReferenceOption[get, set]` | `unsafeNXOpen.GeometricUtilities.OrientXpressBuilder.Reference` | Returns or sets the orientXpress reference coordinate systemMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.OrientationMethodBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57964.html

Represents aNXOpen.GeometricUtilities.OrientationMethodBuilder

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
| `AngularLaw[get]` | `unsafeNXOpen.GeometricUtilities.LawBuilder` | Returns the angular law.More... |
| `Faces[get]` | `unsafeNXOpen.ScCollector` | Returns the faces that provide normal direction for alignment of second axis of local coordinate system.More... |
| `NormalFaceList[get]` | `unsafeNXOpen.SelectFaceList` | Returns the normal face list.More... |
| `OrientationCurve[get]` | `unsafeNXOpen.Section` | Returns the orientation curve.More... |
| `OrientationOption[get, set]` | `unsafeNXOpen.GeometricUtilities.OrientationMethodBuilder.OrientationOptions` | Returns or sets the orientation option.More... |
| `OrientationPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the orientation point.More... |
| `OrientationVector[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the orientation vector.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ParentEquivalencyMap

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57972.html

Represents aNXOpen.GeometricUtilities.ParentEquivalencyMap

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetEntitiesFromCurrentObject(outNXOpen.DisplayableObject[] entitiesFromCurrentObject)` | `unsafe void` | Get the mapped entities from the current object.More... |
| `GetEntitiesFromReplacementObject(outNXOpen.DisplayableObject[] entitiesFromReplacementObject)` | `unsafe void` | Get the mapped entities from the replacement objectMore... |
| `SetMappedEntities(NXOpen.DisplayableObject[] oldEntities,NXOpen.DisplayableObject[] newEntities)` | `unsafe void` | Set externally mapped entitiesMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `MapStatus[get, set]` | `unsafeNXOpen.GeometricUtilities.ParentEquivalencyMap.Status` | Returns or sets the map statusMore... |
| `MapType[get, set]` | `unsafeNXOpen.GeometricUtilities.ParentEquivalencyMap.Type` | Returns or sets the map typeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ParentEquivalencyMapList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57976.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.ParentEquivalencyMap[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.ParentEquivalencyMap@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.ParentEquivalencyMapobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.ParentEquivalencyMapobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.ParentEquivalencyMapobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.ParentEquivalencyMap` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.ParentEquivalencyMap[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.ParentEquivalencyMap@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.ParentEquivalencyMap[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.ParentEquivalencyMapobject1,NXOpen.GeometricUtilities.ParentEquivalencyMapobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.PartModuleInputBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57980.html

Represents aNXOpen.GeometricUtilities.PartModuleInputBuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `DefineSharedBodyInput[get, set]` | `unsafe bool` | Returns or sets the shared body inputs option.More... |
| `InputReferences[get]` | `unsafeNXOpen.Features.PartGeometryCopyBuilder` | Returns the part module input dataMore... |
| `ModifiableGeometry[get]` | `unsafeNXOpen.ScCollectorList` | Returns the faces/edges specified as modifiable geometryMore... |
| `ModifiableGeometryOption[get, set]` | `unsafeNXOpen.GeometricUtilities.PartModuleInputBuilder.ModifiableGeometryOptions` | Returns or sets the Modifiable Geometry optionMore... |
| `SharedBodyInput[get]` | `unsafeNXOpen.Features.PartGeometryCopyBuilder` | Returns the bodies for part module shared bodyMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PartModuleOutputBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57984.html

Represents aNXOpen.GeometricUtilities.PartModuleOutputBuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Activate[get, set]` | `unsafe bool` | Returns or sets the option indicating whether the part module is to be activated.More... |
| `Deactivate[get, set]` | `unsafe bool` | Returns or sets the option indicating whether the part module is to be deactivated.More... |
| `OutputReferences[get]` | `unsafeNXOpen.GeometricUtilities.PartModuleReferencesBuilder` | Returns the part module output dataMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PartModuleOutputBuilder1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57988.html

Represents aNXOpen.GeometricUtilities.PartModuleOutputBuilder1

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `OutputReferences1[get]` | `unsafeNXOpen.Features.PartGeometryCopyBuilder` | Returns the new part module output dataMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PartModuleReferencesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57992.html

Represents aNXOpen.GeometricUtilities.PartModuleReferencesBuilder

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
| `ExpressionList[get]` | `unsafeNXOpen.SelectExpressionList` | Returns the expressions for part module input/outputMore... |
| `GeometryList[get]` | `unsafeNXOpen.GeometricUtilities.SelectionListList` | Returns the geometric references for part module input/outputMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PartModuleRelationshipBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a57996.html

Represents aFeatures.PartModulebuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `LinkedPartModule[get]` | `unsafeNXOpen.Features.SelectPartModule` | Returns the linked part module in separate part to which relationship needs to be establishedMore... |
| `PartModule[get]` | `unsafeNXOpen.Features.SelectPartModule` | Returns the part module in owining part to establish the relationshipMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PathLimits

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58000.html

Represents a path limits data


---

## NXOpen.GeometricUtilities.PatternClocking

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58004.html

enables the ability to apply delta transforms on individual instances of a pattern

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetAngularDelta(string angularDeltaExp)` | `unsafe void` | Sets a angular delta for circular clockingMore... |
| `SetRadialDelta(string radialDelta)` | `unsafe void` | Sets a radial delta for circular clockingMore... |
| `SetXDirectionDelta(string direction1Exp)` | `unsafe void` | Sets an x direction delta for linear clockingMore... |
| `SetYDirectionDelta(string direction2Exp)` | `unsafe void` | Sets a y direction delta for linear clockingMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AngularDelta[get]` | `unsafeNXOpen.Expression` | Returns the angular delta for circular clockingMore... |
| `ClockType[get]` | `unsafeNXOpen.GeometricUtilities.PatternClocking.ClockingType` | Returns the clocking enum to determine if linear or angular clockingMore... |
| `Direction1Delta[get]` | `unsafeNXOpen.Expression` | Returns the x direction delta for linear clockingMore... |
| `Direction2Delta[get]` | `unsafeNXOpen.Expression` | Returns the y direction delta for linear clockingMore... |
| `RadialDelta[get]` | `unsafeNXOpen.Expression` | Returns the radial delta for circular clockingMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PatternClockingBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58008.html

enables the ability to apply delta transforms on individual instances of a pattern within the pattern feature

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `AddInstance(int index1, int index2)` | `unsafe void` | Adds an instance that will get this clockingMore... |
| `RemoveInstance(int index1, int index2)` | `unsafe void` | Removes an instance from this clockingMore... |
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
| `AngularDelta[get]` | `unsafeNXOpen.Expression` | Returns the angular delta for circular clockingMore... |
| `ClockType[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternClockingBuilder.ClockingType` | Returns or sets the clocking enum to determine if linear or angular clockingMore... |
| `Direction1Delta[get]` | `unsafeNXOpen.Expression` | Returns the x direction delta for linear clockingMore... |
| `Direction2Delta[get]` | `unsafeNXOpen.Expression` | Returns the y direction delta for linear clockingMore... |
| `Motion[get]` | `unsafeNXOpen.GeometricUtilities.ModlMotion` | Returns the user defined transform motionMore... |
| `RadialDelta[get]` | `unsafeNXOpen.Expression` | Returns the radial delta for circular clockingMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PatternDefinition

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58012.html

pattern spacing for several pattern based commands

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateClockingBuilder(int ix, int iy)` | `unsafeNXOpen.GeometricUtilities.PatternClockingBuilder` | Creates a pattern clocking objectMore... |
| `CreatePatternInstanceEditBuilder()` | `unsafeNXOpen.GeometricUtilities.PatternInstanceEditBuilder` | This is the default creator forNXOpen.GeometricUtilities.PatternInstanceEditBuilder.More... |
| `GetClocking(int index1, int index2)` | `unsafeNXOpen.GeometricUtilities.PatternClocking` | Returns the clocking data for aNXOpen.GeometricUtilities.PatternDefinitioninstanceMore... |
| `GetDeleteState(int index1, int index2)` | `unsafe bool` | Gets the delete state for the instance at the specified indicies.More... |
| `GetSuppressState(int index1, int index2)` | `unsafe bool` | Gets the suppress state for the instance at the specified indicies.More... |
| `RemoveClocking(int index1, int index2)` | `unsafe void` | Removes clocking from pattern definition instanceMore... |
| `RemoveVariance(int index1, int index2)` | `unsafe void` | Removes variance from pattern definition instanceMore... |
| `SetDeleteState(int index1, int index2, bool deleteState)` | `unsafe void` | Sets the delete state for the instance at the specified indicies.More... |
| `SetSpreadsheetData(double [] spreadsheetTableArray, double [] locationTableArray, bool [] defaultTableArray)` | `unsafe void` | Sets the spreadsheet dataMore... |
| `SetSuppressState(int index1, int index2, bool suppressState)` | `unsafe void` | Sets the suppress state for the instance at the specified indicies.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AlongPathDefinition[get]` | `unsafeNXOpen.GeometricUtilities.AlongPathPattern` | Returns the along path definition.More... |
| `CircularDefinition[get]` | `unsafeNXOpen.GeometricUtilities.CircularPattern` | Returns the circular definition.More... |
| `FrameOnlyToggle[get, set]` | `unsafe bool` | Returns or sets the frameOnlyToggle, a logical flag to indicate if the we need only instances on the boundary.More... |
| `GeneralDefinition[get]` | `unsafeNXOpen.GeometricUtilities.GeneralPattern` | Returns the general definition.More... |
| `HelixDefinition[get]` | `unsafeNXOpen.GeometricUtilities.HelixPattern` | Returns the helix definition.More... |
| `MirrorDefinition[get]` | `unsafeNXOpen.GeometricUtilities.MirrorPattern` | Returns the mirror definition.More... |
| `PatternFill[get]` | `unsafeNXOpen.GeometricUtilities.PatternFill` | Returns the pattern fill definition.More... |
| `PatternIncrementsBuilder[get]` | `unsafeNXOpen.GeometricUtilities.PatternIncrementsBuilder` | Returns the pattern increments definition.More... |
| `PatternOrientation[get]` | `unsafeNXOpen.GeometricUtilities.PatternOrientation` | Returns the pattern orientation definition.More... |
| `PatternType[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternDefinition.PatternEnum` | Returns or sets the pattern typeMore... |
| `PolygonDefinition[get]` | `unsafeNXOpen.GeometricUtilities.PolygonPattern` | Returns the polygon definition.More... |
| `RectangularDefinition[get]` | `unsafeNXOpen.GeometricUtilities.RectangularPattern` | Returns the linear definition.More... |
| `ReferenceDefinition[get]` | `unsafeNXOpen.GeometricUtilities.ReferencePattern` | Returns the reference definition.More... |
| `SeedOnlyToggle[get, set]` | `unsafe bool` | Returns or sets the seedOnlyToggle, a logical flag to indicate if the we need only instances for the seed along the second direction.More... |
| `SpiralDefinition[get]` | `unsafeNXOpen.GeometricUtilities.SpiralPattern` | Returns the spiral definition.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PatternFill

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58016.html

the pattern fill definition

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
| `ApplyMarginToInnerBoundToggle[get, set]` | `unsafe bool` | Returns or sets the applyMarginToInnerBoundToggle, a logical flag to indicate if we need to apply the margin value to internal bounday.More... |
| `FaceBoundary[get]` | `unsafeNXOpen.Section` | Returns the face boundaryMore... |
| `FillBoundary[get]` | `unsafeNXOpen.Section` | Returns the fill boundaryMore... |
| `FillMargin[get]` | `unsafeNXOpen.Expression` | Returns the fill marginMore... |
| `FillOptions[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternFill.PatternFillOptions` | Returns or sets the fill optionsMore... |
| `InternalBoundary[get]` | `unsafeNXOpen.Section` | Returns the fill boundaryMore... |
| `SimplifiedBoundaryToggle[get, set]` | `unsafe bool` | Returns or sets the simplifiedBoundaryToggle, a logical flag to indicate a special case for Linear, Circular, Spiral, or Polygon.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PatternIncrementItem

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58020.html

variational for one master expression of the input object(s) being patterned

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
| `IncrementExpression[get]` | `unsafeNXOpen.Expression` | Returns the increment or variation to be applied to master expressionMore... |
| `MasterExpression[get]` | `unsafeNXOpen.Expression` | Returns the master expressionMore... |
| `Operation[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternIncrementItem.OperationEnum` | Returns or sets the increment operationMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PatternIncrementItemList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58024.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.PatternIncrementItem[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.PatternIncrementItem@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.PatternIncrementItemobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.PatternIncrementItemobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.PatternIncrementItemobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.PatternIncrementItem` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.PatternIncrementItem[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.PatternIncrementItem@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.PatternIncrementItem[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.PatternIncrementItemobject1,NXOpen.GeometricUtilities.PatternIncrementItemobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.PatternIncrementsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58028.html

pattern increments builder

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
| `IncrementsListInDirection1[get]` | `unsafeNXOpen.GeometricUtilities.PatternIncrementsList` | Returns the incrementsNXOpen.GeometricUtilities.PatternIncrementsListin Direction1.More... |
| `IncrementsListInDirection2[get]` | `unsafeNXOpen.GeometricUtilities.PatternIncrementsList` | Returns the incrementsNXOpen.GeometricUtilities.PatternIncrementsListin Direction2.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PatternIncrementsList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58032.html

list ofNXOpen.GeometricUtilities.PatternIncrementItemobjects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreatePatternIncrementItem()` | `unsafeNXOpen.GeometricUtilities.PatternIncrementItem` | This is the default creator forNXOpen.GeometricUtilities.PatternIncrementItem.More... |
| `CreatePatternIncrementItem(NXOpen.ExpressionmasterExpression)` | `unsafeNXOpen.GeometricUtilities.PatternIncrementItem` | This is the actual creator forNXOpen.GeometricUtilities.PatternIncrementItem.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `List[get]` | `unsafeNXOpen.GeometricUtilities.PatternIncrementItemList` | Returns the list ofNXOpen.GeometricUtilities.PatternIncrementItemobjects.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PatternInstanceEditBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58036.html

pattern instance edit builder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetSelectedInstances(int [] firstIndexOfSelectedInstances, int [] secondIndexOfSelectedInstances)` | `unsafe void` | Sets the indices of the selected Pattern Instances whose expressions are to be edited with the expressions provided in theNXOpen.GeometricUtilities.InstanceEditedExpressionsList.More... |
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
| `EditedExpressionsList[get]` | `unsafeNXOpen.GeometricUtilities.InstanceEditedExpressionsList` | Returns the edited expressions listNXOpen.GeometricUtilities.InstanceEditedExpressionsList.More... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PatternOrientation

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58040.html

the pattern orientation definition

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
| `AlongOrientationOption[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternOrientation.Enum` | Returns or sets the orientationOption for Along pattern typeMore... |
| `AlongPathRotationAngle[get]` | `unsafeNXOpen.Expression` | Returns the along path rotation angle for the Along type pattern Normal to Path option.More... |
| `CircularOrientationOption[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternOrientation.Enum` | Returns or sets the orientationOption for Circular pattern typeMore... |
| `FollowFaceProjDirOption[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternOrientation.ProjDirEnum` | Returns or sets the followFaceProjDirOption, an enum for follow face project direction.More... |
| `FollowFaceSelection[get]` | `unsafeNXOpen.ScCollector` | Returns the followFaceSelection, a sc collector to store selected faces.More... |
| `FollowFaceToggle[get, set]` | `unsafe bool` | Returns or sets the followFaceToggle, a logical flag to indicate if the we need to modify the orientation to follow selected faces.More... |
| `FromCSYS[get, set]` | `unsafeNXOpen.CoordinateSystem` | Returns or sets the fromCSYS, a CSYS for certain pattern type orientation need.More... |
| `GeneralOrientationOption[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternOrientation.Enum` | Returns or sets the orientationOption for General pattern typeMore... |
| `HelixOrientationOption[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternOrientation.Enum` | Returns or sets the orientationOption for Helix pattern typeMore... |
| `LinearOrientationOption[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternOrientation.Enum` | Returns or sets the orientationOption for Linear pattern typeMore... |
| `MirrorOrientationOption[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternOrientation.Enum` | Returns or sets the orientationOption for Mirror pattern typeMore... |
| `OrientationOption[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternOrientation.Enum` | Returns or sets the orientationOption for rectangular pattern type Note: this one does not have a straight forward replacement; Replacement based on pattern type:GeometricUtilities.PatternOrientation.LinearOrientationOptionGeometricUtilities.PatternOrientation.CircularOrientationOptionGeometricUtilities.PatternOrientation.AlongOrientationOptionGeometricUtilities.PatternOrientation.PolygonOrientationOptionGeometricUtilities.PatternOrientation.SpiralOrientationOptionGeometricUtilities.PatternOrientation.GeneralOrientationOptionGeometricUtilities.PatternOrientation.MirrorOrientationOptionGeometricUtilities.PatternOrientation.HelixOrientationOptionMore... |
| `PolygonOrientationOption[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternOrientation.Enum` | Returns or sets the orientationOption for Polygon pattern typeMore... |
| `RepeatTransformSetting[get, set]` | `unsafe bool` | Returns or sets the repeatTransformSetting, a logical flag to indicate if the we need to repeatedly apply the transform.More... |
| `SpiralOrientationOption[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternOrientation.Enum` | Returns or sets the orientationOption for Spiral pattern typeMore... |
| `ToCSYS[get, set]` | `unsafeNXOpen.CoordinateSystem` | Returns or sets the toCSYS, a CSYS for certain pattern type orientation need.More... |
| `UserDefinedProjDir[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the userDefinedProjDir, a vector for user defined follow face project direction.More... |
| `VectorForAlong[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the vectorForAlong, a vector for Along type orientation need.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PatternReferencePointServiceBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58044.html

Pattern Reference Point is a service which enables the employing client to compute the reference point for pattern instance locations

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
| `IsReferencePointInferred[get, set]` | `unsafe bool` | Returns or sets the reference point inferred flag.More... |
| `Point[get, set]` | `unsafeNXOpen.Point` | Returns or sets the reference pointMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PatternSpacing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58048.html

defines the various ways pattern instances can be spaced within the pattern, particularly in the context of the PatternDefinition class

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
| `NCopies[get]` | `unsafeNXOpen.Expression` | Returns the number of copies the pattern will generated in this directionMore... |
| `Points[get]` | `unsafeNXOpen.Section` | Returns the section with points to be used in this directionMore... |
| `SpaceType[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternSpacing.SpacingType` | Returns or sets the type of spacing to be used by the patternMore... |
| `SpacingsList[get]` | `unsafeNXOpen.GeometricUtilities.PatternSpacingsList` | Returns the list of spacings (Expression or OnPathDimBuilder) to be used in this directionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PatternSpacingsList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58052.html

list ofNXOpen.GeometricUtilities.PatternSpacingsListItemobjects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreatePatternSpacingsListItem()` | `unsafeNXOpen.GeometricUtilities.PatternSpacingsListItem` | This is the default creator forNXOpen.GeometricUtilities.PatternSpacingsListItem.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `List[get]` | `unsafeNXOpen.GeometricUtilities.PatternSpacingsListItemList` | Returns the list ofNXOpen.GeometricUtilities.PatternSpacingsListItemobjects.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PatternSpacingsListItem

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58056.html

one pattern spacing in the spacings list

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
| `SpacingExpression[get]` | `unsafeNXOpen.Expression` | Returns the spacing expressionMore... |
| `SpacingOnPath[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the spacingNXOpen.GeometricUtilities.OnPathDimensionBuilderMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PatternSpacingsListItemList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58060.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.PatternSpacingsListItem[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.PatternSpacingsListItem@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.PatternSpacingsListItemobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.PatternSpacingsListItemobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.PatternSpacingsListItemobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.PatternSpacingsListItem` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.PatternSpacingsListItem[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.PatternSpacingsListItem@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.PatternSpacingsListItem[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.PatternSpacingsListItemobject1,NXOpen.GeometricUtilities.PatternSpacingsListItemobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.PlayButtonsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58064.html

VCR buttons for any dialog that needs them

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `ForwardToEnd()` | `unsafe void` | TODO: fill in a description for thisMore... |
| `PlayBackward()` | `unsafe void` | TODO: fill in a description for thisMore... |
| `PlayForward()` | `unsafe void` | TODO: fill in a description for thisMore... |
| `RewindToStart()` | `unsafe void` | TODO: fill in a description for thisMore... |
| `StepBackward()` | `unsafe void` | TODO: fill in a description for thisMore... |
| `StepForward()` | `unsafe void` | TODO: fill in a description for thisMore... |
| `Stop()` | `unsafe void` | TODO: fill in a description for thisMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CurrentStep[get, set]` | `unsafe int` | Returns or sets the stepMore... |
| `PlayModes[get, set]` | `unsafeNXOpen.GeometricUtilities.PlayButtonsBuilder.PlayModeValues` | Returns or sets the play modesMore... |
| `ScaleSpeed[get, set]` | `unsafe double` | Returns or sets the scale speedMore... |
| `ScaleStep[get, set]` | `unsafe double` | Returns or sets the scale stepMore... |
| `Speed[get, set]` | `unsafe double` | Returns or sets the speedMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PointFacePlaneSelectionBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58068.html

Represents aNXOpen.GeometricUtilities.PointFacePlaneSelectionBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateLengthLimitPointBuilder(NXOpen.ExpressionmOnPathExp,NXOpen.GeometricUtilities.OnPathDimensionBuildermOnPath, bool mIsFlipped,NXOpen.PointmThruPoint)` | `unsafeNXOpen.GeometricUtilities.LengthLimitPointBuilder` | Creates a FacePlaneSelectionBuilderMore... |
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
| `IsOk[get, set]` | `unsafe bool` | Returns or sets the length limit object data OK flagMore... |
| `LengthLimitPoint[get]` | `unsafeNXOpen.GeometricUtilities.LengthLimitPointBuilder` | Returns the select point as length limit objectMore... |
| `LimitTopolSwitchFinFlag[get, set]` | `unsafe bool` | Returns or sets the limit edge switch fin flagMore... |
| `PlaneHelpPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the user plane cap help pointMore... |
| `SelectEdge[get]` | `unsafeNXOpen.ScCollector` | Returns the select edge as length limit objectMore... |
| `SelectFace[get]` | `unsafeNXOpen.GeometricUtilities.FaceSetData` | Returns the select face as length limit objectMore... |
| `SelectPlane[get, set]` | `unsafeNXOpen.Plane` | Returns or sets the select plane as length limit objectMore... |
| `TrimObject[get, set]` | `unsafeNXOpen.GeometricUtilities.PointFacePlaneSelectionBuilder.TrimObjectType` | Returns or sets the object type for length limit objectMore... |
| `UseFaceCapBlend[get, set]` | `unsafe bool` | Returns or sets the use face cap blend flagMore... |
| `UsePlaneCapBlend[get, set]` | `unsafe bool` | Returns or sets the use plane cap blendMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PointFacePlaneSelectionBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58072.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.PointFacePlaneSelectionBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.PointFacePlaneSelectionBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.PointFacePlaneSelectionBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.PointFacePlaneSelectionBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.PointFacePlaneSelectionBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.PointFacePlaneSelectionBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.PointFacePlaneSelectionBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.PointFacePlaneSelectionBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.PointFacePlaneSelectionBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.PointFacePlaneSelectionBuilderobject1,NXOpen.GeometricUtilities.PointFacePlaneSelectionBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.PointSetAlignmentBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58076.html

This class performs a point set to point set alignment

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Constraint[get, set]` | `unsafeNXOpen.GeometricUtilities.PointSetAlignmentBuilder.ConstraintOptions` | Returns or sets the constraintMore... |
| `FromPointSet[get]` | `unsafeNXOpen.SelectPointList` | Returns the "from" point setMore... |
| `ObjectsToMove[get]` | `unsafeNXOpen.SelectDisplayableObjectList` | Returns the objects to moveMore... |
| `ToPointSet[get]` | `unsafeNXOpen.SelectPointList` | Returns the "to" point setMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PointsFromFileBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58080.html

Represents aNXOpen.GeometricUtilities.PointsFromFileBuilderbuilder read points from a text file with format *

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CoordinateOption[get, set]` | `unsafeNXOpen.GeometricUtilities.PointsFromFileBuilder.Options` | Returns or sets the option indicating type of point coordinatesMore... |
| `FileName[get, set]` | `unsafe string` | Returns or sets the file name of the point data fileMore... |
| `PathName[get, set]` | `unsafe string` | Returns or sets the path name of the point data fileMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PolygonPattern

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58084.html

the polygon pattern definition

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
| `Flip[get, set]` | `unsafe bool` | Returns or sets the flip object for 2D mode.More... |
| `HorizontalRef[get]` | `unsafeNXOpen.GeometricUtilities.HorizontalReference` | Returns the horizontal referenceMore... |
| `NumberOfSides[get]` | `unsafeNXOpen.Expression` | Returns the number of sides for the polygon type pattern will generated in this directionMore... |
| `PolygonSizeOption[get, set]` | `unsafeNXOpen.GeometricUtilities.PolygonPattern.SizeOptions` | Returns or sets the polygon size optionMore... |
| `PolygonSpacing[get]` | `unsafeNXOpen.GeometricUtilities.PolygonPatternSpacing` | Returns the polygon spacing of the instances of the patternMore... |
| `RadialSpacing[get]` | `unsafeNXOpen.GeometricUtilities.DistancePatternSpacing` | Returns the radial spacing of the instances of the patternMore... |
| `RotationAxis[get, set]` | `unsafeNXOpen.Axis` | Returns or sets the rotation axis for the pattern.More... |
| `RotationCenter[get, set]` | `unsafeNXOpen.Point` | Returns or sets the rotation center for the 2d pattern.More... |
| `UseRadialDirectionToggle[get, set]` | `unsafe bool` | Returns or sets the UseRadialDirection toggle attribute.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.PolygonPatternSpacing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58088.html

defines the various ways pattern instances can be spaced within the pattern, particularly in the context of the PatternDefinition class

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `PitchDistance[get]` | `unsafeNXOpen.Expression` | Returns the pitch distance along one side for the spacing of the pattern from one instance to the next.More... |
| `SpanAngle[get]` | `unsafeNXOpen.Expression` | Returns the angle for the spacing of the pattern for the entire pattern.More... |
| `NCopies[get]` | `unsafeNXOpen.Expression` | Returns the number of copies the pattern will generated in this directionMore... |
| `Points[get]` | `unsafeNXOpen.Section` | Returns the section with points to be used in this directionMore... |
| `SpaceType[get, set]` | `unsafeNXOpen.GeometricUtilities.PatternSpacing.SpacingType` | Returns or sets the type of spacing to be used by the patternMore... |
| `SpacingsList[get]` | `unsafeNXOpen.GeometricUtilities.PatternSpacingsList` | Returns the list of spacings (Expression or OnPathDimBuilder) to be used in this directionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ProjectionOptions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58092.html

Represents a ProjectionOptions

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
| `ProjectDirectionMethod[get, set]` | `unsafeNXOpen.GeometricUtilities.ProjectionOptions.DirectionType` | Returns or sets the Projection direction methodMore... |
| `ProjectVector[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the Projection vectorMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.QuadrilateralFrameBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58096.html

Represents aNXOpen.GeometricUtilities.QuadrilateralFrameBuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Subtype[get, set]` | `unsafeNXOpen.GeometricUtilities.QuadrilateralFrameBuilder.Subtypes` | Returns or sets the subtypeMore... |
| `Anchor[get]` | `unsafeNXOpen.GeometricUtilities.AnchorLocatorBuilder` | Returns the anchor of the frameMore... |
| `AnchorAttachment[get, set]` | `unsafeNXOpen.GeometricUtilities.ShapeFrameBuilder.AnchorAttachmentType` | Returns or sets the anchor attachmentMore... |
| `NumberVertices[get]` | `unsafe int` | Returns the number of vertices of the frameMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.Rebuild

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58100.html

Represents aNXOpen.GeometricUtilities.Rebuild

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
| `Degree[get, set]` | `unsafe int` | Returns or sets the degree when rebuild type is none.More... |
| `DegreeType[get, set]` | `unsafeNXOpen.GeometricUtilities.Rebuild.DegreeTypes` | Returns or sets the degree type when rebuild type is none.More... |
| `ManualDegree[get, set]` | `unsafe int` | Returns or sets the degree when rebuild type is manual.More... |
| `MaximumDegree[get, set]` | `unsafe int` | Returns or sets the maximum degree when rebuild type is advanced.More... |
| `MaximumSegments[get, set]` | `unsafe int` | Returns or sets the maximum segments when rebuild type is advanced.More... |
| `RebuildType[get, set]` | `unsafeNXOpen.GeometricUtilities.Rebuild.RebuildTypes` | Returns or sets the rebuild type.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.RectangularFrameBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58104.html

Rectangular frame builder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `EditCoordinateSystem(NXOpen.Pointorigin,NXOpen.Matrix3x3csys)` | `unsafe void` | Edits current coordinate system.More... |
| `UpdateOnCoordinateSystem()` | `unsafe void` | Updates the frame based on coordinate system.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `AnchorLocation[get, set]` | `unsafeNXOpen.GeometricUtilities.RectangularFrameBuilder.AnchorLocationType` | Returns or sets the anchor locationMore... |
| `AnchorLocator[get]` | `unsafeNXOpen.SelectSmartObject` | Returns the point or coordinate system to define initial location and orientation of the frameMore... |
| `CoordinateSystem[get, set]` | `unsafeNXOpen.CoordinateSystem` | Returns or sets the coordinate systemMore... |
| `Height[get]` | `unsafeNXOpen.Expression` | Returns the heightMore... |
| `Length[get]` | `unsafeNXOpen.Expression` | Returns the lengthMore... |
| `Shear[get]` | `unsafeNXOpen.Expression` | Returns the shearMore... |
| `WScale[get, set]` | `unsafe double` | Returns or sets the width scaleMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.RectangularPattern

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58108.html

the rectangular pattern definition

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
| `CreateLastStaggered[get, set]` | `unsafe bool` | Returns or sets the option to generate the last item in a staggered row.More... |
| `HorizontalRef[get]` | `unsafeNXOpen.GeometricUtilities.HorizontalReference` | Returns the horizontal referenceMore... |
| `SimplifiedLayoutType[get, set]` | `unsafeNXOpen.GeometricUtilities.RectangularPattern.SimplifiedLayoutTypes` | Returns or sets the simplified layout type to be used by the patternMore... |
| `StaggerType[get, set]` | `unsafeNXOpen.GeometricUtilities.RectangularPattern.StaggerOptions` | Returns or sets the type of stagger to be used by the patternMore... |
| `UseYDirectionToggle[get, set]` | `unsafe bool` | Returns or sets the UseYDirection toggle attribute.More... |
| `XDirection[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the x axisMore... |
| `XFlip[get, set]` | `unsafe bool` | Returns or sets the XSelection flip attribute.More... |
| `XSelection[get]` | `unsafeNXOpen.SelectNXObject` | Returns the direction object.More... |
| `XSpacing[get]` | `unsafeNXOpen.GeometricUtilities.DistancePatternSpacing` | Returns the instance spacing along the x axisMore... |
| `XSymmetryToggle[get, set]` | `unsafe bool` | Returns or sets the XSymmetry toggle attribute.More... |
| `YDirection[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the y axis, which can be any vector not parallel to the x axisMore... |
| `YFlip[get, set]` | `unsafe bool` | Returns or sets the YSelection flip attribute.More... |
| `YSelection[get]` | `unsafeNXOpen.SelectNXObject` | Returns the direction object.More... |
| `YSpacing[get]` | `unsafeNXOpen.GeometricUtilities.DistancePatternSpacing` | Returns the instance spacing along the y axisMore... |
| `YSymmetryToggle[get, set]` | `unsafe bool` | Returns or sets the YSymmetry toggle attribute.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ReduceSurfaceRadiusBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58112.html

Reduce Surface Radius Builder of Geometric Utilities

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Direction[get, set]` | `unsafe bool` | Returns or sets the direction which specifies concave face respect to the body face normalMore... |
| `FaceGroupList[get]` | `unsafeNXOpen.GeometricUtilities.ReduceSurfaceRadiusFaceGroupBuilderList` | Returns the list containing the face chains as input objects used to do reduction.More... |
| `HighRadius[get, set]` | `unsafe double` | Returns or sets the high radius which specifies lower limit to filter out all qualified facesMore... |
| `IndexListItem[get, set]` | `unsafe int` | Returns or sets the index of list itemMore... |
| `LowRadius[get, set]` | `unsafe double` | Returns or sets the low radius which specifies lower limit to filter out all qualified facesMore... |
| `OnPathDimEnd[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the end position of reduced sheet bodyMore... |
| `OnPathDimStart[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the start position of reduced sheet bodyMore... |
| `PercentReduction[get, set]` | `unsafe double` | Returns or sets the value of percentage reduction methodMore... |
| `PositionTolerance[get, set]` | `unsafe double` | Returns or sets the position tolerance between two faces connectionMore... |
| `ReducedFaceType[get, set]` | `unsafeNXOpen.GeometricUtilities.ReduceSurfaceRadiusBuilder.ReducedFaceTypeSpecification` | Returns or sets the type of performing the radius reduction previewMore... |
| `ReduceValueType[get, set]` | `unsafeNXOpen.GeometricUtilities.ReduceSurfaceRadiusBuilder.ReduceValueTypeSpecification` | Returns or sets the type of reduced value which results surface shapeMore... |
| `SelectChain[get]` | `unsafeNXOpen.ScCollector` | Returns the selected entities for performing the radius reduction operation, which selected by "Select Faces by Chain" and "Single Selection"More... |
| `SelectFace[get]` | `unsafeNXOpen.ScCollector` | Returns the selected entities for performing the radius reduction operation, which selected by "Select Faces by Radius"More... |
| `TangentTolerance[get, set]` | `unsafe double` | Returns or sets the tangent tolerance between two faces connectionMore... |
| `TargetReduction[get, set]` | `unsafe double` | Returns or sets the target value methodMore... |
| `ValueReduction[get, set]` | `unsafe double` | Returns or sets the value of reduction value methodMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ReduceSurfaceRadiusFaceGroupBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58116.html

Reduce Surface Radius Face Group Builder of Geometric Utilities

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `EndLimit[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the end position of reduced sheet bodyMore... |
| `SelectFace[get]` | `unsafeNXOpen.ScCollector` | Returns the selected entities of single chain for performing radius reductionMore... |
| `StartLimit[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the start position of reduced sheet bodyMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ReduceSurfaceRadiusFaceGroupBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58120.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.ReduceSurfaceRadiusFaceGroupBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.ReduceSurfaceRadiusFaceGroupBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.ReduceSurfaceRadiusFaceGroupBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.ReduceSurfaceRadiusFaceGroupBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.ReduceSurfaceRadiusFaceGroupBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.ReduceSurfaceRadiusFaceGroupBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.ReduceSurfaceRadiusFaceGroupBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.ReduceSurfaceRadiusFaceGroupBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.ReduceSurfaceRadiusFaceGroupBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.ReduceSurfaceRadiusFaceGroupBuilderobject1,NXOpen.GeometricUtilities.ReduceSurfaceRadiusFaceGroupBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.ReferencePattern

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58124.html

the reference pattern definition

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `ResetBaseInstance()` | `unsafe void` | Reset the base instance indices to an "undefined" state.More... |
| `SetBaseInstance(int firstIndex, int secondIndex)` | `unsafe void` | Set the base instanceMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `ReferencedPattern[get]` | `unsafeNXOpen.SelectNXObject` | Returns the referenced pattern object.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.RefitControlBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58128.html

This class is used to specify the parameter set to refit faces

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
| `DegreesAndSegmentsOrPatches[get]` | `unsafeNXOpen.GeometricUtilities.DegreesAndSegmentsOrPatchesBuilder` | Returns the refit degrees and segments or patchesMore... |
| `RefitDirection[get, set]` | `unsafeNXOpen.GeometricUtilities.RefitControlBuilder.RefitControlDirection` | Returns or sets the refit directionMore... |
| `RefitMethod[get, set]` | `unsafeNXOpen.GeometricUtilities.RefitControlBuilder.RefitControlMethod` | Returns or sets the refit methodMore... |
| `Tolerance[get, set]` | `unsafe double` | Returns or sets the toleranceMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.RegionTracker

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58132.html

a class which collects all the geometric entities used to identify a region of faces during a boolean feature

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `AppendOneBoundaryBody(NXOpen.BodyboundaryBodyEid, bool sideness)` | `unsafe void` | Append one new region boundary body to the region trackerMore... |
| `GetEdgeSelectors(outNXOpen.Face[] entities)` | `unsafe void` | The input target or tool edges used to identify the regionMore... |
| `GetFaceSelectors(outNXOpen.Face[] entities)` | `unsafe void` | The input target or tool faces used to identify the regionMore... |
| `GetOwningBody()` | `unsafeNXOpen.Body` | The owning body where the region is located ontoMore... |
| `GetVertexSelectors(outNXOpen.Edge[] entities, outNXOpen.GeometricUtilities.RegionTracker.ExtremityType[] extremities)` | `unsafe void` | The input target or tool vertices (edge extremities) used to identify the regionMore... |
| `SetEdgeSelectors(NXOpen.Edge[] entities)` | `unsafe void` | The input target or tool edges used to identify the regionMore... |
| `SetFaceSelectors(NXOpen.Face[] entities)` | `unsafe void` | The input target or tool faces used to identify the regionMore... |
| `SetOneEdgeSelector(NXOpen.Edgeentity)` | `unsafe void` | An input target or tool edge used to identify the regionMore... |
| `SetOneFaceSelector(NXOpen.Faceentity)` | `unsafe void` | An input target or tool face used to identify the regionMore... |
| `SetOnePointSelector(NXOpen.Point3dlocation)` | `unsafe void` | The input point location (x,y,z) used to identify the regionMore... |
| `SetOneVertexSelector(NXOpen.Edgeentity,NXOpen.GeometricUtilities.RegionTracker.ExtremityTypeextremity)` | `unsafe void` | One input target or tool vertex (edge extremity) used to identify the regionMore... |
| `SetOwningBody(NXOpen.BodyowningBodyEid)` | `unsafe void` | The owning body where the region is located ontoMore... |
| `SetVertexSelectors(NXOpen.Edge[] entities,NXOpen.GeometricUtilities.RegionTracker.ExtremityType[] extremities)` | `unsafe void` | The input target or tool vertices (edge extremities) used to identify the regionMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Added[get, set]` | `unsafe bool` | Returns or sets a flag indicating if the region is added/selected by the userMore... |
| `OnTool[get, set]` | `unsafe bool` | Returns or sets a flag indicating if the region belongs to the tool (true) or to the target (false)More... |
| `Removed[get, set]` | `unsafe bool` | Returns or sets a flag indicating if the region is removed/deselected by the userMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.RenameLinkedPartModulePartBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58136.html

Represents aFeatures.PartModulebuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetAllAssociatedLinkedPartModulePartTags(NXOpen.PartmainPartTag, outNXOpen.Part[] linkedPartTags)` | `unsafe void` | Get all linked part module part tags associated with given main part.More... |
| `GetLinkedPartNameToBeSavedAs(NXOpen.PartlinkedPartTag)` | `unsafe string` | Retrieve new name of linked part module part added earlier for "Save As".More... |
| `GetLinkedPartNameToBeSavedAs(out string [] fileName)` | `unsafe void` | Retrieve all linked part module parts and their associated new names.More... |
| `SetLinkedPartNameToBeSavedAs(NXOpen.PartlinkedPartTag, string fileName)` | `unsafe void` | Add linked part module part tag and its new name to perform "Save As" along with its main part.More... |
| `SetLinkedPartNameToBeSavedAs(NXOpen.Part[] linkedPartTag, string [] fileName)` | `unsafe void` | Add multiple linked part module part tags and their new names to perform "Save As" along with its main part.More... |
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


---

## NXOpen.GeometricUtilities.RenewFeatureBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58140.html

Represents a RenewFeatureBuilder object

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `FeatureList[get]` | `unsafeNXOpen.Features.FeatureList` | Returns the renew feature listMore... |
| `MakeRenewedFeatureCurrent[get, set]` | `unsafe bool` | Returns or sets the option to make the renewed feature currentMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ReplAsstBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58160.html

Represents aNXOpen.GeometricUtilities.ReplAsstBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateEmptyMatch()` | `unsafeNXOpen.GeometricUtilities.ParentEquivalencyMap` | This is the default creator for a parent equivalency map.More... |
| `CreateGeometricMaps(outNXOpen.GeometricUtilities.ParentEquivalencyMap[] maps)` | `unsafe void` | Perform geometric matching.More... |
| `CreateInferredMaps(outNXOpen.GeometricUtilities.ParentEquivalencyMap[] maps)` | `unsafe void` | Infer more matches from matches already 'Accepted'.More... |
| `CreateNameBasedMaps(outNXOpen.GeometricUtilities.ParentEquivalencyMap[] maps)` | `unsafe void` | Perform automatic matching based on user-defined object names.More... |
| `Enter()` | `unsafe void` | Entry and re-entry to the Replacement Assistant mapping environment.More... |
| `Exit()` | `unsafe void` | Exit the Replacement Assistant mapping environment.More... |
| `QueryFeatureOutputUsage()` | `unsafe int` | Query the downstream usage of the current feature's output entities and populate the usageInfoList.More... |
| `SetNewParents(NXOpen.DisplayableObject[] replacementObjects)` | `unsafe void` | Set the source entities for the Replacement Assistant.More... |
| `SetProdInt(NXOpen.TaggedObjectprodInt)` | `unsafe void` | Set the product interface tag for the Replacement Assistant.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Allowance[get, set]` | `unsafe double` | Returns or sets the deviation allowance for geometric matchingMore... |
| `MatchList[get]` | `unsafeNXOpen.GeometricUtilities.ParentEquivalencyMapList` | Returns the list of all Parent Equivalency Map objectsMore... |
| `MatchObjectsWithDependentsOnly[get, set]` | `unsafe bool` | Returns or sets the automatic matching preference to match objects with dependents only (if already searched separately)More... |
| `MatchSheetBoundariesOnly[get, set]` | `unsafe bool` | Returns or sets the automatic matching preference to match sheet boundaries onlyMore... |
| `OneToOne[get, set]` | `unsafe bool` | Returns or sets the one to one auto matching preferenceMore... |
| `UsageInfoList[get]` | `unsafeNXOpen.GeometricUtilities.EntityUsageInfoList` | Returns the list of all Entity Usage Info objectsMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ReplaceManager

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58144.html

Represents the Replace Manager class

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateReplaceManualMatchBuilder(NXOpen.Partpart)` | `unsafeNXOpen.GeometricUtilities.ReplaceManualMatchBuilder` | Creates aGeometricUtilities.ReplaceManualMatchBuilderMore... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |
| `GetReplaceManager(NXOpen.Sessionowner)` | `staticReplaceManager` | Returns the ReplaceManager object for the running session which serves as the 'gateway' class for the application API.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ReplaceManualMatchBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58148.html

a light-weight builder to keep track of the entities that need manual mapping

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateReplaceMatchListItem(NXOpen.TaggedObjectparentEntity, string depName, string depPartName)` | `unsafeNXOpen.GeometricUtilities.ReplaceMatchListItem` | Creates a Replace Match Ref builder for manual mapping used in stagemodel_replaceDesignPart commandMore... |
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
| `ReplaceMatchList[get]` | `unsafeNXOpen.GeometricUtilities.ReplaceMatchListItemList` | Returns the list of all match list objects used in the manual mapping dialog used in stagemodel_replaceDesignPart commandMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ReplaceMatchListItem

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58152.html

Used to select matches for Replace Design Part Manual Match Dialog


---

## NXOpen.GeometricUtilities.ReplaceMatchListItemList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58156.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.ReplaceMatchListItem[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.ReplaceMatchListItem@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.ReplaceMatchListItemobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.ReplaceMatchListItemobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.ReplaceMatchListItemobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.ReplaceMatchListItem` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.ReplaceMatchListItem[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.ReplaceMatchListItem@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.ReplaceMatchListItem[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.ReplaceMatchListItemobject1,NXOpen.GeometricUtilities.ReplaceMatchListItemobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.RodItemBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58164.html

Represents a RodItem

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Destroy()` | `unsafe void` | Deletes a Features.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `EndPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the end pointMore... |
| `GraphEdge[get]` | `unsafeNXOpen.Section` | Returns the section defining the unit cell graph.More... |
| `Method[get, set]` | `unsafeNXOpen.GeometricUtilities.RodItemBuilder.CurveCreateType` | Returns or sets the rod creation method.More... |
| `NumberOfSegments[get, set]` | `unsafe int` | Returns or sets the number of segments of the non-linear curve devided into a polylineMore... |
| `StartPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the start point of the rod.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.RodItemBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58168.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.RodItemBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.RodItemBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.RodItemBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.RodItemBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.RodItemBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.RodItemBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.RodItemBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.RodItemBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.RodItemBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.RodItemBuilderobject1,NXOpen.GeometricUtilities.RodItemBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.RodItemListBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58172.html

Represents a RodItemList

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateRodItemBuilder()` | `unsafeNXOpen.GeometricUtilities.RodItemBuilder` | Creates a Features.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `RodItemList[get]` | `unsafeNXOpen.GeometricUtilities.RodItemBuilderList` | Returns the section defining the unit cell graph.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.RotationSetBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58176.html

Represents aNXOpen.GeometricUtilities.RotationSetBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `FindObject(string journalIdentifier)` | `unsafeNXOpen.INXObject` | Finds theNXOpen.NXObjectwith the given identifier as recorded in a journal.More... |
| `Print()` | `unsafe void` | Prints a representation of this object to the system log file.More... |
| `ResetExtraData()` | `unsafe void` | Resets rotation extra data.More... |
| `SetName(string name)` | `unsafe void` | Sets the custom name of the object.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `IsOccurrence[get]` | `unsafe bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `unsafe string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Location[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the location on pathMore... |
| `Name[get]` | `unsafe string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `unsafeNXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `unsafeNXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `unsafeNXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |
| `Value[get]` | `unsafeNXOpen.Expression` | Returns the value expressionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |
| `IsOccurrence[get]` | `bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Name[get]` | `string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `NXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `NXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `NXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |


---

## NXOpen.GeometricUtilities.RotationSetBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58180.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.RotationSetBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.RotationSetBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.RotationSetBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.RotationSetBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.RotationSetBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.RotationSetBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.RotationSetBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.RotationSetBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.RotationSetBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.RotationSetBuilderobject1,NXOpen.GeometricUtilities.RotationSetBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.SShapedLawBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58264.html

Represents a s-shaped law

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `UpdateSpine()` | `unsafe void` | Update the builder based on current spineMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `EndNode[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimWithValueBuilder` | Returns the end nodeMore... |
| `SlopeNode[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimWithValueBuilder` | Returns the slope nodeMore... |
| `Spine[get]` | `unsafeNXOpen.Section` | Returns the SpineMore... |
| `StartNode[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimWithValueBuilder` | Returns the start nodeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.SaveConstraintsBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58184.html

Represents a builder for a Save Constraints

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
| `SaveConstraints[get, set]` | `unsafe bool` | Returns or sets the flag indicating whether to save the constraints or notMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ScalingMethodBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58188.html

Represents aNXOpen.GeometricUtilities.ScalingMethodBuilder

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
| `AreaLaw[get]` | `unsafeNXOpen.GeometricUtilities.LawBuilder` | Returns the area law.More... |
| `BlendingFunctionType[get, set]` | `unsafeNXOpen.GeometricUtilities.ScalingMethodBuilder.BlendingFunctionTypes` | Returns or sets the blending function.More... |
| `EndBlendScaleFactor[get, set]` | `unsafe double` | Returns or sets the end blend scale factor.More... |
| `PerimeterLaw[get]` | `unsafeNXOpen.GeometricUtilities.LawBuilder` | Returns the perimeter law.More... |
| `ScaleFactor[get, set]` | `unsafe double` | Returns or sets the scale factor.More... |
| `ScalingCurve[get]` | `unsafeNXOpen.Section` | Returns the scaling curve.More... |
| `ScalingOption[get, set]` | `unsafeNXOpen.GeometricUtilities.ScalingMethodBuilder.ScalingOptions` | Returns or sets the scaling method option.More... |
| `ScalingPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the scaling point.More... |
| `StartBlendScaleFactor[get, set]` | `unsafe double` | Returns or sets the start blend scale factor.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.ScalingSetBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58192.html

Represents aNXOpen.GeometricUtilities.ScalingSetBuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `ScalingValue[get]` | `unsafeNXOpen.Expression` | Returns the scaling value expressionMore... |
| `IsOccurrence[get]` | `unsafe bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `unsafe string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Location[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the location on pathMore... |
| `Name[get]` | `unsafe string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `unsafeNXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `unsafeNXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `unsafeNXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |
| `Value[get]` | `unsafeNXOpen.Expression` | Returns the value expressionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |
| `IsOccurrence[get]` | `bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Name[get]` | `string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `NXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `NXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `NXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |


---

## NXOpen.GeometricUtilities.ScalingSetBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58196.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.ScalingSetBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.ScalingSetBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.ScalingSetBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.ScalingSetBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.ScalingSetBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.ScalingSetBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.ScalingSetBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.ScalingSetBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.ScalingSetBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.ScalingSetBuilderobject1,NXOpen.GeometricUtilities.ScalingSetBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.SecondarySectionData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58200.html

Represents aNXOpen.GeometricUtilities.SecondarySectionData

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateSketch(double pathLocation)` | `unsafe void` | Copy the master sketch to create the secondary section sketchMore... |
| `DeleteSketch()` | `unsafe void` | Delete secondary section sketchMore... |
| `Destroy()` | `unsafe void` | Delete the secondary section object.More... |
| `GetMasterExpressionValues()` | `unsafeNXOpen.Expression[]` | Get the Master Sketch Expression ValuesMore... |
| `GetSecondarySectionValues()` | `unsafe string []` | Get the Secondary Sketch Expression ValuesMore... |
| `SetMasterExpressionValues(NXOpen.Expression[] expressions)` | `unsafe void` | Set the Master Sketch Expression Values.More... |
| `SetMasterSection(NXOpen.SectionmasterSection)` | `unsafe void` | Mutator to register the master section.More... |
| `SetPathLocation(double pathLocationPercent)` | `unsafe void` | Path LocationMore... |
| `SetSecondarySectionValues(string [] expressions)` | `unsafe void` | Set the Secondary Sketch Expression Values.More... |
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
| `IsEndSection[get, set]` | `unsafe bool` | Returns or sets the End SectionMore... |
| `IsStartSection[get, set]` | `unsafe bool` | Returns or sets the Start SectionMore... |
| `OnPathDimData[get]` | `unsafeNXOpen.GeometricUtilities.Extend` | Returns the on path dimMore... |
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

## NXOpen.GeometricUtilities.SectionPlaneData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58204.html

Represents a Section Plane Data class This class acts like a container to hold the data needed to create a plane

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
| `PlaneNormal[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the normal of the planeMore... |
| `PlaneOrigin[get, set]` | `unsafeNXOpen.Point` | Returns or sets the origin of the planeMore... |
| `PlanePoint1[get, set]` | `unsafeNXOpen.Point` | Returns or sets the first point of the planeMore... |
| `PlanePoint2[get, set]` | `unsafeNXOpen.Point` | Returns or sets the second point of the planeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.SelectDividingObjectBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58208.html

Represents the dividing tool block for dividing face

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
| `ConstraintManager[get]` | `unsafeNXOpen.Features.GeometricConstraintDataManager` | Returns the iso parameter pointMore... |
| `CurvesToOffset[get]` | `unsafeNXOpen.Section` | Returns the curves to offsetMore... |
| `DividingObjectsList[get]` | `unsafeNXOpen.SelectDisplayableObjectList` | Returns the dividing objects listMore... |
| `EndPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the end pointMore... |
| `IsoparametricDirection[get, set]` | `unsafeNXOpen.GeometricUtilities.SelectDividingObjectBuilder.IsoparametricDirectionType` | Returns or sets the isoparametric directionMore... |
| `OffsetDirection[get, set]` | `unsafe bool` | Returns or sets the offset directionMore... |
| `OffsetDistance[get]` | `unsafeNXOpen.Expression` | Returns the offset distanceMore... |
| `StartPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the start pointMore... |
| `ToolOption[get, set]` | `unsafeNXOpen.GeometricUtilities.SelectDividingObjectBuilder.ToolType` | Returns or sets the tool optionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.SelectionList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58212.html

Represents aNXOpen.GeometricUtilities.SelectionList

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `SelectObjectList[get]` | `unsafeNXOpen.SelectDisplayableObjectList` | Returns the list of geometriesMore... |
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

## NXOpen.GeometricUtilities.SelectionListList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58216.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.SelectionList[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.SelectionList@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.SelectionListobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.SelectionListobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.SelectionListobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.SelectionList` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.SelectionList[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.SelectionList@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.SelectionList[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.SelectionListobject1,NXOpen.GeometricUtilities.SelectionListobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.ShapeFrameBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58220.html

Represents aNXOpen.GeometricUtilities.ShapeFrameBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetMidpointCoords(int index)` | `unsafeNXOpen.Point2d` | Gets the coordinates of the i-th midpoint of the frame with respect to the planeMore... |
| `GetVertexCoords(int index)` | `unsafeNXOpen.Point2d` | Gets the coordinates of the i-th vertex of the frame with respect to the planeMore... |
| `SetMidpointCoords(int index,NXOpen.Point2dcoords)` | `unsafe void` | Sets the coordinates of the i-th midpoint of the frame with respect to the planeMore... |
| `SetVertexCoords(int index,NXOpen.Point2dcoords)` | `unsafe void` | Sets the coordinates of the i-th vertex of the frame with respect to the planeMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Anchor[get]` | `unsafeNXOpen.GeometricUtilities.AnchorLocatorBuilder` | Returns the anchor of the frameMore... |
| `AnchorAttachment[get, set]` | `unsafeNXOpen.GeometricUtilities.ShapeFrameBuilder.AnchorAttachmentType` | Returns or sets the anchor attachmentMore... |
| `NumberVertices[get]` | `unsafe int` | Returns the number of vertices of the frameMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.SimpleDraft

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58224.html

Represents an Offset

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetDraftAngle(string draftAngle)` | `unsafe void` | Sets the draft angleMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `DraftAngle[get]` | `unsafeNXOpen.Expression` | Returns the draft angleMore... |
| `DraftType[get, set]` | `unsafeNXOpen.GeometricUtilities.SimpleDraft.SimpleDraftType` | Returns or sets the simple draft typeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.SmartVolumeProfileBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58228.html

This class contains the options for automatically closing the profile to surrounding model geometry

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
| `CloseProfileRule[get, set]` | `unsafeNXOpen.GeometricUtilities.SmartVolumeProfileBuilder.CloseProfileRuleType` | Returns or sets the option defines how to extend the open profile to form a proper intersection with the target body.More... |
| `OpenProfileSmartVolumeOption[get, set]` | `unsafe bool` | Returns or sets the option for enabling open profile smart volume.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.SnipIntoPatchesBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58232.html

Represents aNXOpen.GeometricUtilities.SnipIntoPatchesBuilderbuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateRegionsPreview(NXOpen.FacetargetFace,NXOpen.Curve[] allCurves)` | `unsafe void` | Create region previewMore... |
| `DeleteExtractFace(NXOpen.FaceextractFace)` | `unsafe void` | Delete the extracted faceMore... |
| `DeleteInternalPatch(NXOpen.FacetargetFace,NXOpen.Curve[] allCurves)` | `unsafe void` | Delete internal patch from the selected surfaceMore... |
| `DeleteIsoCurve(NXOpen.Curve[] allCurves)` | `unsafe void` | Delete the isoparametric curve generated on the selected surfaceMore... |
| `GetExtractFace()` | `unsafeNXOpen.Face` | Get extracted faceMore... |
| `GetIsoCurves(NXOpen.FacetargetFace, outNXOpen.Curve[] allCurves)` | `unsafe void` | Get the generated isoparametric curves on the selected surfaceMore... |
| `SnipSurfaceIntoPatches(NXOpen.FacetargetFace)` | `unsafe void` | Snip the selected surface into patchesMore... |
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
| `Face[get]` | `unsafeNXOpen.SelectFace` | Returns the face to snip into patchesMore... |
| `HideOriginal[get, set]` | `unsafe bool` | Returns or sets the option indicating to hide or show the original.More... |
| `Region[get]` | `unsafeNXOpen.RegionPointList` | Returns the region to delete from the surfaceMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.SpineDefinitionBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58236.html

Provides a spine definition for modeling operations

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
| `Method[get, set]` | `unsafeNXOpen.GeometricUtilities.SpineDefinitionBuilder.MethodOptions` | Returns or sets the methodMore... |
| `Section[get]` | `unsafeNXOpen.Section` | Returns the sectionMore... |
| `Vector[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the vectorMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.SpinePlaneBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58240.html

Represents aNXOpen.GeometricUtilities.SpinePlaneBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `AlternateSolution()` | `unsafe void` | Creates the longer arc between the current and previous plane.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Plane[get, set]` | `unsafeNXOpen.Plane` | Returns or sets the planeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.SpinePlaneBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58244.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.SpinePlaneBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.SpinePlaneBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.SpinePlaneBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.SpinePlaneBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.SpinePlaneBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.SpinePlaneBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.SpinePlaneBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.SpinePlaneBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.SpinePlaneBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.SpinePlaneBuilderobject1,NXOpen.GeometricUtilities.SpinePlaneBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.SpinePointData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58248.html

Represents a spine point def object

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `GetLawValueAtPoint()` | `unsafeNXOpen.Expression` | Returns the law value at the specified pointMore... |
| `GetParentSpine()` | `unsafeNXOpen.Section` | Returns the parent spine on which spine point is definedMore... |
| `SetLawValueAtPoint(string valString)` | `unsafe void` | Sets the law value at the specified pointMore... |
| `SetParentSpine(NXOpen.Sectionparent)` | `unsafe void` | Sets the parent spine on which spine point is definedMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `ParameterLength[get, set]` | `unsafe double` | Returns or sets the parameter in arc lengthMore... |
| `ParameterPercent[get, set]` | `unsafe double` | Returns or sets the parameter in percent arc lengthMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.SpinePointDataCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58252.html

This class contains the factory methods for creating a SpinePointData object

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateSpinePointData(double lawValue, double parameter,NXOpen.Sectionparent)` | `unsafeNXOpen.GeometricUtilities.SpinePointData` | Creates a SpinePointData object.More... |
| `CreateSpinePointData(NXOpen.ExpressionlawValueExpression, double parameter,NXOpen.Sectionparent)` | `unsafeNXOpen.GeometricUtilities.SpinePointData` | Creates a SpinePointData object with expression.More... |
| `ToArray()` | `NXOpen.GeometricUtilities.SpinePointData[]` | Returns an array ofNXOpen.GeometricUtilities.SpinePointDataobjects.More... |
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

## NXOpen.GeometricUtilities.SpiralPattern

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58256.html

the Spiral pattern definition

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
| `DirectionType[get, set]` | `unsafeNXOpen.GeometricUtilities.SpiralPattern.OrientType` | Returns or sets the type of spiral direction methodMore... |
| `HorizontalRef[get]` | `unsafeNXOpen.GeometricUtilities.HorizontalReference` | Returns the horizontal referenceMore... |
| `NumberOfTurns[get]` | `unsafeNXOpen.Expression` | Returns the number of turns of spiralMore... |
| `PitchAlongSpiral[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDistancePatternSpacing` | Returns the pitch along spiral curveMore... |
| `RadialPitch[get]` | `unsafeNXOpen.Expression` | Returns the radial pitch of spiralMore... |
| `SizeSpiralType[get, set]` | `unsafeNXOpen.GeometricUtilities.SpiralPattern.SpiralDefineSize` | Returns or sets the size spiral typeMore... |
| `SpiralNormal[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the spiral normal vectorMore... |
| `TotalAngle[get]` | `unsafeNXOpen.Expression` | Returns the total angle of spiralMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.SplineExtensionBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58260.html

Spline extension builder class

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
| `EndExtensionOption[get, set]` | `unsafeNXOpen.GeometricUtilities.SplineExtensionBuilder.ExtensionOption` | Returns or sets the extension optionsMore... |
| `EndPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the point up to which end is extendedMore... |
| `EndValue[get]` | `unsafeNXOpen.Expression` | Returns the end valueMore... |
| `IsSymmetric[get, set]` | `unsafe bool` | Returns or sets the flag indicating if extension is symmetry.More... |
| `StartExtensionOption[get, set]` | `unsafeNXOpen.GeometricUtilities.SplineExtensionBuilder.ExtensionOption` | Returns or sets the extension optionsMore... |
| `StartPoint[get, set]` | `unsafeNXOpen.Point` | Returns or sets the point up to which start is extendedMore... |
| `StartValue[get]` | `unsafeNXOpen.Expression` | Returns the start valueMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.StartHoleData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58268.html

Represents aNXOpen.GeometricUtilities.StartHoleData

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
| `BooleanOperation[get]` | `unsafeNXOpen.GeometricUtilities.BooleanOperation` | Returns the boolean operationMore... |
| `CounterboreDepth[get]` | `unsafeNXOpen.Expression` | Returns the counterbore depthMore... |
| `CounterboreDiameter[get]` | `unsafeNXOpen.Expression` | Returns the counterbore diameterMore... |
| `CountersinkAngle[get]` | `unsafeNXOpen.Expression` | Returns the countersink angleMore... |
| `CountersinkDiameter[get]` | `unsafeNXOpen.Expression` | Returns the countersink diameterMore... |
| `EndChamferAngle[get]` | `unsafeNXOpen.Expression` | Returns the end chamfer angleMore... |
| `EndChamferEnabled[get, set]` | `unsafe bool` | Returns or sets the end chamfer enabledMore... |
| `EndChamferOffset[get]` | `unsafeNXOpen.Expression` | Returns the end chamfer offsetMore... |
| `FitOption[get, set]` | `unsafe string` | Returns or sets the fit optionMore... |
| `HoleDiameter[get]` | `unsafeNXOpen.Expression` | Returns the hole diameterMore... |
| `HoleForm[get, set]` | `unsafeNXOpen.GeometricUtilities.StartHoleData.HoleForms` | Returns or sets the hole formMore... |
| `NeckChamferAngle[get]` | `unsafeNXOpen.Expression` | Returns the neck chamfer angleMore... |
| `NeckChamferEnabled[get, set]` | `unsafe bool` | Returns or sets the neck chamfer enabledMore... |
| `NeckChamferOffset[get]` | `unsafeNXOpen.Expression` | Returns the neck chamfer offsetMore... |
| `ReliefDepth[get]` | `unsafeNXOpen.Expression` | Returns the relief depthMore... |
| `ReliefEnabled[get, set]` | `unsafe bool` | Returns or sets the relief enabledMore... |
| `ScrewSize[get, set]` | `unsafe string` | Returns or sets the screw sizeMore... |
| `ScrewType[get, set]` | `unsafe string` | Returns or sets the screw typeMore... |
| `StartChamferAngle[get]` | `unsafeNXOpen.Expression` | Returns the start chamfer angleMore... |
| `StartChamferEnabled[get, set]` | `unsafe bool` | Returns or sets the start chamfer enabledMore... |
| `StartChamferOffset[get]` | `unsafeNXOpen.Expression` | Returns the start chamfer offsetMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.StepOptionBehavior

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58272.html

Represents aNXOpen.GeometricUtilities.StepOptionBehaviorIt provides several step options for controlling behavior when move face and so on

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
| `StepOption[get, set]` | `unsafeNXOpen.GeometricUtilities.StepOptionBehavior.StepOptionType` | Returns or sets the step optionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.StrokeGestureData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58276.html

Represents aNXOpen.GeometricUtilities.StrokeGestureData

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `AddPoint(NXOpen.GeometricUtilities.StrokeGestureData.Pointpoint)` | `unsafe void` | Appends a point to the strokeMore... |
| `Clear()` | `unsafe void` | Deletes all the pointsMore... |
| `GetPoints()` | `unsafeNXOpen.GeometricUtilities.StrokeGestureData.Point[]` | Queries all the pointsMore... |
| `SetDrawingPlane(NXOpen.Matrix3x3matrix)` | `unsafe void` | Defines the plane in which stroke gesture is executed.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `DrawingScale[get, set]` | `unsafe double` | Returns or sets the drawing scale.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.StrokeGestureData.Point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58280.html

Structure representing stroke point in absolute space

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Point(NXOpen.Point3dPosition, doubleSpeed)` | `` | Constructor for the Point struct.More... |


---

## NXOpen.GeometricUtilities.StyledSweepDoubleOnPathDimBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58284.html

Represents aNXOpen.GeometricUtilities.StyledSweepDoubleOnPathDimBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `ResetExtraData()` | `unsafe void` | Reset pivot position extra data.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
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
| `FirstLocation[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the first locationMore... |
| `SecondLocation[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the second locationMore... |
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

## NXOpen.GeometricUtilities.StyledSweepDoubleOnPathDimBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58288.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.StyledSweepDoubleOnPathDimBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.StyledSweepDoubleOnPathDimBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.StyledSweepDoubleOnPathDimBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.StyledSweepDoubleOnPathDimBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.StyledSweepDoubleOnPathDimBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.StyledSweepDoubleOnPathDimBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.StyledSweepDoubleOnPathDimBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.StyledSweepDoubleOnPathDimBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.StyledSweepDoubleOnPathDimBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.StyledSweepDoubleOnPathDimBuilderobject1,NXOpen.GeometricUtilities.StyledSweepDoubleOnPathDimBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.StyledSweepReferenceMethodBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58292.html

Represents aNXOpen.GeometricUtilities.StyledSweepReferenceMethodBuilder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `UpdateOnReferenceVectorReversal()` | `unsafe void` | Updates the builder based on reference vector senseMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `HasHingeVector[get, set]` | `unsafe bool` | Returns or sets a value indicating whether there is a hinge vectorMore... |
| `ReferenceCurve[get]` | `unsafeNXOpen.Section` | Returns the section orientation reference curve.More... |
| `ReferenceOption[get, set]` | `unsafeNXOpen.GeometricUtilities.StyledSweepReferenceMethodBuilder.ReferenceOptions` | Returns or sets the section orientation reference option.More... |
| `ReferenceVector[get, set]` | `unsafeNXOpen.Direction` | Returns or sets the section orientation reference vector.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.SupportPlaneData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58296.html

Represents aNXOpen.GeometricUtilities.SupportPlaneData

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
| `ExistingPlane[get, set]` | `unsafeNXOpen.DisplayableObject` | Returns or sets the existing face or planeMore... |
| `SupportPlane[get, set]` | `unsafeNXOpen.Plane` | Returns or sets the support planeMore... |
| `SupportPlaneLockStatus[get, set]` | `unsafeNXOpen.GeometricUtilities.SupportPlaneData.LockPlaneStatus` | Returns or sets the support plane lock statusMore... |
| `WorkView[get, set]` | `unsafeNXOpen.View` | Returns or sets the work view required when lock plane status isNXOpen.GeometricUtilities.SupportPlaneData.LockPlaneStatus.AfterFirstConstraintMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.SurfaceRangeBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58300.html

Represents the surface range and anchor builder

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
| `AnchorPosition[get, set]` | `unsafeNXOpen.GeometricUtilities.SurfaceRangeBuilder.AnchorPositionType` | Returns or sets the anchor positionMore... |
| `UEnd[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the u endMore... |
| `UStart[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the u startMore... |
| `VEnd[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the v endMore... |
| `VStart[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the v startMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.TangentMagnitudeBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58304.html

This class provides ability to specify the start and end tangent magnitude values

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
| `EndTangentMagnitude[get]` | `unsafeNXOpen.Expression` | Returns the end tangent magnitudeMore... |
| `StartTangentMagnitude[get]` | `unsafeNXOpen.Expression` | Returns the start tangent magnitudeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.TransformerData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58308.html

Transformation and orientation tool

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Activate(NXOpen.GeometricUtilities.TransformerData.ObjectTypeobjectType)` | `unsafe void` | Sets a component of the tool to be active.More... |
| `AlignToAbsoluteCoordinateSystem()` | `unsafe void` | Reorient the tool by aligning it to absolute coordinate systemMore... |
| `AlignToWorkCoordinateSystem()` | `unsafe void` | Reorient the tool by aligning it to work coordinate systemMore... |
| `ReorientByCoordinateSystem(NXOpen.Matrix3x3matrix)` | `unsafe void` | Reorient the tool by aligning it to a coordinate system.More... |
| `ReorientByDirection(NXOpen.GeometricUtilities.TransformerData.ObjectTypeobjectType,NXOpen.Vector3ddirection)` | `unsafe void` | Reorient the tool by changing its axis direction.More... |
| `Reposition(NXOpen.Point3dorigin,NXOpen.Matrix3x3matrix)` | `unsafe void` | Repositions the tool at a coordinate system.More... |
| `RepositionByOrigin(NXOpen.Point3dorigin)` | `unsafe void` | Repositions the tool by changing its origin.More... |
| `RepositionByPlane(NXOpen.GeometricUtilities.TransformerData.ObjectTypeobjectType,NXOpen.Point3dplaneOrigin,NXOpen.Vector3dplaneNormal)` | `unsafe void` | Repositions the tool by changing its plane.More... |
| `Reverse(NXOpen.GeometricUtilities.TransformerData.ObjectTypeaxisType)` | `unsafe void` | Reverses the axis.More... |
| `Rotate(NXOpen.GeometricUtilities.TransformerData.ObjectTypeaxisType, double angle)` | `unsafe void` | Rotates the tool.More... |
| `Scale(NXOpen.GeometricUtilities.TransformerData.ObjectTypeaxisType, double factor)` | `unsafe void` | Sets the scale factor.More... |
| `SetTransformationObject(NXOpen.GeometricUtilities.TransformerData.ObjectTypeobjectType)` | `unsafe void` | Sets a component of the tool using which transformation is started.More... |
| `StartTransformation()` | `unsafe void` | Sets current coordinate system as reference coordinate system for the transformation.More... |
| `Translate(NXOpen.GeometricUtilities.TransformerData.ObjectTypeaxisType, double distance)` | `unsafe void` | Translates the tool.More... |
| `UpdateOnOriginMove()` | `unsafe void` | Updates tool upon movement of the point representing origin.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |


---

## NXOpen.GeometricUtilities.TransitionCurveBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58312.html

This class provides ability to create a transition(bridge) curve between two adjacent setback curves

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
| `EndTangentDirection[get, set]` | `unsafeNXOpen.GeometricUtilities.TransitionCurveBuilder.TangentDirections` | Returns or sets the end tangent directionMore... |
| `EndTangentMagnitude[get]` | `unsafeNXOpen.Expression` | Returns the end tangent magnitudeMore... |
| `StartTangentDirection[get, set]` | `unsafeNXOpen.GeometricUtilities.TransitionCurveBuilder.TangentDirections` | Returns or sets the start tangent directionMore... |
| `StartTangentMagnitude[get]` | `unsafeNXOpen.Expression` | Returns the start tangent magnitudeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.TransitionCurveBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58316.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.TransitionCurveBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.TransitionCurveBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.TransitionCurveBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.TransitionCurveBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.TransitionCurveBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.TransitionCurveBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.TransitionCurveBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.TransitionCurveBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.TransitionCurveBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.TransitionCurveBuilderobject1,NXOpen.GeometricUtilities.TransitionCurveBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.TransitionLawNodeBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58320.html

Represents a law node with transition type

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Transition[get, set]` | `unsafeNXOpen.GeometricUtilities.TransitionLawNodeBuilder.TransitionType` | Returns or sets the transition typeMore... |
| `IsOccurrence[get]` | `unsafe bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `unsafe string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Location[get]` | `unsafeNXOpen.GeometricUtilities.OnPathDimensionBuilder` | Returns the location on pathMore... |
| `Name[get]` | `unsafe string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `unsafeNXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `unsafeNXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `unsafeNXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |
| `Value[get]` | `unsafeNXOpen.Expression` | Returns the value expressionMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |
| `IsOccurrence[get]` | `bool` | Returns whether this object is an occurrence or not.More... |
| `JournalIdentifier[get]` | `string` | Returns the identifier that would be recorded in a journal for this object.More... |
| `Name[get]` | `string` | Returns the custom name of the object.More... |
| `OwningComponent[get]` | `NXOpen.Assemblies.Component` | Returns the owning component, if this object is an occurrence.More... |
| `OwningPart[get]` | `NXOpen.BasePart` | Returns the owning part of this objectMore... |
| `Prototype[get]` | `NXOpen.INXObject` | Returns the prototype of this object if it is an occurrence.More... |


---

## NXOpen.GeometricUtilities.TransitionLawNodeBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58324.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.TransitionLawNodeBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.TransitionLawNodeBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.TransitionLawNodeBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.TransitionLawNodeBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.TransitionLawNodeBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.TransitionLawNodeBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.TransitionLawNodeBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.TransitionLawNodeBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.TransitionLawNodeBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.TransitionLawNodeBuilderobject1,NXOpen.GeometricUtilities.TransitionLawNodeBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.TriangularFrameBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58328.html

Represents aNXOpen.GeometricUtilities.TriangularFrameBuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Subtype[get, set]` | `unsafeNXOpen.GeometricUtilities.TriangularFrameBuilder.Subtypes` | Returns or sets the subtypeMore... |
| `Anchor[get]` | `unsafeNXOpen.GeometricUtilities.AnchorLocatorBuilder` | Returns the anchor of the frameMore... |
| `AnchorAttachment[get, set]` | `unsafeNXOpen.GeometricUtilities.ShapeFrameBuilder.AnchorAttachmentType` | Returns or sets the anchor attachmentMore... |
| `NumberVertices[get]` | `unsafe int` | Returns the number of vertices of the frameMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.TrimCurveBoundingObjectBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58332.html

Represents aNXOpen.GeometricUtilities.TrimCurveBoundingObjectBuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `BoundingObject[get]` | `unsafeNXOpen.SelectDisplayableObject` | Returns the bounding objectMore... |
| `BoundingObjectList[get]` | `unsafeNXOpen.SelectDisplayableObjectList` | Returns the bounding object listMore... |
| `BoundingObjectMethodType[get, set]` | `unsafeNXOpen.GeometricUtilities.TrimCurveBoundingObjectBuilder.Method` | Returns or sets the bounding object enum typeMore... |
| `BoundingPlane[get, set]` | `unsafeNXOpen.Plane` | Returns or sets the bounding planeMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.TrimCurveBoundingObjectBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58336.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.TrimCurveBoundingObjectBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.TrimCurveBoundingObjectBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.TrimCurveBoundingObjectBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.TrimCurveBoundingObjectBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.TrimCurveBoundingObjectBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.TrimCurveBoundingObjectBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.TrimCurveBoundingObjectBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.TrimCurveBoundingObjectBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.TrimCurveBoundingObjectBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.TrimCurveBoundingObjectBuilderobject1,NXOpen.GeometricUtilities.TrimCurveBoundingObjectBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.TwoExpressionsCollectorSet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58340.html

Represents a two dimension list item builder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `ItemValueTwo[get]` | `unsafeNXOpen.Expression` | Returns the second expressionMore... |
| `Collector[get, set]` | `unsafeNXOpen.ScCollector` | Returns or sets the selectionMore... |
| `ItemFlipFlag[get, set]` | `unsafe bool` | Returns or sets the flip flagMore... |
| `ItemIndex[get, set]` | `unsafe int` | Returns or sets the index in the listMore... |
| `ItemValue[get]` | `unsafeNXOpen.Expression` | Returns the expressionMore... |
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

## NXOpen.GeometricUtilities.TwoExpressionsCollectorSetList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58344.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.TwoExpressionsCollectorSet[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.TwoExpressionsCollectorSet@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.TwoExpressionsCollectorSetobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.TwoExpressionsCollectorSetobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.TwoExpressionsCollectorSetobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.TwoExpressionsCollectorSet` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.TwoExpressionsCollectorSet[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.TwoExpressionsCollectorSet@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.TwoExpressionsCollectorSet[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.TwoExpressionsCollectorSetobject1,NXOpen.GeometricUtilities.TwoExpressionsCollectorSetobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.TwoExpressionsSectionSet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58348.html

Represents a two dimension list section item builder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `ItemValueTwo[get]` | `unsafeNXOpen.Expression` | Returns the second expressionMore... |
| `ItemFlipFlag[get, set]` | `unsafe bool` | Returns or sets the flip flagMore... |
| `ItemIndex[get, set]` | `unsafe int` | Returns or sets the index in the listMore... |
| `ItemValue[get]` | `unsafeNXOpen.Expression` | Returns the expressionMore... |
| `Section[get, set]` | `unsafeNXOpen.Section` | Returns or sets the sectionMore... |
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

## NXOpen.GeometricUtilities.TwoExpressionsSectionSetList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58352.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.TwoExpressionsSectionSet[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.TwoExpressionsSectionSet@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.TwoExpressionsSectionSetobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.TwoExpressionsSectionSetobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.TwoExpressionsSectionSetobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.TwoExpressionsSectionSet` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.TwoExpressionsSectionSet[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.TwoExpressionsSectionSet@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.TwoExpressionsSectionSet[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.TwoExpressionsSectionSetobject1,NXOpen.GeometricUtilities.TwoExpressionsSectionSetobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.UVMapping.MakeSymmetricParameterizationData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58364.html

Make UV parameterization symmetric

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Point[get, set]` | `unsafeNXOpen.Point` | Returns or sets the point of symmetry.More... |
| `ReverseDirection[get, set]` | `unsafe bool` | Returns or sets the reverse directionMore... |
| `Type[get, set]` | `unsafeNXOpen.GeometricUtilities.UVMapping.MakeSymmetricParameterizationData.Types` | Returns or sets the typeMore... |
| `UVPatches[get]` | `unsafeNXOpen.SelectNXObject` | Returns the uv patchesMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.UVMapping.ReverseUVParameterizationData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58372.html

Reverse UV parameterization

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `CanReverseU[get, set]` | `unsafe bool` | Returns or sets the flag indicating if U direction to be reversed.More... |
| `CanReverseV[get, set]` | `unsafe bool` | Returns or sets the flag indicating if V direction to be reversed.More... |
| `Patches[get]` | `unsafeNXOpen.SelectDisplayableObjectList` | Returns the object list.More... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.UVMapping.SelectUVMeshObjectData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58376.html

Represents UV mesh topology object selection

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `ClearAndAdd(NXOpen.NXObject[] objects,NXOpen.Viewview,NXOpen.Point3dpoint)` | `unsafe void` | Clears the currently present objects and adds new objects.More... |
| `SetCursorLocation(NXOpen.Point3dpoint)` | `unsafe void` | Sets the cursor location in absolute coordinates.More... |
| `SetViewDirection(NXOpen.Vector3ddirection)` | `unsafe void` | Sets the view direction.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `SelectionList[get]` | `unsafeNXOpen.SelectDisplayableObjectList` | Returns the object list.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.UVMapping.TransformUVParameterizationData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58380.html

Transform UV parameterization by transforming patches in UV spaces

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Update()` | `unsafe void` | Updates the parameterization by applying the transformation.More... |
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
| `CanMoveToolOnly[get, set]` | `unsafe bool` | Returns or sets the flag indicating if only the transformation tool can be moved without affecting UV patches.More... |
| `CanRelocateToolToSelection[get, set]` | `unsafe bool` | Returns or sets the flat indicating if transformation tool can be relocated based on selected entities.More... |
| `CanReorientToolToSelection[get, set]` | `unsafe bool` | Returns or sets the flat indicating if transformation tool can be reoriented based on selected entities.More... |
| `CanScaleUniformly[get, set]` | `unsafe bool` | Returns or sets the flag indicating if UV patches can be scaled uniformly.More... |
| `UVMeshManipulator[get]` | `unsafeNXOpen.GeometricUtilities.UVMapping.UVMeshManipulatorData` | Returns the UV mesh manipulation Tool.More... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.UVMapping.UVMappingCollection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58384.html

This class contains the methods for creating and manipulating a UVMapping object

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateMakeSymmetricParameterizationData()` | `unsafeNXOpen.GeometricUtilities.UVMapping.MakeSymmetricParameterizationData` | Creates aNXOpen.GeometricUtilities.UVMapping.MakeSymmetricParameterizationDataMore... |
| `CreateReverseUVParameterizationData()` | `unsafeNXOpen.GeometricUtilities.UVMapping.ReverseUVParameterizationData` | Creates aNXOpen.GeometricUtilities.UVMapping.ReverseUVParameterizationDataMore... |
| `CreateTransformUVParameterizationData()` | `unsafeNXOpen.GeometricUtilities.UVMapping.TransformUVParameterizationData` | Creates aNXOpen.GeometricUtilities.UVMapping.TransformUVParameterizationDataMore... |
| `CreateUVParameterizationBuilder()` | `unsafeNXOpen.GeometricUtilities.UVMapping.UVParameterizationBuilder` | Creates aGeometricUtilities.UVMapping.UVParameterizationBuilderMore... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.UVMapping.UVMeshManipulatorData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58388.html

UV Mesh manipulation tool

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `SetTransformerToObject(NXOpen.GeometricUtilities.UVMapping.UVMeshManipulatorData.ObjectSelectionDataselectionData)` | `unsafe void` | Repositions theNXOpen.GeometricUtilities.TransformerDatato the specified entity.More... |
| `SetUAxisDirection(bool canAlignToUDirection)` | `unsafe void` | Aligns the U axis to U or V direction.More... |
| `SetVAxisDirection(bool canAlignToVDirection)` | `unsafe void` | Aligns the V axis to U or V direction.More... |
| `ClearAndAdd(NXOpen.NXObject[] objects,NXOpen.Viewview,NXOpen.Point3dpoint)` | `unsafe void` | Clears the currently present objects and adds new objects.More... |
| `SetCursorLocation(NXOpen.Point3dpoint)` | `unsafe void` | Sets the cursor location in absolute coordinates.More... |
| `SetViewDirection(NXOpen.Vector3ddirection)` | `unsafe void` | Sets the view direction.More... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `Transformer[get]` | `unsafeNXOpen.GeometricUtilities.TransformerData` | Returns the transformation tool.More... |
| `SelectionList[get]` | `unsafeNXOpen.SelectDisplayableObjectList` | Returns the object list.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.UVMapping.UVMeshManipulatorData.ObjectSelectionData

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58392.html

Contains object selection information


---

## NXOpen.GeometricUtilities.UVMapping.UVParameterizationBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58400.html

Represents a UVParameterization builder

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Evaluate()` | `unsafe void` | Evaluates parameterizationMore... |
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
| `Faces[get]` | `unsafeNXOpen.ScCollector` | Returns the facesMore... |
| `NumberOfGridLines[get, set]` | `unsafe int` | Returns or sets the number of grid linesMore... |
| `OuterBoundarySeedEdge[get]` | `unsafeNXOpen.SelectEdge` | Returns the seed edgeMore... |
| `RipEdges[get]` | `unsafeNXOpen.Section` | Returns the rip edgesMore... |
| `TessellationResolution[get, set]` | `unsafeNXOpen.GeometricUtilities.UVMapping.UVParameterizationBuilder.TessellationResolutions` | Returns or sets the tessellation resolutionMore... |
| `Type[get, set]` | `unsafeNXOpen.GeometricUtilities.UVMapping.UVParameterizationBuilder.ParameterizationTypes` | Returns or sets the preserving typeMore... |
| `UDirectionCurve[get]` | `unsafeNXOpen.SelectTaggedObject` | Returns a single edge or curve used to define U direction.More... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.UnitCellBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58356.html

Represents a GeometricUtilities

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
| `ApproximateSourceHexMeshSize[get]` | `unsafeNXOpen.Expression` | Returns the approximate size of hexaherdal mesh elementMore... |
| `CellType[get, set]` | `unsafeNXOpen.GeometricUtilities.UnitCellBuilder.UnitCellType` | Returns or sets the unit cell typeMore... |
| `CellTypeName[get, set]` | `unsafe string` | Returns or sets the name of the unit cell type.More... |
| `CustomUnitCellFile[get, set]` | `unsafe string` | Returns or sets the native file browser0More... |
| `EdgeLength[get]` | `unsafeNXOpen.Expression` | Returns the edge length of the unit cell bounding box, and effective only when the bounding box is a uniform cubeMore... |
| `IsUniformCube[get, set]` | `unsafe bool` | Returns or sets whether the unit cell bounding box is a uniform cubeMore... |
| `SizeX[get]` | `unsafeNXOpen.Expression` | Returns the size of the unit cell bounding box in x axis, and effective only when the bounding box is not a uniform cubeMore... |
| `SizeY[get]` | `unsafeNXOpen.Expression` | Returns the size of the unit cell bounding box in y axis, and effective only when the bounding box is not a uniform cubeMore... |
| `SizeZ[get]` | `unsafeNXOpen.Expression` | Returns the size of the unit cell bounding box in z axis, and effective only when the bounding box is not a uniform cubeMore... |
| `UnitCellBody[get]` | `unsafeNXOpen.ScCollector` | Returns the sheet or solid body that define the seed body for body lattice type.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.UnnestModuleBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58360.html

Represents aNXOpen.GeometricUtilities.UnnestModuleBuilder

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `ModuleToUnnest[get]` | `unsafeNXOpen.Features.SelectFeature` | Returns the module to unnestMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.VoronoiItemBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58404.html

Represents a local specification of pore size and rod diameter for a Voronoi lattice

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `PoreSize[get]` | `unsafeNXOpen.Expression` | Returns the pore size for the given item in the listMore... |
| `RodDiameter[get]` | `unsafeNXOpen.Expression` | Returns the rod diameter for the given iteem in the listMore... |
| `Selection[get]` | `unsafeNXOpen.SelectDisplayableObjectList` | Returns the select object list which contains faces or pointsMore... |
| `PreviewBuilder[get]` | `unsafeNXOpen.PreviewBuilder` | Returns the preview builder subobject.More... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.VoronoiItemBuilderList

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58408.html

Represents a list of objects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Append(NXOpen.GeometricUtilities.VoronoiItemBuilder[] objects)` | `unsafe void` | Appends a set of objects to the listMore... |
| `Append(NXOpen.GeometricUtilities.VoronoiItemBuilder@object)` | `unsafe void` | Appends an object to the listMore... |
| `Clear()` | `unsafe void` | Clears the entire list without deleting the objects.More... |
| `Clear(NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Clears the entire listMore... |
| `ClearIndex(int deleteIdx)` | `unsafe void` | Deletes the item at the index specified.More... |
| `Erase(int index)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(int index,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object at the given position from the list.More... |
| `Erase(NXOpen.GeometricUtilities.VoronoiItemBuilderobj)` | `unsafe void` | Erases the object from the list, but does not delete the object.More... |
| `Erase(NXOpen.GeometricUtilities.VoronoiItemBuilderobj,NXOpen.ObjectList.DeleteOptiondeleteOption)` | `unsafe void` | Erases the object from the list.More... |
| `FindIndex(NXOpen.GeometricUtilities.VoronoiItemBuilderobj)` | `unsafe int` | Finds the index where the input object appears.More... |
| `FindItem(int index)` | `unsafeNXOpen.GeometricUtilities.VoronoiItemBuilder` | Returns the object at the input index.More... |
| `GetContents()` | `unsafeNXOpen.GeometricUtilities.VoronoiItemBuilder[]` | Gets the contents of the entire listMore... |
| `Insert(int location,NXOpen.GeometricUtilities.VoronoiItemBuilder@object)` | `unsafe void` | Inserts an object at the specified locationMore... |
| `MoveToBottom(int index)` | `unsafe void` | Move object at the specified location to the bottom of the list.More... |
| `MoveToTop(int index)` | `unsafe void` | Move object at the specified location to the top of the list.More... |
| `SetContents(NXOpen.GeometricUtilities.VoronoiItemBuilder[] objects)` | `unsafe void` | Sets the contents of the entire list.More... |
| `Swap(int index1, int index2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
| `Swap(NXOpen.GeometricUtilities.VoronoiItemBuilderobject1,NXOpen.GeometricUtilities.VoronoiItemBuilderobject2)` | `unsafe void` | Exchanges the position of two objects inside the list.More... |
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

## NXOpen.GeometricUtilities.VoronoiItemListBuilder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58412.html

the builder for a list ofGeometricUtilities.VoronoiItemBuilderobjects

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `CreateVoronoiItemBuilder()` | `unsafeNXOpen.GeometricUtilities.VoronoiItemBuilder` | Creates aGeometricUtilities.VoronoiItemBuilderMore... |
| `Validate()` | `unsafe bool` | Validate whether the inputs to the component are sufficient for commit to be called.More... |
| `PrintTestData(String variableName)` | `void` | <exclude>More... |
| `PrintTestData(String variableName, int lineNumber)` | `void` | <exclude>More... |
| `ToString()` | `override string` | Returns a String that represents the current Object.More... |
| `AsyncProcessMessage(IMessage msg,IMessageSinkreplySink)` | `IMessageCtrl` | Asynchronously processes the given message.More... |
| `SyncProcessMessage(IMessage msg)` | `IMessage` | Synchronously processes the given message.More... |

### 属性

| 属性名 | 类型 | 说明 |
|--------|------|------|
| `List[get]` | `unsafeNXOpen.GeometricUtilities.VoronoiItemBuilderList` | Returns a list ofGeometricUtilities.VoronoiItemBuilderobjectsMore... |
| `Tag[get]` | `Tag` | Returns the tag of this object.More... |
| `NextSink[get]` | `IMessageSink` | Gets the next message sink in the sink chain.More... |


---

## NXOpen.GeometricUtilities.WaveLinkRepository

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/nxopen_net/a58416.html

Represents aNXOpen.GeometricUtilities.WaveLinkRepository

### 方法

| 方法名 | 返回类型 | 说明 |
|--------|----------|------|
| `Destroy()` | `unsafe void` | Destroy the link repositoryMore... |
| `SetBuilder(NXOpen.Builderbuilder)` | `unsafe void` | Set the builder of the active command.More... |
| `SetLink(NXOpen.Features.FeaturelinkFeature)` | `unsafe void` | Set the link created by interpart selectionMore... |
| `SetNonFeatureApplication(bool flag)` | `unsafe void` | Specify if the client is non-feature based application or not.More... |
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
