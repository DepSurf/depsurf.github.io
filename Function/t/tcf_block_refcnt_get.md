# Function: <code>tcf_block_refcnt_get</code>

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
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588272896,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:789",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588272896,
      "name": "tcf_block_refcnt_get",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588664384,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:1016",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588664384,
      "name": "tcf_block_refcnt_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588886848,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:930",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588886848,
      "name": "tcf_block_refcnt_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589775584,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:893",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589775584,
      "name": "tcf_block_refcnt_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589810816,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:895",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589810816,
      "name": "tcf_block_refcnt_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589714976,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:895",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589714976,
      "name": "tcf_block_refcnt_get",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590473184,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:896",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590473184,
      "name": "tcf_block_refcnt_get",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592077184,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:913",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592077184,
      "name": "tcf_block_refcnt_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593897744,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:915",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593897744,
      "name": "tcf_block_refcnt_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594274016,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:1020",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594274016,
      "name": "tcf_block_refcnt_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595072128,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:1022",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595072128,
      "name": "tcf_block_refcnt_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502476104,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:930",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502476104,
      "name": "tcf_block_refcnt_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235191800,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:930",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235191800,
      "name": "tcf_block_refcnt_get",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296034800,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:930",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296034800,
      "name": "tcf_block_refcnt_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278657326,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:930",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278657326,
      "name": "tcf_block_refcnt_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588493232,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:930",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588493232,
      "name": "tcf_block_refcnt_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588205232,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:930",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588205232,
      "name": "tcf_block_refcnt_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588825408,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:930",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588825408,
      "name": "tcf_block_refcnt_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
```

```json
{
  "name": "tcf_block_refcnt_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588966656,
      "name": "tcf_block_refcnt_get",
      "external": false,
      "loc": "net/sched/cls_api.c:930",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588966656,
      "name": "tcf_block_refcnt_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct tcf_block * tcf_block_refcnt_get(struct net * net, u32 block_index)
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
