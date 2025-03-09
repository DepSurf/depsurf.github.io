# Function: <code>acpi_ns_delete_children</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583679297,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:299",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583679297,
      "name": "acpi_ns_delete_children",
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584003011,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:299",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584003011,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584144459,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:299",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584144459,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584211703,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:299",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584211703,
      "name": "acpi_ns_delete_children",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584545396,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:299",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584545396,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584769875,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:263",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584769875,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584871576,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:263",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584871576,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585075487,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:267",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585075487,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585211822,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:267",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585211822,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585917659,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:267",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585917659,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586039372,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:267",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586039372,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585916196,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:267",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585916196,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586404275,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:267",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586404275,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587653687,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:267",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587653687,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588957664,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:267",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588957664,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589247680,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:267",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589247680,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589554304,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:267",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589554304,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497546064,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:267",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497546064,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585081121,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:267",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585081121,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584996527,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:267",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584996527,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585163406,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:267",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585163406,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```

```json
{
  "name": "acpi_ns_delete_children",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585269566,
      "name": "acpi_ns_delete_children",
      "external": true,
      "loc": "drivers/acpi/acpica/nsalloc.c:267",
      "file": "drivers/acpi/acpica/nsalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner",
        "drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree",
        "drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter",
        "drivers/acpi/acpica/psobject.c:acpi_ps_complete_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585269566,
      "name": "acpi_ns_delete_children",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node * parent_node)
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
