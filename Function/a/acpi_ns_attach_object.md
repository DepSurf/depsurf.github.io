# Function: <code>acpi_ns_attach_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583684104,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:73",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_alias",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583684104,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584008270,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:73",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_alias",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008270,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584149775,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:73",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_alias",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584149775,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584217061,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:73",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_alias",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584217061,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584556821,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:73",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584556821,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584781954,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:37",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584781954,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584884010,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:37",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list",
        "drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584884010,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585087260,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:37",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585087260,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585223611,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:37",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585223611,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585929436,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:37",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585929436,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586051140,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:37",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586051140,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585927983,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:37",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585927983,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586416156,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:37",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586416156,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587666363,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:37",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587666363,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 675
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588972976,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:37",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588972976,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 773
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589263456,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:37",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589263456,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 773
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589570128,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:37",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_notify_handler",
        "drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize",
        "drivers/acpi/acpica/nsxfname.c:acpi_install_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589570128,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 773
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497553004,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:37",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497553004,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585086840,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:37",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585086840,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585002236,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:37",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585002236,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585175195,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:37",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585175195,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```

```json
{
  "name": "acpi_ns_attach_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585281355,
      "name": "acpi_ns_attach_object",
      "external": true,
      "loc": "drivers/acpi/acpica/nsobject.c:37",
      "file": "drivers/acpi/acpica/nsobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field",
        "drivers/acpi/acpica/dsobject.c:acpi_ds_create_node",
        "drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_method",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_processor",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_region",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex",
        "drivers/acpi/acpica/excreate.c:acpi_ex_create_event",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_direct_to_node",
        "drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node",
        "drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585281355,
      "name": "acpi_ns_attach_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_ns_attach_object(struct acpi_namespace_node * node, union acpi_operand_object * object, acpi_object_type type)
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
