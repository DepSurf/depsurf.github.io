# Function: <code>srcu_funnel_gp_start</code>

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
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579836161,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:613",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
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
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579876468,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:614",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
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
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579910510,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:645",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
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
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579958119,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:656",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
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
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579994683,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:631",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
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
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580044811,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:631",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
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
void srcu_funnel_gp_start(struct srcu_struct * ssp, struct srcu_data * sdp, long unsigned int s, bool do_norm)
```

```json
{
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580100224,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:644",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100224,
      "name": "srcu_funnel_gp_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
void srcu_funnel_gp_start(struct srcu_struct * ssp, struct srcu_data * sdp, long unsigned int s, bool do_norm)
```

```json
{
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580081776,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:633",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:__call_srcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081776,
      "name": "srcu_funnel_gp_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
void srcu_funnel_gp_start(struct srcu_struct * ssp, struct srcu_data * sdp, long unsigned int s, bool do_norm)
```

```json
{
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580083136,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:636",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083136,
      "name": "srcu_funnel_gp_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
void srcu_funnel_gp_start(struct srcu_struct * ssp, struct srcu_data * sdp, long unsigned int s, bool do_norm)
```

```json
{
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:628",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580219536,
      "name": "srcu_funnel_gp_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
    },
    {
      "addr": 18446744071592141486,
      "name": "srcu_funnel_gp_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void srcu_funnel_gp_start(struct srcu_struct * ssp, struct srcu_data * sdp, long unsigned int s, bool do_norm)
```

```json
{
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:882",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580379872,
      "name": "srcu_funnel_gp_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 804
    },
    {
      "addr": 18446744071593912571,
      "name": "srcu_funnel_gp_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void srcu_funnel_gp_start(struct srcu_struct * ssp, struct srcu_data * sdp, long unsigned int s, bool do_norm)
```

```json
{
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:946",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602064,
      "name": "srcu_funnel_gp_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 804
    },
    {
      "addr": 18446744071595990705,
      "name": "srcu_funnel_gp_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void srcu_funnel_gp_start(struct srcu_struct * ssp, struct srcu_data * sdp, long unsigned int s, bool do_norm)
```

```json
{
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:998",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580675616,
      "name": "srcu_funnel_gp_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
    },
    {
      "addr": 18446744071596508840,
      "name": "srcu_funnel_gp_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void srcu_funnel_gp_start(struct srcu_struct * ssp, struct srcu_data * sdp, long unsigned int s, bool do_norm)
```

```json
{
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:989",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_gp_start_if_needed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580742288,
      "name": "srcu_funnel_gp_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
    },
    {
      "addr": 18446744071597406578,
      "name": "srcu_funnel_gp_start.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491250568,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:631",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
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
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225260448,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:631",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
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
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284149800,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:631",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
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
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271775588,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:631",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
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
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580013547,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:631",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
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
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579952289,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:631",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
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
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580005083,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:631",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
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
  "name": "srcu_funnel_gp_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580054187,
      "name": "srcu_funnel_gp_start",
      "external": false,
      "loc": "kernel/rcu/srcutree.c:631",
      "file": "kernel/rcu/srcutree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:__call_srcu"
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
void srcu_funnel_gp_start(struct srcu_struct * ssp, struct srcu_data * sdp, long unsigned int s, bool do_norm)
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
