# Function: <code>__tcf_block_put</code>

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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588278928,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:827",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_block_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588278928,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei, bool rtnl_held)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588674208,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:1278",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_block_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588674208,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei, bool rtnl_held)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588899584,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:1192",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_block_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588899584,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei, bool rtnl_held)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589785696,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:1155",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589785696,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei, bool rtnl_held)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589820992,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:1156",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589820992,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei, bool rtnl_held)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589727184,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:1156",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589727184,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei, bool rtnl_held)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590485568,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:1157",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590485568,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei, bool rtnl_held)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592086032,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:1174",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592086032,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei, bool rtnl_held)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593904704,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:1176",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593904704,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei, bool rtnl_held)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594284528,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:1281",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_put",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594284528,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei, bool rtnl_held)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595083584,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:1283",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_put_ext",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595083584,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei, bool rtnl_held)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502492080,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:1192",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_block_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502492080,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei, bool rtnl_held)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235202996,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:1192",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_block_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235202996,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei, bool rtnl_held)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296052880,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:1192",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_block_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296052880,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei, bool rtnl_held)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278667442,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:1192",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_block_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278667442,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei, bool rtnl_held)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588505968,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:1192",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_block_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588505968,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei, bool rtnl_held)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588217968,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:1192",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_block_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588217968,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei, bool rtnl_held)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588838144,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:1192",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_block_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588838144,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei, bool rtnl_held)
```

```json
{
  "name": "__tcf_block_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588978000,
      "name": "__tcf_block_put",
      "external": false,
      "loc": "net/sched/cls_api.c:1192",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_dump_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_block_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588978000,
      "name": "__tcf_block_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
void __tcf_block_put(struct tcf_block * block, struct Qdisc * q, struct tcf_block_ext_info * ei)
```
</details>
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
