# Function: <code>software_node_get</code>

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
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585833040,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:431",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585833040,
      "name": "software_node_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586068720,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:473",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_reference_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586068720,
      "name": "software_node_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586216752,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:473",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_reference_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586216752,
      "name": "software_node_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586985960,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:350",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_get_reference_args"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586981872,
      "name": "software_node_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587071880,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:350",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_get_reference_args"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587067200,
      "name": "software_node_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586956213,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:364",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_reference_args"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586951344,
      "name": "software_node_get",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587522069,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:366",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_reference_args"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587517216,
      "name": "software_node_get",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588848554,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:366",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_reference_args"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588844880,
      "name": "software_node_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590352794,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:366",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_reference_args"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590348800,
      "name": "software_node_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590673744,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:366",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_reference_args"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590669616,
      "name": "software_node_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591035104,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:366",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:software_node_graph_get_port_parent",
        "drivers/base/swnode.c:software_node_graph_get_remote_endpoint",
        "drivers/base/swnode.c:software_node_graph_get_next_endpoint",
        "drivers/base/swnode.c:software_node_get_reference_args"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591030928,
      "name": "software_node_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499025072,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:473",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_reference_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499025072,
      "name": "software_node_get",
      "section": ".text",
      "bind": "STB_LOCAL",
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
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231586560,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:473",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_reference_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231586560,
      "name": "software_node_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292189584,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:473",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_reference_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292189584,
      "name": "software_node_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276391598,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:473",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_reference_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276391598,
      "name": "software_node_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585976960,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:473",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_reference_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585976960,
      "name": "software_node_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585826224,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:473",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_reference_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826224,
      "name": "software_node_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586166768,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:473",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_reference_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586166768,
      "name": "software_node_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
```

```json
{
  "name": "software_node_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586275616,
      "name": "software_node_get",
      "external": false,
      "loc": "drivers/base/swnode.c:473",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:software_node_get_reference_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586275616,
      "name": "software_node_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
struct fwnode_handle * software_node_get(struct fwnode_handle * fwnode)
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
