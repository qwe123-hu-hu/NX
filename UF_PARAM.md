# UF_PARAM 函数参考

> 共 56 个函数

---

## 目录

- [UF_PARAM #Defines](#uf_param #defines)
- [UF_PARAM Enumerations](#uf_param enumerations)
- [UF_PARAM Files](#uf_param files)
- [UF_PARAM Functions](#uf_param functions)
- [UF_PARAM Structures](#uf_param structures)
- [UF_PARAM_MAX_PARAM_NAME_LEN](#uf_param_max_param_name_len)
- [UF_PARAM_REQUIRED_LIST_SIZE](#uf_param_required_list_size)
- [UF_PARAM_append_ude](#uf_param_append_ude)
- [UF_PARAM_ask_2d_value](#uf_param_ask_2d_value)
- [UF_PARAM_ask_3d_value](#uf_param_ask_3d_value)
- [UF_PARAM_ask_double_value](#uf_param_ask_double_value)
- [UF_PARAM_ask_double_vla](#uf_param_ask_double_vla)
- [UF_PARAM_ask_inherited_params](#uf_param_ask_inherited_params)
- [UF_PARAM_ask_int_value](#uf_param_ask_int_value)
- [UF_PARAM_ask_int_vla](#uf_param_ask_int_vla)
- [UF_PARAM_ask_logical_value](#uf_param_ask_logical_value)
- [UF_PARAM_ask_param_attributes](#uf_param_ask_param_attributes)
- [UF_PARAM_ask_param_definer](#uf_param_ask_param_definer)
- [UF_PARAM_ask_param_status](#uf_param_ask_param_status)
- [UF_PARAM_ask_required_params](#uf_param_ask_required_params)
- [UF_PARAM_ask_str_value](#uf_param_ask_str_value)
- [UF_PARAM_ask_subobj_ptr_value](#uf_param_ask_subobj_ptr_value)
- [UF_PARAM_ask_tag_value](#uf_param_ask_tag_value)
- [UF_PARAM_ask_tag_vla](#uf_param_ask_tag_vla)
- [UF_PARAM_ask_udes](#uf_param_ask_udes)
- [UF_PARAM_can_accept_ude](#uf_param_can_accept_ude)
- [UF_PARAM_can_accept_ude_set](#uf_param_can_accept_ude_set)
- [UF_PARAM_check](#uf_param_check)
- [UF_PARAM_delete_all_udes](#uf_param_delete_all_udes)
- [UF_PARAM_delete_ude](#uf_param_delete_ude)
- [UF_PARAM_duplicate](#uf_param_duplicate)
- [UF_PARAM_generate](#uf_param_generate)
- [UF_PARAM_index_attribute_s](#uf_param_index_attribute_s)
- [UF_PARAM_inherit_value](#uf_param_inherit_value)
- [UF_PARAM_is_inherited](#uf_param_is_inherited)
- [UF_PARAM_is_load_with_parent](#uf_param_is_load_with_parent)
- [UF_PARAM_is_same_class](#uf_param_is_same_class)
- [UF_PARAM_is_template](#uf_param_is_template)
- [UF_PARAM_regen_e](#uf_param_regen_e)
- [UF_PARAM_reinit](#uf_param_reinit)
- [UF_PARAM_rename](#uf_param_rename)
- [UF_PARAM_replay_path](#uf_param_replay_path)
- [UF_PARAM_set_2d_value](#uf_param_set_2d_value)
- [UF_PARAM_set_3d_value](#uf_param_set_3d_value)
- [UF_PARAM_set_double_value](#uf_param_set_double_value)
- [UF_PARAM_set_double_vla](#uf_param_set_double_vla)
- [UF_PARAM_set_int_value](#uf_param_set_int_value)
- [UF_PARAM_set_int_vla](#uf_param_set_int_vla)
- [UF_PARAM_set_logical_value](#uf_param_set_logical_value)
- [UF_PARAM_set_str_value](#uf_param_set_str_value)
- [UF_PARAM_set_subobj_ptr_value](#uf_param_set_subobj_ptr_value)
- [UF_PARAM_set_tag_value](#uf_param_set_tag_value)
- [UF_PARAM_set_tag_vla](#uf_param_set_tag_vla)
- [UF_PARAM_status_e](#uf_param_status_e)
- [UF_PARAM_type_e](#uf_param_type_e)
- [uf_param.h](#uf_param.h)

---

## UF_PARAM #Defines

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/contents.html#defines


---

## UF_PARAM Enumerations

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/contents.html#enumerations


---

## UF_PARAM Files

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/contents.html#files


---

## UF_PARAM Functions

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/contents.html#functions


---

## UF_PARAM Structures

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/contents.html#structures


---

## UF_PARAM_MAX_PARAM_NAME_LEN

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/uf_param.html#UF_PARAM_MAX_PARAM_NAME_LEN


---

## UF_PARAM_REQUIRED_LIST_SIZE

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/uf_param.html#UF_PARAM_REQUIRED_LIST_SIZE


---

## UF_PARAM_append_ude

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_append_ude


---

## UF_PARAM_ask_2d_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_ask_2d_value


---

## UF_PARAM_ask_3d_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_ask_3d_value


---

## UF_PARAM_ask_double_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_ask_double_value


---

## UF_PARAM_ask_double_vla

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_ask_double_vla


---

## UF_PARAM_ask_inherited_params

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_ask_inherited_params


---

## UF_PARAM_ask_int_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_ask_int_value


---

## UF_PARAM_ask_int_vla

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_ask_int_vla


---

## UF_PARAM_ask_logical_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_ask_logical_value


---

## UF_PARAM_ask_param_attributes

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_ask_param_attributes


---

## UF_PARAM_ask_param_definer

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_ask_param_definer


---

## UF_PARAM_ask_param_status

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_ask_param_status


---

## UF_PARAM_ask_required_params

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_ask_required_params


---

## UF_PARAM_ask_str_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_ask_str_value


---

## UF_PARAM_ask_subobj_ptr_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_ask_subobj_ptr_value


---

## UF_PARAM_ask_tag_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_ask_tag_value


---

## UF_PARAM_ask_tag_vla

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_ask_tag_vla


---

## UF_PARAM_ask_udes

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_ask_udes


---

## UF_PARAM_can_accept_ude

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_can_accept_ude


---

## UF_PARAM_can_accept_ude_set

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_can_accept_ude_set


---

## UF_PARAM_check

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_check


---

## UF_PARAM_delete_all_udes

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_delete_all_udes


---

## UF_PARAM_delete_ude

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_delete_ude


---

## UF_PARAM_duplicate

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_duplicate


---

## UF_PARAM_generate

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_generate


---

## UF_PARAM_index_attribute_s

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/UF_PARAM_index_attribute_s.html


---

## UF_PARAM_inherit_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_inherit_value


---

## UF_PARAM_is_inherited

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_is_inherited


---

## UF_PARAM_is_load_with_parent

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_is_load_with_parent


---

## UF_PARAM_is_same_class

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_is_same_class


---

## UF_PARAM_is_template

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_is_template


---

## UF_PARAM_regen_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/types.html#UF_PARAM_regen_e


---

## UF_PARAM_reinit

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_reinit


---

## UF_PARAM_rename

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_rename


---

## UF_PARAM_replay_path

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_replay_path


---

## UF_PARAM_set_2d_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_set_2d_value


---

## UF_PARAM_set_3d_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_set_3d_value


---

## UF_PARAM_set_double_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_set_double_value


---

## UF_PARAM_set_double_vla

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_set_double_vla


---

## UF_PARAM_set_int_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_set_int_value


---

## UF_PARAM_set_int_vla

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_set_int_vla


---

## UF_PARAM_set_logical_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_set_logical_value


---

## UF_PARAM_set_str_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_set_str_value


---

## UF_PARAM_set_subobj_ptr_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_set_subobj_ptr_value


---

## UF_PARAM_set_tag_value

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_set_tag_value


---

## UF_PARAM_set_tag_vla

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/global.html#UF_PARAM_set_tag_vla


---

## UF_PARAM_status_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/types.html#UF_PARAM_status_e


---

## UF_PARAM_type_e

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/types.html#UF_PARAM_type_e


---

## uf_param.h

> 原始文档: https://docs.sw.siemens.com/documentation/external/PL20221117716122093/en-US/nx_api/nx/2306/nx_api/en-US/ugopen_doc/uf_param/intro.html#uf_param


---
