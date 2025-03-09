# Function: <code>acpi_ut_value_exit</code>

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
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```

```json
{
  "name": "acpi_ut_value_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584619758,
      "name": "acpi_ut_value_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:505",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584619758,
      "name": "acpi_ut_value_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```

```json
{
  "name": "acpi_ut_value_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584845479,
      "name": "acpi_ut_value_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:485",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584845479,
      "name": "acpi_ut_value_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```

```json
{
  "name": "acpi_ut_value_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584948856,
      "name": "acpi_ut_value_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:485",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584948856,
      "name": "acpi_ut_value_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```

```json
{
  "name": "acpi_ut_value_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585151856,
      "name": "acpi_ut_value_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:485",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585151856,
      "name": "acpi_ut_value_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```

```json
{
  "name": "acpi_ut_value_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585288218,
      "name": "acpi_ut_value_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:485",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585288218,
      "name": "acpi_ut_value_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```

```json
{
  "name": "acpi_ut_value_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585994677,
      "name": "acpi_ut_value_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:485",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_length",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585994677,
      "name": "acpi_ut_value_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```

```json
{
  "name": "acpi_ut_value_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586117523,
      "name": "acpi_ut_value_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:485",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_length",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586117523,
      "name": "acpi_ut_value_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```

```json
{
  "name": "acpi_ut_value_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585994232,
      "name": "acpi_ut_value_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:485",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_length",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585994232,
      "name": "acpi_ut_value_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```

```json
{
  "name": "acpi_ut_value_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586483538,
      "name": "acpi_ut_value_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:485",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_length",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586483538,
      "name": "acpi_ut_value_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```

```json
{
  "name": "acpi_ut_value_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587737355,
      "name": "acpi_ut_value_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:485",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_length",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587737355,
      "name": "acpi_ut_value_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```

```json
{
  "name": "acpi_ut_value_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589059968,
      "name": "acpi_ut_value_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:485",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_length",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589059968,
      "name": "acpi_ut_value_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```

```json
{
  "name": "acpi_ut_value_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589351280,
      "name": "acpi_ut_value_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:485",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_length",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589351280,
      "name": "acpi_ut_value_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```

```json
{
  "name": "acpi_ut_value_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589658128,
      "name": "acpi_ut_value_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:490",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object",
        "drivers/acpi/acpica/exprep.c:acpi_ex_prep_common_field_object",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/psargs.c:acpi_ps_get_next_package_length",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589658128,
      "name": "acpi_ut_value_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```

```json
{
  "name": "acpi_ut_value_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585239802,
      "name": "acpi_ut_value_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:485",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585239802,
      "name": "acpi_ut_value_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```

```json
{
  "name": "acpi_ut_value_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585345962,
      "name": "acpi_ut_value_exit",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:485",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/dsutils.c:acpi_ds_is_result_used",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch",
        "drivers/acpi/acpica/evsci.c:acpi_ev_gpe_xrupt_handler",
        "drivers/acpi/acpica/evsci.c:acpi_ev_sci_xrupt_handler",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/exutils.c:acpi_ex_integer_to_string",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/hwacpi.c:acpi_hw_get_mode",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_normalized_path",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_local",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_type",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585345962,
      "name": "acpi_ut_value_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
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
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
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
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void acpi_ut_value_exit(u32 line_number, const char * function_name, const char * module_name, u32 component_id, u64 value)
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
