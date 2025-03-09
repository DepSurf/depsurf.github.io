# Function: <code>acpi_ut_add_reference</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583725377,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:694",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583725377,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584049857,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:695",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584049857,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584192132,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:695",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584192132,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584259764,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:697",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584259764,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584624413,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:697",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584624413,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584850139,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:664",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584850139,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584953653,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:667",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584953653,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585156788,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:671",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585156788,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585293150,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:671",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585293150,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585999630,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:668",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585999630,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586122476,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:668",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586122476,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585999254,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:676",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585999254,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586488794,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:677",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586488794,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587743186,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:677",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587743186,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589067360,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:677",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589067360,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589358688,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:677",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589358688,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589665536,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:677",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_object_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589665536,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497608612,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:671",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497608612,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585131530,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:671",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585131530,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585046785,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:671",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_store_object_to_local",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_init_args",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585046785,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585244734,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:671",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585244734,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```

```json
{
  "name": "acpi_ut_add_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585350894,
      "name": "acpi_ut_add_reference",
      "external": true,
      "loc": "drivers/acpi/acpica/utdelete.c:671",
      "file": "drivers/acpi/acpica/utdelete.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value",
        "drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_set_value",
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj",
        "drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op",
        "drivers/acpi/acpica/evregion.c:acpi_ev_attach_region",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_to_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference",
        "drivers/acpi/acpica/nsobject.c:acpi_ns_attach_object",
        "drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object",
        "drivers/acpi/acpica/utcopy.c:acpi_ut_copy_simple_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585350894,
      "name": "acpi_ut_add_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void acpi_ut_add_reference(union acpi_operand_object * object)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object * object)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_ut_add_reference(union acpi_operand_object * object)
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
