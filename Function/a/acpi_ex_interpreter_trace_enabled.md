# Function: <code>acpi_ex_interpreter_trace_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583649849,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/exdebug.c:337",
      "file": "drivers/acpi/acpica/exdebug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/exdebug.c:acpi_ex_start_trace_method"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583992908,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:74",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584134286,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:74",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584201406,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:74",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char * name)
```

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584528192,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:74",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584528192,
      "name": "acpi_ex_interpreter_trace_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char * name)
```

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584752536,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:40",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584752536,
      "name": "acpi_ex_interpreter_trace_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char * name)
```

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584854104,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:40",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584854104,
      "name": "acpi_ex_interpreter_trace_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char * name)
```

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585057840,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:40",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585057840,
      "name": "acpi_ex_interpreter_trace_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char * name)
```

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585193925,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:40",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585193925,
      "name": "acpi_ex_interpreter_trace_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char * name)
```

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585899299,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:40",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585899299,
      "name": "acpi_ex_interpreter_trace_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char * name)
```

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586020635,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:40",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586020635,
      "name": "acpi_ex_interpreter_trace_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char * name)
```

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585897647,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:40",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585897647,
      "name": "acpi_ex_interpreter_trace_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char * name)
```

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586385151,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:40",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586385151,
      "name": "acpi_ex_interpreter_trace_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char * name)
```

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587633348,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:40",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587633348,
      "name": "acpi_ex_interpreter_trace_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
u8 acpi_ex_interpreter_trace_enabled(char * name)
```

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588933461,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:40",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method"
      ],
      "caller_func": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588932368,
      "name": "acpi_ex_interpreter_trace_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
u8 acpi_ex_interpreter_trace_enabled(char * name)
```

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589223461,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:40",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method"
      ],
      "caller_func": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589222368,
      "name": "acpi_ex_interpreter_trace_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
u8 acpi_ex_interpreter_trace_enabled(char * name)
```

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589529973,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:40",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method"
      ],
      "caller_func": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589528880,
      "name": "acpi_ex_interpreter_trace_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497538152,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:40",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char * name)
```

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585070573,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:40",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585070573,
      "name": "acpi_ex_interpreter_trace_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char * name)
```

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584986052,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:40",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584986052,
      "name": "acpi_ex_interpreter_trace_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char * name)
```

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585145509,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:40",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585145509,
      "name": "acpi_ex_interpreter_trace_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char * name)
```

```json
{
  "name": "acpi_ex_interpreter_trace_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585251669,
      "name": "acpi_ex_interpreter_trace_enabled",
      "external": false,
      "loc": "drivers/acpi/acpica/extrace.c:40",
      "file": "drivers/acpi/acpica/extrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_opcode",
        "drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method",
        "drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585251669,
      "name": "acpi_ex_interpreter_trace_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
u8 acpi_ex_interpreter_trace_enabled(char * name)
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
u8 acpi_ex_interpreter_trace_enabled(char * name)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char * name)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char * name)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u8 acpi_ex_interpreter_trace_enabled(char * name)
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
