# UF_GDT 函数参考

> 共 331 个函数

---

## 目录

- [UF_GDT #Defines](#uf_gdt #defines)
- [UF_GDT Enumerations](#uf_gdt enumerations)
- [UF_GDT Files](#uf_gdt files)
- [UF_GDT Functions](#uf_gdt functions)
- [UF_GDT Structures](#uf_gdt structures)
- [UF_GDT_END_OF_TABLE](#uf_gdt_end_of_table)
- [UF_GDT_ERROR_BASE](#uf_gdt_error_base)
- [UF_GDT_ERROR_RANGE](#uf_gdt_error_range)
- [UF_GDT_ERR_BAD_ANNOTATION](#uf_gdt_err_bad_annotation)
- [UF_GDT_ERR_BAD_CHARACTERISTIC](#uf_gdt_err_bad_characteristic)
- [UF_GDT_ERR_BAD_COUNT](#uf_gdt_err_bad_count)
- [UF_GDT_ERR_BAD_DATUM_PREC](#uf_gdt_err_bad_datum_prec)
- [UF_GDT_ERR_BAD_EDGE](#uf_gdt_err_bad_edge)
- [UF_GDT_ERR_BAD_ENUM](#uf_gdt_err_bad_enum)
- [UF_GDT_ERR_BAD_FACE_IN_LIST](#uf_gdt_err_bad_face_in_list)
- [UF_GDT_ERR_BAD_FEATURE_TYPE](#uf_gdt_err_bad_feature_type)
- [UF_GDT_ERR_BAD_FRAME_MOD](#uf_gdt_err_bad_frame_mod)
- [UF_GDT_ERR_BAD_MAT_MODIFIER](#uf_gdt_err_bad_mat_modifier)
- [UF_GDT_ERR_BAD_PATTERN_TYPE](#uf_gdt_err_bad_pattern_type)
- [UF_GDT_ERR_BAD_PRECEDENCE_TYPE](#uf_gdt_err_bad_precedence_type)
- [UF_GDT_ERR_BAD_SIZE_VALUE_TYPE](#uf_gdt_err_bad_size_value_type)
- [UF_GDT_ERR_BAD_STANDARD](#uf_gdt_err_bad_standard)
- [UF_GDT_ERR_BAD_TOLERANCE_TYPE](#uf_gdt_err_bad_tolerance_type)
- [UF_GDT_ERR_BAD_TOL_FORMAT](#uf_gdt_err_bad_tol_format)
- [UF_GDT_ERR_BAD_ZONE_SHAPE](#uf_gdt_err_bad_zone_shape)
- [UF_GDT_ERR_DATUM_EXISTS](#uf_gdt_err_datum_exists)
- [UF_GDT_ERR_DELETED_DATUM](#uf_gdt_err_deleted_datum)
- [UF_GDT_ERR_DWG_DISPLAYED](#uf_gdt_err_dwg_displayed)
- [UF_GDT_ERR_FACE_MAP_MISMATCH](#uf_gdt_err_face_map_mismatch)
- [UF_GDT_ERR_FEATURE_NOT_DATUM](#uf_gdt_err_feature_not_datum)
- [UF_GDT_ERR_FEATURE_NOT_PULLED](#uf_gdt_err_feature_not_pulled)
- [UF_GDT_ERR_FEAT_NOT_VALID](#uf_gdt_err_feat_not_valid)
- [UF_GDT_ERR_INCH_PART_WITH_ISO_STANDARD](#uf_gdt_err_inch_part_with_iso_standard)
- [UF_GDT_ERR_INVALID_ASSOC_TYPE](#uf_gdt_err_invalid_assoc_type)
- [UF_GDT_ERR_INVALID_FACES_FOR_EDIT](#uf_gdt_err_invalid_faces_for_edit)
- [UF_GDT_ERR_INVALID_FACE_MAP](#uf_gdt_err_invalid_face_map)
- [UF_GDT_ERR_INVALID_FEAT_TYPE_FOR_THREAD_TOL](#uf_gdt_err_invalid_feat_type_for_thread_tol)
- [UF_GDT_ERR_INVALID_INSTANCE](#uf_gdt_err_invalid_instance)
- [UF_GDT_ERR_INVALID_KEYWORD](#uf_gdt_err_invalid_keyword)
- [UF_GDT_ERR_INVALID_LIM_FITS_DATA](#uf_gdt_err_invalid_lim_fits_data)
- [UF_GDT_ERR_INVALID_MODL_DATA](#uf_gdt_err_invalid_modl_data)
- [UF_GDT_ERR_INVALID_MODL_FEATURE_TYPE](#uf_gdt_err_invalid_modl_feature_type)
- [UF_GDT_ERR_INVALID_MODL_PARAM](#uf_gdt_err_invalid_modl_param)
- [UF_GDT_ERR_INVALID_PATTERN_QUERIED](#uf_gdt_err_invalid_pattern_queried)
- [UF_GDT_ERR_INVALID_PRODUCT_ATT_NUM_FOR_SPLINE_GEAR](#uf_gdt_err_invalid_product_att_num_for_spline_gear)
- [UF_GDT_ERR_INVALID_PROFILE_TOL](#uf_gdt_err_invalid_profile_tol)
- [UF_GDT_ERR_INVALID_PROFILE_ZON](#uf_gdt_err_invalid_profile_zon)
- [UF_GDT_ERR_INVALID_REGION_BODIES](#uf_gdt_err_invalid_region_bodies)
- [UF_GDT_ERR_INVALID_THREAD_TOL](#uf_gdt_err_invalid_thread_tol)
- [UF_GDT_ERR_INVALID_VIEW](#uf_gdt_err_invalid_view)
- [UF_GDT_ERR_MODL_FEATURES_NOT_FULLY_LOADED](#uf_gdt_err_modl_features_not_fully_loaded)
- [UF_GDT_ERR_MODL_FEATURE_NULL_TAG](#uf_gdt_err_modl_feature_null_tag)
- [UF_GDT_ERR_MODL_PARAM_MISMATCH](#uf_gdt_err_modl_param_mismatch)
- [UF_GDT_ERR_NON_POSITIVE_PARAMETERS](#uf_gdt_err_non_positive_parameters)
- [UF_GDT_ERR_NOT_BASE](#uf_gdt_err_not_base)
- [UF_GDT_ERR_NOT_COMPLEX_SUB_FEAT](#uf_gdt_err_not_complex_sub_feat)
- [UF_GDT_ERR_NOT_COMPLEX_TOL_FEAT](#uf_gdt_err_not_complex_tol_feat)
- [UF_GDT_ERR_NOT_DATUM](#uf_gdt_err_not_datum)
- [UF_GDT_ERR_NOT_DATUM_INSTANCE](#uf_gdt_err_not_datum_instance)
- [UF_GDT_ERR_NOT_FCF](#uf_gdt_err_not_fcf)
- [UF_GDT_ERR_NOT_FEATURE_INSTANCE](#uf_gdt_err_not_feature_instance)
- [UF_GDT_ERR_NOT_IDENT_DATUM](#uf_gdt_err_not_ident_datum)
- [UF_GDT_ERR_NOT_INSTANCE](#uf_gdt_err_not_instance)
- [UF_GDT_ERR_NOT_MULTIPLE_DATUM](#uf_gdt_err_not_multiple_datum)
- [UF_GDT_ERR_NOT_PROFILE_FCF](#uf_gdt_err_not_profile_fcf)
- [UF_GDT_ERR_NOT_PULLED_SUBTOLERANCE](#uf_gdt_err_not_pulled_subtolerance)
- [UF_GDT_ERR_NOT_SUBTOLERANCE_TYPE](#uf_gdt_err_not_subtolerance_type)
- [UF_GDT_ERR_NOT_TOL_FEAT](#uf_gdt_err_not_tol_feat)
- [UF_GDT_ERR_NOT_VALID_DATA_FOR_PART_UNIT](#uf_gdt_err_not_valid_data_for_part_unit)
- [UF_GDT_ERR_NOT_VALID_FEAT_TYPE_FOR_LIM_FITS](#uf_gdt_err_not_valid_feat_type_for_lim_fits)
- [UF_GDT_ERR_NOT_VALID_FEAT_TYPE_FOR_LIM_FITS_ENGLISH](#uf_gdt_err_not_valid_feat_type_for_lim_fits_english)
- [UF_GDT_ERR_NOT_WALL_THICKNESS](#uf_gdt_err_not_wall_thickness)
- [UF_GDT_ERR_NO_ADD_PROFILE_LDR](#uf_gdt_err_no_add_profile_ldr)
- [UF_GDT_ERR_NO_ADD_TO_INSTANCE](#uf_gdt_err_no_add_to_instance)
- [UF_GDT_ERR_NO_DIRECTED_DIM](#uf_gdt_err_no_directed_dim)
- [UF_GDT_ERR_NO_INDEXED_LEADER](#uf_gdt_err_no_indexed_leader)
- [UF_GDT_ERR_NO_LIMITS_AND_FITS_TOLERANCE](#uf_gdt_err_no_limits_and_fits_tolerance)
- [UF_GDT_ERR_NO_REMOVE_ONLY_LDR](#uf_gdt_err_no_remove_only_ldr)
- [UF_GDT_ERR_NO_SIZE_DATA_ON_FEATURE](#uf_gdt_err_no_size_data_on_feature)
- [UF_GDT_ERR_NO_TOLERANCE_WITH_INDEX](#uf_gdt_err_no_tolerance_with_index)
- [UF_GDT_ERR_NULL_LABEL](#uf_gdt_err_null_label)
- [UF_GDT_ERR_SIZE_TOL_EXISTS](#uf_gdt_err_size_tol_exists)
- [UF_GDT_ERR_TEST_FAILURE](#uf_gdt_err_test_failure)
- [UF_GDT_ERR_TOL_VALIDATION_FAILED](#uf_gdt_err_tol_validation_failed)
- [UF_GDT_ERR_TOO_MANY_FRAMES](#uf_gdt_err_too_many_frames)
- [UF_GDT_ERR_UB_INTERROGATE](#uf_gdt_err_ub_interrogate)
- [UF_GDT_ERR_UB_IS_NULL](#uf_gdt_err_ub_is_null)
- [UF_GDT_ERR_UB_NOT_ALLOWED](#uf_gdt_err_ub_not_allowed)
- [UF_GDT_ERR_UNVAILABLE_DATA_FOR_CURRENT_SETTING](#uf_gdt_err_unvailable_data_for_current_setting)
- [UF_GDT_ERR_UPDATE_PENDING](#uf_gdt_err_update_pending)
- [UF_GDT_MAX_NAME_LEN](#uf_gdt_max_name_len)
- [UF_GDT_NO_ERRORS](#uf_gdt_no_errors)
- [UF_GDT_SEPERATE_GAGE](#uf_gdt_seperate_gage)
- [UF_GDT_WARNING](#uf_gdt_warning)
- [UF_GDT__MAX_KEYWORD](#uf_gdt__max_keyword)
- [UF_GDT__MIN_KEYWORD](#uf_gdt__min_keyword)
- [UF_GDT_add_datum_identifier](#uf_gdt_add_datum_identifier)
- [UF_GDT_add_datum_to_feature](#uf_gdt_add_datum_to_feature)
- [UF_GDT_add_fcf](#uf_gdt_add_fcf)
- [UF_GDT_add_leader](#uf_gdt_add_leader)
- [UF_GDT_add_size_tolerance](#uf_gdt_add_size_tolerance)
- [UF_GDT_annotation_tags_s](#uf_gdt_annotation_tags_s)
- [UF_GDT_ask_annotation_tags](#uf_gdt_ask_annotation_tags)
- [UF_GDT_ask_appended_text](#uf_gdt_ask_appended_text)
- [UF_GDT_ask_associated_datums](#uf_gdt_ask_associated_datums)
- [UF_GDT_ask_association_type](#uf_gdt_ask_association_type)
- [UF_GDT_ask_callout_strings](#uf_gdt_ask_callout_strings)
- [UF_GDT_ask_characteristic](#uf_gdt_ask_characteristic)
- [UF_GDT_ask_complex_feature](#uf_gdt_ask_complex_feature)
- [UF_GDT_ask_complex_sub_features](#uf_gdt_ask_complex_sub_features)
- [UF_GDT_ask_component_tolerance_index](#uf_gdt_ask_component_tolerance_index)
- [UF_GDT_ask_composite_drf](#uf_gdt_ask_composite_drf)
- [UF_GDT_ask_datum_by_label](#uf_gdt_ask_datum_by_label)
- [UF_GDT_ask_datum_ident_parms](#uf_gdt_ask_datum_ident_parms)
- [UF_GDT_ask_datum_keywords](#uf_gdt_ask_datum_keywords)
- [UF_GDT_ask_datum_multiple_parms](#uf_gdt_ask_datum_multiple_parms)
- [UF_GDT_ask_datum_of_label](#uf_gdt_ask_datum_of_label)
- [UF_GDT_ask_datum_of_target](#uf_gdt_ask_datum_of_target)
- [UF_GDT_ask_datum_referencers](#uf_gdt_ask_datum_referencers)
- [UF_GDT_ask_datum_references](#uf_gdt_ask_datum_references)
- [UF_GDT_ask_datums_of_feature](#uf_gdt_ask_datums_of_feature)
- [UF_GDT_ask_depth_tolerance_parms](#uf_gdt_ask_depth_tolerance_parms)
- [UF_GDT_ask_description](#uf_gdt_ask_description)
- [UF_GDT_ask_directed_dimension](#uf_gdt_ask_directed_dimension)
- [UF_GDT_ask_directed_dimension1](#uf_gdt_ask_directed_dimension1)
- [UF_GDT_ask_drf](#uf_gdt_ask_drf)
- [UF_GDT_ask_face_from_index](#uf_gdt_ask_face_from_index)
- [UF_GDT_ask_face_index](#uf_gdt_ask_face_index)
- [UF_GDT_ask_face_index_string](#uf_gdt_ask_face_index_string)
- [UF_GDT_ask_faces](#uf_gdt_ask_faces)
- [UF_GDT_ask_fcf_drf](#uf_gdt_ask_fcf_drf)
- [UF_GDT_ask_fcf_parms](#uf_gdt_ask_fcf_parms)
- [UF_GDT_ask_fcf_tags](#uf_gdt_ask_fcf_tags)
- [UF_GDT_ask_feature_of_datum](#uf_gdt_ask_feature_of_datum)
- [UF_GDT_ask_feature_parms](#uf_gdt_ask_feature_parms)
- [UF_GDT_ask_feature_type](#uf_gdt_ask_feature_type)
- [UF_GDT_ask_features_of_face](#uf_gdt_ask_features_of_face)
- [UF_GDT_ask_gdt_object_dfa_file](#uf_gdt_ask_gdt_object_dfa_file)
- [UF_GDT_ask_gdt_view_matrix](#uf_gdt_ask_gdt_view_matrix)
- [UF_GDT_ask_geometric_definition](#uf_gdt_ask_geometric_definition)
- [UF_GDT_ask_index_display](#uf_gdt_ask_index_display)
- [UF_GDT_ask_instance_display_information](#uf_gdt_ask_instance_display_information)
- [UF_GDT_ask_keyword_name](#uf_gdt_ask_keyword_name)
- [UF_GDT_ask_keyword_text](#uf_gdt_ask_keyword_text)
- [UF_GDT_ask_label_of_datum](#uf_gdt_ask_label_of_datum)
- [UF_GDT_ask_leader](#uf_gdt_ask_leader)
- [UF_GDT_ask_limits_and_fits_tolerance_parms](#uf_gdt_ask_limits_and_fits_tolerance_parms)
- [UF_GDT_ask_linked_features](#uf_gdt_ask_linked_features)
- [UF_GDT_ask_load_component_flag](#uf_gdt_ask_load_component_flag)
- [UF_GDT_ask_major_dia_feature_of_spline_gear](#uf_gdt_ask_major_dia_feature_of_spline_gear)
- [UF_GDT_ask_minor_dia_feature_of_spline_gear](#uf_gdt_ask_minor_dia_feature_of_spline_gear)
- [UF_GDT_ask_modl_data](#uf_gdt_ask_modl_data)
- [UF_GDT_ask_modl_features](#uf_gdt_ask_modl_features)
- [UF_GDT_ask_non_feature_edge_selection](#uf_gdt_ask_non_feature_edge_selection)
- [UF_GDT_ask_num_leaders](#uf_gdt_ask_num_leaders)
- [UF_GDT_ask_pitch_dia_feature_of_spline_gear](#uf_gdt_ask_pitch_dia_feature_of_spline_gear)
- [UF_GDT_ask_product_attributes](#uf_gdt_ask_product_attributes)
- [UF_GDT_ask_profile_tol_data](#uf_gdt_ask_profile_tol_data)
- [UF_GDT_ask_pulled_tolerance_component](#uf_gdt_ask_pulled_tolerance_component)
- [UF_GDT_ask_size_tolerance_parms](#uf_gdt_ask_size_tolerance_parms)
- [UF_GDT_ask_size_tolerance_tag](#uf_gdt_ask_size_tolerance_tag)
- [UF_GDT_ask_sub_features](#uf_gdt_ask_sub_features)
- [UF_GDT_ask_super_feature](#uf_gdt_ask_super_feature)
- [UF_GDT_ask_table_of_instance](#uf_gdt_ask_table_of_instance)
- [UF_GDT_ask_tags](#uf_gdt_ask_tags)
- [UF_GDT_ask_target_area_xhatch](#uf_gdt_ask_target_area_xhatch)
- [UF_GDT_ask_target_cyl_parms](#uf_gdt_ask_target_cyl_parms)
- [UF_GDT_ask_target_dia_parms](#uf_gdt_ask_target_dia_parms)
- [UF_GDT_ask_target_line_parms](#uf_gdt_ask_target_line_parms)
- [UF_GDT_ask_target_point_parms](#uf_gdt_ask_target_point_parms)
- [UF_GDT_ask_target_rect_parms](#uf_gdt_ask_target_rect_parms)
- [UF_GDT_ask_target_udef_parms](#uf_gdt_ask_target_udef_parms)
- [UF_GDT_ask_targets_of_datum](#uf_gdt_ask_targets_of_datum)
- [UF_GDT_ask_thread_tolerance_parms](#uf_gdt_ask_thread_tolerance_parms)
- [UF_GDT_ask_tol_feat_instance](#uf_gdt_ask_tol_feat_instance)
- [UF_GDT_ask_tol_feat_of_instance](#uf_gdt_ask_tol_feat_of_instance)
- [UF_GDT_ask_tol_feat_tag](#uf_gdt_ask_tol_feat_tag)
- [UF_GDT_ask_tolerance](#uf_gdt_ask_tolerance)
- [UF_GDT_ask_tolerance_from_index](#uf_gdt_ask_tolerance_from_index)
- [UF_GDT_ask_tolerance_index](#uf_gdt_ask_tolerance_index)
- [UF_GDT_ask_tolerance_index_string](#uf_gdt_ask_tolerance_index_string)
- [UF_GDT_ask_tolerance_types](#uf_gdt_ask_tolerance_types)
- [UF_GDT_ask_tolerance_zone](#uf_gdt_ask_tolerance_zone)
- [UF_GDT_ask_tolerances](#uf_gdt_ask_tolerances)
- [UF_GDT_ask_tolerancing_standard](#uf_gdt_ask_tolerancing_standard)
- [UF_GDT_ask_unit_basis](#uf_gdt_ask_unit_basis)
- [UF_GDT_ask_wall_thickness_parms](#uf_gdt_ask_wall_thickness_parms)
- [UF_GDT_break_relationship](#uf_gdt_break_relationship)
- [UF_GDT_callout_string_s](#uf_gdt_callout_string_s)
- [UF_GDT_characteristic_e](#uf_gdt_characteristic_e)
- [UF_GDT_create_datum_identifier](#uf_gdt_create_datum_identifier)
- [UF_GDT_create_datum_multiple](#uf_gdt_create_datum_multiple)
- [UF_GDT_create_drf](#uf_gdt_create_drf)
- [UF_GDT_create_fcf](#uf_gdt_create_fcf)
- [UF_GDT_create_feature_with_product_att](#uf_gdt_create_feature_with_product_att)
- [UF_GDT_create_instance](#uf_gdt_create_instance)
- [UF_GDT_create_modl_based_feature](#uf_gdt_create_modl_based_feature)
- [UF_GDT_create_size_tolerance](#uf_gdt_create_size_tolerance)
- [UF_GDT_create_table_instance](#uf_gdt_create_table_instance)
- [UF_GDT_create_target_cyl_area](#uf_gdt_create_target_cyl_area)
- [UF_GDT_create_target_dia_area](#uf_gdt_create_target_dia_area)
- [UF_GDT_create_target_line](#uf_gdt_create_target_line)
- [UF_GDT_create_target_point](#uf_gdt_create_target_point)
- [UF_GDT_create_target_rect_area](#uf_gdt_create_target_rect_area)
- [UF_GDT_create_target_udef_area](#uf_gdt_create_target_udef_area)
- [UF_GDT_create_wall_thickness](#uf_gdt_create_wall_thickness)
- [UF_GDT_data_frame_s](#uf_gdt_data_frame_s)
- [UF_GDT_data_type_e](#uf_gdt_data_type_e)
- [UF_GDT_datum_assoc_type_e](#uf_gdt_datum_assoc_type_e)
- [UF_GDT_datum_identifier_s](#uf_gdt_datum_identifier_s)
- [UF_GDT_datum_reference_s](#uf_gdt_datum_reference_s)
- [UF_GDT_datum_target_line_s](#uf_gdt_datum_target_line_s)
- [UF_GDT_datum_target_point_s](#uf_gdt_datum_target_point_s)
- [UF_GDT_default_gage_type_e](#uf_gdt_default_gage_type_e)
- [UF_GDT_depth_tolerance_s](#uf_gdt_depth_tolerance_s)
- [UF_GDT_description_s](#uf_gdt_description_s)
- [UF_GDT_directed_dimension1_s](#uf_gdt_directed_dimension1_s)
- [UF_GDT_directed_dimension_s](#uf_gdt_directed_dimension_s)
- [UF_GDT_directed_dimension_type_e](#uf_gdt_directed_dimension_type_e)
- [UF_GDT_drf_data_s](#uf_gdt_drf_data_s)
- [UF_GDT_drf_reference_s](#uf_gdt_drf_reference_s)
- [UF_GDT_edge_select_type_e](#uf_gdt_edge_select_type_e)
- [UF_GDT_export_drawings](#uf_gdt_export_drawings)
- [UF_GDT_fcf_s](#uf_gdt_fcf_s)
- [UF_GDT_feature_parms_s](#uf_gdt_feature_parms_s)
- [UF_GDT_feature_type_e](#uf_gdt_feature_type_e)
- [UF_GDT_free](#uf_gdt_free)
- [UF_GDT_geometric_definition_s](#uf_gdt_geometric_definition_s)
- [UF_GDT_geometric_definition_type_e](#uf_gdt_geometric_definition_type_e)
- [UF_GDT_has_depth_tolerance](#uf_gdt_has_depth_tolerance)
- [UF_GDT_has_directed_dimension](#uf_gdt_has_directed_dimension)
- [UF_GDT_has_geometric_definition](#uf_gdt_has_geometric_definition)
- [UF_GDT_has_limits_and_fits_tolerance](#uf_gdt_has_limits_and_fits_tolerance)
- [UF_GDT_has_size_tolerance](#uf_gdt_has_size_tolerance)
- [UF_GDT_has_wall_thickness](#uf_gdt_has_wall_thickness)
- [UF_GDT_index_display_type_e](#uf_gdt_index_display_type_e)
- [UF_GDT_inherit_model_gdt_to_drawing](#uf_gdt_inherit_model_gdt_to_drawing)
- [UF_GDT_init](#uf_gdt_init)
- [UF_GDT_is_complex_feature](#uf_gdt_is_complex_feature)
- [UF_GDT_is_complex_sub_feature](#uf_gdt_is_complex_sub_feature)
- [UF_GDT_is_composite_tolerance](#uf_gdt_is_composite_tolerance)
- [UF_GDT_is_datum](#uf_gdt_is_datum)
- [UF_GDT_is_datum_target](#uf_gdt_is_datum_target)
- [UF_GDT_is_feature_of_size](#uf_gdt_is_feature_of_size)
- [UF_GDT_is_gdt_view](#uf_gdt_is_gdt_view)
- [UF_GDT_is_linked_feature](#uf_gdt_is_linked_feature)
- [UF_GDT_is_modl_based](#uf_gdt_is_modl_based)
- [UF_GDT_is_pulled_tolerance](#uf_gdt_is_pulled_tolerance)
- [UF_GDT_is_retained](#uf_gdt_is_retained)
- [UF_GDT_is_single_datum_reference_frame](#uf_gdt_is_single_datum_reference_frame)
- [UF_GDT_is_user_defined_keyword](#uf_gdt_is_user_defined_keyword)
- [UF_GDT_keyword_s](#uf_gdt_keyword_s)
- [UF_GDT_leader_spec_s](#uf_gdt_leader_spec_s)
- [UF_GDT_leader_type_e](#uf_gdt_leader_type_e)
- [UF_GDT_limits_and_fits_data_s](#uf_gdt_limits_and_fits_data_s)
- [UF_GDT_limits_and_fits_display_type_e](#uf_gdt_limits_and_fits_display_type_e)
- [UF_GDT_limits_and_fits_tolerance_s](#uf_gdt_limits_and_fits_tolerance_s)
- [UF_GDT_material_modifier_e](#uf_gdt_material_modifier_e)
- [UF_GDT_modifier_data_s](#uf_gdt_modifier_data_s)
- [UF_GDT_modifier_types_e](#uf_gdt_modifier_types_e)
- [UF_GDT_modl_data_s](#uf_gdt_modl_data_s)
- [UF_GDT_modl_parameter_e](#uf_gdt_modl_parameter_e)
- [UF_GDT_multiple_datum_s](#uf_gdt_multiple_datum_s)
- [UF_GDT_pattern_type_e](#uf_gdt_pattern_type_e)
- [UF_GDT_point_s](#uf_gdt_point_s)
- [UF_GDT_precedence_e](#uf_gdt_precedence_e)
- [UF_GDT_product_attribute_s](#uf_gdt_product_attribute_s)
- [UF_GDT_profile_type_e](#uf_gdt_profile_type_e)
- [UF_GDT_proj_zone_s](#uf_gdt_proj_zone_s)
- [UF_GDT_pull_tolerance](#uf_gdt_pull_tolerance)
- [UF_GDT_relation_type_e](#uf_gdt_relation_type_e)
- [UF_GDT_remove_leader](#uf_gdt_remove_leader)
- [UF_GDT_reset_callout_rules](#uf_gdt_reset_callout_rules)
- [UF_GDT_restrained_condition_e](#uf_gdt_restrained_condition_e)
- [UF_GDT_set_appended_text](#uf_gdt_set_appended_text)
- [UF_GDT_set_characteristic](#uf_gdt_set_characteristic)
- [UF_GDT_set_composite_drf](#uf_gdt_set_composite_drf)
- [UF_GDT_set_datum_identifier](#uf_gdt_set_datum_identifier)
- [UF_GDT_set_datum_keywords](#uf_gdt_set_datum_keywords)
- [UF_GDT_set_datum_label](#uf_gdt_set_datum_label)
- [UF_GDT_set_datum_multiple](#uf_gdt_set_datum_multiple)
- [UF_GDT_set_datum_references](#uf_gdt_set_datum_references)
- [UF_GDT_set_depth_tolerance_parms](#uf_gdt_set_depth_tolerance_parms)
- [UF_GDT_set_description](#uf_gdt_set_description)
- [UF_GDT_set_directed_dimension](#uf_gdt_set_directed_dimension)
- [UF_GDT_set_drf](#uf_gdt_set_drf)
- [UF_GDT_set_faces](#uf_gdt_set_faces)
- [UF_GDT_set_fcf](#uf_gdt_set_fcf)
- [UF_GDT_set_fcf_drf](#uf_gdt_set_fcf_drf)
- [UF_GDT_set_geometric_definition](#uf_gdt_set_geometric_definition)
- [UF_GDT_set_index_display](#uf_gdt_set_index_display)
- [UF_GDT_set_instance_display_information](#uf_gdt_set_instance_display_information)
- [UF_GDT_set_keyword_text](#uf_gdt_set_keyword_text)
- [UF_GDT_set_limits_and_fits_tolerance_parms](#uf_gdt_set_limits_and_fits_tolerance_parms)
- [UF_GDT_set_load_component_flag](#uf_gdt_set_load_component_flag)
- [UF_GDT_set_modl_data](#uf_gdt_set_modl_data)
- [UF_GDT_set_non_feature_edge_selection](#uf_gdt_set_non_feature_edge_selection)
- [UF_GDT_set_profile_tol_data](#uf_gdt_set_profile_tol_data)
- [UF_GDT_set_region_parameters](#uf_gdt_set_region_parameters)
- [UF_GDT_set_size_data](#uf_gdt_set_size_data)
- [UF_GDT_set_size_tolerance_parms](#uf_gdt_set_size_tolerance_parms)
- [UF_GDT_set_target_area_xhatch](#uf_gdt_set_target_area_xhatch)
- [UF_GDT_set_thread_tolerance_parms](#uf_gdt_set_thread_tolerance_parms)
- [UF_GDT_set_tolerance_zones](#uf_gdt_set_tolerance_zones)
- [UF_GDT_set_tolerancing_standard](#uf_gdt_set_tolerancing_standard)
- [UF_GDT_set_unit_basis](#uf_gdt_set_unit_basis)
- [UF_GDT_set_wall_thickness_parms](#uf_gdt_set_wall_thickness_parms)
- [UF_GDT_size_tolerance_s](#uf_gdt_size_tolerance_s)
- [UF_GDT_size_value_type_e](#uf_gdt_size_value_type_e)
- [UF_GDT_standard_e](#uf_gdt_standard_e)
- [UF_GDT_standard_keyword_id_e](#uf_gdt_standard_keyword_id_e)
- [UF_GDT_statistical_info_s](#uf_gdt_statistical_info_s)
- [UF_GDT_stub_direction_e](#uf_gdt_stub_direction_e)
- [UF_GDT_surface_parms_s](#uf_gdt_surface_parms_s)
- [UF_GDT_target_cyl_area_s](#uf_gdt_target_cyl_area_s)
- [UF_GDT_target_dia_area_s](#uf_gdt_target_dia_area_s)
- [UF_GDT_target_non_planar_data_s](#uf_gdt_target_non_planar_data_s)
- [UF_GDT_target_rect_area_s](#uf_gdt_target_rect_area_s)
- [UF_GDT_target_udef_area_s](#uf_gdt_target_udef_area_s)
- [UF_GDT_text_location_e](#uf_gdt_text_location_e)
- [UF_GDT_thread_data_s](#uf_gdt_thread_data_s)
- [UF_GDT_thread_tolerance_s](#uf_gdt_thread_tolerance_s)
- [UF_GDT_tol_format_e](#uf_gdt_tol_format_e)
- [UF_GDT_tolerance_type_e](#uf_gdt_tolerance_type_e)
- [UF_GDT_tolerance_value_s](#uf_gdt_tolerance_value_s)
- [UF_GDT_tolerance_zone_s](#uf_gdt_tolerance_zone_s)
- [UF_GDT_unit_basis_s](#uf_gdt_unit_basis_s)
- [UF_GDT_update_features](#uf_gdt_update_features)
- [UF_GDT_upgrade_legacy_feature](#uf_gdt_upgrade_legacy_feature)
- [UF_GDT_zone_shape_e](#uf_gdt_zone_shape_e)
- [uf_gdt.h](#uf_gdt.h)

---

## UF_GDT #Defines

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/contents.html#defines


---

## UF_GDT Enumerations

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/contents.html#enumerations


---

## UF_GDT Files

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/contents.html#files


---

## UF_GDT Functions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/contents.html#functions


---

## UF_GDT Structures

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/contents.html#structures


---

## UF_GDT_END_OF_TABLE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_END_OF_TABLE


---

## UF_GDT_ERROR_BASE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERROR_BASE


---

## UF_GDT_ERROR_RANGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERROR_RANGE


---

## UF_GDT_ERR_BAD_ANNOTATION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_BAD_ANNOTATION


---

## UF_GDT_ERR_BAD_CHARACTERISTIC

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_BAD_CHARACTERISTIC


---

## UF_GDT_ERR_BAD_COUNT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_BAD_COUNT


---

## UF_GDT_ERR_BAD_DATUM_PREC

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_BAD_DATUM_PREC


---

## UF_GDT_ERR_BAD_EDGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_BAD_EDGE


---

## UF_GDT_ERR_BAD_ENUM

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_BAD_ENUM


---

## UF_GDT_ERR_BAD_FACE_IN_LIST

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_BAD_FACE_IN_LIST


---

## UF_GDT_ERR_BAD_FEATURE_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_BAD_FEATURE_TYPE


---

## UF_GDT_ERR_BAD_FRAME_MOD

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_BAD_FRAME_MOD


---

## UF_GDT_ERR_BAD_MAT_MODIFIER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_BAD_MAT_MODIFIER


---

## UF_GDT_ERR_BAD_PATTERN_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_BAD_PATTERN_TYPE


---

## UF_GDT_ERR_BAD_PRECEDENCE_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_BAD_PRECEDENCE_TYPE


---

## UF_GDT_ERR_BAD_SIZE_VALUE_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_BAD_SIZE_VALUE_TYPE


---

## UF_GDT_ERR_BAD_STANDARD

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_BAD_STANDARD


---

## UF_GDT_ERR_BAD_TOLERANCE_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_BAD_TOLERANCE_TYPE


---

## UF_GDT_ERR_BAD_TOL_FORMAT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_BAD_TOL_FORMAT


---

## UF_GDT_ERR_BAD_ZONE_SHAPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_BAD_ZONE_SHAPE


---

## UF_GDT_ERR_DATUM_EXISTS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_DATUM_EXISTS


---

## UF_GDT_ERR_DELETED_DATUM

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_DELETED_DATUM


---

## UF_GDT_ERR_DWG_DISPLAYED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_DWG_DISPLAYED


---

## UF_GDT_ERR_FACE_MAP_MISMATCH

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_FACE_MAP_MISMATCH


---

## UF_GDT_ERR_FEATURE_NOT_DATUM

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_FEATURE_NOT_DATUM


---

## UF_GDT_ERR_FEATURE_NOT_PULLED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_FEATURE_NOT_PULLED


---

## UF_GDT_ERR_FEAT_NOT_VALID

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_FEAT_NOT_VALID


---

## UF_GDT_ERR_INCH_PART_WITH_ISO_STANDARD

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_INCH_PART_WITH_ISO_STANDARD


---

## UF_GDT_ERR_INVALID_ASSOC_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_INVALID_ASSOC_TYPE


---

## UF_GDT_ERR_INVALID_FACES_FOR_EDIT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_INVALID_FACES_FOR_EDIT


---

## UF_GDT_ERR_INVALID_FACE_MAP

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_INVALID_FACE_MAP


---

## UF_GDT_ERR_INVALID_FEAT_TYPE_FOR_THREAD_TOL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_INVALID_FEAT_TYPE_FOR_THREAD_TOL


---

## UF_GDT_ERR_INVALID_INSTANCE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_INVALID_INSTANCE


---

## UF_GDT_ERR_INVALID_KEYWORD

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_INVALID_KEYWORD


---

## UF_GDT_ERR_INVALID_LIM_FITS_DATA

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_INVALID_LIM_FITS_DATA


---

## UF_GDT_ERR_INVALID_MODL_DATA

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_INVALID_MODL_DATA


---

## UF_GDT_ERR_INVALID_MODL_FEATURE_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_INVALID_MODL_FEATURE_TYPE


---

## UF_GDT_ERR_INVALID_MODL_PARAM

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_INVALID_MODL_PARAM


---

## UF_GDT_ERR_INVALID_PATTERN_QUERIED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_INVALID_PATTERN_QUERIED


---

## UF_GDT_ERR_INVALID_PRODUCT_ATT_NUM_FOR_SPLINE_GEAR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_INVALID_PRODUCT_ATT_NUM_FOR_SPLINE_GEAR


---

## UF_GDT_ERR_INVALID_PROFILE_TOL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_INVALID_PROFILE_TOL


---

## UF_GDT_ERR_INVALID_PROFILE_ZON

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_INVALID_PROFILE_ZON


---

## UF_GDT_ERR_INVALID_REGION_BODIES

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_INVALID_REGION_BODIES


---

## UF_GDT_ERR_INVALID_THREAD_TOL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_INVALID_THREAD_TOL


---

## UF_GDT_ERR_INVALID_VIEW

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_INVALID_VIEW


---

## UF_GDT_ERR_MODL_FEATURES_NOT_FULLY_LOADED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_MODL_FEATURES_NOT_FULLY_LOADED


---

## UF_GDT_ERR_MODL_FEATURE_NULL_TAG

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_MODL_FEATURE_NULL_TAG


---

## UF_GDT_ERR_MODL_PARAM_MISMATCH

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_MODL_PARAM_MISMATCH


---

## UF_GDT_ERR_NON_POSITIVE_PARAMETERS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NON_POSITIVE_PARAMETERS


---

## UF_GDT_ERR_NOT_BASE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NOT_BASE


---

## UF_GDT_ERR_NOT_COMPLEX_SUB_FEAT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NOT_COMPLEX_SUB_FEAT


---

## UF_GDT_ERR_NOT_COMPLEX_TOL_FEAT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NOT_COMPLEX_TOL_FEAT


---

## UF_GDT_ERR_NOT_DATUM

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NOT_DATUM


---

## UF_GDT_ERR_NOT_DATUM_INSTANCE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NOT_DATUM_INSTANCE


---

## UF_GDT_ERR_NOT_FCF

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NOT_FCF


---

## UF_GDT_ERR_NOT_FEATURE_INSTANCE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NOT_FEATURE_INSTANCE


---

## UF_GDT_ERR_NOT_IDENT_DATUM

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NOT_IDENT_DATUM


---

## UF_GDT_ERR_NOT_INSTANCE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NOT_INSTANCE


---

## UF_GDT_ERR_NOT_MULTIPLE_DATUM

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NOT_MULTIPLE_DATUM


---

## UF_GDT_ERR_NOT_PROFILE_FCF

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NOT_PROFILE_FCF


---

## UF_GDT_ERR_NOT_PULLED_SUBTOLERANCE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NOT_PULLED_SUBTOLERANCE


---

## UF_GDT_ERR_NOT_SUBTOLERANCE_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NOT_SUBTOLERANCE_TYPE


---

## UF_GDT_ERR_NOT_TOL_FEAT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NOT_TOL_FEAT


---

## UF_GDT_ERR_NOT_VALID_DATA_FOR_PART_UNIT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NOT_VALID_DATA_FOR_PART_UNIT


---

## UF_GDT_ERR_NOT_VALID_FEAT_TYPE_FOR_LIM_FITS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NOT_VALID_FEAT_TYPE_FOR_LIM_FITS


---

## UF_GDT_ERR_NOT_VALID_FEAT_TYPE_FOR_LIM_FITS_ENGLISH

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NOT_VALID_FEAT_TYPE_FOR_LIM_FITS_ENGLISH


---

## UF_GDT_ERR_NOT_WALL_THICKNESS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NOT_WALL_THICKNESS


---

## UF_GDT_ERR_NO_ADD_PROFILE_LDR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NO_ADD_PROFILE_LDR


---

## UF_GDT_ERR_NO_ADD_TO_INSTANCE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NO_ADD_TO_INSTANCE


---

## UF_GDT_ERR_NO_DIRECTED_DIM

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NO_DIRECTED_DIM


---

## UF_GDT_ERR_NO_INDEXED_LEADER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NO_INDEXED_LEADER


---

## UF_GDT_ERR_NO_LIMITS_AND_FITS_TOLERANCE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NO_LIMITS_AND_FITS_TOLERANCE


---

## UF_GDT_ERR_NO_REMOVE_ONLY_LDR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NO_REMOVE_ONLY_LDR


---

## UF_GDT_ERR_NO_SIZE_DATA_ON_FEATURE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NO_SIZE_DATA_ON_FEATURE


---

## UF_GDT_ERR_NO_TOLERANCE_WITH_INDEX

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NO_TOLERANCE_WITH_INDEX


---

## UF_GDT_ERR_NULL_LABEL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_NULL_LABEL


---

## UF_GDT_ERR_SIZE_TOL_EXISTS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_SIZE_TOL_EXISTS


---

## UF_GDT_ERR_TEST_FAILURE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_TEST_FAILURE


---

## UF_GDT_ERR_TOL_VALIDATION_FAILED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_TOL_VALIDATION_FAILED


---

## UF_GDT_ERR_TOO_MANY_FRAMES

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_TOO_MANY_FRAMES


---

## UF_GDT_ERR_UB_INTERROGATE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_UB_INTERROGATE


---

## UF_GDT_ERR_UB_IS_NULL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_UB_IS_NULL


---

## UF_GDT_ERR_UB_NOT_ALLOWED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_UB_NOT_ALLOWED


---

## UF_GDT_ERR_UNVAILABLE_DATA_FOR_CURRENT_SETTING

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_UNVAILABLE_DATA_FOR_CURRENT_SETTING


---

## UF_GDT_ERR_UPDATE_PENDING

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_ERR_UPDATE_PENDING


---

## UF_GDT_MAX_NAME_LEN

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_MAX_NAME_LEN


---

## UF_GDT_NO_ERRORS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_NO_ERRORS


---

## UF_GDT_SEPERATE_GAGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_SEPERATE_GAGE


---

## UF_GDT_WARNING

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT_WARNING


---

## UF_GDT__MAX_KEYWORD

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT__MAX_KEYWORD


---

## UF_GDT__MIN_KEYWORD

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/uf_gdt.html#UF_GDT__MIN_KEYWORD


---

## UF_GDT_add_datum_identifier

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_add_datum_identifier


---

## UF_GDT_add_datum_to_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_add_datum_to_feature


---

## UF_GDT_add_fcf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_add_fcf


---

## UF_GDT_add_leader

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_add_leader


---

## UF_GDT_add_size_tolerance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_add_size_tolerance


---

## UF_GDT_annotation_tags_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_annotation_tags_s.html


---

## UF_GDT_ask_annotation_tags

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_annotation_tags


---

## UF_GDT_ask_appended_text

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_appended_text


---

## UF_GDT_ask_associated_datums

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_associated_datums


---

## UF_GDT_ask_association_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_association_type


---

## UF_GDT_ask_callout_strings

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_callout_strings


---

## UF_GDT_ask_characteristic

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_characteristic


---

## UF_GDT_ask_complex_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_complex_feature


---

## UF_GDT_ask_complex_sub_features

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_complex_sub_features


---

## UF_GDT_ask_component_tolerance_index

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_component_tolerance_index


---

## UF_GDT_ask_composite_drf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_composite_drf


---

## UF_GDT_ask_datum_by_label

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_datum_by_label


---

## UF_GDT_ask_datum_ident_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_datum_ident_parms


---

## UF_GDT_ask_datum_keywords

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_datum_keywords


---

## UF_GDT_ask_datum_multiple_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_datum_multiple_parms


---

## UF_GDT_ask_datum_of_label

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_datum_of_label


---

## UF_GDT_ask_datum_of_target

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_datum_of_target


---

## UF_GDT_ask_datum_referencers

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_datum_referencers


---

## UF_GDT_ask_datum_references

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_datum_references


---

## UF_GDT_ask_datums_of_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_datums_of_feature


---

## UF_GDT_ask_depth_tolerance_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_depth_tolerance_parms


---

## UF_GDT_ask_description

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_description


---

## UF_GDT_ask_directed_dimension

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_directed_dimension


---

## UF_GDT_ask_directed_dimension1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_directed_dimension1


---

## UF_GDT_ask_drf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_drf


---

## UF_GDT_ask_face_from_index

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_face_from_index


---

## UF_GDT_ask_face_index

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_face_index


---

## UF_GDT_ask_face_index_string

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_face_index_string


---

## UF_GDT_ask_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_faces


---

## UF_GDT_ask_fcf_drf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_fcf_drf


---

## UF_GDT_ask_fcf_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_fcf_parms


---

## UF_GDT_ask_fcf_tags

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_fcf_tags


---

## UF_GDT_ask_feature_of_datum

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_feature_of_datum


---

## UF_GDT_ask_feature_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_feature_parms


---

## UF_GDT_ask_feature_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_feature_type


---

## UF_GDT_ask_features_of_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_features_of_face


---

## UF_GDT_ask_gdt_object_dfa_file

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_gdt_object_dfa_file


---

## UF_GDT_ask_gdt_view_matrix

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_gdt_view_matrix


---

## UF_GDT_ask_geometric_definition

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_geometric_definition


---

## UF_GDT_ask_index_display

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_index_display


---

## UF_GDT_ask_instance_display_information

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_instance_display_information


---

## UF_GDT_ask_keyword_name

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_keyword_name


---

## UF_GDT_ask_keyword_text

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_keyword_text


---

## UF_GDT_ask_label_of_datum

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_label_of_datum


---

## UF_GDT_ask_leader

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_leader


---

## UF_GDT_ask_limits_and_fits_tolerance_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_limits_and_fits_tolerance_parms


---

## UF_GDT_ask_linked_features

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_linked_features


---

## UF_GDT_ask_load_component_flag

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_load_component_flag


---

## UF_GDT_ask_major_dia_feature_of_spline_gear

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_major_dia_feature_of_spline_gear


---

## UF_GDT_ask_minor_dia_feature_of_spline_gear

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_minor_dia_feature_of_spline_gear


---

## UF_GDT_ask_modl_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_modl_data


---

## UF_GDT_ask_modl_features

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_modl_features


---

## UF_GDT_ask_non_feature_edge_selection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_non_feature_edge_selection


---

## UF_GDT_ask_num_leaders

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_num_leaders


---

## UF_GDT_ask_pitch_dia_feature_of_spline_gear

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_pitch_dia_feature_of_spline_gear


---

## UF_GDT_ask_product_attributes

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_product_attributes


---

## UF_GDT_ask_profile_tol_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_profile_tol_data


---

## UF_GDT_ask_pulled_tolerance_component

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_pulled_tolerance_component


---

## UF_GDT_ask_size_tolerance_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_size_tolerance_parms


---

## UF_GDT_ask_size_tolerance_tag

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_size_tolerance_tag


---

## UF_GDT_ask_sub_features

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_sub_features


---

## UF_GDT_ask_super_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_super_feature


---

## UF_GDT_ask_table_of_instance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_table_of_instance


---

## UF_GDT_ask_tags

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_tags


---

## UF_GDT_ask_target_area_xhatch

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_target_area_xhatch


---

## UF_GDT_ask_target_cyl_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_target_cyl_parms


---

## UF_GDT_ask_target_dia_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_target_dia_parms


---

## UF_GDT_ask_target_line_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_target_line_parms


---

## UF_GDT_ask_target_point_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_target_point_parms


---

## UF_GDT_ask_target_rect_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_target_rect_parms


---

## UF_GDT_ask_target_udef_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_target_udef_parms


---

## UF_GDT_ask_targets_of_datum

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_targets_of_datum


---

## UF_GDT_ask_thread_tolerance_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_thread_tolerance_parms


---

## UF_GDT_ask_tol_feat_instance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_tol_feat_instance


---

## UF_GDT_ask_tol_feat_of_instance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_tol_feat_of_instance


---

## UF_GDT_ask_tol_feat_tag

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_tol_feat_tag


---

## UF_GDT_ask_tolerance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_tolerance


---

## UF_GDT_ask_tolerance_from_index

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_tolerance_from_index


---

## UF_GDT_ask_tolerance_index

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_tolerance_index


---

## UF_GDT_ask_tolerance_index_string

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_tolerance_index_string


---

## UF_GDT_ask_tolerance_types

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_tolerance_types


---

## UF_GDT_ask_tolerance_zone

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_tolerance_zone


---

## UF_GDT_ask_tolerances

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_tolerances


---

## UF_GDT_ask_tolerancing_standard

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_tolerancing_standard


---

## UF_GDT_ask_unit_basis

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_unit_basis


---

## UF_GDT_ask_wall_thickness_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_ask_wall_thickness_parms


---

## UF_GDT_break_relationship

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_break_relationship


---

## UF_GDT_callout_string_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_callout_string_s.html


---

## UF_GDT_characteristic_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_characteristic_e


---

## UF_GDT_create_datum_identifier

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_create_datum_identifier


---

## UF_GDT_create_datum_multiple

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_create_datum_multiple


---

## UF_GDT_create_drf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_create_drf


---

## UF_GDT_create_fcf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_create_fcf


---

## UF_GDT_create_feature_with_product_att

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_create_feature_with_product_att


---

## UF_GDT_create_instance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_create_instance


---

## UF_GDT_create_modl_based_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_create_modl_based_feature


---

## UF_GDT_create_size_tolerance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_create_size_tolerance


---

## UF_GDT_create_table_instance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_create_table_instance


---

## UF_GDT_create_target_cyl_area

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_create_target_cyl_area


---

## UF_GDT_create_target_dia_area

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_create_target_dia_area


---

## UF_GDT_create_target_line

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_create_target_line


---

## UF_GDT_create_target_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_create_target_point


---

## UF_GDT_create_target_rect_area

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_create_target_rect_area


---

## UF_GDT_create_target_udef_area

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_create_target_udef_area


---

## UF_GDT_create_wall_thickness

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_create_wall_thickness


---

## UF_GDT_data_frame_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_data_frame_s.html


---

## UF_GDT_data_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_data_type_e


---

## UF_GDT_datum_assoc_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_datum_assoc_type_e


---

## UF_GDT_datum_identifier_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_datum_identifier_s.html


---

## UF_GDT_datum_reference_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_datum_reference_s.html


---

## UF_GDT_datum_target_line_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_datum_target_line_s.html


---

## UF_GDT_datum_target_point_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_datum_target_point_s.html


---

## UF_GDT_default_gage_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_default_gage_type_e


---

## UF_GDT_depth_tolerance_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_depth_tolerance_s.html


---

## UF_GDT_description_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_description_s.html


---

## UF_GDT_directed_dimension1_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_directed_dimension1_s.html


---

## UF_GDT_directed_dimension_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_directed_dimension_s.html


---

## UF_GDT_directed_dimension_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_directed_dimension_type_e


---

## UF_GDT_drf_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_drf_data_s.html


---

## UF_GDT_drf_reference_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_drf_reference_s.html


---

## UF_GDT_edge_select_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_edge_select_type_e


---

## UF_GDT_export_drawings

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_export_drawings


---

## UF_GDT_fcf_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_fcf_s.html


---

## UF_GDT_feature_parms_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_feature_parms_s.html


---

## UF_GDT_feature_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_feature_type_e


---

## UF_GDT_free

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_free


---

## UF_GDT_geometric_definition_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_geometric_definition_s.html


---

## UF_GDT_geometric_definition_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_geometric_definition_type_e


---

## UF_GDT_has_depth_tolerance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_has_depth_tolerance


---

## UF_GDT_has_directed_dimension

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_has_directed_dimension


---

## UF_GDT_has_geometric_definition

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_has_geometric_definition


---

## UF_GDT_has_limits_and_fits_tolerance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_has_limits_and_fits_tolerance


---

## UF_GDT_has_size_tolerance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_has_size_tolerance


---

## UF_GDT_has_wall_thickness

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_has_wall_thickness


---

## UF_GDT_index_display_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_index_display_type_e


---

## UF_GDT_inherit_model_gdt_to_drawing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_inherit_model_gdt_to_drawing


---

## UF_GDT_init

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_init


---

## UF_GDT_is_complex_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_is_complex_feature


---

## UF_GDT_is_complex_sub_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_is_complex_sub_feature


---

## UF_GDT_is_composite_tolerance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_is_composite_tolerance


---

## UF_GDT_is_datum

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_is_datum


---

## UF_GDT_is_datum_target

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_is_datum_target


---

## UF_GDT_is_feature_of_size

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_is_feature_of_size


---

## UF_GDT_is_gdt_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_is_gdt_view


---

## UF_GDT_is_linked_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_is_linked_feature


---

## UF_GDT_is_modl_based

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_is_modl_based


---

## UF_GDT_is_pulled_tolerance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_is_pulled_tolerance


---

## UF_GDT_is_retained

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_is_retained


---

## UF_GDT_is_single_datum_reference_frame

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_is_single_datum_reference_frame


---

## UF_GDT_is_user_defined_keyword

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_is_user_defined_keyword


---

## UF_GDT_keyword_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_keyword_s.html


---

## UF_GDT_leader_spec_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_leader_spec_s.html


---

## UF_GDT_leader_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_leader_type_e


---

## UF_GDT_limits_and_fits_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_limits_and_fits_data_s.html


---

## UF_GDT_limits_and_fits_display_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_limits_and_fits_display_type_e


---

## UF_GDT_limits_and_fits_tolerance_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_limits_and_fits_tolerance_s.html


---

## UF_GDT_material_modifier_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_material_modifier_e


---

## UF_GDT_modifier_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_modifier_data_s.html


---

## UF_GDT_modifier_types_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_modifier_types_e


---

## UF_GDT_modl_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_modl_data_s.html


---

## UF_GDT_modl_parameter_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_modl_parameter_e


---

## UF_GDT_multiple_datum_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_multiple_datum_s.html


---

## UF_GDT_pattern_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_pattern_type_e


---

## UF_GDT_point_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_point_s.html


---

## UF_GDT_precedence_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_precedence_e


---

## UF_GDT_product_attribute_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_product_attribute_s.html


---

## UF_GDT_profile_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_profile_type_e


---

## UF_GDT_proj_zone_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_proj_zone_s.html


---

## UF_GDT_pull_tolerance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_pull_tolerance


---

## UF_GDT_relation_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_relation_type_e


---

## UF_GDT_remove_leader

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_remove_leader


---

## UF_GDT_reset_callout_rules

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_reset_callout_rules


---

## UF_GDT_restrained_condition_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_restrained_condition_e


---

## UF_GDT_set_appended_text

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_appended_text


---

## UF_GDT_set_characteristic

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_characteristic


---

## UF_GDT_set_composite_drf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_composite_drf


---

## UF_GDT_set_datum_identifier

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_datum_identifier


---

## UF_GDT_set_datum_keywords

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_datum_keywords


---

## UF_GDT_set_datum_label

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_datum_label


---

## UF_GDT_set_datum_multiple

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_datum_multiple


---

## UF_GDT_set_datum_references

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_datum_references


---

## UF_GDT_set_depth_tolerance_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_depth_tolerance_parms


---

## UF_GDT_set_description

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_description


---

## UF_GDT_set_directed_dimension

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_directed_dimension


---

## UF_GDT_set_drf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_drf


---

## UF_GDT_set_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_faces


---

## UF_GDT_set_fcf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_fcf


---

## UF_GDT_set_fcf_drf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_fcf_drf


---

## UF_GDT_set_geometric_definition

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_geometric_definition


---

## UF_GDT_set_index_display

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_index_display


---

## UF_GDT_set_instance_display_information

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_instance_display_information


---

## UF_GDT_set_keyword_text

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_keyword_text


---

## UF_GDT_set_limits_and_fits_tolerance_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_limits_and_fits_tolerance_parms


---

## UF_GDT_set_load_component_flag

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_load_component_flag


---

## UF_GDT_set_modl_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_modl_data


---

## UF_GDT_set_non_feature_edge_selection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_non_feature_edge_selection


---

## UF_GDT_set_profile_tol_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_profile_tol_data


---

## UF_GDT_set_region_parameters

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_region_parameters


---

## UF_GDT_set_size_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_size_data


---

## UF_GDT_set_size_tolerance_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_size_tolerance_parms


---

## UF_GDT_set_target_area_xhatch

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_target_area_xhatch


---

## UF_GDT_set_thread_tolerance_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_thread_tolerance_parms


---

## UF_GDT_set_tolerance_zones

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_tolerance_zones


---

## UF_GDT_set_tolerancing_standard

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_tolerancing_standard


---

## UF_GDT_set_unit_basis

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_unit_basis


---

## UF_GDT_set_wall_thickness_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_set_wall_thickness_parms


---

## UF_GDT_size_tolerance_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_size_tolerance_s.html


---

## UF_GDT_size_value_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_size_value_type_e


---

## UF_GDT_standard_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_standard_e


---

## UF_GDT_standard_keyword_id_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_standard_keyword_id_e


---

## UF_GDT_statistical_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_statistical_info_s.html


---

## UF_GDT_stub_direction_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_stub_direction_e


---

## UF_GDT_surface_parms_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_surface_parms_s.html


---

## UF_GDT_target_cyl_area_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_target_cyl_area_s.html


---

## UF_GDT_target_dia_area_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_target_dia_area_s.html


---

## UF_GDT_target_non_planar_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_target_non_planar_data_s.html


---

## UF_GDT_target_rect_area_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_target_rect_area_s.html


---

## UF_GDT_target_udef_area_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_target_udef_area_s.html


---

## UF_GDT_text_location_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_text_location_e


---

## UF_GDT_thread_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_thread_data_s.html


---

## UF_GDT_thread_tolerance_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_thread_tolerance_s.html


---

## UF_GDT_tol_format_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_tol_format_e


---

## UF_GDT_tolerance_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_tolerance_type_e


---

## UF_GDT_tolerance_value_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_tolerance_value_s.html


---

## UF_GDT_tolerance_zone_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_tolerance_zone_s.html


---

## UF_GDT_unit_basis_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/UF_GDT_unit_basis_s.html


---

## UF_GDT_update_features

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_update_features


---

## UF_GDT_upgrade_legacy_feature

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/global.html#UF_GDT_upgrade_legacy_feature


---

## UF_GDT_zone_shape_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/types.html#UF_GDT_zone_shape_e


---

## uf_gdt.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_gdt/intro.html#uf_gdt


---
