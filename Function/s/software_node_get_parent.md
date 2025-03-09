# Function: <code>software_node_get_parent</code>

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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585832704,
      "name": "software_node_get_parent",
      "external": true,
      "loc": "drivers/base/swnode.c:476",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585832704,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586068656,
      "name": "software_node_get_parent",
      "external": false,
      "loc": "drivers/base/swnode.c:519",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586068656,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586216672,
      "name": "software_node_get_parent",
      "external": false,
      "loc": "drivers/base/swnode.c:519",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586216672,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586982128,
      "name": "software_node_get_parent",
      "external": false,
      "loc": "drivers/base/swnode.c:428",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586982128,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587067648,
      "name": "software_node_get_parent",
      "external": false,
      "loc": "drivers/base/swnode.c:428",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587067648,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586951904,
      "name": "software_node_get_parent",
      "external": false,
      "loc": "drivers/base/swnode.c:442",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586951904,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587517776,
      "name": "software_node_get_parent",
      "external": false,
      "loc": "drivers/base/swnode.c:444",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587517776,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588852019,
      "name": "software_node_get_parent",
      "external": false,
      "loc": "drivers/base/swnode.c:441",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588845504,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590356515,
      "name": "software_node_get_parent",
      "external": false,
      "loc": "drivers/base/swnode.c:441",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590349488,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590677011,
      "name": "software_node_get_parent",
      "external": false,
      "loc": "drivers/base/swnode.c:441",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590670304,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591038467,
      "name": "software_node_get_parent",
      "external": false,
      "loc": "drivers/base/swnode.c:441",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591031616,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499024960,
      "name": "software_node_get_parent",
      "external": false,
      "loc": "drivers/base/swnode.c:519",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499024960,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231586464,
      "name": "software_node_get_parent",
      "external": false,
      "loc": "drivers/base/swnode.c:519",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231586464,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292189456,
      "name": "software_node_get_parent",
      "external": false,
      "loc": "drivers/base/swnode.c:519",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292189456,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276391510,
      "name": "software_node_get_parent",
      "external": false,
      "loc": "drivers/base/swnode.c:519",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276391510,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585976880,
      "name": "software_node_get_parent",
      "external": false,
      "loc": "drivers/base/swnode.c:519",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585976880,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585826144,
      "name": "software_node_get_parent",
      "external": false,
      "loc": "drivers/base/swnode.c:519",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826144,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586166688,
      "name": "software_node_get_parent",
      "external": false,
      "loc": "drivers/base/swnode.c:519",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586166688,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586275536,
      "name": "software_node_get_parent",
      "external": false,
      "loc": "drivers/base/swnode.c:519",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586275536,
      "name": "software_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
struct fwnode_handle * software_node_get_parent(const struct fwnode_handle * fwnode)
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
