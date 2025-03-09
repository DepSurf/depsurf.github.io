# Function: <code>sockopt_alloc_buf</code>

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
int sockopt_alloc_buf(struct bpf_sockopt_kern * ctx, int max_optlen)
```

```json
{
  "name": "sockopt_alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580909280,
      "name": "sockopt_alloc_buf",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:957",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580909280,
      "name": "sockopt_alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sockopt_alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580962631,
      "name": "sockopt_alloc_buf",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:967",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
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
int sockopt_alloc_buf(struct bpf_sockopt_kern * ctx, int max_optlen)
```

```json
{
  "name": "sockopt_alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581125312,
      "name": "sockopt_alloc_buf",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1277",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125312,
      "name": "sockopt_alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int sockopt_alloc_buf(struct bpf_sockopt_kern * ctx, int max_optlen)
```

```json
{
  "name": "sockopt_alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581159232,
      "name": "sockopt_alloc_buf",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1301",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581159232,
      "name": "sockopt_alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int sockopt_alloc_buf(struct bpf_sockopt_kern * ctx, int max_optlen, struct bpf_sockopt_buf * buf)
```

```json
{
  "name": "sockopt_alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581173952,
      "name": "sockopt_alloc_buf",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1305",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581173952,
      "name": "sockopt_alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int sockopt_alloc_buf(struct bpf_sockopt_kern * ctx, int max_optlen, struct bpf_sockopt_buf * buf)
```

```json
{
  "name": "sockopt_alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413088,
      "name": "sockopt_alloc_buf",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1335",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413088,
      "name": "sockopt_alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int sockopt_alloc_buf(struct bpf_sockopt_kern * ctx, int max_optlen, struct bpf_sockopt_buf * buf)
```

```json
{
  "name": "sockopt_alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581738960,
      "name": "sockopt_alloc_buf",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1503",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581738960,
      "name": "sockopt_alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int sockopt_alloc_buf(struct bpf_sockopt_kern * ctx, int max_optlen, struct bpf_sockopt_buf * buf)
```

```json
{
  "name": "sockopt_alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582150576,
      "name": "sockopt_alloc_buf",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1742",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582150576,
      "name": "sockopt_alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int sockopt_alloc_buf(struct bpf_sockopt_kern * ctx, int max_optlen, struct bpf_sockopt_buf * buf)
```

```json
{
  "name": "sockopt_alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582348016,
      "name": "sockopt_alloc_buf",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1742",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582348016,
      "name": "sockopt_alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int sockopt_alloc_buf(struct bpf_sockopt_kern * ctx, int max_optlen, struct bpf_sockopt_buf * buf)
```

```json
{
  "name": "sockopt_alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582514720,
      "name": "sockopt_alloc_buf",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1757",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582514720,
      "name": "sockopt_alloc_buf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
  "name": "sockopt_alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492311496,
      "name": "sockopt_alloc_buf",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:967",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int sockopt_alloc_buf(struct bpf_sockopt_kern * ctx, int max_optlen)
```

```json
{
  "name": "sockopt_alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226194544,
      "name": "sockopt_alloc_buf",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:967",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226194544,
      "name": "sockopt_alloc_buf",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "sockopt_alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285546480,
      "name": "sockopt_alloc_buf",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:967",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
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
  "name": "sockopt_alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272438644,
      "name": "sockopt_alloc_buf",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:967",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
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
  "name": "sockopt_alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580931431,
      "name": "sockopt_alloc_buf",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:967",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
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
  "name": "sockopt_alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580877495,
      "name": "sockopt_alloc_buf",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:967",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
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
  "name": "sockopt_alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580922679,
      "name": "sockopt_alloc_buf",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:967",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
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
  "name": "sockopt_alloc_buf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580982968,
      "name": "sockopt_alloc_buf",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:967",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt"
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int sockopt_alloc_buf(struct bpf_sockopt_kern * ctx, int max_optlen)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int sockopt_alloc_buf(struct bpf_sockopt_kern * ctx, int max_optlen)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int sockopt_alloc_buf(struct bpf_sockopt_kern * ctx, int max_optlen)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_sockopt_buf * buf</code>
</li>
</ul>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int sockopt_alloc_buf(struct bpf_sockopt_kern * ctx, int max_optlen)
```
</details>
</li>
</ul>
