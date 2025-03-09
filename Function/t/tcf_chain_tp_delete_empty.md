# Function: <code>tcf_chain_tp_delete_empty</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_chain_tp_delete_empty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_chain_tp_delete_empty",
      "external": false,
      "loc": "net/sched/cls_api.c:1763",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588670336,
      "name": "tcf_chain_tp_delete_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071588687041,
      "name": "tcf_chain_tp_delete_empty.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_chain_tp_delete_empty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588893952,
      "name": "tcf_chain_tp_delete_empty",
      "external": false,
      "loc": "net/sched/cls_api.c:1707",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588893952,
      "name": "tcf_chain_tp_delete_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_chain_tp_delete_empty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589783536,
      "name": "tcf_chain_tp_delete_empty",
      "external": false,
      "loc": "net/sched/cls_api.c:1720",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589783536,
      "name": "tcf_chain_tp_delete_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_chain_tp_delete_empty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589818368,
      "name": "tcf_chain_tp_delete_empty",
      "external": false,
      "loc": "net/sched/cls_api.c:1722",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589818368,
      "name": "tcf_chain_tp_delete_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_chain_tp_delete_empty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589718800,
      "name": "tcf_chain_tp_delete_empty",
      "external": false,
      "loc": "net/sched/cls_api.c:1723",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589718800,
      "name": "tcf_chain_tp_delete_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_chain_tp_delete_empty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_chain_tp_delete_empty",
      "external": false,
      "loc": "net/sched/cls_api.c:1721",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590477024,
      "name": "tcf_chain_tp_delete_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    },
    {
      "addr": 18446744071592710484,
      "name": "tcf_chain_tp_delete_empty.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_chain_tp_delete_empty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_chain_tp_delete_empty",
      "external": false,
      "loc": "net/sched/cls_api.c:1740",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592083072,
      "name": "tcf_chain_tp_delete_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071594596755,
      "name": "tcf_chain_tp_delete_empty.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_chain_tp_delete_empty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_chain_tp_delete_empty",
      "external": false,
      "loc": "net/sched/cls_api.c:1742",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593901760,
      "name": "tcf_chain_tp_delete_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071596332957,
      "name": "tcf_chain_tp_delete_empty.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_chain_tp_delete_empty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_chain_tp_delete_empty",
      "external": false,
      "loc": "net/sched/cls_api.c:1890",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594281344,
      "name": "tcf_chain_tp_delete_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071596861845,
      "name": "tcf_chain_tp_delete_empty.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_chain_tp_delete_empty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_chain_tp_delete_empty",
      "external": false,
      "loc": "net/sched/cls_api.c:1940",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595080272,
      "name": "tcf_chain_tp_delete_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071597786937,
      "name": "tcf_chain_tp_delete_empty.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_chain_tp_delete_empty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502485312,
      "name": "tcf_chain_tp_delete_empty",
      "external": false,
      "loc": "net/sched/cls_api.c:1707",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502485312,
      "name": "tcf_chain_tp_delete_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_chain_tp_delete_empty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235200732,
      "name": "tcf_chain_tp_delete_empty",
      "external": false,
      "loc": "net/sched/cls_api.c:1707",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235200732,
      "name": "tcf_chain_tp_delete_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_chain_tp_delete_empty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296049456,
      "name": "tcf_chain_tp_delete_empty",
      "external": false,
      "loc": "net/sched/cls_api.c:1707",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296049456,
      "name": "tcf_chain_tp_delete_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_chain_tp_delete_empty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278665482,
      "name": "tcf_chain_tp_delete_empty",
      "external": false,
      "loc": "net/sched/cls_api.c:1707",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278665482,
      "name": "tcf_chain_tp_delete_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_chain_tp_delete_empty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588500336,
      "name": "tcf_chain_tp_delete_empty",
      "external": false,
      "loc": "net/sched/cls_api.c:1707",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588500336,
      "name": "tcf_chain_tp_delete_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_chain_tp_delete_empty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588212336,
      "name": "tcf_chain_tp_delete_empty",
      "external": false,
      "loc": "net/sched/cls_api.c:1707",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588212336,
      "name": "tcf_chain_tp_delete_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_chain_tp_delete_empty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588832512,
      "name": "tcf_chain_tp_delete_empty",
      "external": false,
      "loc": "net/sched/cls_api.c:1707",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588832512,
      "name": "tcf_chain_tp_delete_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_chain_tp_delete_empty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588975872,
      "name": "tcf_chain_tp_delete_empty",
      "external": false,
      "loc": "net/sched/cls_api.c:1707",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588975872,
      "name": "tcf_chain_tp_delete_empty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void tcf_chain_tp_delete_empty(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```
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
