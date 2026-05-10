# UF_BREP 函数参考

> 共 125 个函数

---

## 目录

- [UF_BREP #Defines](#uf_brep #defines)
- [UF_BREP Callbacks](#uf_brep callbacks)
- [UF_BREP Enumerations](#uf_brep enumerations)
- [UF_BREP Files](#uf_brep files)
- [UF_BREP Functions](#uf_brep functions)
- [UF_BREP Structures](#uf_brep structures)
- [UF_BREP Unions](#uf_brep unions)
- [UF_BREP_ASATTACHED_OPTION](#uf_brep_asattached_option)
- [UF_BREP_BSURF_DIST_OPTION](#uf_brep_bsurf_dist_option)
- [UF_BREP_BSURF_MULT_OPTION](#uf_brep_bsurf_mult_option)
- [UF_BREP_CURVE_DIST_OPTION](#uf_brep_curve_dist_option)
- [UF_BREP_CURVE_MULT_OPTION](#uf_brep_curve_mult_option)
- [UF_BREP_EDGE3D_OPTION](#uf_brep_edge3d_option)
- [UF_BREP_FINSP_OPTION](#uf_brep_finsp_option)
- [UF_BREP_FLATTEN_OPTION](#uf_brep_flatten_option)
- [UF_BREP_FLATTEN_PERIPH_OPTION](#uf_brep_flatten_periph_option)
- [UF_BREP_INITIALIZE_TOPOLOGY](#uf_brep_initialize_topology)
- [UF_BREP_PROJECTION_DIST_OPTION](#uf_brep_projection_dist_option)
- [UF_BREP_PROJECTION_MULT_OPTION](#uf_brep_projection_mult_option)
- [UF_BREP_SIMPLIFY_DIST_OPTION](#uf_brep_simplify_dist_option)
- [UF_BREP_SIMPLIFY_MULT_OPTION](#uf_brep_simplify_mult_option)
- [UF_BREP_SPLIT_OPTION](#uf_brep_split_option)
- [UF_BREP_STATE_IS_FIXED](#uf_brep_state_is_fixed)
- [UF_BREP_STATE_SET_FIXED](#uf_brep_state_set_fixed)
- [UF_BREP_STATE_bad_child_count](#uf_brep_state_bad_child_count)
- [UF_BREP_STATE_bad_loop](#uf_brep_state_bad_loop)
- [UF_BREP_STATE_base](#uf_brep_state_base)
- [UF_BREP_STATE_body_inside_out](#uf_brep_state_body_inside_out)
- [UF_BREP_STATE_degenerate_geometry](#uf_brep_state_degenerate_geometry)
- [UF_BREP_STATE_disjoint_shell](#uf_brep_state_disjoint_shell)
- [UF_BREP_STATE_duplicate_child](#uf_brep_state_duplicate_child)
- [UF_BREP_STATE_edge_not_on_surface](#uf_brep_state_edge_not_on_surface)
- [UF_BREP_STATE_edge_reversed](#uf_brep_state_edge_reversed)
- [UF_BREP_STATE_edge_tol_too_big](#uf_brep_state_edge_tol_too_big)
- [UF_BREP_STATE_extra_child](#uf_brep_state_extra_child)
- [UF_BREP_STATE_extra_parent](#uf_brep_state_extra_parent)
- [UF_BREP_STATE_face_error](#uf_brep_state_face_error)
- [UF_BREP_STATE_face_face_inconsistency](#uf_brep_state_face_face_inconsistency)
- [UF_BREP_STATE_face_or_edge_non_g1](#uf_brep_state_face_or_edge_non_g1)
- [UF_BREP_STATE_inconsistent_geom](#uf_brep_state_inconsistent_geom)
- [UF_BREP_STATE_invalid_entity_ids](#uf_brep_state_invalid_entity_ids)
- [UF_BREP_STATE_invalid_geom](#uf_brep_state_invalid_geom)
- [UF_BREP_STATE_invalid_geometry](#uf_brep_state_invalid_geometry)
- [UF_BREP_STATE_loop_inconsistent](#uf_brep_state_loop_inconsistent)
- [UF_BREP_STATE_missing_child](#uf_brep_state_missing_child)
- [UF_BREP_STATE_missing_parent](#uf_brep_state_missing_parent)
- [UF_BREP_STATE_multi_vertex_loop](#uf_brep_state_multi_vertex_loop)
- [UF_BREP_STATE_non_manifold](#uf_brep_state_non_manifold)
- [UF_BREP_STATE_null_child_array](#uf_brep_state_null_child_array)
- [UF_BREP_STATE_null_child_pointer](#uf_brep_state_null_child_pointer)
- [UF_BREP_STATE_self_intersecting](#uf_brep_state_self_intersecting)
- [UF_BREP_STATE_topology_error](#uf_brep_state_topology_error)
- [UF_BREP_STATE_unknown_body_fault](#uf_brep_state_unknown_body_fault)
- [UF_BREP_STATE_unknown_child](#uf_brep_state_unknown_child)
- [UF_BREP_STATE_unknown_geom_fault](#uf_brep_state_unknown_geom_fault)
- [UF_BREP_STATE_vertex_not_on_curve](#uf_brep_state_vertex_not_on_curve)
- [UF_BREP_STATE_vertex_not_on_surface](#uf_brep_state_vertex_not_on_surface)
- [UF_BREP_STATE_wrong_child](#uf_brep_state_wrong_child)
- [UF_BREP_STATE_wrong_parent](#uf_brep_state_wrong_parent)
- [UF_BREP_arc_s](#uf_brep_arc_s)
- [UF_BREP_ask_edge_class](#uf_brep_ask_edge_class)
- [UF_BREP_ask_geometry](#uf_brep_ask_geometry)
- [UF_BREP_ask_identifier](#uf_brep_ask_identifier)
- [UF_BREP_ask_topology](#uf_brep_ask_topology)
- [UF_BREP_ask_topology_source](#uf_brep_ask_topology_source)
- [UF_BREP_attach_geometry](#uf_brep_attach_geometry)
- [UF_BREP_bsurface_s](#uf_brep_bsurface_s)
- [UF_BREP_composite_s](#uf_brep_composite_s)
- [UF_BREP_cone_s](#uf_brep_cone_s)
- [UF_BREP_conic_s](#uf_brep_conic_s)
- [UF_BREP_cylinder_s](#uf_brep_cylinder_s)
- [UF_BREP_delete_geometry](#uf_brep_delete_geometry)
- [UF_BREP_edge_class_e](#uf_brep_edge_class_e)
- [UF_BREP_err_already_has_geom](#uf_brep_err_already_has_geom)
- [UF_BREP_err_bad_curve_type](#uf_brep_err_bad_curve_type)
- [UF_BREP_err_bad_geom_sense](#uf_brep_err_bad_geom_sense)
- [UF_BREP_err_bad_root_topology_type](#uf_brep_err_bad_root_topology_type)
- [UF_BREP_err_bad_surf_type](#uf_brep_err_bad_surf_type)
- [UF_BREP_err_bad_ug_entity](#uf_brep_err_bad_ug_entity)
- [UF_BREP_err_bad_ug_tag](#uf_brep_err_bad_ug_tag)
- [UF_BREP_err_cant_make_bspline](#uf_brep_err_cant_make_bspline)
- [UF_BREP_err_cant_make_trimsurf](#uf_brep_err_cant_make_trimsurf)
- [UF_BREP_err_edges_dont_trim_face](#uf_brep_err_edges_dont_trim_face)
- [UF_BREP_err_flatten_non_face](#uf_brep_err_flatten_non_face)
- [UF_BREP_err_geom_attach](#uf_brep_err_geom_attach)
- [UF_BREP_err_no_geometry](#uf_brep_err_no_geometry)
- [UF_BREP_err_none](#uf_brep_err_none)
- [UF_BREP_err_null_pointer](#uf_brep_err_null_pointer)
- [UF_BREP_err_ref_cache_obj_is_sleepy](#uf_brep_err_ref_cache_obj_is_sleepy)
- [UF_BREP_err_tight_tolerances](#uf_brep_err_tight_tolerances)
- [UF_BREP_err_topo_cant_have_geom](#uf_brep_err_topo_cant_have_geom)
- [UF_BREP_err_topo_geom_mismatch](#uf_brep_err_topo_geom_mismatch)
- [UF_BREP_err_topology](#uf_brep_err_topology)
- [UF_BREP_err_trim_loop_degenerate](#uf_brep_err_trim_loop_degenerate)
- [UF_BREP_err_validate_topology](#uf_brep_err_validate_topology)
- [UF_BREP_extrude_s](#uf_brep_extrude_s)
- [UF_BREP_free_fn_t](#uf_brep_free_fn_t)
- [UF_BREP_free_geometry_data](#uf_brep_free_geometry_data)
- [UF_BREP_geom_type_e](#uf_brep_geom_type_e)
- [UF_BREP_geom_u](#uf_brep_geom_u)
- [UF_BREP_geometry_s](#uf_brep_geometry_s)
- [UF_BREP_heal_body](#uf_brep_heal_body)
- [UF_BREP_line_s](#uf_brep_line_s)
- [UF_BREP_make_body](#uf_brep_make_body)
- [UF_BREP_mapping_s](#uf_brep_mapping_s)
- [UF_BREP_offset_s](#uf_brep_offset_s)
- [UF_BREP_options_s](#uf_brep_options_s)
- [UF_BREP_orientation_e](#uf_brep_orientation_e)
- [UF_BREP_oriented_child_s](#uf_brep_oriented_child_s)
- [UF_BREP_plane_s](#uf_brep_plane_s)
- [UF_BREP_release_topology](#uf_brep_release_topology)
- [UF_BREP_revolve_s](#uf_brep_revolve_s)
- [UF_BREP_sphere_s](#uf_brep_sphere_s)
- [UF_BREP_spline_s](#uf_brep_spline_s)
- [UF_BREP_state_s](#uf_brep_state_s)
- [UF_BREP_tagged_object_s](#uf_brep_tagged_object_s)
- [UF_BREP_topo_source_e](#uf_brep_topo_source_e)
- [UF_BREP_topo_type_e](#uf_brep_topo_type_e)
- [UF_BREP_topology_s](#uf_brep_topology_s)
- [UF_BREP_torus_s](#uf_brep_torus_s)
- [UF_BREP_u](#uf_brep_u)
- [UF_BREP_uvbox_s](#uf_brep_uvbox_s)
- [UF_BREP_validate_topology](#uf_brep_validate_topology)
- [uf_brep.h](#uf_brep.h)
- [uf_brep_types.h](#uf_brep_types.h)

---

## UF_BREP #Defines

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/contents.html#defines


---

## UF_BREP Callbacks

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/contents.html#callbacks


---

## UF_BREP Enumerations

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/contents.html#enumerations


---

## UF_BREP Files

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/contents.html#files


---

## UF_BREP Functions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/contents.html#functions


---

## UF_BREP Structures

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/contents.html#structures


---

## UF_BREP Unions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/contents.html#unions


---

## UF_BREP_ASATTACHED_OPTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_ASATTACHED_OPTION


---

## UF_BREP_BSURF_DIST_OPTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_BSURF_DIST_OPTION


---

## UF_BREP_BSURF_MULT_OPTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_BSURF_MULT_OPTION


---

## UF_BREP_CURVE_DIST_OPTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_CURVE_DIST_OPTION


---

## UF_BREP_CURVE_MULT_OPTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_CURVE_MULT_OPTION


---

## UF_BREP_EDGE3D_OPTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_EDGE3D_OPTION


---

## UF_BREP_FINSP_OPTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_FINSP_OPTION


---

## UF_BREP_FLATTEN_OPTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_FLATTEN_OPTION


---

## UF_BREP_FLATTEN_PERIPH_OPTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_FLATTEN_PERIPH_OPTION


---

## UF_BREP_INITIALIZE_TOPOLOGY

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_INITIALIZE_TOPOLOGY


---

## UF_BREP_PROJECTION_DIST_OPTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_PROJECTION_DIST_OPTION


---

## UF_BREP_PROJECTION_MULT_OPTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_PROJECTION_MULT_OPTION


---

## UF_BREP_SIMPLIFY_DIST_OPTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_SIMPLIFY_DIST_OPTION


---

## UF_BREP_SIMPLIFY_MULT_OPTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_SIMPLIFY_MULT_OPTION


---

## UF_BREP_SPLIT_OPTION

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_SPLIT_OPTION


---

## UF_BREP_STATE_IS_FIXED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_IS_FIXED


---

## UF_BREP_STATE_SET_FIXED

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_SET_FIXED


---

## UF_BREP_STATE_bad_child_count

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_bad_child_count


---

## UF_BREP_STATE_bad_loop

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_bad_loop


---

## UF_BREP_STATE_base

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_base


---

## UF_BREP_STATE_body_inside_out

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_body_inside_out


---

## UF_BREP_STATE_degenerate_geometry

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_degenerate_geometry


---

## UF_BREP_STATE_disjoint_shell

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_disjoint_shell


---

## UF_BREP_STATE_duplicate_child

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_duplicate_child


---

## UF_BREP_STATE_edge_not_on_surface

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_edge_not_on_surface


---

## UF_BREP_STATE_edge_reversed

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_edge_reversed


---

## UF_BREP_STATE_edge_tol_too_big

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_edge_tol_too_big


---

## UF_BREP_STATE_extra_child

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_extra_child


---

## UF_BREP_STATE_extra_parent

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_extra_parent


---

## UF_BREP_STATE_face_error

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_face_error


---

## UF_BREP_STATE_face_face_inconsistency

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_face_face_inconsistency


---

## UF_BREP_STATE_face_or_edge_non_g1

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_face_or_edge_non_g1


---

## UF_BREP_STATE_inconsistent_geom

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_inconsistent_geom


---

## UF_BREP_STATE_invalid_entity_ids

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_invalid_entity_ids


---

## UF_BREP_STATE_invalid_geom

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_invalid_geom


---

## UF_BREP_STATE_invalid_geometry

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_invalid_geometry


---

## UF_BREP_STATE_loop_inconsistent

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_loop_inconsistent


---

## UF_BREP_STATE_missing_child

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_missing_child


---

## UF_BREP_STATE_missing_parent

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_missing_parent


---

## UF_BREP_STATE_multi_vertex_loop

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_multi_vertex_loop


---

## UF_BREP_STATE_non_manifold

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_non_manifold


---

## UF_BREP_STATE_null_child_array

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_null_child_array


---

## UF_BREP_STATE_null_child_pointer

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_null_child_pointer


---

## UF_BREP_STATE_self_intersecting

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_self_intersecting


---

## UF_BREP_STATE_topology_error

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_topology_error


---

## UF_BREP_STATE_unknown_body_fault

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_unknown_body_fault


---

## UF_BREP_STATE_unknown_child

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_unknown_child


---

## UF_BREP_STATE_unknown_geom_fault

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_unknown_geom_fault


---

## UF_BREP_STATE_vertex_not_on_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_vertex_not_on_curve


---

## UF_BREP_STATE_vertex_not_on_surface

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_vertex_not_on_surface


---

## UF_BREP_STATE_wrong_child

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_wrong_child


---

## UF_BREP_STATE_wrong_parent

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_STATE_wrong_parent


---

## UF_BREP_arc_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_arc_s.html


---

## UF_BREP_ask_edge_class

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/global.html#UF_BREP_ask_edge_class


---

## UF_BREP_ask_geometry

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/global.html#UF_BREP_ask_geometry


---

## UF_BREP_ask_identifier

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/global.html#UF_BREP_ask_identifier


---

## UF_BREP_ask_topology

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/global.html#UF_BREP_ask_topology


---

## UF_BREP_ask_topology_source

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/global.html#UF_BREP_ask_topology_source


---

## UF_BREP_attach_geometry

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/global.html#UF_BREP_attach_geometry


---

## UF_BREP_bsurface_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_bsurface_s.html


---

## UF_BREP_composite_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_composite_s.html


---

## UF_BREP_cone_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_cone_s.html


---

## UF_BREP_conic_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_conic_s.html


---

## UF_BREP_cylinder_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_cylinder_s.html


---

## UF_BREP_delete_geometry

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/global.html#UF_BREP_delete_geometry


---

## UF_BREP_edge_class_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/types.html#UF_BREP_edge_class_e


---

## UF_BREP_err_already_has_geom

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_already_has_geom


---

## UF_BREP_err_bad_curve_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_bad_curve_type


---

## UF_BREP_err_bad_geom_sense

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_bad_geom_sense


---

## UF_BREP_err_bad_root_topology_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_bad_root_topology_type


---

## UF_BREP_err_bad_surf_type

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_bad_surf_type


---

## UF_BREP_err_bad_ug_entity

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_bad_ug_entity


---

## UF_BREP_err_bad_ug_tag

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_bad_ug_tag


---

## UF_BREP_err_cant_make_bspline

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_cant_make_bspline


---

## UF_BREP_err_cant_make_trimsurf

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_cant_make_trimsurf


---

## UF_BREP_err_edges_dont_trim_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_edges_dont_trim_face


---

## UF_BREP_err_flatten_non_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_flatten_non_face


---

## UF_BREP_err_geom_attach

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_geom_attach


---

## UF_BREP_err_no_geometry

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_no_geometry


---

## UF_BREP_err_none

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_none


---

## UF_BREP_err_null_pointer

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_null_pointer


---

## UF_BREP_err_ref_cache_obj_is_sleepy

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_ref_cache_obj_is_sleepy


---

## UF_BREP_err_tight_tolerances

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_tight_tolerances


---

## UF_BREP_err_topo_cant_have_geom

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_topo_cant_have_geom


---

## UF_BREP_err_topo_geom_mismatch

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_topo_geom_mismatch


---

## UF_BREP_err_topology

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_topology


---

## UF_BREP_err_trim_loop_degenerate

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_trim_loop_degenerate


---

## UF_BREP_err_validate_topology

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/uf_brep_types.html#UF_BREP_err_validate_topology


---

## UF_BREP_extrude_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_extrude_s.html


---

## UF_BREP_free_fn_t

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/callback.html#UF_BREP_free_fn_t


---

## UF_BREP_free_geometry_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/global.html#UF_BREP_free_geometry_data


---

## UF_BREP_geom_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/types.html#UF_BREP_geom_type_e


---

## UF_BREP_geom_u

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_geom_u.html


---

## UF_BREP_geometry_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_geometry_s.html


---

## UF_BREP_heal_body

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/global.html#UF_BREP_heal_body


---

## UF_BREP_line_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_line_s.html


---

## UF_BREP_make_body

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/global.html#UF_BREP_make_body


---

## UF_BREP_mapping_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_mapping_s.html


---

## UF_BREP_offset_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_offset_s.html


---

## UF_BREP_options_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_options_s.html


---

## UF_BREP_orientation_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/types.html#UF_BREP_orientation_e


---

## UF_BREP_oriented_child_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_oriented_child_s.html


---

## UF_BREP_plane_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_plane_s.html


---

## UF_BREP_release_topology

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/global.html#UF_BREP_release_topology


---

## UF_BREP_revolve_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_revolve_s.html


---

## UF_BREP_sphere_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_sphere_s.html


---

## UF_BREP_spline_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_spline_s.html


---

## UF_BREP_state_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_state_s.html


---

## UF_BREP_tagged_object_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_tagged_object_s.html


---

## UF_BREP_topo_source_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/types.html#UF_BREP_topo_source_e


---

## UF_BREP_topo_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/types.html#UF_BREP_topo_type_e


---

## UF_BREP_topology_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_topology_s.html


---

## UF_BREP_torus_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_torus_s.html


---

## UF_BREP_u

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_u.html


---

## UF_BREP_uvbox_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/UF_BREP_uvbox_s.html


---

## UF_BREP_validate_topology

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/global.html#UF_BREP_validate_topology


---

## uf_brep.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/intro.html#uf_brep


---

## uf_brep_types.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_brep/intro.html#uf_brep_types


---
