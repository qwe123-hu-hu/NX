# UF_WAVE 函数参考

> 共 81 个函数

---

## 目录

- [UF_WAVE #Defines](#uf_wave #defines)
- [UF_WAVE Enumerations](#uf_wave enumerations)
- [UF_WAVE Files](#uf_wave files)
- [UF_WAVE Functions](#uf_wave functions)
- [UF_WAVE Structures](#uf_wave structures)
- [UF_WAVE_ERROR_BASE](#uf_wave_error_base)
- [UF_WAVE_ERROR_RANGE](#uf_wave_error_range)
- [UF_WAVE_NO_ERRORS](#uf_wave_no_errors)
- [UF_WAVE_accept_link_broken](#uf_wave_accept_link_broken)
- [UF_WAVE_ask_broken_link_source_part](#uf_wave_ask_broken_link_source_part)
- [UF_WAVE_ask_delay_status](#uf_wave_ask_delay_status)
- [UF_WAVE_ask_link_accept_broken](#uf_wave_ask_link_accept_broken)
- [UF_WAVE_ask_link_mirror_data](#uf_wave_ask_link_mirror_data)
- [UF_WAVE_ask_link_region_sources](#uf_wave_ask_link_region_sources)
- [UF_WAVE_ask_link_source](#uf_wave_ask_link_source)
- [UF_WAVE_ask_link_update_time](#uf_wave_ask_link_update_time)
- [UF_WAVE_ask_link_xform](#uf_wave_ask_link_xform)
- [UF_WAVE_ask_linked_feature_geom](#uf_wave_ask_linked_feature_geom)
- [UF_WAVE_ask_linked_feature_info](#uf_wave_ask_linked_feature_info)
- [UF_WAVE_ask_linked_feature_map](#uf_wave_ask_linked_feature_map)
- [UF_WAVE_ask_linked_pt_angle](#uf_wave_ask_linked_pt_angle)
- [UF_WAVE_ask_linked_pt_curve_prm](#uf_wave_ask_linked_pt_curve_prm)
- [UF_WAVE_ask_out_of_date_objects](#uf_wave_ask_out_of_date_objects)
- [UF_WAVE_ask_out_of_date_parts](#uf_wave_ask_out_of_date_parts)
- [UF_WAVE_ask_session_delay](#uf_wave_ask_session_delay)
- [UF_WAVE_convert_links_to_use_product_interface](#uf_wave_convert_links_to_use_product_interface)
- [UF_WAVE_copy_component_as](#uf_wave_copy_component_as)
- [UF_WAVE_create_linked_body](#uf_wave_create_linked_body)
- [UF_WAVE_create_linked_curve](#uf_wave_create_linked_curve)
- [UF_WAVE_create_linked_datum](#uf_wave_create_linked_datum)
- [UF_WAVE_create_linked_face](#uf_wave_create_linked_face)
- [UF_WAVE_create_linked_mirror](#uf_wave_create_linked_mirror)
- [UF_WAVE_create_linked_part](#uf_wave_create_linked_part)
- [UF_WAVE_create_linked_pt_angle](#uf_wave_create_linked_pt_angle)
- [UF_WAVE_create_linked_pt_center](#uf_wave_create_linked_pt_center)
- [UF_WAVE_create_linked_pt_curve](#uf_wave_create_linked_pt_curve)
- [UF_WAVE_create_linked_pt_point](#uf_wave_create_linked_pt_point)
- [UF_WAVE_create_linked_region](#uf_wave_create_linked_region)
- [UF_WAVE_create_linked_route_port](#uf_wave_create_linked_route_port)
- [UF_WAVE_create_linked_route_segment](#uf_wave_create_linked_route_segment)
- [UF_WAVE_create_linked_sketch](#uf_wave_create_linked_sketch)
- [UF_WAVE_create_linked_string](#uf_wave_create_linked_string)
- [UF_WAVE_data_not_loaded](#uf_wave_data_not_loaded)
- [UF_WAVE_delay_status_e](#uf_wave_delay_status_e)
- [UF_WAVE_err_cannot_map](#uf_wave_err_cannot_map)
- [UF_WAVE_err_wave_not_avail](#uf_wave_err_wave_not_avail)
- [UF_WAVE_faces_not_on_same_body](#uf_wave_faces_not_on_same_body)
- [UF_WAVE_free_linked_feature_info](#uf_wave_free_linked_feature_info)
- [UF_WAVE_freeze](#uf_wave_freeze)
- [UF_WAVE_freeze_persistently](#uf_wave_freeze_persistently)
- [UF_WAVE_init_linked_feature_info](#uf_wave_init_linked_feature_info)
- [UF_WAVE_interpart_only](#uf_wave_interpart_only)
- [UF_WAVE_is_link_broken](#uf_wave_is_link_broken)
- [UF_WAVE_is_pilo_xform](#uf_wave_is_pilo_xform)
- [UF_WAVE_link_not_broken](#uf_wave_link_not_broken)
- [UF_WAVE_linked_feature_info_s](#uf_wave_linked_feature_info_s)
- [UF_WAVE_load_parents](#uf_wave_load_parents)
- [UF_WAVE_map_link_geom_to_source](#uf_wave_map_link_geom_to_source)
- [UF_WAVE_map_source_to_link_geom](#uf_wave_map_source_to_link_geom)
- [UF_WAVE_mirror_or_region](#uf_wave_mirror_or_region)
- [UF_WAVE_mirror_region_or_point](#uf_wave_mirror_region_or_point)
- [UF_WAVE_not_a_mirror](#uf_wave_not_a_mirror)
- [UF_WAVE_not_a_point](#uf_wave_not_a_point)
- [UF_WAVE_not_a_region](#uf_wave_not_a_region)
- [UF_WAVE_not_interpart_link](#uf_wave_not_interpart_link)
- [UF_WAVE_part_load_failed](#uf_wave_part_load_failed)
- [UF_WAVE_set_link_data](#uf_wave_set_link_data)
- [UF_WAVE_set_link_mirror_data](#uf_wave_set_link_mirror_data)
- [UF_WAVE_set_link_region_data](#uf_wave_set_link_region_data)
- [UF_WAVE_set_link_update_time](#uf_wave_set_link_update_time)
- [UF_WAVE_set_linked_pt_angle](#uf_wave_set_linked_pt_angle)
- [UF_WAVE_set_linked_pt_center](#uf_wave_set_linked_pt_center)
- [UF_WAVE_set_linked_pt_curve](#uf_wave_set_linked_pt_curve)
- [UF_WAVE_set_linked_pt_point](#uf_wave_set_linked_pt_point)
- [UF_WAVE_set_session_delay](#uf_wave_set_session_delay)
- [UF_WAVE_unfreeze](#uf_wave_unfreeze)
- [UF_WAVE_update_parts](#uf_wave_update_parts)
- [UF_WAVE_update_session](#uf_wave_update_session)
- [uf_wave.h](#uf_wave.h)
- [uf_wave_errors.h](#uf_wave_errors.h)
- [uf_wave_types.h](#uf_wave_types.h)

---

## UF_WAVE #Defines

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/contents.html#defines


---

## UF_WAVE Enumerations

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/contents.html#enumerations


---

## UF_WAVE Files

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/contents.html#files


---

## UF_WAVE Functions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/contents.html#functions


---

## UF_WAVE Structures

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/contents.html#structures


---

## UF_WAVE_ERROR_BASE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/uf_wave_errors.html#UF_WAVE_ERROR_BASE


---

## UF_WAVE_ERROR_RANGE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/uf_wave_errors.html#UF_WAVE_ERROR_RANGE


---

## UF_WAVE_NO_ERRORS

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/uf_wave_errors.html#UF_WAVE_NO_ERRORS


---

## UF_WAVE_accept_link_broken

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_accept_link_broken


---

## UF_WAVE_ask_broken_link_source_part

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_ask_broken_link_source_part


---

## UF_WAVE_ask_delay_status

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_ask_delay_status


---

## UF_WAVE_ask_link_accept_broken

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_ask_link_accept_broken


---

## UF_WAVE_ask_link_mirror_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_ask_link_mirror_data


---

## UF_WAVE_ask_link_region_sources

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_ask_link_region_sources


---

## UF_WAVE_ask_link_source

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_ask_link_source


---

## UF_WAVE_ask_link_update_time

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_ask_link_update_time


---

## UF_WAVE_ask_link_xform

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_ask_link_xform


---

## UF_WAVE_ask_linked_feature_geom

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_ask_linked_feature_geom


---

## UF_WAVE_ask_linked_feature_info

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_ask_linked_feature_info


---

## UF_WAVE_ask_linked_feature_map

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_ask_linked_feature_map


---

## UF_WAVE_ask_linked_pt_angle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_ask_linked_pt_angle


---

## UF_WAVE_ask_linked_pt_curve_prm

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_ask_linked_pt_curve_prm


---

## UF_WAVE_ask_out_of_date_objects

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_ask_out_of_date_objects


---

## UF_WAVE_ask_out_of_date_parts

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_ask_out_of_date_parts


---

## UF_WAVE_ask_session_delay

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_ask_session_delay


---

## UF_WAVE_convert_links_to_use_product_interface

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_convert_links_to_use_product_interface


---

## UF_WAVE_copy_component_as

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_copy_component_as


---

## UF_WAVE_create_linked_body

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_create_linked_body


---

## UF_WAVE_create_linked_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_create_linked_curve


---

## UF_WAVE_create_linked_datum

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_create_linked_datum


---

## UF_WAVE_create_linked_face

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_create_linked_face


---

## UF_WAVE_create_linked_mirror

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_create_linked_mirror


---

## UF_WAVE_create_linked_part

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_create_linked_part


---

## UF_WAVE_create_linked_pt_angle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_create_linked_pt_angle


---

## UF_WAVE_create_linked_pt_center

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_create_linked_pt_center


---

## UF_WAVE_create_linked_pt_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_create_linked_pt_curve


---

## UF_WAVE_create_linked_pt_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_create_linked_pt_point


---

## UF_WAVE_create_linked_region

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_create_linked_region


---

## UF_WAVE_create_linked_route_port

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_create_linked_route_port


---

## UF_WAVE_create_linked_route_segment

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_create_linked_route_segment


---

## UF_WAVE_create_linked_sketch

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_create_linked_sketch


---

## UF_WAVE_create_linked_string

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_create_linked_string


---

## UF_WAVE_data_not_loaded

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/uf_wave_errors.html#UF_WAVE_data_not_loaded


---

## UF_WAVE_delay_status_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/types.html#UF_WAVE_delay_status_e


---

## UF_WAVE_err_cannot_map

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/uf_wave_errors.html#UF_WAVE_err_cannot_map


---

## UF_WAVE_err_wave_not_avail

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/uf_wave_errors.html#UF_WAVE_err_wave_not_avail


---

## UF_WAVE_faces_not_on_same_body

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/uf_wave_errors.html#UF_WAVE_faces_not_on_same_body


---

## UF_WAVE_free_linked_feature_info

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_free_linked_feature_info


---

## UF_WAVE_freeze

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_freeze


---

## UF_WAVE_freeze_persistently

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_freeze_persistently


---

## UF_WAVE_init_linked_feature_info

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_init_linked_feature_info


---

## UF_WAVE_interpart_only

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/uf_wave_errors.html#UF_WAVE_interpart_only


---

## UF_WAVE_is_link_broken

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_is_link_broken


---

## UF_WAVE_is_pilo_xform

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_is_pilo_xform


---

## UF_WAVE_link_not_broken

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/uf_wave_errors.html#UF_WAVE_link_not_broken


---

## UF_WAVE_linked_feature_info_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/UF_WAVE_linked_feature_info_s.html


---

## UF_WAVE_load_parents

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_load_parents


---

## UF_WAVE_map_link_geom_to_source

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_map_link_geom_to_source


---

## UF_WAVE_map_source_to_link_geom

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_map_source_to_link_geom


---

## UF_WAVE_mirror_or_region

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/uf_wave_errors.html#UF_WAVE_mirror_or_region


---

## UF_WAVE_mirror_region_or_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/uf_wave_errors.html#UF_WAVE_mirror_region_or_point


---

## UF_WAVE_not_a_mirror

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/uf_wave_errors.html#UF_WAVE_not_a_mirror


---

## UF_WAVE_not_a_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/uf_wave_errors.html#UF_WAVE_not_a_point


---

## UF_WAVE_not_a_region

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/uf_wave_errors.html#UF_WAVE_not_a_region


---

## UF_WAVE_not_interpart_link

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/uf_wave_errors.html#UF_WAVE_not_interpart_link


---

## UF_WAVE_part_load_failed

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/uf_wave_errors.html#UF_WAVE_part_load_failed


---

## UF_WAVE_set_link_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_set_link_data


---

## UF_WAVE_set_link_mirror_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_set_link_mirror_data


---

## UF_WAVE_set_link_region_data

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_set_link_region_data


---

## UF_WAVE_set_link_update_time

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_set_link_update_time


---

## UF_WAVE_set_linked_pt_angle

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_set_linked_pt_angle


---

## UF_WAVE_set_linked_pt_center

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_set_linked_pt_center


---

## UF_WAVE_set_linked_pt_curve

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_set_linked_pt_curve


---

## UF_WAVE_set_linked_pt_point

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_set_linked_pt_point


---

## UF_WAVE_set_session_delay

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_set_session_delay


---

## UF_WAVE_unfreeze

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_unfreeze


---

## UF_WAVE_update_parts

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_update_parts


---

## UF_WAVE_update_session

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/global.html#UF_WAVE_update_session


---

## uf_wave.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/intro.html#uf_wave


---

## uf_wave_errors.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/intro.html#uf_wave_errors


---

## uf_wave_types.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_wave/intro.html#uf_wave_types


---
