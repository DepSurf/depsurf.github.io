# Function: <code>acpi_db_set_output_destination</code>

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
void acpi_db_set_output_destination(u32 output_flags)
```

```json
{
  "name": "acpi_db_set_output_destination",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584666553,
      "name": "acpi_db_set_output_destination",
      "external": true,
      "loc": "drivers/acpi/acpica/dbutils.c:108",
      "file": "drivers/acpi/acpica/dbutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584666553,
      "name": "acpi_db_set_output_destination",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void acpi_db_set_output_destination(u32 output_flags)
```

```json
{
  "name": "acpi_db_set_output_destination",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584892669,
      "name": "acpi_db_set_output_destination",
      "external": true,
      "loc": "drivers/acpi/acpica/dbutils.c:72",
      "file": "drivers/acpi/acpica/dbutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584892669,
      "name": "acpi_db_set_output_destination",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void acpi_db_set_output_destination(u32 output_flags)
```

```json
{
  "name": "acpi_db_set_output_destination",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584996389,
      "name": "acpi_db_set_output_destination",
      "external": true,
      "loc": "drivers/acpi/acpica/dbutils.c:72",
      "file": "drivers/acpi/acpica/dbutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584996389,
      "name": "acpi_db_set_output_destination",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void acpi_db_set_output_destination(u32 output_flags)
```

```json
{
  "name": "acpi_db_set_output_destination",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585199920,
      "name": "acpi_db_set_output_destination",
      "external": true,
      "loc": "drivers/acpi/acpica/dbutils.c:72",
      "file": "drivers/acpi/acpica/dbutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585199920,
      "name": "acpi_db_set_output_destination",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void acpi_db_set_output_destination(u32 output_flags)
```

```json
{
  "name": "acpi_db_set_output_destination",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585336281,
      "name": "acpi_db_set_output_destination",
      "external": true,
      "loc": "drivers/acpi/acpica/dbutils.c:72",
      "file": "drivers/acpi/acpica/dbutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585336281,
      "name": "acpi_db_set_output_destination",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void acpi_db_set_output_destination(u32 output_flags)
```

```json
{
  "name": "acpi_db_set_output_destination",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043446,
      "name": "acpi_db_set_output_destination",
      "external": true,
      "loc": "drivers/acpi/acpica/dbutils.c:72",
      "file": "drivers/acpi/acpica/dbutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043446,
      "name": "acpi_db_set_output_destination",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void acpi_db_set_output_destination(u32 output_flags)
```

```json
{
  "name": "acpi_db_set_output_destination",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586166490,
      "name": "acpi_db_set_output_destination",
      "external": true,
      "loc": "drivers/acpi/acpica/dbutils.c:72",
      "file": "drivers/acpi/acpica/dbutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586166490,
      "name": "acpi_db_set_output_destination",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void acpi_db_set_output_destination(u32 output_flags)
```

```json
{
  "name": "acpi_db_set_output_destination",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043134,
      "name": "acpi_db_set_output_destination",
      "external": true,
      "loc": "drivers/acpi/acpica/dbutils.c:72",
      "file": "drivers/acpi/acpica/dbutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043134,
      "name": "acpi_db_set_output_destination",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void acpi_db_set_output_destination(u32 output_flags)
```

```json
{
  "name": "acpi_db_set_output_destination",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586534894,
      "name": "acpi_db_set_output_destination",
      "external": true,
      "loc": "drivers/acpi/acpica/dbutils.c:72",
      "file": "drivers/acpi/acpica/dbutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586534894,
      "name": "acpi_db_set_output_destination",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void acpi_db_set_output_destination(u32 output_flags)
```

```json
{
  "name": "acpi_db_set_output_destination",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587792455,
      "name": "acpi_db_set_output_destination",
      "external": true,
      "loc": "drivers/acpi/acpica/dbutils.c:72",
      "file": "drivers/acpi/acpica/dbutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587792455,
      "name": "acpi_db_set_output_destination",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void acpi_db_set_output_destination(u32 output_flags)
```

```json
{
  "name": "acpi_db_set_output_destination",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589128912,
      "name": "acpi_db_set_output_destination",
      "external": true,
      "loc": "drivers/acpi/acpica/dbutils.c:72",
      "file": "drivers/acpi/acpica/dbutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589128912,
      "name": "acpi_db_set_output_destination",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void acpi_db_set_output_destination(u32 output_flags)
```

```json
{
  "name": "acpi_db_set_output_destination",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589420960,
      "name": "acpi_db_set_output_destination",
      "external": true,
      "loc": "drivers/acpi/acpica/dbutils.c:72",
      "file": "drivers/acpi/acpica/dbutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589420960,
      "name": "acpi_db_set_output_destination",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void acpi_db_set_output_destination(u32 output_flags)
```

```json
{
  "name": "acpi_db_set_output_destination",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589728640,
      "name": "acpi_db_set_output_destination",
      "external": true,
      "loc": "drivers/acpi/acpica/dbutils.c:72",
      "file": "drivers/acpi/acpica/dbutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589728640,
      "name": "acpi_db_set_output_destination",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void acpi_db_set_output_destination(u32 output_flags)
```

```json
{
  "name": "acpi_db_set_output_destination",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585287865,
      "name": "acpi_db_set_output_destination",
      "external": true,
      "loc": "drivers/acpi/acpica/dbutils.c:72",
      "file": "drivers/acpi/acpica/dbutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585287865,
      "name": "acpi_db_set_output_destination",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void acpi_db_set_output_destination(u32 output_flags)
```

```json
{
  "name": "acpi_db_set_output_destination",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585394025,
      "name": "acpi_db_set_output_destination",
      "external": true,
      "loc": "drivers/acpi/acpica/dbutils.c:72",
      "file": "drivers/acpi/acpica/dbutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbcmds.c:acpi_db_display_template",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbexec.c:acpi_db_execute",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_display_objects",
        "drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace",
        "drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585394025,
      "name": "acpi_db_set_output_destination",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void acpi_db_set_output_destination(u32 output_flags)
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
void acpi_db_set_output_destination(u32 output_flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_db_set_output_destination(u32 output_flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_db_set_output_destination(u32 output_flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_db_set_output_destination(u32 output_flags)
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
void acpi_db_set_output_destination(u32 output_flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void acpi_db_set_output_destination(u32 output_flags)
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
