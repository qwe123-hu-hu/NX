# UF_MODL 函数参考

> 共 1233 个函数

---

## 目录

- [UF_MODL #Defines](#uf_modl #defines)
- [UF_MODL Callbacks](#uf_modl callbacks)
- [UF_MODL Enumerations](#uf_modl enumerations)
- [UF_MODL Files](#uf_modl files)
- [UF_MODL Functions](#uf_modl functions)
- [UF_MODL Structures](#uf_modl structures)
- [UF_MODL Unions](#uf_modl unions)
- [UF_MODL_ALONG_DRIVER_NORMALS](#uf_modl_along_driver_normals)
- [UF_MODL_ALONG_FIXED_VECTOR](#uf_modl_along_fixed_vector)
- [UF_MODL_ALONG_NORMAL](#uf_modl_along_normal)
- [UF_MODL_ANIMATION_CREATE_FAILED](#uf_modl_animation_create_failed)
- [UF_MODL_ANIMATION_UPDATE_FAILED](#uf_modl_animation_update_failed)
- [UF_MODL_APPLE_TORUS](#uf_modl_apple_torus)
- [UF_MODL_ARC_CENTER](#uf_modl_arc_center)
- [UF_MODL_ARC_TANGENT](#uf_modl_arc_tangent)
- [UF_MODL_ARRAYS_NON_DISTINCT](#uf_modl_arrays_non_distinct)
- [UF_MODL_BAD_ARRAY_LENGTH](#uf_modl_bad_array_length)
- [UF_MODL_BAD_DATUM_CONSTRAINT](#uf_modl_bad_datum_constraint)
- [UF_MODL_BLENDING_FACE](#uf_modl_blending_face)
- [UF_MODL_BLEND_CLIFF_OVERFLOW](#uf_modl_blend_cliff_overflow)
- [UF_MODL_BLEND_NOTCH_OVERFLOW](#uf_modl_blend_notch_overflow)
- [UF_MODL_BLEND_NO_OVERFLOW](#uf_modl_blend_no_overflow)
- [UF_MODL_BLEND_SMOOTH_OVERFLOW](#uf_modl_blend_smooth_overflow)
- [UF_MODL_BOTH_X_PERIODIC](#uf_modl_both_x_periodic)
- [UF_MODL_B_SURFACE_DRIVER](#uf_modl_b_surface_driver)
- [UF_MODL_CIRCULAR_EDGE](#uf_modl_circular_edge)
- [UF_MODL_CLOSED_NON_PERIODIC_CURVE](#uf_modl_closed_non_periodic_curve)
- [UF_MODL_CLOSED_PERIODIC_CURVE](#uf_modl_closed_periodic_curve)
- [UF_MODL_COMPARE_BOTH_ARE_SAME_PARTS](#uf_modl_compare_both_are_same_parts)
- [UF_MODL_COMPARE_EXAMINE_GEOM_FAILED_PART1](#uf_modl_compare_examine_geom_failed_part1)
- [UF_MODL_COMPARE_EXAMINE_GEOM_FAILED_PART2](#uf_modl_compare_examine_geom_failed_part2)
- [UF_MODL_COMPARE_INVALID_PART1](#uf_modl_compare_invalid_part1)
- [UF_MODL_COMPARE_INVALID_PART2](#uf_modl_compare_invalid_part2)
- [UF_MODL_COMPARE_NO_BODIES_PART1](#uf_modl_compare_no_bodies_part1)
- [UF_MODL_COMPARE_NO_BODIES_PART2](#uf_modl_compare_no_bodies_part2)
- [UF_MODL_COMP_CURR_VER](#uf_modl_comp_curr_ver)
- [UF_MODL_CONICAL_FACE](#uf_modl_conical_face)
- [UF_MODL_CONICAL_TOPOLOGY](#uf_modl_conical_topology)
- [UF_MODL_CONST_PARAMETER_EDGE](#uf_modl_const_parameter_edge)
- [UF_MODL_CONVERGENT_EDGE](#uf_modl_convergent_edge)
- [UF_MODL_CONVERGENT_FACE](#uf_modl_convergent_face)
- [UF_MODL_CYLINDRICAL_FACE](#uf_modl_cylindrical_face)
- [UF_MODL_CYLINDRICAL_TOPOLOGY](#uf_modl_cylindrical_topology)
- [UF_MODL_DEVCHK_FIRST_EDGE_NOT_ON_FIRST_FACE](#uf_modl_devchk_first_edge_not_on_first_face)
- [UF_MODL_DEVCHK_SAME_EDGE_FACE_COMBO_TWICE](#uf_modl_devchk_same_edge_face_combo_twice)
- [UF_MODL_DEVCHK_SAME_TAG_INPUT_TWICE](#uf_modl_devchk_same_tag_input_twice)
- [UF_MODL_DEVCHK_SECOND_EDGE_NOT_ON_SECOND_FACE](#uf_modl_devchk_second_edge_not_on_second_face)
- [UF_MODL_DEVCHK_TOO_FEW_CHECK_POINTS](#uf_modl_devchk_too_few_check_points)
- [UF_MODL_DEVCHK_TOO_FEW_U_CHECK_POINTS](#uf_modl_devchk_too_few_u_check_points)
- [UF_MODL_DEVCHK_TOO_FEW_V_CHECK_POINTS](#uf_modl_devchk_too_few_v_check_points)
- [UF_MODL_DEVCHK_WRONG_FIRST_CURVE_TAG](#uf_modl_devchk_wrong_first_curve_tag)
- [UF_MODL_DEVCHK_WRONG_FIRST_EDGE_TAG](#uf_modl_devchk_wrong_first_edge_tag)
- [UF_MODL_DEVCHK_WRONG_FIRST_FACE_TAG](#uf_modl_devchk_wrong_first_face_tag)
- [UF_MODL_DEVCHK_WRONG_SECOND_CURVE_TAG](#uf_modl_devchk_wrong_second_curve_tag)
- [UF_MODL_DEVCHK_WRONG_SECOND_EDGE_TAG](#uf_modl_devchk_wrong_second_edge_tag)
- [UF_MODL_DEVCHK_WRONG_SECOND_FACE_TAG](#uf_modl_devchk_wrong_second_face_tag)
- [UF_MODL_DOUGHNUT_TORUS](#uf_modl_doughnut_torus)
- [UF_MODL_DRAFTBODY_MATCHTYPE_TANGENTTOFACE_NOT_SUPPORTED](#uf_modl_draftbody_matchtype_tangenttoface_not_supported)
- [UF_MODL_DUPLICATE_ELEMENT](#uf_modl_duplicate_element)
- [UF_MODL_DYNAMIC_UPDATE_CONTINUOUS](#uf_modl_dynamic_update_continuous)
- [UF_MODL_DYNAMIC_UPDATE_INCREMENTAL](#uf_modl_dynamic_update_incremental)
- [UF_MODL_EDGE](#uf_modl_edge)
- [UF_MODL_ELLIPTICAL_EDGE](#uf_modl_elliptical_edge)
- [UF_MODL_ENDPOINT_1](#uf_modl_endpoint_1)
- [UF_MODL_ENDPOINT_2](#uf_modl_endpoint_2)
- [UF_MODL_END_POINT](#uf_modl_end_point)
- [UF_MODL_ERROR_SHIFT](#uf_modl_error_shift)
- [UF_MODL_ERR_BLEND_CANT_APPLY](#uf_modl_err_blend_cant_apply)
- [UF_MODL_ERR_BLEND_HASNO_INPUTDATA](#uf_modl_err_blend_hasno_inputdata)
- [UF_MODL_ERR_CANT_QUERY_PARMS_FOR_PSM_FACET_FACE](#uf_modl_err_cant_query_parms_for_psm_facet_face)
- [UF_MODL_ERR_CLOSEST_APPROACH_FAILED](#uf_modl_err_closest_approach_failed)
- [UF_MODL_ERR_INVALID_LS_WEIGHT](#uf_modl_err_invalid_ls_weight)
- [UF_MODL_ERR_MULTIPLE_BODIES](#uf_modl_err_multiple_bodies)
- [UF_MODL_ERR_NULL_SECTION](#uf_modl_err_null_section)
- [UF_MODL_ERR_PENDING_UPDATE](#uf_modl_err_pending_update)
- [UF_MODL_ERR_invalid_pointer](#uf_modl_err_invalid_pointer)
- [UF_MODL_EVAL](#uf_modl_eval)
- [UF_MODL_EVAL_ALL](#uf_modl_eval_all)
- [UF_MODL_EVAL_DERIV1](#uf_modl_eval_deriv1)
- [UF_MODL_EVAL_DERIV2](#uf_modl_eval_deriv2)
- [UF_MODL_EVAL_DERIV3](#uf_modl_eval_deriv3)
- [UF_MODL_EVAL_NORMAL](#uf_modl_eval_normal)
- [UF_MODL_EVAL_UNIT_NORMAL](#uf_modl_eval_unit_normal)
- [UF_MODL_FILE](#uf_modl_file)
- [UF_MODL_FIXED_LENGTH](#uf_modl_fixed_length)
- [UF_MODL_FLAT_TOPOLOGY](#uf_modl_flat_topology)
- [UF_MODL_FOREIGN_EDGE](#uf_modl_foreign_edge)
- [UF_MODL_FOREIGN_FACE](#uf_modl_foreign_face)
- [UF_MODL_FULL_THREAD](#uf_modl_full_thread)
- [UF_MODL_HORZ_CENTERLINE_PNT_1](#uf_modl_horz_centerline_pnt_1)
- [UF_MODL_HORZ_CENTERLINE_PNT_2](#uf_modl_horz_centerline_pnt_2)
- [UF_MODL_INCL_INSTANCES](#uf_modl_incl_instances)
- [UF_MODL_INIT_COMPARE_OPTIONS](#uf_modl_init_compare_options)
- [UF_MODL_INTERSECTION_EDGE](#uf_modl_intersection_edge)
- [UF_MODL_INTERSECT_NOT_PLANE_OR_DATUM_PLANE](#uf_modl_intersect_not_plane_or_datum_plane)
- [UF_MODL_INVALID_FACE_OR_PLANE](#uf_modl_invalid_face_or_plane)
- [UF_MODL_INVALID_LENGTH_PARAMETER](#uf_modl_invalid_length_parameter)
- [UF_MODL_INVALID_ROOT_PART](#uf_modl_invalid_root_part)
- [UF_MODL_INVALID_WORK_PART](#uf_modl_invalid_work_part)
- [UF_MODL_LATER_TIMESTAMP](#uf_modl_later_timestamp)
- [UF_MODL_LEFT_END_POINT](#uf_modl_left_end_point)
- [UF_MODL_LEFT_HAND](#uf_modl_left_hand)
- [UF_MODL_LEMON_TORUS](#uf_modl_lemon_torus)
- [UF_MODL_LIMITS_NOT_SUPPORTED](#uf_modl_limits_not_supported)
- [UF_MODL_LINEAR](#uf_modl_linear)
- [UF_MODL_LINEAR_EDGE](#uf_modl_linear_edge)
- [UF_MODL_LOC](#uf_modl_loc)
- [UF_MODL_LOC_1STDERV](#uf_modl_loc_1stderv)
- [UF_MODL_LOC_1STDERV_2NDDERV](#uf_modl_loc_1stderv_2ndderv)
- [UF_MODL_MAX_X_PERIODIC](#uf_modl_max_x_periodic)
- [UF_MODL_MESH_OF_CURVES_DRIVER](#uf_modl_mesh_of_curves_driver)
- [UF_MODL_MID_POINT](#uf_modl_mid_point)
- [UF_MODL_MIN_X_PERIODIC](#uf_modl_min_x_periodic)
- [UF_MODL_NON_PERIODIC](#uf_modl_non_periodic)
- [UF_MODL_NON_TAPERED](#uf_modl_non_tapered)
- [UF_MODL_NOT_A_TORUS](#uf_modl_not_a_torus)
- [UF_MODL_NOT_SAME_BODY](#uf_modl_not_same_body)
- [UF_MODL_NO_DYNAMIC_UPDATE](#uf_modl_no_dynamic_update)
- [UF_MODL_NO_INSTANCES](#uf_modl_no_instances)
- [UF_MODL_OFFSET_FACE](#uf_modl_offset_face)
- [UF_MODL_OPEN_CURVE](#uf_modl_open_curve)
- [UF_MODL_OPPOSITE_NORMAL](#uf_modl_opposite_normal)
- [UF_MODL_OSCULATING_APPLE_TORUS](#uf_modl_osculating_apple_torus)
- [UF_MODL_PARAMETRIC_FACE](#uf_modl_parametric_face)
- [UF_MODL_PATCH_HOLE](#uf_modl_patch_hole)
- [UF_MODL_PERIODIC](#uf_modl_periodic)
- [UF_MODL_PLANAR](#uf_modl_planar)
- [UF_MODL_PLANAR_FACE](#uf_modl_planar_face)
- [UF_MODL_POINT](#uf_modl_point)
- [UF_MODL_POINT_NOT_ON_FACE](#uf_modl_point_not_on_face)
- [UF_MODL_REPAIR_OPTION_PLANES_NOT_SUPPORTED](#uf_modl_repair_option_planes_not_supported)
- [UF_MODL_RIGHT_END_POINT](#uf_modl_right_end_point)
- [UF_MODL_RIGHT_HAND](#uf_modl_right_hand)
- [UF_MODL_SELF_REFIT_DRIVER](#uf_modl_self_refit_driver)
- [UF_MODL_SHEET_BODY](#uf_modl_sheet_body)
- [UF_MODL_SIMPL_FACE_NOT_REMOVED](#uf_modl_simpl_face_not_removed)
- [UF_MODL_SIMPL_HEAL_FAILED](#uf_modl_simpl_heal_failed)
- [UF_MODL_SIMPL_NO_FACES_DELETED](#uf_modl_simpl_no_faces_deleted)
- [UF_MODL_SIMPL_NO_RETAINED_FACE](#uf_modl_simpl_no_retained_face)
- [UF_MODL_SOLID_BODY](#uf_modl_solid_body)
- [UF_MODL_SPHERICAL_FACE](#uf_modl_spherical_face)
- [UF_MODL_SPHERICAL_TOPOLOGY](#uf_modl_spherical_topology)
- [UF_MODL_SPLINE_EDGE](#uf_modl_spline_edge)
- [UF_MODL_SP_CURVE_EDGE](#uf_modl_sp_curve_edge)
- [UF_MODL_SRF_VALUE_s](#uf_modl_srf_value_s)
- [UF_MODL_STATE_CLAMPED](#uf_modl_state_clamped)
- [UF_MODL_STATE_CLOSED](#uf_modl_state_closed)
- [UF_MODL_STATE_DEGENERACY](#uf_modl_state_degeneracy)
- [UF_MODL_STATE_DEGEN_EDGE](#uf_modl_state_degen_edge)
- [UF_MODL_STATE_G1_DISCONTINUITY](#uf_modl_state_g1_discontinuity)
- [UF_MODL_STATE_IS_FIXED](#uf_modl_state_is_fixed)
- [UF_MODL_STATE_IS_V](#uf_modl_state_is_v)
- [UF_MODL_STATE_KNOT_DECREASING](#uf_modl_state_knot_decreasing)
- [UF_MODL_STATE_KNOT_MULT](#uf_modl_state_knot_mult)
- [UF_MODL_STATE_KNOT_NONC0](#uf_modl_state_knot_nonc0)
- [UF_MODL_STATE_KNOT_TOOCLOSE](#uf_modl_state_knot_tooclose)
- [UF_MODL_STATE_PERIODIC](#uf_modl_state_periodic)
- [UF_MODL_STATE_RANGE_END](#uf_modl_state_range_end)
- [UF_MODL_STATE_RANGE_START](#uf_modl_state_range_start)
- [UF_MODL_STATE_SELF_INTERSECT](#uf_modl_state_self_intersect)
- [UF_MODL_STATE_SMOOTHED_TO_CN](#uf_modl_state_smoothed_to_cn)
- [UF_MODL_STATE_UNNORMALIZED](#uf_modl_state_unnormalized)
- [UF_MODL_STRING_ADD](#uf_modl_string_add)
- [UF_MODL_STRING_REMOVE](#uf_modl_string_remove)
- [UF_MODL_STRING_REPLACE](#uf_modl_string_replace)
- [UF_MODL_SWEEP_TRIM_OPTS](#uf_modl_sweep_trim_opts)
- [UF_MODL_SWEEP_TRIM_SIGNS](#uf_modl_sweep_trim_signs)
- [UF_MODL_SWEEP_TRIM_object_s](#uf_modl_sweep_trim_object_s)
- [UF_MODL_SWEEP_free_trim_data](#uf_modl_sweep_free_trim_data)
- [UF_MODL_SWEPT_FACE](#uf_modl_swept_face)
- [UF_MODL_TAPERED](#uf_modl_tapered)
- [UF_MODL_THREE_DIMENSIONAL](#uf_modl_three_dimensional)
- [UF_MODL_TOROIDAL_FACE](#uf_modl_toroidal_face)
- [UF_MODL_TOROIDAL_TOPOLOGY](#uf_modl_toroidal_topology)
- [UF_MODL_TORUS_TYPE](#uf_modl_torus_type)
- [UF_MODL_TREX_algorithm_e](#uf_modl_trex_algorithm_e)
- [UF_MODL_TREX_appl_data_s](#uf_modl_trex_appl_data_s)
- [UF_MODL_TREX_ask_trim_extend](#uf_modl_trex_ask_trim_extend)
- [UF_MODL_TREX_create_trex_feature](#uf_modl_trex_create_trex_feature)
- [UF_MODL_TREX_data_set_s](#uf_modl_trex_data_set_s)
- [UF_MODL_TREX_edit_trex_feature](#uf_modl_trex_edit_trex_feature)
- [UF_MODL_TREX_extend_method_e](#uf_modl_trex_extend_method_e)
- [UF_MODL_TREX_free_trex_data](#uf_modl_trex_free_trex_data)
- [UF_MODL_TREX_init_trex_data](#uf_modl_trex_init_trex_data)
- [UF_MODL_TREX_init_trex_data_set](#uf_modl_trex_init_trex_data_set)
- [UF_MODL_TREX_region_option_e](#uf_modl_trex_region_option_e)
- [UF_MODL_TREX_to_option_e](#uf_modl_trex_to_option_e)
- [UF_MODL_TRIMMED_CURVE_EDGE](#uf_modl_trimmed_curve_edge)
- [UF_MODL_UDF_CANT_EDITED](#uf_modl_udf_cant_edited)
- [UF_MODL_UDF_CANT_INSTANTIATED](#uf_modl_udf_cant_instantiated)
- [UF_MODL_UDF_INVALID_EXPS](#uf_modl_udf_invalid_exps)
- [UF_MODL_UDF_INVALID_MAPPING](#uf_modl_udf_invalid_mapping)
- [UF_MODL_UDF_INVALID_PARENTS](#uf_modl_udf_invalid_parents)
- [UF_MODL_UNABLE_TO_CREATE_GEODESIC_CURVES](#uf_modl_unable_to_create_geodesic_curves)
- [UF_MODL_UNABLE_TO_FIRE_RAY](#uf_modl_unable_to_fire_ray)
- [UF_MODL_UPDATE_ALL](#uf_modl_update_all)
- [UF_MODL_UPDATE_FIRST_LEVEL](#uf_modl_update_first_level)
- [UF_MODL_VERT_CENTERLINE_PNT_1](#uf_modl_vert_centerline_pnt_1)
- [UF_MODL_VERT_CENTERLINE_PNT_2](#uf_modl_vert_centerline_pnt_2)
- [UF_MODL_WRONG_BODY](#uf_modl_wrong_body)
- [UF_MODL_WRONG_CURVE_TYPE](#uf_modl_wrong_curve_type)
- [UF_MODL_active_part](#uf_modl_active_part)
- [UF_MODL_add_thru_faces](#uf_modl_add_thru_faces)
- [UF_MODL_ask_2dtrim_bsurf](#uf_modl_ask_2dtrim_bsurf)
- [UF_MODL_ask_adjac_faces](#uf_modl_ask_adjac_faces)
- [UF_MODL_ask_alive_edge](#uf_modl_ask_alive_edge)
- [UF_MODL_ask_alive_face](#uf_modl_ask_alive_face)
- [UF_MODL_ask_all_members_of_set](#uf_modl_ask_all_members_of_set)
- [UF_MODL_ask_angle_edge](#uf_modl_ask_angle_edge)
- [UF_MODL_ask_angle_tolerance_of_part](#uf_modl_ask_angle_tolerance_of_part)
- [UF_MODL_ask_ball_groove_parms](#uf_modl_ask_ball_groove_parms)
- [UF_MODL_ask_ball_slot_parms](#uf_modl_ask_ball_slot_parms)
- [UF_MODL_ask_bead](#uf_modl_ask_bead)
- [UF_MODL_ask_bend_allowance_formula](#uf_modl_ask_bend_allowance_formula)
- [UF_MODL_ask_bend_operation](#uf_modl_ask_bend_operation)
- [UF_MODL_ask_blend_face_data](#uf_modl_ask_blend_face_data)
- [UF_MODL_ask_blend_face_data1](#uf_modl_ask_blend_face_data1)
- [UF_MODL_ask_blend_parms](#uf_modl_ask_blend_parms)
- [UF_MODL_ask_block_parms](#uf_modl_ask_block_parms)
- [UF_MODL_ask_body_boundaries](#uf_modl_ask_body_boundaries)
- [UF_MODL_ask_body_consistency](#uf_modl_ask_body_consistency)
- [UF_MODL_ask_body_density](#uf_modl_ask_body_density)
- [UF_MODL_ask_body_edges](#uf_modl_ask_body_edges)
- [UF_MODL_ask_body_faces](#uf_modl_ask_body_faces)
- [UF_MODL_ask_body_feats](#uf_modl_ask_body_feats)
- [UF_MODL_ask_body_features](#uf_modl_ask_body_features)
- [UF_MODL_ask_body_structures](#uf_modl_ask_body_structures)
- [UF_MODL_ask_body_type](#uf_modl_ask_body_type)
- [UF_MODL_ask_body_type_pref](#uf_modl_ask_body_type_pref)
- [UF_MODL_ask_boolean_with_retained_options](#uf_modl_ask_boolean_with_retained_options)
- [UF_MODL_ask_boss_parms](#uf_modl_ask_boss_parms)
- [UF_MODL_ask_bounding_box](#uf_modl_ask_bounding_box)
- [UF_MODL_ask_bounding_box_aligned](#uf_modl_ask_bounding_box_aligned)
- [UF_MODL_ask_bounding_box_exact](#uf_modl_ask_bounding_box_exact)
- [UF_MODL_ask_bplane](#uf_modl_ask_bplane)
- [UF_MODL_ask_bsurf](#uf_modl_ask_bsurf)
- [UF_MODL_ask_bsurf_knot_display](#uf_modl_ask_bsurf_knot_display)
- [UF_MODL_ask_bsurf_pole_display](#uf_modl_ask_bsurf_pole_display)
- [UF_MODL_ask_c_bore_hole_parms](#uf_modl_ask_c_bore_hole_parms)
- [UF_MODL_ask_c_sunk_hole_parms](#uf_modl_ask_c_sunk_hole_parms)
- [UF_MODL_ask_chamfer_parms](#uf_modl_ask_chamfer_parms)
- [UF_MODL_ask_circular_iset_parms](#uf_modl_ask_circular_iset_parms)
- [UF_MODL_ask_circular_pattern_face](#uf_modl_ask_circular_pattern_face)
- [UF_MODL_ask_cnnc_edges](#uf_modl_ask_cnnc_edges)
- [UF_MODL_ask_cone_parms](#uf_modl_ask_cone_parms)
- [UF_MODL_ask_constraint_type](#uf_modl_ask_constraint_type)
- [UF_MODL_ask_constraints](#uf_modl_ask_constraints)
- [UF_MODL_ask_current_feature](#uf_modl_ask_current_feature)
- [UF_MODL_ask_curve_closed](#uf_modl_ask_curve_closed)
- [UF_MODL_ask_curve_fit_method](#uf_modl_ask_curve_fit_method)
- [UF_MODL_ask_curve_mesh](#uf_modl_ask_curve_mesh)
- [UF_MODL_ask_curve_mesh1](#uf_modl_ask_curve_mesh1)
- [UF_MODL_ask_curve_parm](#uf_modl_ask_curve_parm)
- [UF_MODL_ask_curve_parm_no_ext](#uf_modl_ask_curve_parm_no_ext)
- [UF_MODL_ask_curve_periodicity](#uf_modl_ask_curve_periodicity)
- [UF_MODL_ask_curve_points](#uf_modl_ask_curve_points)
- [UF_MODL_ask_curve_props](#uf_modl_ask_curve_props)
- [UF_MODL_ask_cyl_pocket_parms](#uf_modl_ask_cyl_pocket_parms)
- [UF_MODL_ask_cylinder_parms](#uf_modl_ask_cylinder_parms)
- [UF_MODL_ask_datum_axis_parms](#uf_modl_ask_datum_axis_parms)
- [UF_MODL_ask_datum_csys_components](#uf_modl_ask_datum_csys_components)
- [UF_MODL_ask_datum_plane](#uf_modl_ask_datum_plane)
- [UF_MODL_ask_datum_plane_parms](#uf_modl_ask_datum_plane_parms)
- [UF_MODL_ask_datum_point_and_direction](#uf_modl_ask_datum_point_and_direction)
- [UF_MODL_ask_daxis_size](#uf_modl_ask_daxis_size)
- [UF_MODL_ask_default_density](#uf_modl_ask_default_density)
- [UF_MODL_ask_descriptor_of_exp](#uf_modl_ask_descriptor_of_exp)
- [UF_MODL_ask_die_tip](#uf_modl_ask_die_tip)
- [UF_MODL_ask_distance_tolerance_of_part](#uf_modl_ask_distance_tolerance_of_part)
- [UF_MODL_ask_dovetail_slot_parms](#uf_modl_ask_dovetail_slot_parms)
- [UF_MODL_ask_dynamic_update](#uf_modl_ask_dynamic_update)
- [UF_MODL_ask_edge_blend](#uf_modl_ask_edge_blend)
- [UF_MODL_ask_edge_blend1](#uf_modl_ask_edge_blend1)
- [UF_MODL_ask_edge_blend_is_mult](#uf_modl_ask_edge_blend_is_mult)
- [UF_MODL_ask_edge_blend_mult](#uf_modl_ask_edge_blend_mult)
- [UF_MODL_ask_edge_body](#uf_modl_ask_edge_body)
- [UF_MODL_ask_edge_faces](#uf_modl_ask_edge_faces)
- [UF_MODL_ask_edge_feats](#uf_modl_ask_edge_feats)
- [UF_MODL_ask_edge_smoothness](#uf_modl_ask_edge_smoothness)
- [UF_MODL_ask_edge_tolerance](#uf_modl_ask_edge_tolerance)
- [UF_MODL_ask_edge_type](#uf_modl_ask_edge_type)
- [UF_MODL_ask_edge_verts](#uf_modl_ask_edge_verts)
- [UF_MODL_ask_enlarge](#uf_modl_ask_enlarge)
- [UF_MODL_ask_exp](#uf_modl_ask_exp)
- [UF_MODL_ask_exp_desc_of_feat](#uf_modl_ask_exp_desc_of_feat)
- [UF_MODL_ask_exp_desc_of_frec](#uf_modl_ask_exp_desc_of_frec)
- [UF_MODL_ask_exp_tag_string](#uf_modl_ask_exp_tag_string)
- [UF_MODL_ask_exp_tag_value](#uf_modl_ask_exp_tag_value)
- [UF_MODL_ask_exps_of_feature](#uf_modl_ask_exps_of_feature)
- [UF_MODL_ask_exps_of_part](#uf_modl_ask_exps_of_part)
- [UF_MODL_ask_extreme](#uf_modl_ask_extreme)
- [UF_MODL_ask_extrude_offset_dir](#uf_modl_ask_extrude_offset_dir)
- [UF_MODL_ask_extrusion](#uf_modl_ask_extrusion)
- [UF_MODL_ask_face_blend_law_radii](#uf_modl_ask_face_blend_law_radii)
- [UF_MODL_ask_face_blend_law_range1_radii](#uf_modl_ask_face_blend_law_range1_radii)
- [UF_MODL_ask_face_blend_law_range2_radii](#uf_modl_ask_face_blend_law_range2_radii)
- [UF_MODL_ask_face_body](#uf_modl_ask_face_body)
- [UF_MODL_ask_face_constraint](#uf_modl_ask_face_constraint)
- [UF_MODL_ask_face_data](#uf_modl_ask_face_data)
- [UF_MODL_ask_face_edges](#uf_modl_ask_face_edges)
- [UF_MODL_ask_face_face_intersect](#uf_modl_ask_face_face_intersect)
- [UF_MODL_ask_face_feats](#uf_modl_ask_face_feats)
- [UF_MODL_ask_face_grid_count](#uf_modl_ask_face_grid_count)
- [UF_MODL_ask_face_loops](#uf_modl_ask_face_loops)
- [UF_MODL_ask_face_min_radii](#uf_modl_ask_face_min_radii)
- [UF_MODL_ask_face_parm](#uf_modl_ask_face_parm)
- [UF_MODL_ask_face_parm_2](#uf_modl_ask_face_parm_2)
- [UF_MODL_ask_face_periodicity](#uf_modl_ask_face_periodicity)
- [UF_MODL_ask_face_props](#uf_modl_ask_face_props)
- [UF_MODL_ask_face_self_intersect](#uf_modl_ask_face_self_intersect)
- [UF_MODL_ask_face_smoothness](#uf_modl_ask_face_smoothness)
- [UF_MODL_ask_face_spikes](#uf_modl_ask_face_spikes)
- [UF_MODL_ask_face_topology](#uf_modl_ask_face_topology)
- [UF_MODL_ask_face_torus_type](#uf_modl_ask_face_torus_type)
- [UF_MODL_ask_face_type](#uf_modl_ask_face_type)
- [UF_MODL_ask_face_uv_minmax](#uf_modl_ask_face_uv_minmax)
- [UF_MODL_ask_facepair_parms](#uf_modl_ask_facepair_parms)
- [UF_MODL_ask_feat_body](#uf_modl_ask_feat_body)
- [UF_MODL_ask_feat_direction](#uf_modl_ask_feat_direction)
- [UF_MODL_ask_feat_display_name](#uf_modl_ask_feat_display_name)
- [UF_MODL_ask_feat_edges](#uf_modl_ask_feat_edges)
- [UF_MODL_ask_feat_error](#uf_modl_ask_feat_error)
- [UF_MODL_ask_feat_faces](#uf_modl_ask_feat_faces)
- [UF_MODL_ask_feat_fail_list](#uf_modl_ask_feat_fail_list)
- [UF_MODL_ask_feat_location](#uf_modl_ask_feat_location)
- [UF_MODL_ask_feat_name](#uf_modl_ask_feat_name)
- [UF_MODL_ask_feat_object](#uf_modl_ask_feat_object)
- [UF_MODL_ask_feat_or_udf_sysname](#uf_modl_ask_feat_or_udf_sysname)
- [UF_MODL_ask_feat_relatives](#uf_modl_ask_feat_relatives)
- [UF_MODL_ask_feat_sysname](#uf_modl_ask_feat_sysname)
- [UF_MODL_ask_feat_tolerance](#uf_modl_ask_feat_tolerance)
- [UF_MODL_ask_feat_type](#uf_modl_ask_feat_type)
- [UF_MODL_ask_feat_warning_messages](#uf_modl_ask_feat_warning_messages)
- [UF_MODL_ask_feature_boolean](#uf_modl_ask_feature_boolean)
- [UF_MODL_ask_feature_sign](#uf_modl_ask_feature_sign)
- [UF_MODL_ask_features_of_exp](#uf_modl_ask_features_of_exp)
- [UF_MODL_ask_features_of_mirror_set](#uf_modl_ask_features_of_mirror_set)
- [UF_MODL_ask_features_of_udf](#uf_modl_ask_features_of_udf)
- [UF_MODL_ask_flange_parms](#uf_modl_ask_flange_parms)
- [UF_MODL_ask_flange_proc_factor](#uf_modl_ask_flange_proc_factor)
- [UF_MODL_ask_formable_feature_state](#uf_modl_ask_formable_feature_state)
- [UF_MODL_ask_free_form_result](#uf_modl_ask_free_form_result)
- [UF_MODL_ask_general_flange](#uf_modl_ask_general_flange)
- [UF_MODL_ask_general_pad](#uf_modl_ask_general_pad)
- [UF_MODL_ask_general_pad1](#uf_modl_ask_general_pad1)
- [UF_MODL_ask_general_pocket](#uf_modl_ask_general_pocket)
- [UF_MODL_ask_general_pocket1](#uf_modl_ask_general_pocket1)
- [UF_MODL_ask_gflange](#uf_modl_ask_gflange)
- [UF_MODL_ask_hollow_data](#uf_modl_ask_hollow_data)
- [UF_MODL_ask_hollow_parms](#uf_modl_ask_hollow_parms)
- [UF_MODL_ask_horz_dime](#uf_modl_ask_horz_dime)
- [UF_MODL_ask_immediate_children](#uf_modl_ask_immediate_children)
- [UF_MODL_ask_impr_edges](#uf_modl_ask_impr_edges)
- [UF_MODL_ask_impr_faces_parms](#uf_modl_ask_impr_faces_parms)
- [UF_MODL_ask_impr_loop_parms](#uf_modl_ask_impr_loop_parms)
- [UF_MODL_ask_inset_flange_parms](#uf_modl_ask_inset_flange_parms)
- [UF_MODL_ask_instance](#uf_modl_ask_instance)
- [UF_MODL_ask_instance_iset](#uf_modl_ask_instance_iset)
- [UF_MODL_ask_instances_of_feature](#uf_modl_ask_instances_of_feature)
- [UF_MODL_ask_instantiated_udf](#uf_modl_ask_instantiated_udf)
- [UF_MODL_ask_law_extension](#uf_modl_ask_law_extension)
- [UF_MODL_ask_law_extension1](#uf_modl_ask_law_extension1)
- [UF_MODL_ask_linear_iset_parms](#uf_modl_ask_linear_iset_parms)
- [UF_MODL_ask_link_face_plane](#uf_modl_ask_link_face_plane)
- [UF_MODL_ask_link_faces](#uf_modl_ask_link_faces)
- [UF_MODL_ask_linked_exterior](#uf_modl_ask_linked_exterior)
- [UF_MODL_ask_list_count](#uf_modl_ask_list_count)
- [UF_MODL_ask_list_item](#uf_modl_ask_list_item)
- [UF_MODL_ask_local_scale](#uf_modl_ask_local_scale)
- [UF_MODL_ask_loop_list_count](#uf_modl_ask_loop_list_count)
- [UF_MODL_ask_loop_list_item](#uf_modl_ask_loop_list_item)
- [UF_MODL_ask_mass_props_3d](#uf_modl_ask_mass_props_3d)
- [UF_MODL_ask_master](#uf_modl_ask_master)
- [UF_MODL_ask_matching_face_in_instance](#uf_modl_ask_matching_face_in_instance)
- [UF_MODL_ask_max_curvature](#uf_modl_ask_max_curvature)
- [UF_MODL_ask_merged_faces](#uf_modl_ask_merged_faces)
- [UF_MODL_ask_midsrf_feature_create_method](#uf_modl_ask_midsrf_feature_create_method)
- [UF_MODL_ask_midsrf_parms](#uf_modl_ask_midsrf_parms)
- [UF_MODL_ask_minimum_dist](#uf_modl_ask_minimum_dist)
- [UF_MODL_ask_minimum_dist_2](#uf_modl_ask_minimum_dist_2)
- [UF_MODL_ask_minimum_dist_3](#uf_modl_ask_minimum_dist_3)
- [UF_MODL_ask_mirror_pattern_face](#uf_modl_ask_mirror_pattern_face)
- [UF_MODL_ask_misalign_geometry](#uf_modl_ask_misalign_geometry)
- [UF_MODL_ask_move_region](#uf_modl_ask_move_region)
- [UF_MODL_ask_named_body_object](#uf_modl_ask_named_body_object)
- [UF_MODL_ask_nested_frecs](#uf_modl_ask_nested_frecs)
- [UF_MODL_ask_next_feature](#uf_modl_ask_next_feature)
- [UF_MODL_ask_obj_dimensionality](#uf_modl_ask_obj_dimensionality)
- [UF_MODL_ask_object](#uf_modl_ask_object)
- [UF_MODL_ask_object_feat](#uf_modl_ask_object_feat)
- [UF_MODL_ask_offset_parms](#uf_modl_ask_offset_parms)
- [UF_MODL_ask_offset_region](#uf_modl_ask_offset_region)
- [UF_MODL_ask_owning_feat_of_exp](#uf_modl_ask_owning_feat_of_exp)
- [UF_MODL_ask_para_dist](#uf_modl_ask_para_dist)
- [UF_MODL_ask_para_edge](#uf_modl_ask_para_edge)
- [UF_MODL_ask_patch_body_parms](#uf_modl_ask_patch_body_parms)
- [UF_MODL_ask_perp_dist](#uf_modl_ask_perp_dist)
- [UF_MODL_ask_plane](#uf_modl_ask_plane)
- [UF_MODL_ask_plane_of_mirror_set](#uf_modl_ask_plane_of_mirror_set)
- [UF_MODL_ask_point_along_curve](#uf_modl_ask_point_along_curve)
- [UF_MODL_ask_point_along_curve_2](#uf_modl_ask_point_along_curve_2)
- [UF_MODL_ask_point_containment](#uf_modl_ask_point_containment)
- [UF_MODL_ask_points_parms](#uf_modl_ask_points_parms)
- [UF_MODL_ask_previous_feature](#uf_modl_ask_previous_feature)
- [UF_MODL_ask_prism_parms](#uf_modl_ask_prism_parms)
- [UF_MODL_ask_proj_curves](#uf_modl_ask_proj_curves)
- [UF_MODL_ask_prom_feat_of_solid](#uf_modl_ask_prom_feat_of_solid)
- [UF_MODL_ask_promotion_path](#uf_modl_ask_promotion_path)
- [UF_MODL_ask_proper_legacy_feat_name](#uf_modl_ask_proper_legacy_feat_name)
- [UF_MODL_ask_quilt](#uf_modl_ask_quilt)
- [UF_MODL_ask_quilt_type](#uf_modl_ask_quilt_type)
- [UF_MODL_ask_reblend_face](#uf_modl_ask_reblend_face)
- [UF_MODL_ask_rect_groove_parms](#uf_modl_ask_rect_groove_parms)
- [UF_MODL_ask_rect_pad_parms](#uf_modl_ask_rect_pad_parms)
- [UF_MODL_ask_rect_pad_parms_1](#uf_modl_ask_rect_pad_parms_1)
- [UF_MODL_ask_rect_pocket_parms](#uf_modl_ask_rect_pocket_parms)
- [UF_MODL_ask_rect_slot_parms](#uf_modl_ask_rect_slot_parms)
- [UF_MODL_ask_rectangular_pattern_face](#uf_modl_ask_rectangular_pattern_face)
- [UF_MODL_ask_references_of_features](#uf_modl_ask_references_of_features)
- [UF_MODL_ask_refit_face_feature_data](#uf_modl_ask_refit_face_feature_data)
- [UF_MODL_ask_replace_face](#uf_modl_ask_replace_face)
- [UF_MODL_ask_resize_face](#uf_modl_ask_resize_face)
- [UF_MODL_ask_revolution](#uf_modl_ask_revolution)
- [UF_MODL_ask_ripedge](#uf_modl_ask_ripedge)
- [UF_MODL_ask_rough_offset](#uf_modl_ask_rough_offset)
- [UF_MODL_ask_rpo_desc_of_feat](#uf_modl_ask_rpo_desc_of_feat)
- [UF_MODL_ask_rpo_desc_of_frec](#uf_modl_ask_rpo_desc_of_frec)
- [UF_MODL_ask_rpo_routine](#uf_modl_ask_rpo_routine)
- [UF_MODL_ask_ruled](#uf_modl_ask_ruled)
- [UF_MODL_ask_ruled1](#uf_modl_ask_ruled1)
- [UF_MODL_ask_scale](#uf_modl_ask_scale)
- [UF_MODL_ask_section_surface](#uf_modl_ask_section_surface)
- [UF_MODL_ask_set_from_name](#uf_modl_ask_set_from_name)
- [UF_MODL_ask_sets_of_member](#uf_modl_ask_sets_of_member)
- [UF_MODL_ask_shared_edges](#uf_modl_ask_shared_edges)
- [UF_MODL_ask_show_report_reference](#uf_modl_ask_show_report_reference)
- [UF_MODL_ask_silhouette_flange](#uf_modl_ask_silhouette_flange)
- [UF_MODL_ask_simple_hole_parms](#uf_modl_ask_simple_hole_parms)
- [UF_MODL_ask_simplify_parms](#uf_modl_ask_simplify_parms)
- [UF_MODL_ask_sketch_of_sweep](#uf_modl_ask_sketch_of_sweep)
- [UF_MODL_ask_smbend](#uf_modl_ask_smbend)
- [UF_MODL_ask_smbend_corner](#uf_modl_ask_smbend_corner)
- [UF_MODL_ask_smbend_cylinder](#uf_modl_ask_smbend_cylinder)
- [UF_MODL_ask_smcorner](#uf_modl_ask_smcorner)
- [UF_MODL_ask_smcutout](#uf_modl_ask_smcutout)
- [UF_MODL_ask_smhole](#uf_modl_ask_smhole)
- [UF_MODL_ask_smpunch](#uf_modl_ask_smpunch)
- [UF_MODL_ask_smslot](#uf_modl_ask_smslot)
- [UF_MODL_ask_snip_surface_feature_data](#uf_modl_ask_snip_surface_feature_data)
- [UF_MODL_ask_solid_of_prom_feat](#uf_modl_ask_solid_of_prom_feat)
- [UF_MODL_ask_solid_punch](#uf_modl_ask_solid_punch)
- [UF_MODL_ask_sphere_parms](#uf_modl_ask_sphere_parms)
- [UF_MODL_ask_split_edges](#uf_modl_ask_split_edges)
- [UF_MODL_ask_split_faces](#uf_modl_ask_split_faces)
- [UF_MODL_ask_stycorner_data](#uf_modl_ask_stycorner_data)
- [UF_MODL_ask_styled_sweep_feature_data](#uf_modl_ask_styled_sweep_feature_data)
- [UF_MODL_ask_subdiv_face_parms](#uf_modl_ask_subdiv_face_parms)
- [UF_MODL_ask_suppress_exp_tag](#uf_modl_ask_suppress_exp_tag)
- [UF_MODL_ask_suppress_feature](#uf_modl_ask_suppress_feature)
- [UF_MODL_ask_suppress_list](#uf_modl_ask_suppress_list)
- [UF_MODL_ask_sweep](#uf_modl_ask_sweep)
- [UF_MODL_ask_sweep_curves](#uf_modl_ask_sweep_curves)
- [UF_MODL_ask_sweep_direction](#uf_modl_ask_sweep_direction)
- [UF_MODL_ask_sweep_of_udf](#uf_modl_ask_sweep_of_udf)
- [UF_MODL_ask_sweep_parms](#uf_modl_ask_sweep_parms)
- [UF_MODL_ask_symb_thread_parms](#uf_modl_ask_symb_thread_parms)
- [UF_MODL_ask_t_slot_parms](#uf_modl_ask_t_slot_parms)
- [UF_MODL_ask_taper_from_edges](#uf_modl_ask_taper_from_edges)
- [UF_MODL_ask_taper_from_edges1](#uf_modl_ask_taper_from_edges1)
- [UF_MODL_ask_taper_hole_parms](#uf_modl_ask_taper_hole_parms)
- [UF_MODL_ask_taper_parms](#uf_modl_ask_taper_parms)
- [UF_MODL_ask_thru_curves](#uf_modl_ask_thru_curves)
- [UF_MODL_ask_thru_curves1](#uf_modl_ask_thru_curves1)
- [UF_MODL_ask_thru_faces](#uf_modl_ask_thru_faces)
- [UF_MODL_ask_time_stamp_of_feature](#uf_modl_ask_time_stamp_of_feature)
- [UF_MODL_ask_tiny_geometry](#uf_modl_ask_tiny_geometry)
- [UF_MODL_ask_torus_parms](#uf_modl_ask_torus_parms)
- [UF_MODL_ask_trimmed_sheet](#uf_modl_ask_trimmed_sheet)
- [UF_MODL_ask_u_groove_parms](#uf_modl_ask_u_groove_parms)
- [UF_MODL_ask_u_slot_parms](#uf_modl_ask_u_slot_parms)
- [UF_MODL_ask_udf_definition](#uf_modl_ask_udf_definition)
- [UF_MODL_ask_udf_mapping_for_edit](#uf_modl_ask_udf_mapping_for_edit)
- [UF_MODL_ask_udf_mapping_for_insert](#uf_modl_ask_udf_mapping_for_insert)
- [UF_MODL_ask_udf_mapping_routine](#uf_modl_ask_udf_mapping_routine)
- [UF_MODL_ask_udf_parms](#uf_modl_ask_udf_parms)
- [UF_MODL_ask_update_error_message](#uf_modl_ask_update_error_message)
- [UF_MODL_ask_update_fail_option](#uf_modl_ask_update_fail_option)
- [UF_MODL_ask_update_undo_feat](#uf_modl_ask_update_undo_feat)
- [UF_MODL_ask_uv_points_containment](#uf_modl_ask_uv_points_containment)
- [UF_MODL_ask_vda_4955_compliance](#uf_modl_ask_vda_4955_compliance)
- [UF_MODL_ask_vector_angle](#uf_modl_ask_vector_angle)
- [UF_MODL_ask_vert_dime](#uf_modl_ask_vert_dime)
- [UF_MODL_ask_wrap_assembly](#uf_modl_ask_wrap_assembly)
- [UF_MODL_ask_wrap_geometry](#uf_modl_ask_wrap_geometry)
- [UF_MODL_ask_xform_tag_of_datum_csys](#uf_modl_ask_xform_tag_of_datum_csys)
- [UF_MODL_assign_string_directions](#uf_modl_assign_string_directions)
- [UF_MODL_auto_midsrf_feature](#uf_modl_auto_midsrf_feature)
- [UF_MODL_auto_midsrf_feature_w_opts](#uf_modl_auto_midsrf_feature_w_opts)
- [UF_MODL_b_surface_along_driver_normals_data_s](#uf_modl_b_surface_along_driver_normals_data_s)
- [UF_MODL_b_surface_along_fixed_vector_data_s](#uf_modl_b_surface_along_fixed_vector_data_s)
- [UF_MODL_bead_angle_relative_e](#uf_modl_bead_angle_relative_e)
- [UF_MODL_bead_attach_e](#uf_modl_bead_attach_e)
- [UF_MODL_bead_ends](#uf_modl_bead_ends)
- [UF_MODL_bead_hollow_e](#uf_modl_bead_hollow_e)
- [UF_MODL_bead_plane_defined_by_s](#uf_modl_bead_plane_defined_by_s)
- [UF_MODL_bead_plane_fixed_s](#uf_modl_bead_plane_fixed_s)
- [UF_MODL_bead_plane_normal_e](#uf_modl_bead_plane_normal_e)
- [UF_MODL_bead_section_parms_s](#uf_modl_bead_section_parms_s)
- [UF_MODL_bead_section_plane_s](#uf_modl_bead_section_plane_s)
- [UF_MODL_bead_shape_e](#uf_modl_bead_shape_e)
- [UF_MODL_bead_width_relative_e](#uf_modl_bead_width_relative_e)
- [UF_MODL_bend_operation_data_s](#uf_modl_bend_operation_data_s)
- [UF_MODL_bend_operation_e_t](#uf_modl_bend_operation_e_t)
- [UF_MODL_blend_edge_s](#uf_modl_blend_edge_s)
- [UF_MODL_blend_faces_create_data_s](#uf_modl_blend_faces_create_data_s)
- [UF_MODL_blend_faces_limit_data_s](#uf_modl_blend_faces_limit_data_s)
- [UF_MODL_blend_law_parms_union](#uf_modl_blend_law_parms_union)
- [UF_MODL_blend_point_data_s](#uf_modl_blend_point_data_s)
- [UF_MODL_blend_point_s](#uf_modl_blend_point_s)
- [UF_MODL_blend_radius_types](#uf_modl_blend_radius_types)
- [UF_MODL_boolean_body](#uf_modl_boolean_body)
- [UF_MODL_boolean_udf](#uf_modl_boolean_udf)
- [UF_MODL_boolean_udf_1](#uf_modl_boolean_udf_1)
- [UF_MODL_bracket_outline_data_s](#uf_modl_bracket_outline_data_s)
- [UF_MODL_bracket_outline_data_union](#uf_modl_bracket_outline_data_union)
- [UF_MODL_bsurf_row_info_s](#uf_modl_bsurf_row_info_s)
- [UF_MODL_bsurface_s](#uf_modl_bsurface_s)
- [UF_MODL_calculate_ref_dir](#uf_modl_calculate_ref_dir)
- [UF_MODL_change_offset_base_face](#uf_modl_change_offset_base_face)
- [UF_MODL_check_interference](#uf_modl_check_interference)
- [UF_MODL_cliff_blend_f_t](#uf_modl_cliff_blend_f_t)
- [UF_MODL_clock_instance](#uf_modl_clock_instance)
- [UF_MODL_compare](#uf_modl_compare)
- [UF_MODL_compare_accuracy_e](#uf_modl_compare_accuracy_e)
- [UF_MODL_compare_changeduniqueface_rule_e](#uf_modl_compare_changeduniqueface_rule_e)
- [UF_MODL_compare_entity_info_s](#uf_modl_compare_entity_info_s)
- [UF_MODL_compare_entity_match_s](#uf_modl_compare_entity_match_s)
- [UF_MODL_compare_entity_type_e](#uf_modl_compare_entity_type_e)
- [UF_MODL_compare_identicalface_rule_e](#uf_modl_compare_identicalface_rule_e)
- [UF_MODL_compare_options_s](#uf_modl_compare_options_s)
- [UF_MODL_compare_part_entities_data_3_s](#uf_modl_compare_part_entities_data_3_s)
- [UF_MODL_compare_part_entities_data_s](#uf_modl_compare_part_entities_data_s)
- [UF_MODL_compare_part_map_data_3_s](#uf_modl_compare_part_map_data_3_s)
- [UF_MODL_compare_part_map_data_s](#uf_modl_compare_part_map_data_s)
- [UF_MODL_compare_topology](#uf_modl_compare_topology)
- [UF_MODL_convert_to_fixed_datum](#uf_modl_convert_to_fixed_datum)
- [UF_MODL_copy_paste_features](#uf_modl_copy_paste_features)
- [UF_MODL_cre_2dtrim_bsurf](#uf_modl_cre_2dtrim_bsurf)
- [UF_MODL_cre_chamfer_with_flip_option](#uf_modl_cre_chamfer_with_flip_option)
- [UF_MODL_cre_chamfer_with_instance_and_flip_option](#uf_modl_cre_chamfer_with_instance_and_flip_option)
- [UF_MODL_cre_def_facepair_feat](#uf_modl_cre_def_facepair_feat)
- [UF_MODL_cre_sel_facepair_feat](#uf_modl_cre_sel_facepair_feat)
- [UF_MODL_cre_trim_bsurf](#uf_modl_cre_trim_bsurf)
- [UF_MODL_create_ball_groove](#uf_modl_create_ball_groove)
- [UF_MODL_create_ball_slot](#uf_modl_create_ball_slot)
- [UF_MODL_create_bead](#uf_modl_create_bead)
- [UF_MODL_create_bend_operation](#uf_modl_create_bend_operation)
- [UF_MODL_create_blend](#uf_modl_create_blend)
- [UF_MODL_create_blend_faces](#uf_modl_create_blend_faces)
- [UF_MODL_create_block](#uf_modl_create_block)
- [UF_MODL_create_block1](#uf_modl_create_block1)
- [UF_MODL_create_boss](#uf_modl_create_boss)
- [UF_MODL_create_bplane](#uf_modl_create_bplane)
- [UF_MODL_create_bridge_face](#uf_modl_create_bridge_face)
- [UF_MODL_create_bs_2d_edges](#uf_modl_create_bs_2d_edges)
- [UF_MODL_create_bs_edges](#uf_modl_create_bs_edges)
- [UF_MODL_create_bsurf](#uf_modl_create_bsurf)
- [UF_MODL_create_bsurf_thru_pts](#uf_modl_create_bsurf_thru_pts)
- [UF_MODL_create_bsurface](#uf_modl_create_bsurface)
- [UF_MODL_create_c_bore_hole](#uf_modl_create_c_bore_hole)
- [UF_MODL_create_c_sunk_hole](#uf_modl_create_c_sunk_hole)
- [UF_MODL_create_chamfer](#uf_modl_create_chamfer)
- [UF_MODL_create_circular_iset](#uf_modl_create_circular_iset)
- [UF_MODL_create_circular_pattern_face](#uf_modl_create_circular_pattern_face)
- [UF_MODL_create_cone](#uf_modl_create_cone)
- [UF_MODL_create_cone1](#uf_modl_create_cone1)
- [UF_MODL_create_curve_from_edge](#uf_modl_create_curve_from_edge)
- [UF_MODL_create_curve_mesh](#uf_modl_create_curve_mesh)
- [UF_MODL_create_curve_mesh1](#uf_modl_create_curve_mesh1)
- [UF_MODL_create_cyl1](#uf_modl_create_cyl1)
- [UF_MODL_create_cyl_pocket](#uf_modl_create_cyl_pocket)
- [UF_MODL_create_cylinder](#uf_modl_create_cylinder)
- [UF_MODL_create_datum_csys](#uf_modl_create_datum_csys)
- [UF_MODL_create_datum_csys_offset](#uf_modl_create_datum_csys_offset)
- [UF_MODL_create_dove_tail_slot](#uf_modl_create_dove_tail_slot)
- [UF_MODL_create_edge_blend](#uf_modl_create_edge_blend)
- [UF_MODL_create_edge_blend_mult](#uf_modl_create_edge_blend_mult)
- [UF_MODL_create_enlarge](#uf_modl_create_enlarge)
- [UF_MODL_create_exp](#uf_modl_create_exp)
- [UF_MODL_create_exp_tag](#uf_modl_create_exp_tag)
- [UF_MODL_create_extrude_trim_opts](#uf_modl_create_extrude_trim_opts)
- [UF_MODL_create_extrude_trim_opts1](#uf_modl_create_extrude_trim_opts1)
- [UF_MODL_create_extruded](#uf_modl_create_extruded)
- [UF_MODL_create_extruded1](#uf_modl_create_extruded1)
- [UF_MODL_create_extruded2](#uf_modl_create_extruded2)
- [UF_MODL_create_extruded_path](#uf_modl_create_extruded_path)
- [UF_MODL_create_extruded_path1](#uf_modl_create_extruded_path1)
- [UF_MODL_create_extrusion](#uf_modl_create_extrusion)
- [UF_MODL_create_extrusion1](#uf_modl_create_extrusion1)
- [UF_MODL_create_extrusion2](#uf_modl_create_extrusion2)
- [UF_MODL_create_extrusion_default](#uf_modl_create_extrusion_default)
- [UF_MODL_create_extrusion_default1](#uf_modl_create_extrusion_default1)
- [UF_MODL_create_extrusion_dir](#uf_modl_create_extrusion_dir)
- [UF_MODL_create_extrusion_path](#uf_modl_create_extrusion_path)
- [UF_MODL_create_extrusion_path1](#uf_modl_create_extrusion_path1)
- [UF_MODL_create_face_blend](#uf_modl_create_face_blend)
- [UF_MODL_create_face_constraint](#uf_modl_create_face_constraint)
- [UF_MODL_create_face_offset](#uf_modl_create_face_offset)
- [UF_MODL_create_face_taper](#uf_modl_create_face_taper)
- [UF_MODL_create_feature_offset](#uf_modl_create_feature_offset)
- [UF_MODL_create_feature_taper](#uf_modl_create_feature_taper)
- [UF_MODL_create_fitted_spline](#uf_modl_create_fitted_spline)
- [UF_MODL_create_fixed_daxis](#uf_modl_create_fixed_daxis)
- [UF_MODL_create_fixed_dplane](#uf_modl_create_fixed_dplane)
- [UF_MODL_create_flange](#uf_modl_create_flange)
- [UF_MODL_create_frenet_daxis](#uf_modl_create_frenet_daxis)
- [UF_MODL_create_general_flange](#uf_modl_create_general_flange)
- [UF_MODL_create_general_pad](#uf_modl_create_general_pad)
- [UF_MODL_create_general_pocket](#uf_modl_create_general_pocket)
- [UF_MODL_create_geodesic_curves](#uf_modl_create_geodesic_curves)
- [UF_MODL_create_gflange](#uf_modl_create_gflange)
- [UF_MODL_create_hollow](#uf_modl_create_hollow)
- [UF_MODL_create_impr_faces](#uf_modl_create_impr_faces)
- [UF_MODL_create_impr_loop](#uf_modl_create_impr_loop)
- [UF_MODL_create_inset_flange](#uf_modl_create_inset_flange)
- [UF_MODL_create_instantiated_udf](#uf_modl_create_instantiated_udf)
- [UF_MODL_create_instantiated_udf1](#uf_modl_create_instantiated_udf1)
- [UF_MODL_create_isocline_curves](#uf_modl_create_isocline_curves)
- [UF_MODL_create_isocurve](#uf_modl_create_isocurve)
- [UF_MODL_create_law](#uf_modl_create_law)
- [UF_MODL_create_law_extension](#uf_modl_create_law_extension)
- [UF_MODL_create_linear_iset](#uf_modl_create_linear_iset)
- [UF_MODL_create_linked_exterior](#uf_modl_create_linked_exterior)
- [UF_MODL_create_list](#uf_modl_create_list)
- [UF_MODL_create_local_scale](#uf_modl_create_local_scale)
- [UF_MODL_create_midsrf_feature](#uf_modl_create_midsrf_feature)
- [UF_MODL_create_mirror_body](#uf_modl_create_mirror_body)
- [UF_MODL_create_mirror_pattern_face](#uf_modl_create_mirror_pattern_face)
- [UF_MODL_create_mirror_set](#uf_modl_create_mirror_set)
- [UF_MODL_create_move_region](#uf_modl_create_move_region)
- [UF_MODL_create_multi_transition_law](#uf_modl_create_multi_transition_law)
- [UF_MODL_create_non_uni_scale](#uf_modl_create_non_uni_scale)
- [UF_MODL_create_offset_region](#uf_modl_create_offset_region)
- [UF_MODL_create_plane](#uf_modl_create_plane)
- [UF_MODL_create_point_dirr_daxis](#uf_modl_create_point_dirr_daxis)
- [UF_MODL_create_point_dirr_dplane](#uf_modl_create_point_dirr_dplane)
- [UF_MODL_create_points_feature](#uf_modl_create_points_feature)
- [UF_MODL_create_proj_curves](#uf_modl_create_proj_curves)
- [UF_MODL_create_promotion](#uf_modl_create_promotion)
- [UF_MODL_create_quilt](#uf_modl_create_quilt)
- [UF_MODL_create_reblend_face](#uf_modl_create_reblend_face)
- [UF_MODL_create_rect_groove](#uf_modl_create_rect_groove)
- [UF_MODL_create_rect_pad](#uf_modl_create_rect_pad)
- [UF_MODL_create_rect_pocket](#uf_modl_create_rect_pocket)
- [UF_MODL_create_rect_slot](#uf_modl_create_rect_slot)
- [UF_MODL_create_rectangular_pattern_face](#uf_modl_create_rectangular_pattern_face)
- [UF_MODL_create_refit_face_feature](#uf_modl_create_refit_face_feature)
- [UF_MODL_create_relative_daxis](#uf_modl_create_relative_daxis)
- [UF_MODL_create_relative_dplane](#uf_modl_create_relative_dplane)
- [UF_MODL_create_reparam_sheet](#uf_modl_create_reparam_sheet)
- [UF_MODL_create_replace_face](#uf_modl_create_replace_face)
- [UF_MODL_create_resize_face](#uf_modl_create_resize_face)
- [UF_MODL_create_reverse_normal](#uf_modl_create_reverse_normal)
- [UF_MODL_create_revolution](#uf_modl_create_revolution)
- [UF_MODL_create_revolution1](#uf_modl_create_revolution1)
- [UF_MODL_create_revolution_dir](#uf_modl_create_revolution_dir)
- [UF_MODL_create_ripedge](#uf_modl_create_ripedge)
- [UF_MODL_create_rough_offset](#uf_modl_create_rough_offset)
- [UF_MODL_create_rpo_constraints](#uf_modl_create_rpo_constraints)
- [UF_MODL_create_ruled](#uf_modl_create_ruled)
- [UF_MODL_create_ruled1](#uf_modl_create_ruled1)
- [UF_MODL_create_scale](#uf_modl_create_scale)
- [UF_MODL_create_section_surface](#uf_modl_create_section_surface)
- [UF_MODL_create_set_of_feature](#uf_modl_create_set_of_feature)
- [UF_MODL_create_silhouette_flange](#uf_modl_create_silhouette_flange)
- [UF_MODL_create_silhouette_flange_pipe](#uf_modl_create_silhouette_flange_pipe)
- [UF_MODL_create_simple_hole](#uf_modl_create_simple_hole)
- [UF_MODL_create_simplified_curve](#uf_modl_create_simplified_curve)
- [UF_MODL_create_simplify](#uf_modl_create_simplify)
- [UF_MODL_create_smbend](#uf_modl_create_smbend)
- [UF_MODL_create_smbend_corner](#uf_modl_create_smbend_corner)
- [UF_MODL_create_smbend_cylinder](#uf_modl_create_smbend_cylinder)
- [UF_MODL_create_smbracket](#uf_modl_create_smbracket)
- [UF_MODL_create_smcorner](#uf_modl_create_smcorner)
- [UF_MODL_create_smcutout](#uf_modl_create_smcutout)
- [UF_MODL_create_smd_flange](#uf_modl_create_smd_flange)
- [UF_MODL_create_smhole](#uf_modl_create_smhole)
- [UF_MODL_create_smjoggle](#uf_modl_create_smjoggle)
- [UF_MODL_create_smpunch](#uf_modl_create_smpunch)
- [UF_MODL_create_smrelief](#uf_modl_create_smrelief)
- [UF_MODL_create_smslot](#uf_modl_create_smslot)
- [UF_MODL_create_snip_surface_feature](#uf_modl_create_snip_surface_feature)
- [UF_MODL_create_solid_punch](#uf_modl_create_solid_punch)
- [UF_MODL_create_sphere](#uf_modl_create_sphere)
- [UF_MODL_create_sphere1](#uf_modl_create_sphere1)
- [UF_MODL_create_spline](#uf_modl_create_spline)
- [UF_MODL_create_string_list](#uf_modl_create_string_list)
- [UF_MODL_create_stycorner](#uf_modl_create_stycorner)
- [UF_MODL_create_styled_sweep_feature](#uf_modl_create_styled_sweep_feature)
- [UF_MODL_create_subdiv_face](#uf_modl_create_subdiv_face)
- [UF_MODL_create_surf_from_cloud](#uf_modl_create_surf_from_cloud)
- [UF_MODL_create_sweep](#uf_modl_create_sweep)
- [UF_MODL_create_t_slot](#uf_modl_create_t_slot)
- [UF_MODL_create_taper_from_edges](#uf_modl_create_taper_from_edges)
- [UF_MODL_create_taper_from_faces](#uf_modl_create_taper_from_faces)
- [UF_MODL_create_taper_from_tangent_faces](#uf_modl_create_taper_from_tangent_faces)
- [UF_MODL_create_taper_split_line](#uf_modl_create_taper_split_line)
- [UF_MODL_create_thru_curves](#uf_modl_create_thru_curves)
- [UF_MODL_create_thru_curves1](#uf_modl_create_thru_curves1)
- [UF_MODL_create_trimmed_sheet](#uf_modl_create_trimmed_sheet)
- [UF_MODL_create_trimmed_tube](#uf_modl_create_trimmed_tube)
- [UF_MODL_create_trimmed_tube1](#uf_modl_create_trimmed_tube1)
- [UF_MODL_create_true_taper_from_edges](#uf_modl_create_true_taper_from_edges)
- [UF_MODL_create_tube](#uf_modl_create_tube)
- [UF_MODL_create_tube1](#uf_modl_create_tube1)
- [UF_MODL_create_u_groove](#uf_modl_create_u_groove)
- [UF_MODL_create_u_slot](#uf_modl_create_u_slot)
- [UF_MODL_create_uniform_scale](#uf_modl_create_uniform_scale)
- [UF_MODL_create_variable_hollow](#uf_modl_create_variable_hollow)
- [UF_MODL_create_variable_offset](#uf_modl_create_variable_offset)
- [UF_MODL_create_variable_taper_from_edges](#uf_modl_create_variable_taper_from_edges)
- [UF_MODL_create_wrap_assembly](#uf_modl_create_wrap_assembly)
- [UF_MODL_create_wrap_geometry](#uf_modl_create_wrap_geometry)
- [UF_MODL_curve_direction_e](#uf_modl_curve_direction_e)
- [UF_MODL_curve_mesh_along_driver_normals_data_s](#uf_modl_curve_mesh_along_driver_normals_data_s)
- [UF_MODL_curve_mesh_along_fixed_vector_data_s](#uf_modl_curve_mesh_along_fixed_vector_data_s)
- [UF_MODL_curves_represent_e](#uf_modl_curves_represent_e)
- [UF_MODL_default_rpo_menu](#uf_modl_default_rpo_menu)
- [UF_MODL_delete_body_parms](#uf_modl_delete_body_parms)
- [UF_MODL_delete_exp](#uf_modl_delete_exp)
- [UF_MODL_delete_exp_tag](#uf_modl_delete_exp_tag)
- [UF_MODL_delete_feature](#uf_modl_delete_feature)
- [UF_MODL_delete_list](#uf_modl_delete_list)
- [UF_MODL_delete_list_item](#uf_modl_delete_list_item)
- [UF_MODL_delete_loop_list](#uf_modl_delete_loop_list)
- [UF_MODL_delete_object_parms](#uf_modl_delete_object_parms)
- [UF_MODL_density_units_e](#uf_modl_density_units_e)
- [UF_MODL_devchk_adjacent_edges](#uf_modl_devchk_adjacent_edges)
- [UF_MODL_devchk_curve_to_curve](#uf_modl_devchk_curve_to_curve)
- [UF_MODL_devchk_curve_to_face](#uf_modl_devchk_curve_to_face)
- [UF_MODL_devchk_edge_to_edge](#uf_modl_devchk_edge_to_edge)
- [UF_MODL_devchk_edge_to_face](#uf_modl_devchk_edge_to_face)
- [UF_MODL_devchk_ee_info_s](#uf_modl_devchk_ee_info_s)
- [UF_MODL_devchk_face_to_face](#uf_modl_devchk_face_to_face)
- [UF_MODL_deviation_check_data_s](#uf_modl_deviation_check_data_s)
- [UF_MODL_dfo_constraint_s](#uf_modl_dfo_constraint_s)
- [UF_MODL_dfo_constraint_type_e](#uf_modl_dfo_constraint_type_e)
- [UF_MODL_dfo_region_s](#uf_modl_dfo_region_s)
- [UF_MODL_dfo_scale_type_t](#uf_modl_dfo_scale_type_t)
- [UF_MODL_die_tip_info_s](#uf_modl_die_tip_info_s)
- [UF_MODL_dimension_data_s](#uf_modl_dimension_data_s)
- [UF_MODL_dissect_exp_string](#uf_modl_dissect_exp_string)
- [UF_MODL_dump_midsurf_facepair_report](#uf_modl_dump_midsurf_facepair_report)
- [UF_MODL_edge_blend_data_s](#uf_modl_edge_blend_data_s)
- [UF_MODL_edge_blend_mult_data_s](#uf_modl_edge_blend_mult_data_s)
- [UF_MODL_edge_blend_set_s](#uf_modl_edge_blend_set_s)
- [UF_MODL_edge_blend_setback_data_s](#uf_modl_edge_blend_setback_data_s)
- [UF_MODL_edge_blend_stopshort_data_s](#uf_modl_edge_blend_stopshort_data_s)
- [UF_MODL_edit_bead](#uf_modl_edit_bead)
- [UF_MODL_edit_bend_allowance_formula](#uf_modl_edit_bend_allowance_formula)
- [UF_MODL_edit_bend_operation](#uf_modl_edit_bend_operation)
- [UF_MODL_edit_boolean_with_retained_options](#uf_modl_edit_boolean_with_retained_options)
- [UF_MODL_edit_bsurf](#uf_modl_edit_bsurf)
- [UF_MODL_edit_circular_iset](#uf_modl_edit_circular_iset)
- [UF_MODL_edit_circular_pattern_face](#uf_modl_edit_circular_pattern_face)
- [UF_MODL_edit_datum_direction](#uf_modl_edit_datum_direction)
- [UF_MODL_edit_datum_point](#uf_modl_edit_datum_point)
- [UF_MODL_edit_edge_blend](#uf_modl_edit_edge_blend)
- [UF_MODL_edit_edge_blend_mult](#uf_modl_edit_edge_blend_mult)
- [UF_MODL_edit_enlarge](#uf_modl_edit_enlarge)
- [UF_MODL_edit_exp](#uf_modl_edit_exp)
- [UF_MODL_edit_face_constraint](#uf_modl_edit_face_constraint)
- [UF_MODL_edit_face_grid_count](#uf_modl_edit_face_grid_count)
- [UF_MODL_edit_face_join](#uf_modl_edit_face_join)
- [UF_MODL_edit_formable_feature_state](#uf_modl_edit_formable_feature_state)
- [UF_MODL_edit_general_flange](#uf_modl_edit_general_flange)
- [UF_MODL_edit_general_pad](#uf_modl_edit_general_pad)
- [UF_MODL_edit_general_pocket](#uf_modl_edit_general_pocket)
- [UF_MODL_edit_gflange](#uf_modl_edit_gflange)
- [UF_MODL_edit_hole_type](#uf_modl_edit_hole_type)
- [UF_MODL_edit_hollow](#uf_modl_edit_hollow)
- [UF_MODL_edit_import_body_feature](#uf_modl_edit_import_body_feature)
- [UF_MODL_edit_import_body_features](#uf_modl_edit_import_body_features)
- [UF_MODL_edit_impr_faces_parms](#uf_modl_edit_impr_faces_parms)
- [UF_MODL_edit_impr_loop_parms](#uf_modl_edit_impr_loop_parms)
- [UF_MODL_edit_inset_flange](#uf_modl_edit_inset_flange)
- [UF_MODL_edit_instantiated_udf](#uf_modl_edit_instantiated_udf)
- [UF_MODL_edit_law_extension](#uf_modl_edit_law_extension)
- [UF_MODL_edit_linear_iset](#uf_modl_edit_linear_iset)
- [UF_MODL_edit_linked_exterior](#uf_modl_edit_linked_exterior)
- [UF_MODL_edit_local_scale](#uf_modl_edit_local_scale)
- [UF_MODL_edit_mirror_pattern_face](#uf_modl_edit_mirror_pattern_face)
- [UF_MODL_edit_mirror_set](#uf_modl_edit_mirror_set)
- [UF_MODL_edit_move_region](#uf_modl_edit_move_region)
- [UF_MODL_edit_offset_region](#uf_modl_edit_offset_region)
- [UF_MODL_edit_patch_body_parms](#uf_modl_edit_patch_body_parms)
- [UF_MODL_edit_plane](#uf_modl_edit_plane)
- [UF_MODL_edit_points_parms](#uf_modl_edit_points_parms)
- [UF_MODL_edit_quilt](#uf_modl_edit_quilt)
- [UF_MODL_edit_reblend_face](#uf_modl_edit_reblend_face)
- [UF_MODL_edit_rectangular_pattern_face](#uf_modl_edit_rectangular_pattern_face)
- [UF_MODL_edit_refit_face_feature](#uf_modl_edit_refit_face_feature)
- [UF_MODL_edit_replace_face](#uf_modl_edit_replace_face)
- [UF_MODL_edit_resize_face](#uf_modl_edit_resize_face)
- [UF_MODL_edit_ripedge](#uf_modl_edit_ripedge)
- [UF_MODL_edit_rough_offset](#uf_modl_edit_rough_offset)
- [UF_MODL_edit_scale](#uf_modl_edit_scale)
- [UF_MODL_edit_section_surface](#uf_modl_edit_section_surface)
- [UF_MODL_edit_set_hide_state](#uf_modl_edit_set_hide_state)
- [UF_MODL_edit_set_members](#uf_modl_edit_set_members)
- [UF_MODL_edit_silhouette_flange](#uf_modl_edit_silhouette_flange)
- [UF_MODL_edit_simplify_parms](#uf_modl_edit_simplify_parms)
- [UF_MODL_edit_slot_type](#uf_modl_edit_slot_type)
- [UF_MODL_edit_smbend](#uf_modl_edit_smbend)
- [UF_MODL_edit_smbend_corner](#uf_modl_edit_smbend_corner)
- [UF_MODL_edit_smbend_cylinder](#uf_modl_edit_smbend_cylinder)
- [UF_MODL_edit_smcorner](#uf_modl_edit_smcorner)
- [UF_MODL_edit_smcutout](#uf_modl_edit_smcutout)
- [UF_MODL_edit_smd_flange](#uf_modl_edit_smd_flange)
- [UF_MODL_edit_smhole](#uf_modl_edit_smhole)
- [UF_MODL_edit_smpunch](#uf_modl_edit_smpunch)
- [UF_MODL_edit_smslot](#uf_modl_edit_smslot)
- [UF_MODL_edit_snip_surface_feature](#uf_modl_edit_snip_surface_feature)
- [UF_MODL_edit_solid_punch](#uf_modl_edit_solid_punch)
- [UF_MODL_edit_stycorner](#uf_modl_edit_stycorner)
- [UF_MODL_edit_styled_sweep_feature](#uf_modl_edit_styled_sweep_feature)
- [UF_MODL_edit_subdiv_face](#uf_modl_edit_subdiv_face)
- [UF_MODL_edit_sweep_curves](#uf_modl_edit_sweep_curves)
- [UF_MODL_edit_symb_thread](#uf_modl_edit_symb_thread)
- [UF_MODL_edit_taper_from_edges](#uf_modl_edit_taper_from_edges)
- [UF_MODL_edit_trimmed_sheet](#uf_modl_edit_trimmed_sheet)
- [UF_MODL_edit_wrap_assembly](#uf_modl_edit_wrap_assembly)
- [UF_MODL_edit_wrap_geometry](#uf_modl_edit_wrap_geometry)
- [UF_MODL_err_feature_e](#uf_modl_err_feature_e)
- [UF_MODL_eval_exp](#uf_modl_eval_exp)
- [UF_MODL_evaluate_curve](#uf_modl_evaluate_curve)
- [UF_MODL_evaluate_face](#uf_modl_evaluate_face)
- [UF_MODL_evaluate_parm](#uf_modl_evaluate_parm)
- [UF_MODL_export_exp](#uf_modl_export_exp)
- [UF_MODL_export_udf](#uf_modl_export_udf)
- [UF_MODL_extract_face](#uf_modl_extract_face)
- [UF_MODL_face_blend_create_data_s](#uf_modl_face_blend_create_data_s)
- [UF_MODL_face_extension_e](#uf_modl_face_extension_e)
- [UF_MODL_faces_s](#uf_modl_faces_s)
- [UF_MODL_feature_can_be_copied](#uf_modl_feature_can_be_copied)
- [UF_MODL_features_s](#uf_modl_features_s)
- [UF_MODL_fix_bsurface_data](#uf_modl_fix_bsurface_data)
- [UF_MODL_flange_data_s](#uf_modl_flange_data_s)
- [UF_MODL_form_features](#uf_modl_form_features)
- [UF_MODL_free_bead](#uf_modl_free_bead)
- [UF_MODL_free_bsurf_data](#uf_modl_free_bsurf_data)
- [UF_MODL_free_compare_data](#uf_modl_free_compare_data)
- [UF_MODL_free_compare_data_3](#uf_modl_free_compare_data_3)
- [UF_MODL_free_general_pad](#uf_modl_free_general_pad)
- [UF_MODL_free_general_pocket](#uf_modl_free_general_pocket)
- [UF_MODL_free_gflange_data](#uf_modl_free_gflange_data)
- [UF_MODL_free_law](#uf_modl_free_law)
- [UF_MODL_free_law_extension](#uf_modl_free_law_extension)
- [UF_MODL_free_quilt](#uf_modl_free_quilt)
- [UF_MODL_free_refit_face_feature_data](#uf_modl_free_refit_face_feature_data)
- [UF_MODL_free_rough_offset_data](#uf_modl_free_rough_offset_data)
- [UF_MODL_free_silhouette_flange](#uf_modl_free_silhouette_flange)
- [UF_MODL_free_snip_surface_feature_data](#uf_modl_free_snip_surface_feature_data)
- [UF_MODL_free_string_list](#uf_modl_free_string_list)
- [UF_MODL_free_styled_sweep_feature_data](#uf_modl_free_styled_sweep_feature_data)
- [UF_MODL_free_symb_thread_data](#uf_modl_free_symb_thread_data)
- [UF_MODL_free_udfs_def_data](#uf_modl_free_udfs_def_data)
- [UF_MODL_genflg_ask_num_states](#uf_modl_genflg_ask_num_states)
- [UF_MODL_genflg_ask_state_data](#uf_modl_genflg_ask_state_data)
- [UF_MODL_genflg_create_state](#uf_modl_genflg_create_state)
- [UF_MODL_genflg_delete_state](#uf_modl_genflg_delete_state)
- [UF_MODL_genflg_edit_state](#uf_modl_genflg_edit_state)
- [UF_MODL_genflg_state_data_s](#uf_modl_genflg_state_data_s)
- [UF_MODL_get_curve_edge_direction](#uf_modl_get_curve_edge_direction)
- [UF_MODL_get_dimension_data](#uf_modl_get_dimension_data)
- [UF_MODL_gflange_data_s](#uf_modl_gflange_data_s)
- [UF_MODL_gflange_distort_e](#uf_modl_gflange_distort_e)
- [UF_MODL_gflange_e](#uf_modl_gflange_e)
- [UF_MODL_gflange_options_data_s](#uf_modl_gflange_options_data_s)
- [UF_MODL_gflange_parameters_mode_data_s](#uf_modl_gflange_parameters_mode_data_s)
- [UF_MODL_gflange_punch_vector_mode_data_s](#uf_modl_gflange_punch_vector_mode_data_s)
- [UF_MODL_gflange_sections_mode_data_s](#uf_modl_gflange_sections_mode_data_s)
- [UF_MODL_gflange_shaping_faces_mode_data_s](#uf_modl_gflange_shaping_faces_mode_data_s)
- [UF_MODL_hide_parent_curves](#uf_modl_hide_parent_curves)
- [UF_MODL_hole_type_e](#uf_modl_hole_type_e)
- [UF_MODL_identify_exterior_using_hl](#uf_modl_identify_exterior_using_hl)
- [UF_MODL_identify_exterior_using_rays](#uf_modl_identify_exterior_using_rays)
- [UF_MODL_import_body_feature_edit_option_e](#uf_modl_import_body_feature_edit_option_e)
- [UF_MODL_import_exp](#uf_modl_import_exp)
- [UF_MODL_import_udf](#uf_modl_import_udf)
- [UF_MODL_imprint_faces_data_s](#uf_modl_imprint_faces_data_s)
- [UF_MODL_imprint_loop_data_s](#uf_modl_imprint_loop_data_s)
- [UF_MODL_init_edge_blend_mult](#uf_modl_init_edge_blend_mult)
- [UF_MODL_init_edge_blend_point_mult](#uf_modl_init_edge_blend_point_mult)
- [UF_MODL_init_edge_blend_set_mult](#uf_modl_init_edge_blend_set_mult)
- [UF_MODL_init_edge_blend_setback_mult](#uf_modl_init_edge_blend_setback_mult)
- [UF_MODL_init_edge_blend_stopshort_mult](#uf_modl_init_edge_blend_stopshort_mult)
- [UF_MODL_init_face_blend_data](#uf_modl_init_face_blend_data)
- [UF_MODL_init_ripedge_ufdata](#uf_modl_init_ripedge_ufdata)
- [UF_MODL_init_section_surface](#uf_modl_init_section_surface)
- [UF_MODL_init_silhouette_flange_data](#uf_modl_init_silhouette_flange_data)
- [UF_MODL_init_smcorner_ufdata](#uf_modl_init_smcorner_ufdata)
- [UF_MODL_init_string_list](#uf_modl_init_string_list)
- [UF_MODL_init_stycorner_data](#uf_modl_init_stycorner_data)
- [UF_MODL_initialize_compare_data](#uf_modl_initialize_compare_data)
- [UF_MODL_inset_flange_data_s](#uf_modl_inset_flange_data_s)
- [UF_MODL_intersect_bodies](#uf_modl_intersect_bodies)
- [UF_MODL_intersect_bodies_with_retained_options](#uf_modl_intersect_bodies_with_retained_options)
- [UF_MODL_intersect_curve_to_curve](#uf_modl_intersect_curve_to_curve)
- [UF_MODL_intersect_curve_to_face](#uf_modl_intersect_curve_to_face)
- [UF_MODL_intersect_curve_to_plane](#uf_modl_intersect_curve_to_plane)
- [UF_MODL_intersect_info_coincide_s](#uf_modl_intersect_info_coincide_s)
- [UF_MODL_intersect_info_curve_s](#uf_modl_intersect_info_curve_s)
- [UF_MODL_intersect_info_intersect_s](#uf_modl_intersect_info_intersect_s)
- [UF_MODL_intersect_info_point_s](#uf_modl_intersect_info_point_s)
- [UF_MODL_intersect_info_s](#uf_modl_intersect_info_s)
- [UF_MODL_intersect_objects](#uf_modl_intersect_objects)
- [UF_MODL_intersect_type_e](#uf_modl_intersect_type_e)
- [UF_MODL_is_body_convergent](#uf_modl_is_body_convergent)
- [UF_MODL_is_body_feature](#uf_modl_is_body_feature)
- [UF_MODL_is_browseable_feature](#uf_modl_is_browseable_feature)
- [UF_MODL_is_datum_axis_reversed](#uf_modl_is_datum_axis_reversed)
- [UF_MODL_is_datum_plane_reversed](#uf_modl_is_datum_plane_reversed)
- [UF_MODL_is_exp_in_part](#uf_modl_is_exp_in_part)
- [UF_MODL_is_feature_a_hidden_set_member](#uf_modl_is_feature_a_hidden_set_member)
- [UF_MODL_is_feature_a_set_member](#uf_modl_is_feature_a_set_member)
- [UF_MODL_is_geometric_expression](#uf_modl_is_geometric_expression)
- [UF_MODL_is_import_body_feature](#uf_modl_is_import_body_feature)
- [UF_MODL_isodivide_face](#uf_modl_isodivide_face)
- [UF_MODL_isotrim_face](#uf_modl_isotrim_face)
- [UF_MODL_law_constant_s](#uf_modl_law_constant_s)
- [UF_MODL_law_curve_s](#uf_modl_law_curve_s)
- [UF_MODL_law_defined_by_u](#uf_modl_law_defined_by_u)
- [UF_MODL_law_equation_s](#uf_modl_law_equation_s)
- [UF_MODL_law_linear_cubic_s](#uf_modl_law_linear_cubic_s)
- [UF_MODL_law_method_e](#uf_modl_law_method_e)
- [UF_MODL_law_no_spine_constant_s](#uf_modl_law_no_spine_constant_s)
- [UF_MODL_law_no_spine_curve_s](#uf_modl_law_no_spine_curve_s)
- [UF_MODL_law_no_spine_defined_by_union](#uf_modl_law_no_spine_defined_by_union)
- [UF_MODL_law_no_spine_equation_s](#uf_modl_law_no_spine_equation_s)
- [UF_MODL_law_no_spine_linear_cubic_s](#uf_modl_law_no_spine_linear_cubic_s)
- [UF_MODL_law_no_spine_s](#uf_modl_law_no_spine_s)
- [UF_MODL_law_spine_pt_val_s](#uf_modl_law_spine_pt_val_s)
- [UF_MODL_law_spine_pts_linear_cubic_s](#uf_modl_law_spine_pts_linear_cubic_s)
- [UF_MODL_law_spine_s](#uf_modl_law_spine_s)
- [UF_MODL_lawext_data_s](#uf_modl_lawext_data_s)
- [UF_MODL_lawext_dirref_e](#uf_modl_lawext_dirref_e)
- [UF_MODL_linked_ext_s](#uf_modl_linked_ext_s)
- [UF_MODL_mapping_data_output_objs_non_ss_s](#uf_modl_mapping_data_output_objs_non_ss_s)
- [UF_MODL_mapping_data_output_objs_ss_s](#uf_modl_mapping_data_output_objs_ss_s)
- [UF_MODL_matchedge_ask_data](#uf_modl_matchedge_ask_data)
- [UF_MODL_matchedge_check](#uf_modl_matchedge_check)
- [UF_MODL_matchedge_create_feature](#uf_modl_matchedge_create_feature)
- [UF_MODL_matchedge_data_s](#uf_modl_matchedge_data_s)
- [UF_MODL_matchedge_edit_feature](#uf_modl_matchedge_edit_feature)
- [UF_MODL_matchedge_free_data](#uf_modl_matchedge_free_data)
- [UF_MODL_mode_specific_data_u](#uf_modl_mode_specific_data_u)
- [UF_MODL_model_compare](#uf_modl_model_compare)
- [UF_MODL_model_compare_2](#uf_modl_model_compare_2)
- [UF_MODL_model_compare_3](#uf_modl_model_compare_3)
- [UF_MODL_move_feature](#uf_modl_move_feature)
- [UF_MODL_mswp_ask_extrude](#uf_modl_mswp_ask_extrude)
- [UF_MODL_mswp_create_extrude](#uf_modl_mswp_create_extrude)
- [UF_MODL_mswp_edit_extrude](#uf_modl_mswp_edit_extrude)
- [UF_MODL_mswp_extrude_s](#uf_modl_mswp_extrude_s)
- [UF_MODL_mswp_init_extrude_data](#uf_modl_mswp_init_extrude_data)
- [UF_MODL_mswp_limit_data_u](#uf_modl_mswp_limit_data_u)
- [UF_MODL_mswp_limit_s](#uf_modl_mswp_limit_s)
- [UF_MODL_mswp_limit_type_t](#uf_modl_mswp_limit_type_t)
- [UF_MODL_mswp_limits_s](#uf_modl_mswp_limits_s)
- [UF_MODL_mswp_multi_taper_s](#uf_modl_mswp_multi_taper_s)
- [UF_MODL_mswp_offset_type_e](#uf_modl_mswp_offset_type_e)
- [UF_MODL_mswp_offsets_s](#uf_modl_mswp_offsets_s)
- [UF_MODL_mswp_string_data_s](#uf_modl_mswp_string_data_s)
- [UF_MODL_mswp_taper_chain_s](#uf_modl_mswp_taper_chain_s)
- [UF_MODL_mswp_taper_s](#uf_modl_mswp_taper_s)
- [UF_MODL_mswp_taper_type_e](#uf_modl_mswp_taper_type_e)
- [UF_MODL_mswp_until_selected_data_s](#uf_modl_mswp_until_selected_data_s)
- [UF_MODL_offset_trans_faces_s](#uf_modl_offset_trans_faces_s)
- [UF_MODL_offset_trans_type_e](#uf_modl_offset_trans_type_e)
- [UF_MODL_operations](#uf_modl_operations)
- [UF_MODL_outline_represents_e](#uf_modl_outline_represents_e)
- [UF_MODL_overlap_check_e](#uf_modl_overlap_check_e)
- [UF_MODL_parent_disp_info_s](#uf_modl_parent_disp_info_s)
- [UF_MODL_parm_constant_s](#uf_modl_parm_constant_s)
- [UF_MODL_parm_defined_by_union](#uf_modl_parm_defined_by_union)
- [UF_MODL_parm_law_no_spine_s](#uf_modl_parm_law_no_spine_s)
- [UF_MODL_parm_law_spine_s](#uf_modl_parm_law_spine_s)
- [UF_MODL_parm_method_e](#uf_modl_parm_method_e)
- [UF_MODL_parm_s](#uf_modl_parm_s)
- [UF_MODL_paste_features](#uf_modl_paste_features)
- [UF_MODL_patch_body](#uf_modl_patch_body)
- [UF_MODL_pocketpad_outline_defined_by_s](#uf_modl_pocketpad_outline_defined_by_s)
- [UF_MODL_pocketpad_outline_double_outline_corner_s](#uf_modl_pocketpad_outline_double_outline_corner_s)
- [UF_MODL_pocketpad_outline_double_outline_s](#uf_modl_pocketpad_outline_double_outline_s)
- [UF_MODL_pocketpad_outline_s](#uf_modl_pocketpad_outline_s)
- [UF_MODL_pocketpad_outline_single_outline_corner_s](#uf_modl_pocketpad_outline_single_outline_corner_s)
- [UF_MODL_pocketpad_type_e](#uf_modl_pocketpad_type_e)
- [UF_MODL_preview_simplify](#uf_modl_preview_simplify)
- [UF_MODL_proj_type_e](#uf_modl_proj_type_e)
- [UF_MODL_project_curves_s](#uf_modl_project_curves_s)
- [UF_MODL_prom_map_object_down](#uf_modl_prom_map_object_down)
- [UF_MODL_prom_map_object_up](#uf_modl_prom_map_object_up)
- [UF_MODL_punch_type_e](#uf_modl_punch_type_e)
- [UF_MODL_put_list_item](#uf_modl_put_list_item)
- [UF_MODL_quilt_data_s](#uf_modl_quilt_data_s)
- [UF_MODL_quilt_data_structures_union](#uf_modl_quilt_data_structures_union)
- [UF_MODL_quilt_type_e](#uf_modl_quilt_type_e)
- [UF_MODL_ray_hit_point_info_s](#uf_modl_ray_hit_point_info_s)
- [UF_MODL_reattach_dir_ref](#uf_modl_reattach_dir_ref)
- [UF_MODL_reattach_target_face](#uf_modl_reattach_target_face)
- [UF_MODL_reattach_thru_faces](#uf_modl_reattach_thru_faces)
- [UF_MODL_reattach_tool_face](#uf_modl_reattach_tool_face)
- [UF_MODL_reblend_face_data_s](#uf_modl_reblend_face_data_s)
- [UF_MODL_reblend_face_s](#uf_modl_reblend_face_s)
- [UF_MODL_record_feature_update_warnings](#uf_modl_record_feature_update_warnings)
- [UF_MODL_redefine_replace_faces](#uf_modl_redefine_replace_faces)
- [UF_MODL_redefine_rpo_constraint](#uf_modl_redefine_rpo_constraint)
- [UF_MODL_redefine_trim_faces](#uf_modl_redefine_trim_faces)
- [UF_MODL_refit_face_continuity_e](#uf_modl_refit_face_continuity_e)
- [UF_MODL_refit_face_data_s](#uf_modl_refit_face_data_s)
- [UF_MODL_refit_face_fit_direction_e](#uf_modl_refit_face_fit_direction_e)
- [UF_MODL_refit_face_refit_direction_e](#uf_modl_refit_face_refit_direction_e)
- [UF_MODL_refit_face_refit_method_e](#uf_modl_refit_face_refit_method_e)
- [UF_MODL_refit_face_target_data_s](#uf_modl_refit_face_target_data_s)
- [UF_MODL_register_cliff_blend](#uf_modl_register_cliff_blend)
- [UF_MODL_register_rpo_routine](#uf_modl_register_rpo_routine)
- [UF_MODL_register_udf_mapping_routine](#uf_modl_register_udf_mapping_routine)
- [UF_MODL_register_var_blend](#uf_modl_register_var_blend)
- [UF_MODL_remove_thru_faces](#uf_modl_remove_thru_faces)
- [UF_MODL_rename_exp](#uf_modl_rename_exp)
- [UF_MODL_reorder_feature](#uf_modl_reorder_feature)
- [UF_MODL_replace_body_data](#uf_modl_replace_body_data)
- [UF_MODL_replace_boolean_body](#uf_modl_replace_boolean_body)
- [UF_MODL_replace_feat_strings](#uf_modl_replace_feat_strings)
- [UF_MODL_replace_features](#uf_modl_replace_features)
- [UF_MODL_replace_features_t](#uf_modl_replace_features_t)
- [UF_MODL_replace_sweep_strings](#uf_modl_replace_sweep_strings)
- [UF_MODL_require_udf_mapping_for_edit](#uf_modl_require_udf_mapping_for_edit)
- [UF_MODL_require_udf_mapping_for_insert](#uf_modl_require_udf_mapping_for_insert)
- [UF_MODL_reverse_datum_axis](#uf_modl_reverse_datum_axis)
- [UF_MODL_reverse_datum_plane](#uf_modl_reverse_datum_plane)
- [UF_MODL_reverse_dir_ref](#uf_modl_reverse_dir_ref)
- [UF_MODL_ripedge_data_s](#uf_modl_ripedge_data_s)
- [UF_MODL_rough_offset_s](#uf_modl_rough_offset_s)
- [UF_MODL_rpo_f_p_t](#uf_modl_rpo_f_p_t)
- [UF_MODL_secsrf_cre_method](#uf_modl_secsrf_cre_method)
- [UF_MODL_secsrf_data_s](#uf_modl_secsrf_data_s)
- [UF_MODL_secsrf_param_data_values_s](#uf_modl_secsrf_param_data_values_s)
- [UF_MODL_secsrf_param_method](#uf_modl_secsrf_param_method)
- [UF_MODL_secsrf_param_s](#uf_modl_secsrf_param_s)
- [UF_MODL_self_refit_data_s](#uf_modl_self_refit_data_s)
- [UF_MODL_set_angle_tolerance_of_part](#uf_modl_set_angle_tolerance_of_part)
- [UF_MODL_set_body_density](#uf_modl_set_body_density)
- [UF_MODL_set_body_type_pref](#uf_modl_set_body_type_pref)
- [UF_MODL_set_bsurf_knot_display](#uf_modl_set_bsurf_knot_display)
- [UF_MODL_set_bsurf_pole_display](#uf_modl_set_bsurf_pole_display)
- [UF_MODL_set_containment](#uf_modl_set_containment)
- [UF_MODL_set_current_feature](#uf_modl_set_current_feature)
- [UF_MODL_set_curve_fit_method](#uf_modl_set_curve_fit_method)
- [UF_MODL_set_datum_csys_scaling](#uf_modl_set_datum_csys_scaling)
- [UF_MODL_set_datum_csys_visibility](#uf_modl_set_datum_csys_visibility)
- [UF_MODL_set_default_density](#uf_modl_set_default_density)
- [UF_MODL_set_distance_tolerance_of_part](#uf_modl_set_distance_tolerance_of_part)
- [UF_MODL_set_dynamic_update](#uf_modl_set_dynamic_update)
- [UF_MODL_set_face_blend_law_radii](#uf_modl_set_face_blend_law_radii)
- [UF_MODL_set_face_blend_law_range1_radii](#uf_modl_set_face_blend_law_range1_radii)
- [UF_MODL_set_face_blend_law_range2_radii](#uf_modl_set_face_blend_law_range2_radii)
- [UF_MODL_set_feat_tolerance](#uf_modl_set_feat_tolerance)
- [UF_MODL_set_flange_proc_factor](#uf_modl_set_flange_proc_factor)
- [UF_MODL_set_free_form_result](#uf_modl_set_free_form_result)
- [UF_MODL_set_immediate_children](#uf_modl_set_immediate_children)
- [UF_MODL_set_midsrf_feature_create_method](#uf_modl_set_midsrf_feature_create_method)
- [UF_MODL_set_rpo_refernce](#uf_modl_set_rpo_refernce)
- [UF_MODL_set_show_report_reference](#uf_modl_set_show_report_reference)
- [UF_MODL_set_suppress_exp_tag](#uf_modl_set_suppress_exp_tag)
- [UF_MODL_set_sweep_axis](#uf_modl_set_sweep_axis)
- [UF_MODL_set_sweep_tolerances](#uf_modl_set_sweep_tolerances)
- [UF_MODL_set_udf_parms](#uf_modl_set_udf_parms)
- [UF_MODL_set_update_fail_option](#uf_modl_set_update_fail_option)
- [UF_MODL_set_xform_tag_of_datum_csys](#uf_modl_set_xform_tag_of_datum_csys)
- [UF_MODL_sflange_continuity_e](#uf_modl_sflange_continuity_e)
- [UF_MODL_sflange_data_s](#uf_modl_sflange_data_s)
- [UF_MODL_sflange_dir_e](#uf_modl_sflange_dir_e)
- [UF_MODL_sflange_trim_e](#uf_modl_sflange_trim_e)
- [UF_MODL_sflange_type_e](#uf_modl_sflange_type_e)
- [UF_MODL_shape_pattern_client_dialog_data_s](#uf_modl_shape_pattern_client_dialog_data_s)
- [UF_MODL_shape_pattern_create_dialog](#uf_modl_shape_pattern_create_dialog)
- [UF_MODL_shape_pattern_free_client_data](#uf_modl_shape_pattern_free_client_data)
- [UF_MODL_shape_pattern_init_client_data](#uf_modl_shape_pattern_init_client_data)
- [UF_MODL_show_parent_curves](#uf_modl_show_parent_curves)
- [UF_MODL_simpl_data_s](#uf_modl_simpl_data_s)
- [UF_MODL_single_outline_s](#uf_modl_single_outline_s)
- [UF_MODL_slot_type_e](#uf_modl_slot_type_e)
- [UF_MODL_smbend_angle_e](#uf_modl_smbend_angle_e)
- [UF_MODL_smbend_corner_data_s](#uf_modl_smbend_corner_data_s)
- [UF_MODL_smbend_curve_e](#uf_modl_smbend_curve_e)
- [UF_MODL_smbend_cylinder_data_s](#uf_modl_smbend_cylinder_data_s)
- [UF_MODL_smbend_data_s](#uf_modl_smbend_data_s)
- [UF_MODL_smbend_direction_e](#uf_modl_smbend_direction_e)
- [UF_MODL_smbend_radius_e](#uf_modl_smbend_radius_e)
- [UF_MODL_smbend_stat_side_e](#uf_modl_smbend_stat_side_e)
- [UF_MODL_smbracket_data_s](#uf_modl_smbracket_data_s)
- [UF_MODL_smcorner_data_s](#uf_modl_smcorner_data_s)
- [UF_MODL_smcorner_type_t](#uf_modl_smcorner_type_t)
- [UF_MODL_smcutout_data_s](#uf_modl_smcutout_data_s)
- [UF_MODL_smcutout_type_e](#uf_modl_smcutout_type_e)
- [UF_MODL_smhole_data_s](#uf_modl_smhole_data_s)
- [UF_MODL_smhole_direction_type_e](#uf_modl_smhole_direction_type_e)
- [UF_MODL_smhole_type_e](#uf_modl_smhole_type_e)
- [UF_MODL_smjoggle_data_s](#uf_modl_smjoggle_data_s)
- [UF_MODL_smooth_bsurface_data](#uf_modl_smooth_bsurface_data)
- [UF_MODL_smpunch_cut_sets_s](#uf_modl_smpunch_cut_sets_s)
- [UF_MODL_smpunch_data_s](#uf_modl_smpunch_data_s)
- [UF_MODL_smpunch_top_type_e](#uf_modl_smpunch_top_type_e)
- [UF_MODL_smrelief_data_s](#uf_modl_smrelief_data_s)
- [UF_MODL_smslot_data_s](#uf_modl_smslot_data_s)
- [UF_MODL_smslot_type_e](#uf_modl_smslot_type_e)
- [UF_MODL_smspunch_type_t](#uf_modl_smspunch_type_t)
- [UF_MODL_snipsrf_feature_data_s](#uf_modl_snipsrf_feature_data_s)
- [UF_MODL_snipsurf_boundary_type_e](#uf_modl_snipsurf_boundary_type_e)
- [UF_MODL_snipsurf_refit_method_e](#uf_modl_snipsurf_refit_method_e)
- [UF_MODL_solid_punch_data_s](#uf_modl_solid_punch_data_s)
- [UF_MODL_sort_features](#uf_modl_sort_features)
- [UF_MODL_spherical_corner_s](#uf_modl_spherical_corner_s)
- [UF_MODL_split_body](#uf_modl_split_body)
- [UF_MODL_split_body_retain_tool](#uf_modl_split_body_retain_tool)
- [UF_MODL_state_e](#uf_modl_state_e)
- [UF_MODL_state_info_s](#uf_modl_state_info_s)
- [UF_MODL_stycorner_crv_opt_s](#uf_modl_stycorner_crv_opt_s)
- [UF_MODL_stycorner_data_s](#uf_modl_stycorner_data_s)
- [UF_MODL_styled_sweep_data_s](#uf_modl_styled_sweep_data_s)
- [UF_MODL_styled_sweep_move_string_e](#uf_modl_styled_sweep_move_string_e)
- [UF_MODL_subtract_bodies](#uf_modl_subtract_bodies)
- [UF_MODL_subtract_bodies_with_retained_options](#uf_modl_subtract_bodies_with_retained_options)
- [UF_MODL_suppress_feature](#uf_modl_suppress_feature)
- [UF_MODL_symb_thread_data_s](#uf_modl_symb_thread_data_s)
- [UF_MODL_taper_relative_to_e](#uf_modl_taper_relative_to_e)
- [UF_MODL_trace_a_ray](#uf_modl_trace_a_ray)
- [UF_MODL_transf_aa_s](#uf_modl_transf_aa_s)
- [UF_MODL_transf_angle_s](#uf_modl_transf_angle_s)
- [UF_MODL_transf_dist_s](#uf_modl_transf_dist_s)
- [UF_MODL_transf_pp_s](#uf_modl_transf_pp_s)
- [UF_MODL_transform_type_t](#uf_modl_transform_type_t)
- [UF_MODL_trim_blend_options](#uf_modl_trim_blend_options)
- [UF_MODL_trim_body](#uf_modl_trim_body)
- [UF_MODL_trim_midsrf_feature](#uf_modl_trim_midsrf_feature)
- [UF_MODL_trim_object](#uf_modl_trim_object)
- [UF_MODL_trim_sheet](#uf_modl_trim_sheet)
- [UF_MODL_udf_default_edit_mapping_tool](#uf_modl_udf_default_edit_mapping_tool)
- [UF_MODL_udf_default_insert_mapping_tool](#uf_modl_udf_default_insert_mapping_tool)
- [UF_MODL_udf_exp_data_s](#uf_modl_udf_exp_data_s)
- [UF_MODL_udf_free_exp_data](#uf_modl_udf_free_exp_data)
- [UF_MODL_udf_free_mapping_data](#uf_modl_udf_free_mapping_data)
- [UF_MODL_udf_free_ref_data](#uf_modl_udf_free_ref_data)
- [UF_MODL_udf_init_exp_data](#uf_modl_udf_init_exp_data)
- [UF_MODL_udf_init_insert_data_from_def](#uf_modl_udf_init_insert_data_from_def)
- [UF_MODL_udf_init_mapping_data](#uf_modl_udf_init_mapping_data)
- [UF_MODL_udf_init_ref_data](#uf_modl_udf_init_ref_data)
- [UF_MODL_udf_mapping_data_s](#uf_modl_udf_mapping_data_s)
- [UF_MODL_udf_mapping_data_union](#uf_modl_udf_mapping_data_union)
- [UF_MODL_udf_mapping_f_p_t](#uf_modl_udf_mapping_f_p_t)
- [UF_MODL_udf_ref_data_s](#uf_modl_udf_ref_data_s)
- [UF_MODL_udf_reverse_dir_e](#uf_modl_udf_reverse_dir_e)
- [UF_MODL_udf_rpo_menu](#uf_modl_udf_rpo_menu)
- [UF_MODL_udfs_ask_def_data](#uf_modl_udfs_ask_def_data)
- [UF_MODL_udfs_create_def](#uf_modl_udfs_create_def)
- [UF_MODL_udfs_def_data_s](#uf_modl_udfs_def_data_s)
- [UF_MODL_udfs_exp_s](#uf_modl_udfs_exp_s)
- [UF_MODL_udfs_redefine_def](#uf_modl_udfs_redefine_def)
- [UF_MODL_unclock_instance](#uf_modl_unclock_instance)
- [UF_MODL_unclock_iset](#uf_modl_unclock_iset)
- [UF_MODL_unform_features](#uf_modl_unform_features)
- [UF_MODL_unite_bodies](#uf_modl_unite_bodies)
- [UF_MODL_unite_bodies_with_retained_options](#uf_modl_unite_bodies_with_retained_options)
- [UF_MODL_unregister_cliff_blend](#uf_modl_unregister_cliff_blend)
- [UF_MODL_unregister_rpo_routine](#uf_modl_unregister_rpo_routine)
- [UF_MODL_unregister_udf_mapping_routine](#uf_modl_unregister_udf_mapping_routine)
- [UF_MODL_unregister_var_blend](#uf_modl_unregister_var_blend)
- [UF_MODL_unset_containment](#uf_modl_unset_containment)
- [UF_MODL_unset_suppress_exp_tag](#uf_modl_unset_suppress_exp_tag)
- [UF_MODL_unsuppress_feature](#uf_modl_unsuppress_feature)
- [UF_MODL_update](#uf_modl_update)
- [UF_MODL_update_all_features](#uf_modl_update_all_features)
- [UF_MODL_update_for_animation](#uf_modl_update_for_animation)
- [UF_MODL_update_option_e](#uf_modl_update_option_e)
- [UF_MODL_validate_body](#uf_modl_validate_body)
- [UF_MODL_var_blend_f_t](#uf_modl_var_blend_f_t)
- [UF_MODL_vector_axis_s](#uf_modl_vector_axis_s)
- [UF_MODL_vector_defined_by_union](#uf_modl_vector_defined_by_union)
- [UF_MODL_vector_direction_s](#uf_modl_vector_direction_s)
- [UF_MODL_vector_face_normal_s](#uf_modl_vector_face_normal_s)
- [UF_MODL_vector_plane_of_curves_s](#uf_modl_vector_plane_of_curves_s)
- [UF_MODL_vector_s](#uf_modl_vector_s)
- [UF_MODL_vector_two_points_s](#uf_modl_vector_two_points_s)
- [UF_MODL_vector_type_e](#uf_modl_vector_type_e)
- [UF_MODL_wrap_assem_s](#uf_modl_wrap_assem_s)
- [UF_MODL_wrap_geom_s](#uf_modl_wrap_geom_s)
- [uf_modl.h](#uf_modl.h)
- [uf_modl_blends.h](#uf_modl_blends.h)
- [uf_modl_bsurf.h](#uf_modl_bsurf.h)
- [uf_modl_curves.h](#uf_modl_curves.h)
- [uf_modl_datum_features.h](#uf_modl_datum_features.h)
- [uf_modl_dfo.h](#uf_modl_dfo.h)
- [uf_modl_dieeng.h](#uf_modl_dieeng.h)
- [uf_modl_error.h](#uf_modl_error.h)
- [uf_modl_expressions.h](#uf_modl_expressions.h)
- [uf_modl_form_features.h](#uf_modl_form_features.h)
- [uf_modl_freeform.h](#uf_modl_freeform.h)
- [uf_modl_grooves.h](#uf_modl_grooves.h)
- [uf_modl_holes.h](#uf_modl_holes.h)
- [uf_modl_hollow.h](#uf_modl_hollow.h)
- [uf_modl_import_body.h](#uf_modl_import_body.h)
- [uf_modl_isets.h](#uf_modl_isets.h)
- [uf_modl_legacy.h](#uf_modl_legacy.h)
- [uf_modl_mswp.h](#uf_modl_mswp.h)
- [uf_modl_mswp_types.h](#uf_modl_mswp_types.h)
- [uf_modl_pads.h](#uf_modl_pads.h)
- [uf_modl_pockets.h](#uf_modl_pockets.h)
- [uf_modl_primitives.h](#uf_modl_primitives.h)
- [uf_modl_promotions.h](#uf_modl_promotions.h)
- [uf_modl_simplify.h](#uf_modl_simplify.h)
- [uf_modl_sketch.h](#uf_modl_sketch.h)
- [uf_modl_slots.h](#uf_modl_slots.h)
- [uf_modl_smd.h](#uf_modl_smd.h)
- [uf_modl_sweep.h](#uf_modl_sweep.h)
- [uf_modl_taper.h](#uf_modl_taper.h)
- [uf_modl_trex.h](#uf_modl_trex.h)
- [uf_modl_types.h](#uf_modl_types.h)
- [uf_modl_udf.h](#uf_modl_udf.h)
- [uf_modl_ugopenint.h](#uf_modl_ugopenint.h)
- [uf_modl_utilities.h](#uf_modl_utilities.h)
- [uf_modl_vdac.h](#uf_modl_vdac.h)

---

## UF_MODL #Defines

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/contents.html#defines


---

## UF_MODL Callbacks

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/contents.html#callbacks


---

## UF_MODL Enumerations

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/contents.html#enumerations


---

## UF_MODL Files

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/contents.html#files


---

## UF_MODL Functions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/contents.html#functions


---

## UF_MODL Structures

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/contents.html#structures


---

## UF_MODL Unions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/contents.html#unions


---

## UF_MODL_ALONG_DRIVER_NORMALS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_ALONG_DRIVER_NORMALS


---

## UF_MODL_ALONG_FIXED_VECTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_ALONG_FIXED_VECTOR


---

## UF_MODL_ALONG_NORMAL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_ALONG_NORMAL


---

## UF_MODL_ANIMATION_CREATE_FAILED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_ANIMATION_CREATE_FAILED


---

## UF_MODL_ANIMATION_UPDATE_FAILED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_ANIMATION_UPDATE_FAILED


---

## UF_MODL_APPLE_TORUS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_APPLE_TORUS


---

## UF_MODL_ARC_CENTER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_ARC_CENTER


---

## UF_MODL_ARC_TANGENT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_ARC_TANGENT


---

## UF_MODL_ARRAYS_NON_DISTINCT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_ARRAYS_NON_DISTINCT


---

## UF_MODL_BAD_ARRAY_LENGTH

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_BAD_ARRAY_LENGTH


---

## UF_MODL_BAD_DATUM_CONSTRAINT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_BAD_DATUM_CONSTRAINT


---

## UF_MODL_BLENDING_FACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_BLENDING_FACE


---

## UF_MODL_BLEND_CLIFF_OVERFLOW

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_BLEND_CLIFF_OVERFLOW


---

## UF_MODL_BLEND_NOTCH_OVERFLOW

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_BLEND_NOTCH_OVERFLOW


---

## UF_MODL_BLEND_NO_OVERFLOW

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_BLEND_NO_OVERFLOW


---

## UF_MODL_BLEND_SMOOTH_OVERFLOW

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_BLEND_SMOOTH_OVERFLOW


---

## UF_MODL_BOTH_X_PERIODIC

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_BOTH_X_PERIODIC


---

## UF_MODL_B_SURFACE_DRIVER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_B_SURFACE_DRIVER


---

## UF_MODL_CIRCULAR_EDGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_CIRCULAR_EDGE


---

## UF_MODL_CLOSED_NON_PERIODIC_CURVE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_CLOSED_NON_PERIODIC_CURVE


---

## UF_MODL_CLOSED_PERIODIC_CURVE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_CLOSED_PERIODIC_CURVE


---

## UF_MODL_COMPARE_BOTH_ARE_SAME_PARTS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_COMPARE_BOTH_ARE_SAME_PARTS


---

## UF_MODL_COMPARE_EXAMINE_GEOM_FAILED_PART1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_COMPARE_EXAMINE_GEOM_FAILED_PART1


---

## UF_MODL_COMPARE_EXAMINE_GEOM_FAILED_PART2

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_COMPARE_EXAMINE_GEOM_FAILED_PART2


---

## UF_MODL_COMPARE_INVALID_PART1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_COMPARE_INVALID_PART1


---

## UF_MODL_COMPARE_INVALID_PART2

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_COMPARE_INVALID_PART2


---

## UF_MODL_COMPARE_NO_BODIES_PART1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_COMPARE_NO_BODIES_PART1


---

## UF_MODL_COMPARE_NO_BODIES_PART2

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_COMPARE_NO_BODIES_PART2


---

## UF_MODL_COMP_CURR_VER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_mdlcmp.html#UF_MODL_COMP_CURR_VER


---

## UF_MODL_CONICAL_FACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_CONICAL_FACE


---

## UF_MODL_CONICAL_TOPOLOGY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_CONICAL_TOPOLOGY


---

## UF_MODL_CONST_PARAMETER_EDGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_CONST_PARAMETER_EDGE


---

## UF_MODL_CONVERGENT_EDGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_CONVERGENT_EDGE


---

## UF_MODL_CONVERGENT_FACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_CONVERGENT_FACE


---

## UF_MODL_CYLINDRICAL_FACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_CYLINDRICAL_FACE


---

## UF_MODL_CYLINDRICAL_TOPOLOGY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_CYLINDRICAL_TOPOLOGY


---

## UF_MODL_DEVCHK_FIRST_EDGE_NOT_ON_FIRST_FACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_DEVCHK_FIRST_EDGE_NOT_ON_FIRST_FACE


---

## UF_MODL_DEVCHK_SAME_EDGE_FACE_COMBO_TWICE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_DEVCHK_SAME_EDGE_FACE_COMBO_TWICE


---

## UF_MODL_DEVCHK_SAME_TAG_INPUT_TWICE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_DEVCHK_SAME_TAG_INPUT_TWICE


---

## UF_MODL_DEVCHK_SECOND_EDGE_NOT_ON_SECOND_FACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_DEVCHK_SECOND_EDGE_NOT_ON_SECOND_FACE


---

## UF_MODL_DEVCHK_TOO_FEW_CHECK_POINTS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_DEVCHK_TOO_FEW_CHECK_POINTS


---

## UF_MODL_DEVCHK_TOO_FEW_U_CHECK_POINTS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_DEVCHK_TOO_FEW_U_CHECK_POINTS


---

## UF_MODL_DEVCHK_TOO_FEW_V_CHECK_POINTS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_DEVCHK_TOO_FEW_V_CHECK_POINTS


---

## UF_MODL_DEVCHK_WRONG_FIRST_CURVE_TAG

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_DEVCHK_WRONG_FIRST_CURVE_TAG


---

## UF_MODL_DEVCHK_WRONG_FIRST_EDGE_TAG

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_DEVCHK_WRONG_FIRST_EDGE_TAG


---

## UF_MODL_DEVCHK_WRONG_FIRST_FACE_TAG

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_DEVCHK_WRONG_FIRST_FACE_TAG


---

## UF_MODL_DEVCHK_WRONG_SECOND_CURVE_TAG

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_DEVCHK_WRONG_SECOND_CURVE_TAG


---

## UF_MODL_DEVCHK_WRONG_SECOND_EDGE_TAG

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_DEVCHK_WRONG_SECOND_EDGE_TAG


---

## UF_MODL_DEVCHK_WRONG_SECOND_FACE_TAG

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_DEVCHK_WRONG_SECOND_FACE_TAG


---

## UF_MODL_DOUGHNUT_TORUS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_DOUGHNUT_TORUS


---

## UF_MODL_DRAFTBODY_MATCHTYPE_TANGENTTOFACE_NOT_SUPPORTED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_DRAFTBODY_MATCHTYPE_TANGENTTOFACE_NOT_SUPPORTED


---

## UF_MODL_DUPLICATE_ELEMENT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_DUPLICATE_ELEMENT


---

## UF_MODL_DYNAMIC_UPDATE_CONTINUOUS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_DYNAMIC_UPDATE_CONTINUOUS


---

## UF_MODL_DYNAMIC_UPDATE_INCREMENTAL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_DYNAMIC_UPDATE_INCREMENTAL


---

## UF_MODL_EDGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_EDGE


---

## UF_MODL_ELLIPTICAL_EDGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_ELLIPTICAL_EDGE


---

## UF_MODL_ENDPOINT_1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_ENDPOINT_1


---

## UF_MODL_ENDPOINT_2

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_ENDPOINT_2


---

## UF_MODL_END_POINT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_END_POINT


---

## UF_MODL_ERROR_SHIFT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_ERROR_SHIFT


---

## UF_MODL_ERR_BLEND_CANT_APPLY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_ERR_BLEND_CANT_APPLY


---

## UF_MODL_ERR_BLEND_HASNO_INPUTDATA

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_ERR_BLEND_HASNO_INPUTDATA


---

## UF_MODL_ERR_CANT_QUERY_PARMS_FOR_PSM_FACET_FACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_ERR_CANT_QUERY_PARMS_FOR_PSM_FACET_FACE


---

## UF_MODL_ERR_CLOSEST_APPROACH_FAILED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_ERR_CLOSEST_APPROACH_FAILED


---

## UF_MODL_ERR_INVALID_LS_WEIGHT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_ERR_INVALID_LS_WEIGHT


---

## UF_MODL_ERR_MULTIPLE_BODIES

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_ERR_MULTIPLE_BODIES


---

## UF_MODL_ERR_NULL_SECTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_ERR_NULL_SECTION


---

## UF_MODL_ERR_PENDING_UPDATE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_ERR_PENDING_UPDATE


---

## UF_MODL_ERR_invalid_pointer

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_ERR_invalid_pointer


---

## UF_MODL_EVAL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_EVAL


---

## UF_MODL_EVAL_ALL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_EVAL_ALL


---

## UF_MODL_EVAL_DERIV1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_EVAL_DERIV1


---

## UF_MODL_EVAL_DERIV2

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_EVAL_DERIV2


---

## UF_MODL_EVAL_DERIV3

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_EVAL_DERIV3


---

## UF_MODL_EVAL_NORMAL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_EVAL_NORMAL


---

## UF_MODL_EVAL_UNIT_NORMAL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_EVAL_UNIT_NORMAL


---

## UF_MODL_FILE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl.html#UF_MODL_FILE


---

## UF_MODL_FIXED_LENGTH

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_FIXED_LENGTH


---

## UF_MODL_FLAT_TOPOLOGY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_FLAT_TOPOLOGY


---

## UF_MODL_FOREIGN_EDGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_FOREIGN_EDGE


---

## UF_MODL_FOREIGN_FACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_FOREIGN_FACE


---

## UF_MODL_FULL_THREAD

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_FULL_THREAD


---

## UF_MODL_HORZ_CENTERLINE_PNT_1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_HORZ_CENTERLINE_PNT_1


---

## UF_MODL_HORZ_CENTERLINE_PNT_2

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_HORZ_CENTERLINE_PNT_2


---

## UF_MODL_INCL_INSTANCES

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_INCL_INSTANCES


---

## UF_MODL_INIT_COMPARE_OPTIONS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_mdlcmp.html#UF_MODL_INIT_COMPARE_OPTIONS


---

## UF_MODL_INTERSECTION_EDGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_INTERSECTION_EDGE


---

## UF_MODL_INTERSECT_NOT_PLANE_OR_DATUM_PLANE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_INTERSECT_NOT_PLANE_OR_DATUM_PLANE


---

## UF_MODL_INVALID_FACE_OR_PLANE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_INVALID_FACE_OR_PLANE


---

## UF_MODL_INVALID_LENGTH_PARAMETER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_INVALID_LENGTH_PARAMETER


---

## UF_MODL_INVALID_ROOT_PART

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_INVALID_ROOT_PART


---

## UF_MODL_INVALID_WORK_PART

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_INVALID_WORK_PART


---

## UF_MODL_LATER_TIMESTAMP

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_LATER_TIMESTAMP


---

## UF_MODL_LEFT_END_POINT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_LEFT_END_POINT


---

## UF_MODL_LEFT_HAND

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_LEFT_HAND


---

## UF_MODL_LEMON_TORUS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_LEMON_TORUS


---

## UF_MODL_LIMITS_NOT_SUPPORTED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_LIMITS_NOT_SUPPORTED


---

## UF_MODL_LINEAR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_LINEAR


---

## UF_MODL_LINEAR_EDGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_LINEAR_EDGE


---

## UF_MODL_LOC

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_LOC


---

## UF_MODL_LOC_1STDERV

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_LOC_1STDERV


---

## UF_MODL_LOC_1STDERV_2NDDERV

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_LOC_1STDERV_2NDDERV


---

## UF_MODL_MAX_X_PERIODIC

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_MAX_X_PERIODIC


---

## UF_MODL_MESH_OF_CURVES_DRIVER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_MESH_OF_CURVES_DRIVER


---

## UF_MODL_MID_POINT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_MID_POINT


---

## UF_MODL_MIN_X_PERIODIC

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_MIN_X_PERIODIC


---

## UF_MODL_NON_PERIODIC

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_NON_PERIODIC


---

## UF_MODL_NON_TAPERED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_NON_TAPERED


---

## UF_MODL_NOT_A_TORUS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_NOT_A_TORUS


---

## UF_MODL_NOT_SAME_BODY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_NOT_SAME_BODY


---

## UF_MODL_NO_DYNAMIC_UPDATE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_NO_DYNAMIC_UPDATE


---

## UF_MODL_NO_INSTANCES

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_NO_INSTANCES


---

## UF_MODL_OFFSET_FACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_OFFSET_FACE


---

## UF_MODL_OPEN_CURVE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_OPEN_CURVE


---

## UF_MODL_OPPOSITE_NORMAL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_OPPOSITE_NORMAL


---

## UF_MODL_OSCULATING_APPLE_TORUS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_OSCULATING_APPLE_TORUS


---

## UF_MODL_PARAMETRIC_FACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_PARAMETRIC_FACE


---

## UF_MODL_PATCH_HOLE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_PATCH_HOLE


---

## UF_MODL_PERIODIC

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_PERIODIC


---

## UF_MODL_PLANAR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_PLANAR


---

## UF_MODL_PLANAR_FACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_PLANAR_FACE


---

## UF_MODL_POINT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_POINT


---

## UF_MODL_POINT_NOT_ON_FACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_POINT_NOT_ON_FACE


---

## UF_MODL_REPAIR_OPTION_PLANES_NOT_SUPPORTED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_REPAIR_OPTION_PLANES_NOT_SUPPORTED


---

## UF_MODL_RIGHT_END_POINT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_RIGHT_END_POINT


---

## UF_MODL_RIGHT_HAND

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_RIGHT_HAND


---

## UF_MODL_SELF_REFIT_DRIVER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_SELF_REFIT_DRIVER


---

## UF_MODL_SHEET_BODY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_SHEET_BODY


---

## UF_MODL_SIMPL_FACE_NOT_REMOVED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_SIMPL_FACE_NOT_REMOVED


---

## UF_MODL_SIMPL_HEAL_FAILED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_SIMPL_HEAL_FAILED


---

## UF_MODL_SIMPL_NO_FACES_DELETED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_SIMPL_NO_FACES_DELETED


---

## UF_MODL_SIMPL_NO_RETAINED_FACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_SIMPL_NO_RETAINED_FACE


---

## UF_MODL_SOLID_BODY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_SOLID_BODY


---

## UF_MODL_SPHERICAL_FACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_SPHERICAL_FACE


---

## UF_MODL_SPHERICAL_TOPOLOGY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_SPHERICAL_TOPOLOGY


---

## UF_MODL_SPLINE_EDGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_SPLINE_EDGE


---

## UF_MODL_SP_CURVE_EDGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_SP_CURVE_EDGE


---

## UF_MODL_SRF_VALUE_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_SRF_VALUE_s.html


---

## UF_MODL_STATE_CLAMPED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STATE_CLAMPED


---

## UF_MODL_STATE_CLOSED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STATE_CLOSED


---

## UF_MODL_STATE_DEGENERACY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STATE_DEGENERACY


---

## UF_MODL_STATE_DEGEN_EDGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STATE_DEGEN_EDGE


---

## UF_MODL_STATE_G1_DISCONTINUITY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STATE_G1_DISCONTINUITY


---

## UF_MODL_STATE_IS_FIXED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STATE_IS_FIXED


---

## UF_MODL_STATE_IS_V

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STATE_IS_V


---

## UF_MODL_STATE_KNOT_DECREASING

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STATE_KNOT_DECREASING


---

## UF_MODL_STATE_KNOT_MULT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STATE_KNOT_MULT


---

## UF_MODL_STATE_KNOT_NONC0

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STATE_KNOT_NONC0


---

## UF_MODL_STATE_KNOT_TOOCLOSE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STATE_KNOT_TOOCLOSE


---

## UF_MODL_STATE_PERIODIC

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STATE_PERIODIC


---

## UF_MODL_STATE_RANGE_END

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STATE_RANGE_END


---

## UF_MODL_STATE_RANGE_START

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STATE_RANGE_START


---

## UF_MODL_STATE_SELF_INTERSECT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STATE_SELF_INTERSECT


---

## UF_MODL_STATE_SMOOTHED_TO_CN

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STATE_SMOOTHED_TO_CN


---

## UF_MODL_STATE_UNNORMALIZED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STATE_UNNORMALIZED


---

## UF_MODL_STRING_ADD

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STRING_ADD


---

## UF_MODL_STRING_REMOVE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STRING_REMOVE


---

## UF_MODL_STRING_REPLACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_STRING_REPLACE


---

## UF_MODL_SWEEP_TRIM_OPTS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_SWEEP_TRIM_OPTS


---

## UF_MODL_SWEEP_TRIM_SIGNS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_SWEEP_TRIM_SIGNS


---

## UF_MODL_SWEEP_TRIM_object_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_SWEEP_TRIM_object_s.html


---

## UF_MODL_SWEEP_free_trim_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_SWEEP_free_trim_data


---

## UF_MODL_SWEPT_FACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_SWEPT_FACE


---

## UF_MODL_TAPERED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_TAPERED


---

## UF_MODL_THREE_DIMENSIONAL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_THREE_DIMENSIONAL


---

## UF_MODL_TOROIDAL_FACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_TOROIDAL_FACE


---

## UF_MODL_TOROIDAL_TOPOLOGY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_TOROIDAL_TOPOLOGY


---

## UF_MODL_TORUS_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_TORUS_TYPE


---

## UF_MODL_TREX_algorithm_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_TREX_algorithm_e


---

## UF_MODL_TREX_appl_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_TREX_appl_data_s.html


---

## UF_MODL_TREX_ask_trim_extend

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_TREX_ask_trim_extend


---

## UF_MODL_TREX_create_trex_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_TREX_create_trex_feature


---

## UF_MODL_TREX_data_set_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_TREX_data_set_s.html


---

## UF_MODL_TREX_edit_trex_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_TREX_edit_trex_feature


---

## UF_MODL_TREX_extend_method_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_TREX_extend_method_e


---

## UF_MODL_TREX_free_trex_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_TREX_free_trex_data


---

## UF_MODL_TREX_init_trex_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_TREX_init_trex_data


---

## UF_MODL_TREX_init_trex_data_set

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_TREX_init_trex_data_set


---

## UF_MODL_TREX_region_option_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_TREX_region_option_e


---

## UF_MODL_TREX_to_option_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_TREX_to_option_e


---

## UF_MODL_TRIMMED_CURVE_EDGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_TRIMMED_CURVE_EDGE


---

## UF_MODL_UDF_CANT_EDITED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_UDF_CANT_EDITED


---

## UF_MODL_UDF_CANT_INSTANTIATED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_UDF_CANT_INSTANTIATED


---

## UF_MODL_UDF_INVALID_EXPS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_UDF_INVALID_EXPS


---

## UF_MODL_UDF_INVALID_MAPPING

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_UDF_INVALID_MAPPING


---

## UF_MODL_UDF_INVALID_PARENTS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_UDF_INVALID_PARENTS


---

## UF_MODL_UNABLE_TO_CREATE_GEODESIC_CURVES

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_UNABLE_TO_CREATE_GEODESIC_CURVES


---

## UF_MODL_UNABLE_TO_FIRE_RAY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_UNABLE_TO_FIRE_RAY


---

## UF_MODL_UPDATE_ALL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_UPDATE_ALL


---

## UF_MODL_UPDATE_FIRST_LEVEL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_UPDATE_FIRST_LEVEL


---

## UF_MODL_VERT_CENTERLINE_PNT_1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_VERT_CENTERLINE_PNT_1


---

## UF_MODL_VERT_CENTERLINE_PNT_2

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_types.html#UF_MODL_VERT_CENTERLINE_PNT_2


---

## UF_MODL_WRONG_BODY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_WRONG_BODY


---

## UF_MODL_WRONG_CURVE_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/uf_modl_error.html#UF_MODL_WRONG_CURVE_TYPE


---

## UF_MODL_active_part

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_active_part


---

## UF_MODL_add_thru_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_add_thru_faces


---

## UF_MODL_ask_2dtrim_bsurf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_2dtrim_bsurf


---

## UF_MODL_ask_adjac_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_adjac_faces


---

## UF_MODL_ask_alive_edge

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_alive_edge


---

## UF_MODL_ask_alive_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_alive_face


---

## UF_MODL_ask_all_members_of_set

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_all_members_of_set


---

## UF_MODL_ask_angle_edge

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_angle_edge


---

## UF_MODL_ask_angle_tolerance_of_part

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_angle_tolerance_of_part


---

## UF_MODL_ask_ball_groove_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_ball_groove_parms


---

## UF_MODL_ask_ball_slot_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_ball_slot_parms


---

## UF_MODL_ask_bead

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_bead


---

## UF_MODL_ask_bend_allowance_formula

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_bend_allowance_formula


---

## UF_MODL_ask_bend_operation

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_bend_operation


---

## UF_MODL_ask_blend_face_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_blend_face_data


---

## UF_MODL_ask_blend_face_data1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_blend_face_data1


---

## UF_MODL_ask_blend_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_blend_parms


---

## UF_MODL_ask_block_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_block_parms


---

## UF_MODL_ask_body_boundaries

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_body_boundaries


---

## UF_MODL_ask_body_consistency

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_body_consistency


---

## UF_MODL_ask_body_density

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_body_density


---

## UF_MODL_ask_body_edges

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_body_edges


---

## UF_MODL_ask_body_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_body_faces


---

## UF_MODL_ask_body_feats

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_body_feats


---

## UF_MODL_ask_body_features

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_body_features


---

## UF_MODL_ask_body_structures

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_body_structures


---

## UF_MODL_ask_body_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_body_type


---

## UF_MODL_ask_body_type_pref

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_body_type_pref


---

## UF_MODL_ask_boolean_with_retained_options

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_boolean_with_retained_options


---

## UF_MODL_ask_boss_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_boss_parms


---

## UF_MODL_ask_bounding_box

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_bounding_box


---

## UF_MODL_ask_bounding_box_aligned

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_bounding_box_aligned


---

## UF_MODL_ask_bounding_box_exact

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_bounding_box_exact


---

## UF_MODL_ask_bplane

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_bplane


---

## UF_MODL_ask_bsurf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_bsurf


---

## UF_MODL_ask_bsurf_knot_display

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_bsurf_knot_display


---

## UF_MODL_ask_bsurf_pole_display

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_bsurf_pole_display


---

## UF_MODL_ask_c_bore_hole_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_c_bore_hole_parms


---

## UF_MODL_ask_c_sunk_hole_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_c_sunk_hole_parms


---

## UF_MODL_ask_chamfer_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_chamfer_parms


---

## UF_MODL_ask_circular_iset_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_circular_iset_parms


---

## UF_MODL_ask_circular_pattern_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_circular_pattern_face


---

## UF_MODL_ask_cnnc_edges

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_cnnc_edges


---

## UF_MODL_ask_cone_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_cone_parms


---

## UF_MODL_ask_constraint_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_constraint_type


---

## UF_MODL_ask_constraints

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_constraints


---

## UF_MODL_ask_current_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_current_feature


---

## UF_MODL_ask_curve_closed

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_curve_closed


---

## UF_MODL_ask_curve_fit_method

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_curve_fit_method


---

## UF_MODL_ask_curve_mesh

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_curve_mesh


---

## UF_MODL_ask_curve_mesh1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_curve_mesh1


---

## UF_MODL_ask_curve_parm

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_curve_parm


---

## UF_MODL_ask_curve_parm_no_ext

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_curve_parm_no_ext


---

## UF_MODL_ask_curve_periodicity

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_curve_periodicity


---

## UF_MODL_ask_curve_points

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_curve_points


---

## UF_MODL_ask_curve_props

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_curve_props


---

## UF_MODL_ask_cyl_pocket_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_cyl_pocket_parms


---

## UF_MODL_ask_cylinder_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_cylinder_parms


---

## UF_MODL_ask_datum_axis_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_datum_axis_parms


---

## UF_MODL_ask_datum_csys_components

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_datum_csys_components


---

## UF_MODL_ask_datum_plane

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_datum_plane


---

## UF_MODL_ask_datum_plane_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_datum_plane_parms


---

## UF_MODL_ask_datum_point_and_direction

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_datum_point_and_direction


---

## UF_MODL_ask_daxis_size

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_daxis_size


---

## UF_MODL_ask_default_density

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_default_density


---

## UF_MODL_ask_descriptor_of_exp

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_descriptor_of_exp


---

## UF_MODL_ask_die_tip

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_die_tip


---

## UF_MODL_ask_distance_tolerance_of_part

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_distance_tolerance_of_part


---

## UF_MODL_ask_dovetail_slot_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_dovetail_slot_parms


---

## UF_MODL_ask_dynamic_update

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_dynamic_update


---

## UF_MODL_ask_edge_blend

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_edge_blend


---

## UF_MODL_ask_edge_blend1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_edge_blend1


---

## UF_MODL_ask_edge_blend_is_mult

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_edge_blend_is_mult


---

## UF_MODL_ask_edge_blend_mult

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_edge_blend_mult


---

## UF_MODL_ask_edge_body

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_edge_body


---

## UF_MODL_ask_edge_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_edge_faces


---

## UF_MODL_ask_edge_feats

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_edge_feats


---

## UF_MODL_ask_edge_smoothness

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_edge_smoothness


---

## UF_MODL_ask_edge_tolerance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_edge_tolerance


---

## UF_MODL_ask_edge_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_edge_type


---

## UF_MODL_ask_edge_verts

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_edge_verts


---

## UF_MODL_ask_enlarge

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_enlarge


---

## UF_MODL_ask_exp

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_exp


---

## UF_MODL_ask_exp_desc_of_feat

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_exp_desc_of_feat


---

## UF_MODL_ask_exp_desc_of_frec

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_exp_desc_of_frec


---

## UF_MODL_ask_exp_tag_string

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_exp_tag_string


---

## UF_MODL_ask_exp_tag_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_exp_tag_value


---

## UF_MODL_ask_exps_of_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_exps_of_feature


---

## UF_MODL_ask_exps_of_part

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_exps_of_part


---

## UF_MODL_ask_extreme

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_extreme


---

## UF_MODL_ask_extrude_offset_dir

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_extrude_offset_dir


---

## UF_MODL_ask_extrusion

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_extrusion


---

## UF_MODL_ask_face_blend_law_radii

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_blend_law_radii


---

## UF_MODL_ask_face_blend_law_range1_radii

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_blend_law_range1_radii


---

## UF_MODL_ask_face_blend_law_range2_radii

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_blend_law_range2_radii


---

## UF_MODL_ask_face_body

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_body


---

## UF_MODL_ask_face_constraint

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_constraint


---

## UF_MODL_ask_face_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_data


---

## UF_MODL_ask_face_edges

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_edges


---

## UF_MODL_ask_face_face_intersect

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_face_intersect


---

## UF_MODL_ask_face_feats

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_feats


---

## UF_MODL_ask_face_grid_count

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_grid_count


---

## UF_MODL_ask_face_loops

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_loops


---

## UF_MODL_ask_face_min_radii

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_min_radii


---

## UF_MODL_ask_face_parm

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_parm


---

## UF_MODL_ask_face_parm_2

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_parm_2


---

## UF_MODL_ask_face_periodicity

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_periodicity


---

## UF_MODL_ask_face_props

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_props


---

## UF_MODL_ask_face_self_intersect

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_self_intersect


---

## UF_MODL_ask_face_smoothness

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_smoothness


---

## UF_MODL_ask_face_spikes

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_spikes


---

## UF_MODL_ask_face_topology

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_topology


---

## UF_MODL_ask_face_torus_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_torus_type


---

## UF_MODL_ask_face_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_type


---

## UF_MODL_ask_face_uv_minmax

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_face_uv_minmax


---

## UF_MODL_ask_facepair_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_facepair_parms


---

## UF_MODL_ask_feat_body

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_feat_body


---

## UF_MODL_ask_feat_direction

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_feat_direction


---

## UF_MODL_ask_feat_display_name

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_feat_display_name


---

## UF_MODL_ask_feat_edges

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_feat_edges


---

## UF_MODL_ask_feat_error

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_feat_error


---

## UF_MODL_ask_feat_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_feat_faces


---

## UF_MODL_ask_feat_fail_list

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_feat_fail_list


---

## UF_MODL_ask_feat_location

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_feat_location


---

## UF_MODL_ask_feat_name

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_feat_name


---

## UF_MODL_ask_feat_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_feat_object


---

## UF_MODL_ask_feat_or_udf_sysname

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_feat_or_udf_sysname


---

## UF_MODL_ask_feat_relatives

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_feat_relatives


---

## UF_MODL_ask_feat_sysname

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_feat_sysname


---

## UF_MODL_ask_feat_tolerance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_feat_tolerance


---

## UF_MODL_ask_feat_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_feat_type


---

## UF_MODL_ask_feat_warning_messages

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_feat_warning_messages


---

## UF_MODL_ask_feature_boolean

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_feature_boolean


---

## UF_MODL_ask_feature_sign

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_feature_sign


---

## UF_MODL_ask_features_of_exp

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_features_of_exp


---

## UF_MODL_ask_features_of_mirror_set

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_features_of_mirror_set


---

## UF_MODL_ask_features_of_udf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_features_of_udf


---

## UF_MODL_ask_flange_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_flange_parms


---

## UF_MODL_ask_flange_proc_factor

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_flange_proc_factor


---

## UF_MODL_ask_formable_feature_state

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_formable_feature_state


---

## UF_MODL_ask_free_form_result

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_free_form_result


---

## UF_MODL_ask_general_flange

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_general_flange


---

## UF_MODL_ask_general_pad

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_general_pad


---

## UF_MODL_ask_general_pad1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_general_pad1


---

## UF_MODL_ask_general_pocket

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_general_pocket


---

## UF_MODL_ask_general_pocket1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_general_pocket1


---

## UF_MODL_ask_gflange

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_gflange


---

## UF_MODL_ask_hollow_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_hollow_data


---

## UF_MODL_ask_hollow_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_hollow_parms


---

## UF_MODL_ask_horz_dime

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_horz_dime


---

## UF_MODL_ask_immediate_children

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_immediate_children


---

## UF_MODL_ask_impr_edges

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_impr_edges


---

## UF_MODL_ask_impr_faces_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_impr_faces_parms


---

## UF_MODL_ask_impr_loop_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_impr_loop_parms


---

## UF_MODL_ask_inset_flange_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_inset_flange_parms


---

## UF_MODL_ask_instance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_instance


---

## UF_MODL_ask_instance_iset

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_instance_iset


---

## UF_MODL_ask_instances_of_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_instances_of_feature


---

## UF_MODL_ask_instantiated_udf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_instantiated_udf


---

## UF_MODL_ask_law_extension

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_law_extension


---

## UF_MODL_ask_law_extension1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_law_extension1


---

## UF_MODL_ask_linear_iset_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_linear_iset_parms


---

## UF_MODL_ask_link_face_plane

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_link_face_plane


---

## UF_MODL_ask_link_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_link_faces


---

## UF_MODL_ask_linked_exterior

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_linked_exterior


---

## UF_MODL_ask_list_count

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_list_count


---

## UF_MODL_ask_list_item

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_list_item


---

## UF_MODL_ask_local_scale

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_local_scale


---

## UF_MODL_ask_loop_list_count

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_loop_list_count


---

## UF_MODL_ask_loop_list_item

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_loop_list_item


---

## UF_MODL_ask_mass_props_3d

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_mass_props_3d


---

## UF_MODL_ask_master

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_master


---

## UF_MODL_ask_matching_face_in_instance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_matching_face_in_instance


---

## UF_MODL_ask_max_curvature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_max_curvature


---

## UF_MODL_ask_merged_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_merged_faces


---

## UF_MODL_ask_midsrf_feature_create_method

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_midsrf_feature_create_method


---

## UF_MODL_ask_midsrf_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_midsrf_parms


---

## UF_MODL_ask_minimum_dist

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_minimum_dist


---

## UF_MODL_ask_minimum_dist_2

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_minimum_dist_2


---

## UF_MODL_ask_minimum_dist_3

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_minimum_dist_3


---

## UF_MODL_ask_mirror_pattern_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_mirror_pattern_face


---

## UF_MODL_ask_misalign_geometry

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_misalign_geometry


---

## UF_MODL_ask_move_region

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_move_region


---

## UF_MODL_ask_named_body_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_named_body_object


---

## UF_MODL_ask_nested_frecs

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_nested_frecs


---

## UF_MODL_ask_next_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_next_feature


---

## UF_MODL_ask_obj_dimensionality

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_obj_dimensionality


---

## UF_MODL_ask_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_object


---

## UF_MODL_ask_object_feat

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_object_feat


---

## UF_MODL_ask_offset_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_offset_parms


---

## UF_MODL_ask_offset_region

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_offset_region


---

## UF_MODL_ask_owning_feat_of_exp

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_owning_feat_of_exp


---

## UF_MODL_ask_para_dist

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_para_dist


---

## UF_MODL_ask_para_edge

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_para_edge


---

## UF_MODL_ask_patch_body_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_patch_body_parms


---

## UF_MODL_ask_perp_dist

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_perp_dist


---

## UF_MODL_ask_plane

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_plane


---

## UF_MODL_ask_plane_of_mirror_set

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_plane_of_mirror_set


---

## UF_MODL_ask_point_along_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_point_along_curve


---

## UF_MODL_ask_point_along_curve_2

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_point_along_curve_2


---

## UF_MODL_ask_point_containment

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_point_containment


---

## UF_MODL_ask_points_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_points_parms


---

## UF_MODL_ask_previous_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_previous_feature


---

## UF_MODL_ask_prism_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_prism_parms


---

## UF_MODL_ask_proj_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_proj_curves


---

## UF_MODL_ask_prom_feat_of_solid

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_prom_feat_of_solid


---

## UF_MODL_ask_promotion_path

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_promotion_path


---

## UF_MODL_ask_proper_legacy_feat_name

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_proper_legacy_feat_name


---

## UF_MODL_ask_quilt

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_quilt


---

## UF_MODL_ask_quilt_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_quilt_type


---

## UF_MODL_ask_reblend_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_reblend_face


---

## UF_MODL_ask_rect_groove_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_rect_groove_parms


---

## UF_MODL_ask_rect_pad_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_rect_pad_parms


---

## UF_MODL_ask_rect_pad_parms_1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_rect_pad_parms_1


---

## UF_MODL_ask_rect_pocket_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_rect_pocket_parms


---

## UF_MODL_ask_rect_slot_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_rect_slot_parms


---

## UF_MODL_ask_rectangular_pattern_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_rectangular_pattern_face


---

## UF_MODL_ask_references_of_features

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_references_of_features


---

## UF_MODL_ask_refit_face_feature_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_refit_face_feature_data


---

## UF_MODL_ask_replace_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_replace_face


---

## UF_MODL_ask_resize_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_resize_face


---

## UF_MODL_ask_revolution

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_revolution


---

## UF_MODL_ask_ripedge

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_ripedge


---

## UF_MODL_ask_rough_offset

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_rough_offset


---

## UF_MODL_ask_rpo_desc_of_feat

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_rpo_desc_of_feat


---

## UF_MODL_ask_rpo_desc_of_frec

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_rpo_desc_of_frec


---

## UF_MODL_ask_rpo_routine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_rpo_routine


---

## UF_MODL_ask_ruled

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_ruled


---

## UF_MODL_ask_ruled1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_ruled1


---

## UF_MODL_ask_scale

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_scale


---

## UF_MODL_ask_section_surface

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_section_surface


---

## UF_MODL_ask_set_from_name

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_set_from_name


---

## UF_MODL_ask_sets_of_member

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_sets_of_member


---

## UF_MODL_ask_shared_edges

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_shared_edges


---

## UF_MODL_ask_show_report_reference

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_show_report_reference


---

## UF_MODL_ask_silhouette_flange

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_silhouette_flange


---

## UF_MODL_ask_simple_hole_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_simple_hole_parms


---

## UF_MODL_ask_simplify_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_simplify_parms


---

## UF_MODL_ask_sketch_of_sweep

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_sketch_of_sweep


---

## UF_MODL_ask_smbend

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_smbend


---

## UF_MODL_ask_smbend_corner

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_smbend_corner


---

## UF_MODL_ask_smbend_cylinder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_smbend_cylinder


---

## UF_MODL_ask_smcorner

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_smcorner


---

## UF_MODL_ask_smcutout

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_smcutout


---

## UF_MODL_ask_smhole

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_smhole


---

## UF_MODL_ask_smpunch

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_smpunch


---

## UF_MODL_ask_smslot

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_smslot


---

## UF_MODL_ask_snip_surface_feature_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_snip_surface_feature_data


---

## UF_MODL_ask_solid_of_prom_feat

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_solid_of_prom_feat


---

## UF_MODL_ask_solid_punch

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_solid_punch


---

## UF_MODL_ask_sphere_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_sphere_parms


---

## UF_MODL_ask_split_edges

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_split_edges


---

## UF_MODL_ask_split_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_split_faces


---

## UF_MODL_ask_stycorner_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_stycorner_data


---

## UF_MODL_ask_styled_sweep_feature_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_styled_sweep_feature_data


---

## UF_MODL_ask_subdiv_face_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_subdiv_face_parms


---

## UF_MODL_ask_suppress_exp_tag

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_suppress_exp_tag


---

## UF_MODL_ask_suppress_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_suppress_feature


---

## UF_MODL_ask_suppress_list

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_suppress_list


---

## UF_MODL_ask_sweep

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_sweep


---

## UF_MODL_ask_sweep_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_sweep_curves


---

## UF_MODL_ask_sweep_direction

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_sweep_direction


---

## UF_MODL_ask_sweep_of_udf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_sweep_of_udf


---

## UF_MODL_ask_sweep_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_sweep_parms


---

## UF_MODL_ask_symb_thread_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_symb_thread_parms


---

## UF_MODL_ask_t_slot_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_t_slot_parms


---

## UF_MODL_ask_taper_from_edges

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_taper_from_edges


---

## UF_MODL_ask_taper_from_edges1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_taper_from_edges1


---

## UF_MODL_ask_taper_hole_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_taper_hole_parms


---

## UF_MODL_ask_taper_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_taper_parms


---

## UF_MODL_ask_thru_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_thru_curves


---

## UF_MODL_ask_thru_curves1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_thru_curves1


---

## UF_MODL_ask_thru_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_thru_faces


---

## UF_MODL_ask_time_stamp_of_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_time_stamp_of_feature


---

## UF_MODL_ask_tiny_geometry

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_tiny_geometry


---

## UF_MODL_ask_torus_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_torus_parms


---

## UF_MODL_ask_trimmed_sheet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_trimmed_sheet


---

## UF_MODL_ask_u_groove_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_u_groove_parms


---

## UF_MODL_ask_u_slot_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_u_slot_parms


---

## UF_MODL_ask_udf_definition

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_udf_definition


---

## UF_MODL_ask_udf_mapping_for_edit

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_udf_mapping_for_edit


---

## UF_MODL_ask_udf_mapping_for_insert

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_udf_mapping_for_insert


---

## UF_MODL_ask_udf_mapping_routine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_udf_mapping_routine


---

## UF_MODL_ask_udf_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_udf_parms


---

## UF_MODL_ask_update_error_message

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_update_error_message


---

## UF_MODL_ask_update_fail_option

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_update_fail_option


---

## UF_MODL_ask_update_undo_feat

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_update_undo_feat


---

## UF_MODL_ask_uv_points_containment

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_uv_points_containment


---

## UF_MODL_ask_vda_4955_compliance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_vda_4955_compliance


---

## UF_MODL_ask_vector_angle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_vector_angle


---

## UF_MODL_ask_vert_dime

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_vert_dime


---

## UF_MODL_ask_wrap_assembly

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_wrap_assembly


---

## UF_MODL_ask_wrap_geometry

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_wrap_geometry


---

## UF_MODL_ask_xform_tag_of_datum_csys

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_ask_xform_tag_of_datum_csys


---

## UF_MODL_assign_string_directions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_assign_string_directions


---

## UF_MODL_auto_midsrf_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_auto_midsrf_feature


---

## UF_MODL_auto_midsrf_feature_w_opts

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_auto_midsrf_feature_w_opts


---

## UF_MODL_b_surface_along_driver_normals_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_b_surface_along_driver_normals_data_s.html


---

## UF_MODL_b_surface_along_fixed_vector_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_b_surface_along_fixed_vector_data_s.html


---

## UF_MODL_bead_angle_relative_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_bead_angle_relative_e


---

## UF_MODL_bead_attach_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_bead_attach_e


---

## UF_MODL_bead_ends

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_bead_ends


---

## UF_MODL_bead_hollow_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_bead_hollow_e


---

## UF_MODL_bead_plane_defined_by_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_bead_plane_defined_by_s.html


---

## UF_MODL_bead_plane_fixed_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_bead_plane_fixed_s.html


---

## UF_MODL_bead_plane_normal_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_bead_plane_normal_e


---

## UF_MODL_bead_section_parms_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_bead_section_parms_s.html


---

## UF_MODL_bead_section_plane_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_bead_section_plane_s.html


---

## UF_MODL_bead_shape_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_bead_shape_e


---

## UF_MODL_bead_width_relative_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_bead_width_relative_e


---

## UF_MODL_bend_operation_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_bend_operation_data_s.html


---

## UF_MODL_bend_operation_e_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_bend_operation_e_t


---

## UF_MODL_blend_edge_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_blend_edge_s.html


---

## UF_MODL_blend_faces_create_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_blend_faces_create_data_s.html


---

## UF_MODL_blend_faces_limit_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_blend_faces_limit_data_s.html


---

## UF_MODL_blend_law_parms_union

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_blend_law_parms_union.html


---

## UF_MODL_blend_point_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_blend_point_data_s.html


---

## UF_MODL_blend_point_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_blend_point_s.html


---

## UF_MODL_blend_radius_types

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_blend_radius_types


---

## UF_MODL_boolean_body

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_boolean_body


---

## UF_MODL_boolean_udf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_boolean_udf


---

## UF_MODL_boolean_udf_1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_boolean_udf_1


---

## UF_MODL_bracket_outline_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_bracket_outline_data_s.html


---

## UF_MODL_bracket_outline_data_union

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_bracket_outline_data_union.html


---

## UF_MODL_bsurf_row_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_bsurf_row_info_s.html


---

## UF_MODL_bsurface_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_bsurface_s.html


---

## UF_MODL_calculate_ref_dir

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_calculate_ref_dir


---

## UF_MODL_change_offset_base_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_change_offset_base_face


---

## UF_MODL_check_interference

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_check_interference


---

## UF_MODL_cliff_blend_f_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/callback.html#UF_MODL_cliff_blend_f_t


---

## UF_MODL_clock_instance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_clock_instance


---

## UF_MODL_compare

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_compare


---

## UF_MODL_compare_accuracy_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_compare_accuracy_e


---

## UF_MODL_compare_changeduniqueface_rule_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_compare_changeduniqueface_rule_e


---

## UF_MODL_compare_entity_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_compare_entity_info_s.html


---

## UF_MODL_compare_entity_match_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_compare_entity_match_s.html


---

## UF_MODL_compare_entity_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_compare_entity_type_e


---

## UF_MODL_compare_identicalface_rule_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_compare_identicalface_rule_e


---

## UF_MODL_compare_options_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_compare_options_s.html


---

## UF_MODL_compare_part_entities_data_3_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_compare_part_entities_data_3_s.html


---

## UF_MODL_compare_part_entities_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_compare_part_entities_data_s.html


---

## UF_MODL_compare_part_map_data_3_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_compare_part_map_data_3_s.html


---

## UF_MODL_compare_part_map_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_compare_part_map_data_s.html


---

## UF_MODL_compare_topology

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_compare_topology


---

## UF_MODL_convert_to_fixed_datum

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_convert_to_fixed_datum


---

## UF_MODL_copy_paste_features

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_copy_paste_features


---

## UF_MODL_cre_2dtrim_bsurf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_cre_2dtrim_bsurf


---

## UF_MODL_cre_chamfer_with_flip_option

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_cre_chamfer_with_flip_option


---

## UF_MODL_cre_chamfer_with_instance_and_flip_option

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_cre_chamfer_with_instance_and_flip_option


---

## UF_MODL_cre_def_facepair_feat

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_cre_def_facepair_feat


---

## UF_MODL_cre_sel_facepair_feat

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_cre_sel_facepair_feat


---

## UF_MODL_cre_trim_bsurf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_cre_trim_bsurf


---

## UF_MODL_create_ball_groove

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_ball_groove


---

## UF_MODL_create_ball_slot

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_ball_slot


---

## UF_MODL_create_bead

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_bead


---

## UF_MODL_create_bend_operation

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_bend_operation


---

## UF_MODL_create_blend

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_blend


---

## UF_MODL_create_blend_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_blend_faces


---

## UF_MODL_create_block

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_block


---

## UF_MODL_create_block1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_block1


---

## UF_MODL_create_boss

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_boss


---

## UF_MODL_create_bplane

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_bplane


---

## UF_MODL_create_bridge_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_bridge_face


---

## UF_MODL_create_bs_2d_edges

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_bs_2d_edges


---

## UF_MODL_create_bs_edges

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_bs_edges


---

## UF_MODL_create_bsurf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_bsurf


---

## UF_MODL_create_bsurf_thru_pts

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_bsurf_thru_pts


---

## UF_MODL_create_bsurface

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_bsurface


---

## UF_MODL_create_c_bore_hole

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_c_bore_hole


---

## UF_MODL_create_c_sunk_hole

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_c_sunk_hole


---

## UF_MODL_create_chamfer

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_chamfer


---

## UF_MODL_create_circular_iset

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_circular_iset


---

## UF_MODL_create_circular_pattern_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_circular_pattern_face


---

## UF_MODL_create_cone

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_cone


---

## UF_MODL_create_cone1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_cone1


---

## UF_MODL_create_curve_from_edge

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_curve_from_edge


---

## UF_MODL_create_curve_mesh

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_curve_mesh


---

## UF_MODL_create_curve_mesh1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_curve_mesh1


---

## UF_MODL_create_cyl1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_cyl1


---

## UF_MODL_create_cyl_pocket

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_cyl_pocket


---

## UF_MODL_create_cylinder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_cylinder


---

## UF_MODL_create_datum_csys

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_datum_csys


---

## UF_MODL_create_datum_csys_offset

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_datum_csys_offset


---

## UF_MODL_create_dove_tail_slot

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_dove_tail_slot


---

## UF_MODL_create_edge_blend

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_edge_blend


---

## UF_MODL_create_edge_blend_mult

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_edge_blend_mult


---

## UF_MODL_create_enlarge

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_enlarge


---

## UF_MODL_create_exp

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_exp


---

## UF_MODL_create_exp_tag

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_exp_tag


---

## UF_MODL_create_extrude_trim_opts

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_extrude_trim_opts


---

## UF_MODL_create_extrude_trim_opts1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_extrude_trim_opts1


---

## UF_MODL_create_extruded

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_extruded


---

## UF_MODL_create_extruded1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_extruded1


---

## UF_MODL_create_extruded2

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_extruded2


---

## UF_MODL_create_extruded_path

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_extruded_path


---

## UF_MODL_create_extruded_path1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_extruded_path1


---

## UF_MODL_create_extrusion

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_extrusion


---

## UF_MODL_create_extrusion1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_extrusion1


---

## UF_MODL_create_extrusion2

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_extrusion2


---

## UF_MODL_create_extrusion_default

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_extrusion_default


---

## UF_MODL_create_extrusion_default1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_extrusion_default1


---

## UF_MODL_create_extrusion_dir

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_extrusion_dir


---

## UF_MODL_create_extrusion_path

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_extrusion_path


---

## UF_MODL_create_extrusion_path1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_extrusion_path1


---

## UF_MODL_create_face_blend

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_face_blend


---

## UF_MODL_create_face_constraint

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_face_constraint


---

## UF_MODL_create_face_offset

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_face_offset


---

## UF_MODL_create_face_taper

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_face_taper


---

## UF_MODL_create_feature_offset

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_feature_offset


---

## UF_MODL_create_feature_taper

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_feature_taper


---

## UF_MODL_create_fitted_spline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_fitted_spline


---

## UF_MODL_create_fixed_daxis

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_fixed_daxis


---

## UF_MODL_create_fixed_dplane

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_fixed_dplane


---

## UF_MODL_create_flange

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_flange


---

## UF_MODL_create_frenet_daxis

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_frenet_daxis


---

## UF_MODL_create_general_flange

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_general_flange


---

## UF_MODL_create_general_pad

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_general_pad


---

## UF_MODL_create_general_pocket

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_general_pocket


---

## UF_MODL_create_geodesic_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_geodesic_curves


---

## UF_MODL_create_gflange

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_gflange


---

## UF_MODL_create_hollow

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_hollow


---

## UF_MODL_create_impr_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_impr_faces


---

## UF_MODL_create_impr_loop

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_impr_loop


---

## UF_MODL_create_inset_flange

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_inset_flange


---

## UF_MODL_create_instantiated_udf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_instantiated_udf


---

## UF_MODL_create_instantiated_udf1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_instantiated_udf1


---

## UF_MODL_create_isocline_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_isocline_curves


---

## UF_MODL_create_isocurve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_isocurve


---

## UF_MODL_create_law

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_law


---

## UF_MODL_create_law_extension

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_law_extension


---

## UF_MODL_create_linear_iset

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_linear_iset


---

## UF_MODL_create_linked_exterior

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_linked_exterior


---

## UF_MODL_create_list

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_list


---

## UF_MODL_create_local_scale

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_local_scale


---

## UF_MODL_create_midsrf_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_midsrf_feature


---

## UF_MODL_create_mirror_body

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_mirror_body


---

## UF_MODL_create_mirror_pattern_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_mirror_pattern_face


---

## UF_MODL_create_mirror_set

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_mirror_set


---

## UF_MODL_create_move_region

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_move_region


---

## UF_MODL_create_multi_transition_law

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_multi_transition_law


---

## UF_MODL_create_non_uni_scale

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_non_uni_scale


---

## UF_MODL_create_offset_region

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_offset_region


---

## UF_MODL_create_plane

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_plane


---

## UF_MODL_create_point_dirr_daxis

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_point_dirr_daxis


---

## UF_MODL_create_point_dirr_dplane

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_point_dirr_dplane


---

## UF_MODL_create_points_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_points_feature


---

## UF_MODL_create_proj_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_proj_curves


---

## UF_MODL_create_promotion

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_promotion


---

## UF_MODL_create_quilt

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_quilt


---

## UF_MODL_create_reblend_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_reblend_face


---

## UF_MODL_create_rect_groove

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_rect_groove


---

## UF_MODL_create_rect_pad

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_rect_pad


---

## UF_MODL_create_rect_pocket

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_rect_pocket


---

## UF_MODL_create_rect_slot

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_rect_slot


---

## UF_MODL_create_rectangular_pattern_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_rectangular_pattern_face


---

## UF_MODL_create_refit_face_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_refit_face_feature


---

## UF_MODL_create_relative_daxis

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_relative_daxis


---

## UF_MODL_create_relative_dplane

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_relative_dplane


---

## UF_MODL_create_reparam_sheet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_reparam_sheet


---

## UF_MODL_create_replace_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_replace_face


---

## UF_MODL_create_resize_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_resize_face


---

## UF_MODL_create_reverse_normal

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_reverse_normal


---

## UF_MODL_create_revolution

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_revolution


---

## UF_MODL_create_revolution1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_revolution1


---

## UF_MODL_create_revolution_dir

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_revolution_dir


---

## UF_MODL_create_ripedge

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_ripedge


---

## UF_MODL_create_rough_offset

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_rough_offset


---

## UF_MODL_create_rpo_constraints

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_rpo_constraints


---

## UF_MODL_create_ruled

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_ruled


---

## UF_MODL_create_ruled1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_ruled1


---

## UF_MODL_create_scale

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_scale


---

## UF_MODL_create_section_surface

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_section_surface


---

## UF_MODL_create_set_of_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_set_of_feature


---

## UF_MODL_create_silhouette_flange

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_silhouette_flange


---

## UF_MODL_create_silhouette_flange_pipe

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_silhouette_flange_pipe


---

## UF_MODL_create_simple_hole

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_simple_hole


---

## UF_MODL_create_simplified_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_simplified_curve


---

## UF_MODL_create_simplify

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_simplify


---

## UF_MODL_create_smbend

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_smbend


---

## UF_MODL_create_smbend_corner

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_smbend_corner


---

## UF_MODL_create_smbend_cylinder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_smbend_cylinder


---

## UF_MODL_create_smbracket

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_smbracket


---

## UF_MODL_create_smcorner

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_smcorner


---

## UF_MODL_create_smcutout

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_smcutout


---

## UF_MODL_create_smd_flange

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_smd_flange


---

## UF_MODL_create_smhole

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_smhole


---

## UF_MODL_create_smjoggle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_smjoggle


---

## UF_MODL_create_smpunch

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_smpunch


---

## UF_MODL_create_smrelief

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_smrelief


---

## UF_MODL_create_smslot

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_smslot


---

## UF_MODL_create_snip_surface_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_snip_surface_feature


---

## UF_MODL_create_solid_punch

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_solid_punch


---

## UF_MODL_create_sphere

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_sphere


---

## UF_MODL_create_sphere1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_sphere1


---

## UF_MODL_create_spline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_spline


---

## UF_MODL_create_string_list

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_string_list


---

## UF_MODL_create_stycorner

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_stycorner


---

## UF_MODL_create_styled_sweep_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_styled_sweep_feature


---

## UF_MODL_create_subdiv_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_subdiv_face


---

## UF_MODL_create_surf_from_cloud

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_surf_from_cloud


---

## UF_MODL_create_sweep

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_sweep


---

## UF_MODL_create_t_slot

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_t_slot


---

## UF_MODL_create_taper_from_edges

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_taper_from_edges


---

## UF_MODL_create_taper_from_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_taper_from_faces


---

## UF_MODL_create_taper_from_tangent_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_taper_from_tangent_faces


---

## UF_MODL_create_taper_split_line

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_taper_split_line


---

## UF_MODL_create_thru_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_thru_curves


---

## UF_MODL_create_thru_curves1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_thru_curves1


---

## UF_MODL_create_trimmed_sheet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_trimmed_sheet


---

## UF_MODL_create_trimmed_tube

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_trimmed_tube


---

## UF_MODL_create_trimmed_tube1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_trimmed_tube1


---

## UF_MODL_create_true_taper_from_edges

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_true_taper_from_edges


---

## UF_MODL_create_tube

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_tube


---

## UF_MODL_create_tube1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_tube1


---

## UF_MODL_create_u_groove

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_u_groove


---

## UF_MODL_create_u_slot

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_u_slot


---

## UF_MODL_create_uniform_scale

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_uniform_scale


---

## UF_MODL_create_variable_hollow

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_variable_hollow


---

## UF_MODL_create_variable_offset

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_variable_offset


---

## UF_MODL_create_variable_taper_from_edges

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_variable_taper_from_edges


---

## UF_MODL_create_wrap_assembly

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_wrap_assembly


---

## UF_MODL_create_wrap_geometry

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_create_wrap_geometry


---

## UF_MODL_curve_direction_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_curve_direction_e


---

## UF_MODL_curve_mesh_along_driver_normals_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_curve_mesh_along_driver_normals_data_s.html


---

## UF_MODL_curve_mesh_along_fixed_vector_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_curve_mesh_along_fixed_vector_data_s.html


---

## UF_MODL_curves_represent_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_curves_represent_e


---

## UF_MODL_default_rpo_menu

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_default_rpo_menu


---

## UF_MODL_delete_body_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_delete_body_parms


---

## UF_MODL_delete_exp

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_delete_exp


---

## UF_MODL_delete_exp_tag

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_delete_exp_tag


---

## UF_MODL_delete_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_delete_feature


---

## UF_MODL_delete_list

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_delete_list


---

## UF_MODL_delete_list_item

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_delete_list_item


---

## UF_MODL_delete_loop_list

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_delete_loop_list


---

## UF_MODL_delete_object_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_delete_object_parms


---

## UF_MODL_density_units_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_density_units_e


---

## UF_MODL_devchk_adjacent_edges

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_devchk_adjacent_edges


---

## UF_MODL_devchk_curve_to_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_devchk_curve_to_curve


---

## UF_MODL_devchk_curve_to_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_devchk_curve_to_face


---

## UF_MODL_devchk_edge_to_edge

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_devchk_edge_to_edge


---

## UF_MODL_devchk_edge_to_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_devchk_edge_to_face


---

## UF_MODL_devchk_ee_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_devchk_ee_info_s.html


---

## UF_MODL_devchk_face_to_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_devchk_face_to_face


---

## UF_MODL_deviation_check_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_deviation_check_data_s.html


---

## UF_MODL_dfo_constraint_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_dfo_constraint_s.html


---

## UF_MODL_dfo_constraint_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_dfo_constraint_type_e


---

## UF_MODL_dfo_region_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_dfo_region_s.html


---

## UF_MODL_dfo_scale_type_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_dfo_scale_type_t


---

## UF_MODL_die_tip_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_die_tip_info_s.html


---

## UF_MODL_dimension_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_dimension_data_s.html


---

## UF_MODL_dissect_exp_string

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_dissect_exp_string


---

## UF_MODL_dump_midsurf_facepair_report

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_dump_midsurf_facepair_report


---

## UF_MODL_edge_blend_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_edge_blend_data_s.html


---

## UF_MODL_edge_blend_mult_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_edge_blend_mult_data_s.html


---

## UF_MODL_edge_blend_set_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_edge_blend_set_s.html


---

## UF_MODL_edge_blend_setback_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_edge_blend_setback_data_s.html


---

## UF_MODL_edge_blend_stopshort_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_edge_blend_stopshort_data_s.html


---

## UF_MODL_edit_bead

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_bead


---

## UF_MODL_edit_bend_allowance_formula

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_bend_allowance_formula


---

## UF_MODL_edit_bend_operation

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_bend_operation


---

## UF_MODL_edit_boolean_with_retained_options

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_boolean_with_retained_options


---

## UF_MODL_edit_bsurf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_bsurf


---

## UF_MODL_edit_circular_iset

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_circular_iset


---

## UF_MODL_edit_circular_pattern_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_circular_pattern_face


---

## UF_MODL_edit_datum_direction

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_datum_direction


---

## UF_MODL_edit_datum_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_datum_point


---

## UF_MODL_edit_edge_blend

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_edge_blend


---

## UF_MODL_edit_edge_blend_mult

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_edge_blend_mult


---

## UF_MODL_edit_enlarge

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_enlarge


---

## UF_MODL_edit_exp

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_exp


---

## UF_MODL_edit_face_constraint

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_face_constraint


---

## UF_MODL_edit_face_grid_count

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_face_grid_count


---

## UF_MODL_edit_face_join

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_face_join


---

## UF_MODL_edit_formable_feature_state

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_formable_feature_state


---

## UF_MODL_edit_general_flange

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_general_flange


---

## UF_MODL_edit_general_pad

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_general_pad


---

## UF_MODL_edit_general_pocket

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_general_pocket


---

## UF_MODL_edit_gflange

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_gflange


---

## UF_MODL_edit_hole_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_hole_type


---

## UF_MODL_edit_hollow

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_hollow


---

## UF_MODL_edit_import_body_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_import_body_feature


---

## UF_MODL_edit_import_body_features

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_import_body_features


---

## UF_MODL_edit_impr_faces_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_impr_faces_parms


---

## UF_MODL_edit_impr_loop_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_impr_loop_parms


---

## UF_MODL_edit_inset_flange

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_inset_flange


---

## UF_MODL_edit_instantiated_udf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_instantiated_udf


---

## UF_MODL_edit_law_extension

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_law_extension


---

## UF_MODL_edit_linear_iset

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_linear_iset


---

## UF_MODL_edit_linked_exterior

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_linked_exterior


---

## UF_MODL_edit_local_scale

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_local_scale


---

## UF_MODL_edit_mirror_pattern_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_mirror_pattern_face


---

## UF_MODL_edit_mirror_set

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_mirror_set


---

## UF_MODL_edit_move_region

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_move_region


---

## UF_MODL_edit_offset_region

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_offset_region


---

## UF_MODL_edit_patch_body_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_patch_body_parms


---

## UF_MODL_edit_plane

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_plane


---

## UF_MODL_edit_points_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_points_parms


---

## UF_MODL_edit_quilt

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_quilt


---

## UF_MODL_edit_reblend_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_reblend_face


---

## UF_MODL_edit_rectangular_pattern_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_rectangular_pattern_face


---

## UF_MODL_edit_refit_face_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_refit_face_feature


---

## UF_MODL_edit_replace_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_replace_face


---

## UF_MODL_edit_resize_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_resize_face


---

## UF_MODL_edit_ripedge

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_ripedge


---

## UF_MODL_edit_rough_offset

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_rough_offset


---

## UF_MODL_edit_scale

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_scale


---

## UF_MODL_edit_section_surface

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_section_surface


---

## UF_MODL_edit_set_hide_state

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_set_hide_state


---

## UF_MODL_edit_set_members

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_set_members


---

## UF_MODL_edit_silhouette_flange

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_silhouette_flange


---

## UF_MODL_edit_simplify_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_simplify_parms


---

## UF_MODL_edit_slot_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_slot_type


---

## UF_MODL_edit_smbend

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_smbend


---

## UF_MODL_edit_smbend_corner

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_smbend_corner


---

## UF_MODL_edit_smbend_cylinder

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_smbend_cylinder


---

## UF_MODL_edit_smcorner

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_smcorner


---

## UF_MODL_edit_smcutout

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_smcutout


---

## UF_MODL_edit_smd_flange

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_smd_flange


---

## UF_MODL_edit_smhole

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_smhole


---

## UF_MODL_edit_smpunch

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_smpunch


---

## UF_MODL_edit_smslot

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_smslot


---

## UF_MODL_edit_snip_surface_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_snip_surface_feature


---

## UF_MODL_edit_solid_punch

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_solid_punch


---

## UF_MODL_edit_stycorner

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_stycorner


---

## UF_MODL_edit_styled_sweep_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_styled_sweep_feature


---

## UF_MODL_edit_subdiv_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_subdiv_face


---

## UF_MODL_edit_sweep_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_sweep_curves


---

## UF_MODL_edit_symb_thread

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_symb_thread


---

## UF_MODL_edit_taper_from_edges

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_taper_from_edges


---

## UF_MODL_edit_trimmed_sheet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_trimmed_sheet


---

## UF_MODL_edit_wrap_assembly

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_wrap_assembly


---

## UF_MODL_edit_wrap_geometry

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_edit_wrap_geometry


---

## UF_MODL_err_feature_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_err_feature_e


---

## UF_MODL_eval_exp

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_eval_exp


---

## UF_MODL_evaluate_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_evaluate_curve


---

## UF_MODL_evaluate_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_evaluate_face


---

## UF_MODL_evaluate_parm

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_evaluate_parm


---

## UF_MODL_export_exp

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_export_exp


---

## UF_MODL_export_udf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_export_udf


---

## UF_MODL_extract_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_extract_face


---

## UF_MODL_face_blend_create_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_face_blend_create_data_s.html


---

## UF_MODL_face_extension_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_face_extension_e


---

## UF_MODL_faces_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_faces_s.html


---

## UF_MODL_feature_can_be_copied

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_feature_can_be_copied


---

## UF_MODL_features_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_features_s.html


---

## UF_MODL_fix_bsurface_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_fix_bsurface_data


---

## UF_MODL_flange_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_flange_data_s.html


---

## UF_MODL_form_features

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_form_features


---

## UF_MODL_free_bead

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_free_bead


---

## UF_MODL_free_bsurf_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_free_bsurf_data


---

## UF_MODL_free_compare_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_free_compare_data


---

## UF_MODL_free_compare_data_3

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_free_compare_data_3


---

## UF_MODL_free_general_pad

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_free_general_pad


---

## UF_MODL_free_general_pocket

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_free_general_pocket


---

## UF_MODL_free_gflange_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_free_gflange_data


---

## UF_MODL_free_law

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_free_law


---

## UF_MODL_free_law_extension

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_free_law_extension


---

## UF_MODL_free_quilt

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_free_quilt


---

## UF_MODL_free_refit_face_feature_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_free_refit_face_feature_data


---

## UF_MODL_free_rough_offset_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_free_rough_offset_data


---

## UF_MODL_free_silhouette_flange

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_free_silhouette_flange


---

## UF_MODL_free_snip_surface_feature_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_free_snip_surface_feature_data


---

## UF_MODL_free_string_list

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_free_string_list


---

## UF_MODL_free_styled_sweep_feature_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_free_styled_sweep_feature_data


---

## UF_MODL_free_symb_thread_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_free_symb_thread_data


---

## UF_MODL_free_udfs_def_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_free_udfs_def_data


---

## UF_MODL_genflg_ask_num_states

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_genflg_ask_num_states


---

## UF_MODL_genflg_ask_state_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_genflg_ask_state_data


---

## UF_MODL_genflg_create_state

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_genflg_create_state


---

## UF_MODL_genflg_delete_state

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_genflg_delete_state


---

## UF_MODL_genflg_edit_state

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_genflg_edit_state


---

## UF_MODL_genflg_state_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_genflg_state_data_s.html


---

## UF_MODL_get_curve_edge_direction

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_get_curve_edge_direction


---

## UF_MODL_get_dimension_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_get_dimension_data


---

## UF_MODL_gflange_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_gflange_data_s.html


---

## UF_MODL_gflange_distort_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_gflange_distort_e


---

## UF_MODL_gflange_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_gflange_e


---

## UF_MODL_gflange_options_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_gflange_options_data_s.html


---

## UF_MODL_gflange_parameters_mode_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_gflange_parameters_mode_data_s.html


---

## UF_MODL_gflange_punch_vector_mode_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_gflange_punch_vector_mode_data_s.html


---

## UF_MODL_gflange_sections_mode_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_gflange_sections_mode_data_s.html


---

## UF_MODL_gflange_shaping_faces_mode_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_gflange_shaping_faces_mode_data_s.html


---

## UF_MODL_hide_parent_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_hide_parent_curves


---

## UF_MODL_hole_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_hole_type_e


---

## UF_MODL_identify_exterior_using_hl

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_identify_exterior_using_hl


---

## UF_MODL_identify_exterior_using_rays

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_identify_exterior_using_rays


---

## UF_MODL_import_body_feature_edit_option_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_import_body_feature_edit_option_e


---

## UF_MODL_import_exp

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_import_exp


---

## UF_MODL_import_udf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_import_udf


---

## UF_MODL_imprint_faces_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_imprint_faces_data_s.html


---

## UF_MODL_imprint_loop_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_imprint_loop_data_s.html


---

## UF_MODL_init_edge_blend_mult

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_init_edge_blend_mult


---

## UF_MODL_init_edge_blend_point_mult

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_init_edge_blend_point_mult


---

## UF_MODL_init_edge_blend_set_mult

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_init_edge_blend_set_mult


---

## UF_MODL_init_edge_blend_setback_mult

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_init_edge_blend_setback_mult


---

## UF_MODL_init_edge_blend_stopshort_mult

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_init_edge_blend_stopshort_mult


---

## UF_MODL_init_face_blend_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_init_face_blend_data


---

## UF_MODL_init_ripedge_ufdata

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_init_ripedge_ufdata


---

## UF_MODL_init_section_surface

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_init_section_surface


---

## UF_MODL_init_silhouette_flange_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_init_silhouette_flange_data


---

## UF_MODL_init_smcorner_ufdata

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_init_smcorner_ufdata


---

## UF_MODL_init_string_list

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_init_string_list


---

## UF_MODL_init_stycorner_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_init_stycorner_data


---

## UF_MODL_initialize_compare_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_initialize_compare_data


---

## UF_MODL_inset_flange_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_inset_flange_data_s.html


---

## UF_MODL_intersect_bodies

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_intersect_bodies


---

## UF_MODL_intersect_bodies_with_retained_options

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_intersect_bodies_with_retained_options


---

## UF_MODL_intersect_curve_to_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_intersect_curve_to_curve


---

## UF_MODL_intersect_curve_to_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_intersect_curve_to_face


---

## UF_MODL_intersect_curve_to_plane

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_intersect_curve_to_plane


---

## UF_MODL_intersect_info_coincide_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_intersect_info_coincide_s.html


---

## UF_MODL_intersect_info_curve_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_intersect_info_curve_s.html


---

## UF_MODL_intersect_info_intersect_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_intersect_info_intersect_s.html


---

## UF_MODL_intersect_info_point_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_intersect_info_point_s.html


---

## UF_MODL_intersect_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_intersect_info_s.html


---

## UF_MODL_intersect_objects

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_intersect_objects


---

## UF_MODL_intersect_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_intersect_type_e


---

## UF_MODL_is_body_convergent

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_is_body_convergent


---

## UF_MODL_is_body_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_is_body_feature


---

## UF_MODL_is_browseable_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_is_browseable_feature


---

## UF_MODL_is_datum_axis_reversed

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_is_datum_axis_reversed


---

## UF_MODL_is_datum_plane_reversed

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_is_datum_plane_reversed


---

## UF_MODL_is_exp_in_part

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_is_exp_in_part


---

## UF_MODL_is_feature_a_hidden_set_member

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_is_feature_a_hidden_set_member


---

## UF_MODL_is_feature_a_set_member

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_is_feature_a_set_member


---

## UF_MODL_is_geometric_expression

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_is_geometric_expression


---

## UF_MODL_is_import_body_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_is_import_body_feature


---

## UF_MODL_isodivide_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_isodivide_face


---

## UF_MODL_isotrim_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_isotrim_face


---

## UF_MODL_law_constant_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_law_constant_s.html


---

## UF_MODL_law_curve_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_law_curve_s.html


---

## UF_MODL_law_defined_by_u

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_law_defined_by_u.html


---

## UF_MODL_law_equation_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_law_equation_s.html


---

## UF_MODL_law_linear_cubic_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_law_linear_cubic_s.html


---

## UF_MODL_law_method_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_law_method_e


---

## UF_MODL_law_no_spine_constant_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_law_no_spine_constant_s.html


---

## UF_MODL_law_no_spine_curve_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_law_no_spine_curve_s.html


---

## UF_MODL_law_no_spine_defined_by_union

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_law_no_spine_defined_by_union.html


---

## UF_MODL_law_no_spine_equation_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_law_no_spine_equation_s.html


---

## UF_MODL_law_no_spine_linear_cubic_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_law_no_spine_linear_cubic_s.html


---

## UF_MODL_law_no_spine_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_law_no_spine_s.html


---

## UF_MODL_law_spine_pt_val_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_law_spine_pt_val_s.html


---

## UF_MODL_law_spine_pts_linear_cubic_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_law_spine_pts_linear_cubic_s.html


---

## UF_MODL_law_spine_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_law_spine_s.html


---

## UF_MODL_lawext_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_lawext_data_s.html


---

## UF_MODL_lawext_dirref_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_lawext_dirref_e


---

## UF_MODL_linked_ext_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_linked_ext_s.html


---

## UF_MODL_mapping_data_output_objs_non_ss_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_mapping_data_output_objs_non_ss_s.html


---

## UF_MODL_mapping_data_output_objs_ss_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_mapping_data_output_objs_ss_s.html


---

## UF_MODL_matchedge_ask_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_matchedge_ask_data


---

## UF_MODL_matchedge_check

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_matchedge_check


---

## UF_MODL_matchedge_create_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_matchedge_create_feature


---

## UF_MODL_matchedge_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_matchedge_data_s.html


---

## UF_MODL_matchedge_edit_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_matchedge_edit_feature


---

## UF_MODL_matchedge_free_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_matchedge_free_data


---

## UF_MODL_mode_specific_data_u

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_mode_specific_data_u.html


---

## UF_MODL_model_compare

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_model_compare


---

## UF_MODL_model_compare_2

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_model_compare_2


---

## UF_MODL_model_compare_3

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_model_compare_3


---

## UF_MODL_move_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_move_feature


---

## UF_MODL_mswp_ask_extrude

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_mswp_ask_extrude


---

## UF_MODL_mswp_create_extrude

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_mswp_create_extrude


---

## UF_MODL_mswp_edit_extrude

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_mswp_edit_extrude


---

## UF_MODL_mswp_extrude_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_mswp_extrude_s.html


---

## UF_MODL_mswp_init_extrude_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_mswp_init_extrude_data


---

## UF_MODL_mswp_limit_data_u

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_mswp_limit_data_u.html


---

## UF_MODL_mswp_limit_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_mswp_limit_s.html


---

## UF_MODL_mswp_limit_type_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_mswp_limit_type_t


---

## UF_MODL_mswp_limits_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_mswp_limits_s.html


---

## UF_MODL_mswp_multi_taper_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_mswp_multi_taper_s.html


---

## UF_MODL_mswp_offset_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_mswp_offset_type_e


---

## UF_MODL_mswp_offsets_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_mswp_offsets_s.html


---

## UF_MODL_mswp_string_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_mswp_string_data_s.html


---

## UF_MODL_mswp_taper_chain_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_mswp_taper_chain_s.html


---

## UF_MODL_mswp_taper_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_mswp_taper_s.html


---

## UF_MODL_mswp_taper_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_mswp_taper_type_e


---

## UF_MODL_mswp_until_selected_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_mswp_until_selected_data_s.html


---

## UF_MODL_offset_trans_faces_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_offset_trans_faces_s.html


---

## UF_MODL_offset_trans_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_offset_trans_type_e


---

## UF_MODL_operations

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_operations


---

## UF_MODL_outline_represents_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_outline_represents_e


---

## UF_MODL_overlap_check_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_overlap_check_e


---

## UF_MODL_parent_disp_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_parent_disp_info_s.html


---

## UF_MODL_parm_constant_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_parm_constant_s.html


---

## UF_MODL_parm_defined_by_union

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_parm_defined_by_union.html


---

## UF_MODL_parm_law_no_spine_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_parm_law_no_spine_s.html


---

## UF_MODL_parm_law_spine_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_parm_law_spine_s.html


---

## UF_MODL_parm_method_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_parm_method_e


---

## UF_MODL_parm_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_parm_s.html


---

## UF_MODL_paste_features

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_paste_features


---

## UF_MODL_patch_body

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_patch_body


---

## UF_MODL_pocketpad_outline_defined_by_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_pocketpad_outline_defined_by_s.html


---

## UF_MODL_pocketpad_outline_double_outline_corner_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_pocketpad_outline_double_outline_corner_s.html


---

## UF_MODL_pocketpad_outline_double_outline_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_pocketpad_outline_double_outline_s.html


---

## UF_MODL_pocketpad_outline_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_pocketpad_outline_s.html


---

## UF_MODL_pocketpad_outline_single_outline_corner_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_pocketpad_outline_single_outline_corner_s.html


---

## UF_MODL_pocketpad_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_pocketpad_type_e


---

## UF_MODL_preview_simplify

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_preview_simplify


---

## UF_MODL_proj_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_proj_type_e


---

## UF_MODL_project_curves_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_project_curves_s.html


---

## UF_MODL_prom_map_object_down

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_prom_map_object_down


---

## UF_MODL_prom_map_object_up

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_prom_map_object_up


---

## UF_MODL_punch_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_punch_type_e


---

## UF_MODL_put_list_item

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_put_list_item


---

## UF_MODL_quilt_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_quilt_data_s.html


---

## UF_MODL_quilt_data_structures_union

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_quilt_data_structures_union.html


---

## UF_MODL_quilt_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_quilt_type_e


---

## UF_MODL_ray_hit_point_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_ray_hit_point_info_s.html


---

## UF_MODL_reattach_dir_ref

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_reattach_dir_ref


---

## UF_MODL_reattach_target_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_reattach_target_face


---

## UF_MODL_reattach_thru_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_reattach_thru_faces


---

## UF_MODL_reattach_tool_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_reattach_tool_face


---

## UF_MODL_reblend_face_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_reblend_face_data_s.html


---

## UF_MODL_reblend_face_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_reblend_face_s.html


---

## UF_MODL_record_feature_update_warnings

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_record_feature_update_warnings


---

## UF_MODL_redefine_replace_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_redefine_replace_faces


---

## UF_MODL_redefine_rpo_constraint

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_redefine_rpo_constraint


---

## UF_MODL_redefine_trim_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_redefine_trim_faces


---

## UF_MODL_refit_face_continuity_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_refit_face_continuity_e


---

## UF_MODL_refit_face_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_refit_face_data_s.html


---

## UF_MODL_refit_face_fit_direction_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_refit_face_fit_direction_e


---

## UF_MODL_refit_face_refit_direction_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_refit_face_refit_direction_e


---

## UF_MODL_refit_face_refit_method_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_refit_face_refit_method_e


---

## UF_MODL_refit_face_target_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_refit_face_target_data_s.html


---

## UF_MODL_register_cliff_blend

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_register_cliff_blend


---

## UF_MODL_register_rpo_routine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_register_rpo_routine


---

## UF_MODL_register_udf_mapping_routine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_register_udf_mapping_routine


---

## UF_MODL_register_var_blend

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_register_var_blend


---

## UF_MODL_remove_thru_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_remove_thru_faces


---

## UF_MODL_rename_exp

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_rename_exp


---

## UF_MODL_reorder_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_reorder_feature


---

## UF_MODL_replace_body_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_replace_body_data


---

## UF_MODL_replace_boolean_body

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_replace_boolean_body


---

## UF_MODL_replace_feat_strings

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_replace_feat_strings


---

## UF_MODL_replace_features

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_replace_features


---

## UF_MODL_replace_features_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_replace_features_t.html


---

## UF_MODL_replace_sweep_strings

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_replace_sweep_strings


---

## UF_MODL_require_udf_mapping_for_edit

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_require_udf_mapping_for_edit


---

## UF_MODL_require_udf_mapping_for_insert

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_require_udf_mapping_for_insert


---

## UF_MODL_reverse_datum_axis

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_reverse_datum_axis


---

## UF_MODL_reverse_datum_plane

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_reverse_datum_plane


---

## UF_MODL_reverse_dir_ref

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_reverse_dir_ref


---

## UF_MODL_ripedge_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_ripedge_data_s.html


---

## UF_MODL_rough_offset_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_rough_offset_s.html


---

## UF_MODL_rpo_f_p_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/callback.html#UF_MODL_rpo_f_p_t


---

## UF_MODL_secsrf_cre_method

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_secsrf_cre_method


---

## UF_MODL_secsrf_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_secsrf_data_s.html


---

## UF_MODL_secsrf_param_data_values_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_secsrf_param_data_values_s.html


---

## UF_MODL_secsrf_param_method

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_secsrf_param_method


---

## UF_MODL_secsrf_param_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_secsrf_param_s.html


---

## UF_MODL_self_refit_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_self_refit_data_s.html


---

## UF_MODL_set_angle_tolerance_of_part

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_angle_tolerance_of_part


---

## UF_MODL_set_body_density

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_body_density


---

## UF_MODL_set_body_type_pref

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_body_type_pref


---

## UF_MODL_set_bsurf_knot_display

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_bsurf_knot_display


---

## UF_MODL_set_bsurf_pole_display

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_bsurf_pole_display


---

## UF_MODL_set_containment

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_containment


---

## UF_MODL_set_current_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_current_feature


---

## UF_MODL_set_curve_fit_method

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_curve_fit_method


---

## UF_MODL_set_datum_csys_scaling

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_datum_csys_scaling


---

## UF_MODL_set_datum_csys_visibility

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_datum_csys_visibility


---

## UF_MODL_set_default_density

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_default_density


---

## UF_MODL_set_distance_tolerance_of_part

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_distance_tolerance_of_part


---

## UF_MODL_set_dynamic_update

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_dynamic_update


---

## UF_MODL_set_face_blend_law_radii

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_face_blend_law_radii


---

## UF_MODL_set_face_blend_law_range1_radii

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_face_blend_law_range1_radii


---

## UF_MODL_set_face_blend_law_range2_radii

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_face_blend_law_range2_radii


---

## UF_MODL_set_feat_tolerance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_feat_tolerance


---

## UF_MODL_set_flange_proc_factor

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_flange_proc_factor


---

## UF_MODL_set_free_form_result

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_free_form_result


---

## UF_MODL_set_immediate_children

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_immediate_children


---

## UF_MODL_set_midsrf_feature_create_method

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_midsrf_feature_create_method


---

## UF_MODL_set_rpo_refernce

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_rpo_refernce


---

## UF_MODL_set_show_report_reference

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_show_report_reference


---

## UF_MODL_set_suppress_exp_tag

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_suppress_exp_tag


---

## UF_MODL_set_sweep_axis

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_sweep_axis


---

## UF_MODL_set_sweep_tolerances

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_sweep_tolerances


---

## UF_MODL_set_udf_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_udf_parms


---

## UF_MODL_set_update_fail_option

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_update_fail_option


---

## UF_MODL_set_xform_tag_of_datum_csys

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_set_xform_tag_of_datum_csys


---

## UF_MODL_sflange_continuity_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_sflange_continuity_e


---

## UF_MODL_sflange_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_sflange_data_s.html


---

## UF_MODL_sflange_dir_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_sflange_dir_e


---

## UF_MODL_sflange_trim_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_sflange_trim_e


---

## UF_MODL_sflange_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_sflange_type_e


---

## UF_MODL_shape_pattern_client_dialog_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_shape_pattern_client_dialog_data_s.html


---

## UF_MODL_shape_pattern_create_dialog

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_shape_pattern_create_dialog


---

## UF_MODL_shape_pattern_free_client_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_shape_pattern_free_client_data


---

## UF_MODL_shape_pattern_init_client_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_shape_pattern_init_client_data


---

## UF_MODL_show_parent_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_show_parent_curves


---

## UF_MODL_simpl_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_simpl_data_s.html


---

## UF_MODL_single_outline_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_single_outline_s.html


---

## UF_MODL_slot_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_slot_type_e


---

## UF_MODL_smbend_angle_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_smbend_angle_e


---

## UF_MODL_smbend_corner_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_smbend_corner_data_s.html


---

## UF_MODL_smbend_curve_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_smbend_curve_e


---

## UF_MODL_smbend_cylinder_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_smbend_cylinder_data_s.html


---

## UF_MODL_smbend_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_smbend_data_s.html


---

## UF_MODL_smbend_direction_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_smbend_direction_e


---

## UF_MODL_smbend_radius_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_smbend_radius_e


---

## UF_MODL_smbend_stat_side_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_smbend_stat_side_e


---

## UF_MODL_smbracket_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_smbracket_data_s.html


---

## UF_MODL_smcorner_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_smcorner_data_s.html


---

## UF_MODL_smcorner_type_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_smcorner_type_t


---

## UF_MODL_smcutout_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_smcutout_data_s.html


---

## UF_MODL_smcutout_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_smcutout_type_e


---

## UF_MODL_smhole_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_smhole_data_s.html


---

## UF_MODL_smhole_direction_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_smhole_direction_type_e


---

## UF_MODL_smhole_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_smhole_type_e


---

## UF_MODL_smjoggle_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_smjoggle_data_s.html


---

## UF_MODL_smooth_bsurface_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_smooth_bsurface_data


---

## UF_MODL_smpunch_cut_sets_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_smpunch_cut_sets_s.html


---

## UF_MODL_smpunch_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_smpunch_data_s.html


---

## UF_MODL_smpunch_top_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_smpunch_top_type_e


---

## UF_MODL_smrelief_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_smrelief_data_s.html


---

## UF_MODL_smslot_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_smslot_data_s.html


---

## UF_MODL_smslot_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_smslot_type_e


---

## UF_MODL_smspunch_type_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_smspunch_type_t


---

## UF_MODL_snipsrf_feature_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_snipsrf_feature_data_s.html


---

## UF_MODL_snipsurf_boundary_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_snipsurf_boundary_type_e


---

## UF_MODL_snipsurf_refit_method_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_snipsurf_refit_method_e


---

## UF_MODL_solid_punch_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_solid_punch_data_s.html


---

## UF_MODL_sort_features

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_sort_features


---

## UF_MODL_spherical_corner_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_spherical_corner_s.html


---

## UF_MODL_split_body

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_split_body


---

## UF_MODL_split_body_retain_tool

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_split_body_retain_tool


---

## UF_MODL_state_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_state_e


---

## UF_MODL_state_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_state_info_s.html


---

## UF_MODL_stycorner_crv_opt_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_stycorner_crv_opt_s.html


---

## UF_MODL_stycorner_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_stycorner_data_s.html


---

## UF_MODL_styled_sweep_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_styled_sweep_data_s.html


---

## UF_MODL_styled_sweep_move_string_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_styled_sweep_move_string_e


---

## UF_MODL_subtract_bodies

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_subtract_bodies


---

## UF_MODL_subtract_bodies_with_retained_options

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_subtract_bodies_with_retained_options


---

## UF_MODL_suppress_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_suppress_feature


---

## UF_MODL_symb_thread_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_symb_thread_data_s.html


---

## UF_MODL_taper_relative_to_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_taper_relative_to_e


---

## UF_MODL_trace_a_ray

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_trace_a_ray


---

## UF_MODL_transf_aa_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_transf_aa_s.html


---

## UF_MODL_transf_angle_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_transf_angle_s.html


---

## UF_MODL_transf_dist_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_transf_dist_s.html


---

## UF_MODL_transf_pp_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_transf_pp_s.html


---

## UF_MODL_transform_type_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_transform_type_t


---

## UF_MODL_trim_blend_options

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_trim_blend_options


---

## UF_MODL_trim_body

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_trim_body


---

## UF_MODL_trim_midsrf_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_trim_midsrf_feature


---

## UF_MODL_trim_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_trim_object.html


---

## UF_MODL_trim_sheet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_trim_sheet


---

## UF_MODL_udf_default_edit_mapping_tool

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_udf_default_edit_mapping_tool


---

## UF_MODL_udf_default_insert_mapping_tool

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_udf_default_insert_mapping_tool


---

## UF_MODL_udf_exp_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_udf_exp_data_s.html


---

## UF_MODL_udf_free_exp_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_udf_free_exp_data


---

## UF_MODL_udf_free_mapping_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_udf_free_mapping_data


---

## UF_MODL_udf_free_ref_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_udf_free_ref_data


---

## UF_MODL_udf_init_exp_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_udf_init_exp_data


---

## UF_MODL_udf_init_insert_data_from_def

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_udf_init_insert_data_from_def


---

## UF_MODL_udf_init_mapping_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_udf_init_mapping_data


---

## UF_MODL_udf_init_ref_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_udf_init_ref_data


---

## UF_MODL_udf_mapping_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_udf_mapping_data_s.html


---

## UF_MODL_udf_mapping_data_union

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_udf_mapping_data_union.html


---

## UF_MODL_udf_mapping_f_p_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/callback.html#UF_MODL_udf_mapping_f_p_t


---

## UF_MODL_udf_ref_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_udf_ref_data_s.html


---

## UF_MODL_udf_reverse_dir_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_udf_reverse_dir_e


---

## UF_MODL_udf_rpo_menu

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_udf_rpo_menu


---

## UF_MODL_udfs_ask_def_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_udfs_ask_def_data


---

## UF_MODL_udfs_create_def

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_udfs_create_def


---

## UF_MODL_udfs_def_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_udfs_def_data_s.html


---

## UF_MODL_udfs_exp_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_udfs_exp_s.html


---

## UF_MODL_udfs_redefine_def

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_udfs_redefine_def


---

## UF_MODL_unclock_instance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_unclock_instance


---

## UF_MODL_unclock_iset

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_unclock_iset


---

## UF_MODL_unform_features

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_unform_features


---

## UF_MODL_unite_bodies

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_unite_bodies


---

## UF_MODL_unite_bodies_with_retained_options

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_unite_bodies_with_retained_options


---

## UF_MODL_unregister_cliff_blend

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_unregister_cliff_blend


---

## UF_MODL_unregister_rpo_routine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_unregister_rpo_routine


---

## UF_MODL_unregister_udf_mapping_routine

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_unregister_udf_mapping_routine


---

## UF_MODL_unregister_var_blend

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_unregister_var_blend


---

## UF_MODL_unset_containment

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_unset_containment


---

## UF_MODL_unset_suppress_exp_tag

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_unset_suppress_exp_tag


---

## UF_MODL_unsuppress_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_unsuppress_feature


---

## UF_MODL_update

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_update


---

## UF_MODL_update_all_features

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_update_all_features


---

## UF_MODL_update_for_animation

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_update_for_animation


---

## UF_MODL_update_option_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_update_option_e


---

## UF_MODL_validate_body

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/global.html#UF_MODL_validate_body


---

## UF_MODL_var_blend_f_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/callback.html#UF_MODL_var_blend_f_t


---

## UF_MODL_vector_axis_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_vector_axis_s.html


---

## UF_MODL_vector_defined_by_union

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_vector_defined_by_union.html


---

## UF_MODL_vector_direction_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_vector_direction_s.html


---

## UF_MODL_vector_face_normal_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_vector_face_normal_s.html


---

## UF_MODL_vector_plane_of_curves_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_vector_plane_of_curves_s.html


---

## UF_MODL_vector_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_vector_s.html


---

## UF_MODL_vector_two_points_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_vector_two_points_s.html


---

## UF_MODL_vector_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/types.html#UF_MODL_vector_type_e


---

## UF_MODL_wrap_assem_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_wrap_assem_s.html


---

## UF_MODL_wrap_geom_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/UF_MODL_wrap_geom_s.html


---

## uf_modl.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl


---

## uf_modl_blends.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_blends


---

## uf_modl_bsurf.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_bsurf


---

## uf_modl_curves.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_curves


---

## uf_modl_datum_features.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_datum_features


---

## uf_modl_dfo.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_dfo


---

## uf_modl_dieeng.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_dieeng


---

## uf_modl_error.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_error


---

## uf_modl_expressions.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_expressions


---

## uf_modl_form_features.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_form_features


---

## uf_modl_freeform.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_freeform


---

## uf_modl_grooves.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_grooves


---

## uf_modl_holes.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_holes


---

## uf_modl_hollow.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_hollow


---

## uf_modl_import_body.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_import_body


---

## uf_modl_isets.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_isets


---

## uf_modl_legacy.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_legacy


---

## uf_modl_mswp.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_mswp


---

## uf_modl_mswp_types.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_mswp_types


---

## uf_modl_pads.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_pads


---

## uf_modl_pockets.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_pockets


---

## uf_modl_primitives.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_primitives


---

## uf_modl_promotions.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_promotions


---

## uf_modl_simplify.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_simplify


---

## uf_modl_sketch.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_sketch


---

## uf_modl_slots.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_slots


---

## uf_modl_smd.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_smd


---

## uf_modl_sweep.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_sweep


---

## uf_modl_taper.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_taper


---

## uf_modl_trex.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_trex


---

## uf_modl_types.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_types


---

## uf_modl_udf.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_udf


---

## uf_modl_ugopenint.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_ugopenint


---

## uf_modl_utilities.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_utilities


---

## uf_modl_vdac.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_modl/intro.html#uf_modl_vdac


---
