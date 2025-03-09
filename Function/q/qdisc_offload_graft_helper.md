# Function: <code>qdisc_offload_graft_helper</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588258384,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:832",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588258384,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588649712,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:823",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588649712,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588872080,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:823",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588872080,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589754288,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:832",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589754288,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589788880,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:834",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589788880,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589693472,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:834",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589693472,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590451248,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:840",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590451248,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592053184,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:841",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592053184,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593871856,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:843",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593871856,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594246816,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:851",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594246816,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595044112,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:851",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595044112,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502460160,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:823",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502460160,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235176108,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:823",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235176108,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296014928,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:823",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296014928,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278645530,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:823",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278645530,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588478464,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:823",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588478464,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588190464,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:823",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588190464,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588810640,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:823",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588810640,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
```

```json
{
  "name": "qdisc_offload_graft_helper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588951312,
      "name": "qdisc_offload_graft_helper",
      "external": true,
      "loc": "net/sched/sch_api.c:823",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_mq.c:mq_graft",
        "net/sched/sch_api.c:qdisc_graft",
        "net/sched/sch_api.c:qdisc_graft"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588951312,
      "name": "qdisc_offload_graft_helper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void qdisc_offload_graft_helper(struct net_device * dev, struct Qdisc * sch, struct Qdisc * new, struct Qdisc * old, enum tc_setup_type type, void * type_data, struct netlink_ext_ack * extack)
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
