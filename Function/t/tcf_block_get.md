# Function: <code>tcf_block_get</code>

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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587241824,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:264",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587241824,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587758736,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:323",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587758736,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588105760,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:647",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588105760,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588280208,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1102",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588280208,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1480",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588687106,
      "name": "tcf_block_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071588675568,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588901088,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1394",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588901088,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589786720,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1357",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589786720,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589822032,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1358",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589822032,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589739136,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1358",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589739136,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590497792,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1359",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590497792,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592087632,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1376",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592087632,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593906336,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1378",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593906336,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594286160,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1483",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594286160,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595085504,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1503",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595085504,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502493664,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1394",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502493664,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235204464,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1394",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235204464,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296054944,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1394",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296054944,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278668844,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1394",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278668844,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588507472,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1394",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588507472,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588219472,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1394",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588219472,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588839648,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1394",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588839648,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain, struct Qdisc * q, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588979536,
      "name": "tcf_block_get",
      "external": true,
      "loc": "net/sched/cls_api.c:1394",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588979536,
      "name": "tcf_block_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int tcf_block_get(struct tcf_block * * p_block, struct tcf_proto * * p_filter_chain)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct Qdisc * q</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack * extack</code>
</li>
</ul>
</details>
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
