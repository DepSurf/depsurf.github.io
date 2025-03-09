# Function: <code>bpf_prog_array_alloc</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580541449,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:1443",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:compute_effective_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540912,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580625294,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:1541",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:compute_effective_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580624672,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580685557,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:1791",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:compute_effective_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684896,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580752970,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:1786",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:compute_effective_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752304,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580803562,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:1786",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:compute_effective_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580802864,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580921002,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:1864",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_attach",
        "kernel/bpf/cgroup.c:compute_effective_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920304,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580917658,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:1866",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_attach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:compute_effective_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916800,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580921610,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:1962",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_attach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:compute_effective_progs",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920752,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581124126,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:1975",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_attach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:compute_effective_progs",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123264,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581393582,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:2261",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_attach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:compute_effective_progs",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581392592,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581743358,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:2234",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_attach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:compute_effective_progs",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742160,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581902670,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:2251",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_attach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:compute_effective_progs",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901472,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582026334,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:2427",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_link_create",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_attach",
        "kernel/bpf/net_namespace.c:bpf_netns_link_release",
        "kernel/bpf/cgroup.c:compute_effective_progs",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582025136,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492118964,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:1786",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:compute_effective_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492117760,
      "name": "bpf_prog_array_alloc",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226019812,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:1786",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:compute_effective_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226018908,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285326572,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:1786",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:compute_effective_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285325504,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272290588,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:1786",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:compute_effective_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272289898,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580772362,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:1786",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:compute_effective_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580771664,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580718538,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:1786",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:compute_effective_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580717840,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580763610,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:1786",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:compute_effective_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580762912,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```

```json
{
  "name": "bpf_prog_array_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580821754,
      "name": "bpf_prog_array_alloc",
      "external": true,
      "loc": "kernel/bpf/core.c:1786",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy",
        "kernel/bpf/core.c:bpf_prog_array_copy"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:compute_effective_progs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821056,
      "name": "bpf_prog_array_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct bpf_prog_array * bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
