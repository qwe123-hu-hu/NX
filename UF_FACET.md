# UF_FACET 函数参考

> 共 114 个函数

---

## 目录

- [UF_FACET #Defines](#uf_facet #defines)
- [UF_FACET Files](#uf_facet files)
- [UF_FACET Functions](#uf_facet functions)
- [UF_FACET Structures](#uf_facet structures)
- [UF_FACET_CONVEXITY_NOT_DETERMINED](#uf_facet_convexity_not_determined)
- [UF_FACET_DRAW_INTERIOR](#uf_facet_draw_interior)
- [UF_FACET_DRAW_SILHOUETTE](#uf_facet_draw_silhouette)
- [UF_FACET_DRAW_WIRE](#uf_facet_draw_wire)
- [UF_FACET_ERROR_BASE](#uf_facet_error_base)
- [UF_FACET_INIT_PARAMETERS](#uf_facet_init_parameters)
- [UF_FACET_IS_CONCAVE](#uf_facet_is_concave)
- [UF_FACET_IS_CONVEX](#uf_facet_is_convex)
- [UF_FACET_NULL_EDGE_ID](#uf_facet_null_edge_id)
- [UF_FACET_NULL_FACET_ID](#uf_facet_null_facet_id)
- [UF_FACET_NULL_FACE_ID](#uf_facet_null_face_id)
- [UF_FACET_PARAM_VERSION_CURR](#uf_facet_param_version_curr)
- [UF_FACET_TYPE_DOUBLE](#uf_facet_type_double)
- [UF_FACET_TYPE_FLOAT](#uf_facet_type_float)
- [UF_FACET_add_facet_to_model](#uf_facet_add_facet_to_model)
- [UF_FACET_ask_adjacent_facet](#uf_facet_ask_adjacent_facet)
- [UF_FACET_ask_available_solid](#uf_facet_ask_available_solid)
- [UF_FACET_ask_default_parameters](#uf_facet_ask_default_parameters)
- [UF_FACET_ask_edge_convexity](#uf_facet_ask_edge_convexity)
- [UF_FACET_ask_errors_during_tessellation](#uf_facet_ask_errors_during_tessellation)
- [UF_FACET_ask_face_id_of_facet](#uf_facet_ask_face_id_of_facet)
- [UF_FACET_ask_face_id_of_solid_face](#uf_facet_ask_face_id_of_solid_face)
- [UF_FACET_ask_face_of_tessellation](#uf_facet_ask_face_of_tessellation)
- [UF_FACET_ask_facet_data_of_tessellation](#uf_facet_ask_facet_data_of_tessellation)
- [UF_FACET_ask_max_facet_verts](#uf_facet_ask_max_facet_verts)
- [UF_FACET_ask_model_parameters](#uf_facet_ask_model_parameters)
- [UF_FACET_ask_models_of_solid](#uf_facet_ask_models_of_solid)
- [UF_FACET_ask_n_facets_in_model](#uf_facet_ask_n_facets_in_model)
- [UF_FACET_ask_normals_of_facet](#uf_facet_ask_normals_of_facet)
- [UF_FACET_ask_num_faces](#uf_facet_ask_num_faces)
- [UF_FACET_ask_num_facets_in_face](#uf_facet_ask_num_facets_in_face)
- [UF_FACET_ask_num_facets_in_tessellation](#uf_facet_ask_num_facets_in_tessellation)
- [UF_FACET_ask_num_verts_in_facet](#uf_facet_ask_num_verts_in_facet)
- [UF_FACET_ask_params_of_facet](#uf_facet_ask_params_of_facet)
- [UF_FACET_ask_plane_equation](#uf_facet_ask_plane_equation)
- [UF_FACET_ask_solid_face_of_face_id](#uf_facet_ask_solid_face_of_face_id)
- [UF_FACET_ask_solid_face_of_facet](#uf_facet_ask_solid_face_of_facet)
- [UF_FACET_ask_solid_of_model](#uf_facet_ask_solid_of_model)
- [UF_FACET_ask_surface_data_for_face](#uf_facet_ask_surface_data_for_face)
- [UF_FACET_ask_vertex_convexity](#uf_facet_ask_vertex_convexity)
- [UF_FACET_ask_vertices_of_facet](#uf_facet_ask_vertices_of_facet)
- [UF_FACET_create_model](#uf_facet_create_model)
- [UF_FACET_cycle_facets](#uf_facet_cycle_facets)
- [UF_FACET_cycle_facets_in_face](#uf_facet_cycle_facets_in_face)
- [UF_FACET_del_facet_from_model](#uf_facet_del_facet_from_model)
- [UF_FACET_delete_all_facets_from_model](#uf_facet_delete_all_facets_from_model)
- [UF_FACET_delete_tessellation](#uf_facet_delete_tessellation)
- [UF_FACET_disassoc_from_solid](#uf_facet_disassoc_from_solid)
- [UF_FACET_err_bad_adjacency](#uf_facet_err_bad_adjacency)
- [UF_FACET_err_bad_nx_curve_data](#uf_facet_err_bad_nx_curve_data)
- [UF_FACET_err_body_not_alive](#uf_facet_err_body_not_alive)
- [UF_FACET_err_body_outside_parasolid_limit](#uf_facet_err_body_outside_parasolid_limit)
- [UF_FACET_err_cannot_edit_occurrence](#uf_facet_err_cannot_edit_occurrence)
- [UF_FACET_err_edge_not_found](#uf_facet_err_edge_not_found)
- [UF_FACET_err_facet_not_planar](#uf_facet_err_facet_not_planar)
- [UF_FACET_err_insufficient_vertices](#uf_facet_err_insufficient_vertices)
- [UF_FACET_err_invalid_curve_ang_tol](#uf_facet_err_invalid_curve_ang_tol)
- [UF_FACET_err_invalid_curve_dist_tol](#uf_facet_err_invalid_curve_dist_tol)
- [UF_FACET_err_invalid_curve_max_len](#uf_facet_err_invalid_curve_max_len)
- [UF_FACET_err_invalid_edge_id](#uf_facet_err_invalid_edge_id)
- [UF_FACET_err_invalid_face_id](#uf_facet_err_invalid_face_id)
- [UF_FACET_err_invalid_face_tag](#uf_facet_err_invalid_face_tag)
- [UF_FACET_err_invalid_facet_id](#uf_facet_err_invalid_facet_id)
- [UF_FACET_err_invalid_facet_width](#uf_facet_err_invalid_facet_width)
- [UF_FACET_err_invalid_model](#uf_facet_err_invalid_model)
- [UF_FACET_err_invalid_num_sides](#uf_facet_err_invalid_num_sides)
- [UF_FACET_err_invalid_surf_ang_tol](#uf_facet_err_invalid_surf_ang_tol)
- [UF_FACET_err_invalid_surf_dist_tol](#uf_facet_err_invalid_surf_dist_tol)
- [UF_FACET_err_invalid_version_number](#uf_facet_err_invalid_version_number)
- [UF_FACET_err_invalid_vertex_id](#uf_facet_err_invalid_vertex_id)
- [UF_FACET_err_minimum_body](#uf_facet_err_minimum_body)
- [UF_FACET_err_non_manifold](#uf_facet_err_non_manifold)
- [UF_FACET_err_not_a_vrml_file](#uf_facet_err_not_a_vrml_file)
- [UF_FACET_err_not_an_stl_file](#uf_facet_err_not_an_stl_file)
- [UF_FACET_err_not_solid_body_or_face](#uf_facet_err_not_solid_body_or_face)
- [UF_FACET_err_object_not_supported](#uf_facet_err_object_not_supported)
- [UF_FACET_err_precise_data_not_avail](#uf_facet_err_precise_data_not_avail)
- [UF_FACET_err_solid_not_available](#uf_facet_err_solid_not_available)
- [UF_FACET_err_solid_not_loaded](#uf_facet_err_solid_not_loaded)
- [UF_FACET_err_stl_corrupt_file](#uf_facet_err_stl_corrupt_file)
- [UF_FACET_err_stl_invalid_data](#uf_facet_err_stl_invalid_data)
- [UF_FACET_err_stl_parse_fail](#uf_facet_err_stl_parse_fail)
- [UF_FACET_err_unknown_vrml_version](#uf_facet_err_unknown_vrml_version)
- [UF_FACET_err_vrml_file_not_found](#uf_facet_err_vrml_file_not_found)
- [UF_FACET_err_vrml_gunzip_fail](#uf_facet_err_vrml_gunzip_fail)
- [UF_FACET_err_vrml_parser_fail](#uf_facet_err_vrml_parser_fail)
- [UF_FACET_err_zero_facets_produced](#uf_facet_err_zero_facets_produced)
- [UF_FACET_facet_solid](#uf_facet_facet_solid)
- [UF_FACET_find_edge_in_facet](#uf_facet_find_edge_in_facet)
- [UF_FACET_is_facet_convex](#uf_facet_is_facet_convex)
- [UF_FACET_is_model_convex](#uf_facet_is_model_convex)
- [UF_FACET_is_model_up_to_date](#uf_facet_is_model_up_to_date)
- [UF_FACET_model_edits_done](#uf_facet_model_edits_done)
- [UF_FACET_parameters_s](#uf_facet_parameters_s)
- [UF_FACET_rebuild_adjacencies](#uf_facet_rebuild_adjacencies)
- [UF_FACET_set_adjacent_facet](#uf_facet_set_adjacent_facet)
- [UF_FACET_set_default_parameters](#uf_facet_set_default_parameters)
- [UF_FACET_set_vertex_of_facet](#uf_facet_set_vertex_of_facet)
- [UF_FACET_tessellate_face](#uf_facet_tessellate_face)
- [UF_FACET_tessellation_err_body_fault](#uf_facet_tessellation_err_body_fault)
- [UF_FACET_tessellation_err_face_fault](#uf_facet_tessellation_err_face_fault)
- [UF_FACET_tessellation_err_facet_fault](#uf_facet_tessellation_err_facet_fault)
- [UF_FACET_tessellation_err_mangled_fault](#uf_facet_tessellation_err_mangled_fault)
- [UF_FACET_tessellation_err_normal_fault](#uf_facet_tessellation_err_normal_fault)
- [UF_FACET_tessellation_err_thin_face_fault](#uf_facet_tessellation_err_thin_face_fault)
- [UF_FACET_tessellation_error_s](#uf_facet_tessellation_error_s)
- [UF_FACET_tessellation_parameters_s](#uf_facet_tessellation_parameters_s)
- [UF_FACET_update_model](#uf_facet_update_model)
- [uf_facet.h](#uf_facet.h)
- [uf_facet_tessellation.h](#uf_facet_tessellation.h)

---

## UF_FACET #Defines

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/contents.html#defines


---

## UF_FACET Files

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/contents.html#files


---

## UF_FACET Functions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/contents.html#functions


---

## UF_FACET Structures

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/contents.html#structures


---

## UF_FACET_CONVEXITY_NOT_DETERMINED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_CONVEXITY_NOT_DETERMINED


---

## UF_FACET_DRAW_INTERIOR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_DRAW_INTERIOR


---

## UF_FACET_DRAW_SILHOUETTE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_DRAW_SILHOUETTE


---

## UF_FACET_DRAW_WIRE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_DRAW_WIRE


---

## UF_FACET_ERROR_BASE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_ERROR_BASE


---

## UF_FACET_INIT_PARAMETERS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_INIT_PARAMETERS


---

## UF_FACET_IS_CONCAVE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_IS_CONCAVE


---

## UF_FACET_IS_CONVEX

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_IS_CONVEX


---

## UF_FACET_NULL_EDGE_ID

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_NULL_EDGE_ID


---

## UF_FACET_NULL_FACET_ID

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_NULL_FACET_ID


---

## UF_FACET_NULL_FACE_ID

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_NULL_FACE_ID


---

## UF_FACET_PARAM_VERSION_CURR

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_PARAM_VERSION_CURR


---

## UF_FACET_TYPE_DOUBLE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_TYPE_DOUBLE


---

## UF_FACET_TYPE_FLOAT

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_TYPE_FLOAT


---

## UF_FACET_add_facet_to_model

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_add_facet_to_model


---

## UF_FACET_ask_adjacent_facet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_adjacent_facet


---

## UF_FACET_ask_available_solid

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_available_solid


---

## UF_FACET_ask_default_parameters

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_default_parameters


---

## UF_FACET_ask_edge_convexity

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_edge_convexity


---

## UF_FACET_ask_errors_during_tessellation

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_errors_during_tessellation


---

## UF_FACET_ask_face_id_of_facet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_face_id_of_facet


---

## UF_FACET_ask_face_id_of_solid_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_face_id_of_solid_face


---

## UF_FACET_ask_face_of_tessellation

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_face_of_tessellation


---

## UF_FACET_ask_facet_data_of_tessellation

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_facet_data_of_tessellation


---

## UF_FACET_ask_max_facet_verts

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_max_facet_verts


---

## UF_FACET_ask_model_parameters

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_model_parameters


---

## UF_FACET_ask_models_of_solid

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_models_of_solid


---

## UF_FACET_ask_n_facets_in_model

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_n_facets_in_model


---

## UF_FACET_ask_normals_of_facet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_normals_of_facet


---

## UF_FACET_ask_num_faces

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_num_faces


---

## UF_FACET_ask_num_facets_in_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_num_facets_in_face


---

## UF_FACET_ask_num_facets_in_tessellation

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_num_facets_in_tessellation


---

## UF_FACET_ask_num_verts_in_facet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_num_verts_in_facet


---

## UF_FACET_ask_params_of_facet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_params_of_facet


---

## UF_FACET_ask_plane_equation

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_plane_equation


---

## UF_FACET_ask_solid_face_of_face_id

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_solid_face_of_face_id


---

## UF_FACET_ask_solid_face_of_facet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_solid_face_of_facet


---

## UF_FACET_ask_solid_of_model

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_solid_of_model


---

## UF_FACET_ask_surface_data_for_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_surface_data_for_face


---

## UF_FACET_ask_vertex_convexity

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_vertex_convexity


---

## UF_FACET_ask_vertices_of_facet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_ask_vertices_of_facet


---

## UF_FACET_create_model

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_create_model


---

## UF_FACET_cycle_facets

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_cycle_facets


---

## UF_FACET_cycle_facets_in_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_cycle_facets_in_face


---

## UF_FACET_del_facet_from_model

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_del_facet_from_model


---

## UF_FACET_delete_all_facets_from_model

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_delete_all_facets_from_model


---

## UF_FACET_delete_tessellation

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_delete_tessellation


---

## UF_FACET_disassoc_from_solid

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_disassoc_from_solid


---

## UF_FACET_err_bad_adjacency

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_bad_adjacency


---

## UF_FACET_err_bad_nx_curve_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_bad_nx_curve_data


---

## UF_FACET_err_body_not_alive

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_body_not_alive


---

## UF_FACET_err_body_outside_parasolid_limit

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_body_outside_parasolid_limit


---

## UF_FACET_err_cannot_edit_occurrence

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_cannot_edit_occurrence


---

## UF_FACET_err_edge_not_found

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_edge_not_found


---

## UF_FACET_err_facet_not_planar

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_facet_not_planar


---

## UF_FACET_err_insufficient_vertices

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_insufficient_vertices


---

## UF_FACET_err_invalid_curve_ang_tol

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_invalid_curve_ang_tol


---

## UF_FACET_err_invalid_curve_dist_tol

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_invalid_curve_dist_tol


---

## UF_FACET_err_invalid_curve_max_len

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_invalid_curve_max_len


---

## UF_FACET_err_invalid_edge_id

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_invalid_edge_id


---

## UF_FACET_err_invalid_face_id

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_invalid_face_id


---

## UF_FACET_err_invalid_face_tag

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_invalid_face_tag


---

## UF_FACET_err_invalid_facet_id

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_invalid_facet_id


---

## UF_FACET_err_invalid_facet_width

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_invalid_facet_width


---

## UF_FACET_err_invalid_model

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_invalid_model


---

## UF_FACET_err_invalid_num_sides

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_invalid_num_sides


---

## UF_FACET_err_invalid_surf_ang_tol

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_invalid_surf_ang_tol


---

## UF_FACET_err_invalid_surf_dist_tol

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_invalid_surf_dist_tol


---

## UF_FACET_err_invalid_version_number

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_invalid_version_number


---

## UF_FACET_err_invalid_vertex_id

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_invalid_vertex_id


---

## UF_FACET_err_minimum_body

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_minimum_body


---

## UF_FACET_err_non_manifold

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_non_manifold


---

## UF_FACET_err_not_a_vrml_file

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_not_a_vrml_file


---

## UF_FACET_err_not_an_stl_file

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_not_an_stl_file


---

## UF_FACET_err_not_solid_body_or_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_not_solid_body_or_face


---

## UF_FACET_err_object_not_supported

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_object_not_supported


---

## UF_FACET_err_precise_data_not_avail

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_precise_data_not_avail


---

## UF_FACET_err_solid_not_available

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_solid_not_available


---

## UF_FACET_err_solid_not_loaded

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_solid_not_loaded


---

## UF_FACET_err_stl_corrupt_file

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_stl_corrupt_file


---

## UF_FACET_err_stl_invalid_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_stl_invalid_data


---

## UF_FACET_err_stl_parse_fail

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_stl_parse_fail


---

## UF_FACET_err_unknown_vrml_version

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_unknown_vrml_version


---

## UF_FACET_err_vrml_file_not_found

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_vrml_file_not_found


---

## UF_FACET_err_vrml_gunzip_fail

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_vrml_gunzip_fail


---

## UF_FACET_err_vrml_parser_fail

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_vrml_parser_fail


---

## UF_FACET_err_zero_facets_produced

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet.html#UF_FACET_err_zero_facets_produced


---

## UF_FACET_facet_solid

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_facet_solid


---

## UF_FACET_find_edge_in_facet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_find_edge_in_facet


---

## UF_FACET_is_facet_convex

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_is_facet_convex


---

## UF_FACET_is_model_convex

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_is_model_convex


---

## UF_FACET_is_model_up_to_date

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_is_model_up_to_date


---

## UF_FACET_model_edits_done

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_model_edits_done


---

## UF_FACET_parameters_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/UF_FACET_parameters_s.html


---

## UF_FACET_rebuild_adjacencies

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_rebuild_adjacencies


---

## UF_FACET_set_adjacent_facet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_set_adjacent_facet


---

## UF_FACET_set_default_parameters

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_set_default_parameters


---

## UF_FACET_set_vertex_of_facet

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_set_vertex_of_facet


---

## UF_FACET_tessellate_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_tessellate_face


---

## UF_FACET_tessellation_err_body_fault

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet_tessellation.html#UF_FACET_tessellation_err_body_fault


---

## UF_FACET_tessellation_err_face_fault

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet_tessellation.html#UF_FACET_tessellation_err_face_fault


---

## UF_FACET_tessellation_err_facet_fault

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet_tessellation.html#UF_FACET_tessellation_err_facet_fault


---

## UF_FACET_tessellation_err_mangled_fault

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet_tessellation.html#UF_FACET_tessellation_err_mangled_fault


---

## UF_FACET_tessellation_err_normal_fault

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet_tessellation.html#UF_FACET_tessellation_err_normal_fault


---

## UF_FACET_tessellation_err_thin_face_fault

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/uf_facet_tessellation.html#UF_FACET_tessellation_err_thin_face_fault


---

## UF_FACET_tessellation_error_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/UF_FACET_tessellation_error_s.html


---

## UF_FACET_tessellation_parameters_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/UF_FACET_tessellation_parameters_s.html


---

## UF_FACET_update_model

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/global.html#UF_FACET_update_model


---

## uf_facet.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/intro.html#uf_facet


---

## uf_facet_tessellation.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_facet/intro.html#uf_facet_tessellation


---
