# Function: <code>tcf_proto_create</code>

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
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587244596,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:130",
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
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587761444,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:123",
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
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588103452,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:125",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588286437,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:155",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588684204,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:180",
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
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588909937,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:250",
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
struct tcf_proto * tcf_proto_create(const char * kind, u32 protocol, u32 prio, struct tcf_chain * chain, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589774576,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:251",
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
      "addr": 18446744071589774576,
      "name": "tcf_proto_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
struct tcf_proto * tcf_proto_create(const char * kind, u32 protocol, u32 prio, struct tcf_chain * chain, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589810112,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:251",
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
      "addr": 18446744071589810112,
      "name": "tcf_proto_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589733844,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:251",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590492362,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:251",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592094819,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:268",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593919640,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:270",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594292604,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:372",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595091823,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:372",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502501540,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:250",
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
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235208996,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:250",
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
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296060080,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:250",
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
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278672674,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:250",
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
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588516321,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:250",
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
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588228321,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:250",
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
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588848497,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:250",
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
  "name": "tcf_proto_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588984544,
      "name": "tcf_proto_create",
      "external": false,
      "loc": "net/sched/cls_api.c:250",
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
struct tcf_proto * tcf_proto_create(const char * kind, u32 protocol, u32 prio, struct tcf_chain * chain, bool rtnl_held, struct netlink_ext_ack * extack)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct tcf_proto * tcf_proto_create(const char * kind, u32 protocol, u32 prio, struct tcf_chain * chain, bool rtnl_held, struct netlink_ext_ack * extack)
```
</details>
</li>
</ul>
