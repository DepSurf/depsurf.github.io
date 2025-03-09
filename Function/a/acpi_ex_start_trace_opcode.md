# Function: <code>acpi_ex_start_trace_opcode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583650203,
      "name": "acpi_ex_start_trace_opcode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:338",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583993262,
      "name": "acpi_ex_start_trace_opcode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:313",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584134577,
      "name": "acpi_ex_start_trace_opcode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584201697,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:313",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584201697,
      "name": "acpi_ex_start_trace_opcode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584528864,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:313",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584528864,
      "name": "acpi_ex_start_trace_opcode",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584753208,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:279",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584753208,
      "name": "acpi_ex_start_trace_opcode",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584854779,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:279",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584854779,
      "name": "acpi_ex_start_trace_opcode",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585058517,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:279",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585058517,
      "name": "acpi_ex_start_trace_opcode",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585194602,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:279",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585194602,
      "name": "acpi_ex_start_trace_opcode",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585899976,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:279",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585899976,
      "name": "acpi_ex_start_trace_opcode",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586021312,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:279",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586021312,
      "name": "acpi_ex_start_trace_opcode",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585898322,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:279",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585898322,
      "name": "acpi_ex_start_trace_opcode",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586385826,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:279",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586385826,
      "name": "acpi_ex_start_trace_opcode",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587634091,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:279",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587634091,
      "name": "acpi_ex_start_trace_opcode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588933328,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:279",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588933328,
      "name": "acpi_ex_start_trace_opcode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589223328,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:279",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589223328,
      "name": "acpi_ex_start_trace_opcode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589529840,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:279",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589529840,
      "name": "acpi_ex_start_trace_opcode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497538488,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:279",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497538488,
      "name": "acpi_ex_start_trace_opcode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585070956,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:279",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585070956,
      "name": "acpi_ex_start_trace_opcode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584986435,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:279",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584986435,
      "name": "acpi_ex_start_trace_opcode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585146186,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:279",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585146186,
      "name": "acpi_ex_start_trace_opcode",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```

```json
{
  "name": "acpi_ex_start_trace_opcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585252346,
      "name": "acpi_ex_start_trace_opcode",
      "external": true,
      "loc": "drivers/acpi/acpica/extrace.c:279",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585252346,
      "name": "acpi_ex_start_trace_opcode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```
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
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_ex_start_trace_opcode(union acpi_parse_object * op, struct acpi_walk_state * walk_state)
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
