# UF_CURVE 函数参考

> 共 273 个函数

---

## 目录

- [UF_CURVE #Defines](#uf_curve #defines)
- [UF_CURVE Enumerations](#uf_curve enumerations)
- [UF_CURVE Files](#uf_curve files)
- [UF_CURVE Functions](#uf_curve functions)
- [UF_CURVE Structures](#uf_curve structures)
- [UF_CURVE Unions](#uf_curve unions)
- [UF_CURVE_2_CURVE](#uf_curve_2_curve)
- [UF_CURVE_3_CURVE](#uf_curve_3_curve)
- [UF_CURVE_AMBIGUOUS_ENDS](#uf_curve_ambiguous_ends)
- [UF_CURVE_ANGLES_EXCEED_2PI](#uf_curve_angles_exceed_2pi)
- [UF_CURVE_ANGLE_INVALID](#uf_curve_angle_invalid)
- [UF_CURVE_BCMMCP_s](#uf_curve_bcmmcp_s)
- [UF_CURVE_CANT_EVAL_FIXED_LENGTH](#uf_curve_cant_eval_fixed_length)
- [UF_CURVE_CIRCLE_IN_FILLET](#uf_curve_circle_in_fillet)
- [UF_CURVE_CIRCULAR_SHAPE](#uf_curve_circular_shape)
- [UF_CURVE_CLOSED_NON_PERIODIC_CURVE](#uf_curve_closed_non_periodic_curve)
- [UF_CURVE_CLOSED_PERIODIC_CURVE](#uf_curve_closed_periodic_curve)
- [UF_CURVE_CONT_ORDER_ILLEGAL](#uf_curve_cont_order_illegal)
- [UF_CURVE_CRVATR_AUTO_DIR](#uf_curve_crvatr_auto_dir)
- [UF_CURVE_CRVATR_NONE](#uf_curve_crvatr_none)
- [UF_CURVE_CRVATR_VEC](#uf_curve_crvatr_vec)
- [UF_CURVE_CURVATURE](#uf_curve_curvature)
- [UF_CURVE_ENDPOINTS_Z_DIFFERENT](#uf_curve_endpoints_z_different)
- [UF_CURVE_FILLET_IN_CIRCLE](#uf_curve_fillet_in_circle)
- [UF_CURVE_INVALID_SUBTYPE](#uf_curve_invalid_subtype)
- [UF_CURVE_LINEAR_SHAPE](#uf_curve_linear_shape)
- [UF_CURVE_LINE_ARC__is_arc_equal](#uf_curve_line_arc__is_arc_equal)
- [UF_CURVE_LINE_ARC__is_line_equal](#uf_curve_line_arc__is_line_equal)
- [UF_CURVE_LOC](#uf_curve_loc)
- [UF_CURVE_LOC_1STDERV](#uf_curve_loc_1stderv)
- [UF_CURVE_LOC_1STDERV_2NDDERV](#uf_curve_loc_1stderv_2ndderv)
- [UF_CURVE_NATURAL_SHAPE](#uf_curve_natural_shape)
- [UF_CURVE_NOT_AN_ARC_TAG](#uf_curve_not_an_arc_tag)
- [UF_CURVE_NOT_A_CONIC](#uf_curve_not_a_conic)
- [UF_CURVE_NOT_A_CONIC_TAG](#uf_curve_not_a_conic_tag)
- [UF_CURVE_NOT_A_LINE_TAG](#uf_curve_not_a_line_tag)
- [UF_CURVE_NOT_A_MATRIX_TAG](#uf_curve_not_a_matrix_tag)
- [UF_CURVE_NOT_A_POINT_TAG](#uf_curve_not_a_point_tag)
- [UF_CURVE_NOT_A_SPLINE_TAG](#uf_curve_not_a_spline_tag)
- [UF_CURVE_OPEN_CURVE](#uf_curve_open_curve)
- [UF_CURVE_SLOPE_AUTO](#uf_curve_slope_auto)
- [UF_CURVE_SLOPE_DIR](#uf_curve_slope_dir)
- [UF_CURVE_SLOPE_NONE](#uf_curve_slope_none)
- [UF_CURVE_SLOPE_VEC](#uf_curve_slope_vec)
- [UF_CURVE_SPLINE_CANT_CREATE](#uf_curve_spline_cant_create)
- [UF_CURVE_SPLINE_DEGENERATE](#uf_curve_spline_degenerate)
- [UF_CURVE_SPLINE_ILLEGAL_DATA](#uf_curve_spline_illegal_data)
- [UF_CURVE_SPLINE_WEIGHT_NONPOS](#uf_curve_spline_weight_nonpos)
- [UF_CURVE_START_EXCEEDS_END](#uf_curve_start_exceeds_end)
- [UF_CURVE_STATE_CLAMPED](#uf_curve_state_clamped)
- [UF_CURVE_STATE_CLOSED](#uf_curve_state_closed)
- [UF_CURVE_STATE_DEFINED](#uf_curve_state_defined)
- [UF_CURVE_STATE_DEGENERACY](#uf_curve_state_degeneracy)
- [UF_CURVE_STATE_G1_DISCONTINUITY](#uf_curve_state_g1_discontinuity)
- [UF_CURVE_STATE_IS_FIXED](#uf_curve_state_is_fixed)
- [UF_CURVE_STATE_KNOT_DECREASING](#uf_curve_state_knot_decreasing)
- [UF_CURVE_STATE_KNOT_MULT](#uf_curve_state_knot_mult)
- [UF_CURVE_STATE_KNOT_NONC0](#uf_curve_state_knot_nonc0)
- [UF_CURVE_STATE_KNOT_TOOCLOSE](#uf_curve_state_knot_tooclose)
- [UF_CURVE_STATE_NOT_TRIMMED](#uf_curve_state_not_trimmed)
- [UF_CURVE_STATE_PERIODIC](#uf_curve_state_periodic)
- [UF_CURVE_STATE_RANGE_END](#uf_curve_state_range_end)
- [UF_CURVE_STATE_RANGE_START](#uf_curve_state_range_start)
- [UF_CURVE_STATE_SMOOTHED_TO_CN](#uf_curve_state_smoothed_to_cn)
- [UF_CURVE_STATE_UNNORMALIZED](#uf_curve_state_unnormalized)
- [UF_CURVE_TANGENT](#uf_curve_tangent)
- [UF_CURVE_TANGENT_OUTSIDE](#uf_curve_tangent_outside)
- [UF_CURVE_TRIM_MULT_PTS](#uf_curve_trim_mult_pts)
- [UF_CURVE_add_faces_ocf_data](#uf_curve_add_faces_ocf_data)
- [UF_CURVE_add_string_to_ocf_data](#uf_curve_add_string_to_ocf_data)
- [UF_CURVE_arc_s](#uf_curve_arc_s)
- [UF_CURVE_ask_arc_data](#uf_curve_ask_arc_data)
- [UF_CURVE_ask_arc_length](#uf_curve_ask_arc_length)
- [UF_CURVE_ask_bridge_feature](#uf_curve_ask_bridge_feature)
- [UF_CURVE_ask_centroid](#uf_curve_ask_centroid)
- [UF_CURVE_ask_combine_curves](#uf_curve_ask_combine_curves)
- [UF_CURVE_ask_conic_data](#uf_curve_ask_conic_data)
- [UF_CURVE_ask_curve_fit_data](#uf_curve_ask_curve_fit_data)
- [UF_CURVE_ask_curve_inflections](#uf_curve_ask_curve_inflections)
- [UF_CURVE_ask_curve_struct](#uf_curve_ask_curve_struct)
- [UF_CURVE_ask_curve_struct_data](#uf_curve_ask_curve_struct_data)
- [UF_CURVE_ask_curve_turn_angle](#uf_curve_ask_curve_turn_angle)
- [UF_CURVE_ask_feature_curves](#uf_curve_ask_feature_curves)
- [UF_CURVE_ask_int_curve_parents](#uf_curve_ask_int_curve_parents)
- [UF_CURVE_ask_int_curves](#uf_curve_ask_int_curves)
- [UF_CURVE_ask_int_parms](#uf_curve_ask_int_parms)
- [UF_CURVE_ask_int_parms_sc](#uf_curve_ask_int_parms_sc)
- [UF_CURVE_ask_isocline](#uf_curve_ask_isocline)
- [UF_CURVE_ask_joined_parms](#uf_curve_ask_joined_parms)
- [UF_CURVE_ask_line_arc_data](#uf_curve_ask_line_arc_data)
- [UF_CURVE_ask_line_arc_output](#uf_curve_ask_line_arc_output)
- [UF_CURVE_ask_line_data](#uf_curve_ask_line_data)
- [UF_CURVE_ask_ocf_data](#uf_curve_ask_ocf_data)
- [UF_CURVE_ask_offset_curves](#uf_curve_ask_offset_curves)
- [UF_CURVE_ask_offset_direction_2](#uf_curve_ask_offset_direction_2)
- [UF_CURVE_ask_offset_parms](#uf_curve_ask_offset_parms)
- [UF_CURVE_ask_parameterization](#uf_curve_ask_parameterization)
- [UF_CURVE_ask_point_data](#uf_curve_ask_point_data)
- [UF_CURVE_ask_proj_curve_parents](#uf_curve_ask_proj_curve_parents)
- [UF_CURVE_ask_proj_curves](#uf_curve_ask_proj_curves)
- [UF_CURVE_ask_spline_data](#uf_curve_ask_spline_data)
- [UF_CURVE_ask_spline_feature](#uf_curve_ask_spline_feature)
- [UF_CURVE_ask_spline_thru_pts](#uf_curve_ask_spline_thru_pts)
- [UF_CURVE_ask_trim](#uf_curve_ask_trim)
- [UF_CURVE_ask_wrap_curve_parents](#uf_curve_ask_wrap_curve_parents)
- [UF_CURVE_ask_wrap_curves](#uf_curve_ask_wrap_curves)
- [UF_CURVE_ask_wrap_parms](#uf_curve_ask_wrap_parms)
- [UF_CURVE_asso_arc_subtype_e](#uf_curve_asso_arc_subtype_e)
- [UF_CURVE_auto_join_curves](#uf_curve_auto_join_curves)
- [UF_CURVE_bridge_data_s](#uf_curve_bridge_data_s)
- [UF_CURVE_bridge_method_e](#uf_curve_bridge_method_e)
- [UF_CURVE_combine_curves_direction_s](#uf_curve_combine_curves_direction_s)
- [UF_CURVE_conic_s](#uf_curve_conic_s)
- [UF_CURVE_constraint_s](#uf_curve_constraint_s)
- [UF_CURVE_constraint_type_e](#uf_curve_constraint_type_e)
- [UF_CURVE_convert_conic_to_gen](#uf_curve_convert_conic_to_gen)
- [UF_CURVE_convert_conic_to_std](#uf_curve_convert_conic_to_std)
- [UF_CURVE_create_arc](#uf_curve_create_arc)
- [UF_CURVE_create_arc_3point](#uf_curve_create_arc_3point)
- [UF_CURVE_create_arc_3tangent](#uf_curve_create_arc_3tangent)
- [UF_CURVE_create_arc_center_radius](#uf_curve_create_arc_center_radius)
- [UF_CURVE_create_arc_center_tangent](#uf_curve_create_arc_center_tangent)
- [UF_CURVE_create_arc_point_center](#uf_curve_create_arc_point_center)
- [UF_CURVE_create_arc_point_point_radius](#uf_curve_create_arc_point_point_radius)
- [UF_CURVE_create_arc_point_point_tangent](#uf_curve_create_arc_point_point_tangent)
- [UF_CURVE_create_arc_point_tangent_point](#uf_curve_create_arc_point_tangent_point)
- [UF_CURVE_create_arc_point_tangent_radius](#uf_curve_create_arc_point_tangent_radius)
- [UF_CURVE_create_arc_point_tangent_tangent](#uf_curve_create_arc_point_tangent_tangent)
- [UF_CURVE_create_arc_tangent_point_point](#uf_curve_create_arc_tangent_point_point)
- [UF_CURVE_create_arc_tangent_point_tangent](#uf_curve_create_arc_tangent_point_tangent)
- [UF_CURVE_create_arc_tangent_tangent_point](#uf_curve_create_arc_tangent_tangent_point)
- [UF_CURVE_create_arc_tangent_tangent_radius](#uf_curve_create_arc_tangent_tangent_radius)
- [UF_CURVE_create_arc_thru_3pts](#uf_curve_create_arc_thru_3pts)
- [UF_CURVE_create_bridge_curve](#uf_curve_create_bridge_curve)
- [UF_CURVE_create_bridge_feature](#uf_curve_create_bridge_feature)
- [UF_CURVE_create_combine_curves](#uf_curve_create_combine_curves)
- [UF_CURVE_create_conic](#uf_curve_create_conic)
- [UF_CURVE_create_fillet](#uf_curve_create_fillet)
- [UF_CURVE_create_int_object](#uf_curve_create_int_object)
- [UF_CURVE_create_isocline](#uf_curve_create_isocline)
- [UF_CURVE_create_joined_curve](#uf_curve_create_joined_curve)
- [UF_CURVE_create_joined_feature](#uf_curve_create_joined_feature)
- [UF_CURVE_create_line](#uf_curve_create_line)
- [UF_CURVE_create_line_arc](#uf_curve_create_line_arc)
- [UF_CURVE_create_line_point_angle](#uf_curve_create_line_point_angle)
- [UF_CURVE_create_line_point_point](#uf_curve_create_line_point_point)
- [UF_CURVE_create_line_point_principal_axis](#uf_curve_create_line_point_principal_axis)
- [UF_CURVE_create_line_point_tangent](#uf_curve_create_line_point_tangent)
- [UF_CURVE_create_line_tangent_point](#uf_curve_create_line_tangent_point)
- [UF_CURVE_create_ocf_feature](#uf_curve_create_ocf_feature)
- [UF_CURVE_create_offset_curve](#uf_curve_create_offset_curve)
- [UF_CURVE_create_offset_object](#uf_curve_create_offset_object)
- [UF_CURVE_create_point](#uf_curve_create_point)
- [UF_CURVE_create_precise_outline](#uf_curve_create_precise_outline)
- [UF_CURVE_create_precise_outline_curves](#uf_curve_create_precise_outline_curves)
- [UF_CURVE_create_proj_curves](#uf_curve_create_proj_curves)
- [UF_CURVE_create_proj_curves1](#uf_curve_create_proj_curves1)
- [UF_CURVE_create_shadow_curves](#uf_curve_create_shadow_curves)
- [UF_CURVE_create_shadow_outline](#uf_curve_create_shadow_outline)
- [UF_CURVE_create_silhouette](#uf_curve_create_silhouette)
- [UF_CURVE_create_simplified_curve](#uf_curve_create_simplified_curve)
- [UF_CURVE_create_spline](#uf_curve_create_spline)
- [UF_CURVE_create_spline_feature](#uf_curve_create_spline_feature)
- [UF_CURVE_create_spline_thru_pts](#uf_curve_create_spline_thru_pts)
- [UF_CURVE_create_trim](#uf_curve_create_trim)
- [UF_CURVE_create_wrap_object](#uf_curve_create_wrap_object)
- [UF_CURVE_direction_e](#uf_curve_direction_e)
- [UF_CURVE_direction_struct_u](#uf_curve_direction_struct_u)
- [UF_CURVE_edit_arc_data](#uf_curve_edit_arc_data)
- [UF_CURVE_edit_bridge_feature](#uf_curve_edit_bridge_feature)
- [UF_CURVE_edit_by_curve_fit_data](#uf_curve_edit_by_curve_fit_data)
- [UF_CURVE_edit_combine_curves](#uf_curve_edit_combine_curves)
- [UF_CURVE_edit_conic_data](#uf_curve_edit_conic_data)
- [UF_CURVE_edit_int_object](#uf_curve_edit_int_object)
- [UF_CURVE_edit_isocline](#uf_curve_edit_isocline)
- [UF_CURVE_edit_joined_feature](#uf_curve_edit_joined_feature)
- [UF_CURVE_edit_length](#uf_curve_edit_length)
- [UF_CURVE_edit_line_arc](#uf_curve_edit_line_arc)
- [UF_CURVE_edit_line_data](#uf_curve_edit_line_data)
- [UF_CURVE_edit_move_mult_points](#uf_curve_edit_move_mult_points)
- [UF_CURVE_edit_ocf_feature](#uf_curve_edit_ocf_feature)
- [UF_CURVE_edit_offset_object](#uf_curve_edit_offset_object)
- [UF_CURVE_edit_point_data](#uf_curve_edit_point_data)
- [UF_CURVE_edit_proj_curves](#uf_curve_edit_proj_curves)
- [UF_CURVE_edit_proj_curves1](#uf_curve_edit_proj_curves1)
- [UF_CURVE_edit_spline_feature](#uf_curve_edit_spline_feature)
- [UF_CURVE_edit_spline_thru_pts](#uf_curve_edit_spline_thru_pts)
- [UF_CURVE_edit_trim](#uf_curve_edit_trim)
- [UF_CURVE_edit_trim_curve](#uf_curve_edit_trim_curve)
- [UF_CURVE_edit_with_template](#uf_curve_edit_with_template)
- [UF_CURVE_edit_wrap_object](#uf_curve_edit_wrap_object)
- [UF_CURVE_end_type_e](#uf_curve_end_type_e)
- [UF_CURVE_evaluate_curve](#uf_curve_evaluate_curve)
- [UF_CURVE_evaluate_curve_structure](#uf_curve_evaluate_curve_structure)
- [UF_CURVE_fit_error_s](#uf_curve_fit_error_s)
- [UF_CURVE_fix_spline_data](#uf_curve_fix_spline_data)
- [UF_CURVE_free_curve_struct](#uf_curve_free_curve_struct)
- [UF_CURVE_free_ocf_data](#uf_curve_free_ocf_data)
- [UF_CURVE_free_offset_parms](#uf_curve_free_offset_parms)
- [UF_CURVE_free_trim](#uf_curve_free_trim)
- [UF_CURVE_free_wrap_parms](#uf_curve_free_wrap_parms)
- [UF_CURVE_genconic_s](#uf_curve_genconic_s)
- [UF_CURVE_help_data_s](#uf_curve_help_data_s)
- [UF_CURVE_help_data_type_e](#uf_curve_help_data_type_e)
- [UF_CURVE_init_ocf_data](#uf_curve_init_ocf_data)
- [UF_CURVE_init_proj_curves_data](#uf_curve_init_proj_curves_data)
- [UF_CURVE_init_proj_curves_data1](#uf_curve_init_proj_curves_data1)
- [UF_CURVE_intersect](#uf_curve_intersect)
- [UF_CURVE_intersect_info_s](#uf_curve_intersect_info_s)
- [UF_CURVE_is_spline_in_sync](#uf_curve_is_spline_in_sync)
- [UF_CURVE_is_spline_self_int](#uf_curve_is_spline_self_int)
- [UF_CURVE_join_types](#uf_curve_join_types)
- [UF_CURVE_limit_s](#uf_curve_limit_s)
- [UF_CURVE_limit_type_e](#uf_curve_limit_type_e)
- [UF_CURVE_line_arc_s](#uf_curve_line_arc_s)
- [UF_CURVE_line_arc_type_e](#uf_curve_line_arc_type_e)
- [UF_CURVE_line_s](#uf_curve_line_s)
- [UF_CURVE_modify_offsets_in_string](#uf_curve_modify_offsets_in_string)
- [UF_CURVE_ocf_ask_curves](#uf_curve_ocf_ask_curves)
- [UF_CURVE_ocf_cross_boundaries_e](#uf_curve_ocf_cross_boundaries_e)
- [UF_CURVE_ocf_data_s](#uf_curve_ocf_data_s)
- [UF_CURVE_ocf_face_data_s](#uf_curve_ocf_face_data_s)
- [UF_CURVE_ocf_method_e](#uf_curve_ocf_method_e)
- [UF_CURVE_ocf_offset_pt_direction](#uf_curve_ocf_offset_pt_direction)
- [UF_CURVE_ocf_span_method_e](#uf_curve_ocf_span_method_e)
- [UF_CURVE_ocf_string_data_s](#uf_curve_ocf_string_data_s)
- [UF_CURVE_ocf_trim_method_e](#uf_curve_ocf_trim_method_e)
- [UF_CURVE_ocf_values_s](#uf_curve_ocf_values_s)
- [UF_CURVE_offset_axial_data_s](#uf_curve_offset_axial_data_s)
- [UF_CURVE_offset_data_s](#uf_curve_offset_data_s)
- [UF_CURVE_offset_def_u](#uf_curve_offset_def_u)
- [UF_CURVE_offset_distance_data_s](#uf_curve_offset_distance_data_s)
- [UF_CURVE_offset_distance_tangent_data_s](#uf_curve_offset_distance_tangent_data_s)
- [UF_CURVE_offset_draft_data_s](#uf_curve_offset_draft_data_s)
- [UF_CURVE_offset_draft_tangent_data_s](#uf_curve_offset_draft_tangent_data_s)
- [UF_CURVE_offset_type_e](#uf_curve_offset_type_e)
- [UF_CURVE_principal_axis_e](#uf_curve_principal_axis_e)
- [UF_CURVE_proj1_s](#uf_curve_proj1_s)
- [UF_CURVE_proj_s](#uf_curve_proj_s)
- [UF_CURVE_pt_slope_crvatr_s](#uf_curve_pt_slope_crvatr_s)
- [UF_CURVE_remove_string_from_ocf_data](#uf_curve_remove_string_from_ocf_data)
- [UF_CURVE_section_ask_parallel_data](#uf_curve_section_ask_parallel_data)
- [UF_CURVE_section_ask_perpcrv_data](#uf_curve_section_ask_perpcrv_data)
- [UF_CURVE_section_ask_planes_data](#uf_curve_section_ask_planes_data)
- [UF_CURVE_section_ask_radial_data](#uf_curve_section_ask_radial_data)
- [UF_CURVE_section_ask_type](#uf_curve_section_ask_type)
- [UF_CURVE_section_curve_ask_parents](#uf_curve_section_curve_ask_parents)
- [UF_CURVE_section_from_parallel_planes](#uf_curve_section_from_parallel_planes)
- [UF_CURVE_section_from_perpcrv_planes](#uf_curve_section_from_perpcrv_planes)
- [UF_CURVE_section_from_planes](#uf_curve_section_from_planes)
- [UF_CURVE_section_from_radial_planes](#uf_curve_section_from_radial_planes)
- [UF_CURVE_section_general_data_s](#uf_curve_section_general_data_s)
- [UF_CURVE_section_parallel_data_s](#uf_curve_section_parallel_data_s)
- [UF_CURVE_section_perpcrv_data_s](#uf_curve_section_perpcrv_data_s)
- [UF_CURVE_section_planes_data_s](#uf_curve_section_planes_data_s)
- [UF_CURVE_section_radial_data_s](#uf_curve_section_radial_data_s)
- [UF_CURVE_smooth_spline_data](#uf_curve_smooth_spline_data)
- [UF_CURVE_smooth_spline_data_st](#uf_curve_smooth_spline_data_st)
- [UF_CURVE_spline_s](#uf_curve_spline_s)
- [UF_CURVE_state_s](#uf_curve_state_s)
- [UF_CURVE_struct_s](#uf_curve_struct_s)
- [UF_CURVE_trim_bound_s](#uf_curve_trim_bound_s)
- [UF_CURVE_trim_incr_length_s](#uf_curve_trim_incr_length_s)
- [UF_CURVE_trim_mult_s](#uf_curve_trim_mult_s)
- [UF_CURVE_trim_one_bound_s](#uf_curve_trim_one_bound_s)
- [UF_CURVE_trim_opts_e](#uf_curve_trim_opts_e)
- [UF_CURVE_trim_s](#uf_curve_trim_s)
- [UF_CURVE_trim_to_u](#uf_curve_trim_to_u)
- [UF_CURVE_trim_total_length_s](#uf_curve_trim_total_length_s)
- [UF_CURVE_trim_two_bound_s](#uf_curve_trim_two_bound_s)
- [UF_CURVE_wrap_data_s](#uf_curve_wrap_data_s)
- [UF_CURVE_wrap_type_e](#uf_curve_wrap_type_e)
- [uf_curve.h](#uf_curve.h)

---

## UF_CURVE #Defines

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/contents.html#defines


---

## UF_CURVE Enumerations

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/contents.html#enumerations


---

## UF_CURVE Files

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/contents.html#files


---

## UF_CURVE Functions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/contents.html#functions


---

## UF_CURVE Structures

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/contents.html#structures


---

## UF_CURVE Unions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/contents.html#unions


---

## UF_CURVE_2_CURVE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_2_CURVE


---

## UF_CURVE_3_CURVE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_3_CURVE


---

## UF_CURVE_AMBIGUOUS_ENDS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_AMBIGUOUS_ENDS


---

## UF_CURVE_ANGLES_EXCEED_2PI

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_ANGLES_EXCEED_2PI


---

## UF_CURVE_ANGLE_INVALID

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_ANGLE_INVALID


---

## UF_CURVE_BCMMCP_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_BCMMCP_s.html


---

## UF_CURVE_CANT_EVAL_FIXED_LENGTH

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_CANT_EVAL_FIXED_LENGTH


---

## UF_CURVE_CIRCLE_IN_FILLET

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_CIRCLE_IN_FILLET


---

## UF_CURVE_CIRCULAR_SHAPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_CIRCULAR_SHAPE


---

## UF_CURVE_CLOSED_NON_PERIODIC_CURVE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_CLOSED_NON_PERIODIC_CURVE


---

## UF_CURVE_CLOSED_PERIODIC_CURVE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_CLOSED_PERIODIC_CURVE


---

## UF_CURVE_CONT_ORDER_ILLEGAL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_CONT_ORDER_ILLEGAL


---

## UF_CURVE_CRVATR_AUTO_DIR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_CRVATR_AUTO_DIR


---

## UF_CURVE_CRVATR_NONE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_CRVATR_NONE


---

## UF_CURVE_CRVATR_VEC

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_CRVATR_VEC


---

## UF_CURVE_CURVATURE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_CURVATURE


---

## UF_CURVE_ENDPOINTS_Z_DIFFERENT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_ENDPOINTS_Z_DIFFERENT


---

## UF_CURVE_FILLET_IN_CIRCLE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_FILLET_IN_CIRCLE


---

## UF_CURVE_INVALID_SUBTYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_INVALID_SUBTYPE


---

## UF_CURVE_LINEAR_SHAPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_LINEAR_SHAPE


---

## UF_CURVE_LINE_ARC__is_arc_equal

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_LINE_ARC__is_arc_equal


---

## UF_CURVE_LINE_ARC__is_line_equal

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_LINE_ARC__is_line_equal


---

## UF_CURVE_LOC

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_LOC


---

## UF_CURVE_LOC_1STDERV

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_LOC_1STDERV


---

## UF_CURVE_LOC_1STDERV_2NDDERV

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_LOC_1STDERV_2NDDERV


---

## UF_CURVE_NATURAL_SHAPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_NATURAL_SHAPE


---

## UF_CURVE_NOT_AN_ARC_TAG

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_NOT_AN_ARC_TAG


---

## UF_CURVE_NOT_A_CONIC

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_NOT_A_CONIC


---

## UF_CURVE_NOT_A_CONIC_TAG

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_NOT_A_CONIC_TAG


---

## UF_CURVE_NOT_A_LINE_TAG

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_NOT_A_LINE_TAG


---

## UF_CURVE_NOT_A_MATRIX_TAG

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_NOT_A_MATRIX_TAG


---

## UF_CURVE_NOT_A_POINT_TAG

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_NOT_A_POINT_TAG


---

## UF_CURVE_NOT_A_SPLINE_TAG

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_NOT_A_SPLINE_TAG


---

## UF_CURVE_OPEN_CURVE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_OPEN_CURVE


---

## UF_CURVE_SLOPE_AUTO

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_SLOPE_AUTO


---

## UF_CURVE_SLOPE_DIR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_SLOPE_DIR


---

## UF_CURVE_SLOPE_NONE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_SLOPE_NONE


---

## UF_CURVE_SLOPE_VEC

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_SLOPE_VEC


---

## UF_CURVE_SPLINE_CANT_CREATE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_SPLINE_CANT_CREATE


---

## UF_CURVE_SPLINE_DEGENERATE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_SPLINE_DEGENERATE


---

## UF_CURVE_SPLINE_ILLEGAL_DATA

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_SPLINE_ILLEGAL_DATA


---

## UF_CURVE_SPLINE_WEIGHT_NONPOS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_SPLINE_WEIGHT_NONPOS


---

## UF_CURVE_START_EXCEEDS_END

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_START_EXCEEDS_END


---

## UF_CURVE_STATE_CLAMPED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_STATE_CLAMPED


---

## UF_CURVE_STATE_CLOSED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_STATE_CLOSED


---

## UF_CURVE_STATE_DEFINED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_STATE_DEFINED


---

## UF_CURVE_STATE_DEGENERACY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_STATE_DEGENERACY


---

## UF_CURVE_STATE_G1_DISCONTINUITY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_STATE_G1_DISCONTINUITY


---

## UF_CURVE_STATE_IS_FIXED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_STATE_IS_FIXED


---

## UF_CURVE_STATE_KNOT_DECREASING

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_STATE_KNOT_DECREASING


---

## UF_CURVE_STATE_KNOT_MULT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_STATE_KNOT_MULT


---

## UF_CURVE_STATE_KNOT_NONC0

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_STATE_KNOT_NONC0


---

## UF_CURVE_STATE_KNOT_TOOCLOSE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_STATE_KNOT_TOOCLOSE


---

## UF_CURVE_STATE_NOT_TRIMMED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_STATE_NOT_TRIMMED


---

## UF_CURVE_STATE_PERIODIC

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_STATE_PERIODIC


---

## UF_CURVE_STATE_RANGE_END

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_STATE_RANGE_END


---

## UF_CURVE_STATE_RANGE_START

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_STATE_RANGE_START


---

## UF_CURVE_STATE_SMOOTHED_TO_CN

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_STATE_SMOOTHED_TO_CN


---

## UF_CURVE_STATE_UNNORMALIZED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_STATE_UNNORMALIZED


---

## UF_CURVE_TANGENT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_TANGENT


---

## UF_CURVE_TANGENT_OUTSIDE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_TANGENT_OUTSIDE


---

## UF_CURVE_TRIM_MULT_PTS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/uf_curve.html#UF_CURVE_TRIM_MULT_PTS


---

## UF_CURVE_add_faces_ocf_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_add_faces_ocf_data


---

## UF_CURVE_add_string_to_ocf_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_add_string_to_ocf_data


---

## UF_CURVE_arc_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_arc_s.html


---

## UF_CURVE_ask_arc_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_arc_data


---

## UF_CURVE_ask_arc_length

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_arc_length


---

## UF_CURVE_ask_bridge_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_bridge_feature


---

## UF_CURVE_ask_centroid

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_centroid


---

## UF_CURVE_ask_combine_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_combine_curves


---

## UF_CURVE_ask_conic_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_conic_data


---

## UF_CURVE_ask_curve_fit_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_curve_fit_data


---

## UF_CURVE_ask_curve_inflections

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_curve_inflections


---

## UF_CURVE_ask_curve_struct

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_curve_struct


---

## UF_CURVE_ask_curve_struct_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_curve_struct_data


---

## UF_CURVE_ask_curve_turn_angle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_curve_turn_angle


---

## UF_CURVE_ask_feature_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_feature_curves


---

## UF_CURVE_ask_int_curve_parents

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_int_curve_parents


---

## UF_CURVE_ask_int_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_int_curves


---

## UF_CURVE_ask_int_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_int_parms


---

## UF_CURVE_ask_int_parms_sc

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_int_parms_sc


---

## UF_CURVE_ask_isocline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_isocline


---

## UF_CURVE_ask_joined_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_joined_parms


---

## UF_CURVE_ask_line_arc_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_line_arc_data


---

## UF_CURVE_ask_line_arc_output

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_line_arc_output


---

## UF_CURVE_ask_line_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_line_data


---

## UF_CURVE_ask_ocf_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_ocf_data


---

## UF_CURVE_ask_offset_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_offset_curves


---

## UF_CURVE_ask_offset_direction_2

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_offset_direction_2


---

## UF_CURVE_ask_offset_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_offset_parms


---

## UF_CURVE_ask_parameterization

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_parameterization


---

## UF_CURVE_ask_point_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_point_data


---

## UF_CURVE_ask_proj_curve_parents

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_proj_curve_parents


---

## UF_CURVE_ask_proj_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_proj_curves


---

## UF_CURVE_ask_spline_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_spline_data


---

## UF_CURVE_ask_spline_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_spline_feature


---

## UF_CURVE_ask_spline_thru_pts

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_spline_thru_pts


---

## UF_CURVE_ask_trim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_trim


---

## UF_CURVE_ask_wrap_curve_parents

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_wrap_curve_parents


---

## UF_CURVE_ask_wrap_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_wrap_curves


---

## UF_CURVE_ask_wrap_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ask_wrap_parms


---

## UF_CURVE_asso_arc_subtype_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/types.html#UF_CURVE_asso_arc_subtype_e


---

## UF_CURVE_auto_join_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_auto_join_curves


---

## UF_CURVE_bridge_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_bridge_data_s.html


---

## UF_CURVE_bridge_method_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/types.html#UF_CURVE_bridge_method_e


---

## UF_CURVE_combine_curves_direction_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_combine_curves_direction_s.html


---

## UF_CURVE_conic_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_conic_s.html


---

## UF_CURVE_constraint_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_constraint_s.html


---

## UF_CURVE_constraint_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/types.html#UF_CURVE_constraint_type_e


---

## UF_CURVE_convert_conic_to_gen

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_convert_conic_to_gen


---

## UF_CURVE_convert_conic_to_std

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_convert_conic_to_std


---

## UF_CURVE_create_arc

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_arc


---

## UF_CURVE_create_arc_3point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_arc_3point


---

## UF_CURVE_create_arc_3tangent

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_arc_3tangent


---

## UF_CURVE_create_arc_center_radius

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_arc_center_radius


---

## UF_CURVE_create_arc_center_tangent

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_arc_center_tangent


---

## UF_CURVE_create_arc_point_center

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_arc_point_center


---

## UF_CURVE_create_arc_point_point_radius

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_arc_point_point_radius


---

## UF_CURVE_create_arc_point_point_tangent

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_arc_point_point_tangent


---

## UF_CURVE_create_arc_point_tangent_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_arc_point_tangent_point


---

## UF_CURVE_create_arc_point_tangent_radius

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_arc_point_tangent_radius


---

## UF_CURVE_create_arc_point_tangent_tangent

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_arc_point_tangent_tangent


---

## UF_CURVE_create_arc_tangent_point_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_arc_tangent_point_point


---

## UF_CURVE_create_arc_tangent_point_tangent

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_arc_tangent_point_tangent


---

## UF_CURVE_create_arc_tangent_tangent_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_arc_tangent_tangent_point


---

## UF_CURVE_create_arc_tangent_tangent_radius

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_arc_tangent_tangent_radius


---

## UF_CURVE_create_arc_thru_3pts

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_arc_thru_3pts


---

## UF_CURVE_create_bridge_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_bridge_curve


---

## UF_CURVE_create_bridge_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_bridge_feature


---

## UF_CURVE_create_combine_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_combine_curves


---

## UF_CURVE_create_conic

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_conic


---

## UF_CURVE_create_fillet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_fillet


---

## UF_CURVE_create_int_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_int_object


---

## UF_CURVE_create_isocline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_isocline


---

## UF_CURVE_create_joined_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_joined_curve


---

## UF_CURVE_create_joined_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_joined_feature


---

## UF_CURVE_create_line

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_line


---

## UF_CURVE_create_line_arc

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_line_arc


---

## UF_CURVE_create_line_point_angle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_line_point_angle


---

## UF_CURVE_create_line_point_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_line_point_point


---

## UF_CURVE_create_line_point_principal_axis

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_line_point_principal_axis


---

## UF_CURVE_create_line_point_tangent

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_line_point_tangent


---

## UF_CURVE_create_line_tangent_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_line_tangent_point


---

## UF_CURVE_create_ocf_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_ocf_feature


---

## UF_CURVE_create_offset_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_offset_curve


---

## UF_CURVE_create_offset_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_offset_object


---

## UF_CURVE_create_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_point


---

## UF_CURVE_create_precise_outline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_precise_outline


---

## UF_CURVE_create_precise_outline_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_precise_outline_curves


---

## UF_CURVE_create_proj_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_proj_curves


---

## UF_CURVE_create_proj_curves1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_proj_curves1


---

## UF_CURVE_create_shadow_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_shadow_curves


---

## UF_CURVE_create_shadow_outline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_shadow_outline


---

## UF_CURVE_create_silhouette

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_silhouette


---

## UF_CURVE_create_simplified_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_simplified_curve


---

## UF_CURVE_create_spline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_spline


---

## UF_CURVE_create_spline_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_spline_feature


---

## UF_CURVE_create_spline_thru_pts

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_spline_thru_pts


---

## UF_CURVE_create_trim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_trim


---

## UF_CURVE_create_wrap_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_create_wrap_object


---

## UF_CURVE_direction_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/types.html#UF_CURVE_direction_e


---

## UF_CURVE_direction_struct_u

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_direction_struct_u.html


---

## UF_CURVE_edit_arc_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_arc_data


---

## UF_CURVE_edit_bridge_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_bridge_feature


---

## UF_CURVE_edit_by_curve_fit_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_by_curve_fit_data


---

## UF_CURVE_edit_combine_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_combine_curves


---

## UF_CURVE_edit_conic_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_conic_data


---

## UF_CURVE_edit_int_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_int_object


---

## UF_CURVE_edit_isocline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_isocline


---

## UF_CURVE_edit_joined_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_joined_feature


---

## UF_CURVE_edit_length

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_length


---

## UF_CURVE_edit_line_arc

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_line_arc


---

## UF_CURVE_edit_line_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_line_data


---

## UF_CURVE_edit_move_mult_points

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_move_mult_points


---

## UF_CURVE_edit_ocf_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_ocf_feature


---

## UF_CURVE_edit_offset_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_offset_object


---

## UF_CURVE_edit_point_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_point_data


---

## UF_CURVE_edit_proj_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_proj_curves


---

## UF_CURVE_edit_proj_curves1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_proj_curves1


---

## UF_CURVE_edit_spline_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_spline_feature


---

## UF_CURVE_edit_spline_thru_pts

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_spline_thru_pts


---

## UF_CURVE_edit_trim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_trim


---

## UF_CURVE_edit_trim_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_trim_curve


---

## UF_CURVE_edit_with_template

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_with_template


---

## UF_CURVE_edit_wrap_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_edit_wrap_object


---

## UF_CURVE_end_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/types.html#UF_CURVE_end_type_e


---

## UF_CURVE_evaluate_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_evaluate_curve


---

## UF_CURVE_evaluate_curve_structure

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_evaluate_curve_structure


---

## UF_CURVE_fit_error_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_fit_error_s.html


---

## UF_CURVE_fix_spline_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_fix_spline_data


---

## UF_CURVE_free_curve_struct

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_free_curve_struct


---

## UF_CURVE_free_ocf_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_free_ocf_data


---

## UF_CURVE_free_offset_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_free_offset_parms


---

## UF_CURVE_free_trim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_free_trim


---

## UF_CURVE_free_wrap_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_free_wrap_parms


---

## UF_CURVE_genconic_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_genconic_s.html


---

## UF_CURVE_help_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_help_data_s.html


---

## UF_CURVE_help_data_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/types.html#UF_CURVE_help_data_type_e


---

## UF_CURVE_init_ocf_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_init_ocf_data


---

## UF_CURVE_init_proj_curves_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_init_proj_curves_data


---

## UF_CURVE_init_proj_curves_data1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_init_proj_curves_data1


---

## UF_CURVE_intersect

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_intersect


---

## UF_CURVE_intersect_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_intersect_info_s.html


---

## UF_CURVE_is_spline_in_sync

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_is_spline_in_sync


---

## UF_CURVE_is_spline_self_int

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_is_spline_self_int


---

## UF_CURVE_join_types

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/types.html#UF_CURVE_join_types


---

## UF_CURVE_limit_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_limit_s.html


---

## UF_CURVE_limit_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/types.html#UF_CURVE_limit_type_e


---

## UF_CURVE_line_arc_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_line_arc_s.html


---

## UF_CURVE_line_arc_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/types.html#UF_CURVE_line_arc_type_e


---

## UF_CURVE_line_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_line_s.html


---

## UF_CURVE_modify_offsets_in_string

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_modify_offsets_in_string


---

## UF_CURVE_ocf_ask_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ocf_ask_curves


---

## UF_CURVE_ocf_cross_boundaries_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/types.html#UF_CURVE_ocf_cross_boundaries_e


---

## UF_CURVE_ocf_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_ocf_data_s.html


---

## UF_CURVE_ocf_face_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_ocf_face_data_s.html


---

## UF_CURVE_ocf_method_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/types.html#UF_CURVE_ocf_method_e


---

## UF_CURVE_ocf_offset_pt_direction

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_ocf_offset_pt_direction


---

## UF_CURVE_ocf_span_method_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/types.html#UF_CURVE_ocf_span_method_e


---

## UF_CURVE_ocf_string_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_ocf_string_data_s.html


---

## UF_CURVE_ocf_trim_method_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/types.html#UF_CURVE_ocf_trim_method_e


---

## UF_CURVE_ocf_values_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_ocf_values_s.html


---

## UF_CURVE_offset_axial_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_offset_axial_data_s.html


---

## UF_CURVE_offset_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_offset_data_s.html


---

## UF_CURVE_offset_def_u

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_offset_def_u.html


---

## UF_CURVE_offset_distance_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_offset_distance_data_s.html


---

## UF_CURVE_offset_distance_tangent_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_offset_distance_tangent_data_s.html


---

## UF_CURVE_offset_draft_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_offset_draft_data_s.html


---

## UF_CURVE_offset_draft_tangent_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_offset_draft_tangent_data_s.html


---

## UF_CURVE_offset_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/types.html#UF_CURVE_offset_type_e


---

## UF_CURVE_principal_axis_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/types.html#UF_CURVE_principal_axis_e


---

## UF_CURVE_proj1_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_proj1_s.html


---

## UF_CURVE_proj_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_proj_s.html


---

## UF_CURVE_pt_slope_crvatr_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_pt_slope_crvatr_s.html


---

## UF_CURVE_remove_string_from_ocf_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_remove_string_from_ocf_data


---

## UF_CURVE_section_ask_parallel_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_section_ask_parallel_data


---

## UF_CURVE_section_ask_perpcrv_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_section_ask_perpcrv_data


---

## UF_CURVE_section_ask_planes_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_section_ask_planes_data


---

## UF_CURVE_section_ask_radial_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_section_ask_radial_data


---

## UF_CURVE_section_ask_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_section_ask_type


---

## UF_CURVE_section_curve_ask_parents

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_section_curve_ask_parents


---

## UF_CURVE_section_from_parallel_planes

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_section_from_parallel_planes


---

## UF_CURVE_section_from_perpcrv_planes

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_section_from_perpcrv_planes


---

## UF_CURVE_section_from_planes

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_section_from_planes


---

## UF_CURVE_section_from_radial_planes

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_section_from_radial_planes


---

## UF_CURVE_section_general_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_section_general_data_s.html


---

## UF_CURVE_section_parallel_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_section_parallel_data_s.html


---

## UF_CURVE_section_perpcrv_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_section_perpcrv_data_s.html


---

## UF_CURVE_section_planes_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_section_planes_data_s.html


---

## UF_CURVE_section_radial_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_section_radial_data_s.html


---

## UF_CURVE_smooth_spline_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_smooth_spline_data


---

## UF_CURVE_smooth_spline_data_st

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/global.html#UF_CURVE_smooth_spline_data_st


---

## UF_CURVE_spline_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_spline_s.html


---

## UF_CURVE_state_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_state_s.html


---

## UF_CURVE_struct_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_struct_s.html


---

## UF_CURVE_trim_bound_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_trim_bound_s.html


---

## UF_CURVE_trim_incr_length_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_trim_incr_length_s.html


---

## UF_CURVE_trim_mult_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_trim_mult_s.html


---

## UF_CURVE_trim_one_bound_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_trim_one_bound_s.html


---

## UF_CURVE_trim_opts_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/types.html#UF_CURVE_trim_opts_e


---

## UF_CURVE_trim_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_trim_s.html


---

## UF_CURVE_trim_to_u

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_trim_to_u.html


---

## UF_CURVE_trim_total_length_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_trim_total_length_s.html


---

## UF_CURVE_trim_two_bound_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_trim_two_bound_s.html


---

## UF_CURVE_wrap_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/UF_CURVE_wrap_data_s.html


---

## UF_CURVE_wrap_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/types.html#UF_CURVE_wrap_type_e


---

## uf_curve.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_curve/intro.html#uf_curve


---
