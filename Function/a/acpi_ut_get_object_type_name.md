# Function: <code>acpi_ut_get_object_type_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583723818,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:233",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583723818,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584048301,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:234",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584048301,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584190576,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:235",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584190576,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258182,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:235",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258182,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584621291,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:235",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584621291,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584847008,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:201",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584847008,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584950385,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:201",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584950385,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585153395,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:201",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585153395,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585289757,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:201",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585289757,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585996227,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:202",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585996227,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586119073,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:202",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586119073,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585995782,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:202",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585995782,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586485168,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:202",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586485168,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587739413,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:202",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_repair_null_element",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587739413,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589062528,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:202",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_repair_null_element",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589062528,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589353840,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:202",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_repair_null_element",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589353840,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589660688,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:202",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_setup_region",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_index",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_repair_null_element",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589660688,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497606616,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:201",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497606616,
      "name": "acpi_ut_get_object_type_name",
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585129725,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:201",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585129725,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585044980,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:201",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585044980,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585241341,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:201",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585241341,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```

```json
{
  "name": "acpi_ut_get_object_type_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585347501,
      "name": "acpi_ut_get_object_type_name",
      "external": true,
      "loc": "drivers/acpi/acpica/utdecode.c:201",
      "file": "drivers/acpi/acpica/utdecode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_obj_stack_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_push",
        "drivers/acpi/acpica/dswstate.c:acpi_ds_result_pop",
        "drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_target_type",
        "drivers/acpi/acpica/exdebug.c:acpi_ex_do_debug_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exdump.c:acpi_ex_dump_object",
        "drivers/acpi/acpica/exfldio.c:acpi_ex_access_region",
        "drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exresop.c:acpi_ex_resolve_operands",
        "drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object",
        "drivers/acpi/acpica/exstoren.c:acpi_ex_resolve_object",
        "drivers/acpi/acpica/nseval.c:acpi_ns_evaluate",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_wrap_with_package",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/rscreate.c:acpi_rs_create_pci_routing_table",
        "drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj",
        "drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object",
        "drivers/acpi/acpica/utobject.c:acpi_ut_get_simple_object_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585347501,
      "name": "acpi_ut_get_object_type_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>char *</code> ➡️ <code>const char *</code>
</li>
</ul>
</details>
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
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
const char * acpi_ut_get_object_type_name(union acpi_operand_object * obj_desc)
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
