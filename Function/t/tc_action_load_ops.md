# Function: <code>tc_action_load_ops</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tc_action_ops * tc_action_load_ops(char * name, struct nlattr * nla, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tc_action_load_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589840672,
      "name": "tc_action_load_ops",
      "external": true,
      "loc": "net/sched/act_api.c:931",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_exts_validate",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589840672,
      "name": "tc_action_load_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
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
struct tc_action_ops * tc_action_load_ops(char * name, struct nlattr * nla, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tc_action_load_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589745584,
      "name": "tc_action_load_ops",
      "external": true,
      "loc": "net/sched/act_api.c:944",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_exts_validate",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589745584,
      "name": "tc_action_load_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
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
struct tc_action_ops * tc_action_load_ops(struct nlattr * nla, bool police, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tc_action_load_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590504048,
      "name": "tc_action_load_ops",
      "external": true,
      "loc": "net/sched/act_api.c:953",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_exts_validate",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590504048,
      "name": "tc_action_load_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
struct tc_action_ops * tc_action_load_ops(struct nlattr * nla, bool police, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tc_action_load_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592108192,
      "name": "tc_action_load_ops",
      "external": true,
      "loc": "net/sched/act_api.c:1276",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_exts_validate_ex",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592108192,
      "name": "tc_action_load_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
struct tc_action_ops * tc_action_load_ops(struct nlattr * nla, bool police, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tc_action_load_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593928048,
      "name": "tc_action_load_ops",
      "external": true,
      "loc": "net/sched/act_api.c:1302",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_exts_validate_ex",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593928048,
      "name": "tc_action_load_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
struct tc_action_ops * tc_action_load_ops(struct nlattr * nla, bool police, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tc_action_load_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594305024,
      "name": "tc_action_load_ops",
      "external": true,
      "loc": "net/sched/act_api.c:1297",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_exts_validate_ex",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594305024,
      "name": "tc_action_load_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
struct tc_action_ops * tc_action_load_ops(struct nlattr * nla, u32 flags, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tc_action_load_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595104096,
      "name": "tc_action_load_ops",
      "external": true,
      "loc": "net/sched/act_api.c:1327",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_exts_validate_ex",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595104096,
      "name": "tc_action_load_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct tc_action_ops * tc_action_load_ops(char * name, struct nlattr * nla, bool rtnl_held, struct netlink_ext_ack * extack)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool police</code>
</li>
<li>
<b>Param removed. </b>
<code>char * name</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, nla, rtnl_held, extack</code> ➡️ <code>nla, police, rtnl_held, extack</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool police</code>
</li>
<li>
<b>Param removed. </b>
<code>bool rtnl_held</code>
</li>
<li>
<b>Param reordered. </b>
<code>nla, police, rtnl_held, extack</code> ➡️ <code>nla, flags, extack</code>
</li>
</ul>
</details>
</li>
</ul>
