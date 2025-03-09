# Function: <code>software_node_register</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int software_node_register(const struct software_node * node)
```

```json
{
  "name": "software_node_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586070992,
      "name": "software_node_register",
      "external": true,
      "loc": "drivers/base/swnode.c:757",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_register_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586070992,
      "name": "software_node_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int software_node_register(const struct software_node * node)
```

```json
{
  "name": "software_node_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586220240,
      "name": "software_node_register",
      "external": true,
      "loc": "drivers/base/swnode.c:797",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_register_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586220240,
      "name": "software_node_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int software_node_register(const struct software_node * node)
```

```json
{
  "name": "software_node_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586986126,
      "name": "software_node_register",
      "external": true,
      "loc": "drivers/base/swnode.c:782",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_register_nodes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586984320,
      "name": "software_node_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int software_node_register(const struct software_node * node)
```

```json
{
  "name": "software_node_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587069904,
      "name": "software_node_register",
      "external": true,
      "loc": "drivers/base/swnode.c:782",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_register_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587069904,
      "name": "software_node_register",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int software_node_register(const struct software_node * node)
```

```json
{
  "name": "software_node_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586954944,
      "name": "software_node_register",
      "external": true,
      "loc": "drivers/base/swnode.c:950",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:software_node_register_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586954944,
      "name": "software_node_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int software_node_register(const struct software_node * node)
```

```json
{
  "name": "software_node_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587520608,
      "name": "software_node_register",
      "external": true,
      "loc": "drivers/base/swnode.c:952",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:software_node_register_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587520608,
      "name": "software_node_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int software_node_register(const struct software_node * node)
```

```json
{
  "name": "software_node_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588850672,
      "name": "software_node_register",
      "external": true,
      "loc": "drivers/base/swnode.c:946",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:software_node_register_node_group",
        "drivers/base/swnode.c:software_node_register_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588850672,
      "name": "software_node_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int software_node_register(const struct software_node * node)
```

```json
{
  "name": "software_node_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590355104,
      "name": "software_node_register",
      "external": true,
      "loc": "drivers/base/swnode.c:946",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:software_node_register_node_group",
        "drivers/base/swnode.c:software_node_register_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590355104,
      "name": "software_node_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int software_node_register(const struct software_node * node)
```

```json
{
  "name": "software_node_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590675760,
      "name": "software_node_register",
      "external": true,
      "loc": "drivers/base/swnode.c:885",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:software_node_register_node_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590675760,
      "name": "software_node_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int software_node_register(const struct software_node * node)
```

```json
{
  "name": "software_node_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591037216,
      "name": "software_node_register",
      "external": true,
      "loc": "drivers/base/swnode.c:888",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:device_add_software_node",
        "drivers/base/swnode.c:software_node_register_node_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591037216,
      "name": "software_node_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int software_node_register(const struct software_node * node)
```

```json
{
  "name": "software_node_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499028344,
      "name": "software_node_register",
      "external": true,
      "loc": "drivers/base/swnode.c:797",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_register_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499028344,
      "name": "software_node_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int software_node_register(const struct software_node * node)
```

```json
{
  "name": "software_node_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231588972,
      "name": "software_node_register",
      "external": true,
      "loc": "drivers/base/swnode.c:797",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_register_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231588972,
      "name": "software_node_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int software_node_register(const struct software_node * node)
```

```json
{
  "name": "software_node_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292195520,
      "name": "software_node_register",
      "external": true,
      "loc": "drivers/base/swnode.c:797",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_register_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292195520,
      "name": "software_node_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int software_node_register(const struct software_node * node)
```

```json
{
  "name": "software_node_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276394330,
      "name": "software_node_register",
      "external": true,
      "loc": "drivers/base/swnode.c:797",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_register_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276394330,
      "name": "software_node_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int software_node_register(const struct software_node * node)
```

```json
{
  "name": "software_node_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585980448,
      "name": "software_node_register",
      "external": true,
      "loc": "drivers/base/swnode.c:797",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_register_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585980448,
      "name": "software_node_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int software_node_register(const struct software_node * node)
```

```json
{
  "name": "software_node_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585829712,
      "name": "software_node_register",
      "external": true,
      "loc": "drivers/base/swnode.c:797",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_register_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585829712,
      "name": "software_node_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int software_node_register(const struct software_node * node)
```

```json
{
  "name": "software_node_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586170256,
      "name": "software_node_register",
      "external": true,
      "loc": "drivers/base/swnode.c:797",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_register_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586170256,
      "name": "software_node_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int software_node_register(const struct software_node * node)
```

```json
{
  "name": "software_node_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586277888,
      "name": "software_node_register",
      "external": true,
      "loc": "drivers/base/swnode.c:797",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_register_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586277888,
      "name": "software_node_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int software_node_register(const struct software_node * node)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
