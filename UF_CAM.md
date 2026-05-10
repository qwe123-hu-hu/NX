# UF_CAM 函数参考

> 共 229 个函数

---

## 目录

- [UF_CAM #Defines](#uf_cam #defines)
- [UF_CAM Enumerations](#uf_cam enumerations)
- [UF_CAM Files](#uf_cam files)
- [UF_CAM Functions](#uf_cam functions)
- [UF_CAM Structures](#uf_cam structures)
- [UF_CAMBND_UDE_set_type_e](#uf_cambnd_ude_set_type_e)
- [UF_CAMBND_WEDM_append_item_ude](#uf_cambnd_wedm_append_item_ude)
- [UF_CAMBND_WEDM_ask_item_udes](#uf_cambnd_wedm_ask_item_udes)
- [UF_CAMBND_WEDM_delete_all_item_udes](#uf_cambnd_wedm_delete_all_item_udes)
- [UF_CAMBND_WEDM_delete_item_ude](#uf_cambnd_wedm_delete_item_ude)
- [UF_CAMBND_app_data_s](#uf_cambnd_app_data_s)
- [UF_CAMBND_append_bnd_from_curve](#uf_cambnd_append_bnd_from_curve)
- [UF_CAMBND_append_bnd_from_face](#uf_cambnd_append_bnd_from_face)
- [UF_CAMBND_append_item_ude](#uf_cambnd_append_item_ude)
- [UF_CAMBND_ask_boundaries](#uf_cambnd_ask_boundaries)
- [UF_CAMBND_ask_boundary_app_data](#uf_cambnd_ask_boundary_app_data)
- [UF_CAMBND_ask_boundary_data](#uf_cambnd_ask_boundary_data)
- [UF_CAMBND_ask_boundary_group_data](#uf_cambnd_ask_boundary_group_data)
- [UF_CAMBND_ask_boundary_items](#uf_cambnd_ask_boundary_items)
- [UF_CAMBND_ask_item_app_data](#uf_cambnd_ask_item_app_data)
- [UF_CAMBND_ask_item_entity](#uf_cambnd_ask_item_entity)
- [UF_CAMBND_ask_item_group_data](#uf_cambnd_ask_item_group_data)
- [UF_CAMBND_ask_item_udes](#uf_cambnd_ask_item_udes)
- [UF_CAMBND_boundary_data_s](#uf_cambnd_boundary_data_s)
- [UF_CAMBND_can_accept_item_ude](#uf_cambnd_can_accept_item_ude)
- [UF_CAMBND_delete_all_item_udes](#uf_cambnd_delete_all_item_udes)
- [UF_CAMBND_delete_boundaries](#uf_cambnd_delete_boundaries)
- [UF_CAMBND_delete_boundary](#uf_cambnd_delete_boundary)
- [UF_CAMBND_delete_item_ude](#uf_cambnd_delete_item_ude)
- [UF_CAMBND_group_data_s](#uf_cambnd_group_data_s)
- [UF_CAMBND_is_inherited](#uf_cambnd_is_inherited)
- [UF_CAMBND_set_boundary_app_data](#uf_cambnd_set_boundary_app_data)
- [UF_CAMBND_set_boundary_group_data](#uf_cambnd_set_boundary_group_data)
- [UF_CAMBND_set_boundary_plane](#uf_cambnd_set_boundary_plane)
- [UF_CAMBND_set_item_app_data](#uf_cambnd_set_item_app_data)
- [UF_CAMBND_set_item_group_data](#uf_cambnd_set_item_group_data)
- [UF_CAMGEOM_app_data_s](#uf_camgeom_app_data_s)
- [UF_CAMGEOM_append_custom_points](#uf_camgeom_append_custom_points)
- [UF_CAMGEOM_append_items](#uf_camgeom_append_items)
- [UF_CAMGEOM_ask_collector_items](#uf_camgeom_ask_collector_items)
- [UF_CAMGEOM_ask_custom_points](#uf_camgeom_ask_custom_points)
- [UF_CAMGEOM_ask_geom_provider](#uf_camgeom_ask_geom_provider)
- [UF_CAMGEOM_ask_item_app_data](#uf_camgeom_ask_item_app_data)
- [UF_CAMGEOM_ask_item_entity](#uf_camgeom_ask_item_entity)
- [UF_CAMGEOM_ask_item_maxmin](#uf_camgeom_ask_item_maxmin)
- [UF_CAMGEOM_ask_items](#uf_camgeom_ask_items)
- [UF_CAMGEOM_custom_point_s](#uf_camgeom_custom_point_s)
- [UF_CAMGEOM_custom_point_type_e](#uf_camgeom_custom_point_type_e)
- [UF_CAMGEOM_delete_custom_points](#uf_camgeom_delete_custom_points)
- [UF_CAMGEOM_delete_geometry](#uf_camgeom_delete_geometry)
- [UF_CAMGEOM_delete_item](#uf_camgeom_delete_item)
- [UF_CAMGEOM_eval_surface](#uf_camgeom_eval_surface)
- [UF_CAMGEOM_set_item_app_data](#uf_camgeom_set_item_app_data)
- [UF_CAMTEXT_append_items](#uf_camtext_append_items)
- [UF_CAMTEXT_ask_item_entity](#uf_camtext_ask_item_entity)
- [UF_CAMTEXT_ask_items](#uf_camtext_ask_items)
- [UF_CAMTEXT_delete_geometry](#uf_camtext_delete_geometry)
- [UF_CAMTEXT_delete_item](#uf_camtext_delete_item)
- [UF_CAM_ERROR_4GD_PART_NOT_SUPPORTED](#uf_cam_error_4gd_part_not_supported)
- [UF_CAM_ERROR_CUT_LEVELS_NOT_SUPPORTED](#uf_cam_error_cut_levels_not_supported)
- [UF_CAM_ERROR_CUT_LEVEL_CHANGE_NOT_MADE](#uf_cam_error_cut_level_change_not_made)
- [UF_CAM_ERROR_DATA_MATCH](#uf_cam_error_data_match)
- [UF_CAM_ERROR_DATA_NOT_AVAILABLE](#uf_cam_error_data_not_available)
- [UF_CAM_ERROR_DATA_NOT_CORRECT_TYPE](#uf_cam_error_data_not_correct_type)
- [UF_CAM_ERROR_DUPLICATE_NAME](#uf_cam_error_duplicate_name)
- [UF_CAM_ERROR_FROM_TURNING_PROCESSOR](#uf_cam_error_from_turning_processor)
- [UF_CAM_ERROR_GOUGE_CHECK_NOT_SUPPORTED](#uf_cam_error_gouge_check_not_supported)
- [UF_CAM_ERROR_HOLDER_UPDATE_ONLY](#uf_cam_error_holder_update_only)
- [UF_CAM_ERROR_INCONSISTENT_IPW_BOX](#uf_cam_error_inconsistent_ipw_box)
- [UF_CAM_ERROR_INSPECTION_SETUP](#uf_cam_error_inspection_setup)
- [UF_CAM_ERROR_INSPECTION_TEMPLATE](#uf_cam_error_inspection_template)
- [UF_CAM_ERROR_INTERNAL_LICENSE_REQUIRED](#uf_cam_error_internal_license_required)
- [UF_CAM_ERROR_INVALID_APP_DATA](#uf_cam_error_invalid_app_data)
- [UF_CAM_ERROR_INVALID_CAM_BASE_DIR](#uf_cam_error_invalid_cam_base_dir)
- [UF_CAM_ERROR_INVALID_CUSTOM_POINT_TYPE](#uf_cam_error_invalid_custom_point_type)
- [UF_CAM_ERROR_INVALID_CUT_LEVEL_ENTITY](#uf_cam_error_invalid_cut_level_entity)
- [UF_CAM_ERROR_INVALID_DIAMETER](#uf_cam_error_invalid_diameter)
- [UF_CAM_ERROR_INVALID_DRIVE_GEOMETRY](#uf_cam_error_invalid_drive_geometry)
- [UF_CAM_ERROR_INVALID_DRIVE_METHOD](#uf_cam_error_invalid_drive_method)
- [UF_CAM_ERROR_INVALID_EVENT_INDEX](#uf_cam_error_invalid_event_index)
- [UF_CAM_ERROR_INVALID_GROUP_DATA](#uf_cam_error_invalid_group_data)
- [UF_CAM_ERROR_INVALID_INDEX](#uf_cam_error_invalid_index)
- [UF_CAM_ERROR_INVALID_INHERITED_ENTITY](#uf_cam_error_invalid_inherited_entity)
- [UF_CAM_ERROR_INVALID_INPUT](#uf_cam_error_invalid_input)
- [UF_CAM_ERROR_INVALID_INPUT_ENTITY](#uf_cam_error_invalid_input_entity)
- [UF_CAM_ERROR_INVALID_INSP_BASE_DIR](#uf_cam_error_invalid_insp_base_dir)
- [UF_CAM_ERROR_INVALID_LENGTH](#uf_cam_error_invalid_length)
- [UF_CAM_ERROR_INVALID_PARAMETER](#uf_cam_error_invalid_parameter)
- [UF_CAM_ERROR_INVALID_PATH_STRUCTURE](#uf_cam_error_invalid_path_structure)
- [UF_CAM_ERROR_INVALID_POCKET_NUM_OF_TOOLS](#uf_cam_error_invalid_pocket_num_of_tools)
- [UF_CAM_ERROR_INVALID_RADIUS](#uf_cam_error_invalid_radius)
- [UF_CAM_ERROR_INVALID_TAPER](#uf_cam_error_invalid_taper)
- [UF_CAM_ERROR_INVALID_TURN_WORKPIECE_DIAMETER](#uf_cam_error_invalid_turn_workpiece_diameter)
- [UF_CAM_ERROR_INVALID_TURN_WORKPIECE_DIRECTION](#uf_cam_error_invalid_turn_workpiece_direction)
- [UF_CAM_ERROR_INVALID_TURN_WORKPIECE_INNER_DIAMETER](#uf_cam_error_invalid_turn_workpiece_inner_diameter)
- [UF_CAM_ERROR_INVALID_TURN_WORKPIECE_LENGTH](#uf_cam_error_invalid_turn_workpiece_length)
- [UF_CAM_ERROR_INVALID_TURN_WORKPIECE_STOCK](#uf_cam_error_invalid_turn_workpiece_stock)
- [UF_CAM_ERROR_INVALID_TYPE_OF_WORKPIECE](#uf_cam_error_invalid_type_of_workpiece)
- [UF_CAM_ERROR_INVALID_WORKFLOW_CONFIG](#uf_cam_error_invalid_workflow_config)
- [UF_CAM_ERROR_IPW_DOES_NOT_EXIST](#uf_cam_error_ipw_does_not_exist)
- [UF_CAM_ERROR_LEGACY_OFFSET_NOT_ALLOWED](#uf_cam_error_legacy_offset_not_allowed)
- [UF_CAM_ERROR_LIBRARY_NOT_FOUND](#uf_cam_error_library_not_found)
- [UF_CAM_ERROR_MANUFACTURING_SETUP](#uf_cam_error_manufacturing_setup)
- [UF_CAM_ERROR_MANUFACTURING_TEMPLATE](#uf_cam_error_manufacturing_template)
- [UF_CAM_ERROR_MASTER_TEMPLATE_COMPLEX_MERGE](#uf_cam_error_master_template_complex_merge)
- [UF_CAM_ERROR_MRM_DND_LICENSE_REQUIRED](#uf_cam_error_mrm_dnd_license_required)
- [UF_CAM_ERROR_NOT_AUTO_BLANK](#uf_cam_error_not_auto_blank)
- [UF_CAM_ERROR_NOT_LIBRARY_HOLDER](#uf_cam_error_not_library_holder)
- [UF_CAM_ERROR_NOT_LIBRARY_TOOL](#uf_cam_error_not_library_tool)
- [UF_CAM_ERROR_NOT_PLANAR_FACE](#uf_cam_error_not_planar_face)
- [UF_CAM_ERROR_NO_CAM_SESSION](#uf_cam_error_no_cam_session)
- [UF_CAM_ERROR_NO_CURRENT_OPT](#uf_cam_error_no_current_opt)
- [UF_CAM_ERROR_NO_CUT_METHOD](#uf_cam_error_no_cut_method)
- [UF_CAM_ERROR_NO_FEEDS_SPEEDS_LIBRARY](#uf_cam_error_no_feeds_speeds_library)
- [UF_CAM_ERROR_NO_MATCHING_RECORD](#uf_cam_error_no_matching_record)
- [UF_CAM_ERROR_NO_MULTITOOL_ERROR](#uf_cam_error_no_multitool_error)
- [UF_CAM_ERROR_NO_PART_MATERIAL](#uf_cam_error_no_part_material)
- [UF_CAM_ERROR_NO_PATH_EXISTS](#uf_cam_error_no_path_exists)
- [UF_CAM_ERROR_NO_ROBOT_CHAIN](#uf_cam_error_no_robot_chain)
- [UF_CAM_ERROR_NO_SETUP](#uf_cam_error_no_setup)
- [UF_CAM_ERROR_NO_TOOL_MATERIAL](#uf_cam_error_no_tool_material)
- [UF_CAM_ERROR_OBJECT_IS_NOT_TAGGED_OBJECT](#uf_cam_error_object_is_not_tagged_object)
- [UF_CAM_ERROR_OBJECT_NOT_DESIRED_CLASS](#uf_cam_error_object_not_desired_class)
- [UF_CAM_ERROR_PATH_CREATION_FAILED](#uf_cam_error_path_creation_failed)
- [UF_CAM_ERROR_PATH_EVENT_CREATION_FAILED](#uf_cam_error_path_event_creation_failed)
- [UF_CAM_ERROR_PATH_EVENT_NOT_CORRECT_TYPE](#uf_cam_error_path_event_not_correct_type)
- [UF_CAM_ERROR_PLANE_NOT_DEFINED](#uf_cam_error_plane_not_defined)
- [UF_CAM_ERROR_POINT_NOT_FOUND](#uf_cam_error_point_not_found)
- [UF_CAM_ERROR_PREFERENCE_NOT_DEFINED](#uf_cam_error_preference_not_defined)
- [UF_CAM_ERROR_READ_ONLY_PARAM](#uf_cam_error_read_only_param)
- [UF_CAM_ERROR_REMOVE_DEPENDENCIES](#uf_cam_error_remove_dependencies)
- [UF_CAM_ERROR_RESTORE_DEPENDENCIES](#uf_cam_error_restore_dependencies)
- [UF_CAM_ERROR_SAVE_SPINNING_IPW_AS_PART](#uf_cam_error_save_spinning_ipw_as_part)
- [UF_CAM_ERROR_SINGLE_RANGE_NOT_CHANGED](#uf_cam_error_single_range_not_changed)
- [UF_CAM_ERROR_SOLID_TOOL_NOT_LOADED](#uf_cam_error_solid_tool_not_loaded)
- [UF_CAM_ERROR_TAG_IS_NOT_TAGGED_OBJECT](#uf_cam_error_tag_is_not_tagged_object)
- [UF_CAM_ERROR_TAG_NOT_CORRECT_TYPE](#uf_cam_error_tag_not_correct_type)
- [UF_CAM_ERROR_TEMPLATE_OBJECT_UI_DIFFERENT](#uf_cam_error_template_object_ui_different)
- [UF_CAM_ERROR_TEMPLATE_OBJECT_VALUE_DIFFERENT](#uf_cam_error_template_object_value_different)
- [UF_CAM_ERROR_TOOLS_NOT_SAME_SUBTYPE](#uf_cam_error_tools_not_same_subtype)
- [UF_CAM_ERROR_TOOLS_NOT_SAME_TYPE](#uf_cam_error_tools_not_same_type)
- [UF_CAM_ERROR_TURNING_BOUNDARY_ONLY_ONE_ALLOWED](#uf_cam_error_turning_boundary_only_one_allowed)
- [UF_CAM_ERROR_TYPE_TEMPLATE_OBJECT_INVALID_PARENT](#uf_cam_error_type_template_object_invalid_parent)
- [UF_CAM_ERROR_TYPE_TEMPLATE_STRUCTURE_DIFFERENT](#uf_cam_error_type_template_structure_different)
- [UF_CAM_ERROR_UI_CUSTOMIZATION_EXPLORER_FAILURE](#uf_cam_error_ui_customization_explorer_failure)
- [UF_CAM_ERROR_UI_DIALOG_ERROR](#uf_cam_error_ui_dialog_error)
- [UF_CAM_ERROR_UI_UNKNOWN_ERROR](#uf_cam_error_ui_unknown_error)
- [UF_CAM_ERROR_UNDEFINED_TURN_WORKPIECE_TYPE](#uf_cam_error_undefined_turn_workpiece_type)
- [UF_CAM_ERROR_UPDATE_GEOMETRY_DEPENDENCIES](#uf_cam_error_update_geometry_dependencies)
- [UF_CAM_MAX_TEMPLATE_SET_NAME_BUFSIZE](#uf_cam_max_template_set_name_bufsize)
- [UF_CAM_MAX_TEMPLATE_SET_NAME_LEN](#uf_cam_max_template_set_name_len)
- [UF_CAM_MAX_TEMPLATE_SET_NAME_NCHARS](#uf_cam_max_template_set_name_nchars)
- [UF_CAM_OLD_H](#uf_cam_old_h)
- [UF_CAM_PREF_ask_data_type](#uf_cam_pref_ask_data_type)
- [UF_CAM_PREF_ask_integer_value](#uf_cam_pref_ask_integer_value)
- [UF_CAM_PREF_ask_logical_value](#uf_cam_pref_ask_logical_value)
- [UF_CAM_PREF_e](#uf_cam_pref_e)
- [UF_CAM_PREF_set_integer_value](#uf_cam_pref_set_integer_value)
- [UF_CAM_PREF_set_logical_value](#uf_cam_pref_set_logical_value)
- [UF_CAM_PREPRO_ERROR_BASE](#uf_cam_prepro_error_base)
- [UF_CAM_PREPRO_init_module](#uf_cam_prepro_init_module)
- [UF_CAM_PREPRO_invalid_model](#uf_cam_prepro_invalid_model)
- [UF_CAM_PREPRO_mark_model_as_cam](#uf_cam_prepro_mark_model_as_cam)
- [UF_CAM_SESSION_ERROR_NO_SESSION](#uf_cam_session_error_no_session)
- [UF_CAM_ask_auto_blank](#uf_cam_ask_auto_blank)
- [UF_CAM_ask_blank_matl_db_object](#uf_cam_ask_blank_matl_db_object)
- [UF_CAM_ask_cam_preferences](#uf_cam_ask_cam_preferences)
- [UF_CAM_ask_clear_plane_data](#uf_cam_ask_clear_plane_data)
- [UF_CAM_ask_clear_plane_status](#uf_cam_ask_clear_plane_status)
- [UF_CAM_ask_clear_plane_tag](#uf_cam_ask_clear_plane_tag)
- [UF_CAM_ask_clear_plane_usage](#uf_cam_ask_clear_plane_usage)
- [UF_CAM_ask_config_file](#uf_cam_ask_config_file)
- [UF_CAM_ask_cutter_db_object](#uf_cam_ask_cutter_db_object)
- [UF_CAM_ask_doc_template_name](#uf_cam_ask_doc_template_name)
- [UF_CAM_ask_f_s_db_object](#uf_cam_ask_f_s_db_object)
- [UF_CAM_ask_leastsq_sphere](#uf_cam_ask_leastsq_sphere)
- [UF_CAM_ask_lower_limit_plane_data](#uf_cam_ask_lower_limit_plane_data)
- [UF_CAM_ask_lower_limit_plane_status](#uf_cam_ask_lower_limit_plane_status)
- [UF_CAM_ask_lower_limit_plane_tag](#uf_cam_ask_lower_limit_plane_tag)
- [UF_CAM_ask_lower_limit_plane_usage](#uf_cam_ask_lower_limit_plane_usage)
- [UF_CAM_ask_mach_tool_db_object](#uf_cam_ask_mach_tool_db_object)
- [UF_CAM_ask_opt_template_object](#uf_cam_ask_opt_template_object)
- [UF_CAM_ask_post_template_name](#uf_cam_ask_post_template_name)
- [UF_CAM_ask_tool_matl_db_object](#uf_cam_ask_tool_matl_db_object)
- [UF_CAM_avoidance_type_e](#uf_cam_avoidance_type_e)
- [UF_CAM_blank_geom_type_e](#uf_cam_blank_geom_type_e)
- [UF_CAM_boundary_type_e](#uf_cam_boundary_type_e)
- [UF_CAM_feedrate_unit_e](#uf_cam_feedrate_unit_e)
- [UF_CAM_geom_type_e](#uf_cam_geom_type_e)
- [UF_CAM_init_session](#uf_cam_init_session)
- [UF_CAM_is_session_initialized](#uf_cam_is_session_initialized)
- [UF_CAM_material_side_e](#uf_cam_material_side_e)
- [UF_CAM_opt_add_template_part](#uf_cam_opt_add_template_part)
- [UF_CAM_opt_add_type](#uf_cam_opt_add_type)
- [UF_CAM_opt_ask_clsf_names](#uf_cam_opt_ask_clsf_names)
- [UF_CAM_opt_ask_doc_names](#uf_cam_opt_ask_doc_names)
- [UF_CAM_opt_ask_object](#uf_cam_opt_ask_object)
- [UF_CAM_opt_ask_post_names](#uf_cam_opt_ask_post_names)
- [UF_CAM_opt_ask_subtypes](#uf_cam_opt_ask_subtypes)
- [UF_CAM_opt_ask_types](#uf_cam_opt_ask_types)
- [UF_CAM_opt_stype_cls_e](#uf_cam_opt_stype_cls_e)
- [UF_CAM_preferences_s](#uf_cam_preferences_s)
- [UF_CAM_reinit_opt](#uf_cam_reinit_opt)
- [UF_CAM_reinit_session](#uf_cam_reinit_session)
- [UF_CAM_set_auto_blank](#uf_cam_set_auto_blank)
- [UF_CAM_set_cam_preferences](#uf_cam_set_cam_preferences)
- [UF_CAM_set_clear_plane_data](#uf_cam_set_clear_plane_data)
- [UF_CAM_set_clear_plane_status](#uf_cam_set_clear_plane_status)
- [UF_CAM_set_clear_plane_tag](#uf_cam_set_clear_plane_tag)
- [UF_CAM_set_clear_plane_usage](#uf_cam_set_clear_plane_usage)
- [UF_CAM_set_lower_limit_plane_data](#uf_cam_set_lower_limit_plane_data)
- [UF_CAM_set_lower_limit_plane_status](#uf_cam_set_lower_limit_plane_status)
- [UF_CAM_set_lower_limit_plane_tag](#uf_cam_set_lower_limit_plane_tag)
- [UF_CAM_set_lower_limit_plane_usage](#uf_cam_set_lower_limit_plane_usage)
- [UF_CAM_set_material](#uf_cam_set_material)
- [UF_CAM_tool_position_e](#uf_cam_tool_position_e)
- [UF_CAM_update_list_object_customization](#uf_cam_update_list_object_customization)
- [UF_CAM_update_single_object_customization](#uf_cam_update_single_object_customization)
- [UF_CAM_wizard_ask_current_object](#uf_cam_wizard_ask_current_object)
- [UF_CAM_wizard_set_current_object](#uf_cam_wizard_set_current_object)
- [uf_cam.h](#uf_cam.h)
- [uf_cam_errors.h](#uf_cam_errors.h)
- [uf_cam_planes.h](#uf_cam_planes.h)
- [uf_cam_prefs.h](#uf_cam_prefs.h)
- [uf_cam_prepro.h](#uf_cam_prepro.h)
- [uf_cam_spec.h](#uf_cam_spec.h)
- [uf_cambnd.h](#uf_cambnd.h)
- [uf_camgeom.h](#uf_camgeom.h)
- [uf_camtext.h](#uf_camtext.h)

---

## UF_CAM #Defines

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/contents.html#defines


---

## UF_CAM Enumerations

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/contents.html#enumerations


---

## UF_CAM Files

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/contents.html#files


---

## UF_CAM Functions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/contents.html#functions


---

## UF_CAM Structures

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/contents.html#structures


---

## UF_CAMBND_UDE_set_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/types.html#UF_CAMBND_UDE_set_type_e


---

## UF_CAMBND_WEDM_append_item_ude

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_WEDM_append_item_ude


---

## UF_CAMBND_WEDM_ask_item_udes

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_WEDM_ask_item_udes


---

## UF_CAMBND_WEDM_delete_all_item_udes

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_WEDM_delete_all_item_udes


---

## UF_CAMBND_WEDM_delete_item_ude

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_WEDM_delete_item_ude


---

## UF_CAMBND_app_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/UF_CAMBND_app_data_s.html


---

## UF_CAMBND_append_bnd_from_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_append_bnd_from_curve


---

## UF_CAMBND_append_bnd_from_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_append_bnd_from_face


---

## UF_CAMBND_append_item_ude

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_append_item_ude


---

## UF_CAMBND_ask_boundaries

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_ask_boundaries


---

## UF_CAMBND_ask_boundary_app_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_ask_boundary_app_data


---

## UF_CAMBND_ask_boundary_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_ask_boundary_data


---

## UF_CAMBND_ask_boundary_group_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_ask_boundary_group_data


---

## UF_CAMBND_ask_boundary_items

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_ask_boundary_items


---

## UF_CAMBND_ask_item_app_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_ask_item_app_data


---

## UF_CAMBND_ask_item_entity

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_ask_item_entity


---

## UF_CAMBND_ask_item_group_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_ask_item_group_data


---

## UF_CAMBND_ask_item_udes

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_ask_item_udes


---

## UF_CAMBND_boundary_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/UF_CAMBND_boundary_data_s.html


---

## UF_CAMBND_can_accept_item_ude

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_can_accept_item_ude


---

## UF_CAMBND_delete_all_item_udes

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_delete_all_item_udes


---

## UF_CAMBND_delete_boundaries

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_delete_boundaries


---

## UF_CAMBND_delete_boundary

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_delete_boundary


---

## UF_CAMBND_delete_item_ude

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_delete_item_ude


---

## UF_CAMBND_group_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/UF_CAMBND_group_data_s.html


---

## UF_CAMBND_is_inherited

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_is_inherited


---

## UF_CAMBND_set_boundary_app_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_set_boundary_app_data


---

## UF_CAMBND_set_boundary_group_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_set_boundary_group_data


---

## UF_CAMBND_set_boundary_plane

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_set_boundary_plane


---

## UF_CAMBND_set_item_app_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_set_item_app_data


---

## UF_CAMBND_set_item_group_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMBND_set_item_group_data


---

## UF_CAMGEOM_app_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/UF_CAMGEOM_app_data_s.html


---

## UF_CAMGEOM_append_custom_points

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMGEOM_append_custom_points


---

## UF_CAMGEOM_append_items

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMGEOM_append_items


---

## UF_CAMGEOM_ask_collector_items

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMGEOM_ask_collector_items


---

## UF_CAMGEOM_ask_custom_points

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMGEOM_ask_custom_points


---

## UF_CAMGEOM_ask_geom_provider

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMGEOM_ask_geom_provider


---

## UF_CAMGEOM_ask_item_app_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMGEOM_ask_item_app_data


---

## UF_CAMGEOM_ask_item_entity

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMGEOM_ask_item_entity


---

## UF_CAMGEOM_ask_item_maxmin

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMGEOM_ask_item_maxmin


---

## UF_CAMGEOM_ask_items

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMGEOM_ask_items


---

## UF_CAMGEOM_custom_point_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/UF_CAMGEOM_custom_point_s.html


---

## UF_CAMGEOM_custom_point_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/types.html#UF_CAMGEOM_custom_point_type_e


---

## UF_CAMGEOM_delete_custom_points

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMGEOM_delete_custom_points


---

## UF_CAMGEOM_delete_geometry

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMGEOM_delete_geometry


---

## UF_CAMGEOM_delete_item

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMGEOM_delete_item


---

## UF_CAMGEOM_eval_surface

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMGEOM_eval_surface


---

## UF_CAMGEOM_set_item_app_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMGEOM_set_item_app_data


---

## UF_CAMTEXT_append_items

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMTEXT_append_items


---

## UF_CAMTEXT_ask_item_entity

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMTEXT_ask_item_entity


---

## UF_CAMTEXT_ask_items

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMTEXT_ask_items


---

## UF_CAMTEXT_delete_geometry

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMTEXT_delete_geometry


---

## UF_CAMTEXT_delete_item

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAMTEXT_delete_item


---

## UF_CAM_ERROR_4GD_PART_NOT_SUPPORTED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_4GD_PART_NOT_SUPPORTED


---

## UF_CAM_ERROR_CUT_LEVELS_NOT_SUPPORTED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_CUT_LEVELS_NOT_SUPPORTED


---

## UF_CAM_ERROR_CUT_LEVEL_CHANGE_NOT_MADE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_CUT_LEVEL_CHANGE_NOT_MADE


---

## UF_CAM_ERROR_DATA_MATCH

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_DATA_MATCH


---

## UF_CAM_ERROR_DATA_NOT_AVAILABLE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_DATA_NOT_AVAILABLE


---

## UF_CAM_ERROR_DATA_NOT_CORRECT_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_DATA_NOT_CORRECT_TYPE


---

## UF_CAM_ERROR_DUPLICATE_NAME

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_DUPLICATE_NAME


---

## UF_CAM_ERROR_FROM_TURNING_PROCESSOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_FROM_TURNING_PROCESSOR


---

## UF_CAM_ERROR_GOUGE_CHECK_NOT_SUPPORTED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_GOUGE_CHECK_NOT_SUPPORTED


---

## UF_CAM_ERROR_HOLDER_UPDATE_ONLY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_HOLDER_UPDATE_ONLY


---

## UF_CAM_ERROR_INCONSISTENT_IPW_BOX

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INCONSISTENT_IPW_BOX


---

## UF_CAM_ERROR_INSPECTION_SETUP

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INSPECTION_SETUP


---

## UF_CAM_ERROR_INSPECTION_TEMPLATE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INSPECTION_TEMPLATE


---

## UF_CAM_ERROR_INTERNAL_LICENSE_REQUIRED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INTERNAL_LICENSE_REQUIRED


---

## UF_CAM_ERROR_INVALID_APP_DATA

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_APP_DATA


---

## UF_CAM_ERROR_INVALID_CAM_BASE_DIR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_CAM_BASE_DIR


---

## UF_CAM_ERROR_INVALID_CUSTOM_POINT_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_CUSTOM_POINT_TYPE


---

## UF_CAM_ERROR_INVALID_CUT_LEVEL_ENTITY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_CUT_LEVEL_ENTITY


---

## UF_CAM_ERROR_INVALID_DIAMETER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_DIAMETER


---

## UF_CAM_ERROR_INVALID_DRIVE_GEOMETRY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_DRIVE_GEOMETRY


---

## UF_CAM_ERROR_INVALID_DRIVE_METHOD

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_DRIVE_METHOD


---

## UF_CAM_ERROR_INVALID_EVENT_INDEX

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_EVENT_INDEX


---

## UF_CAM_ERROR_INVALID_GROUP_DATA

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_GROUP_DATA


---

## UF_CAM_ERROR_INVALID_INDEX

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_INDEX


---

## UF_CAM_ERROR_INVALID_INHERITED_ENTITY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_INHERITED_ENTITY


---

## UF_CAM_ERROR_INVALID_INPUT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_INPUT


---

## UF_CAM_ERROR_INVALID_INPUT_ENTITY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_INPUT_ENTITY


---

## UF_CAM_ERROR_INVALID_INSP_BASE_DIR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_INSP_BASE_DIR


---

## UF_CAM_ERROR_INVALID_LENGTH

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_LENGTH


---

## UF_CAM_ERROR_INVALID_PARAMETER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_PARAMETER


---

## UF_CAM_ERROR_INVALID_PATH_STRUCTURE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_PATH_STRUCTURE


---

## UF_CAM_ERROR_INVALID_POCKET_NUM_OF_TOOLS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_POCKET_NUM_OF_TOOLS


---

## UF_CAM_ERROR_INVALID_RADIUS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_RADIUS


---

## UF_CAM_ERROR_INVALID_TAPER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_TAPER


---

## UF_CAM_ERROR_INVALID_TURN_WORKPIECE_DIAMETER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_TURN_WORKPIECE_DIAMETER


---

## UF_CAM_ERROR_INVALID_TURN_WORKPIECE_DIRECTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_TURN_WORKPIECE_DIRECTION


---

## UF_CAM_ERROR_INVALID_TURN_WORKPIECE_INNER_DIAMETER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_TURN_WORKPIECE_INNER_DIAMETER


---

## UF_CAM_ERROR_INVALID_TURN_WORKPIECE_LENGTH

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_TURN_WORKPIECE_LENGTH


---

## UF_CAM_ERROR_INVALID_TURN_WORKPIECE_STOCK

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_TURN_WORKPIECE_STOCK


---

## UF_CAM_ERROR_INVALID_TYPE_OF_WORKPIECE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_TYPE_OF_WORKPIECE


---

## UF_CAM_ERROR_INVALID_WORKFLOW_CONFIG

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_INVALID_WORKFLOW_CONFIG


---

## UF_CAM_ERROR_IPW_DOES_NOT_EXIST

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_IPW_DOES_NOT_EXIST


---

## UF_CAM_ERROR_LEGACY_OFFSET_NOT_ALLOWED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_LEGACY_OFFSET_NOT_ALLOWED


---

## UF_CAM_ERROR_LIBRARY_NOT_FOUND

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_LIBRARY_NOT_FOUND


---

## UF_CAM_ERROR_MANUFACTURING_SETUP

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_MANUFACTURING_SETUP


---

## UF_CAM_ERROR_MANUFACTURING_TEMPLATE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_MANUFACTURING_TEMPLATE


---

## UF_CAM_ERROR_MASTER_TEMPLATE_COMPLEX_MERGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_MASTER_TEMPLATE_COMPLEX_MERGE


---

## UF_CAM_ERROR_MRM_DND_LICENSE_REQUIRED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_MRM_DND_LICENSE_REQUIRED


---

## UF_CAM_ERROR_NOT_AUTO_BLANK

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_NOT_AUTO_BLANK


---

## UF_CAM_ERROR_NOT_LIBRARY_HOLDER

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_NOT_LIBRARY_HOLDER


---

## UF_CAM_ERROR_NOT_LIBRARY_TOOL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_NOT_LIBRARY_TOOL


---

## UF_CAM_ERROR_NOT_PLANAR_FACE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_NOT_PLANAR_FACE


---

## UF_CAM_ERROR_NO_CAM_SESSION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_NO_CAM_SESSION


---

## UF_CAM_ERROR_NO_CURRENT_OPT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_NO_CURRENT_OPT


---

## UF_CAM_ERROR_NO_CUT_METHOD

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_NO_CUT_METHOD


---

## UF_CAM_ERROR_NO_FEEDS_SPEEDS_LIBRARY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_NO_FEEDS_SPEEDS_LIBRARY


---

## UF_CAM_ERROR_NO_MATCHING_RECORD

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_NO_MATCHING_RECORD


---

## UF_CAM_ERROR_NO_MULTITOOL_ERROR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_NO_MULTITOOL_ERROR


---

## UF_CAM_ERROR_NO_PART_MATERIAL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_NO_PART_MATERIAL


---

## UF_CAM_ERROR_NO_PATH_EXISTS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_NO_PATH_EXISTS


---

## UF_CAM_ERROR_NO_ROBOT_CHAIN

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_NO_ROBOT_CHAIN


---

## UF_CAM_ERROR_NO_SETUP

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_NO_SETUP


---

## UF_CAM_ERROR_NO_TOOL_MATERIAL

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_NO_TOOL_MATERIAL


---

## UF_CAM_ERROR_OBJECT_IS_NOT_TAGGED_OBJECT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_OBJECT_IS_NOT_TAGGED_OBJECT


---

## UF_CAM_ERROR_OBJECT_NOT_DESIRED_CLASS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_OBJECT_NOT_DESIRED_CLASS


---

## UF_CAM_ERROR_PATH_CREATION_FAILED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_PATH_CREATION_FAILED


---

## UF_CAM_ERROR_PATH_EVENT_CREATION_FAILED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_PATH_EVENT_CREATION_FAILED


---

## UF_CAM_ERROR_PATH_EVENT_NOT_CORRECT_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_PATH_EVENT_NOT_CORRECT_TYPE


---

## UF_CAM_ERROR_PLANE_NOT_DEFINED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_PLANE_NOT_DEFINED


---

## UF_CAM_ERROR_POINT_NOT_FOUND

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_POINT_NOT_FOUND


---

## UF_CAM_ERROR_PREFERENCE_NOT_DEFINED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_PREFERENCE_NOT_DEFINED


---

## UF_CAM_ERROR_READ_ONLY_PARAM

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_READ_ONLY_PARAM


---

## UF_CAM_ERROR_REMOVE_DEPENDENCIES

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_REMOVE_DEPENDENCIES


---

## UF_CAM_ERROR_RESTORE_DEPENDENCIES

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_RESTORE_DEPENDENCIES


---

## UF_CAM_ERROR_SAVE_SPINNING_IPW_AS_PART

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_SAVE_SPINNING_IPW_AS_PART


---

## UF_CAM_ERROR_SINGLE_RANGE_NOT_CHANGED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_SINGLE_RANGE_NOT_CHANGED


---

## UF_CAM_ERROR_SOLID_TOOL_NOT_LOADED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_SOLID_TOOL_NOT_LOADED


---

## UF_CAM_ERROR_TAG_IS_NOT_TAGGED_OBJECT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_TAG_IS_NOT_TAGGED_OBJECT


---

## UF_CAM_ERROR_TAG_NOT_CORRECT_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_TAG_NOT_CORRECT_TYPE


---

## UF_CAM_ERROR_TEMPLATE_OBJECT_UI_DIFFERENT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_TEMPLATE_OBJECT_UI_DIFFERENT


---

## UF_CAM_ERROR_TEMPLATE_OBJECT_VALUE_DIFFERENT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_TEMPLATE_OBJECT_VALUE_DIFFERENT


---

## UF_CAM_ERROR_TOOLS_NOT_SAME_SUBTYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_TOOLS_NOT_SAME_SUBTYPE


---

## UF_CAM_ERROR_TOOLS_NOT_SAME_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_TOOLS_NOT_SAME_TYPE


---

## UF_CAM_ERROR_TURNING_BOUNDARY_ONLY_ONE_ALLOWED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_TURNING_BOUNDARY_ONLY_ONE_ALLOWED


---

## UF_CAM_ERROR_TYPE_TEMPLATE_OBJECT_INVALID_PARENT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_TYPE_TEMPLATE_OBJECT_INVALID_PARENT


---

## UF_CAM_ERROR_TYPE_TEMPLATE_STRUCTURE_DIFFERENT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_TYPE_TEMPLATE_STRUCTURE_DIFFERENT


---

## UF_CAM_ERROR_UI_CUSTOMIZATION_EXPLORER_FAILURE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_UI_CUSTOMIZATION_EXPLORER_FAILURE


---

## UF_CAM_ERROR_UI_DIALOG_ERROR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_UI_DIALOG_ERROR


---

## UF_CAM_ERROR_UI_UNKNOWN_ERROR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_UI_UNKNOWN_ERROR


---

## UF_CAM_ERROR_UNDEFINED_TURN_WORKPIECE_TYPE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_UNDEFINED_TURN_WORKPIECE_TYPE


---

## UF_CAM_ERROR_UPDATE_GEOMETRY_DEPENDENCIES

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_ERROR_UPDATE_GEOMETRY_DEPENDENCIES


---

## UF_CAM_MAX_TEMPLATE_SET_NAME_BUFSIZE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam.html#UF_CAM_MAX_TEMPLATE_SET_NAME_BUFSIZE


---

## UF_CAM_MAX_TEMPLATE_SET_NAME_LEN

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam.html#UF_CAM_MAX_TEMPLATE_SET_NAME_LEN


---

## UF_CAM_MAX_TEMPLATE_SET_NAME_NCHARS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam.html#UF_CAM_MAX_TEMPLATE_SET_NAME_NCHARS


---

## UF_CAM_OLD_H

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_spec.html#UF_CAM_OLD_H


---

## UF_CAM_PREF_ask_data_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_PREF_ask_data_type


---

## UF_CAM_PREF_ask_integer_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_PREF_ask_integer_value


---

## UF_CAM_PREF_ask_logical_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_PREF_ask_logical_value


---

## UF_CAM_PREF_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/types.html#UF_CAM_PREF_e


---

## UF_CAM_PREF_set_integer_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_PREF_set_integer_value


---

## UF_CAM_PREF_set_logical_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_PREF_set_logical_value


---

## UF_CAM_PREPRO_ERROR_BASE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_prepro.html#UF_CAM_PREPRO_ERROR_BASE


---

## UF_CAM_PREPRO_init_module

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_PREPRO_init_module


---

## UF_CAM_PREPRO_invalid_model

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_prepro.html#UF_CAM_PREPRO_invalid_model


---

## UF_CAM_PREPRO_mark_model_as_cam

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_PREPRO_mark_model_as_cam


---

## UF_CAM_SESSION_ERROR_NO_SESSION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/uf_cam_errors.html#UF_CAM_SESSION_ERROR_NO_SESSION


---

## UF_CAM_ask_auto_blank

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_auto_blank


---

## UF_CAM_ask_blank_matl_db_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_blank_matl_db_object


---

## UF_CAM_ask_cam_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_cam_preferences


---

## UF_CAM_ask_clear_plane_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_clear_plane_data


---

## UF_CAM_ask_clear_plane_status

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_clear_plane_status


---

## UF_CAM_ask_clear_plane_tag

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_clear_plane_tag


---

## UF_CAM_ask_clear_plane_usage

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_clear_plane_usage


---

## UF_CAM_ask_config_file

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_config_file


---

## UF_CAM_ask_cutter_db_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_cutter_db_object


---

## UF_CAM_ask_doc_template_name

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_doc_template_name


---

## UF_CAM_ask_f_s_db_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_f_s_db_object


---

## UF_CAM_ask_leastsq_sphere

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_leastsq_sphere


---

## UF_CAM_ask_lower_limit_plane_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_lower_limit_plane_data


---

## UF_CAM_ask_lower_limit_plane_status

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_lower_limit_plane_status


---

## UF_CAM_ask_lower_limit_plane_tag

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_lower_limit_plane_tag


---

## UF_CAM_ask_lower_limit_plane_usage

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_lower_limit_plane_usage


---

## UF_CAM_ask_mach_tool_db_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_mach_tool_db_object


---

## UF_CAM_ask_opt_template_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_opt_template_object


---

## UF_CAM_ask_post_template_name

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_post_template_name


---

## UF_CAM_ask_tool_matl_db_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_ask_tool_matl_db_object


---

## UF_CAM_avoidance_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/types.html#UF_CAM_avoidance_type_e


---

## UF_CAM_blank_geom_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/types.html#UF_CAM_blank_geom_type_e


---

## UF_CAM_boundary_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/types.html#UF_CAM_boundary_type_e


---

## UF_CAM_feedrate_unit_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/types.html#UF_CAM_feedrate_unit_e


---

## UF_CAM_geom_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/types.html#UF_CAM_geom_type_e


---

## UF_CAM_init_session

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_init_session


---

## UF_CAM_is_session_initialized

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_is_session_initialized


---

## UF_CAM_material_side_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/types.html#UF_CAM_material_side_e


---

## UF_CAM_opt_add_template_part

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_opt_add_template_part


---

## UF_CAM_opt_add_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_opt_add_type


---

## UF_CAM_opt_ask_clsf_names

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_opt_ask_clsf_names


---

## UF_CAM_opt_ask_doc_names

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_opt_ask_doc_names


---

## UF_CAM_opt_ask_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_opt_ask_object


---

## UF_CAM_opt_ask_post_names

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_opt_ask_post_names


---

## UF_CAM_opt_ask_subtypes

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_opt_ask_subtypes


---

## UF_CAM_opt_ask_types

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_opt_ask_types


---

## UF_CAM_opt_stype_cls_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/types.html#UF_CAM_opt_stype_cls_e


---

## UF_CAM_preferences_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/UF_CAM_preferences_s.html


---

## UF_CAM_reinit_opt

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_reinit_opt


---

## UF_CAM_reinit_session

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_reinit_session


---

## UF_CAM_set_auto_blank

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_set_auto_blank


---

## UF_CAM_set_cam_preferences

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_set_cam_preferences


---

## UF_CAM_set_clear_plane_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_set_clear_plane_data


---

## UF_CAM_set_clear_plane_status

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_set_clear_plane_status


---

## UF_CAM_set_clear_plane_tag

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_set_clear_plane_tag


---

## UF_CAM_set_clear_plane_usage

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_set_clear_plane_usage


---

## UF_CAM_set_lower_limit_plane_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_set_lower_limit_plane_data


---

## UF_CAM_set_lower_limit_plane_status

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_set_lower_limit_plane_status


---

## UF_CAM_set_lower_limit_plane_tag

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_set_lower_limit_plane_tag


---

## UF_CAM_set_lower_limit_plane_usage

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_set_lower_limit_plane_usage


---

## UF_CAM_set_material

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_set_material


---

## UF_CAM_tool_position_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/types.html#UF_CAM_tool_position_e


---

## UF_CAM_update_list_object_customization

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_update_list_object_customization


---

## UF_CAM_update_single_object_customization

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_update_single_object_customization


---

## UF_CAM_wizard_ask_current_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_wizard_ask_current_object


---

## UF_CAM_wizard_set_current_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/global.html#UF_CAM_wizard_set_current_object


---

## uf_cam.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/intro.html#uf_cam


---

## uf_cam_errors.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/intro.html#uf_cam_errors


---

## uf_cam_planes.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/intro.html#uf_cam_planes


---

## uf_cam_prefs.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/intro.html#uf_cam_prefs


---

## uf_cam_prepro.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/intro.html#uf_cam_prepro


---

## uf_cam_spec.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/intro.html#uf_cam_spec


---

## uf_cambnd.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/intro.html#uf_cambnd


---

## uf_camgeom.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/intro.html#uf_camgeom


---

## uf_camtext.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_cam/intro.html#uf_camtext


---
