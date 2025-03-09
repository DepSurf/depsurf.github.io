# Function: <code>qdisc_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int qdisc_notify(struct net * net, struct sk_buff * oskb, struct nlmsghdr * n, u32 clid, struct Qdisc * old, struct Qdisc * new)
```

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586463968,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:1399",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:notify_and_destroy",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586463968,
      "name": "qdisc_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int qdisc_notify(struct net * net, struct sk_buff * oskb, struct nlmsghdr * n, u32 clid, struct Qdisc * old, struct Qdisc * new)
```

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586910464,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:1401",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:notify_and_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586910464,
      "name": "qdisc_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int qdisc_notify(struct net * net, struct sk_buff * oskb, struct nlmsghdr * n, u32 clid, struct Qdisc * old, struct Qdisc * new)
```

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587104896,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:1419",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:notify_and_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587104896,
      "name": "qdisc_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int qdisc_notify(struct net * net, struct sk_buff * oskb, struct nlmsghdr * n, u32 clid, struct Qdisc * old, struct Qdisc * new)
```

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587233120,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:1425",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:notify_and_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587233120,
      "name": "qdisc_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
int qdisc_notify(struct net * net, struct sk_buff * oskb, struct nlmsghdr * n, u32 clid, struct Qdisc * old, struct Qdisc * new)
```

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587748608,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:848",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:notify_and_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587748608,
      "name": "qdisc_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588086624,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:878",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:notify_and_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588086624,
      "name": "qdisc_notify.isra.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588263344,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:965",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:notify_and_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588263344,
      "name": "qdisc_notify.isra.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588655120,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:956",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:notify_and_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588655120,
      "name": "qdisc_notify.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588877504,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:956",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:notify_and_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588877504,
      "name": "qdisc_notify.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589762256,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:965",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589762256,
      "name": "qdisc_notify.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589796880,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:967",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589796880,
      "name": "qdisc_notify.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589701104,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:967",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589701104,
      "name": "qdisc_notify.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590459216,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:973",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590459216,
      "name": "qdisc_notify.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592059216,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:973",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592059216,
      "name": "qdisc_notify.isra.0",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593878720,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:992",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593878720,
      "name": "qdisc_notify.isra.0",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594257136,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:1006",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594257136,
      "name": "qdisc_notify.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595054496,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:1032",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595054496,
      "name": "qdisc_notify.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502466872,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:956",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:notify_and_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502466872,
      "name": "qdisc_notify.isra.0",
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
int qdisc_notify(struct net * net, struct sk_buff * oskb, struct nlmsghdr * n, u32 clid, struct Qdisc * old, struct Qdisc * new)
```

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235181660,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:956",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:notify_and_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235181660,
      "name": "qdisc_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296021408,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:956",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:notify_and_destroy",
        "net/sched/sch_api.c:notify_and_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296021408,
      "name": "qdisc_notify.isra.0",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278650040,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:956",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:notify_and_destroy",
        "net/sched/sch_api.c:notify_and_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278650040,
      "name": "qdisc_notify.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588483888,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:956",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:notify_and_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588483888,
      "name": "qdisc_notify.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588195888,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:956",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:notify_and_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588195888,
      "name": "qdisc_notify.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588816064,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:956",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:notify_and_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588816064,
      "name": "qdisc_notify.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "qdisc_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588956672,
      "name": "qdisc_notify",
      "external": false,
      "loc": "net/sched/sch_api.c:956",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:notify_and_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588956672,
      "name": "qdisc_notify.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int qdisc_notify(struct net * net, struct sk_buff * oskb, struct nlmsghdr * n, u32 clid, struct Qdisc * old, struct Qdisc * new)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int qdisc_notify(struct net * net, struct sk_buff * oskb, struct nlmsghdr * n, u32 clid, struct Qdisc * old, struct Qdisc * new)
```
</details>
</li>
</ul>
