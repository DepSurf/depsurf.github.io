# Function: <code>acpi_ns_delete_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583679036,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:106",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583679036,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584002748,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:106",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584002748,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584144196,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:106",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584144196,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584211440,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:106",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584211440,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584544770,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:106",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584544770,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584769245,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:70",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584769245,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584870946,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:70",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584870946,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585074813,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:70",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585074813,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585211147,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:70",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585211147,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585916984,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:70",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585916984,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586038694,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:70",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586038694,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585915518,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:70",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585915518,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586403597,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:70",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586403597,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587652957,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:70",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587652957,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588956800,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:70",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588956800,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589246816,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:70",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589246816,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589553440,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:70",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589553440,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497545668,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:70",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497545668,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585080850,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:70",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585080850,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584996256,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:70",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584996256,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585162731,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:70",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585162731,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```

```json
{
  "name": "acpi_ns_delete_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585268891,
      "name": "acpi_ns_delete_node",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:70",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node",
        "drivers/acpi/acpica/nsutils.c:acpi_ns_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585268891,
      "name": "acpi_ns_delete_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node * node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node * node)
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
