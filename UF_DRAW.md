# UF_DRAW 函数参考

> 共 339 个函数

---

## 目录

- [UF_DRAW #Defines](#uf_draw #defines)
- [UF_DRAW Enumerations](#uf_draw enumerations)
- [UF_DRAW Files](#uf_draw files)
- [UF_DRAW Functions](#uf_draw functions)
- [UF_DRAW Structures](#uf_draw structures)
- [UF_DRAW Unions](#uf_draw unions)
- [UF_DRAW_CURVE_HLP_ATTR](#uf_draw_curve_hlp_attr)
- [UF_DRAW_CURVE_HLR_ATTR](#uf_draw_curve_hlr_attr)
- [UF_DRAW_DRAWING_VIEW](#uf_draw_drawing_view)
- [UF_DRAW_ERROR_BASE](#uf_draw_error_base)
- [UF_DRAW_ERROR_RANGE](#uf_draw_error_range)
- [UF_DRAW_MAX_LABEL_LEN](#uf_draw_max_label_len)
- [UF_DRAW_MAX_LETTER_BUFSIZE](#uf_draw_max_letter_bufsize)
- [UF_DRAW_MAX_LETTER_LEN](#uf_draw_max_letter_len)
- [UF_DRAW_MAX_LETTER_NCHARS](#uf_draw_max_letter_nchars)
- [UF_DRAW_MAX_NUM_STEP_SXSEGS](#uf_draw_max_num_step_sxsegs)
- [UF_DRAW_MAX_NUM_SXSEGS](#uf_draw_max_num_sxsegs)
- [UF_DRAW_MODELING_VIEW](#uf_draw_modeling_view)
- [UF_DRAW_NO_ERRORS](#uf_draw_no_errors)
- [UF_DRAW_NUM_VIEW_PARMS](#uf_draw_num_view_parms)
- [UF_DRAW_SECTION_ATTR](#uf_draw_section_attr)
- [UF_DRAW_WARNING](#uf_draw_warning)
- [UF_DRAW_add_auxiliary_view](#uf_draw_add_auxiliary_view)
- [UF_DRAW_add_circ_detail_view](#uf_draw_add_circ_detail_view)
- [UF_DRAW_add_detail_view](#uf_draw_add_detail_view)
- [UF_DRAW_add_orthographic_view](#uf_draw_add_orthographic_view)
- [UF_DRAW_add_sxline_sxseg](#uf_draw_add_sxline_sxseg)
- [UF_DRAW_add_sxseg](#uf_draw_add_sxseg)
- [UF_DRAW_arrow_parms_s](#uf_draw_arrow_parms_s)
- [UF_DRAW_arw_head_cntl_e](#uf_draw_arw_head_cntl_e)
- [UF_DRAW_arw_head_type_e](#uf_draw_arw_head_type_e)
- [UF_DRAW_ask_auto_update](#uf_draw_ask_auto_update)
- [UF_DRAW_ask_body_sils_in_view](#uf_draw_ask_body_sils_in_view)
- [UF_DRAW_ask_border_color](#uf_draw_ask_border_color)
- [UF_DRAW_ask_border_display](#uf_draw_ask_border_display)
- [UF_DRAW_ask_bound_by_objects](#uf_draw_ask_bound_by_objects)
- [UF_DRAW_ask_boundary_curves](#uf_draw_ask_boundary_curves)
- [UF_DRAW_ask_boundary_type](#uf_draw_ask_boundary_type)
- [UF_DRAW_ask_break_region_data](#uf_draw_ask_break_region_data)
- [UF_DRAW_ask_break_regions](#uf_draw_ask_break_regions)
- [UF_DRAW_ask_breakout_data](#uf_draw_ask_breakout_data)
- [UF_DRAW_ask_comp_section_in_view](#uf_draw_ask_comp_section_in_view)
- [UF_DRAW_ask_current_drawing](#uf_draw_ask_current_drawing)
- [UF_DRAW_ask_curve_group_members](#uf_draw_ask_curve_group_members)
- [UF_DRAW_ask_curve_of_sxedge](#uf_draw_ask_curve_of_sxedge)
- [UF_DRAW_ask_display_state](#uf_draw_ask_display_state)
- [UF_DRAW_ask_displayed_objects](#uf_draw_ask_displayed_objects)
- [UF_DRAW_ask_dmv_rotation_plane](#uf_draw_ask_dmv_rotation_plane)
- [UF_DRAW_ask_drafting_curve_parents](#uf_draw_ask_drafting_curve_parents)
- [UF_DRAW_ask_drafting_curve_type](#uf_draw_ask_drafting_curve_type)
- [UF_DRAW_ask_drawing_info](#uf_draw_ask_drawing_info)
- [UF_DRAW_ask_drawing_of_view](#uf_draw_ask_drawing_of_view)
- [UF_DRAW_ask_drawing_ref_pt](#uf_draw_ask_drawing_ref_pt)
- [UF_DRAW_ask_drawings](#uf_draw_ask_drawings)
- [UF_DRAW_ask_face_of_sil](#uf_draw_ask_face_of_sil)
- [UF_DRAW_ask_face_sils_in_view](#uf_draw_ask_face_sils_in_view)
- [UF_DRAW_ask_folded_sxline](#uf_draw_ask_folded_sxline)
- [UF_DRAW_ask_group_of_curve](#uf_draw_ask_group_of_curve)
- [UF_DRAW_ask_half_sxline](#uf_draw_ask_half_sxline)
- [UF_DRAW_ask_num_drawings](#uf_draw_ask_num_drawings)
- [UF_DRAW_ask_num_views](#uf_draw_ask_num_views)
- [UF_DRAW_ask_pictorial_sxline](#uf_draw_ask_pictorial_sxline)
- [UF_DRAW_ask_render_set_objects](#uf_draw_ask_render_set_objects)
- [UF_DRAW_ask_render_set_parms](#uf_draw_ask_render_set_parms)
- [UF_DRAW_ask_render_sets](#uf_draw_ask_render_sets)
- [UF_DRAW_ask_render_sets_of_view](#uf_draw_ask_render_sets_of_view)
- [UF_DRAW_ask_revolved_sxline](#uf_draw_ask_revolved_sxline)
- [UF_DRAW_ask_simple_sxline](#uf_draw_ask_simple_sxline)
- [UF_DRAW_ask_simplified_curve](#uf_draw_ask_simplified_curve)
- [UF_DRAW_ask_solid_of_section](#uf_draw_ask_solid_of_section)
- [UF_DRAW_ask_stepped_sxline](#uf_draw_ask_stepped_sxline)
- [UF_DRAW_ask_suppress_view_updat](#uf_draw_ask_suppress_view_updat)
- [UF_DRAW_ask_sxedges_of_sxsolid](#uf_draw_ask_sxedges_of_sxsolid)
- [UF_DRAW_ask_sxline_default_prfs](#uf_draw_ask_sxline_default_prfs)
- [UF_DRAW_ask_sxline_display](#uf_draw_ask_sxline_display)
- [UF_DRAW_ask_sxline_of_sxview](#uf_draw_ask_sxline_of_sxview)
- [UF_DRAW_ask_sxline_sxseg](#uf_draw_ask_sxline_sxseg)
- [UF_DRAW_ask_sxline_type](#uf_draw_ask_sxline_type)
- [UF_DRAW_ask_sxsolids_of_sxview](#uf_draw_ask_sxsolids_of_sxview)
- [UF_DRAW_ask_sxview_display](#uf_draw_ask_sxview_display)
- [UF_DRAW_ask_unfolded_sxline](#uf_draw_ask_unfolded_sxline)
- [UF_DRAW_ask_view_anchor](#uf_draw_ask_view_anchor)
- [UF_DRAW_ask_view_angle](#uf_draw_ask_view_angle)
- [UF_DRAW_ask_view_borders](#uf_draw_ask_view_borders)
- [UF_DRAW_ask_view_display](#uf_draw_ask_view_display)
- [UF_DRAW_ask_view_label](#uf_draw_ask_view_label)
- [UF_DRAW_ask_view_label_parms](#uf_draw_ask_view_label_parms)
- [UF_DRAW_ask_view_notes](#uf_draw_ask_view_notes)
- [UF_DRAW_ask_view_of_drawing](#uf_draw_ask_view_of_drawing)
- [UF_DRAW_ask_view_of_note](#uf_draw_ask_view_of_note)
- [UF_DRAW_ask_view_of_view_label](#uf_draw_ask_view_of_view_label)
- [UF_DRAW_ask_view_parm_scale](#uf_draw_ask_view_parm_scale)
- [UF_DRAW_ask_view_scale](#uf_draw_ask_view_scale)
- [UF_DRAW_ask_view_status](#uf_draw_ask_view_status)
- [UF_DRAW_ask_view_thd_app_pitch](#uf_draw_ask_view_thd_app_pitch)
- [UF_DRAW_ask_view_thd_meth](#uf_draw_ask_view_thd_meth)
- [UF_DRAW_ask_views](#uf_draw_ask_views)
- [UF_DRAW_ask_xhatch_of_sxsolid](#uf_draw_ask_xhatch_of_sxsolid)
- [UF_DRAW_associative_views](#uf_draw_associative_views)
- [UF_DRAW_attach_note_to_view](#uf_draw_attach_note_to_view)
- [UF_DRAW_bad_arrow_dist_past_part](#uf_draw_bad_arrow_dist_past_part)
- [UF_DRAW_bad_arrow_head_control](#uf_draw_bad_arrow_head_control)
- [UF_DRAW_bad_arrow_head_type](#uf_draw_bad_arrow_head_type)
- [UF_DRAW_bad_arrow_incl_angle](#uf_draw_bad_arrow_incl_angle)
- [UF_DRAW_bad_arrow_len](#uf_draw_bad_arrow_len)
- [UF_DRAW_bad_arrow_size](#uf_draw_bad_arrow_size)
- [UF_DRAW_bad_arrow_stub_len](#uf_draw_bad_arrow_stub_len)
- [UF_DRAW_bad_num_leg1_sxsegs](#uf_draw_bad_num_leg1_sxsegs)
- [UF_DRAW_bad_num_step_sxsegs](#uf_draw_bad_num_step_sxsegs)
- [UF_DRAW_bad_num_sxsegs](#uf_draw_bad_num_sxsegs)
- [UF_DRAW_bad_sxline_display](#uf_draw_bad_sxline_display)
- [UF_DRAW_bad_sxview_scale](#uf_draw_bad_sxview_scale)
- [UF_DRAW_boundary_not_smart](#uf_draw_boundary_not_smart)
- [UF_DRAW_boundary_type_e](#uf_draw_boundary_type_e)
- [UF_DRAW_break_position_type_e](#uf_draw_break_position_type_e)
- [UF_DRAW_break_region_boundary_s](#uf_draw_break_region_boundary_s)
- [UF_DRAW_break_region_data_s](#uf_draw_break_region_data_s)
- [UF_DRAW_breakout_data_s](#uf_draw_breakout_data_s)
- [UF_DRAW_cannot_assoc_object](#uf_draw_cannot_assoc_object)
- [UF_DRAW_comp_section_in_view_e](#uf_draw_comp_section_in_view_e)
- [UF_DRAW_copy_view](#uf_draw_copy_view)
- [UF_DRAW_create_break_region](#uf_draw_create_break_region)
- [UF_DRAW_create_breakout](#uf_draw_create_breakout)
- [UF_DRAW_create_drawing](#uf_draw_create_drawing)
- [UF_DRAW_create_half_sxview](#uf_draw_create_half_sxview)
- [UF_DRAW_create_render_set](#uf_draw_create_render_set)
- [UF_DRAW_create_revolved_sxview](#uf_draw_create_revolved_sxview)
- [UF_DRAW_create_simple_sxview](#uf_draw_create_simple_sxview)
- [UF_DRAW_create_simplified_curve](#uf_draw_create_simplified_curve)
- [UF_DRAW_create_stepped_sxview](#uf_draw_create_stepped_sxview)
- [UF_DRAW_create_sxview_from_dmv](#uf_draw_create_sxview_from_dmv)
- [UF_DRAW_create_unfolded_sxview](#uf_draw_create_unfolded_sxview)
- [UF_DRAW_create_view_label](#uf_draw_create_view_label)
- [UF_DRAW_curve_is_associative](#uf_draw_curve_is_associative)
- [UF_DRAW_data_source_e](#uf_draw_data_source_e)
- [UF_DRAW_define_bound_by_objects](#uf_draw_define_bound_by_objects)
- [UF_DRAW_define_boundary_s](#uf_draw_define_boundary_s)
- [UF_DRAW_define_view_auto_rect](#uf_draw_define_view_auto_rect)
- [UF_DRAW_define_view_boundary](#uf_draw_define_view_boundary)
- [UF_DRAW_define_view_boundary1](#uf_draw_define_view_boundary1)
- [UF_DRAW_define_view_manual_rect](#uf_draw_define_view_manual_rect)
- [UF_DRAW_delete_drawing](#uf_draw_delete_drawing)
- [UF_DRAW_delete_sxline_sxseg](#uf_draw_delete_sxline_sxseg)
- [UF_DRAW_delete_view_label](#uf_draw_delete_view_label)
- [UF_DRAW_design_in_context](#uf_draw_design_in_context)
- [UF_DRAW_detach_note_from_view](#uf_draw_detach_note_from_view)
- [UF_DRAW_drafting_curve_type_e](#uf_draw_drafting_curve_type_e)
- [UF_DRAW_drawing_already_exists](#uf_draw_drawing_already_exists)
- [UF_DRAW_dwg_is_displayed](#uf_draw_dwg_is_displayed)
- [UF_DRAW_dwg_not_current](#uf_draw_dwg_not_current)
- [UF_DRAW_edge_hiding_edge_e](#uf_draw_edge_hiding_edge_e)
- [UF_DRAW_edit_boundary_point](#uf_draw_edit_boundary_point)
- [UF_DRAW_edit_sxline_display](#uf_draw_edit_sxline_display)
- [UF_DRAW_english_size_e](#uf_draw_english_size_e)
- [UF_DRAW_erase_sxview_objects](#uf_draw_erase_sxview_objects)
- [UF_DRAW_extracted_edges_e](#uf_draw_extracted_edges_e)
- [UF_DRAW_free_boundary](#uf_draw_free_boundary)
- [UF_DRAW_gap_e](#uf_draw_gap_e)
- [UF_DRAW_get_view_model_view_part](#uf_draw_get_view_model_view_part)
- [UF_DRAW_half_sxsegs_s](#uf_draw_half_sxsegs_s)
- [UF_DRAW_hidden_line_e](#uf_draw_hidden_line_e)
- [UF_DRAW_import_view](#uf_draw_import_view)
- [UF_DRAW_info_s](#uf_draw_info_s)
- [UF_DRAW_initialize_view_info](#uf_draw_initialize_view_info)
- [UF_DRAW_invalid_anchor_point](#uf_draw_invalid_anchor_point)
- [UF_DRAW_invalid_arrow_dir](#uf_draw_invalid_arrow_dir)
- [UF_DRAW_invalid_assoc_modifier](#uf_draw_invalid_assoc_modifier)
- [UF_DRAW_invalid_boundary_curves](#uf_draw_invalid_boundary_curves)
- [UF_DRAW_invalid_drawing_name](#uf_draw_invalid_drawing_name)
- [UF_DRAW_invalid_drawing_size_values](#uf_draw_invalid_drawing_size_values)
- [UF_DRAW_invalid_dwg_pos](#uf_draw_invalid_dwg_pos)
- [UF_DRAW_invalid_hinge_dir](#uf_draw_invalid_hinge_dir)
- [UF_DRAW_invalid_note](#uf_draw_invalid_note)
- [UF_DRAW_invalid_number_of_copies](#uf_draw_invalid_number_of_copies)
- [UF_DRAW_invalid_object_assoc](#uf_draw_invalid_object_assoc)
- [UF_DRAW_invalid_object_view](#uf_draw_invalid_object_view)
- [UF_DRAW_invalid_parameter](#uf_draw_invalid_parameter)
- [UF_DRAW_invalid_parameter_value](#uf_draw_invalid_parameter_value)
- [UF_DRAW_invalid_pen_number](#uf_draw_invalid_pen_number)
- [UF_DRAW_invalid_pen_option](#uf_draw_invalid_pen_option)
- [UF_DRAW_invalid_plot_scale](#uf_draw_invalid_plot_scale)
- [UF_DRAW_invalid_size_code_value](#uf_draw_invalid_size_code_value)
- [UF_DRAW_invalid_spline](#uf_draw_invalid_spline)
- [UF_DRAW_invalid_step_dir](#uf_draw_invalid_step_dir)
- [UF_DRAW_invalid_sxline_leg](#uf_draw_invalid_sxline_leg)
- [UF_DRAW_invalid_sxseg_type](#uf_draw_invalid_sxseg_type)
- [UF_DRAW_invalid_tabnot_cell](#uf_draw_invalid_tabnot_cell)
- [UF_DRAW_invalid_units_value](#uf_draw_invalid_units_value)
- [UF_DRAW_invalid_view](#uf_draw_invalid_view)
- [UF_DRAW_invalid_view_bound_type](#uf_draw_invalid_view_bound_type)
- [UF_DRAW_invalid_view_type](#uf_draw_invalid_view_type)
- [UF_DRAW_is_drafting_component](#uf_draw_is_drafting_component)
- [UF_DRAW_is_object_out_of_date](#uf_draw_is_object_out_of_date)
- [UF_DRAW_is_sxview](#uf_draw_is_sxview)
- [UF_DRAW_is_thread_curve](#uf_draw_is_thread_curve)
- [UF_DRAW_label_on_parent_type_t](#uf_draw_label_on_parent_type_t)
- [UF_DRAW_metric_size_e](#uf_draw_metric_size_e)
- [UF_DRAW_move_sxline_rotpt](#uf_draw_move_sxline_rotpt)
- [UF_DRAW_move_sxline_sxseg](#uf_draw_move_sxline_sxseg)
- [UF_DRAW_move_sxseg](#uf_draw_move_sxseg)
- [UF_DRAW_move_view](#uf_draw_move_view)
- [UF_DRAW_move_view_to_drawing](#uf_draw_move_view_to_drawing)
- [UF_DRAW_no_add_to_half_sxline](#uf_draw_no_add_to_half_sxline)
- [UF_DRAW_no_arc_center](#uf_draw_no_arc_center)
- [UF_DRAW_no_current_drawing](#uf_draw_no_current_drawing)
- [UF_DRAW_no_cut_in_leg1](#uf_draw_no_cut_in_leg1)
- [UF_DRAW_no_cut_in_leg2](#uf_draw_no_cut_in_leg2)
- [UF_DRAW_no_delete_half_sxline](#uf_draw_no_delete_half_sxline)
- [UF_DRAW_no_drawing_view](#uf_draw_no_drawing_view)
- [UF_DRAW_no_dwg_of_dwg_view](#uf_draw_no_dwg_of_dwg_view)
- [UF_DRAW_no_end_point](#uf_draw_no_end_point)
- [UF_DRAW_no_intersection](#uf_draw_no_intersection)
- [UF_DRAW_no_more_tabnot_fonts](#uf_draw_no_more_tabnot_fonts)
- [UF_DRAW_no_more_tabnot_sizes](#uf_draw_no_more_tabnot_sizes)
- [UF_DRAW_no_more_views_to_dwg](#uf_draw_no_more_views_to_dwg)
- [UF_DRAW_no_view_created](#uf_draw_no_view_created)
- [UF_DRAW_not_two_cuts_defined](#uf_draw_not_two_cuts_defined)
- [UF_DRAW_null_object](#uf_draw_null_object)
- [UF_DRAW_object_is_not_linear](#uf_draw_object_is_not_linear)
- [UF_DRAW_object_is_view_dep](#uf_draw_object_is_view_dep)
- [UF_DRAW_open_drawing](#uf_draw_open_drawing)
- [UF_DRAW_parameter_type_wrong](#uf_draw_parameter_type_wrong)
- [UF_DRAW_parent_view_out_of_date](#uf_draw_parent_view_out_of_date)
- [UF_DRAW_part_not_loaded](#uf_draw_part_not_loaded)
- [UF_DRAW_pen_assignment_e](#uf_draw_pen_assignment_e)
- [UF_DRAW_plotter_data_s](#uf_draw_plotter_data_s)
- [UF_DRAW_point_not_on_drawing](#uf_draw_point_not_on_drawing)
- [UF_DRAW_point_not_smart](#uf_draw_point_not_smart)
- [UF_DRAW_point_not_visible](#uf_draw_point_not_visible)
- [UF_DRAW_proj_dir_e](#uf_draw_proj_dir_e)
- [UF_DRAW_projection_angle_e](#uf_draw_projection_angle_e)
- [UF_DRAW_pview_not_detail_view](#uf_draw_pview_not_detail_view)
- [UF_DRAW_pview_not_dwg_view](#uf_draw_pview_not_dwg_view)
- [UF_DRAW_pview_not_sxview](#uf_draw_pview_not_sxview)
- [UF_DRAW_redefine_sxline_hinge](#uf_draw_redefine_sxline_hinge)
- [UF_DRAW_remove_break_region](#uf_draw_remove_break_region)
- [UF_DRAW_remove_breakout](#uf_draw_remove_breakout)
- [UF_DRAW_remove_dmv_rotation_plane](#uf_draw_remove_dmv_rotation_plane)
- [UF_DRAW_rename_drawing](#uf_draw_rename_drawing)
- [UF_DRAW_render_prefs_s](#uf_draw_render_prefs_s)
- [UF_DRAW_retrieve_drawing_cgm](#uf_draw_retrieve_drawing_cgm)
- [UF_DRAW_secondary_indexing_align_t](#uf_draw_secondary_indexing_align_t)
- [UF_DRAW_set_auto_update](#uf_draw_set_auto_update)
- [UF_DRAW_set_border_color](#uf_draw_set_border_color)
- [UF_DRAW_set_border_display](#uf_draw_set_border_display)
- [UF_DRAW_set_boundary_assoc](#uf_draw_set_boundary_assoc)
- [UF_DRAW_set_break_region_data](#uf_draw_set_break_region_data)
- [UF_DRAW_set_breakout_data](#uf_draw_set_breakout_data)
- [UF_DRAW_set_comp_section_in_view](#uf_draw_set_comp_section_in_view)
- [UF_DRAW_set_display_state](#uf_draw_set_display_state)
- [UF_DRAW_set_dmv_rotation_plane](#uf_draw_set_dmv_rotation_plane)
- [UF_DRAW_set_drawing_info](#uf_draw_set_drawing_info)
- [UF_DRAW_set_drawing_ref_pt](#uf_draw_set_drawing_ref_pt)
- [UF_DRAW_set_render_set_objects](#uf_draw_set_render_set_objects)
- [UF_DRAW_set_render_set_parms](#uf_draw_set_render_set_parms)
- [UF_DRAW_set_render_sets_for_view](#uf_draw_set_render_sets_for_view)
- [UF_DRAW_set_suppress_view_updat](#uf_draw_set_suppress_view_updat)
- [UF_DRAW_set_sxline_default_prfs](#uf_draw_set_sxline_default_prfs)
- [UF_DRAW_set_sxview_display](#uf_draw_set_sxview_display)
- [UF_DRAW_set_view_anchor](#uf_draw_set_view_anchor)
- [UF_DRAW_set_view_angle](#uf_draw_set_view_angle)
- [UF_DRAW_set_view_display](#uf_draw_set_view_display)
- [UF_DRAW_set_view_label_parms](#uf_draw_set_view_label_parms)
- [UF_DRAW_set_view_parm_scale](#uf_draw_set_view_parm_scale)
- [UF_DRAW_set_view_scale](#uf_draw_set_view_scale)
- [UF_DRAW_set_view_status](#uf_draw_set_view_status)
- [UF_DRAW_set_view_thd_app_pitch](#uf_draw_set_view_thd_app_pitch)
- [UF_DRAW_set_view_thd_meth](#uf_draw_set_view_thd_meth)
- [UF_DRAW_silhouette_e](#uf_draw_silhouette_e)
- [UF_DRAW_size_state_e](#uf_draw_size_state_e)
- [UF_DRAW_size_union_u](#uf_draw_size_union_u)
- [UF_DRAW_sketch_object](#uf_draw_sketch_object)
- [UF_DRAW_smooth_e](#uf_draw_smooth_e)
- [UF_DRAW_sx_assy_xhatch_e](#uf_draw_sx_assy_xhatch_e)
- [UF_DRAW_sx_background_e](#uf_draw_sx_background_e)
- [UF_DRAW_sx_crosshatch_e](#uf_draw_sx_crosshatch_e)
- [UF_DRAW_sx_section_sheet_body_e](#uf_draw_sx_section_sheet_body_e)
- [UF_DRAW_sxline_display_e](#uf_draw_sxline_display_e)
- [UF_DRAW_sxline_leg_e](#uf_draw_sxline_leg_e)
- [UF_DRAW_sxline_not_correct_type](#uf_draw_sxline_not_correct_type)
- [UF_DRAW_sxline_status_e](#uf_draw_sxline_status_e)
- [UF_DRAW_sxline_sxsegs_s](#uf_draw_sxline_sxsegs_s)
- [UF_DRAW_sxline_type_e](#uf_draw_sxline_type_e)
- [UF_DRAW_sxseg_highlight_e](#uf_draw_sxseg_highlight_e)
- [UF_DRAW_sxseg_info_s](#uf_draw_sxseg_info_s)
- [UF_DRAW_sxseg_mode_e](#uf_draw_sxseg_mode_e)
- [UF_DRAW_sxseg_type_e](#uf_draw_sxseg_type_e)
- [UF_DRAW_sxview_prfs_s](#uf_draw_sxview_prfs_s)
- [UF_DRAW_tag_is_null](#uf_draw_tag_is_null)
- [UF_DRAW_tag_not_drawing](#uf_draw_tag_not_drawing)
- [UF_DRAW_tag_not_sxedge](#uf_draw_tag_not_sxedge)
- [UF_DRAW_tag_not_sxline](#uf_draw_tag_not_sxline)
- [UF_DRAW_tag_not_sxseg](#uf_draw_tag_not_sxseg)
- [UF_DRAW_tag_not_sxsolid](#uf_draw_tag_not_sxsolid)
- [UF_DRAW_tag_not_sxview](#uf_draw_tag_not_sxview)
- [UF_DRAW_tag_not_view](#uf_draw_tag_not_view)
- [UF_DRAW_tag_not_view_label](#uf_draw_tag_not_view_label)
- [UF_DRAW_thd_meth_e](#uf_draw_thd_meth_e)
- [UF_DRAW_unable_to_delete_view](#uf_draw_unable_to_delete_view)
- [UF_DRAW_unable_to_edit_bnd_point](#uf_draw_unable_to_edit_bnd_point)
- [UF_DRAW_unable_to_obtain_display_data](#uf_draw_unable_to_obtain_display_data)
- [UF_DRAW_unable_to_rotate_view](#uf_draw_unable_to_rotate_view)
- [UF_DRAW_unable_to_set_ref_pt](#uf_draw_unable_to_set_ref_pt)
- [UF_DRAW_unable_to_simplify_curve](#uf_draw_unable_to_simplify_curve)
- [UF_DRAW_unrecoverable_error](#uf_draw_unrecoverable_error)
- [UF_DRAW_upd_out_of_date_views](#uf_draw_upd_out_of_date_views)
- [UF_DRAW_update_one_view](#uf_draw_update_one_view)
- [UF_DRAW_uvhatch_e](#uf_draw_uvhatch_e)
- [UF_DRAW_vb_curve_crosses_curve](#uf_draw_vb_curve_crosses_curve)
- [UF_DRAW_vb_curve_disconnected](#uf_draw_vb_curve_disconnected)
- [UF_DRAW_vb_curve_self_intersects](#uf_draw_vb_curve_self_intersects)
- [UF_DRAW_vb_no_curve](#uf_draw_vb_no_curve)
- [UF_DRAW_vb_non_manifold_curve](#uf_draw_vb_non_manifold_curve)
- [UF_DRAW_view_already_exists](#uf_draw_view_already_exists)
- [UF_DRAW_view_boundary_s](#uf_draw_view_boundary_s)
- [UF_DRAW_view_cannot_be_made_ref](#uf_draw_view_cannot_be_made_ref)
- [UF_DRAW_view_indep_object](#uf_draw_view_indep_object)
- [UF_DRAW_view_info_s](#uf_draw_view_info_s)
- [UF_DRAW_view_is_expanded](#uf_draw_view_is_expanded)
- [UF_DRAW_view_is_facet_view](#uf_draw_view_is_facet_view)
- [UF_DRAW_view_is_not_active](#uf_draw_view_is_not_active)
- [UF_DRAW_view_is_not_member_view](#uf_draw_view_is_not_member_view)
- [UF_DRAW_view_label_letter_format_t](#uf_draw_view_label_letter_format_t)
- [UF_DRAW_view_label_parm_type_t](#uf_draw_view_label_parm_type_t)
- [UF_DRAW_view_label_parms_s](#uf_draw_view_label_parms_s)
- [UF_DRAW_view_label_position_t](#uf_draw_view_label_position_t)
- [UF_DRAW_view_label_scale_format_t](#uf_draw_view_label_scale_format_t)
- [UF_DRAW_view_label_scale_position_t](#uf_draw_view_label_scale_position_t)
- [UF_DRAW_view_label_view_text_type_t](#uf_draw_view_label_view_text_type_t)
- [UF_DRAW_view_not_on_current_drawing](#uf_draw_view_not_on_current_drawing)
- [UF_DRAW_view_not_on_drawing](#uf_draw_view_not_on_drawing)
- [UF_DRAW_view_pos_not_on_drawing](#uf_draw_view_pos_not_on_drawing)
- [UF_DRAW_view_prfs_s](#uf_draw_view_prfs_s)
- [UF_DRAW_view_status_e](#uf_draw_view_status_e)
- [UF_DRAW_virtual_intersect_e](#uf_draw_virtual_intersect_e)
- [UF_DRAW_vw_scale_is_not_parametric](#uf_draw_vw_scale_is_not_parametric)
- [uf_draw.h](#uf_draw.h)
- [uf_draw_errors.h](#uf_draw_errors.h)
- [uf_draw_types.h](#uf_draw_types.h)

---

## UF_DRAW #Defines

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/contents.html#defines


---

## UF_DRAW Enumerations

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/contents.html#enumerations


---

## UF_DRAW Files

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/contents.html#files


---

## UF_DRAW Functions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/contents.html#functions


---

## UF_DRAW Structures

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/contents.html#structures


---

## UF_DRAW Unions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/contents.html#unions


---

## UF_DRAW_CURVE_HLP_ATTR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_types.html#UF_DRAW_CURVE_HLP_ATTR


---

## UF_DRAW_CURVE_HLR_ATTR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_types.html#UF_DRAW_CURVE_HLR_ATTR


---

## UF_DRAW_DRAWING_VIEW

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw.html#UF_DRAW_DRAWING_VIEW


---

## UF_DRAW_ERROR_BASE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_ERROR_BASE


---

## UF_DRAW_ERROR_RANGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_ERROR_RANGE


---

## UF_DRAW_MAX_LABEL_LEN

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_types.html#UF_DRAW_MAX_LABEL_LEN


---

## UF_DRAW_MAX_LETTER_BUFSIZE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_types.html#UF_DRAW_MAX_LETTER_BUFSIZE


---

## UF_DRAW_MAX_LETTER_LEN

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_types.html#UF_DRAW_MAX_LETTER_LEN


---

## UF_DRAW_MAX_LETTER_NCHARS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_types.html#UF_DRAW_MAX_LETTER_NCHARS


---

## UF_DRAW_MAX_NUM_STEP_SXSEGS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_types.html#UF_DRAW_MAX_NUM_STEP_SXSEGS


---

## UF_DRAW_MAX_NUM_SXSEGS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_types.html#UF_DRAW_MAX_NUM_SXSEGS


---

## UF_DRAW_MODELING_VIEW

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw.html#UF_DRAW_MODELING_VIEW


---

## UF_DRAW_NO_ERRORS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_NO_ERRORS


---

## UF_DRAW_NUM_VIEW_PARMS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_types.html#UF_DRAW_NUM_VIEW_PARMS


---

## UF_DRAW_SECTION_ATTR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_types.html#UF_DRAW_SECTION_ATTR


---

## UF_DRAW_WARNING

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_WARNING


---

## UF_DRAW_add_auxiliary_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_add_auxiliary_view


---

## UF_DRAW_add_circ_detail_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_add_circ_detail_view


---

## UF_DRAW_add_detail_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_add_detail_view


---

## UF_DRAW_add_orthographic_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_add_orthographic_view


---

## UF_DRAW_add_sxline_sxseg

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_add_sxline_sxseg


---

## UF_DRAW_add_sxseg

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_add_sxseg


---

## UF_DRAW_arrow_parms_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/UF_DRAW_arrow_parms_s.html


---

## UF_DRAW_arw_head_cntl_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_arw_head_cntl_e


---

## UF_DRAW_arw_head_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_arw_head_type_e


---

## UF_DRAW_ask_auto_update

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_auto_update


---

## UF_DRAW_ask_body_sils_in_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_body_sils_in_view


---

## UF_DRAW_ask_border_color

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_border_color


---

## UF_DRAW_ask_border_display

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_border_display


---

## UF_DRAW_ask_bound_by_objects

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_bound_by_objects


---

## UF_DRAW_ask_boundary_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_boundary_curves


---

## UF_DRAW_ask_boundary_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_boundary_type


---

## UF_DRAW_ask_break_region_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_break_region_data


---

## UF_DRAW_ask_break_regions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_break_regions


---

## UF_DRAW_ask_breakout_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_breakout_data


---

## UF_DRAW_ask_comp_section_in_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_comp_section_in_view


---

## UF_DRAW_ask_current_drawing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_current_drawing


---

## UF_DRAW_ask_curve_group_members

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_curve_group_members


---

## UF_DRAW_ask_curve_of_sxedge

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_curve_of_sxedge


---

## UF_DRAW_ask_display_state

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_display_state


---

## UF_DRAW_ask_displayed_objects

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_displayed_objects


---

## UF_DRAW_ask_dmv_rotation_plane

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_dmv_rotation_plane


---

## UF_DRAW_ask_drafting_curve_parents

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_drafting_curve_parents


---

## UF_DRAW_ask_drafting_curve_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_drafting_curve_type


---

## UF_DRAW_ask_drawing_info

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_drawing_info


---

## UF_DRAW_ask_drawing_of_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_drawing_of_view


---

## UF_DRAW_ask_drawing_ref_pt

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_drawing_ref_pt


---

## UF_DRAW_ask_drawings

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_drawings


---

## UF_DRAW_ask_face_of_sil

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_face_of_sil


---

## UF_DRAW_ask_face_sils_in_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_face_sils_in_view


---

## UF_DRAW_ask_folded_sxline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_folded_sxline


---

## UF_DRAW_ask_group_of_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_group_of_curve


---

## UF_DRAW_ask_half_sxline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_half_sxline


---

## UF_DRAW_ask_num_drawings

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_num_drawings


---

## UF_DRAW_ask_num_views

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_num_views


---

## UF_DRAW_ask_pictorial_sxline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_pictorial_sxline


---

## UF_DRAW_ask_render_set_objects

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_render_set_objects


---

## UF_DRAW_ask_render_set_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_render_set_parms


---

## UF_DRAW_ask_render_sets

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_render_sets


---

## UF_DRAW_ask_render_sets_of_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_render_sets_of_view


---

## UF_DRAW_ask_revolved_sxline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_revolved_sxline


---

## UF_DRAW_ask_simple_sxline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_simple_sxline


---

## UF_DRAW_ask_simplified_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_simplified_curve


---

## UF_DRAW_ask_solid_of_section

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_solid_of_section


---

## UF_DRAW_ask_stepped_sxline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_stepped_sxline


---

## UF_DRAW_ask_suppress_view_updat

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_suppress_view_updat


---

## UF_DRAW_ask_sxedges_of_sxsolid

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_sxedges_of_sxsolid


---

## UF_DRAW_ask_sxline_default_prfs

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_sxline_default_prfs


---

## UF_DRAW_ask_sxline_display

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_sxline_display


---

## UF_DRAW_ask_sxline_of_sxview

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_sxline_of_sxview


---

## UF_DRAW_ask_sxline_sxseg

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_sxline_sxseg


---

## UF_DRAW_ask_sxline_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_sxline_type


---

## UF_DRAW_ask_sxsolids_of_sxview

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_sxsolids_of_sxview


---

## UF_DRAW_ask_sxview_display

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_sxview_display


---

## UF_DRAW_ask_unfolded_sxline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_unfolded_sxline


---

## UF_DRAW_ask_view_anchor

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_view_anchor


---

## UF_DRAW_ask_view_angle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_view_angle


---

## UF_DRAW_ask_view_borders

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_view_borders


---

## UF_DRAW_ask_view_display

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_view_display


---

## UF_DRAW_ask_view_label

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_view_label


---

## UF_DRAW_ask_view_label_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_view_label_parms


---

## UF_DRAW_ask_view_notes

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_view_notes


---

## UF_DRAW_ask_view_of_drawing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_view_of_drawing


---

## UF_DRAW_ask_view_of_note

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_view_of_note


---

## UF_DRAW_ask_view_of_view_label

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_view_of_view_label


---

## UF_DRAW_ask_view_parm_scale

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_view_parm_scale


---

## UF_DRAW_ask_view_scale

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_view_scale


---

## UF_DRAW_ask_view_status

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_view_status


---

## UF_DRAW_ask_view_thd_app_pitch

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_view_thd_app_pitch


---

## UF_DRAW_ask_view_thd_meth

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_view_thd_meth


---

## UF_DRAW_ask_views

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_views


---

## UF_DRAW_ask_xhatch_of_sxsolid

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_ask_xhatch_of_sxsolid


---

## UF_DRAW_associative_views

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_associative_views


---

## UF_DRAW_attach_note_to_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_attach_note_to_view


---

## UF_DRAW_bad_arrow_dist_past_part

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_bad_arrow_dist_past_part


---

## UF_DRAW_bad_arrow_head_control

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_bad_arrow_head_control


---

## UF_DRAW_bad_arrow_head_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_bad_arrow_head_type


---

## UF_DRAW_bad_arrow_incl_angle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_bad_arrow_incl_angle


---

## UF_DRAW_bad_arrow_len

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_bad_arrow_len


---

## UF_DRAW_bad_arrow_size

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_bad_arrow_size


---

## UF_DRAW_bad_arrow_stub_len

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_bad_arrow_stub_len


---

## UF_DRAW_bad_num_leg1_sxsegs

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_bad_num_leg1_sxsegs


---

## UF_DRAW_bad_num_step_sxsegs

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_bad_num_step_sxsegs


---

## UF_DRAW_bad_num_sxsegs

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_bad_num_sxsegs


---

## UF_DRAW_bad_sxline_display

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_bad_sxline_display


---

## UF_DRAW_bad_sxview_scale

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_bad_sxview_scale


---

## UF_DRAW_boundary_not_smart

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_boundary_not_smart


---

## UF_DRAW_boundary_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_boundary_type_e


---

## UF_DRAW_break_position_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_break_position_type_e


---

## UF_DRAW_break_region_boundary_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/UF_DRAW_break_region_boundary_s.html


---

## UF_DRAW_break_region_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/UF_DRAW_break_region_data_s.html


---

## UF_DRAW_breakout_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/UF_DRAW_breakout_data_s.html


---

## UF_DRAW_cannot_assoc_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_cannot_assoc_object


---

## UF_DRAW_comp_section_in_view_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_comp_section_in_view_e


---

## UF_DRAW_copy_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_copy_view


---

## UF_DRAW_create_break_region

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_create_break_region


---

## UF_DRAW_create_breakout

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_create_breakout


---

## UF_DRAW_create_drawing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_create_drawing


---

## UF_DRAW_create_half_sxview

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_create_half_sxview


---

## UF_DRAW_create_render_set

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_create_render_set


---

## UF_DRAW_create_revolved_sxview

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_create_revolved_sxview


---

## UF_DRAW_create_simple_sxview

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_create_simple_sxview


---

## UF_DRAW_create_simplified_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_create_simplified_curve


---

## UF_DRAW_create_stepped_sxview

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_create_stepped_sxview


---

## UF_DRAW_create_sxview_from_dmv

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_create_sxview_from_dmv


---

## UF_DRAW_create_unfolded_sxview

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_create_unfolded_sxview


---

## UF_DRAW_create_view_label

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_create_view_label


---

## UF_DRAW_curve_is_associative

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_curve_is_associative


---

## UF_DRAW_data_source_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_data_source_e


---

## UF_DRAW_define_bound_by_objects

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_define_bound_by_objects


---

## UF_DRAW_define_boundary_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/UF_DRAW_define_boundary_s.html


---

## UF_DRAW_define_view_auto_rect

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_define_view_auto_rect


---

## UF_DRAW_define_view_boundary

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_define_view_boundary


---

## UF_DRAW_define_view_boundary1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_define_view_boundary1


---

## UF_DRAW_define_view_manual_rect

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_define_view_manual_rect


---

## UF_DRAW_delete_drawing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_delete_drawing


---

## UF_DRAW_delete_sxline_sxseg

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_delete_sxline_sxseg


---

## UF_DRAW_delete_view_label

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_delete_view_label


---

## UF_DRAW_design_in_context

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_design_in_context


---

## UF_DRAW_detach_note_from_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_detach_note_from_view


---

## UF_DRAW_drafting_curve_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_drafting_curve_type_e


---

## UF_DRAW_drawing_already_exists

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_drawing_already_exists


---

## UF_DRAW_dwg_is_displayed

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_dwg_is_displayed


---

## UF_DRAW_dwg_not_current

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_dwg_not_current


---

## UF_DRAW_edge_hiding_edge_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_edge_hiding_edge_e


---

## UF_DRAW_edit_boundary_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_edit_boundary_point


---

## UF_DRAW_edit_sxline_display

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_edit_sxline_display


---

## UF_DRAW_english_size_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_english_size_e


---

## UF_DRAW_erase_sxview_objects

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_erase_sxview_objects


---

## UF_DRAW_extracted_edges_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_extracted_edges_e


---

## UF_DRAW_free_boundary

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_free_boundary


---

## UF_DRAW_gap_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_gap_e


---

## UF_DRAW_get_view_model_view_part

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_get_view_model_view_part


---

## UF_DRAW_half_sxsegs_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/UF_DRAW_half_sxsegs_s.html


---

## UF_DRAW_hidden_line_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_hidden_line_e


---

## UF_DRAW_import_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_import_view


---

## UF_DRAW_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/UF_DRAW_info_s.html


---

## UF_DRAW_initialize_view_info

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_initialize_view_info


---

## UF_DRAW_invalid_anchor_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_anchor_point


---

## UF_DRAW_invalid_arrow_dir

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_arrow_dir


---

## UF_DRAW_invalid_assoc_modifier

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_assoc_modifier


---

## UF_DRAW_invalid_boundary_curves

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_boundary_curves


---

## UF_DRAW_invalid_drawing_name

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_drawing_name


---

## UF_DRAW_invalid_drawing_size_values

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_drawing_size_values


---

## UF_DRAW_invalid_dwg_pos

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_dwg_pos


---

## UF_DRAW_invalid_hinge_dir

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_hinge_dir


---

## UF_DRAW_invalid_note

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_note


---

## UF_DRAW_invalid_number_of_copies

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_number_of_copies


---

## UF_DRAW_invalid_object_assoc

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_object_assoc


---

## UF_DRAW_invalid_object_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_object_view


---

## UF_DRAW_invalid_parameter

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_parameter


---

## UF_DRAW_invalid_parameter_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_parameter_value


---

## UF_DRAW_invalid_pen_number

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_pen_number


---

## UF_DRAW_invalid_pen_option

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_pen_option


---

## UF_DRAW_invalid_plot_scale

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_plot_scale


---

## UF_DRAW_invalid_size_code_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_size_code_value


---

## UF_DRAW_invalid_spline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_spline


---

## UF_DRAW_invalid_step_dir

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_step_dir


---

## UF_DRAW_invalid_sxline_leg

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_sxline_leg


---

## UF_DRAW_invalid_sxseg_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_sxseg_type


---

## UF_DRAW_invalid_tabnot_cell

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_tabnot_cell


---

## UF_DRAW_invalid_units_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_units_value


---

## UF_DRAW_invalid_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_view


---

## UF_DRAW_invalid_view_bound_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_view_bound_type


---

## UF_DRAW_invalid_view_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_invalid_view_type


---

## UF_DRAW_is_drafting_component

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_is_drafting_component


---

## UF_DRAW_is_object_out_of_date

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_is_object_out_of_date


---

## UF_DRAW_is_sxview

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_is_sxview


---

## UF_DRAW_is_thread_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_is_thread_curve


---

## UF_DRAW_label_on_parent_type_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_label_on_parent_type_t


---

## UF_DRAW_metric_size_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_metric_size_e


---

## UF_DRAW_move_sxline_rotpt

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_move_sxline_rotpt


---

## UF_DRAW_move_sxline_sxseg

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_move_sxline_sxseg


---

## UF_DRAW_move_sxseg

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_move_sxseg


---

## UF_DRAW_move_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_move_view


---

## UF_DRAW_move_view_to_drawing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_move_view_to_drawing


---

## UF_DRAW_no_add_to_half_sxline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_no_add_to_half_sxline


---

## UF_DRAW_no_arc_center

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_no_arc_center


---

## UF_DRAW_no_current_drawing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_no_current_drawing


---

## UF_DRAW_no_cut_in_leg1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_no_cut_in_leg1


---

## UF_DRAW_no_cut_in_leg2

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_no_cut_in_leg2


---

## UF_DRAW_no_delete_half_sxline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_no_delete_half_sxline


---

## UF_DRAW_no_drawing_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_no_drawing_view


---

## UF_DRAW_no_dwg_of_dwg_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_no_dwg_of_dwg_view


---

## UF_DRAW_no_end_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_no_end_point


---

## UF_DRAW_no_intersection

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_no_intersection


---

## UF_DRAW_no_more_tabnot_fonts

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_no_more_tabnot_fonts


---

## UF_DRAW_no_more_tabnot_sizes

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_no_more_tabnot_sizes


---

## UF_DRAW_no_more_views_to_dwg

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_no_more_views_to_dwg


---

## UF_DRAW_no_view_created

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_no_view_created


---

## UF_DRAW_not_two_cuts_defined

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_not_two_cuts_defined


---

## UF_DRAW_null_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_null_object


---

## UF_DRAW_object_is_not_linear

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_object_is_not_linear


---

## UF_DRAW_object_is_view_dep

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_object_is_view_dep


---

## UF_DRAW_open_drawing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_open_drawing


---

## UF_DRAW_parameter_type_wrong

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_parameter_type_wrong


---

## UF_DRAW_parent_view_out_of_date

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_parent_view_out_of_date


---

## UF_DRAW_part_not_loaded

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_part_not_loaded


---

## UF_DRAW_pen_assignment_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_pen_assignment_e


---

## UF_DRAW_plotter_data_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/UF_DRAW_plotter_data_s.html


---

## UF_DRAW_point_not_on_drawing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_point_not_on_drawing


---

## UF_DRAW_point_not_smart

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_point_not_smart


---

## UF_DRAW_point_not_visible

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_point_not_visible


---

## UF_DRAW_proj_dir_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_proj_dir_e


---

## UF_DRAW_projection_angle_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_projection_angle_e


---

## UF_DRAW_pview_not_detail_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_pview_not_detail_view


---

## UF_DRAW_pview_not_dwg_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_pview_not_dwg_view


---

## UF_DRAW_pview_not_sxview

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_pview_not_sxview


---

## UF_DRAW_redefine_sxline_hinge

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_redefine_sxline_hinge


---

## UF_DRAW_remove_break_region

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_remove_break_region


---

## UF_DRAW_remove_breakout

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_remove_breakout


---

## UF_DRAW_remove_dmv_rotation_plane

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_remove_dmv_rotation_plane


---

## UF_DRAW_rename_drawing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_rename_drawing


---

## UF_DRAW_render_prefs_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/UF_DRAW_render_prefs_s.html


---

## UF_DRAW_retrieve_drawing_cgm

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_retrieve_drawing_cgm


---

## UF_DRAW_secondary_indexing_align_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_secondary_indexing_align_t


---

## UF_DRAW_set_auto_update

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_auto_update


---

## UF_DRAW_set_border_color

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_border_color


---

## UF_DRAW_set_border_display

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_border_display


---

## UF_DRAW_set_boundary_assoc

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_boundary_assoc


---

## UF_DRAW_set_break_region_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_break_region_data


---

## UF_DRAW_set_breakout_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_breakout_data


---

## UF_DRAW_set_comp_section_in_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_comp_section_in_view


---

## UF_DRAW_set_display_state

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_display_state


---

## UF_DRAW_set_dmv_rotation_plane

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_dmv_rotation_plane


---

## UF_DRAW_set_drawing_info

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_drawing_info


---

## UF_DRAW_set_drawing_ref_pt

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_drawing_ref_pt


---

## UF_DRAW_set_render_set_objects

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_render_set_objects


---

## UF_DRAW_set_render_set_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_render_set_parms


---

## UF_DRAW_set_render_sets_for_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_render_sets_for_view


---

## UF_DRAW_set_suppress_view_updat

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_suppress_view_updat


---

## UF_DRAW_set_sxline_default_prfs

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_sxline_default_prfs


---

## UF_DRAW_set_sxview_display

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_sxview_display


---

## UF_DRAW_set_view_anchor

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_view_anchor


---

## UF_DRAW_set_view_angle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_view_angle


---

## UF_DRAW_set_view_display

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_view_display


---

## UF_DRAW_set_view_label_parms

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_view_label_parms


---

## UF_DRAW_set_view_parm_scale

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_view_parm_scale


---

## UF_DRAW_set_view_scale

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_view_scale


---

## UF_DRAW_set_view_status

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_view_status


---

## UF_DRAW_set_view_thd_app_pitch

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_view_thd_app_pitch


---

## UF_DRAW_set_view_thd_meth

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_set_view_thd_meth


---

## UF_DRAW_silhouette_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_silhouette_e


---

## UF_DRAW_size_state_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_size_state_e


---

## UF_DRAW_size_union_u

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/UF_DRAW_size_union_u.html


---

## UF_DRAW_sketch_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_sketch_object


---

## UF_DRAW_smooth_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_smooth_e


---

## UF_DRAW_sx_assy_xhatch_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_sx_assy_xhatch_e


---

## UF_DRAW_sx_background_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_sx_background_e


---

## UF_DRAW_sx_crosshatch_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_sx_crosshatch_e


---

## UF_DRAW_sx_section_sheet_body_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_sx_section_sheet_body_e


---

## UF_DRAW_sxline_display_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_sxline_display_e


---

## UF_DRAW_sxline_leg_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_sxline_leg_e


---

## UF_DRAW_sxline_not_correct_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_sxline_not_correct_type


---

## UF_DRAW_sxline_status_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_sxline_status_e


---

## UF_DRAW_sxline_sxsegs_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/UF_DRAW_sxline_sxsegs_s.html


---

## UF_DRAW_sxline_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_sxline_type_e


---

## UF_DRAW_sxseg_highlight_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_sxseg_highlight_e


---

## UF_DRAW_sxseg_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/UF_DRAW_sxseg_info_s.html


---

## UF_DRAW_sxseg_mode_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_sxseg_mode_e


---

## UF_DRAW_sxseg_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_sxseg_type_e


---

## UF_DRAW_sxview_prfs_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/UF_DRAW_sxview_prfs_s.html


---

## UF_DRAW_tag_is_null

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_tag_is_null


---

## UF_DRAW_tag_not_drawing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_tag_not_drawing


---

## UF_DRAW_tag_not_sxedge

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_tag_not_sxedge


---

## UF_DRAW_tag_not_sxline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_tag_not_sxline


---

## UF_DRAW_tag_not_sxseg

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_tag_not_sxseg


---

## UF_DRAW_tag_not_sxsolid

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_tag_not_sxsolid


---

## UF_DRAW_tag_not_sxview

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_tag_not_sxview


---

## UF_DRAW_tag_not_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_tag_not_view


---

## UF_DRAW_tag_not_view_label

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_tag_not_view_label


---

## UF_DRAW_thd_meth_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_thd_meth_e


---

## UF_DRAW_unable_to_delete_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_unable_to_delete_view


---

## UF_DRAW_unable_to_edit_bnd_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_unable_to_edit_bnd_point


---

## UF_DRAW_unable_to_obtain_display_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_unable_to_obtain_display_data


---

## UF_DRAW_unable_to_rotate_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_unable_to_rotate_view


---

## UF_DRAW_unable_to_set_ref_pt

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_unable_to_set_ref_pt


---

## UF_DRAW_unable_to_simplify_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_unable_to_simplify_curve


---

## UF_DRAW_unrecoverable_error

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_unrecoverable_error


---

## UF_DRAW_upd_out_of_date_views

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_upd_out_of_date_views


---

## UF_DRAW_update_one_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/global.html#UF_DRAW_update_one_view


---

## UF_DRAW_uvhatch_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_uvhatch_e


---

## UF_DRAW_vb_curve_crosses_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_vb_curve_crosses_curve


---

## UF_DRAW_vb_curve_disconnected

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_vb_curve_disconnected


---

## UF_DRAW_vb_curve_self_intersects

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_vb_curve_self_intersects


---

## UF_DRAW_vb_no_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_vb_no_curve


---

## UF_DRAW_vb_non_manifold_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_vb_non_manifold_curve


---

## UF_DRAW_view_already_exists

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_view_already_exists


---

## UF_DRAW_view_boundary_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/UF_DRAW_view_boundary_s.html


---

## UF_DRAW_view_cannot_be_made_ref

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_view_cannot_be_made_ref


---

## UF_DRAW_view_indep_object

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_view_indep_object


---

## UF_DRAW_view_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/UF_DRAW_view_info_s.html


---

## UF_DRAW_view_is_expanded

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_view_is_expanded


---

## UF_DRAW_view_is_facet_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_view_is_facet_view


---

## UF_DRAW_view_is_not_active

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_view_is_not_active


---

## UF_DRAW_view_is_not_member_view

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_view_is_not_member_view


---

## UF_DRAW_view_label_letter_format_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_view_label_letter_format_t


---

## UF_DRAW_view_label_parm_type_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_view_label_parm_type_t


---

## UF_DRAW_view_label_parms_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/UF_DRAW_view_label_parms_s.html


---

## UF_DRAW_view_label_position_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_view_label_position_t


---

## UF_DRAW_view_label_scale_format_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_view_label_scale_format_t


---

## UF_DRAW_view_label_scale_position_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_view_label_scale_position_t


---

## UF_DRAW_view_label_view_text_type_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_view_label_view_text_type_t


---

## UF_DRAW_view_not_on_current_drawing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_view_not_on_current_drawing


---

## UF_DRAW_view_not_on_drawing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_view_not_on_drawing


---

## UF_DRAW_view_pos_not_on_drawing

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_view_pos_not_on_drawing


---

## UF_DRAW_view_prfs_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/UF_DRAW_view_prfs_s.html


---

## UF_DRAW_view_status_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_view_status_e


---

## UF_DRAW_virtual_intersect_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/types.html#UF_DRAW_virtual_intersect_e


---

## UF_DRAW_vw_scale_is_not_parametric

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/uf_draw_errors.html#UF_DRAW_vw_scale_is_not_parametric


---

## uf_draw.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/intro.html#uf_draw


---

## uf_draw_errors.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/intro.html#uf_draw_errors


---

## uf_draw_types.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_draw/intro.html#uf_draw_types


---
