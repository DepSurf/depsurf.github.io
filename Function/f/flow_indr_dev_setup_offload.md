# Function: <code>flow_indr_dev_setup_offload</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int flow_indr_dev_setup_offload(struct net_device * dev, enum tc_setup_type type, void * data, struct flow_block_offload * bo, void (*)(struct flow_block_cb *) cleanup)
```

```json
{
  "name": "flow_indr_dev_setup_offload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589554752,
      "name": "flow_indr_dev_setup_offload",
      "external": true,
      "loc": "net/core/flow_offload.c:466",
      "file": "net/core/flow_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589554752,
      "name": "flow_indr_dev_setup_offload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int flow_indr_dev_setup_offload(struct net_device * dev, struct Qdisc * sch, enum tc_setup_type type, void * data, struct flow_block_offload * bo, void (*)(struct flow_block_cb *) cleanup)
```

```json
{
  "name": "flow_indr_dev_setup_offload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589563872,
      "name": "flow_indr_dev_setup_offload",
      "external": true,
      "loc": "net/core/flow_offload.c:466",
      "file": "net/core/flow_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589563872,
      "name": "flow_indr_dev_setup_offload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int flow_indr_dev_setup_offload(struct net_device * dev, struct Qdisc * sch, enum tc_setup_type type, void * data, struct flow_block_offload * bo, void (*)(struct flow_block_cb *) cleanup)
```

```json
{
  "name": "flow_indr_dev_setup_offload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589462160,
      "name": "flow_indr_dev_setup_offload",
      "external": true,
      "loc": "net/core/flow_offload.c:466",
      "file": "net/core/flow_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589462160,
      "name": "flow_indr_dev_setup_offload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int flow_indr_dev_setup_offload(struct net_device * dev, struct Qdisc * sch, enum tc_setup_type type, void * data, struct flow_block_offload * bo, void (*)(struct flow_block_cb *) cleanup)
```

```json
{
  "name": "flow_indr_dev_setup_offload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590201184,
      "name": "flow_indr_dev_setup_offload",
      "external": true,
      "loc": "net/core/flow_offload.c:546",
      "file": "net/core/flow_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590201184,
      "name": "flow_indr_dev_setup_offload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
int flow_indr_dev_setup_offload(struct net_device * dev, struct Qdisc * sch, enum tc_setup_type type, void * data, struct flow_block_offload * bo, void (*)(struct flow_block_cb *) cleanup)
```

```json
{
  "name": "flow_indr_dev_setup_offload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591767472,
      "name": "flow_indr_dev_setup_offload",
      "external": true,
      "loc": "net/core/flow_offload.c:570",
      "file": "net/core/flow_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_update_hw_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591767472,
      "name": "flow_indr_dev_setup_offload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
int flow_indr_dev_setup_offload(struct net_device * dev, struct Qdisc * sch, enum tc_setup_type type, void * data, struct flow_block_offload * bo, void (*)(struct flow_block_cb *) cleanup)
```

```json
{
  "name": "flow_indr_dev_setup_offload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593558944,
      "name": "flow_indr_dev_setup_offload",
      "external": true,
      "loc": "net/core/flow_offload.c:598",
      "file": "net/core/flow_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_update_hw_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593558944,
      "name": "flow_indr_dev_setup_offload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
int flow_indr_dev_setup_offload(struct net_device * dev, struct Qdisc * sch, enum tc_setup_type type, void * data, struct flow_block_offload * bo, void (*)(struct flow_block_cb *) cleanup)
```

```json
{
  "name": "flow_indr_dev_setup_offload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594028224,
      "name": "flow_indr_dev_setup_offload",
      "external": true,
      "loc": "net/core/flow_offload.c:598",
      "file": "net/core/flow_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_update_hw_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594028224,
      "name": "flow_indr_dev_setup_offload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
int flow_indr_dev_setup_offload(struct net_device * dev, struct Qdisc * sch, enum tc_setup_type type, void * data, struct flow_block_offload * bo, void (*)(struct flow_block_cb *) cleanup)
```

```json
{
  "name": "flow_indr_dev_setup_offload",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594815216,
      "name": "flow_indr_dev_setup_offload",
      "external": true,
      "loc": "net/core/flow_offload.c:605",
      "file": "net/core/flow_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_update_hw_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594815216,
      "name": "flow_indr_dev_setup_offload",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int flow_indr_dev_setup_offload(struct net_device * dev, enum tc_setup_type type, void * data, struct flow_block_offload * bo, void (*)(struct flow_block_cb *) cleanup)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct Qdisc * sch</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, type, data, bo, cleanup</code> ➡️ <code>dev, sch, type, data, bo, cleanup</code>
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
