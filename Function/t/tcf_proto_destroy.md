# Function: <code>tcf_proto_destroy</code>

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
void tcf_proto_destroy(struct tcf_proto * tp)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587240064,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:182",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/cls_api.c:tcf_chain_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587240064,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void tcf_proto_destroy(struct tcf_proto * tp)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587755744,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:175",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/cls_api.c:tcf_chain_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587755744,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void tcf_proto_destroy(struct tcf_proto * tp, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588095280,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:176",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588095280,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void tcf_proto_destroy(struct tcf_proto * tp, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588272832,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:188",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588272832,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void tcf_proto_destroy(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588670080,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:223",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_proto_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588670080,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void tcf_proto_destroy(struct tcf_proto * tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588893536,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:293",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588893536,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void tcf_proto_destroy(struct tcf_proto * tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589781936,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:294",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:tcf_proto_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589781936,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void tcf_proto_destroy(struct tcf_proto * tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589817216,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:294",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:tcf_proto_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589817216,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void tcf_proto_destroy(struct tcf_proto * tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589718352,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:294",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:tcf_proto_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589718352,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void tcf_proto_destroy(struct tcf_proto * tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590476576,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:294",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:tcf_proto_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590476576,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void tcf_proto_destroy(struct tcf_proto * tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592081808,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:311",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592081808,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void tcf_proto_destroy(struct tcf_proto * tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593901120,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:313",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593901120,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void tcf_proto_destroy(struct tcf_proto * tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594280000,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:415",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594280000,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void tcf_proto_destroy(struct tcf_proto * tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595078928,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:415",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique",
        "net/sched/cls_api.c:tcf_chain_tp_insert_unique"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595078928,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void tcf_proto_destroy(struct tcf_proto * tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502484808,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:293",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_proto_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502484808,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void tcf_proto_destroy(struct tcf_proto * tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235200240,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:293",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_proto_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235200240,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void tcf_proto_destroy(struct tcf_proto * tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296048848,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:293",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_proto_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296048848,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void tcf_proto_destroy(struct tcf_proto * tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278665118,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:293",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_tp_delete_empty",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_chain_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278665118,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void tcf_proto_destroy(struct tcf_proto * tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588499920,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:293",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588499920,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void tcf_proto_destroy(struct tcf_proto * tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588211920,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:293",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588211920,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void tcf_proto_destroy(struct tcf_proto * tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588832096,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:293",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588832096,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void tcf_proto_destroy(struct tcf_proto * tp, bool rtnl_held, bool sig_destroy, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588975456,
      "name": "tcf_proto_destroy",
      "external": false,
      "loc": "net/sched/cls_api.c:293",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588975456,
      "name": "tcf_proto_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void tcf_proto_destroy(struct tcf_proto * tp)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool rtnl_held</code>
</li>
<li>
<b>Param reordered. </b>
<code>tp, extack</code> ➡️ <code>tp, rtnl_held, extack</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool sig_destroy</code>
</li>
<li>
<b>Param reordered. </b>
<code>tp, rtnl_held, extack</code> ➡️ <code>tp, rtnl_held, sig_destroy, extack</code>
</li>
</ul>
</details>
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
