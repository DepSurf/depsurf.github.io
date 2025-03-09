# Function: <code>acpi_ut_trace_str</code>

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
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```

```json
{
  "name": "acpi_ut_trace_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584620587,
      "name": "acpi_ut_trace_str",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:347",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R",
        "drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584620587,
      "name": "acpi_ut_trace_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```

```json
{
  "name": "acpi_ut_trace_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584846304,
      "name": "acpi_ut_trace_str",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:327",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R",
        "drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584846304,
      "name": "acpi_ut_trace_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```

```json
{
  "name": "acpi_ut_trace_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584949681,
      "name": "acpi_ut_trace_str",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:327",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R",
        "drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584949681,
      "name": "acpi_ut_trace_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```

```json
{
  "name": "acpi_ut_trace_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585152681,
      "name": "acpi_ut_trace_str",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:327",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R",
        "drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585152681,
      "name": "acpi_ut_trace_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```

```json
{
  "name": "acpi_ut_trace_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585289043,
      "name": "acpi_ut_trace_str",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:327",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R",
        "drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585289043,
      "name": "acpi_ut_trace_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```

```json
{
  "name": "acpi_ut_trace_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585995509,
      "name": "acpi_ut_trace_str",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:327",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R",
        "drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585995509,
      "name": "acpi_ut_trace_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```

```json
{
  "name": "acpi_ut_trace_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586118355,
      "name": "acpi_ut_trace_str",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:327",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R",
        "drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586118355,
      "name": "acpi_ut_trace_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```

```json
{
  "name": "acpi_ut_trace_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585995064,
      "name": "acpi_ut_trace_str",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:327",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R",
        "drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585995064,
      "name": "acpi_ut_trace_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```

```json
{
  "name": "acpi_ut_trace_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586484370,
      "name": "acpi_ut_trace_str",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:327",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R",
        "drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586484370,
      "name": "acpi_ut_trace_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```

```json
{
  "name": "acpi_ut_trace_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587738391,
      "name": "acpi_ut_trace_str",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:327",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R",
        "drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587738391,
      "name": "acpi_ut_trace_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```

```json
{
  "name": "acpi_ut_trace_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589061392,
      "name": "acpi_ut_trace_str",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:327",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R",
        "drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589061392,
      "name": "acpi_ut_trace_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```

```json
{
  "name": "acpi_ut_trace_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589352704,
      "name": "acpi_ut_trace_str",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:327",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R",
        "drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589352704,
      "name": "acpi_ut_trace_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```

```json
{
  "name": "acpi_ut_trace_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589659552,
      "name": "acpi_ut_trace_str",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:332",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R",
        "drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589659552,
      "name": "acpi_ut_trace_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```

```json
{
  "name": "acpi_ut_trace_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585240627,
      "name": "acpi_ut_trace_str",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:327",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R",
        "drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585240627,
      "name": "acpi_ut_trace_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```

```json
{
  "name": "acpi_ut_trace_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585346787,
      "name": "acpi_ut_trace_str",
      "external": true,
      "loc": "drivers/acpi/acpica/utdebug.c:327",
      "file": "drivers/acpi/acpica/utdebug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R",
        "drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R",
        "drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R",
        "drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R",
        "drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64",
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585346787,
      "name": "acpi_ut_trace_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
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
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
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
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char * function_name, const char * module_name, u32 component_id, const char * string)
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
