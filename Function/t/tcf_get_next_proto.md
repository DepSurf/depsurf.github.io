# Function: <code>tcf_get_next_proto</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held)
```

```json
{
  "name": "tcf_get_next_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588678895,
      "name": "tcf_get_next_proto",
      "external": true,
      "loc": "net/sched/cls_api.c:1115",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_tclass",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588670672,
      "name": "tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held)
```

```json
{
  "name": "tcf_get_next_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588904422,
      "name": "tcf_get_next_proto",
      "external": true,
      "loc": "net/sched/cls_api.c:1029",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588897072,
      "name": "tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held)
```

```json
{
  "name": "tcf_get_next_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589782640,
      "name": "tcf_get_next_proto",
      "external": true,
      "loc": "net/sched/cls_api.c:992",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589782640,
      "name": "tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "tcf_get_next_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589817472,
      "name": "tcf_get_next_proto",
      "external": true,
      "loc": "net/sched/cls_api.c:994",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589817472,
      "name": "tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "tcf_get_next_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589721776,
      "name": "tcf_get_next_proto",
      "external": true,
      "loc": "net/sched/cls_api.c:994",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589721776,
      "name": "tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "tcf_get_next_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590480064,
      "name": "tcf_get_next_proto",
      "external": true,
      "loc": "net/sched/cls_api.c:995",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590480064,
      "name": "tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "tcf_get_next_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592082320,
      "name": "tcf_get_next_proto",
      "external": true,
      "loc": "net/sched/cls_api.c:1012",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592082320,
      "name": "tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "tcf_get_next_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593901680,
      "name": "tcf_get_next_proto",
      "external": true,
      "loc": "net/sched/cls_api.c:1014",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593901680,
      "name": "tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "tcf_get_next_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594280560,
      "name": "tcf_get_next_proto",
      "external": true,
      "loc": "net/sched/cls_api.c:1119",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594280560,
      "name": "tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "tcf_get_next_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595079488,
      "name": "tcf_get_next_proto",
      "external": true,
      "loc": "net/sched/cls_api.c:1121",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595079488,
      "name": "tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held)
```

```json
{
  "name": "tcf_get_next_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502487456,
      "name": "tcf_get_next_proto",
      "external": true,
      "loc": "net/sched/cls_api.c:1029",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502487456,
      "name": "tcf_get_next_proto",
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
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held)
```

```json
{
  "name": "tcf_get_next_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235211032,
      "name": "tcf_get_next_proto",
      "external": true,
      "loc": "net/sched/cls_api.c:1029",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235200484,
      "name": "tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held)
```

```json
{
  "name": "tcf_get_next_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296049888,
      "name": "tcf_get_next_proto",
      "external": true,
      "loc": "net/sched/cls_api.c:1029",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296049888,
      "name": "tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held)
```

```json
{
  "name": "tcf_get_next_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278665726,
      "name": "tcf_get_next_proto",
      "external": true,
      "loc": "net/sched/cls_api.c:1029",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278665726,
      "name": "tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held)
```

```json
{
  "name": "tcf_get_next_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588510806,
      "name": "tcf_get_next_proto",
      "external": true,
      "loc": "net/sched/cls_api.c:1029",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588503456,
      "name": "tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held)
```

```json
{
  "name": "tcf_get_next_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588222806,
      "name": "tcf_get_next_proto",
      "external": true,
      "loc": "net/sched/cls_api.c:1029",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588215456,
      "name": "tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held)
```

```json
{
  "name": "tcf_get_next_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588842982,
      "name": "tcf_get_next_proto",
      "external": true,
      "loc": "net/sched/cls_api.c:1029",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588835632,
      "name": "tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held)
```

```json
{
  "name": "tcf_get_next_proto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588987110,
      "name": "tcf_get_next_proto",
      "external": true,
      "loc": "net/sched/cls_api.c:1029",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588976112,
      "name": "tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct tcf_proto * tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp, bool rtnl_held)
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool rtnl_held</code>
</li>
</ul>
</details>
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
