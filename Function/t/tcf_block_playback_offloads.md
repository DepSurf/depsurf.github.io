# Function: <code>tcf_block_playback_offloads</code>

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
int tcf_block_playback_offloads(struct tcf_block * block, tc_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588271600,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1180",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:__tcf_block_cb_unregister",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588271600,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
int tcf_block_playback_offloads(struct tcf_block * block, flow_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588670736,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1521",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588670736,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int tcf_block_playback_offloads(struct tcf_block * block, flow_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588897136,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1435",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588897136,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int tcf_block_playback_offloads(struct tcf_block * block, flow_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589783952,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1398",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_unbind",
        "net/sched/cls_api.c:tcf_block_bind",
        "net/sched/cls_api.c:tcf_block_bind",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589783952,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int tcf_block_playback_offloads(struct tcf_block * block, flow_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589819248,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1399",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_unbind",
        "net/sched/cls_api.c:tcf_block_bind",
        "net/sched/cls_api.c:tcf_block_bind",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589819248,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int tcf_block_playback_offloads(struct tcf_block * block, flow_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589722480,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1399",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_unbind",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589722480,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
int tcf_block_playback_offloads(struct tcf_block * block, flow_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590480768,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1400",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_unbind",
        "net/sched/cls_api.c:tcf_block_bind",
        "net/sched/cls_api.c:tcf_block_bind",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590480768,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
int tcf_block_playback_offloads(struct tcf_block * block, flow_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592084032,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1417",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_unbind",
        "net/sched/cls_api.c:tcf_block_bind",
        "net/sched/cls_api.c:tcf_block_bind",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592084032,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int tcf_block_playback_offloads(struct tcf_block * block, flow_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593902576,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1419",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_unbind",
        "net/sched/cls_api.c:tcf_block_bind",
        "net/sched/cls_api.c:tcf_block_bind",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593902576,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int tcf_block_playback_offloads(struct tcf_block * block, flow_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594282368,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1524",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_unbind",
        "net/sched/cls_api.c:tcf_block_bind",
        "net/sched/cls_api.c:tcf_block_bind",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594282368,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int tcf_block_playback_offloads(struct tcf_block * block, flow_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595081296,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1548",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_unbind",
        "net/sched/cls_api.c:tcf_block_bind",
        "net/sched/cls_api.c:tcf_block_bind",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595081296,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
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
int tcf_block_playback_offloads(struct tcf_block * block, flow_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502487552,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1435",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502487552,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int tcf_block_playback_offloads(struct tcf_block * block, flow_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235201004,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1435",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235201004,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int tcf_block_playback_offloads(struct tcf_block * block, flow_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296050000,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1435",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296050000,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
int tcf_block_playback_offloads(struct tcf_block * block, flow_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278665838,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1435",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278665838,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
int tcf_block_playback_offloads(struct tcf_block * block, flow_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588503520,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1435",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588503520,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int tcf_block_playback_offloads(struct tcf_block * block, flow_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588215520,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1435",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588215520,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int tcf_block_playback_offloads(struct tcf_block * block, flow_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588835696,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1435",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588835696,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int tcf_block_playback_offloads(struct tcf_block * block, flow_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_block_playback_offloads",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588976176,
      "name": "tcf_block_playback_offloads",
      "external": false,
      "loc": "net/sched/cls_api.c:1435",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588976176,
      "name": "tcf_block_playback_offloads",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int tcf_block_playback_offloads(struct tcf_block * block, tc_setup_cb_t * cb, void * cb_priv, bool add, bool offload_in_use, struct netlink_ext_ack * extack)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>tc_setup_cb_t * cb</code> ➡️ <code>flow_setup_cb_t * cb</code>
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
