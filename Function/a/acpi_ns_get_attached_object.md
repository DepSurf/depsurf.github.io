# Function: <code>acpi_ns_get_attached_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583684378,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:278",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_alias",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583684378,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584008544,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:278",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_alias",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008544,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584150049,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:278",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_alias",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584150049,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584217317,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:278",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_alias",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584217317,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584557408,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:278",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object",
        "drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584557408,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584782541,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:242",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_deactivate_mem_region",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object",
        "drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584782541,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584884597,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:242",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_deactivate_mem_region",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object",
        "drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584884597,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585087848,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:246",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_deactivate_mem_region",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object",
        "drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585087848,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585224199,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:246",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_deactivate_mem_region",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object",
        "drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585224199,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585930024,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:246",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_deactivate_mem_region",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_value",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object",
        "drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk",
        "drivers/acpi/acpica/dbobject.c:acpi_db_decode_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585930024,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586051728,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:246",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_deactivate_mem_region",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_delete_value",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object",
        "drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk",
        "drivers/acpi/acpica/dbobject.c:acpi_db_decode_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586051728,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585928571,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:246",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_deactivate_mem_region",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object",
        "drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk",
        "drivers/acpi/acpica/dbobject.c:acpi_db_decode_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585928571,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586416744,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:246",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_deactivate_mem_region",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object",
        "drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk",
        "drivers/acpi/acpica/dbobject.c:acpi_db_decode_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586416744,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587667038,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:246",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk",
        "drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk",
        "drivers/acpi/acpica/dbobject.c:acpi_db_decode_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587667038,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588973776,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:246",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk",
        "drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk",
        "drivers/acpi/acpica/dbobject.c:acpi_db_decode_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588973776,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589264256,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:246",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk",
        "drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk",
        "drivers/acpi/acpica/dbobject.c:acpi_db_decode_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589264256,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589570928,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:246",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_get_gpe_event_info",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/evxface.c:acpi_remove_notify_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_remove_gpe_block",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/evxfregn.c:acpi_remove_address_space_handler",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_op",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execution_walk",
        "drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk",
        "drivers/acpi/acpica/dbobject.c:acpi_db_decode_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589570928,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497553292,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:246",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_deactivate_mem_region",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497553292,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585087085,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:246",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_deactivate_mem_region",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585087085,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585002481,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:246",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_deactivate_mem_region",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585002481,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585175783,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:246",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_deactivate_mem_region",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object",
        "drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585175783,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_get_attached_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585281943,
      "name": "acpi_ns_get_attached_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:246",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_deactivate_mem_region",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_get_field_names",
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_bank_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_table_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_buffer_field_operands",
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_initialize_region",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/dswload.c:acpi_ds_load1_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswload2.c:acpi_ds_load2_end_op",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_init_aml_walk",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_has_default_handler",
        "drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request",
        "drivers/acpi/acpica/evregion.c:acpi_ev_reg_run",
        "drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object",
        "drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_package",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers",
        "drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object",
        "drivers/acpi/acpica/dbnames.c:acpi_db_integrity_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585281943,
      "name": "acpi_ns_get_attached_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
union acpi_operand_object * acpi_ns_get_attached_object(struct acpi_namespace_node * node)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
