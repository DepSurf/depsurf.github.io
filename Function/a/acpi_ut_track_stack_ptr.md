# Function: <code>acpi_ut_track_stack_ptr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr()
```

```json
{
  "name": "acpi_ut_track_stack_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584620221,
      "name": "acpi_ut_track_stack_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:89",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_handle",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_move_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement",
        "drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception",
        "drivers/acpi/acpica/utdebug.c:acpi_trace_point",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource",
        "drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584620221,
      "name": "acpi_ut_track_stack_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr()
```

```json
{
  "name": "acpi_ut_track_stack_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584845938,
      "name": "acpi_ut_track_stack_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:55",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_handle",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_move_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement",
        "drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception",
        "drivers/acpi/acpica/utdebug.c:acpi_trace_point",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource",
        "drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584845938,
      "name": "acpi_ut_track_stack_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr()
```

```json
{
  "name": "acpi_ut_track_stack_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584949315,
      "name": "acpi_ut_track_stack_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:55",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_handle",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_move_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement",
        "drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception",
        "drivers/acpi/acpica/utdebug.c:acpi_trace_point",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource",
        "drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584949315,
      "name": "acpi_ut_track_stack_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr()
```

```json
{
  "name": "acpi_ut_track_stack_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585152312,
      "name": "acpi_ut_track_stack_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:55",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_handle",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_move_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement",
        "drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception",
        "drivers/acpi/acpica/utdebug.c:acpi_trace_point",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource",
        "drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585152312,
      "name": "acpi_ut_track_stack_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr()
```

```json
{
  "name": "acpi_ut_track_stack_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585288674,
      "name": "acpi_ut_track_stack_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:55",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_handle",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_move_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement",
        "drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception",
        "drivers/acpi/acpica/utdebug.c:acpi_trace_point",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource",
        "drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585288674,
      "name": "acpi_ut_track_stack_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr()
```

```json
{
  "name": "acpi_ut_track_stack_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585995138,
      "name": "acpi_ut_track_stack_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:55",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_handle",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_struct_option_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_move_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement",
        "drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception",
        "drivers/acpi/acpica/utdebug.c:acpi_trace_point",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource",
        "drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_label",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585995138,
      "name": "acpi_ut_track_stack_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr()
```

```json
{
  "name": "acpi_ut_track_stack_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586117984,
      "name": "acpi_ut_track_stack_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:55",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_handle",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_struct_option_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_move_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement",
        "drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception",
        "drivers/acpi/acpica/utdebug.c:acpi_trace_point",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource",
        "drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_label",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586117984,
      "name": "acpi_ut_track_stack_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr()
```

```json
{
  "name": "acpi_ut_track_stack_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585994693,
      "name": "acpi_ut_track_stack_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:55",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_handle",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_struct_option_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_move_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement",
        "drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception",
        "drivers/acpi/acpica/utdebug.c:acpi_trace_point",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource",
        "drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_label",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585994693,
      "name": "acpi_ut_track_stack_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr()
```

```json
{
  "name": "acpi_ut_track_stack_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586483999,
      "name": "acpi_ut_track_stack_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:55",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_handle",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_struct_option_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_move_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement",
        "drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception",
        "drivers/acpi/acpica/utdebug.c:acpi_trace_point",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource",
        "drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_label",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586483999,
      "name": "acpi_ut_track_stack_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr()
```

```json
{
  "name": "acpi_ut_track_stack_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587737966,
      "name": "acpi_ut_track_stack_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:55",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_handle",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_struct_option_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_move_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement",
        "drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception",
        "drivers/acpi/acpica/utdebug.c:acpi_trace_point",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource",
        "drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_label",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587737966,
      "name": "acpi_ut_track_stack_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_ut_track_stack_ptr()
```

```json
{
  "name": "acpi_ut_track_stack_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589060652,
      "name": "acpi_ut_track_stack_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:55",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdebug.c:acpi_trace_point",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_handle",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_move_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement",
        "drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources",
        "drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589061072,
      "name": "acpi_ut_track_stack_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_ut_track_stack_ptr()
```

```json
{
  "name": "acpi_ut_track_stack_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589351964,
      "name": "acpi_ut_track_stack_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:55",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdebug.c:acpi_trace_point",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_handle",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_move_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement",
        "drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources",
        "drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589352384,
      "name": "acpi_ut_track_stack_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_ut_track_stack_ptr()
```

```json
{
  "name": "acpi_ut_track_stack_ptr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589658812,
      "name": "acpi_ut_track_stack_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:60",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utdebug.c:acpi_trace_point",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr"
      ],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_handle",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_move_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement",
        "drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_walk_aml_resources",
        "drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589659232,
      "name": "acpi_ut_track_stack_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr()
```

```json
{
  "name": "acpi_ut_track_stack_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585240258,
      "name": "acpi_ut_track_stack_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:55",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_handle",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_move_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement",
        "drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception",
        "drivers/acpi/acpica/utdebug.c:acpi_trace_point",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource",
        "drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585240258,
      "name": "acpi_ut_track_stack_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void acpi_ut_track_stack_ptr()
```

```json
{
  "name": "acpi_ut_track_stack_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585346418,
      "name": "acpi_ut_track_stack_ptr",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:55",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_method_error",
        "drivers/acpi/acpica/evevent.c:acpi_ev_fixed_event_detect",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_notify_dispatch",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_ascii",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_do_math_op",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_reset_event",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_sleep",
        "drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall",
        "drivers/acpi/acpica/exutils.c:acpi_ex_pci_cls_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_truncate_for32bit_table",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_clear_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_get_bit_register_info",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_validate_handle",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_internal_name_length",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_walk_namespace",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nswalk.c:acpi_ns_get_next_node_typed",
        "drivers/acpi/acpica/nsxfname.c:acpi_get_handle",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_depth_next",
        "drivers/acpi/acpica/pstree.c:acpi_ps_get_arg",
        "drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op",
        "drivers/acpi/acpica/psutils.c:acpi_ps_init_op",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_set_address_common",
        "drivers/acpi/acpica/rsaddr.c:acpi_rs_get_address_common",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_list_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rscalc.c:acpi_rs_get_aml_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_get_resource_source",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_header",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_set_resource_length",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_move_data",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_encode_bitmask",
        "drivers/acpi/acpica/rsutils.c:acpi_rs_decode_bitmask",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_eelement",
        "drivers/acpi/acpica/utexcep.c:acpi_ut_validate_exception",
        "drivers/acpi/acpica/utdebug.c:acpi_trace_point",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_u32",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_str",
        "drivers/acpi/acpica/utdebug.c:acpi_ut_trace_ptr",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_object_list",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_display_init_pathname",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_create_update_state_and_push",
        "drivers/acpi/acpica/utmisc.c:acpi_ut_dword_byte_swap",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strupr",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_object_size",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_descriptor_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_header_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_length",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_get_resource_type",
        "drivers/acpi/acpica/utresrc.c:acpi_ut_validate_resource",
        "drivers/acpi/acpica/utstate.c:acpi_ut_delete_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_control_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_pkg_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_update_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_thread_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_pop_generic_state",
        "drivers/acpi/acpica/utstate.c:acpi_ut_push_generic_state",
        "drivers/acpi/acpica/dbxface.c:acpi_db_single_step",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_irq_list",
        "drivers/acpi/acpica/rsdump.c:acpi_rs_dump_resource_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585346418,
      "name": "acpi_ut_track_stack_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void acpi_ut_track_stack_ptr()
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void acpi_ut_track_stack_ptr()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_ut_track_stack_ptr()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_ut_track_stack_ptr()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_ut_track_stack_ptr()
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void acpi_ut_track_stack_ptr()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void acpi_ut_track_stack_ptr()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
