# Function: <code>tc_dump_qdisc_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586463296,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1430",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586463296,
      "name": "tc_dump_qdisc_root.isra.26",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586909776,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1432",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586909776,
      "name": "tc_dump_qdisc_root.isra.26",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587104144,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1450",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587104144,
      "name": "tc_dump_qdisc_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587232256,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1456",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587232256,
      "name": "tc_dump_qdisc_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587747744,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1433",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587747744,
      "name": "tc_dump_qdisc_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588085744,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1571",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588085744,
      "name": "tc_dump_qdisc_root",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588262448,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1667",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588262448,
      "name": "tc_dump_qdisc_root",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588654176,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1673",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588654176,
      "name": "tc_dump_qdisc_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588876560,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1673",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588876560,
      "name": "tc_dump_qdisc_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589761312,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1683",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589761312,
      "name": "tc_dump_qdisc_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589795936,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1684",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589795936,
      "name": "tc_dump_qdisc_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589700128,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1684",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589700128,
      "name": "tc_dump_qdisc_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590458192,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1690",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590458192,
      "name": "tc_dump_qdisc_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592058672,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1681",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592058672,
      "name": "tc_dump_qdisc_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593878160,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1699",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593878160,
      "name": "tc_dump_qdisc_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594255952,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1768",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594255952,
      "name": "tc_dump_qdisc_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
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
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595053312,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1797",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595053312,
      "name": "tc_dump_qdisc_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
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
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502465952,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1673",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502465952,
      "name": "tc_dump_qdisc_root.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235180732,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1673",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235180732,
      "name": "tc_dump_qdisc_root",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296020176,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1673",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296020176,
      "name": "tc_dump_qdisc_root.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278649346,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1673",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278649346,
      "name": "tc_dump_qdisc_root.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588482944,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1673",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588482944,
      "name": "tc_dump_qdisc_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588194944,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1673",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588194944,
      "name": "tc_dump_qdisc_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588815120,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1673",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588815120,
      "name": "tc_dump_qdisc_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```

```json
{
  "name": "tc_dump_qdisc_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588955728,
      "name": "tc_dump_qdisc_root",
      "external": false,
      "loc": "net/sched/sch_api.c:1673",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_dump_qdisc",
        "net/sched/sch_api.c:tc_dump_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588955728,
      "name": "tc_dump_qdisc_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool dump_invisible</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
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
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int tc_dump_qdisc_root(struct Qdisc * root, struct sk_buff * skb, struct netlink_callback * cb, int * q_idx_p, int s_q_idx, bool recur, bool dump_invisible)
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
