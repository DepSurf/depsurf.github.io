# Function: <code>tcf_chain_tp_find</code>

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
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587244444,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:391",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_tfilter"
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
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587761266,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:568",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_tfilter"
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
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588100887,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:914",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588283685,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1360",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
```

```json
{
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588663280,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1803",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588663280,
      "name": "tcf_chain_tp_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
```

```json
{
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588885712,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1748",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588885712,
      "name": "tcf_chain_tp_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
```

```json
{
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589776608,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1761",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589776608,
      "name": "tcf_chain_tp_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
```

```json
{
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589811552,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1763",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589811552,
      "name": "tcf_chain_tp_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
```

```json
{
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589715120,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1764",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589715120,
      "name": "tcf_chain_tp_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
```

```json
{
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590473328,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1762",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590473328,
      "name": "tcf_chain_tp_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
```

```json
{
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592077392,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1781",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592077392,
      "name": "tcf_chain_tp_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
```

```json
{
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593897968,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1783",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593897968,
      "name": "tcf_chain_tp_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
```

```json
{
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594274224,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1931",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594274224,
      "name": "tcf_chain_tp_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
```

```json
{
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595072336,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1981",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595072336,
      "name": "tcf_chain_tp_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502478472,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1748",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502478472,
      "name": "tcf_chain_tp_find.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
```

```json
{
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235191644,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1748",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235191644,
      "name": "tcf_chain_tp_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296058164,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1748",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
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
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278670676,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1748",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
```

```json
{
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588492096,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1748",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588492096,
      "name": "tcf_chain_tp_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
```

```json
{
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588204096,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1748",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588204096,
      "name": "tcf_chain_tp_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
```

```json
{
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588824272,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1748",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588824272,
      "name": "tcf_chain_tp_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
```

```json
{
  "name": "tcf_chain_tp_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588964880,
      "name": "tcf_chain_tp_find",
      "external": false,
      "loc": "net/sched/cls_api.c:1748",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588964880,
      "name": "tcf_chain_tp_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct tcf_proto * tcf_chain_tp_find(struct tcf_chain * chain, struct tcf_chain_info * chain_info, u32 protocol, u32 prio, bool prio_allocate)
```
</details>
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
