# Function: <code>tcf_chain_flush</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain * chain)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587240128,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:204",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/cls_api.c:tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587240128,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void tcf_chain_flush(struct tcf_chain * chain)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587755808,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:205",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/cls_api.c:tcf_block_put_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587755808,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void tcf_chain_flush(struct tcf_chain * chain)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588095344,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:221",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588095344,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void tcf_chain_flush(struct tcf_chain * chain)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588278128,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:356",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:__tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588278128,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void tcf_chain_flush(struct tcf_chain * chain, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588670224,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:529",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588670224,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void tcf_chain_flush(struct tcf_chain * chain, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588893760,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:581",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588893760,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void tcf_chain_flush(struct tcf_chain * chain, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589782704,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:596",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:__tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589782704,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void tcf_chain_flush(struct tcf_chain * chain, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589817536,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:596",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:__tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589817536,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void tcf_chain_flush(struct tcf_chain * chain, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589718608,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:596",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:__tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589718608,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void tcf_chain_flush(struct tcf_chain * chain, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590476832,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:596",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:__tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590476832,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void tcf_chain_flush(struct tcf_chain * chain, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592082112,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:613",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:__tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592082112,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void tcf_chain_flush(struct tcf_chain * chain, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593901456,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:615",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:__tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593901456,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void tcf_chain_flush(struct tcf_chain * chain, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594280336,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:720",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:__tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594280336,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void tcf_chain_flush(struct tcf_chain * chain, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595079264,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:720",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:__tcf_block_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595079264,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void tcf_chain_flush(struct tcf_chain * chain, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502485104,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:581",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502485104,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void tcf_chain_flush(struct tcf_chain * chain, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235200552,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:581",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235200552,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void tcf_chain_flush(struct tcf_chain * chain, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296049168,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:581",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296049168,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void tcf_chain_flush(struct tcf_chain * chain, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278665276,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:581",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278665276,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
void tcf_chain_flush(struct tcf_chain * chain, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588500144,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:581",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588500144,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void tcf_chain_flush(struct tcf_chain * chain, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588212144,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:581",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588212144,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void tcf_chain_flush(struct tcf_chain * chain, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588832320,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:581",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588832320,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void tcf_chain_flush(struct tcf_chain * chain, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588975680,
      "name": "tcf_chain_flush",
      "external": false,
      "loc": "net/sched/cls_api.c:581",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588975680,
      "name": "tcf_chain_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void tcf_chain_flush(struct tcf_chain * chain)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool rtnl_held</code>
</li>
</ul>
</details>
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
