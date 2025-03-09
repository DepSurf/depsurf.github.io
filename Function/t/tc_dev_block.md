# Function: <code>tc_dev_block</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tcf_block * tc_dev_block(struct net_device * dev, bool ingress)
```

```json
{
  "name": "tc_dev_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588886240,
      "name": "tc_dev_block",
      "external": false,
      "loc": "net/sched/cls_api.c:634",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_indr_block_get_and_cmd",
        "net/sched/cls_api.c:tc_indr_block_get_and_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588886240,
      "name": "tc_dev_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct tcf_block * tc_dev_block(struct net_device * dev, bool ingress)
```

```json
{
  "name": "tc_dev_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502475528,
      "name": "tc_dev_block",
      "external": false,
      "loc": "net/sched/cls_api.c:634",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_indr_block_get_and_cmd",
        "net/sched/cls_api.c:tc_indr_block_get_and_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502475528,
      "name": "tc_dev_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
struct tcf_block * tc_dev_block(struct net_device * dev, bool ingress)
```

```json
{
  "name": "tc_dev_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235190516,
      "name": "tc_dev_block",
      "external": false,
      "loc": "net/sched/cls_api.c:634",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_indr_block_get_and_cmd",
        "net/sched/cls_api.c:tc_indr_block_get_and_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235190516,
      "name": "tc_dev_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
struct tcf_block * tc_dev_block(struct net_device * dev, bool ingress)
```

```json
{
  "name": "tc_dev_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296033680,
      "name": "tc_dev_block",
      "external": false,
      "loc": "net/sched/cls_api.c:634",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_indr_block_get_and_cmd",
        "net/sched/cls_api.c:tc_indr_block_get_and_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296033680,
      "name": "tc_dev_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct tcf_block * tc_dev_block(struct net_device * dev, bool ingress)
```

```json
{
  "name": "tc_dev_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278656580,
      "name": "tc_dev_block",
      "external": false,
      "loc": "net/sched/cls_api.c:634",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_indr_block_get_and_cmd",
        "net/sched/cls_api.c:tc_indr_block_get_and_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278656580,
      "name": "tc_dev_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct tcf_block * tc_dev_block(struct net_device * dev, bool ingress)
```

```json
{
  "name": "tc_dev_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588492624,
      "name": "tc_dev_block",
      "external": false,
      "loc": "net/sched/cls_api.c:634",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_indr_block_get_and_cmd",
        "net/sched/cls_api.c:tc_indr_block_get_and_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588492624,
      "name": "tc_dev_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
struct tcf_block * tc_dev_block(struct net_device * dev, bool ingress)
```

```json
{
  "name": "tc_dev_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588204624,
      "name": "tc_dev_block",
      "external": false,
      "loc": "net/sched/cls_api.c:634",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_indr_block_get_and_cmd",
        "net/sched/cls_api.c:tc_indr_block_get_and_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588204624,
      "name": "tc_dev_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
struct tcf_block * tc_dev_block(struct net_device * dev, bool ingress)
```

```json
{
  "name": "tc_dev_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588824800,
      "name": "tc_dev_block",
      "external": false,
      "loc": "net/sched/cls_api.c:634",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_indr_block_get_and_cmd",
        "net/sched/cls_api.c:tc_indr_block_get_and_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588824800,
      "name": "tc_dev_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
struct tcf_block * tc_dev_block(struct net_device * dev, bool ingress)
```

```json
{
  "name": "tc_dev_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588965712,
      "name": "tc_dev_block",
      "external": false,
      "loc": "net/sched/cls_api.c:634",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_indr_block_get_and_cmd",
        "net/sched/cls_api.c:tc_indr_block_get_and_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588965712,
      "name": "tc_dev_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct tcf_block * tc_dev_block(struct net_device * dev, bool ingress)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct tcf_block * tc_dev_block(struct net_device * dev, bool ingress)
```
</details>
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
