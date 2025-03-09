# Function: <code>tcf_chain_tp_insert_unique</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_tp_insert_unique",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588684379,
      "name": "tcf_chain_tp_insert_unique",
      "external": false,
      "loc": "net/sched/cls_api.c:1735",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_new_tfilter"
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
  "name": "tcf_chain_tp_insert_unique",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588910131,
      "name": "tcf_chain_tp_insert_unique",
      "external": false,
      "loc": "net/sched/cls_api.c:1673",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_new_tfilter"
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
struct tcf_proto * tcf_chain_tp_insert_unique(struct tcf_chain * chain, struct tcf_proto * tp_new, u32 protocol, u32 prio, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_tp_insert_unique",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589782112,
      "name": "tcf_chain_tp_insert_unique",
      "external": false,
      "loc": "net/sched/cls_api.c:1686",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589782112,
      "name": "tcf_chain_tp_insert_unique",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
struct tcf_proto * tcf_chain_tp_insert_unique(struct tcf_chain * chain, struct tcf_proto * tp_new, u32 protocol, u32 prio, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_tp_insert_unique",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589818784,
      "name": "tcf_chain_tp_insert_unique",
      "external": false,
      "loc": "net/sched/cls_api.c:1688",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589818784,
      "name": "tcf_chain_tp_insert_unique",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
struct tcf_proto * tcf_chain_tp_insert_unique(struct tcf_chain * chain, struct tcf_proto * tp_new, u32 protocol, u32 prio, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_tp_insert_unique",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589719040,
      "name": "tcf_chain_tp_insert_unique",
      "external": false,
      "loc": "net/sched/cls_api.c:1689",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589719040,
      "name": "tcf_chain_tp_insert_unique",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
struct tcf_proto * tcf_chain_tp_insert_unique(struct tcf_chain * chain, struct tcf_proto * tp_new, u32 protocol, u32 prio, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_tp_insert_unique",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_chain_tp_insert_unique",
      "external": false,
      "loc": "net/sched/cls_api.c:1687",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590477264,
      "name": "tcf_chain_tp_insert_unique",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
    },
    {
      "addr": 18446744071592710511,
      "name": "tcf_chain_tp_insert_unique.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct tcf_proto * tcf_chain_tp_insert_unique(struct tcf_chain * chain, struct tcf_proto * tp_new, u32 protocol, u32 prio, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_tp_insert_unique",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_chain_tp_insert_unique",
      "external": false,
      "loc": "net/sched/cls_api.c:1706",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592083536,
      "name": "tcf_chain_tp_insert_unique",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    },
    {
      "addr": 18446744071594596782,
      "name": "tcf_chain_tp_insert_unique.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct tcf_proto * tcf_chain_tp_insert_unique(struct tcf_chain * chain, struct tcf_proto * tp_new, u32 protocol, u32 prio, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_tp_insert_unique",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_chain_tp_insert_unique",
      "external": false,
      "loc": "net/sched/cls_api.c:1708",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593902064,
      "name": "tcf_chain_tp_insert_unique",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    },
    {
      "addr": 18446744071596332984,
      "name": "tcf_chain_tp_insert_unique.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct tcf_proto * tcf_chain_tp_insert_unique(struct tcf_chain * chain, struct tcf_proto * tp_new, u32 protocol, u32 prio, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_tp_insert_unique",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_chain_tp_insert_unique",
      "external": false,
      "loc": "net/sched/cls_api.c:1856",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594281856,
      "name": "tcf_chain_tp_insert_unique",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    },
    {
      "addr": 18446744071596861872,
      "name": "tcf_chain_tp_insert_unique.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct tcf_proto * tcf_chain_tp_insert_unique(struct tcf_chain * chain, struct tcf_proto * tp_new, u32 protocol, u32 prio, bool rtnl_held)
```

```json
{
  "name": "tcf_chain_tp_insert_unique",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_chain_tp_insert_unique",
      "external": false,
      "loc": "net/sched/cls_api.c:1906",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595080784,
      "name": "tcf_chain_tp_insert_unique",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    },
    {
      "addr": 18446744071597786964,
      "name": "tcf_chain_tp_insert_unique.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "tcf_chain_tp_insert_unique",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502501676,
      "name": "tcf_chain_tp_insert_unique",
      "external": false,
      "loc": "net/sched/cls_api.c:1673",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_new_tfilter"
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
  "name": "tcf_chain_tp_insert_unique",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235209152,
      "name": "tcf_chain_tp_insert_unique",
      "external": false,
      "loc": "net/sched/cls_api.c:1673",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_new_tfilter"
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
  "name": "tcf_chain_tp_insert_unique",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296060228,
      "name": "tcf_chain_tp_insert_unique",
      "external": false,
      "loc": "net/sched/cls_api.c:1673",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_new_tfilter"
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
  "name": "tcf_chain_tp_insert_unique",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278671374,
      "name": "tcf_chain_tp_insert_unique",
      "external": false,
      "loc": "net/sched/cls_api.c:1673",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_new_tfilter"
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
  "name": "tcf_chain_tp_insert_unique",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588516515,
      "name": "tcf_chain_tp_insert_unique",
      "external": false,
      "loc": "net/sched/cls_api.c:1673",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_new_tfilter"
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
  "name": "tcf_chain_tp_insert_unique",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588228515,
      "name": "tcf_chain_tp_insert_unique",
      "external": false,
      "loc": "net/sched/cls_api.c:1673",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_new_tfilter"
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
  "name": "tcf_chain_tp_insert_unique",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588848691,
      "name": "tcf_chain_tp_insert_unique",
      "external": false,
      "loc": "net/sched/cls_api.c:1673",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_new_tfilter"
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
  "name": "tcf_chain_tp_insert_unique",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588984738,
      "name": "tcf_chain_tp_insert_unique",
      "external": false,
      "loc": "net/sched/cls_api.c:1673",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_new_tfilter"
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
struct tcf_proto * tcf_chain_tp_insert_unique(struct tcf_chain * chain, struct tcf_proto * tp_new, u32 protocol, u32 prio, bool rtnl_held)
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
