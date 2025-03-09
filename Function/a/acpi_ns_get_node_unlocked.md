# Function: <code>acpi_ns_get_node_unlocked</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584156510,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:686",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584156510,
      "name": "acpi_ns_get_node_unlocked.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071584157968,
      "name": "acpi_ns_get_node_unlocked",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584223772,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:681",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584223772,
      "name": "acpi_ns_get_node_unlocked.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071584225247,
      "name": "acpi_ns_get_node_unlocked",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584569806,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:681",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584569806,
      "name": "acpi_ns_get_node_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584794944,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:647",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584794944,
      "name": "acpi_ns_get_node_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584897335,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:647",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584897335,
      "name": "acpi_ns_get_node_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585100315,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:635",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585100315,
      "name": "acpi_ns_get_node_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585236673,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:635",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585236673,
      "name": "acpi_ns_get_node_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585942493,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:635",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585942493,
      "name": "acpi_ns_get_node_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
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
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586065441,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:635",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586065441,
      "name": "acpi_ns_get_node_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
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
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585942248,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:635",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585942248,
      "name": "acpi_ns_get_node_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586430541,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:635",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586430541,
      "name": "acpi_ns_get_node_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587681557,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:635",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587681557,
      "name": "acpi_ns_get_node_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 519
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
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588991488,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:635",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588991488,
      "name": "acpi_ns_get_node_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589282000,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:635",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589282000,
      "name": "acpi_ns_get_node_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589588720,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:635",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589588720,
      "name": "acpi_ns_get_node_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497561024,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:635",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497561024,
      "name": "acpi_ns_get_node_unlocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336497562908,
      "name": "acpi_ns_get_node_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585093672,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:635",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585093672,
      "name": "acpi_ns_get_node_unlocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585095087,
      "name": "acpi_ns_get_node_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585009075,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:635",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585009075,
      "name": "acpi_ns_get_node_unlocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585010441,
      "name": "acpi_ns_get_node_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585188257,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:635",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585188257,
      "name": "acpi_ns_get_node_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```

```json
{
  "name": "acpi_ns_get_node_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585294417,
      "name": "acpi_ns_get_node_unlocked",
      "external": true,
      "loc": "drivers/acpi/acpica/nsutils.c:635",
      "file": "drivers/acpi/acpica/nsutils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op",
        "drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_get_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585294417,
      "name": "acpi_ns_get_node_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```
</details>
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
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_ns_get_node_unlocked(struct acpi_namespace_node * prefix_node, const char * pathname, u32 flags, struct acpi_namespace_node * * return_node)
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
