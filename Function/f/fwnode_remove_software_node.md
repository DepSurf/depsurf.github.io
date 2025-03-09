# Function: <code>fwnode_remove_software_node</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585832976,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:608",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585832976,
      "name": "fwnode_remove_software_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586068928,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:800",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/swnode.c:software_node_unregister_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586068928,
      "name": "fwnode_remove_software_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586216960,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:840",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/swnode.c:software_node_unregister_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586216960,
      "name": "fwnode_remove_software_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586986206,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:839",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_register_nodes"
      ],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586982416,
      "name": "fwnode_remove_software_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587070049,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:842",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_unregister_nodes"
      ],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587067936,
      "name": "fwnode_remove_software_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586955131,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:1007",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_unregister_nodes"
      ],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586952192,
      "name": "fwnode_remove_software_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587520795,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:1009",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_unregister_nodes"
      ],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587518064,
      "name": "fwnode_remove_software_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588849550,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:1003",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_unregister_nodes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588845824,
      "name": "fwnode_remove_software_node",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590353886,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:1003",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_unregister_nodes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590349856,
      "name": "fwnode_remove_software_node",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590670672,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:942",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590670672,
      "name": "fwnode_remove_software_node",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591031984,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:945",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591031984,
      "name": "fwnode_remove_software_node",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499025352,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:840",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/swnode.c:software_node_unregister_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499025352,
      "name": "fwnode_remove_software_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231586796,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:840",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/swnode.c:software_node_unregister_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231586796,
      "name": "fwnode_remove_software_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292190736,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:840",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/swnode.c:software_node_unregister_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292190736,
      "name": "fwnode_remove_software_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276392040,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:840",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/swnode.c:software_node_unregister_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276392040,
      "name": "fwnode_remove_software_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585977168,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:840",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/swnode.c:software_node_unregister_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585977168,
      "name": "fwnode_remove_software_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585826432,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:840",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/swnode.c:software_node_unregister_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826432,
      "name": "fwnode_remove_software_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586166976,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:840",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/swnode.c:software_node_unregister_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586166976,
      "name": "fwnode_remove_software_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```

```json
{
  "name": "fwnode_remove_software_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586275824,
      "name": "fwnode_remove_software_node",
      "external": true,
      "loc": "drivers/base/swnode.c:840",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_remove_properties",
        "drivers/base/swnode.c:software_node_unregister_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586275824,
      "name": "fwnode_remove_software_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void fwnode_remove_software_node(struct fwnode_handle * fwnode)
```
</details>
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
