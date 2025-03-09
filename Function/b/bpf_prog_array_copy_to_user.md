# Function: <code>bpf_prog_array_copy_to_user</code>

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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * progs, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580541088,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:1475",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541088,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array * progs, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580624848,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:1592",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580624848,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580685088,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:1846",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685088,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580752544,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:1845",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752544,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580803104,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:1845",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580803104,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580920544,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:1923",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920544,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917040,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:1925",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917040,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580920992,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:2021",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920992,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581123504,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:2034",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123504,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581392896,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:2320",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581392896,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581742608,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:2314",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742608,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581901920,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:2331",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901920,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582025584,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:2507",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/net_namespace.c:netns_bpf_prog_query",
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582025584,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492118136,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:1845",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492118136,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226019200,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:1845",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226019200,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285325904,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:1845",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285325904,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272290184,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:1845",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272290184,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580771904,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:1845",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580771904,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580718080,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:1845",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580718080,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580763152,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:1845",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580763152,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * array, __u32 * prog_ids, u32 cnt)
```

```json
{
  "name": "bpf_prog_array_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580821296,
      "name": "bpf_prog_array_copy_to_user",
      "external": true,
      "loc": "kernel/bpf/core.c:1845",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821296,
      "name": "bpf_prog_array_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int bpf_prog_array_copy_to_user(struct bpf_prog_array * progs, __u32 * prog_ids, u32 cnt)
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
