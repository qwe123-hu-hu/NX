# UF_DRF 函数参考

> 共 750 个函数

---

## 目录

- [UF_DRF #Defines](#uf_drf #defines)
- [UF_DRF Callbacks](#uf_drf callbacks)
- [UF_DRF Enumerations](#uf_drf enumerations)
- [UF_DRF Files](#uf_drf files)
- [UF_DRF Functions](#uf_drf functions)
- [UF_DRF Structures](#uf_drf structures)
- [UF_DRF_BAD_SYMBOL_TEXT_OBJECT](#uf_drf_bad_symbol_text_object)
- [UF_DRF_CANNOT_ATTACH_CANT_FIND_NORMAL](#uf_drf_cannot_attach_cant_find_normal)
- [UF_DRF_CANNOT_ATTACH_TO_DIM_TYPE](#uf_drf_cannot_attach_to_dim_type)
- [UF_DRF_CANNOT_ATTACH_TO_DISASSOC_DMV_FACET_REP](#uf_drf_cannot_attach_to_disassoc_dmv_facet_rep)
- [UF_DRF_CANNOT_ATTACH_TO_LEADER_WITHOUT_ARROWS](#uf_drf_cannot_attach_to_leader_without_arrows)
- [UF_DRF_CANNOT_ATTACH_TO_NON_FACE](#uf_drf_cannot_attach_to_non_face)
- [UF_DRF_CANNOT_ATTACH_TO_NON_LINEAR](#uf_drf_cannot_attach_to_non_linear)
- [UF_DRF_CANNOT_ATTACH_TO_OBJ_IN_DIFF_VIEW](#uf_drf_cannot_attach_to_obj_in_diff_view)
- [UF_DRF_CANNOT_ATTACH_TO_OCC](#uf_drf_cannot_attach_to_occ)
- [UF_DRF_CANNOT_ATTACH_TO_RETAINED_ANNOT](#uf_drf_cannot_attach_to_retained_annot)
- [UF_DRF_CANNOT_ATTACH_TO_VIEW_LABEL](#uf_drf_cannot_attach_to_view_label)
- [UF_DRF_CANNOT_ATTACH_TO_WELD_SYMBOL](#uf_drf_cannot_attach_to_weld_symbol)
- [UF_DRF_CANNOT_CHANGE_LEADER_POS_PARAM](#uf_drf_cannot_change_leader_pos_param)
- [UF_DRF_CANNOT_DISPLAY_ALL_AROUND_ALL_OVER_CIRCLE](#uf_drf_cannot_display_all_around_all_over_circle)
- [UF_DRF_CANNOT_DISPLAY_ALL_AROUND_CIRCLE](#uf_drf_cannot_display_all_around_circle)
- [UF_DRF_CANNOT_DISPLAY_ALL_OVER_CIRCLE](#uf_drf_cannot_display_all_over_circle)
- [UF_DRF_CANNOT_PROCESS_SYMBOL_FONT](#uf_drf_cannot_process_symbol_font)
- [UF_DRF_CANT_REMOVE_LAST_LEADER](#uf_drf_cant_remove_last_leader)
- [UF_DRF_CLINE_ALL_POINTS_NOT_COLLINEAR](#uf_drf_cline_all_points_not_collinear)
- [UF_DRF_CLINE_ANGLE_OUT_OF_RANGE](#uf_drf_cline_angle_out_of_range)
- [UF_DRF_CLINE_AUTO_INVALID_CYL_EXTENSION](#uf_drf_cline_auto_invalid_cyl_extension)
- [UF_DRF_CLINE_AUTO_INVALID_VIEW](#uf_drf_cline_auto_invalid_view)
- [UF_DRF_CLINE_AUTO_NO_VIEWS](#uf_drf_cline_auto_no_views)
- [UF_DRF_CLINE_DUPLICATE_POINTS_SELECTED](#uf_drf_cline_duplicate_points_selected)
- [UF_DRF_CLINE_INCORRECT_NUM_ASSOC_OBJECTS](#uf_drf_cline_incorrect_num_assoc_objects)
- [UF_DRF_CLINE_INSUFFICIENT_INPUT](#uf_drf_cline_insufficient_input)
- [UF_DRF_CLINE_INVALID_EXTENSION](#uf_drf_cline_invalid_extension)
- [UF_DRF_CLINE_INVALID_INPUT](#uf_drf_cline_invalid_input)
- [UF_DRF_CLINE_INVALID_INTERSECTION](#uf_drf_cline_invalid_intersection)
- [UF_DRF_CLINE_INVALID_OBJECT](#uf_drf_cline_invalid_object)
- [UF_DRF_CLINE_INVALID_OFFSET_DISTANCE](#uf_drf_cline_invalid_offset_distance)
- [UF_DRF_CLINE_INVALID_OFFSET_OBJECT](#uf_drf_cline_invalid_offset_object)
- [UF_DRF_CLINE_INVALID_RADIUS](#uf_drf_cline_invalid_radius)
- [UF_DRF_CLINE_MEMORY_ALLOCATION_ERROR](#uf_drf_cline_memory_allocation_error)
- [UF_DRF_CLINE_NON_COLLINEAR_POINTS](#uf_drf_cline_non_collinear_points)
- [UF_DRF_CLINE_POINTS_COLLINEAR](#uf_drf_cline_points_collinear)
- [UF_DRF_CLINE_POINTS_COMPUTATION_FAILURE](#uf_drf_cline_points_computation_failure)
- [UF_DRF_CLINE_RETAINED_HANDLE_FOUND](#uf_drf_cline_retained_handle_found)
- [UF_DRF_CLINE_UNABLE_TO_CREATE_ERROR](#uf_drf_cline_unable_to_create_error)
- [UF_DRF_CLINE_UNEQUAL_RADIUS](#uf_drf_cline_unequal_radius)
- [UF_DRF_CMP_DWG_DIFF_FOUND](#uf_drf_cmp_dwg_diff_found)
- [UF_DRF_CMP_DWG_DIFF_NOT_PERFORMED](#uf_drf_cmp_dwg_diff_not_performed)
- [UF_DRF_COINCIDENT_ANCHOR_ORIENTATION_PT](#uf_drf_coincident_anchor_orientation_pt)
- [UF_DRF_CONFLICT_BASIC_TOL_AND_INSPECTION_TYPE](#uf_drf_conflict_basic_tol_and_inspection_type)
- [UF_DRF_CONFLICT_REF_TOL_AND_REF_SYMBOL_TYPE](#uf_drf_conflict_ref_tol_and_ref_symbol_type)
- [UF_DRF_DECIMAL_PLACES_MAX](#uf_drf_decimal_places_max)
- [UF_DRF_DEFAULT_TEXT_OUT_OF_BOUNDS](#uf_drf_default_text_out_of_bounds)
- [UF_DRF_DIAMETER_RADIUS_SYMBOL_MAX_BUFSIZE](#uf_drf_diameter_radius_symbol_max_bufsize)
- [UF_DRF_DIAMETER_RADIUS_SYMBOL_MAX_LENGTH](#uf_drf_diameter_radius_symbol_max_length)
- [UF_DRF_DIAMETER_RADIUS_SYMBOL_MAX_NCHARS](#uf_drf_diameter_radius_symbol_max_nchars)
- [UF_DRF_DIM_HAS_NO_EXT_LINES](#uf_drf_dim_has_no_ext_lines)
- [UF_DRF_ERROR_BASE](#uf_drf_error_base)
- [UF_DRF_ERROR_OPENING_CURRENT_SBF_FILE](#uf_drf_error_opening_current_sbf_file)
- [UF_DRF_ERROR_RANGE](#uf_drf_error_range)
- [UF_DRF_FILENAME_EXISTS](#uf_drf_filename_exists)
- [UF_DRF_GDT_REQUIRED_FOR_LEADER_TYPE](#uf_drf_gdt_required_for_leader_type)
- [UF_DRF_HAS_NO_LEADER_POS_PARAM](#uf_drf_has_no_leader_pos_param)
- [UF_DRF_IMAGE_CORRUPT_OBJECT](#uf_drf_image_corrupt_object)
- [UF_DRF_INFINITE_RADIUS](#uf_drf_infinite_radius)
- [UF_DRF_INTERMEDIATE_PTS_NOT_ALLOWED](#uf_drf_intermediate_pts_not_allowed)
- [UF_DRF_INVALID_ALIGN_POSITION](#uf_drf_invalid_align_position)
- [UF_DRF_INVALID_ALL_AROUND_SYMBOL_SIZE](#uf_drf_invalid_all_around_symbol_size)
- [UF_DRF_INVALID_ANCHOR_POINT_OBJECT](#uf_drf_invalid_anchor_point_object)
- [UF_DRF_INVALID_APPEARANCE_SLANT_ANGLE](#uf_drf_invalid_appearance_slant_angle)
- [UF_DRF_INVALID_APPENDED_TEXT_ASPECT_RATIO](#uf_drf_invalid_appended_text_aspect_ratio)
- [UF_DRF_INVALID_APPENDED_TEXT_CHARACTER_SPACE_FACTOR](#uf_drf_invalid_appended_text_character_space_factor)
- [UF_DRF_INVALID_APPENDED_TEXT_LINE_SPACE_FACTOR](#uf_drf_invalid_appended_text_line_space_factor)
- [UF_DRF_INVALID_APPENDED_TEXT_SIZE](#uf_drf_invalid_appended_text_size)
- [UF_DRF_INVALID_AREA_FILL_MATERIAL](#uf_drf_invalid_area_fill_material)
- [UF_DRF_INVALID_AREA_FILL_SCALE](#uf_drf_invalid_area_fill_scale)
- [UF_DRF_INVALID_ARROWHEAD_LENGTH](#uf_drf_invalid_arrowhead_length)
- [UF_DRF_INVALID_ARROW_DISPLAY](#uf_drf_invalid_arrow_display)
- [UF_DRF_INVALID_ARROW_FILL_STATUS](#uf_drf_invalid_arrow_fill_status)
- [UF_DRF_INVALID_ARROW_OUT_LENGTH_FACTOR](#uf_drf_invalid_arrow_out_length_factor)
- [UF_DRF_INVALID_ARROW_TYPE](#uf_drf_invalid_arrow_type)
- [UF_DRF_INVALID_ASSOCIATED_OBJECT](#uf_drf_invalid_associated_object)
- [UF_DRF_INVALID_CHAMFER_DIMENSION](#uf_drf_invalid_chamfer_dimension)
- [UF_DRF_INVALID_CHAMFER_DIMENSION_FORM](#uf_drf_invalid_chamfer_dimension_form)
- [UF_DRF_INVALID_CHAMFER_DIMENSION_LEADER_TYPE](#uf_drf_invalid_chamfer_dimension_leader_type)
- [UF_DRF_INVALID_CHAMFER_DIMENSION_SPACE_FACTOR](#uf_drf_invalid_chamfer_dimension_space_factor)
- [UF_DRF_INVALID_CHAMFER_DIMENSION_STUB_TYPE](#uf_drf_invalid_chamfer_dimension_stub_type)
- [UF_DRF_INVALID_CHAMFER_DIMENSION_SYMBOL_NAME](#uf_drf_invalid_chamfer_dimension_symbol_name)
- [UF_DRF_INVALID_CHAMFER_DIMENSION_SYMBOL_TYPE](#uf_drf_invalid_chamfer_dimension_symbol_type)
- [UF_DRF_INVALID_CMP_DWG_BASELINE](#uf_drf_invalid_cmp_dwg_baseline)
- [UF_DRF_INVALID_CMP_DWG_PLOT_OPTIONS](#uf_drf_invalid_cmp_dwg_plot_options)
- [UF_DRF_INVALID_COLOR](#uf_drf_invalid_color)
- [UF_DRF_INVALID_COLUMN](#uf_drf_invalid_column)
- [UF_DRF_INVALID_CROSSHATCH_FILE_FORMAT](#uf_drf_invalid_crosshatch_file_format)
- [UF_DRF_INVALID_CUSTOM_SYMBOL_PIECE](#uf_drf_invalid_custom_symbol_piece)
- [UF_DRF_INVALID_DATUM_LENGTH_PAST_ARROW](#uf_drf_invalid_datum_length_past_arrow)
- [UF_DRF_INVALID_DATUM_TARGET_INDEX](#uf_drf_invalid_datum_target_index)
- [UF_DRF_INVALID_DATUM_TARGET_LABEL](#uf_drf_invalid_datum_target_label)
- [UF_DRF_INVALID_DECIMAL_POINT_CHARACTER](#uf_drf_invalid_decimal_point_character)
- [UF_DRF_INVALID_DETAIL_LEVEL_TYPE](#uf_drf_invalid_detail_level_type)
- [UF_DRF_INVALID_DIAMETER_SYMBOL_TYPE](#uf_drf_invalid_diameter_symbol_type)
- [UF_DRF_INVALID_DIAM_RADIUS_PLACEMENT](#uf_drf_invalid_diam_radius_placement)
- [UF_DRF_INVALID_DIMENSION_ANGULAR_FORMAT](#uf_drf_invalid_dimension_angular_format)
- [UF_DRF_INVALID_DIMENSION_ANGULAR_FORMAT_TOLERANCE](#uf_drf_invalid_dimension_angular_format_tolerance)
- [UF_DRF_INVALID_DIMENSION_ANGULAR_SUPPRESS_ZEROS](#uf_drf_invalid_dimension_angular_suppress_zeros)
- [UF_DRF_INVALID_DIMENSION_ORIENTATION](#uf_drf_invalid_dimension_orientation)
- [UF_DRF_INVALID_DIMENSION_TEXT_ASPECT_RATIO](#uf_drf_invalid_dimension_text_aspect_ratio)
- [UF_DRF_INVALID_DIMENSION_TEXT_CHARACTER_SPACE_FACTOR](#uf_drf_invalid_dimension_text_character_space_factor)
- [UF_DRF_INVALID_DIMENSION_TEXT_LINE_SPACE_FACTOR](#uf_drf_invalid_dimension_text_line_space_factor)
- [UF_DRF_INVALID_DIMENSION_TEXT_SIZE](#uf_drf_invalid_dimension_text_size)
- [UF_DRF_INVALID_DIMENSION_TOL_PLACEMENT](#uf_drf_invalid_dimension_tol_placement)
- [UF_DRF_INVALID_DIM_APP_TEXT_SPACE_FACTOR](#uf_drf_invalid_dim_app_text_space_factor)
- [UF_DRF_INVALID_DIM_DIM_LINE_SPACE_FACTOR](#uf_drf_invalid_dim_dim_line_space_factor)
- [UF_DRF_INVALID_DIM_INSPECTION_TYPE](#uf_drf_invalid_dim_inspection_type)
- [UF_DRF_INVALID_DIM_REFERENCE_TYPE](#uf_drf_invalid_dim_reference_type)
- [UF_DRF_INVALID_DIM_TOL_TEXT_SPACE_FACTOR](#uf_drf_invalid_dim_tol_text_space_factor)
- [UF_DRF_INVALID_DIM_TYPE_FOR_OPERATION](#uf_drf_invalid_dim_type_for_operation)
- [UF_DRF_INVALID_DOGLEG_ANGLE](#uf_drf_invalid_dogleg_angle)
- [UF_DRF_INVALID_DOGLEG_END_OFFSET](#uf_drf_invalid_dogleg_end_offset)
- [UF_DRF_INVALID_DOGLEG_END_OFFSET_ZERO](#uf_drf_invalid_dogleg_end_offset_zero)
- [UF_DRF_INVALID_DOGLEG_START_OFFSET](#uf_drf_invalid_dogleg_start_offset)
- [UF_DRF_INVALID_DOT_DIAMETER](#uf_drf_invalid_dot_diameter)
- [UF_DRF_INVALID_DUAL_DIMENSION_FORMAT](#uf_drf_invalid_dual_dimension_format)
- [UF_DRF_INVALID_DUAL_DIMENSION_UNITS](#uf_drf_invalid_dual_dimension_units)
- [UF_DRF_INVALID_DUAL_FRACTION_TYPE](#uf_drf_invalid_dual_fraction_type)
- [UF_DRF_INVALID_EXTENSION_LINE_DISPLAY](#uf_drf_invalid_extension_line_display)
- [UF_DRF_INVALID_FABRICATION_NUMBER](#uf_drf_invalid_fabrication_number)
- [UF_DRF_INVALID_FACE_ORIENTATION](#uf_drf_invalid_face_orientation)
- [UF_DRF_INVALID_FIRST_POS_TO_EXTENSION_LINE_DISTANCE](#uf_drf_invalid_first_pos_to_extension_line_distance)
- [UF_DRF_INVALID_FOLDER_INPUT](#uf_drf_invalid_folder_input)
- [UF_DRF_INVALID_FONT](#uf_drf_invalid_font)
- [UF_DRF_INVALID_FONT_STYLE](#uf_drf_invalid_font_style)
- [UF_DRF_INVALID_FRACTION_DENOMINATOR](#uf_drf_invalid_fraction_denominator)
- [UF_DRF_INVALID_GDT_FRAME_FACTOR](#uf_drf_invalid_gdt_frame_factor)
- [UF_DRF_INVALID_GENERAL_TEXT_ASPECT_RATIO](#uf_drf_invalid_general_text_aspect_ratio)
- [UF_DRF_INVALID_GENERAL_TEXT_CHARACTER_SPACE_FACTOR](#uf_drf_invalid_general_text_character_space_factor)
- [UF_DRF_INVALID_GENERAL_TEXT_LINE_SPACE_FACTOR](#uf_drf_invalid_general_text_line_space_factor)
- [UF_DRF_INVALID_GENERAL_TEXT_SIZE](#uf_drf_invalid_general_text_size)
- [UF_DRF_INVALID_HATCH_DISTANCE](#uf_drf_invalid_hatch_distance)
- [UF_DRF_INVALID_HATCH_TOLERANCE](#uf_drf_invalid_hatch_tolerance)
- [UF_DRF_INVALID_HORIZ_TEXT_JUST](#uf_drf_invalid_horiz_text_just)
- [UF_DRF_INVALID_ID_SYMBOL](#uf_drf_invalid_id_symbol)
- [UF_DRF_INVALID_INHERIT_TAG](#uf_drf_invalid_inherit_tag)
- [UF_DRF_INVALID_INTEGER_INPUT](#uf_drf_invalid_integer_input)
- [UF_DRF_INVALID_JOG_ANGLE](#uf_drf_invalid_jog_angle)
- [UF_DRF_INVALID_JOG_END_OFFSET](#uf_drf_invalid_jog_end_offset)
- [UF_DRF_INVALID_JOG_END_OFFSET_ZERO](#uf_drf_invalid_jog_end_offset_zero)
- [UF_DRF_INVALID_JOG_EXTLINE_ANGLE_CONFIG](#uf_drf_invalid_jog_extline_angle_config)
- [UF_DRF_INVALID_JOG_START_OFFSET](#uf_drf_invalid_jog_start_offset)
- [UF_DRF_INVALID_LEADER_LOCATION](#uf_drf_invalid_leader_location)
- [UF_DRF_INVALID_LINEAR_FRACTION_TYPE](#uf_drf_invalid_linear_fraction_type)
- [UF_DRF_INVALID_LINEAR_UNITS](#uf_drf_invalid_linear_units)
- [UF_DRF_INVALID_LINE_PAST_ARROW_DISTANCE](#uf_drf_invalid_line_past_arrow_distance)
- [UF_DRF_INVALID_NARROW_DIMENSION_DISPLAY_TYPE](#uf_drf_invalid_narrow_dimension_display_type)
- [UF_DRF_INVALID_NARROW_DIMENSION_LEADER_ANGLE](#uf_drf_invalid_narrow_dimension_leader_angle)
- [UF_DRF_INVALID_NARROW_DIMENSION_TEXT_ORIENTATION](#uf_drf_invalid_narrow_dimension_text_orientation)
- [UF_DRF_INVALID_NOTE_TITLE](#uf_drf_invalid_note_title)
- [UF_DRF_INVALID_NUMBER_OF_DECIMAL_PLACES](#uf_drf_invalid_number_of_decimal_places)
- [UF_DRF_INVALID_NUMBER_OF_FEATURES](#uf_drf_invalid_number_of_features)
- [UF_DRF_INVALID_NUMBER_OF_VIEWS](#uf_drf_invalid_number_of_views)
- [UF_DRF_INVALID_OBJ_FOR_ASSORTED_PARTS](#uf_drf_invalid_obj_for_assorted_parts)
- [UF_DRF_INVALID_OFFSET_CURVES](#uf_drf_invalid_offset_curves)
- [UF_DRF_INVALID_ORDINATE_MARGIN_NUMBER](#uf_drf_invalid_ordinate_margin_number)
- [UF_DRF_INVALID_ORDINATE_MARGIN_SPACING](#uf_drf_invalid_ordinate_margin_spacing)
- [UF_DRF_INVALID_PINLIST_FILTER](#uf_drf_invalid_pinlist_filter)
- [UF_DRF_INVALID_RADIUS_SYMBOL_TYPE](#uf_drf_invalid_radius_symbol_type)
- [UF_DRF_INVALID_REAL_INPUT](#uf_drf_invalid_real_input)
- [UF_DRF_INVALID_ROW](#uf_drf_invalid_row)
- [UF_DRF_INVALID_SECOND_POS_TO_EXTENSION_LINE_DISTANCE](#uf_drf_invalid_second_pos_to_extension_line_distance)
- [UF_DRF_INVALID_STACK_HORIZONTAL_ALIGNMENT](#uf_drf_invalid_stack_horizontal_alignment)
- [UF_DRF_INVALID_STACK_SPACE_FACTOR](#uf_drf_invalid_stack_space_factor)
- [UF_DRF_INVALID_STACK_VERTICAL_ALIGNMENT](#uf_drf_invalid_stack_vertical_alignment)
- [UF_DRF_INVALID_STOCK_LENGTH_VALUE](#uf_drf_invalid_stock_length_value)
- [UF_DRF_INVALID_STRING_INPUT](#uf_drf_invalid_string_input)
- [UF_DRF_INVALID_STUB_LENGTH](#uf_drf_invalid_stub_length)
- [UF_DRF_INVALID_SYMBOL_ASPECT_RATIO](#uf_drf_invalid_symbol_aspect_ratio)
- [UF_DRF_INVALID_SYMBOL_FONT_OBJECTS](#uf_drf_invalid_symbol_font_objects)
- [UF_DRF_INVALID_SYMBOL_NAME](#uf_drf_invalid_symbol_name)
- [UF_DRF_INVALID_SYMBOL_TO_DIMENSION_TEXT_DISTANCE](#uf_drf_invalid_symbol_to_dimension_text_distance)
- [UF_DRF_INVALID_SYMBOL_TYPE](#uf_drf_invalid_symbol_type)
- [UF_DRF_INVALID_TEXT](#uf_drf_invalid_text)
- [UF_DRF_INVALID_TEXT_ARROW_PLACEMENT](#uf_drf_invalid_text_arrow_placement)
- [UF_DRF_INVALID_TEXT_OVER_LEADER_GAP_FACTOR](#uf_drf_invalid_text_over_leader_gap_factor)
- [UF_DRF_INVALID_TEXT_OVER_STUB_FACTOR](#uf_drf_invalid_text_over_stub_factor)
- [UF_DRF_INVALID_TEXT_PLACEMENT](#uf_drf_invalid_text_placement)
- [UF_DRF_INVALID_TEXT_TO_LINE_DISTANCE](#uf_drf_invalid_text_to_line_distance)
- [UF_DRF_INVALID_TOLERANCE_TEXT_ASPECT_RATIO](#uf_drf_invalid_tolerance_text_aspect_ratio)
- [UF_DRF_INVALID_TOLERANCE_TEXT_CHARACTER_SPACE_FACTOR](#uf_drf_invalid_tolerance_text_character_space_factor)
- [UF_DRF_INVALID_TOLERANCE_TEXT_LINE_SPACE_FACTOR](#uf_drf_invalid_tolerance_text_line_space_factor)
- [UF_DRF_INVALID_TOLERANCE_TEXT_SIZE](#uf_drf_invalid_tolerance_text_size)
- [UF_DRF_INVALID_TOLERANCE_TYPE](#uf_drf_invalid_tolerance_type)
- [UF_DRF_INVALID_TRIM_DIM_LINE_TYPE](#uf_drf_invalid_trim_dim_line_type)
- [UF_DRF_INVALID_TRUE_LENGTH_TEXT_POSITION](#uf_drf_invalid_true_length_text_position)
- [UF_DRF_INVALID_USE_OF_API](#uf_drf_invalid_use_of_api)
- [UF_DRF_INVALID_WELD_LINE_GAP](#uf_drf_invalid_weld_line_gap)
- [UF_DRF_INVALID_WELD_SPACE_FACTOR](#uf_drf_invalid_weld_space_factor)
- [UF_DRF_INVALID_WELD_SYMBOL_SIZE_FACTOR](#uf_drf_invalid_weld_symbol_size_factor)
- [UF_DRF_INVALID_WELD_TYPE](#uf_drf_invalid_weld_type)
- [UF_DRF_INVALID_WIDTH](#uf_drf_invalid_width)
- [UF_DRF_LEADER_HAS_NO_CONNECTION](#uf_drf_leader_has_no_connection)
- [UF_DRF_LEADER_IS_REQD](#uf_drf_leader_is_reqd)
- [UF_DRF_LEADER_MAX_INT_POINTS](#uf_drf_leader_max_int_points)
- [UF_DRF_LEADER_MAX_LEADERS](#uf_drf_leader_max_leaders)
- [UF_DRF_LEADER_REQUIRED](#uf_drf_leader_required)
- [UF_DRF_LIMIT_FIT_INVALID_ASSY_DISPLAY_STYLE](#uf_drf_limit_fit_invalid_assy_display_style)
- [UF_DRF_LIMIT_FIT_INVALID_DEVIATION](#uf_drf_limit_fit_invalid_deviation)
- [UF_DRF_LIMIT_FIT_INVALID_DISPLAY_STYLE](#uf_drf_limit_fit_invalid_display_style)
- [UF_DRF_LIMIT_FIT_INVALID_GRADE](#uf_drf_limit_fit_invalid_grade)
- [UF_DRF_LIMIT_FIT_INVALID_HOLE_TYPE](#uf_drf_limit_fit_invalid_hole_type)
- [UF_DRF_LIMIT_FIT_INVALID_PAREN_STYLE](#uf_drf_limit_fit_invalid_paren_style)
- [UF_DRF_LIMIT_FIT_INVALID_SEPARATOR](#uf_drf_limit_fit_invalid_separator)
- [UF_DRF_LIMIT_FIT_INVALID_SPLIT_BY_DIMLINE](#uf_drf_limit_fit_invalid_split_by_dimline)
- [UF_DRF_LIMIT_FIT_INVALID_TOL_ALIGNMENT](#uf_drf_limit_fit_invalid_tol_alignment)
- [UF_DRF_MAP_DRF_LINE_WIDTH_TO_OBJ_WIDTH](#uf_drf_map_drf_line_width_to_obj_width)
- [UF_DRF_MAP_OBJ_WIDTH_TO_DRF_LINE_WIDTH](#uf_drf_map_obj_width_to_drf_line_width)
- [UF_DRF_MAX_FONT_BUFSIZE](#uf_drf_max_font_bufsize)
- [UF_DRF_MAX_FONT_LEN](#uf_drf_max_font_len)
- [UF_DRF_MAX_FONT_NCHARS](#uf_drf_max_font_nchars)
- [UF_DRF_MAX_HATCH_FILE_NAME_LEN](#uf_drf_max_hatch_file_name_len)
- [UF_DRF_MAX_HATCH_MATERIAL_NAME](#uf_drf_max_hatch_material_name)
- [UF_DRF_MAX_HATCH_MATERIAL_NAME_BUFSIZE](#uf_drf_max_hatch_material_name_bufsize)
- [UF_DRF_MAX_HATCH_MATERIAL_NAME_NCHARS](#uf_drf_max_hatch_material_name_nchars)
- [UF_DRF_MIN_NEW_WIDTH](#uf_drf_min_new_width)
- [UF_DRF_MORE_THAN_7_LEADERS](#uf_drf_more_than_7_leaders)
- [UF_DRF_MULTIPLE_PLISTS_NOT_ALLOWED](#uf_drf_multiple_plists_not_allowed)
- [UF_DRF_NOT_A_CUSTOM_SYMBOL](#uf_drf_not_a_custom_symbol)
- [UF_DRF_NOT_DRAFTING_OBJECT](#uf_drf_not_drafting_object)
- [UF_DRF_NOT_VALID_FOR_GB_DAT_DIM](#uf_drf_not_valid_for_gb_dat_dim)
- [UF_DRF_NOT_VALID_GDT_TYPE](#uf_drf_not_valid_gdt_type)
- [UF_DRF_NOT_VALID_LEADER_ATTACH_OBJ](#uf_drf_not_valid_leader_attach_obj)
- [UF_DRF_NO_ERRORS](#uf_drf_no_errors)
- [UF_DRF_NO_SBF_FILE_NAME](#uf_drf_no_sbf_file_name)
- [UF_DRF_NO_TEMPLATE_ENV_VAR](#uf_drf_no_template_env_var)
- [UF_DRF_NO_VALID_COMPONENT_FOUND](#uf_drf_no_valid_component_found)
- [UF_DRF_OBJECTS_ARE_NOT_CONSTANT](#uf_drf_objects_are_not_constant)
- [UF_DRF_OBJECT_IS_NOT_A_WELD_SYMBOL](#uf_drf_object_is_not_a_weld_symbol)
- [UF_DRF_OFFSET_INVALID_ARC](#uf_drf_offset_invalid_arc)
- [UF_DRF_OFFSET_INVALID_DISTANCE](#uf_drf_offset_invalid_distance)
- [UF_DRF_OFFSET_INVALID_OBJECT](#uf_drf_offset_invalid_object)
- [UF_DRF_ORIGIN_TYPE_UNSUPPORTED](#uf_drf_origin_type_unsupported)
- [UF_DRF_REFILE_PART_FAILURE](#uf_drf_refile_part_failure)
- [UF_DRF_RETAINED_COLOR_ORIGINAL](#uf_drf_retained_color_original)
- [UF_DRF_RETAINED_FONT_ORIGINAL](#uf_drf_retained_font_original)
- [UF_DRF_RETAINED_WIDTH_ORIGINAL](#uf_drf_retained_width_original)
- [UF_DRF_SYMBOL_INVALID_SYMBOL_NAME](#uf_drf_symbol_invalid_symbol_name)
- [UF_DRF_SYMBOL_INVALID_SYMBOL_PATH](#uf_drf_symbol_invalid_symbol_path)
- [UF_DRF_SYMBOL_IS_ALREADY_IN_EDIT](#uf_drf_symbol_is_already_in_edit)
- [UF_DRF_SYMBOL_NAME_DOES_NOT_EXIST](#uf_drf_symbol_name_does_not_exist)
- [UF_DRF_SYMBOL_NAME_EXISTS](#uf_drf_symbol_name_exists)
- [UF_DRF_SYMBOL_SELECTED_DIFFERENT_SYMBOLS](#uf_drf_symbol_selected_different_symbols)
- [UF_DRF_SYMBOL_UNSUPPORTED_SKETCH](#uf_drf_symbol_unsupported_sketch)
- [UF_DRF_SYM_INSUFFICIENT_ASSOC_OBJECTS](#uf_drf_sym_insufficient_assoc_objects)
- [UF_DRF_SYM_INVALID_INTERSECTION](#uf_drf_sym_invalid_intersection)
- [UF_DRF_TEMPLATE_ALREADY_LOADED](#uf_drf_template_already_loaded)
- [UF_DRF_TEMPLATE_NAME_NOT_FOUND](#uf_drf_template_name_not_found)
- [UF_DRF_TEMPLATE_WONT_LOAD](#uf_drf_template_wont_load)
- [UF_DRF_TOO_MANY_LEADERS](#uf_drf_too_many_leaders)
- [UF_DRF_UNITS_INVALID_CELL_SLANT_ANGLE](#uf_drf_units_invalid_cell_slant_angle)
- [UF_DRF_UNITS_INVALID_NUMERATOR_AGGERGATE](#uf_drf_units_invalid_numerator_aggergate)
- [UF_DRF_UNITS_INVALID_NUMERATOR_DEGREE](#uf_drf_units_invalid_numerator_degree)
- [UF_DRF_UNITS_INVALID_NUMERATOR_FRACTION](#uf_drf_units_invalid_numerator_fraction)
- [UF_DRF_UNITS_INVALID_NUMERATOR_MINUTES](#uf_drf_units_invalid_numerator_minutes)
- [UF_DRF_UNITS_INVALID_NUMERATOR_SECONDS](#uf_drf_units_invalid_numerator_seconds)
- [UF_DRF_UNSUPPORTED_CHARACTER_INPUT](#uf_drf_unsupported_character_input)
- [UF_DRF_UPDATE_ALL](#uf_drf_update_all)
- [UF_DRF_UPDATE_AUTO](#uf_drf_update_auto)
- [UF_DRF_UPDATE_FORCE](#uf_drf_update_force)
- [UF_DRF_UPDATE_NAMED](#uf_drf_update_named)
- [UF_DRF_WARNING](#uf_drf_warning)
- [UF_DRF_add_assortpart_to_ann](#uf_drf_add_assortpart_to_ann)
- [UF_DRF_add_compound_weld_symbol](#uf_drf_add_compound_weld_symbol)
- [UF_DRF_add_controlling_exp](#uf_drf_add_controlling_exp)
- [UF_DRF_add_symbol_to_object](#uf_drf_add_symbol_to_object)
- [UF_DRF_add_to_dimension](#uf_drf_add_to_dimension)
- [UF_DRF_align_position_e](#uf_drf_align_position_e)
- [UF_DRF_angular_suppress_zeros_e](#uf_drf_angular_suppress_zeros_e)
- [UF_DRF_angular_units_e](#uf_drf_angular_units_e)
- [UF_DRF_appended_text_location_e](#uf_drf_appended_text_location_e)
- [UF_DRF_appended_text_s](#uf_drf_appended_text_s)
- [UF_DRF_arc_info_s](#uf_drf_arc_info_s)
- [UF_DRF_arc_is_not_in_same_view](#uf_drf_arc_is_not_in_same_view)
- [UF_DRF_are_draft_objects_const](#uf_drf_are_draft_objects_const)
- [UF_DRF_area_fill_material_e](#uf_drf_area_fill_material_e)
- [UF_DRF_areafill_s](#uf_drf_areafill_s)
- [UF_DRF_arrow_display_e](#uf_drf_arrow_display_e)
- [UF_DRF_arrow_fill_type_e](#uf_drf_arrow_fill_type_e)
- [UF_DRF_arrow_info_s](#uf_drf_arrow_info_s)
- [UF_DRF_arrow_type_e](#uf_drf_arrow_type_e)
- [UF_DRF_arrowhead_and_fill_type_e](#uf_drf_arrowhead_and_fill_type_e)
- [UF_DRF_ask_ang_obj_suppress_zeros](#uf_drf_ask_ang_obj_suppress_zeros)
- [UF_DRF_ask_ang_obj_units_format](#uf_drf_ask_ang_obj_units_format)
- [UF_DRF_ask_ann_arc_seg_angles](#uf_drf_ask_ann_arc_seg_angles)
- [UF_DRF_ask_ann_data](#uf_drf_ask_ann_data)
- [UF_DRF_ask_ann_line_seg_ends](#uf_drf_ask_ann_line_seg_ends)
- [UF_DRF_ask_annotation_template](#uf_drf_ask_annotation_template)
- [UF_DRF_ask_annotation_text_box](#uf_drf_ask_annotation_text_box)
- [UF_DRF_ask_appended_text](#uf_drf_ask_appended_text)
- [UF_DRF_ask_areafill_data](#uf_drf_ask_areafill_data)
- [UF_DRF_ask_arrow_data](#uf_drf_ask_arrow_data)
- [UF_DRF_ask_assoc_exp](#uf_drf_ask_assoc_exp)
- [UF_DRF_ask_associative_origin](#uf_drf_ask_associative_origin)
- [UF_DRF_ask_associativity_data](#uf_drf_ask_associativity_data)
- [UF_DRF_ask_boundaries](#uf_drf_ask_boundaries)
- [UF_DRF_ask_callout_of_annotation](#uf_drf_ask_callout_of_annotation)
- [UF_DRF_ask_callout_row_members](#uf_drf_ask_callout_row_members)
- [UF_DRF_ask_centerline_info](#uf_drf_ask_centerline_info)
- [UF_DRF_ask_chamfer_dimension_data](#uf_drf_ask_chamfer_dimension_data)
- [UF_DRF_ask_controlling_exp](#uf_drf_ask_controlling_exp)
- [UF_DRF_ask_controlling_member_of_callout](#uf_drf_ask_controlling_member_of_callout)
- [UF_DRF_ask_custom_symbol_angle](#uf_drf_ask_custom_symbol_angle)
- [UF_DRF_ask_custom_symbol_attach_locations](#uf_drf_ask_custom_symbol_attach_locations)
- [UF_DRF_ask_custom_symbol_leader](#uf_drf_ask_custom_symbol_leader)
- [UF_DRF_ask_custom_symbol_name](#uf_drf_ask_custom_symbol_name)
- [UF_DRF_ask_custom_symbol_scale](#uf_drf_ask_custom_symbol_scale)
- [UF_DRF_ask_diameter_radius_preferences](#uf_drf_ask_diameter_radius_preferences)
- [UF_DRF_ask_dim_appended_text_space_factor](#uf_drf_ask_dim_appended_text_space_factor)
- [UF_DRF_ask_dim_dim_line_space_factor](#uf_drf_ask_dim_dim_line_space_factor)
- [UF_DRF_ask_dim_info](#uf_drf_ask_dim_info)
- [UF_DRF_ask_dim_inspection_type](#uf_drf_ask_dim_inspection_type)
- [UF_DRF_ask_dim_reference_type](#uf_drf_ask_dim_reference_type)
- [UF_DRF_ask_dim_tolerance_text_space_factor](#uf_drf_ask_dim_tolerance_text_space_factor)
- [UF_DRF_ask_dimension_preferences](#uf_drf_ask_dimension_preferences)
- [UF_DRF_ask_dimension_preferences1](#uf_drf_ask_dimension_preferences1)
- [UF_DRF_ask_dimension_set_offset](#uf_drf_ask_dimension_set_offset)
- [UF_DRF_ask_dimension_text](#uf_drf_ask_dimension_text)
- [UF_DRF_ask_dimensions_of_set](#uf_drf_ask_dimensions_of_set)
- [UF_DRF_ask_dogleg_info](#uf_drf_ask_dogleg_info)
- [UF_DRF_ask_draft_aid_text_info](#uf_drf_ask_draft_aid_text_info)
- [UF_DRF_ask_embedded_uds_font_info](#uf_drf_ask_embedded_uds_font_info)
- [UF_DRF_ask_folded_radius_info](#uf_drf_ask_folded_radius_info)
- [UF_DRF_ask_gdt_symbol_info](#uf_drf_ask_gdt_symbol_info)
- [UF_DRF_ask_hatch_fill_preferences](#uf_drf_ask_hatch_fill_preferences)
- [UF_DRF_ask_id_symbol_geometry](#uf_drf_ask_id_symbol_geometry)
- [UF_DRF_ask_id_symbol_info](#uf_drf_ask_id_symbol_info)
- [UF_DRF_ask_id_symbol_type](#uf_drf_ask_id_symbol_type)
- [UF_DRF_ask_image_data](#uf_drf_ask_image_data)
- [UF_DRF_ask_label_info](#uf_drf_ask_label_info)
- [UF_DRF_ask_lettering_preferences](#uf_drf_ask_lettering_preferences)
- [UF_DRF_ask_line_arrow_preferences](#uf_drf_ask_line_arrow_preferences)
- [UF_DRF_ask_narrow_dimension_data](#uf_drf_ask_narrow_dimension_data)
- [UF_DRF_ask_number_blocks](#uf_drf_ask_number_blocks)
- [UF_DRF_ask_number_rows_in_callout](#uf_drf_ask_number_rows_in_callout)
- [UF_DRF_ask_obj_suppress_pre_zeros](#uf_drf_ask_obj_suppress_pre_zeros)
- [UF_DRF_ask_obj_text_above_ldr](#uf_drf_ask_obj_text_above_ldr)
- [UF_DRF_ask_object_preferences](#uf_drf_ask_object_preferences)
- [UF_DRF_ask_objects_controlled_by_exp](#uf_drf_ask_objects_controlled_by_exp)
- [UF_DRF_ask_ordorigin_info](#uf_drf_ask_ordorigin_info)
- [UF_DRF_ask_origin](#uf_drf_ask_origin)
- [UF_DRF_ask_parent_of_inherited_pmi](#uf_drf_ask_parent_of_inherited_pmi)
- [UF_DRF_ask_plot_drawing_images](#uf_drf_ask_plot_drawing_images)
- [UF_DRF_ask_preferences](#uf_drf_ask_preferences)
- [UF_DRF_ask_retain_color_font_width](#uf_drf_ask_retain_color_font_width)
- [UF_DRF_ask_retained_state](#uf_drf_ask_retained_state)
- [UF_DRF_ask_sbf_file](#uf_drf_ask_sbf_file)
- [UF_DRF_ask_set_of_dimension](#uf_drf_ask_set_of_dimension)
- [UF_DRF_ask_suppress_pre_zeros](#uf_drf_ask_suppress_pre_zeros)
- [UF_DRF_ask_suppress_view_update](#uf_drf_ask_suppress_view_update)
- [UF_DRF_ask_symbol_data](#uf_drf_ask_symbol_data)
- [UF_DRF_ask_symbol_data_from_name](#uf_drf_ask_symbol_data_from_name)
- [UF_DRF_ask_symbol_mirror_and_flip](#uf_drf_ask_symbol_mirror_and_flip)
- [UF_DRF_ask_symbol_preferences](#uf_drf_ask_symbol_preferences)
- [UF_DRF_ask_symbols_used](#uf_drf_ask_symbols_used)
- [UF_DRF_ask_text_above_leader](#uf_drf_ask_text_above_leader)
- [UF_DRF_ask_text_data](#uf_drf_ask_text_data)
- [UF_DRF_ask_ud_symbol_font_info](#uf_drf_ask_ud_symbol_font_info)
- [UF_DRF_ask_uds_object_size](#uf_drf_ask_uds_object_size)
- [UF_DRF_ask_units_format_preferences](#uf_drf_ask_units_format_preferences)
- [UF_DRF_ask_vertical_note](#uf_drf_ask_vertical_note)
- [UF_DRF_ask_weld_symbol](#uf_drf_ask_weld_symbol)
- [UF_DRF_assoc_info_s](#uf_drf_assoc_info_s)
- [UF_DRF_assoc_line_type_e](#uf_drf_assoc_line_type_e)
- [UF_DRF_assoc_type_e](#uf_drf_assoc_type_e)
- [UF_DRF_associative_origin_s](#uf_drf_associative_origin_s)
- [UF_DRF_associative_origin_type_t](#uf_drf_associative_origin_type_t)
- [UF_DRF_assortpart_arc_s](#uf_drf_assortpart_arc_s)
- [UF_DRF_assortpart_arrow_s](#uf_drf_assortpart_arrow_s)
- [UF_DRF_assortpart_line_s](#uf_drf_assortpart_line_s)
- [UF_DRF_assortpart_text_s](#uf_drf_assortpart_text_s)
- [UF_DRF_begin_line_fn_t](#uf_drf_begin_line_fn_t)
- [UF_DRF_block_type_e](#uf_drf_block_type_e)
- [UF_DRF_cannot_close_xhatch_file](#uf_drf_cannot_close_xhatch_file)
- [UF_DRF_center_point](#uf_drf_center_point)
- [UF_DRF_centerline_info_s](#uf_drf_centerline_info_s)
- [UF_DRF_cfw_s](#uf_drf_cfw_s)
- [UF_DRF_chamfer_dimension_data_s](#uf_drf_chamfer_dimension_data_s)
- [UF_DRF_chamfer_dimension_form_e](#uf_drf_chamfer_dimension_form_e)
- [UF_DRF_chamfer_dimension_leader_type_e](#uf_drf_chamfer_dimension_leader_type_e)
- [UF_DRF_chamfer_dimension_stub_type_e](#uf_drf_chamfer_dimension_stub_type_e)
- [UF_DRF_chamfer_dimension_symbol_type_e](#uf_drf_chamfer_dimension_symbol_type_e)
- [UF_DRF_coincident_points](#uf_drf_coincident_points)
- [UF_DRF_collinear_points](#uf_drf_collinear_points)
- [UF_DRF_count_text_substring](#uf_drf_count_text_substring)
- [UF_DRF_cre_text_block](#uf_drf_cre_text_block)
- [UF_DRF_create_3pt_cline_fbolt](#uf_drf_create_3pt_cline_fbolt)
- [UF_DRF_create_3pt_cline_fcir](#uf_drf_create_3pt_cline_fcir)
- [UF_DRF_create_3pt_cline_pbolt](#uf_drf_create_3pt_cline_pbolt)
- [UF_DRF_create_3pt_cline_pcir](#uf_drf_create_3pt_cline_pcir)
- [UF_DRF_create_angular_dim](#uf_drf_create_angular_dim)
- [UF_DRF_create_arclength_dim](#uf_drf_create_arclength_dim)
- [UF_DRF_create_areafill](#uf_drf_create_areafill)
- [UF_DRF_create_assortpart_aid](#uf_drf_create_assortpart_aid)
- [UF_DRF_create_assortpart_dim](#uf_drf_create_assortpart_dim)
- [UF_DRF_create_block_cline](#uf_drf_create_block_cline)
- [UF_DRF_create_chamfer_dim](#uf_drf_create_chamfer_dim)
- [UF_DRF_create_concir_dim](#uf_drf_create_concir_dim)
- [UF_DRF_create_cpt_cline_fbolt](#uf_drf_create_cpt_cline_fbolt)
- [UF_DRF_create_cpt_cline_fcir](#uf_drf_create_cpt_cline_fcir)
- [UF_DRF_create_cpt_cline_pbolt](#uf_drf_create_cpt_cline_pbolt)
- [UF_DRF_create_cpt_cline_pcir](#uf_drf_create_cpt_cline_pcir)
- [UF_DRF_create_crosshatch](#uf_drf_create_crosshatch)
- [UF_DRF_create_cylindrical_dim](#uf_drf_create_cylindrical_dim)
- [UF_DRF_create_diameter_dim](#uf_drf_create_diameter_dim)
- [UF_DRF_create_foldedradius_dim](#uf_drf_create_foldedradius_dim)
- [UF_DRF_create_gdt_symbol](#uf_drf_create_gdt_symbol)
- [UF_DRF_create_gdt_symbol_with_multiple_leaders](#uf_drf_create_gdt_symbol_with_multiple_leaders)
- [UF_DRF_create_hole_dim](#uf_drf_create_hole_dim)
- [UF_DRF_create_horizontal_baseline_dimension](#uf_drf_create_horizontal_baseline_dimension)
- [UF_DRF_create_horizontal_chain_dimension](#uf_drf_create_horizontal_chain_dimension)
- [UF_DRF_create_horizontal_dim](#uf_drf_create_horizontal_dim)
- [UF_DRF_create_id_symbol](#uf_drf_create_id_symbol)
- [UF_DRF_create_image](#uf_drf_create_image)
- [UF_DRF_create_image_from_file](#uf_drf_create_image_from_file)
- [UF_DRF_create_label](#uf_drf_create_label)
- [UF_DRF_create_linear_cline](#uf_drf_create_linear_cline)
- [UF_DRF_create_non_assoc_hatch](#uf_drf_create_non_assoc_hatch)
- [UF_DRF_create_note](#uf_drf_create_note)
- [UF_DRF_create_offctrpt_cx](#uf_drf_create_offctrpt_cx)
- [UF_DRF_create_offctrpt_cy](#uf_drf_create_offctrpt_cy)
- [UF_DRF_create_offctrpt_fx](#uf_drf_create_offctrpt_fx)
- [UF_DRF_create_offctrpt_fy](#uf_drf_create_offctrpt_fy)
- [UF_DRF_create_offctrpt_nx](#uf_drf_create_offctrpt_nx)
- [UF_DRF_create_offctrpt_ny](#uf_drf_create_offctrpt_ny)
- [UF_DRF_create_offcyl_cline_obj](#uf_drf_create_offcyl_cline_obj)
- [UF_DRF_create_offcyl_cline_off](#uf_drf_create_offcyl_cline_off)
- [UF_DRF_create_orddimension](#uf_drf_create_orddimension)
- [UF_DRF_create_ordinate_dim](#uf_drf_create_ordinate_dim)
- [UF_DRF_create_ordinate_margin](#uf_drf_create_ordinate_margin)
- [UF_DRF_create_ordinate_origin](#uf_drf_create_ordinate_origin)
- [UF_DRF_create_ordmargin](#uf_drf_create_ordmargin)
- [UF_DRF_create_ordorigin](#uf_drf_create_ordorigin)
- [UF_DRF_create_parallel_dim](#uf_drf_create_parallel_dim)
- [UF_DRF_create_perpendicular_dim](#uf_drf_create_perpendicular_dim)
- [UF_DRF_create_radius_dim](#uf_drf_create_radius_dim)
- [UF_DRF_create_sbf_file](#uf_drf_create_sbf_file)
- [UF_DRF_create_side_seam](#uf_drf_create_side_seam)
- [UF_DRF_create_sym_cline](#uf_drf_create_sym_cline)
- [UF_DRF_create_symbol_font](#uf_drf_create_symbol_font)
- [UF_DRF_create_top_seam](#uf_drf_create_top_seam)
- [UF_DRF_create_vertical_baseline_dimension](#uf_drf_create_vertical_baseline_dimension)
- [UF_DRF_create_vertical_chain_dimension](#uf_drf_create_vertical_chain_dimension)
- [UF_DRF_create_vertical_dim](#uf_drf_create_vertical_dim)
- [UF_DRF_create_weld_symbol](#uf_drf_create_weld_symbol)
- [UF_DRF_create_xhatch](#uf_drf_create_xhatch)
- [UF_DRF_crosshatch_file_not_found](#uf_drf_crosshatch_file_not_found)
- [UF_DRF_custom_symbol_s](#uf_drf_custom_symbol_s)
- [UF_DRF_custom_symbol_text_s](#uf_drf_custom_symbol_text_s)
- [UF_DRF_custom_symbol_text_type_e](#uf_drf_custom_symbol_text_type_e)
- [UF_DRF_cyl_dim_with_2_margins](#uf_drf_cyl_dim_with_2_margins)
- [UF_DRF_decimal_point_character_e](#uf_drf_decimal_point_character_e)
- [UF_DRF_diameter_radius_placement_e](#uf_drf_diameter_radius_placement_e)
- [UF_DRF_diameter_radius_preferences_s](#uf_drf_diameter_radius_preferences_s)
- [UF_DRF_diameter_symbol_e](#uf_drf_diameter_symbol_e)
- [UF_DRF_dim_info_s](#uf_drf_dim_info_s)
- [UF_DRF_dim_line_info_s](#uf_drf_dim_line_info_s)
- [UF_DRF_dim_not_drawing_object](#uf_drf_dim_not_drawing_object)
- [UF_DRF_dimension_orientation_e](#uf_drf_dimension_orientation_e)
- [UF_DRF_dimension_preferences1_s](#uf_drf_dimension_preferences1_s)
- [UF_DRF_dimension_preferences_s](#uf_drf_dimension_preferences_s)
- [UF_DRF_dogleg_info_s](#uf_drf_dogleg_info_s)
- [UF_DRF_dogleg_type_e](#uf_drf_dogleg_type_e)
- [UF_DRF_draft_aid_line_s](#uf_drf_draft_aid_line_s)
- [UF_DRF_draft_aid_text_info_s](#uf_drf_draft_aid_text_info_s)
- [UF_DRF_draft_aid_text_s](#uf_drf_draft_aid_text_s)
- [UF_DRF_draw_arc_fn_t](#uf_drf_draw_arc_fn_t)
- [UF_DRF_draw_char_fn_t](#uf_drf_draw_char_fn_t)
- [UF_DRF_draw_standard_font_string_fn_t](#uf_drf_draw_standard_font_string_fn_t)
- [UF_DRF_draw_to_position_fn_t](#uf_drf_draw_to_position_fn_t)
- [UF_DRF_draw_user_symbol_fn_t](#uf_drf_draw_user_symbol_fn_t)
- [UF_DRF_drawing_is_active](#uf_drf_drawing_is_active)
- [UF_DRF_dual_dimension_format_e](#uf_drf_dual_dimension_format_e)
- [UF_DRF_edit_dim_assoc](#uf_drf_edit_dim_assoc)
- [UF_DRF_edit_weld_symbol](#uf_drf_edit_weld_symbol)
- [UF_DRF_end_line_fn_t](#uf_drf_end_line_fn_t)
- [UF_DRF_error_in_k25h7pa](#uf_drf_error_in_k25h7pa)
- [UF_DRF_extension_line_display_e](#uf_drf_extension_line_display_e)
- [UF_DRF_fill_region_fn_t](#uf_drf_fill_region_fn_t)
- [UF_DRF_first_end_point](#uf_drf_first_end_point)
- [UF_DRF_first_object_is_a_point](#uf_drf_first_object_is_a_point)
- [UF_DRF_flip_image_about_height](#uf_drf_flip_image_about_height)
- [UF_DRF_flip_image_about_width](#uf_drf_flip_image_about_width)
- [UF_DRF_folded_radius_info_s](#uf_drf_folded_radius_info_s)
- [UF_DRF_form_requires_1_object](#uf_drf_form_requires_1_object)
- [UF_DRF_form_requires_2_objects](#uf_drf_form_requires_2_objects)
- [UF_DRF_form_requires_3_or_more_objects](#uf_drf_form_requires_3_or_more_objects)
- [UF_DRF_fraction_denominator_e](#uf_drf_fraction_denominator_e)
- [UF_DRF_fraction_type_e](#uf_drf_fraction_type_e)
- [UF_DRF_frame_corner_e](#uf_drf_frame_corner_e)
- [UF_DRF_frdim](#uf_drf_frdim)
- [UF_DRF_free_appended_text](#uf_drf_free_appended_text)
- [UF_DRF_free_centerline](#uf_drf_free_centerline)
- [UF_DRF_free_comp_data](#uf_drf_free_comp_data)
- [UF_DRF_free_dimension](#uf_drf_free_dimension)
- [UF_DRF_free_dimension_preferences1](#uf_drf_free_dimension_preferences1)
- [UF_DRF_free_font](#uf_drf_free_font)
- [UF_DRF_free_gdtsymbol](#uf_drf_free_gdtsymbol)
- [UF_DRF_free_idsymbol](#uf_drf_free_idsymbol)
- [UF_DRF_free_image_data](#uf_drf_free_image_data)
- [UF_DRF_free_label](#uf_drf_free_label)
- [UF_DRF_free_leader_data](#uf_drf_free_leader_data)
- [UF_DRF_free_text](#uf_drf_free_text)
- [UF_DRF_gdt_leader_data_s](#uf_drf_gdt_leader_data_s)
- [UF_DRF_gdt_leader_s](#uf_drf_gdt_leader_s)
- [UF_DRF_gdt_symbol_info_s](#uf_drf_gdt_symbol_info_s)
- [UF_DRF_get_symbol_divider](#uf_drf_get_symbol_divider)
- [UF_DRF_get_text_bars](#uf_drf_get_text_bars)
- [UF_DRF_get_text_substring](#uf_drf_get_text_substring)
- [UF_DRF_get_xhatch_parms](#uf_drf_get_xhatch_parms)
- [UF_DRF_has_associative_origin](#uf_drf_has_associative_origin)
- [UF_DRF_hatch_fill_preferences_s](#uf_drf_hatch_fill_preferences_s)
- [UF_DRF_id_symbol_info_s](#uf_drf_id_symbol_info_s)
- [UF_DRF_id_symbol_type_e](#uf_drf_id_symbol_type_e)
- [UF_DRF_image_data_s](#uf_drf_image_data_s)
- [UF_DRF_inherit_feature_data](#uf_drf_inherit_feature_data)
- [UF_DRF_inherit_type_e](#uf_drf_inherit_type_e)
- [UF_DRF_init_associativity_data](#uf_drf_init_associativity_data)
- [UF_DRF_init_assortpart_arc](#uf_drf_init_assortpart_arc)
- [UF_DRF_init_assortpart_arrow](#uf_drf_init_assortpart_arrow)
- [UF_DRF_init_assortpart_line](#uf_drf_init_assortpart_line)
- [UF_DRF_init_assortpart_text](#uf_drf_init_assortpart_text)
- [UF_DRF_init_image_data](#uf_drf_init_image_data)
- [UF_DRF_init_line_object](#uf_drf_init_line_object)
- [UF_DRF_init_object_structure](#uf_drf_init_object_structure)
- [UF_DRF_init_symbol_create_data](#uf_drf_init_symbol_create_data)
- [UF_DRF_initialize_custom_symbol_text_data](#uf_drf_initialize_custom_symbol_text_data)
- [UF_DRF_initialize_leader_data](#uf_drf_initialize_leader_data)
- [UF_DRF_inspection_type_e](#uf_drf_inspection_type_e)
- [UF_DRF_intermediate_points_s](#uf_drf_intermediate_points_s)
- [UF_DRF_invalid_ang_dim_form](#uf_drf_invalid_ang_dim_form)
- [UF_DRF_invalid_centerline_form](#uf_drf_invalid_centerline_form)
- [UF_DRF_invalid_circular_dim_form](#uf_drf_invalid_circular_dim_form)
- [UF_DRF_invalid_fold_location](#uf_drf_invalid_fold_location)
- [UF_DRF_invalid_frame_corner](#uf_drf_invalid_frame_corner)
- [UF_DRF_invalid_id_symbol_type](#uf_drf_invalid_id_symbol_type)
- [UF_DRF_invalid_leader_attach_type](#uf_drf_invalid_leader_attach_type)
- [UF_DRF_invalid_leader_mode](#uf_drf_invalid_leader_mode)
- [UF_DRF_invalid_leader_type](#uf_drf_invalid_leader_type)
- [UF_DRF_invalid_line_assoc_type](#uf_drf_invalid_line_assoc_type)
- [UF_DRF_invalid_linear_dim_form](#uf_drf_invalid_linear_dim_form)
- [UF_DRF_invalid_number_of_bounds](#uf_drf_invalid_number_of_bounds)
- [UF_DRF_invalid_number_of_objects](#uf_drf_invalid_number_of_objects)
- [UF_DRF_invalid_object](#uf_drf_invalid_object)
- [UF_DRF_invalid_object1](#uf_drf_invalid_object1)
- [UF_DRF_invalid_object1_assoc_type](#uf_drf_invalid_object1_assoc_type)
- [UF_DRF_invalid_object1_modifier](#uf_drf_invalid_object1_modifier)
- [UF_DRF_invalid_object2](#uf_drf_invalid_object2)
- [UF_DRF_invalid_object2_assoc_type](#uf_drf_invalid_object2_assoc_type)
- [UF_DRF_invalid_object2_modifier](#uf_drf_invalid_object2_modifier)
- [UF_DRF_invalid_object_assoc_type](#uf_drf_invalid_object_assoc_type)
- [UF_DRF_invalid_object_modifier](#uf_drf_invalid_object_modifier)
- [UF_DRF_invalid_object_type_center_point](#uf_drf_invalid_object_type_center_point)
- [UF_DRF_invalid_object_type_centerline](#uf_drf_invalid_object_type_centerline)
- [UF_DRF_invalid_object_type_offset_point](#uf_drf_invalid_object_type_offset_point)
- [UF_DRF_invalid_object_view_id](#uf_drf_invalid_object_view_id)
- [UF_DRF_invalid_origin](#uf_drf_invalid_origin)
- [UF_DRF_invalid_parameter](#uf_drf_invalid_parameter)
- [UF_DRF_invalid_parameter_value](#uf_drf_invalid_parameter_value)
- [UF_DRF_invalid_view](#uf_drf_invalid_view)
- [UF_DRF_is_annotation_retained](#uf_drf_is_annotation_retained)
- [UF_DRF_is_block_centerline](#uf_drf_is_block_centerline)
- [UF_DRF_is_chamfer_dimension](#uf_drf_is_chamfer_dimension)
- [UF_DRF_is_inherited_pmi](#uf_drf_is_inherited_pmi)
- [UF_DRF_is_narrow_dimension](#uf_drf_is_narrow_dimension)
- [UF_DRF_is_object_out_of_date](#uf_drf_is_object_out_of_date)
- [UF_DRF_is_pmi_display_instance](#uf_drf_is_pmi_display_instance)
- [UF_DRF_is_sbf_symbol](#uf_drf_is_sbf_symbol)
- [UF_DRF_is_valid_width](#uf_drf_is_valid_width)
- [UF_DRF_label_info_s](#uf_drf_label_info_s)
- [UF_DRF_last_end_point](#uf_drf_last_end_point)
- [UF_DRF_leader_attach_type_e](#uf_drf_leader_attach_type_e)
- [UF_DRF_leader_data_s](#uf_drf_leader_data_s)
- [UF_DRF_leader_info_s](#uf_drf_leader_info_s)
- [UF_DRF_leader_mode_e](#uf_drf_leader_mode_e)
- [UF_DRF_leader_orientation_e](#uf_drf_leader_orientation_e)
- [UF_DRF_leader_s](#uf_drf_leader_s)
- [UF_DRF_leader_side_e](#uf_drf_leader_side_e)
- [UF_DRF_leader_type_e](#uf_drf_leader_type_e)
- [UF_DRF_lettering_preferences_s](#uf_drf_lettering_preferences_s)
- [UF_DRF_lettering_s](#uf_drf_lettering_s)
- [UF_DRF_line_arrow_preferences_s](#uf_drf_line_arrow_preferences_s)
- [UF_DRF_line_object_s](#uf_drf_line_object_s)
- [UF_DRF_line_width_e](#uf_drf_line_width_e)
- [UF_DRF_linear_units_e](#uf_drf_linear_units_e)
- [UF_DRF_margin_to_cline](#uf_drf_margin_to_cline)
- [UF_DRF_material_definition_not_found](#uf_drf_material_definition_not_found)
- [UF_DRF_model_objects_on_drawing](#uf_drf_model_objects_on_drawing)
- [UF_DRF_narrow_dimension_display_type_e](#uf_drf_narrow_dimension_display_type_e)
- [UF_DRF_narrow_dimension_info_s](#uf_drf_narrow_dimension_info_s)
- [UF_DRF_narrow_dimension_text_orientation_e](#uf_drf_narrow_dimension_text_orientation_e)
- [UF_DRF_no_boundary](#uf_drf_no_boundary)
- [UF_DRF_no_boundary_members](#uf_drf_no_boundary_members)
- [UF_DRF_no_margin_to_convert](#uf_drf_no_margin_to_convert)
- [UF_DRF_no_objects](#uf_drf_no_objects)
- [UF_DRF_no_text](#uf_drf_no_text)
- [UF_DRF_no_text_found](#uf_drf_no_text_found)
- [UF_DRF_not_a_centerline](#uf_drf_not_a_centerline)
- [UF_DRF_not_a_cylindrical_dim](#uf_drf_not_a_cylindrical_dim)
- [UF_DRF_not_a_dimension](#uf_drf_not_a_dimension)
- [UF_DRF_not_a_folded_radius_dim](#uf_drf_not_a_folded_radius_dim)
- [UF_DRF_not_a_gdt_symbol](#uf_drf_not_a_gdt_symbol)
- [UF_DRF_not_a_id_symbol](#uf_drf_not_a_id_symbol)
- [UF_DRF_not_a_label](#uf_drf_not_a_label)
- [UF_DRF_not_a_ordinate_margin](#uf_drf_not_a_ordinate_margin)
- [UF_DRF_not_an_ordinate_origin](#uf_drf_not_an_ordinate_origin)
- [UF_DRF_null_object](#uf_drf_null_object)
- [UF_DRF_null_object1](#uf_drf_null_object1)
- [UF_DRF_null_object1_structure](#uf_drf_null_object1_structure)
- [UF_DRF_null_object2](#uf_drf_null_object2)
- [UF_DRF_null_object2_structure](#uf_drf_null_object2_structure)
- [UF_DRF_null_object_structure](#uf_drf_null_object_structure)
- [UF_DRF_object_assoc_data_s](#uf_drf_object_assoc_data_s)
- [UF_DRF_object_assoc_line_type_e](#uf_drf_object_assoc_line_type_e)
- [UF_DRF_object_assoc_point_type_e](#uf_drf_object_assoc_point_type_e)
- [UF_DRF_object_is_not_a_line](#uf_drf_object_is_not_a_line)
- [UF_DRF_object_s](#uf_drf_object_s)
- [UF_DRF_objects_not_in_same_view](#uf_drf_objects_not_in_same_view)
- [UF_DRF_off_distance](#uf_drf_off_distance)
- [UF_DRF_off_position](#uf_drf_off_position)
- [UF_DRF_offset_center_point_requires_arc](#uf_drf_offset_center_point_requires_arc)
- [UF_DRF_ordarrow_line_type_e](#uf_drf_ordarrow_line_type_e)
- [UF_DRF_orddim_margin_type_e](#uf_drf_orddim_margin_type_e)
- [UF_DRF_orddimension_info_s](#uf_drf_orddimension_info_s)
- [UF_DRF_orddisp_info_s](#uf_drf_orddisp_info_s)
- [UF_DRF_ordorigin_display_type_e](#uf_drf_ordorigin_display_type_e)
- [UF_DRF_place_symbol](#uf_drf_place_symbol)
- [UF_DRF_point_coincident_with_center](#uf_drf_point_coincident_with_center)
- [UF_DRF_point_not_on_centerline](#uf_drf_point_not_on_centerline)
- [UF_DRF_pop_orientation_fn_t](#uf_drf_pop_orientation_fn_t)
- [UF_DRF_push_orientation_fn_t](#uf_drf_push_orientation_fn_t)
- [UF_DRF_quadrant_type_e](#uf_drf_quadrant_type_e)
- [UF_DRF_radius_symbol_e](#uf_drf_radius_symbol_e)
- [UF_DRF_record_draft_objects](#uf_drf_record_draft_objects)
- [UF_DRF_reference_symbol_type_e](#uf_drf_reference_symbol_type_e)
- [UF_DRF_remove_controlling_exp](#uf_drf_remove_controlling_exp)
- [UF_DRF_render_arrowhead](#uf_drf_render_arrowhead)
- [UF_DRF_render_table_s](#uf_drf_render_table_s)
- [UF_DRF_render_text](#uf_drf_render_text)
- [UF_DRF_render_text_status_t](#uf_drf_render_text_status_t)
- [UF_DRF_retained_state_e](#uf_drf_retained_state_e)
- [UF_DRF_rotate_image](#uf_drf_rotate_image)
- [UF_DRF_section_line_arrowhead_e](#uf_drf_section_line_arrowhead_e)
- [UF_DRF_section_line_display_e](#uf_drf_section_line_display_e)
- [UF_DRF_set_annotation_template](#uf_drf_set_annotation_template)
- [UF_DRF_set_appended_text](#uf_drf_set_appended_text)
- [UF_DRF_set_areafill_angle](#uf_drf_set_areafill_angle)
- [UF_DRF_set_areafill_material](#uf_drf_set_areafill_material)
- [UF_DRF_set_areafill_scale](#uf_drf_set_areafill_scale)
- [UF_DRF_set_associative_origin](#uf_drf_set_associative_origin)
- [UF_DRF_set_associativity_data](#uf_drf_set_associativity_data)
- [UF_DRF_set_cfw_fn_t](#uf_drf_set_cfw_fn_t)
- [UF_DRF_set_chamfer_dimension_data](#uf_drf_set_chamfer_dimension_data)
- [UF_DRF_set_custom_symbol_angle](#uf_drf_set_custom_symbol_angle)
- [UF_DRF_set_custom_symbol_scale](#uf_drf_set_custom_symbol_scale)
- [UF_DRF_set_customer_sbf_file](#uf_drf_set_customer_sbf_file)
- [UF_DRF_set_cyl_dim](#uf_drf_set_cyl_dim)
- [UF_DRF_set_diameter_radius_preferences](#uf_drf_set_diameter_radius_preferences)
- [UF_DRF_set_dim_appended_text_space_factor](#uf_drf_set_dim_appended_text_space_factor)
- [UF_DRF_set_dim_dim_line_space_factor](#uf_drf_set_dim_dim_line_space_factor)
- [UF_DRF_set_dim_inspection_type](#uf_drf_set_dim_inspection_type)
- [UF_DRF_set_dim_reference_type](#uf_drf_set_dim_reference_type)
- [UF_DRF_set_dim_tolerance_text_space_factor](#uf_drf_set_dim_tolerance_text_space_factor)
- [UF_DRF_set_dimension_preferences](#uf_drf_set_dimension_preferences)
- [UF_DRF_set_dimension_preferences1](#uf_drf_set_dimension_preferences1)
- [UF_DRF_set_dimension_set_offset](#uf_drf_set_dimension_set_offset)
- [UF_DRF_set_draft_common](#uf_drf_set_draft_common)
- [UF_DRF_set_hatch_fill_preferences](#uf_drf_set_hatch_fill_preferences)
- [UF_DRF_set_image_align_position](#uf_drf_set_image_align_position)
- [UF_DRF_set_image_aspect_ratio_lock](#uf_drf_set_image_aspect_ratio_lock)
- [UF_DRF_set_image_height](#uf_drf_set_image_height)
- [UF_DRF_set_image_width](#uf_drf_set_image_width)
- [UF_DRF_set_lettering_preferences](#uf_drf_set_lettering_preferences)
- [UF_DRF_set_line_arrow_preferences](#uf_drf_set_line_arrow_preferences)
- [UF_DRF_set_narrow_dimension_data](#uf_drf_set_narrow_dimension_data)
- [UF_DRF_set_object_preferences](#uf_drf_set_object_preferences)
- [UF_DRF_set_origin](#uf_drf_set_origin)
- [UF_DRF_set_plot_drawing_images](#uf_drf_set_plot_drawing_images)
- [UF_DRF_set_preferences](#uf_drf_set_preferences)
- [UF_DRF_set_retain_color_font_width](#uf_drf_set_retain_color_font_width)
- [UF_DRF_set_retained_state](#uf_drf_set_retained_state)
- [UF_DRF_set_specified_sbf_file](#uf_drf_set_specified_sbf_file)
- [UF_DRF_set_suppress_pre_zeros](#uf_drf_set_suppress_pre_zeros)
- [UF_DRF_set_suppress_view_update](#uf_drf_set_suppress_view_update)
- [UF_DRF_set_symbol_preferences](#uf_drf_set_symbol_preferences)
- [UF_DRF_set_text_above_leader](#uf_drf_set_text_above_leader)
- [UF_DRF_set_to_position_fn_t](#uf_drf_set_to_position_fn_t)
- [UF_DRF_set_tolerance](#uf_drf_set_tolerance)
- [UF_DRF_set_uds_size](#uf_drf_set_uds_size)
- [UF_DRF_set_ugdefault_sbf_file](#uf_drf_set_ugdefault_sbf_file)
- [UF_DRF_set_units_format_preferences](#uf_drf_set_units_format_preferences)
- [UF_DRF_set_vertical_note](#uf_drf_set_vertical_note)
- [UF_DRF_set_weld_symbol_standard](#uf_drf_set_weld_symbol_standard)
- [UF_DRF_set_xhatch_mat](#uf_drf_set_xhatch_mat)
- [UF_DRF_stack_align_position_t](#uf_drf_stack_align_position_t)
- [UF_DRF_stroke_info_s](#uf_drf_stroke_info_s)
- [UF_DRF_symbol_connection_s](#uf_drf_symbol_connection_s)
- [UF_DRF_symbol_connection_type_e](#uf_drf_symbol_connection_type_e)
- [UF_DRF_symbol_create_data_s](#uf_drf_symbol_create_data_s)
- [UF_DRF_symbol_data_s](#uf_drf_symbol_data_s)
- [UF_DRF_symbol_instance_s](#uf_drf_symbol_instance_s)
- [UF_DRF_symbol_preferences_s](#uf_drf_symbol_preferences_s)
- [UF_DRF_tag_is_null](#uf_drf_tag_is_null)
- [UF_DRF_text_above_leader_e](#uf_drf_text_above_leader_e)
- [UF_DRF_text_arrow_placement_e](#uf_drf_text_arrow_placement_e)
- [UF_DRF_text_cfw_s](#uf_drf_text_cfw_s)
- [UF_DRF_text_just_e](#uf_drf_text_just_e)
- [UF_DRF_text_s](#uf_drf_text_s)
- [UF_DRF_text_type_e](#uf_drf_text_type_e)
- [UF_DRF_thru_3_points](#uf_drf_thru_3_points)
- [UF_DRF_tolerance_placement_e](#uf_drf_tolerance_placement_e)
- [UF_DRF_tolerance_type_e](#uf_drf_tolerance_type_e)
- [UF_DRF_too_many_boundaries](#uf_drf_too_many_boundaries)
- [UF_DRF_too_many_characters_in_line](#uf_drf_too_many_characters_in_line)
- [UF_DRF_too_many_characters_in_text](#uf_drf_too_many_characters_in_text)
- [UF_DRF_too_many_objects](#uf_drf_too_many_objects)
- [UF_DRF_transfer_to_drawing](#uf_drf_transfer_to_drawing)
- [UF_DRF_trim_dim_line_style_e](#uf_drf_trim_dim_line_style_e)
- [UF_DRF_two_points_in_a_row](#uf_drf_two_points_in_a_row)
- [UF_DRF_ud_symbol_data_not_found](#uf_drf_ud_symbol_data_not_found)
- [UF_DRF_ud_symbol_font_info_s](#uf_drf_ud_symbol_font_info_s)
- [UF_DRF_ud_symbol_pen_type_e](#uf_drf_ud_symbol_pen_type_e)
- [UF_DRF_uds_size_s](#uf_drf_uds_size_s)
- [UF_DRF_uds_size_type_e](#uf_drf_uds_size_type_e)
- [UF_DRF_unable_to_create_crosshatching](#uf_drf_unable_to_create_crosshatching)
- [UF_DRF_units_format_preferences_s](#uf_drf_units_format_preferences_s)
- [UF_DRF_unknown_error](#uf_drf_unknown_error)
- [UF_DRF_unrecoverable_error](#uf_drf_unrecoverable_error)
- [UF_DRF_update_views](#uf_drf_update_views)
- [UF_DRF_valid_cline_form_e](#uf_drf_valid_cline_form_e)
- [UF_DRF_valid_material_e](#uf_drf_valid_material_e)
- [UF_DRF_vertical_text_just_e](#uf_drf_vertical_text_just_e)
- [UF_DRF_weld_contour_types_e](#uf_drf_weld_contour_types_e)
- [UF_DRF_weld_finish_types_e](#uf_drf_weld_finish_types_e)
- [UF_DRF_weld_ident_line_type_e](#uf_drf_weld_ident_line_type_e)
- [UF_DRF_weld_size_code_e](#uf_drf_weld_size_code_e)
- [UF_DRF_weld_sym_ext_type_e](#uf_drf_weld_sym_ext_type_e)
- [UF_DRF_weld_sym_info_s](#uf_drf_weld_sym_info_s)
- [UF_DRF_weld_symbol_types_e](#uf_drf_weld_symbol_types_e)
- [UF_DRF_weld_symbols_s](#uf_drf_weld_symbols_s)
- [uf_drf.h](#uf_drf.h)
- [uf_drf_errors.h](#uf_drf_errors.h)
- [uf_drf_types.h](#uf_drf_types.h)

---

## UF_DRF #Defines

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/contents.html#defines


---

## UF_DRF Callbacks

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/contents.html#callbacks


---

## UF_DRF Enumerations

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/contents.html#enumerations


---

## UF_DRF Files

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/contents.html#files


---

## UF_DRF Functions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/contents.html#functions


---

## UF_DRF Structures

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/contents.html#structures


---

## UF_DRF_BAD_SYMBOL_TEXT_OBJECT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_BAD_SYMBOL_TEXT_OBJECT


---

## UF_DRF_CANNOT_ATTACH_CANT_FIND_NORMAL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CANNOT_ATTACH_CANT_FIND_NORMAL


---

## UF_DRF_CANNOT_ATTACH_TO_DIM_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CANNOT_ATTACH_TO_DIM_TYPE


---

## UF_DRF_CANNOT_ATTACH_TO_DISASSOC_DMV_FACET_REP

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CANNOT_ATTACH_TO_DISASSOC_DMV_FACET_REP


---

## UF_DRF_CANNOT_ATTACH_TO_LEADER_WITHOUT_ARROWS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CANNOT_ATTACH_TO_LEADER_WITHOUT_ARROWS


---

## UF_DRF_CANNOT_ATTACH_TO_NON_FACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CANNOT_ATTACH_TO_NON_FACE


---

## UF_DRF_CANNOT_ATTACH_TO_NON_LINEAR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CANNOT_ATTACH_TO_NON_LINEAR


---

## UF_DRF_CANNOT_ATTACH_TO_OBJ_IN_DIFF_VIEW

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CANNOT_ATTACH_TO_OBJ_IN_DIFF_VIEW


---

## UF_DRF_CANNOT_ATTACH_TO_OCC

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CANNOT_ATTACH_TO_OCC


---

## UF_DRF_CANNOT_ATTACH_TO_RETAINED_ANNOT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CANNOT_ATTACH_TO_RETAINED_ANNOT


---

## UF_DRF_CANNOT_ATTACH_TO_VIEW_LABEL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CANNOT_ATTACH_TO_VIEW_LABEL


---

## UF_DRF_CANNOT_ATTACH_TO_WELD_SYMBOL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CANNOT_ATTACH_TO_WELD_SYMBOL


---

## UF_DRF_CANNOT_CHANGE_LEADER_POS_PARAM

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CANNOT_CHANGE_LEADER_POS_PARAM


---

## UF_DRF_CANNOT_DISPLAY_ALL_AROUND_ALL_OVER_CIRCLE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CANNOT_DISPLAY_ALL_AROUND_ALL_OVER_CIRCLE


---

## UF_DRF_CANNOT_DISPLAY_ALL_AROUND_CIRCLE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CANNOT_DISPLAY_ALL_AROUND_CIRCLE


---

## UF_DRF_CANNOT_DISPLAY_ALL_OVER_CIRCLE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CANNOT_DISPLAY_ALL_OVER_CIRCLE


---

## UF_DRF_CANNOT_PROCESS_SYMBOL_FONT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CANNOT_PROCESS_SYMBOL_FONT


---

## UF_DRF_CANT_REMOVE_LAST_LEADER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CANT_REMOVE_LAST_LEADER


---

## UF_DRF_CLINE_ALL_POINTS_NOT_COLLINEAR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_ALL_POINTS_NOT_COLLINEAR


---

## UF_DRF_CLINE_ANGLE_OUT_OF_RANGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_ANGLE_OUT_OF_RANGE


---

## UF_DRF_CLINE_AUTO_INVALID_CYL_EXTENSION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_AUTO_INVALID_CYL_EXTENSION


---

## UF_DRF_CLINE_AUTO_INVALID_VIEW

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_AUTO_INVALID_VIEW


---

## UF_DRF_CLINE_AUTO_NO_VIEWS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_AUTO_NO_VIEWS


---

## UF_DRF_CLINE_DUPLICATE_POINTS_SELECTED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_DUPLICATE_POINTS_SELECTED


---

## UF_DRF_CLINE_INCORRECT_NUM_ASSOC_OBJECTS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_INCORRECT_NUM_ASSOC_OBJECTS


---

## UF_DRF_CLINE_INSUFFICIENT_INPUT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_INSUFFICIENT_INPUT


---

## UF_DRF_CLINE_INVALID_EXTENSION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_INVALID_EXTENSION


---

## UF_DRF_CLINE_INVALID_INPUT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_INVALID_INPUT


---

## UF_DRF_CLINE_INVALID_INTERSECTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_INVALID_INTERSECTION


---

## UF_DRF_CLINE_INVALID_OBJECT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_INVALID_OBJECT


---

## UF_DRF_CLINE_INVALID_OFFSET_DISTANCE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_INVALID_OFFSET_DISTANCE


---

## UF_DRF_CLINE_INVALID_OFFSET_OBJECT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_INVALID_OFFSET_OBJECT


---

## UF_DRF_CLINE_INVALID_RADIUS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_INVALID_RADIUS


---

## UF_DRF_CLINE_MEMORY_ALLOCATION_ERROR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_MEMORY_ALLOCATION_ERROR


---

## UF_DRF_CLINE_NON_COLLINEAR_POINTS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_NON_COLLINEAR_POINTS


---

## UF_DRF_CLINE_POINTS_COLLINEAR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_POINTS_COLLINEAR


---

## UF_DRF_CLINE_POINTS_COMPUTATION_FAILURE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_POINTS_COMPUTATION_FAILURE


---

## UF_DRF_CLINE_RETAINED_HANDLE_FOUND

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_RETAINED_HANDLE_FOUND


---

## UF_DRF_CLINE_UNABLE_TO_CREATE_ERROR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_UNABLE_TO_CREATE_ERROR


---

## UF_DRF_CLINE_UNEQUAL_RADIUS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CLINE_UNEQUAL_RADIUS


---

## UF_DRF_CMP_DWG_DIFF_FOUND

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CMP_DWG_DIFF_FOUND


---

## UF_DRF_CMP_DWG_DIFF_NOT_PERFORMED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CMP_DWG_DIFF_NOT_PERFORMED


---

## UF_DRF_COINCIDENT_ANCHOR_ORIENTATION_PT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_COINCIDENT_ANCHOR_ORIENTATION_PT


---

## UF_DRF_CONFLICT_BASIC_TOL_AND_INSPECTION_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CONFLICT_BASIC_TOL_AND_INSPECTION_TYPE


---

## UF_DRF_CONFLICT_REF_TOL_AND_REF_SYMBOL_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_CONFLICT_REF_TOL_AND_REF_SYMBOL_TYPE


---

## UF_DRF_DECIMAL_PLACES_MAX

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_DECIMAL_PLACES_MAX


---

## UF_DRF_DEFAULT_TEXT_OUT_OF_BOUNDS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_DEFAULT_TEXT_OUT_OF_BOUNDS


---

## UF_DRF_DIAMETER_RADIUS_SYMBOL_MAX_BUFSIZE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_DIAMETER_RADIUS_SYMBOL_MAX_BUFSIZE


---

## UF_DRF_DIAMETER_RADIUS_SYMBOL_MAX_LENGTH

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_DIAMETER_RADIUS_SYMBOL_MAX_LENGTH


---

## UF_DRF_DIAMETER_RADIUS_SYMBOL_MAX_NCHARS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_DIAMETER_RADIUS_SYMBOL_MAX_NCHARS


---

## UF_DRF_DIM_HAS_NO_EXT_LINES

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_DIM_HAS_NO_EXT_LINES


---

## UF_DRF_ERROR_BASE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_ERROR_BASE


---

## UF_DRF_ERROR_OPENING_CURRENT_SBF_FILE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_ERROR_OPENING_CURRENT_SBF_FILE


---

## UF_DRF_ERROR_RANGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_ERROR_RANGE


---

## UF_DRF_FILENAME_EXISTS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_FILENAME_EXISTS


---

## UF_DRF_GDT_REQUIRED_FOR_LEADER_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_GDT_REQUIRED_FOR_LEADER_TYPE


---

## UF_DRF_HAS_NO_LEADER_POS_PARAM

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_HAS_NO_LEADER_POS_PARAM


---

## UF_DRF_IMAGE_CORRUPT_OBJECT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_IMAGE_CORRUPT_OBJECT


---

## UF_DRF_INFINITE_RADIUS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INFINITE_RADIUS


---

## UF_DRF_INTERMEDIATE_PTS_NOT_ALLOWED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INTERMEDIATE_PTS_NOT_ALLOWED


---

## UF_DRF_INVALID_ALIGN_POSITION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_ALIGN_POSITION


---

## UF_DRF_INVALID_ALL_AROUND_SYMBOL_SIZE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_ALL_AROUND_SYMBOL_SIZE


---

## UF_DRF_INVALID_ANCHOR_POINT_OBJECT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_ANCHOR_POINT_OBJECT


---

## UF_DRF_INVALID_APPEARANCE_SLANT_ANGLE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_APPEARANCE_SLANT_ANGLE


---

## UF_DRF_INVALID_APPENDED_TEXT_ASPECT_RATIO

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_APPENDED_TEXT_ASPECT_RATIO


---

## UF_DRF_INVALID_APPENDED_TEXT_CHARACTER_SPACE_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_APPENDED_TEXT_CHARACTER_SPACE_FACTOR


---

## UF_DRF_INVALID_APPENDED_TEXT_LINE_SPACE_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_APPENDED_TEXT_LINE_SPACE_FACTOR


---

## UF_DRF_INVALID_APPENDED_TEXT_SIZE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_APPENDED_TEXT_SIZE


---

## UF_DRF_INVALID_AREA_FILL_MATERIAL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_AREA_FILL_MATERIAL


---

## UF_DRF_INVALID_AREA_FILL_SCALE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_AREA_FILL_SCALE


---

## UF_DRF_INVALID_ARROWHEAD_LENGTH

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_ARROWHEAD_LENGTH


---

## UF_DRF_INVALID_ARROW_DISPLAY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_ARROW_DISPLAY


---

## UF_DRF_INVALID_ARROW_FILL_STATUS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_ARROW_FILL_STATUS


---

## UF_DRF_INVALID_ARROW_OUT_LENGTH_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_ARROW_OUT_LENGTH_FACTOR


---

## UF_DRF_INVALID_ARROW_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_ARROW_TYPE


---

## UF_DRF_INVALID_ASSOCIATED_OBJECT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_ASSOCIATED_OBJECT


---

## UF_DRF_INVALID_CHAMFER_DIMENSION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_CHAMFER_DIMENSION


---

## UF_DRF_INVALID_CHAMFER_DIMENSION_FORM

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_CHAMFER_DIMENSION_FORM


---

## UF_DRF_INVALID_CHAMFER_DIMENSION_LEADER_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_CHAMFER_DIMENSION_LEADER_TYPE


---

## UF_DRF_INVALID_CHAMFER_DIMENSION_SPACE_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_CHAMFER_DIMENSION_SPACE_FACTOR


---

## UF_DRF_INVALID_CHAMFER_DIMENSION_STUB_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_CHAMFER_DIMENSION_STUB_TYPE


---

## UF_DRF_INVALID_CHAMFER_DIMENSION_SYMBOL_NAME

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_CHAMFER_DIMENSION_SYMBOL_NAME


---

## UF_DRF_INVALID_CHAMFER_DIMENSION_SYMBOL_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_CHAMFER_DIMENSION_SYMBOL_TYPE


---

## UF_DRF_INVALID_CMP_DWG_BASELINE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_CMP_DWG_BASELINE


---

## UF_DRF_INVALID_CMP_DWG_PLOT_OPTIONS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_CMP_DWG_PLOT_OPTIONS


---

## UF_DRF_INVALID_COLOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_COLOR


---

## UF_DRF_INVALID_COLUMN

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_COLUMN


---

## UF_DRF_INVALID_CROSSHATCH_FILE_FORMAT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_CROSSHATCH_FILE_FORMAT


---

## UF_DRF_INVALID_CUSTOM_SYMBOL_PIECE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_CUSTOM_SYMBOL_PIECE


---

## UF_DRF_INVALID_DATUM_LENGTH_PAST_ARROW

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DATUM_LENGTH_PAST_ARROW


---

## UF_DRF_INVALID_DATUM_TARGET_INDEX

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DATUM_TARGET_INDEX


---

## UF_DRF_INVALID_DATUM_TARGET_LABEL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DATUM_TARGET_LABEL


---

## UF_DRF_INVALID_DECIMAL_POINT_CHARACTER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DECIMAL_POINT_CHARACTER


---

## UF_DRF_INVALID_DETAIL_LEVEL_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DETAIL_LEVEL_TYPE


---

## UF_DRF_INVALID_DIAMETER_SYMBOL_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DIAMETER_SYMBOL_TYPE


---

## UF_DRF_INVALID_DIAM_RADIUS_PLACEMENT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DIAM_RADIUS_PLACEMENT


---

## UF_DRF_INVALID_DIMENSION_ANGULAR_FORMAT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DIMENSION_ANGULAR_FORMAT


---

## UF_DRF_INVALID_DIMENSION_ANGULAR_FORMAT_TOLERANCE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DIMENSION_ANGULAR_FORMAT_TOLERANCE


---

## UF_DRF_INVALID_DIMENSION_ANGULAR_SUPPRESS_ZEROS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DIMENSION_ANGULAR_SUPPRESS_ZEROS


---

## UF_DRF_INVALID_DIMENSION_ORIENTATION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DIMENSION_ORIENTATION


---

## UF_DRF_INVALID_DIMENSION_TEXT_ASPECT_RATIO

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DIMENSION_TEXT_ASPECT_RATIO


---

## UF_DRF_INVALID_DIMENSION_TEXT_CHARACTER_SPACE_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DIMENSION_TEXT_CHARACTER_SPACE_FACTOR


---

## UF_DRF_INVALID_DIMENSION_TEXT_LINE_SPACE_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DIMENSION_TEXT_LINE_SPACE_FACTOR


---

## UF_DRF_INVALID_DIMENSION_TEXT_SIZE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DIMENSION_TEXT_SIZE


---

## UF_DRF_INVALID_DIMENSION_TOL_PLACEMENT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DIMENSION_TOL_PLACEMENT


---

## UF_DRF_INVALID_DIM_APP_TEXT_SPACE_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DIM_APP_TEXT_SPACE_FACTOR


---

## UF_DRF_INVALID_DIM_DIM_LINE_SPACE_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DIM_DIM_LINE_SPACE_FACTOR


---

## UF_DRF_INVALID_DIM_INSPECTION_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DIM_INSPECTION_TYPE


---

## UF_DRF_INVALID_DIM_REFERENCE_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DIM_REFERENCE_TYPE


---

## UF_DRF_INVALID_DIM_TOL_TEXT_SPACE_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DIM_TOL_TEXT_SPACE_FACTOR


---

## UF_DRF_INVALID_DIM_TYPE_FOR_OPERATION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DIM_TYPE_FOR_OPERATION


---

## UF_DRF_INVALID_DOGLEG_ANGLE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DOGLEG_ANGLE


---

## UF_DRF_INVALID_DOGLEG_END_OFFSET

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DOGLEG_END_OFFSET


---

## UF_DRF_INVALID_DOGLEG_END_OFFSET_ZERO

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DOGLEG_END_OFFSET_ZERO


---

## UF_DRF_INVALID_DOGLEG_START_OFFSET

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DOGLEG_START_OFFSET


---

## UF_DRF_INVALID_DOT_DIAMETER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DOT_DIAMETER


---

## UF_DRF_INVALID_DUAL_DIMENSION_FORMAT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DUAL_DIMENSION_FORMAT


---

## UF_DRF_INVALID_DUAL_DIMENSION_UNITS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DUAL_DIMENSION_UNITS


---

## UF_DRF_INVALID_DUAL_FRACTION_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_DUAL_FRACTION_TYPE


---

## UF_DRF_INVALID_EXTENSION_LINE_DISPLAY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_EXTENSION_LINE_DISPLAY


---

## UF_DRF_INVALID_FABRICATION_NUMBER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_FABRICATION_NUMBER


---

## UF_DRF_INVALID_FACE_ORIENTATION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_FACE_ORIENTATION


---

## UF_DRF_INVALID_FIRST_POS_TO_EXTENSION_LINE_DISTANCE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_FIRST_POS_TO_EXTENSION_LINE_DISTANCE


---

## UF_DRF_INVALID_FOLDER_INPUT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_FOLDER_INPUT


---

## UF_DRF_INVALID_FONT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_FONT


---

## UF_DRF_INVALID_FONT_STYLE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_FONT_STYLE


---

## UF_DRF_INVALID_FRACTION_DENOMINATOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_FRACTION_DENOMINATOR


---

## UF_DRF_INVALID_GDT_FRAME_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_GDT_FRAME_FACTOR


---

## UF_DRF_INVALID_GENERAL_TEXT_ASPECT_RATIO

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_GENERAL_TEXT_ASPECT_RATIO


---

## UF_DRF_INVALID_GENERAL_TEXT_CHARACTER_SPACE_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_GENERAL_TEXT_CHARACTER_SPACE_FACTOR


---

## UF_DRF_INVALID_GENERAL_TEXT_LINE_SPACE_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_GENERAL_TEXT_LINE_SPACE_FACTOR


---

## UF_DRF_INVALID_GENERAL_TEXT_SIZE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_GENERAL_TEXT_SIZE


---

## UF_DRF_INVALID_HATCH_DISTANCE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_HATCH_DISTANCE


---

## UF_DRF_INVALID_HATCH_TOLERANCE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_HATCH_TOLERANCE


---

## UF_DRF_INVALID_HORIZ_TEXT_JUST

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_HORIZ_TEXT_JUST


---

## UF_DRF_INVALID_ID_SYMBOL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_ID_SYMBOL


---

## UF_DRF_INVALID_INHERIT_TAG

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_INHERIT_TAG


---

## UF_DRF_INVALID_INTEGER_INPUT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_INTEGER_INPUT


---

## UF_DRF_INVALID_JOG_ANGLE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_JOG_ANGLE


---

## UF_DRF_INVALID_JOG_END_OFFSET

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_JOG_END_OFFSET


---

## UF_DRF_INVALID_JOG_END_OFFSET_ZERO

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_JOG_END_OFFSET_ZERO


---

## UF_DRF_INVALID_JOG_EXTLINE_ANGLE_CONFIG

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_JOG_EXTLINE_ANGLE_CONFIG


---

## UF_DRF_INVALID_JOG_START_OFFSET

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_JOG_START_OFFSET


---

## UF_DRF_INVALID_LEADER_LOCATION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_LEADER_LOCATION


---

## UF_DRF_INVALID_LINEAR_FRACTION_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_LINEAR_FRACTION_TYPE


---

## UF_DRF_INVALID_LINEAR_UNITS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_LINEAR_UNITS


---

## UF_DRF_INVALID_LINE_PAST_ARROW_DISTANCE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_LINE_PAST_ARROW_DISTANCE


---

## UF_DRF_INVALID_NARROW_DIMENSION_DISPLAY_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_NARROW_DIMENSION_DISPLAY_TYPE


---

## UF_DRF_INVALID_NARROW_DIMENSION_LEADER_ANGLE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_NARROW_DIMENSION_LEADER_ANGLE


---

## UF_DRF_INVALID_NARROW_DIMENSION_TEXT_ORIENTATION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_NARROW_DIMENSION_TEXT_ORIENTATION


---

## UF_DRF_INVALID_NOTE_TITLE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_NOTE_TITLE


---

## UF_DRF_INVALID_NUMBER_OF_DECIMAL_PLACES

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_NUMBER_OF_DECIMAL_PLACES


---

## UF_DRF_INVALID_NUMBER_OF_FEATURES

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_NUMBER_OF_FEATURES


---

## UF_DRF_INVALID_NUMBER_OF_VIEWS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_NUMBER_OF_VIEWS


---

## UF_DRF_INVALID_OBJ_FOR_ASSORTED_PARTS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_OBJ_FOR_ASSORTED_PARTS


---

## UF_DRF_INVALID_OFFSET_CURVES

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_OFFSET_CURVES


---

## UF_DRF_INVALID_ORDINATE_MARGIN_NUMBER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_ORDINATE_MARGIN_NUMBER


---

## UF_DRF_INVALID_ORDINATE_MARGIN_SPACING

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_ORDINATE_MARGIN_SPACING


---

## UF_DRF_INVALID_PINLIST_FILTER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_PINLIST_FILTER


---

## UF_DRF_INVALID_RADIUS_SYMBOL_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_RADIUS_SYMBOL_TYPE


---

## UF_DRF_INVALID_REAL_INPUT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_REAL_INPUT


---

## UF_DRF_INVALID_ROW

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_ROW


---

## UF_DRF_INVALID_SECOND_POS_TO_EXTENSION_LINE_DISTANCE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_SECOND_POS_TO_EXTENSION_LINE_DISTANCE


---

## UF_DRF_INVALID_STACK_HORIZONTAL_ALIGNMENT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_STACK_HORIZONTAL_ALIGNMENT


---

## UF_DRF_INVALID_STACK_SPACE_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_STACK_SPACE_FACTOR


---

## UF_DRF_INVALID_STACK_VERTICAL_ALIGNMENT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_STACK_VERTICAL_ALIGNMENT


---

## UF_DRF_INVALID_STOCK_LENGTH_VALUE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_STOCK_LENGTH_VALUE


---

## UF_DRF_INVALID_STRING_INPUT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_STRING_INPUT


---

## UF_DRF_INVALID_STUB_LENGTH

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_STUB_LENGTH


---

## UF_DRF_INVALID_SYMBOL_ASPECT_RATIO

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_SYMBOL_ASPECT_RATIO


---

## UF_DRF_INVALID_SYMBOL_FONT_OBJECTS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_SYMBOL_FONT_OBJECTS


---

## UF_DRF_INVALID_SYMBOL_NAME

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_SYMBOL_NAME


---

## UF_DRF_INVALID_SYMBOL_TO_DIMENSION_TEXT_DISTANCE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_SYMBOL_TO_DIMENSION_TEXT_DISTANCE


---

## UF_DRF_INVALID_SYMBOL_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_SYMBOL_TYPE


---

## UF_DRF_INVALID_TEXT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_TEXT


---

## UF_DRF_INVALID_TEXT_ARROW_PLACEMENT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_TEXT_ARROW_PLACEMENT


---

## UF_DRF_INVALID_TEXT_OVER_LEADER_GAP_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_TEXT_OVER_LEADER_GAP_FACTOR


---

## UF_DRF_INVALID_TEXT_OVER_STUB_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_TEXT_OVER_STUB_FACTOR


---

## UF_DRF_INVALID_TEXT_PLACEMENT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_TEXT_PLACEMENT


---

## UF_DRF_INVALID_TEXT_TO_LINE_DISTANCE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_TEXT_TO_LINE_DISTANCE


---

## UF_DRF_INVALID_TOLERANCE_TEXT_ASPECT_RATIO

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_TOLERANCE_TEXT_ASPECT_RATIO


---

## UF_DRF_INVALID_TOLERANCE_TEXT_CHARACTER_SPACE_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_TOLERANCE_TEXT_CHARACTER_SPACE_FACTOR


---

## UF_DRF_INVALID_TOLERANCE_TEXT_LINE_SPACE_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_TOLERANCE_TEXT_LINE_SPACE_FACTOR


---

## UF_DRF_INVALID_TOLERANCE_TEXT_SIZE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_TOLERANCE_TEXT_SIZE


---

## UF_DRF_INVALID_TOLERANCE_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_TOLERANCE_TYPE


---

## UF_DRF_INVALID_TRIM_DIM_LINE_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_TRIM_DIM_LINE_TYPE


---

## UF_DRF_INVALID_TRUE_LENGTH_TEXT_POSITION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_TRUE_LENGTH_TEXT_POSITION


---

## UF_DRF_INVALID_USE_OF_API

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_USE_OF_API


---

## UF_DRF_INVALID_WELD_LINE_GAP

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_WELD_LINE_GAP


---

## UF_DRF_INVALID_WELD_SPACE_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_WELD_SPACE_FACTOR


---

## UF_DRF_INVALID_WELD_SYMBOL_SIZE_FACTOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_WELD_SYMBOL_SIZE_FACTOR


---

## UF_DRF_INVALID_WELD_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_WELD_TYPE


---

## UF_DRF_INVALID_WIDTH

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_INVALID_WIDTH


---

## UF_DRF_LEADER_HAS_NO_CONNECTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_LEADER_HAS_NO_CONNECTION


---

## UF_DRF_LEADER_IS_REQD

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_LEADER_IS_REQD


---

## UF_DRF_LEADER_MAX_INT_POINTS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_LEADER_MAX_INT_POINTS


---

## UF_DRF_LEADER_MAX_LEADERS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_LEADER_MAX_LEADERS


---

## UF_DRF_LEADER_REQUIRED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_LEADER_REQUIRED


---

## UF_DRF_LIMIT_FIT_INVALID_ASSY_DISPLAY_STYLE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_LIMIT_FIT_INVALID_ASSY_DISPLAY_STYLE


---

## UF_DRF_LIMIT_FIT_INVALID_DEVIATION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_LIMIT_FIT_INVALID_DEVIATION


---

## UF_DRF_LIMIT_FIT_INVALID_DISPLAY_STYLE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_LIMIT_FIT_INVALID_DISPLAY_STYLE


---

## UF_DRF_LIMIT_FIT_INVALID_GRADE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_LIMIT_FIT_INVALID_GRADE


---

## UF_DRF_LIMIT_FIT_INVALID_HOLE_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_LIMIT_FIT_INVALID_HOLE_TYPE


---

## UF_DRF_LIMIT_FIT_INVALID_PAREN_STYLE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_LIMIT_FIT_INVALID_PAREN_STYLE


---

## UF_DRF_LIMIT_FIT_INVALID_SEPARATOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_LIMIT_FIT_INVALID_SEPARATOR


---

## UF_DRF_LIMIT_FIT_INVALID_SPLIT_BY_DIMLINE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_LIMIT_FIT_INVALID_SPLIT_BY_DIMLINE


---

## UF_DRF_LIMIT_FIT_INVALID_TOL_ALIGNMENT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_LIMIT_FIT_INVALID_TOL_ALIGNMENT


---

## UF_DRF_MAP_DRF_LINE_WIDTH_TO_OBJ_WIDTH

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_MAP_DRF_LINE_WIDTH_TO_OBJ_WIDTH


---

## UF_DRF_MAP_OBJ_WIDTH_TO_DRF_LINE_WIDTH

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_MAP_OBJ_WIDTH_TO_DRF_LINE_WIDTH


---

## UF_DRF_MAX_FONT_BUFSIZE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_MAX_FONT_BUFSIZE


---

## UF_DRF_MAX_FONT_LEN

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf.html#UF_DRF_MAX_FONT_LEN


---

## UF_DRF_MAX_FONT_NCHARS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_MAX_FONT_NCHARS


---

## UF_DRF_MAX_HATCH_FILE_NAME_LEN

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_MAX_HATCH_FILE_NAME_LEN


---

## UF_DRF_MAX_HATCH_MATERIAL_NAME

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_MAX_HATCH_MATERIAL_NAME


---

## UF_DRF_MAX_HATCH_MATERIAL_NAME_BUFSIZE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_MAX_HATCH_MATERIAL_NAME_BUFSIZE


---

## UF_DRF_MAX_HATCH_MATERIAL_NAME_NCHARS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_MAX_HATCH_MATERIAL_NAME_NCHARS


---

## UF_DRF_MIN_NEW_WIDTH

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_MIN_NEW_WIDTH


---

## UF_DRF_MORE_THAN_7_LEADERS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_MORE_THAN_7_LEADERS


---

## UF_DRF_MULTIPLE_PLISTS_NOT_ALLOWED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_MULTIPLE_PLISTS_NOT_ALLOWED


---

## UF_DRF_NOT_A_CUSTOM_SYMBOL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_NOT_A_CUSTOM_SYMBOL


---

## UF_DRF_NOT_DRAFTING_OBJECT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_NOT_DRAFTING_OBJECT


---

## UF_DRF_NOT_VALID_FOR_GB_DAT_DIM

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_NOT_VALID_FOR_GB_DAT_DIM


---

## UF_DRF_NOT_VALID_GDT_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_NOT_VALID_GDT_TYPE


---

## UF_DRF_NOT_VALID_LEADER_ATTACH_OBJ

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_NOT_VALID_LEADER_ATTACH_OBJ


---

## UF_DRF_NO_ERRORS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_NO_ERRORS


---

## UF_DRF_NO_SBF_FILE_NAME

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_NO_SBF_FILE_NAME


---

## UF_DRF_NO_TEMPLATE_ENV_VAR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_NO_TEMPLATE_ENV_VAR


---

## UF_DRF_NO_VALID_COMPONENT_FOUND

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_NO_VALID_COMPONENT_FOUND


---

## UF_DRF_OBJECTS_ARE_NOT_CONSTANT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_OBJECTS_ARE_NOT_CONSTANT


---

## UF_DRF_OBJECT_IS_NOT_A_WELD_SYMBOL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_OBJECT_IS_NOT_A_WELD_SYMBOL


---

## UF_DRF_OFFSET_INVALID_ARC

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_OFFSET_INVALID_ARC


---

## UF_DRF_OFFSET_INVALID_DISTANCE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_OFFSET_INVALID_DISTANCE


---

## UF_DRF_OFFSET_INVALID_OBJECT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_OFFSET_INVALID_OBJECT


---

## UF_DRF_ORIGIN_TYPE_UNSUPPORTED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_ORIGIN_TYPE_UNSUPPORTED


---

## UF_DRF_REFILE_PART_FAILURE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_REFILE_PART_FAILURE


---

## UF_DRF_RETAINED_COLOR_ORIGINAL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_RETAINED_COLOR_ORIGINAL


---

## UF_DRF_RETAINED_FONT_ORIGINAL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_RETAINED_FONT_ORIGINAL


---

## UF_DRF_RETAINED_WIDTH_ORIGINAL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_RETAINED_WIDTH_ORIGINAL


---

## UF_DRF_SYMBOL_INVALID_SYMBOL_NAME

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_SYMBOL_INVALID_SYMBOL_NAME


---

## UF_DRF_SYMBOL_INVALID_SYMBOL_PATH

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_SYMBOL_INVALID_SYMBOL_PATH


---

## UF_DRF_SYMBOL_IS_ALREADY_IN_EDIT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_SYMBOL_IS_ALREADY_IN_EDIT


---

## UF_DRF_SYMBOL_NAME_DOES_NOT_EXIST

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_SYMBOL_NAME_DOES_NOT_EXIST


---

## UF_DRF_SYMBOL_NAME_EXISTS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_SYMBOL_NAME_EXISTS


---

## UF_DRF_SYMBOL_SELECTED_DIFFERENT_SYMBOLS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_SYMBOL_SELECTED_DIFFERENT_SYMBOLS


---

## UF_DRF_SYMBOL_UNSUPPORTED_SKETCH

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_SYMBOL_UNSUPPORTED_SKETCH


---

## UF_DRF_SYM_INSUFFICIENT_ASSOC_OBJECTS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_SYM_INSUFFICIENT_ASSOC_OBJECTS


---

## UF_DRF_SYM_INVALID_INTERSECTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_SYM_INVALID_INTERSECTION


---

## UF_DRF_TEMPLATE_ALREADY_LOADED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_TEMPLATE_ALREADY_LOADED


---

## UF_DRF_TEMPLATE_NAME_NOT_FOUND

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_TEMPLATE_NAME_NOT_FOUND


---

## UF_DRF_TEMPLATE_WONT_LOAD

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_TEMPLATE_WONT_LOAD


---

## UF_DRF_TOO_MANY_LEADERS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_TOO_MANY_LEADERS


---

## UF_DRF_UNITS_INVALID_CELL_SLANT_ANGLE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_UNITS_INVALID_CELL_SLANT_ANGLE


---

## UF_DRF_UNITS_INVALID_NUMERATOR_AGGERGATE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_UNITS_INVALID_NUMERATOR_AGGERGATE


---

## UF_DRF_UNITS_INVALID_NUMERATOR_DEGREE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_UNITS_INVALID_NUMERATOR_DEGREE


---

## UF_DRF_UNITS_INVALID_NUMERATOR_FRACTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_UNITS_INVALID_NUMERATOR_FRACTION


---

## UF_DRF_UNITS_INVALID_NUMERATOR_MINUTES

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_UNITS_INVALID_NUMERATOR_MINUTES


---

## UF_DRF_UNITS_INVALID_NUMERATOR_SECONDS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_UNITS_INVALID_NUMERATOR_SECONDS


---

## UF_DRF_UNSUPPORTED_CHARACTER_INPUT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_UNSUPPORTED_CHARACTER_INPUT


---

## UF_DRF_UPDATE_ALL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf.html#UF_DRF_UPDATE_ALL


---

## UF_DRF_UPDATE_AUTO

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf.html#UF_DRF_UPDATE_AUTO


---

## UF_DRF_UPDATE_FORCE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf.html#UF_DRF_UPDATE_FORCE


---

## UF_DRF_UPDATE_NAMED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf.html#UF_DRF_UPDATE_NAMED


---

## UF_DRF_WARNING

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_WARNING


---

## UF_DRF_add_assortpart_to_ann

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_add_assortpart_to_ann


---

## UF_DRF_add_compound_weld_symbol

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_add_compound_weld_symbol


---

## UF_DRF_add_controlling_exp

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_add_controlling_exp


---

## UF_DRF_add_symbol_to_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_add_symbol_to_object


---

## UF_DRF_add_to_dimension

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_add_to_dimension


---

## UF_DRF_align_position_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_align_position_e


---

## UF_DRF_angular_suppress_zeros_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_angular_suppress_zeros_e


---

## UF_DRF_angular_units_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_angular_units_e


---

## UF_DRF_appended_text_location_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_appended_text_location_e


---

## UF_DRF_appended_text_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_appended_text_s.html


---

## UF_DRF_arc_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_arc_info_s.html


---

## UF_DRF_arc_is_not_in_same_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_arc_is_not_in_same_view


---

## UF_DRF_are_draft_objects_const

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_are_draft_objects_const


---

## UF_DRF_area_fill_material_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_area_fill_material_e


---

## UF_DRF_areafill_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_areafill_s.html


---

## UF_DRF_arrow_display_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_arrow_display_e


---

## UF_DRF_arrow_fill_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_arrow_fill_type_e


---

## UF_DRF_arrow_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_arrow_info_s.html


---

## UF_DRF_arrow_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_arrow_type_e


---

## UF_DRF_arrowhead_and_fill_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_arrowhead_and_fill_type_e


---

## UF_DRF_ask_ang_obj_suppress_zeros

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_ang_obj_suppress_zeros


---

## UF_DRF_ask_ang_obj_units_format

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_ang_obj_units_format


---

## UF_DRF_ask_ann_arc_seg_angles

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_ann_arc_seg_angles


---

## UF_DRF_ask_ann_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_ann_data


---

## UF_DRF_ask_ann_line_seg_ends

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_ann_line_seg_ends


---

## UF_DRF_ask_annotation_template

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_annotation_template


---

## UF_DRF_ask_annotation_text_box

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_annotation_text_box


---

## UF_DRF_ask_appended_text

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_appended_text


---

## UF_DRF_ask_areafill_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_areafill_data


---

## UF_DRF_ask_arrow_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_arrow_data


---

## UF_DRF_ask_assoc_exp

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_assoc_exp


---

## UF_DRF_ask_associative_origin

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_associative_origin


---

## UF_DRF_ask_associativity_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_associativity_data


---

## UF_DRF_ask_boundaries

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_boundaries


---

## UF_DRF_ask_callout_of_annotation

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_callout_of_annotation


---

## UF_DRF_ask_callout_row_members

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_callout_row_members


---

## UF_DRF_ask_centerline_info

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_centerline_info


---

## UF_DRF_ask_chamfer_dimension_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_chamfer_dimension_data


---

## UF_DRF_ask_controlling_exp

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_controlling_exp


---

## UF_DRF_ask_controlling_member_of_callout

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_controlling_member_of_callout


---

## UF_DRF_ask_custom_symbol_angle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_custom_symbol_angle


---

## UF_DRF_ask_custom_symbol_attach_locations

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_custom_symbol_attach_locations


---

## UF_DRF_ask_custom_symbol_leader

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_custom_symbol_leader


---

## UF_DRF_ask_custom_symbol_name

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_custom_symbol_name


---

## UF_DRF_ask_custom_symbol_scale

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_custom_symbol_scale


---

## UF_DRF_ask_diameter_radius_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_diameter_radius_preferences


---

## UF_DRF_ask_dim_appended_text_space_factor

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_dim_appended_text_space_factor


---

## UF_DRF_ask_dim_dim_line_space_factor

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_dim_dim_line_space_factor


---

## UF_DRF_ask_dim_info

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_dim_info


---

## UF_DRF_ask_dim_inspection_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_dim_inspection_type


---

## UF_DRF_ask_dim_reference_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_dim_reference_type


---

## UF_DRF_ask_dim_tolerance_text_space_factor

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_dim_tolerance_text_space_factor


---

## UF_DRF_ask_dimension_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_dimension_preferences


---

## UF_DRF_ask_dimension_preferences1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_dimension_preferences1


---

## UF_DRF_ask_dimension_set_offset

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_dimension_set_offset


---

## UF_DRF_ask_dimension_text

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_dimension_text


---

## UF_DRF_ask_dimensions_of_set

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_dimensions_of_set


---

## UF_DRF_ask_dogleg_info

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_dogleg_info


---

## UF_DRF_ask_draft_aid_text_info

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_draft_aid_text_info


---

## UF_DRF_ask_embedded_uds_font_info

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_embedded_uds_font_info


---

## UF_DRF_ask_folded_radius_info

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_folded_radius_info


---

## UF_DRF_ask_gdt_symbol_info

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_gdt_symbol_info


---

## UF_DRF_ask_hatch_fill_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_hatch_fill_preferences


---

## UF_DRF_ask_id_symbol_geometry

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_id_symbol_geometry


---

## UF_DRF_ask_id_symbol_info

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_id_symbol_info


---

## UF_DRF_ask_id_symbol_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_id_symbol_type


---

## UF_DRF_ask_image_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_image_data


---

## UF_DRF_ask_label_info

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_label_info


---

## UF_DRF_ask_lettering_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_lettering_preferences


---

## UF_DRF_ask_line_arrow_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_line_arrow_preferences


---

## UF_DRF_ask_narrow_dimension_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_narrow_dimension_data


---

## UF_DRF_ask_number_blocks

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_number_blocks


---

## UF_DRF_ask_number_rows_in_callout

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_number_rows_in_callout


---

## UF_DRF_ask_obj_suppress_pre_zeros

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_obj_suppress_pre_zeros


---

## UF_DRF_ask_obj_text_above_ldr

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_obj_text_above_ldr


---

## UF_DRF_ask_object_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_object_preferences


---

## UF_DRF_ask_objects_controlled_by_exp

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_objects_controlled_by_exp


---

## UF_DRF_ask_ordorigin_info

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_ordorigin_info


---

## UF_DRF_ask_origin

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_origin


---

## UF_DRF_ask_parent_of_inherited_pmi

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_parent_of_inherited_pmi


---

## UF_DRF_ask_plot_drawing_images

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_plot_drawing_images


---

## UF_DRF_ask_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_preferences


---

## UF_DRF_ask_retain_color_font_width

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_retain_color_font_width


---

## UF_DRF_ask_retained_state

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_retained_state


---

## UF_DRF_ask_sbf_file

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_sbf_file


---

## UF_DRF_ask_set_of_dimension

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_set_of_dimension


---

## UF_DRF_ask_suppress_pre_zeros

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_suppress_pre_zeros


---

## UF_DRF_ask_suppress_view_update

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_suppress_view_update


---

## UF_DRF_ask_symbol_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_symbol_data


---

## UF_DRF_ask_symbol_data_from_name

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_symbol_data_from_name


---

## UF_DRF_ask_symbol_mirror_and_flip

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_symbol_mirror_and_flip


---

## UF_DRF_ask_symbol_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_symbol_preferences


---

## UF_DRF_ask_symbols_used

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_symbols_used


---

## UF_DRF_ask_text_above_leader

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_text_above_leader


---

## UF_DRF_ask_text_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_text_data


---

## UF_DRF_ask_ud_symbol_font_info

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_ud_symbol_font_info


---

## UF_DRF_ask_uds_object_size

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_uds_object_size


---

## UF_DRF_ask_units_format_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_units_format_preferences


---

## UF_DRF_ask_vertical_note

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_vertical_note


---

## UF_DRF_ask_weld_symbol

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_ask_weld_symbol


---

## UF_DRF_assoc_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_assoc_info_s.html


---

## UF_DRF_assoc_line_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_assoc_line_type_e


---

## UF_DRF_assoc_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_assoc_type_e


---

## UF_DRF_associative_origin_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_associative_origin_s.html


---

## UF_DRF_associative_origin_type_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_associative_origin_type_t


---

## UF_DRF_assortpart_arc_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_assortpart_arc_s.html


---

## UF_DRF_assortpart_arrow_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_assortpart_arrow_s.html


---

## UF_DRF_assortpart_line_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_assortpart_line_s.html


---

## UF_DRF_assortpart_text_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_assortpart_text_s.html


---

## UF_DRF_begin_line_fn_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/callback.html#UF_DRF_begin_line_fn_t


---

## UF_DRF_block_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_block_type_e


---

## UF_DRF_cannot_close_xhatch_file

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_cannot_close_xhatch_file


---

## UF_DRF_center_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_center_point


---

## UF_DRF_centerline_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_centerline_info_s.html


---

## UF_DRF_cfw_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_cfw_s.html


---

## UF_DRF_chamfer_dimension_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_chamfer_dimension_data_s.html


---

## UF_DRF_chamfer_dimension_form_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_chamfer_dimension_form_e


---

## UF_DRF_chamfer_dimension_leader_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_chamfer_dimension_leader_type_e


---

## UF_DRF_chamfer_dimension_stub_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_chamfer_dimension_stub_type_e


---

## UF_DRF_chamfer_dimension_symbol_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_chamfer_dimension_symbol_type_e


---

## UF_DRF_coincident_points

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_coincident_points


---

## UF_DRF_collinear_points

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_collinear_points


---

## UF_DRF_count_text_substring

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_count_text_substring


---

## UF_DRF_cre_text_block

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_cre_text_block


---

## UF_DRF_create_3pt_cline_fbolt

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_3pt_cline_fbolt


---

## UF_DRF_create_3pt_cline_fcir

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_3pt_cline_fcir


---

## UF_DRF_create_3pt_cline_pbolt

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_3pt_cline_pbolt


---

## UF_DRF_create_3pt_cline_pcir

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_3pt_cline_pcir


---

## UF_DRF_create_angular_dim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_angular_dim


---

## UF_DRF_create_arclength_dim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_arclength_dim


---

## UF_DRF_create_areafill

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_areafill


---

## UF_DRF_create_assortpart_aid

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_assortpart_aid


---

## UF_DRF_create_assortpart_dim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_assortpart_dim


---

## UF_DRF_create_block_cline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_block_cline


---

## UF_DRF_create_chamfer_dim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_chamfer_dim


---

## UF_DRF_create_concir_dim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_concir_dim


---

## UF_DRF_create_cpt_cline_fbolt

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_cpt_cline_fbolt


---

## UF_DRF_create_cpt_cline_fcir

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_cpt_cline_fcir


---

## UF_DRF_create_cpt_cline_pbolt

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_cpt_cline_pbolt


---

## UF_DRF_create_cpt_cline_pcir

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_cpt_cline_pcir


---

## UF_DRF_create_crosshatch

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_crosshatch


---

## UF_DRF_create_cylindrical_dim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_cylindrical_dim


---

## UF_DRF_create_diameter_dim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_diameter_dim


---

## UF_DRF_create_foldedradius_dim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_foldedradius_dim


---

## UF_DRF_create_gdt_symbol

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_gdt_symbol


---

## UF_DRF_create_gdt_symbol_with_multiple_leaders

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_gdt_symbol_with_multiple_leaders


---

## UF_DRF_create_hole_dim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_hole_dim


---

## UF_DRF_create_horizontal_baseline_dimension

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_horizontal_baseline_dimension


---

## UF_DRF_create_horizontal_chain_dimension

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_horizontal_chain_dimension


---

## UF_DRF_create_horizontal_dim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_horizontal_dim


---

## UF_DRF_create_id_symbol

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_id_symbol


---

## UF_DRF_create_image

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_image


---

## UF_DRF_create_image_from_file

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_image_from_file


---

## UF_DRF_create_label

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_label


---

## UF_DRF_create_linear_cline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_linear_cline


---

## UF_DRF_create_non_assoc_hatch

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_non_assoc_hatch


---

## UF_DRF_create_note

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_note


---

## UF_DRF_create_offctrpt_cx

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_offctrpt_cx


---

## UF_DRF_create_offctrpt_cy

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_offctrpt_cy


---

## UF_DRF_create_offctrpt_fx

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_offctrpt_fx


---

## UF_DRF_create_offctrpt_fy

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_offctrpt_fy


---

## UF_DRF_create_offctrpt_nx

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_offctrpt_nx


---

## UF_DRF_create_offctrpt_ny

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_offctrpt_ny


---

## UF_DRF_create_offcyl_cline_obj

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_offcyl_cline_obj


---

## UF_DRF_create_offcyl_cline_off

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_offcyl_cline_off


---

## UF_DRF_create_orddimension

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_orddimension


---

## UF_DRF_create_ordinate_dim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_ordinate_dim


---

## UF_DRF_create_ordinate_margin

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_ordinate_margin


---

## UF_DRF_create_ordinate_origin

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_ordinate_origin


---

## UF_DRF_create_ordmargin

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_ordmargin


---

## UF_DRF_create_ordorigin

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_ordorigin


---

## UF_DRF_create_parallel_dim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_parallel_dim


---

## UF_DRF_create_perpendicular_dim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_perpendicular_dim


---

## UF_DRF_create_radius_dim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_radius_dim


---

## UF_DRF_create_sbf_file

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_sbf_file


---

## UF_DRF_create_side_seam

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_side_seam


---

## UF_DRF_create_sym_cline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_sym_cline


---

## UF_DRF_create_symbol_font

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_symbol_font


---

## UF_DRF_create_top_seam

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_top_seam


---

## UF_DRF_create_vertical_baseline_dimension

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_vertical_baseline_dimension


---

## UF_DRF_create_vertical_chain_dimension

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_vertical_chain_dimension


---

## UF_DRF_create_vertical_dim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_vertical_dim


---

## UF_DRF_create_weld_symbol

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_weld_symbol


---

## UF_DRF_create_xhatch

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_create_xhatch


---

## UF_DRF_crosshatch_file_not_found

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_crosshatch_file_not_found


---

## UF_DRF_custom_symbol_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_custom_symbol_s.html


---

## UF_DRF_custom_symbol_text_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_custom_symbol_text_s.html


---

## UF_DRF_custom_symbol_text_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_custom_symbol_text_type_e


---

## UF_DRF_cyl_dim_with_2_margins

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_cyl_dim_with_2_margins


---

## UF_DRF_decimal_point_character_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_decimal_point_character_e


---

## UF_DRF_diameter_radius_placement_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_diameter_radius_placement_e


---

## UF_DRF_diameter_radius_preferences_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_diameter_radius_preferences_s.html


---

## UF_DRF_diameter_symbol_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_diameter_symbol_e


---

## UF_DRF_dim_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_dim_info_s.html


---

## UF_DRF_dim_line_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_dim_line_info_s.html


---

## UF_DRF_dim_not_drawing_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_dim_not_drawing_object


---

## UF_DRF_dimension_orientation_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_dimension_orientation_e


---

## UF_DRF_dimension_preferences1_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_dimension_preferences1_s.html


---

## UF_DRF_dimension_preferences_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_dimension_preferences_s.html


---

## UF_DRF_dogleg_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_dogleg_info_s.html


---

## UF_DRF_dogleg_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_dogleg_type_e


---

## UF_DRF_draft_aid_line_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_draft_aid_line_s.html


---

## UF_DRF_draft_aid_text_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_draft_aid_text_info_s.html


---

## UF_DRF_draft_aid_text_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_draft_aid_text_s.html


---

## UF_DRF_draw_arc_fn_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/callback.html#UF_DRF_draw_arc_fn_t


---

## UF_DRF_draw_char_fn_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/callback.html#UF_DRF_draw_char_fn_t


---

## UF_DRF_draw_standard_font_string_fn_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/callback.html#UF_DRF_draw_standard_font_string_fn_t


---

## UF_DRF_draw_to_position_fn_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/callback.html#UF_DRF_draw_to_position_fn_t


---

## UF_DRF_draw_user_symbol_fn_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/callback.html#UF_DRF_draw_user_symbol_fn_t


---

## UF_DRF_drawing_is_active

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_drawing_is_active


---

## UF_DRF_dual_dimension_format_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_dual_dimension_format_e


---

## UF_DRF_edit_dim_assoc

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_edit_dim_assoc


---

## UF_DRF_edit_weld_symbol

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_edit_weld_symbol


---

## UF_DRF_end_line_fn_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/callback.html#UF_DRF_end_line_fn_t


---

## UF_DRF_error_in_k25h7pa

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_error_in_k25h7pa


---

## UF_DRF_extension_line_display_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_extension_line_display_e


---

## UF_DRF_fill_region_fn_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/callback.html#UF_DRF_fill_region_fn_t


---

## UF_DRF_first_end_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_first_end_point


---

## UF_DRF_first_object_is_a_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_first_object_is_a_point


---

## UF_DRF_flip_image_about_height

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_flip_image_about_height


---

## UF_DRF_flip_image_about_width

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_flip_image_about_width


---

## UF_DRF_folded_radius_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_folded_radius_info_s.html


---

## UF_DRF_form_requires_1_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_form_requires_1_object


---

## UF_DRF_form_requires_2_objects

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_form_requires_2_objects


---

## UF_DRF_form_requires_3_or_more_objects

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_form_requires_3_or_more_objects


---

## UF_DRF_fraction_denominator_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_fraction_denominator_e


---

## UF_DRF_fraction_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_fraction_type_e


---

## UF_DRF_frame_corner_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_frame_corner_e


---

## UF_DRF_frdim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_frdim


---

## UF_DRF_free_appended_text

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_free_appended_text


---

## UF_DRF_free_centerline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_free_centerline


---

## UF_DRF_free_comp_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_free_comp_data


---

## UF_DRF_free_dimension

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_free_dimension


---

## UF_DRF_free_dimension_preferences1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_free_dimension_preferences1


---

## UF_DRF_free_font

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_free_font


---

## UF_DRF_free_gdtsymbol

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_free_gdtsymbol


---

## UF_DRF_free_idsymbol

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_free_idsymbol


---

## UF_DRF_free_image_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_free_image_data


---

## UF_DRF_free_label

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_free_label


---

## UF_DRF_free_leader_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_free_leader_data


---

## UF_DRF_free_text

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_free_text


---

## UF_DRF_gdt_leader_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_gdt_leader_data_s.html


---

## UF_DRF_gdt_leader_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_gdt_leader_s.html


---

## UF_DRF_gdt_symbol_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_gdt_symbol_info_s.html


---

## UF_DRF_get_symbol_divider

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_get_symbol_divider


---

## UF_DRF_get_text_bars

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_get_text_bars


---

## UF_DRF_get_text_substring

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_get_text_substring


---

## UF_DRF_get_xhatch_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_get_xhatch_parms


---

## UF_DRF_has_associative_origin

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_has_associative_origin


---

## UF_DRF_hatch_fill_preferences_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_hatch_fill_preferences_s.html


---

## UF_DRF_id_symbol_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_id_symbol_info_s.html


---

## UF_DRF_id_symbol_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_id_symbol_type_e


---

## UF_DRF_image_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_image_data_s.html


---

## UF_DRF_inherit_feature_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_inherit_feature_data


---

## UF_DRF_inherit_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_inherit_type_e


---

## UF_DRF_init_associativity_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_init_associativity_data


---

## UF_DRF_init_assortpart_arc

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_init_assortpart_arc


---

## UF_DRF_init_assortpart_arrow

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_init_assortpart_arrow


---

## UF_DRF_init_assortpart_line

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_init_assortpart_line


---

## UF_DRF_init_assortpart_text

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_init_assortpart_text


---

## UF_DRF_init_image_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_init_image_data


---

## UF_DRF_init_line_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_init_line_object


---

## UF_DRF_init_object_structure

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_init_object_structure


---

## UF_DRF_init_symbol_create_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_init_symbol_create_data


---

## UF_DRF_initialize_custom_symbol_text_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_initialize_custom_symbol_text_data


---

## UF_DRF_initialize_leader_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_initialize_leader_data


---

## UF_DRF_inspection_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_inspection_type_e


---

## UF_DRF_intermediate_points_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_intermediate_points_s.html


---

## UF_DRF_invalid_ang_dim_form

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_ang_dim_form


---

## UF_DRF_invalid_centerline_form

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_centerline_form


---

## UF_DRF_invalid_circular_dim_form

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_circular_dim_form


---

## UF_DRF_invalid_fold_location

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_fold_location


---

## UF_DRF_invalid_frame_corner

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_frame_corner


---

## UF_DRF_invalid_id_symbol_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_id_symbol_type


---

## UF_DRF_invalid_leader_attach_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_leader_attach_type


---

## UF_DRF_invalid_leader_mode

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_leader_mode


---

## UF_DRF_invalid_leader_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_leader_type


---

## UF_DRF_invalid_line_assoc_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_line_assoc_type


---

## UF_DRF_invalid_linear_dim_form

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_linear_dim_form


---

## UF_DRF_invalid_number_of_bounds

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_number_of_bounds


---

## UF_DRF_invalid_number_of_objects

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_number_of_objects


---

## UF_DRF_invalid_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_object


---

## UF_DRF_invalid_object1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_object1


---

## UF_DRF_invalid_object1_assoc_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_object1_assoc_type


---

## UF_DRF_invalid_object1_modifier

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_object1_modifier


---

## UF_DRF_invalid_object2

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_object2


---

## UF_DRF_invalid_object2_assoc_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_object2_assoc_type


---

## UF_DRF_invalid_object2_modifier

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_object2_modifier


---

## UF_DRF_invalid_object_assoc_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_object_assoc_type


---

## UF_DRF_invalid_object_modifier

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_object_modifier


---

## UF_DRF_invalid_object_type_center_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_object_type_center_point


---

## UF_DRF_invalid_object_type_centerline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_object_type_centerline


---

## UF_DRF_invalid_object_type_offset_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_object_type_offset_point


---

## UF_DRF_invalid_object_view_id

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_object_view_id


---

## UF_DRF_invalid_origin

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_origin


---

## UF_DRF_invalid_parameter

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_parameter


---

## UF_DRF_invalid_parameter_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_parameter_value


---

## UF_DRF_invalid_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_invalid_view


---

## UF_DRF_is_annotation_retained

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_is_annotation_retained


---

## UF_DRF_is_block_centerline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_is_block_centerline


---

## UF_DRF_is_chamfer_dimension

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_is_chamfer_dimension


---

## UF_DRF_is_inherited_pmi

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_is_inherited_pmi


---

## UF_DRF_is_narrow_dimension

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_is_narrow_dimension


---

## UF_DRF_is_object_out_of_date

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_is_object_out_of_date


---

## UF_DRF_is_pmi_display_instance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_is_pmi_display_instance


---

## UF_DRF_is_sbf_symbol

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_is_sbf_symbol


---

## UF_DRF_is_valid_width

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_is_valid_width


---

## UF_DRF_label_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_label_info_s.html


---

## UF_DRF_last_end_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_last_end_point


---

## UF_DRF_leader_attach_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_leader_attach_type_e


---

## UF_DRF_leader_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_leader_data_s.html


---

## UF_DRF_leader_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_leader_info_s.html


---

## UF_DRF_leader_mode_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_leader_mode_e


---

## UF_DRF_leader_orientation_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_leader_orientation_e


---

## UF_DRF_leader_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_leader_s.html


---

## UF_DRF_leader_side_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_leader_side_e


---

## UF_DRF_leader_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_leader_type_e


---

## UF_DRF_lettering_preferences_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_lettering_preferences_s.html


---

## UF_DRF_lettering_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_lettering_s.html


---

## UF_DRF_line_arrow_preferences_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_line_arrow_preferences_s.html


---

## UF_DRF_line_object_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_line_object_s.html


---

## UF_DRF_line_width_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_line_width_e


---

## UF_DRF_linear_units_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_linear_units_e


---

## UF_DRF_margin_to_cline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_margin_to_cline


---

## UF_DRF_material_definition_not_found

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_material_definition_not_found


---

## UF_DRF_model_objects_on_drawing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_model_objects_on_drawing


---

## UF_DRF_narrow_dimension_display_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_narrow_dimension_display_type_e


---

## UF_DRF_narrow_dimension_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_narrow_dimension_info_s.html


---

## UF_DRF_narrow_dimension_text_orientation_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_narrow_dimension_text_orientation_e


---

## UF_DRF_no_boundary

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_no_boundary


---

## UF_DRF_no_boundary_members

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_no_boundary_members


---

## UF_DRF_no_margin_to_convert

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_no_margin_to_convert


---

## UF_DRF_no_objects

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_no_objects


---

## UF_DRF_no_text

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_no_text


---

## UF_DRF_no_text_found

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_no_text_found


---

## UF_DRF_not_a_centerline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_not_a_centerline


---

## UF_DRF_not_a_cylindrical_dim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_not_a_cylindrical_dim


---

## UF_DRF_not_a_dimension

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_not_a_dimension


---

## UF_DRF_not_a_folded_radius_dim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_not_a_folded_radius_dim


---

## UF_DRF_not_a_gdt_symbol

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_not_a_gdt_symbol


---

## UF_DRF_not_a_id_symbol

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_not_a_id_symbol


---

## UF_DRF_not_a_label

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_not_a_label


---

## UF_DRF_not_a_ordinate_margin

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_not_a_ordinate_margin


---

## UF_DRF_not_an_ordinate_origin

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_not_an_ordinate_origin


---

## UF_DRF_null_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_null_object


---

## UF_DRF_null_object1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_null_object1


---

## UF_DRF_null_object1_structure

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_null_object1_structure


---

## UF_DRF_null_object2

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_null_object2


---

## UF_DRF_null_object2_structure

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_null_object2_structure


---

## UF_DRF_null_object_structure

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_null_object_structure


---

## UF_DRF_object_assoc_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_object_assoc_data_s.html


---

## UF_DRF_object_assoc_line_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_object_assoc_line_type_e


---

## UF_DRF_object_assoc_point_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_object_assoc_point_type_e


---

## UF_DRF_object_is_not_a_line

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_object_is_not_a_line


---

## UF_DRF_object_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_object_s.html


---

## UF_DRF_objects_not_in_same_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_objects_not_in_same_view


---

## UF_DRF_off_distance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_off_distance


---

## UF_DRF_off_position

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_off_position


---

## UF_DRF_offset_center_point_requires_arc

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_offset_center_point_requires_arc


---

## UF_DRF_ordarrow_line_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_ordarrow_line_type_e


---

## UF_DRF_orddim_margin_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_orddim_margin_type_e


---

## UF_DRF_orddimension_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_orddimension_info_s.html


---

## UF_DRF_orddisp_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_orddisp_info_s.html


---

## UF_DRF_ordorigin_display_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_ordorigin_display_type_e


---

## UF_DRF_place_symbol

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_place_symbol


---

## UF_DRF_point_coincident_with_center

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_point_coincident_with_center


---

## UF_DRF_point_not_on_centerline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_point_not_on_centerline


---

## UF_DRF_pop_orientation_fn_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/callback.html#UF_DRF_pop_orientation_fn_t


---

## UF_DRF_push_orientation_fn_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/callback.html#UF_DRF_push_orientation_fn_t


---

## UF_DRF_quadrant_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_quadrant_type_e


---

## UF_DRF_radius_symbol_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_radius_symbol_e


---

## UF_DRF_record_draft_objects

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_record_draft_objects


---

## UF_DRF_reference_symbol_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_reference_symbol_type_e


---

## UF_DRF_remove_controlling_exp

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_remove_controlling_exp


---

## UF_DRF_render_arrowhead

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_render_arrowhead


---

## UF_DRF_render_table_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_render_table_s.html


---

## UF_DRF_render_text

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_render_text


---

## UF_DRF_render_text_status_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_render_text_status_t


---

## UF_DRF_retained_state_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_retained_state_e


---

## UF_DRF_rotate_image

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_rotate_image


---

## UF_DRF_section_line_arrowhead_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_section_line_arrowhead_e


---

## UF_DRF_section_line_display_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_section_line_display_e


---

## UF_DRF_set_annotation_template

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_annotation_template


---

## UF_DRF_set_appended_text

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_appended_text


---

## UF_DRF_set_areafill_angle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_areafill_angle


---

## UF_DRF_set_areafill_material

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_areafill_material


---

## UF_DRF_set_areafill_scale

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_areafill_scale


---

## UF_DRF_set_associative_origin

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_associative_origin


---

## UF_DRF_set_associativity_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_associativity_data


---

## UF_DRF_set_cfw_fn_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/callback.html#UF_DRF_set_cfw_fn_t


---

## UF_DRF_set_chamfer_dimension_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_chamfer_dimension_data


---

## UF_DRF_set_custom_symbol_angle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_custom_symbol_angle


---

## UF_DRF_set_custom_symbol_scale

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_custom_symbol_scale


---

## UF_DRF_set_customer_sbf_file

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_customer_sbf_file


---

## UF_DRF_set_cyl_dim

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_cyl_dim


---

## UF_DRF_set_diameter_radius_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_diameter_radius_preferences


---

## UF_DRF_set_dim_appended_text_space_factor

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_dim_appended_text_space_factor


---

## UF_DRF_set_dim_dim_line_space_factor

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_dim_dim_line_space_factor


---

## UF_DRF_set_dim_inspection_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_dim_inspection_type


---

## UF_DRF_set_dim_reference_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_dim_reference_type


---

## UF_DRF_set_dim_tolerance_text_space_factor

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_dim_tolerance_text_space_factor


---

## UF_DRF_set_dimension_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_dimension_preferences


---

## UF_DRF_set_dimension_preferences1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_dimension_preferences1


---

## UF_DRF_set_dimension_set_offset

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_dimension_set_offset


---

## UF_DRF_set_draft_common

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_draft_common


---

## UF_DRF_set_hatch_fill_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_hatch_fill_preferences


---

## UF_DRF_set_image_align_position

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_image_align_position


---

## UF_DRF_set_image_aspect_ratio_lock

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_image_aspect_ratio_lock


---

## UF_DRF_set_image_height

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_image_height


---

## UF_DRF_set_image_width

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_image_width


---

## UF_DRF_set_lettering_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_lettering_preferences


---

## UF_DRF_set_line_arrow_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_line_arrow_preferences


---

## UF_DRF_set_narrow_dimension_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_narrow_dimension_data


---

## UF_DRF_set_object_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_object_preferences


---

## UF_DRF_set_origin

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_origin


---

## UF_DRF_set_plot_drawing_images

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_plot_drawing_images


---

## UF_DRF_set_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_preferences


---

## UF_DRF_set_retain_color_font_width

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_retain_color_font_width


---

## UF_DRF_set_retained_state

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_retained_state


---

## UF_DRF_set_specified_sbf_file

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_specified_sbf_file


---

## UF_DRF_set_suppress_pre_zeros

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_suppress_pre_zeros


---

## UF_DRF_set_suppress_view_update

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_suppress_view_update


---

## UF_DRF_set_symbol_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_symbol_preferences


---

## UF_DRF_set_text_above_leader

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_text_above_leader


---

## UF_DRF_set_to_position_fn_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/callback.html#UF_DRF_set_to_position_fn_t


---

## UF_DRF_set_tolerance

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_tolerance


---

## UF_DRF_set_uds_size

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_uds_size


---

## UF_DRF_set_ugdefault_sbf_file

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_ugdefault_sbf_file


---

## UF_DRF_set_units_format_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_units_format_preferences


---

## UF_DRF_set_vertical_note

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_vertical_note


---

## UF_DRF_set_weld_symbol_standard

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_weld_symbol_standard


---

## UF_DRF_set_xhatch_mat

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_set_xhatch_mat


---

## UF_DRF_stack_align_position_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_stack_align_position_t


---

## UF_DRF_stroke_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_stroke_info_s.html


---

## UF_DRF_symbol_connection_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_symbol_connection_s.html


---

## UF_DRF_symbol_connection_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_symbol_connection_type_e


---

## UF_DRF_symbol_create_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_symbol_create_data_s.html


---

## UF_DRF_symbol_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_symbol_data_s.html


---

## UF_DRF_symbol_instance_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_symbol_instance_s.html


---

## UF_DRF_symbol_preferences_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_symbol_preferences_s.html


---

## UF_DRF_tag_is_null

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_tag_is_null


---

## UF_DRF_text_above_leader_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_text_above_leader_e


---

## UF_DRF_text_arrow_placement_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_text_arrow_placement_e


---

## UF_DRF_text_cfw_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_text_cfw_s.html


---

## UF_DRF_text_just_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_text_just_e


---

## UF_DRF_text_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_text_s.html


---

## UF_DRF_text_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_text_type_e


---

## UF_DRF_thru_3_points

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_types.html#UF_DRF_thru_3_points


---

## UF_DRF_tolerance_placement_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_tolerance_placement_e


---

## UF_DRF_tolerance_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_tolerance_type_e


---

## UF_DRF_too_many_boundaries

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_too_many_boundaries


---

## UF_DRF_too_many_characters_in_line

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_too_many_characters_in_line


---

## UF_DRF_too_many_characters_in_text

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_too_many_characters_in_text


---

## UF_DRF_too_many_objects

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_too_many_objects


---

## UF_DRF_transfer_to_drawing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_transfer_to_drawing


---

## UF_DRF_trim_dim_line_style_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_trim_dim_line_style_e


---

## UF_DRF_two_points_in_a_row

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_two_points_in_a_row


---

## UF_DRF_ud_symbol_data_not_found

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_ud_symbol_data_not_found


---

## UF_DRF_ud_symbol_font_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_ud_symbol_font_info_s.html


---

## UF_DRF_ud_symbol_pen_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_ud_symbol_pen_type_e


---

## UF_DRF_uds_size_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_uds_size_s.html


---

## UF_DRF_uds_size_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_uds_size_type_e


---

## UF_DRF_unable_to_create_crosshatching

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_unable_to_create_crosshatching


---

## UF_DRF_units_format_preferences_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_units_format_preferences_s.html


---

## UF_DRF_unknown_error

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_unknown_error


---

## UF_DRF_unrecoverable_error

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/uf_drf_errors.html#UF_DRF_unrecoverable_error


---

## UF_DRF_update_views

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/global.html#UF_DRF_update_views


---

## UF_DRF_valid_cline_form_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_valid_cline_form_e


---

## UF_DRF_valid_material_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_valid_material_e


---

## UF_DRF_vertical_text_just_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_vertical_text_just_e


---

## UF_DRF_weld_contour_types_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_weld_contour_types_e


---

## UF_DRF_weld_finish_types_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_weld_finish_types_e


---

## UF_DRF_weld_ident_line_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_weld_ident_line_type_e


---

## UF_DRF_weld_size_code_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_weld_size_code_e


---

## UF_DRF_weld_sym_ext_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_weld_sym_ext_type_e


---

## UF_DRF_weld_sym_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_weld_sym_info_s.html


---

## UF_DRF_weld_symbol_types_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/types.html#UF_DRF_weld_symbol_types_e


---

## UF_DRF_weld_symbols_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/UF_DRF_weld_symbols_s.html


---

## uf_drf.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/intro.html#uf_drf


---

## uf_drf_errors.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/intro.html#uf_drf_errors


---

## uf_drf_types.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_drf/intro.html#uf_drf_types


---
