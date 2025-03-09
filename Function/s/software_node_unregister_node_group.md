# Function: <code>software_node_unregister_node_group</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void software_node_unregister_node_group(const struct software_node * * node_group)
```

```json
{
  "name": "software_node_unregister_node_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586985504,
      "name": "software_node_unregister_node_group",
      "external": true,
      "loc": "drivers/base/swnode.c:762",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586985504,
      "name": "software_node_unregister_node_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void software_node_unregister_node_group(const struct software_node * * node_group)
```

```json
{
  "name": "software_node_unregister_node_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587070736,
      "name": "software_node_unregister_node_group",
      "external": true,
      "loc": "drivers/base/swnode.c:766",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587070736,
      "name": "software_node_unregister_node_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void software_node_unregister_node_group(const struct software_node * * node_group)
```

```json
{
  "name": "software_node_unregister_node_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586955328,
      "name": "software_node_unregister_node_group",
      "external": true,
      "loc": "drivers/base/swnode.c:930",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586955328,
      "name": "software_node_unregister_node_group.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071586955440,
      "name": "software_node_unregister_node_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void software_node_unregister_node_group(const struct software_node * * node_group)
```

```json
{
  "name": "software_node_unregister_node_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587520992,
      "name": "software_node_unregister_node_group",
      "external": true,
      "loc": "drivers/base/swnode.c:932",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587520992,
      "name": "software_node_unregister_node_group.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071587521104,
      "name": "software_node_unregister_node_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void software_node_unregister_node_group(const struct software_node * * node_group)
```

```json
{
  "name": "software_node_unregister_node_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588851266,
      "name": "software_node_unregister_node_group",
      "external": true,
      "loc": "drivers/base/swnode.c:926",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_register_node_group"
      ],
      "caller_func": [
        "drivers/base/swnode.c:software_node_register_node_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588849664,
      "name": "software_node_unregister_node_group.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    },
    {
      "addr": 18446744071588849920,
      "name": "software_node_unregister_node_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void software_node_unregister_node_group(const struct software_node * * node_group)
```

```json
{
  "name": "software_node_unregister_node_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590355730,
      "name": "software_node_unregister_node_group",
      "external": true,
      "loc": "drivers/base/swnode.c:926",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_register_node_group"
      ],
      "caller_func": [
        "drivers/base/swnode.c:software_node_register_node_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590354016,
      "name": "software_node_unregister_node_group.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    },
    {
      "addr": 18446744071590354288,
      "name": "software_node_unregister_node_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void software_node_unregister_node_group(const struct software_node * * node_group)
```

```json
{
  "name": "software_node_unregister_node_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590676130,
      "name": "software_node_unregister_node_group",
      "external": true,
      "loc": "drivers/base/swnode.c:865",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_register_node_group"
      ],
      "caller_func": [
        "drivers/base/swnode.c:software_node_register_node_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590674688,
      "name": "software_node_unregister_node_group.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    },
    {
      "addr": 18446744071590674960,
      "name": "software_node_unregister_node_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void software_node_unregister_node_group(const struct software_node * * node_group)
```

```json
{
  "name": "software_node_unregister_node_group",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591037586,
      "name": "software_node_unregister_node_group",
      "external": true,
      "loc": "drivers/base/swnode.c:868",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_register_node_group"
      ],
      "caller_func": [
        "drivers/base/swnode.c:software_node_register_node_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591036144,
      "name": "software_node_unregister_node_group.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    },
    {
      "addr": 18446744071591036416,
      "name": "software_node_unregister_node_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void software_node_unregister_node_group(const struct software_node * * node_group)
```
</details>
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
