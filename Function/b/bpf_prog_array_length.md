# Function: <code>bpf_prog_array_length</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int bpf_prog_array_length(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580541008,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:1461",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541008,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int bpf_prog_array_length(struct bpf_prog_array * progs)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580625565,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:1559",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580624768,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580685849,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:1810",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685008,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580753214,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:1804",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752416,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580803806,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:1804",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580802976,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580921252,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:1882",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920416,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580917908,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:1884",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916912,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580921861,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:1980",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920864,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581124389,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:1993",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123376,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581393865,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:2279",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581392736,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581743657,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:2273",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742416,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581902969,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:2290",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901728,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582026633,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:2466",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582025392,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492119292,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:1804",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492117928,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226020076,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:1804",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226019036,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285327000,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:1804",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285325696,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272290824,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:1804",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272290046,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580772606,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:1804",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580771776,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580718782,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:1804",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580717952,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580763854,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:1804",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580763024,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bpf_prog_array_length(struct bpf_prog_array * array)
```

```json
{
  "name": "bpf_prog_array_length",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580821998,
      "name": "bpf_prog_array_length",
      "external": true,
      "loc": "kernel/bpf/core.c:1804",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_copy_info"
      ],
      "caller_func": [
        "kernel/trace/bpf_trace.c:perf_event_attach_bpf_prog",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821168,
      "name": "bpf_prog_array_length",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int bpf_prog_array_length(struct bpf_prog_array * progs)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_prog_array * array</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_prog_array * progs</code>
</li>
</ul>
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
