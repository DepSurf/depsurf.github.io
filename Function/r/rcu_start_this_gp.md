# Function: <code>rcu_start_this_gp</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579918730,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:1644",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:1471",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:1123",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:1131",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool rcu_start_this_gp(struct rcu_node * rnp_start, struct rcu_data * rdp, long unsigned int gp_seq_req)
```

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580113296,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:1330",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580113296,
      "name": "rcu_start_this_gp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
bool rcu_start_this_gp(struct rcu_node * rnp_start, struct rcu_data * rdp, long unsigned int gp_seq_req)
```

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094784,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:1410",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094784,
      "name": "rcu_start_this_gp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
bool rcu_start_this_gp(struct rcu_node * rnp_start, struct rcu_data * rdp, long unsigned int gp_seq_req)
```

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580096656,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:1414",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:start_poll_synchronize_rcu",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096656,
      "name": "rcu_start_this_gp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
bool rcu_start_this_gp(struct rcu_node * rnp_start, struct rcu_data * rdp, long unsigned int gp_seq_req)
```

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580235952,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:1367",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:start_poll_synchronize_rcu",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580235952,
      "name": "rcu_start_this_gp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
bool rcu_start_this_gp(struct rcu_node * rnp_start, struct rcu_data * rdp, long unsigned int gp_seq_req)
```

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580384608,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:1383",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:start_poll_synchronize_rcu",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580384608,
      "name": "rcu_start_this_gp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
bool rcu_start_this_gp(struct rcu_node * rnp_start, struct rcu_data * rdp, long unsigned int gp_seq_req)
```

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580611648,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:958",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:start_poll_synchronize_rcu_common",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580611648,
      "name": "rcu_start_this_gp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
bool rcu_start_this_gp(struct rcu_node * rnp_start, struct rcu_data * rdp, long unsigned int gp_seq_req)
```

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580685488,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:918",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:start_poll_synchronize_rcu_common",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685488,
      "name": "rcu_start_this_gp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
bool rcu_start_this_gp(struct rcu_node * rnp_start, struct rcu_data * rdp, long unsigned int gp_seq_req)
```

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580752304,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:928",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:start_poll_synchronize_rcu_common",
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752304,
      "name": "rcu_start_this_gp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:1131",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:1131",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:1131",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271787884,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:1131",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:1131",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:1131",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:1131",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_start_this_gp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_start_this_gp",
      "external": false,
      "loc": "kernel/rcu/tree.c:1131",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_accelerate_cbs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool rcu_start_this_gp(struct rcu_node * rnp_start, struct rcu_data * rdp, long unsigned int gp_seq_req)
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
