# Function: <code>init_srcu_struct_nodes</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579832447,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:61",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579872781,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:62",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579906749,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:89",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
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
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579954285,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:95",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
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
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579992830,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:83",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
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
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580042958,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:83",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
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
void init_srcu_struct_nodes(struct srcu_struct * ssp, bool is_static)
```

```json
{
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580097888,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:96",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097888,
      "name": "init_srcu_struct_nodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 870
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
void init_srcu_struct_nodes(struct srcu_struct * ssp, bool is_static)
```

```json
{
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580079424,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:83",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580079424,
      "name": "init_srcu_struct_nodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 863
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
void init_srcu_struct_nodes(struct srcu_struct * ssp, bool is_static)
```

```json
{
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580080992,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:83",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080992,
      "name": "init_srcu_struct_nodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 873
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void init_srcu_struct_nodes(struct srcu_struct * ssp)
```

```json
{
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:83",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580216928,
      "name": "init_srcu_struct_nodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1300
    },
    {
      "addr": 18446744071592141455,
      "name": "init_srcu_struct_nodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool init_srcu_struct_nodes(struct srcu_struct * ssp, gfp_t gfp_flags)
```

```json
{
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:164",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580376992,
      "name": "init_srcu_struct_nodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1388
    },
    {
      "addr": 18446744071593912497,
      "name": "init_srcu_struct_nodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool init_srcu_struct_nodes(struct srcu_struct * ssp, gfp_t gfp_flags)
```

```json
{
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:164",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580604800,
      "name": "init_srcu_struct_nodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
    },
    {
      "addr": 18446744071595990745,
      "name": "init_srcu_struct_nodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool init_srcu_struct_nodes(struct srcu_struct * ssp, gfp_t gfp_flags)
```

```json
{
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:164",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580678608,
      "name": "init_srcu_struct_nodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1363
    },
    {
      "addr": 18446744071596508901,
      "name": "init_srcu_struct_nodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool init_srcu_struct_nodes(struct srcu_struct * ssp, gfp_t gfp_flags)
```

```json
{
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:164",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_gp_end",
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580745280,
      "name": "init_srcu_struct_nodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1362
    },
    {
      "addr": 18446744071597406639,
      "name": "init_srcu_struct_nodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491244608,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:83",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
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
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225257704,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:83",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
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
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284147136,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:83",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
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
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271773244,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:83",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
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
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580011694,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:83",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
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
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579950446,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:83",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
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
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580003230,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:83",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
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
  "name": "init_srcu_struct_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580050558,
      "name": "init_srcu_struct_nodes",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:83",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:init_srcu_struct_fields"
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
void init_srcu_struct_nodes(struct srcu_struct * ssp, bool is_static)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool is_static</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
