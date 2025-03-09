# Function: <code>__try_online_node</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __try_online_node(int nid, u64 start, bool set_node_online)
```

```json
{
  "name": "__try_online_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581467532,
      "name": "__try_online_node",
      "external": false,
      "loc": "mm/memory_hotplug.c:1028",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581467392,
      "name": "__try_online_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071581471049,
      "name": "__try_online_node.cold.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __try_online_node(int nid, u64 start, bool set_node_online)
```

```json
{
  "name": "__try_online_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581583055,
      "name": "__try_online_node",
      "external": false,
      "loc": "mm/memory_hotplug.c:1009",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582912,
      "name": "__try_online_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071581586689,
      "name": "__try_online_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __try_online_node(int nid, u64 start, bool set_node_online)
```

```json
{
  "name": "__try_online_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581647727,
      "name": "__try_online_node",
      "external": false,
      "loc": "mm/memory_hotplug.c:984",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647584,
      "name": "__try_online_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071581650043,
      "name": "__try_online_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__try_online_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591173119,
      "name": "__try_online_node",
      "external": false,
      "loc": "mm/memory_hotplug.c:966",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581863072,
      "name": "__try_online_node.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__try_online_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591668909,
      "name": "__try_online_node",
      "external": false,
      "loc": "mm/memory_hotplug.c:971",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581907616,
      "name": "__try_online_node.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int __try_online_node(int nid, bool set_node_online)
```

```json
{
  "name": "__try_online_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581754011,
      "name": "__try_online_node",
      "external": false,
      "loc": "mm/memory_hotplug.c:1099",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581753936,
      "name": "__try_online_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071591273618,
      "name": "__try_online_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int __try_online_node(int nid, bool set_node_online)
```

```json
{
  "name": "__try_online_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582036107,
      "name": "__try_online_node",
      "external": false,
      "loc": "mm/memory_hotplug.c:1255",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582036032,
      "name": "__try_online_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071592207949,
      "name": "__try_online_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int __try_online_node(int nid, bool set_node_online)
```

```json
{
  "name": "__try_online_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582464561,
      "name": "__try_online_node",
      "external": false,
      "loc": "mm/memory_hotplug.c:1221",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582464480,
      "name": "__try_online_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071593985600,
      "name": "__try_online_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int __try_online_node(int nid, bool set_node_online)
```

```json
{
  "name": "__try_online_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582979488,
      "name": "__try_online_node",
      "external": false,
      "loc": "mm/memory_hotplug.c:1219",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582979488,
      "name": "__try_online_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int __try_online_node(int nid, bool set_node_online)
```

```json
{
  "name": "__try_online_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583191264,
      "name": "__try_online_node",
      "external": false,
      "loc": "mm/memory_hotplug.c:1194",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583191264,
      "name": "__try_online_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
int __try_online_node(int nid, bool set_node_online)
```

```json
{
  "name": "__try_online_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583376160,
      "name": "__try_online_node",
      "external": false,
      "loc": "mm/memory_hotplug.c:1272",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583376160,
      "name": "__try_online_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
int __try_online_node(int nid, u64 start, bool set_node_online)
```

```json
{
  "name": "__try_online_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493095736,
      "name": "__try_online_node",
      "external": false,
      "loc": "mm/memory_hotplug.c:984",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493095736,
      "name": "__try_online_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __try_online_node(int nid, u64 start, bool set_node_online)
```

```json
{
  "name": "__try_online_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286545408,
      "name": "__try_online_node",
      "external": false,
      "loc": "mm/memory_hotplug.c:984",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286545408,
      "name": "__try_online_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
    }
  ]
}
```
</details>
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
int __try_online_node(int nid, u64 start, bool set_node_online)
```

```json
{
  "name": "__try_online_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581616463,
      "name": "__try_online_node",
      "external": false,
      "loc": "mm/memory_hotplug.c:984",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581616320,
      "name": "__try_online_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071581618779,
      "name": "__try_online_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int __try_online_node(int nid, u64 start, bool set_node_online)
```

```json
{
  "name": "__try_online_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581557791,
      "name": "__try_online_node",
      "external": false,
      "loc": "mm/memory_hotplug.c:984",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581557648,
      "name": "__try_online_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071581560107,
      "name": "__try_online_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __try_online_node(int nid, u64 start, bool set_node_online)
```

```json
{
  "name": "__try_online_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581607775,
      "name": "__try_online_node",
      "external": false,
      "loc": "mm/memory_hotplug.c:984",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581607632,
      "name": "__try_online_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071581610091,
      "name": "__try_online_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __try_online_node(int nid, u64 start, bool set_node_online)
```

```json
{
  "name": "__try_online_node",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581674175,
      "name": "__try_online_node",
      "external": false,
      "loc": "mm/memory_hotplug.c:984",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581674032,
      "name": "__try_online_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071581676283,
      "name": "__try_online_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int __try_online_node(int nid, u64 start, bool set_node_online)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int __try_online_node(int nid, u64 start, bool set_node_online)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int __try_online_node(int nid, bool set_node_online)
```
</details>
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
int __try_online_node(int nid, u64 start, bool set_node_online)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __try_online_node(int nid, u64 start, bool set_node_online)
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
