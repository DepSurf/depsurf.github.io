# Function: <code>tcf_proto_put</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588670176,
      "name": "tcf_proto_put",
      "external": false,
      "loc": "net/sched/cls_api.c:232",
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
        "net/sched/cls_api.c:tcf_chain_tp_delete_empty",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_chain_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588670176,
      "name": "tcf_proto_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588893712,
      "name": "tcf_proto_put",
      "external": false,
      "loc": "net/sched/cls_api.c:304",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
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
      "addr": 18446744071588893712,
      "name": "tcf_proto_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589782560,
      "name": "tcf_proto_put",
      "external": false,
      "loc": "net/sched/cls_api.c:305",
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
        "net/sched/cls_api.c:tcf_chain_tp_delete_empty",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_chain_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589782560,
      "name": "tcf_proto_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589817392,
      "name": "tcf_proto_put",
      "external": false,
      "loc": "net/sched/cls_api.c:305",
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
        "net/sched/cls_api.c:tcf_chain_tp_delete_empty",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_chain_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589817392,
      "name": "tcf_proto_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589718528,
      "name": "tcf_proto_put",
      "external": false,
      "loc": "net/sched/cls_api.c:305",
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
        "net/sched/cls_api.c:tcf_chain_tp_delete_empty",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_chain_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589718528,
      "name": "tcf_proto_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590476752,
      "name": "tcf_proto_put",
      "external": false,
      "loc": "net/sched/cls_api.c:305",
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
        "net/sched/cls_api.c:tcf_chain_tp_delete_empty",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_chain_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590476752,
      "name": "tcf_proto_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592082000,
      "name": "tcf_proto_put",
      "external": false,
      "loc": "net/sched/cls_api.c:322",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
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
      "addr": 18446744071592082000,
      "name": "tcf_proto_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593901328,
      "name": "tcf_proto_put",
      "external": false,
      "loc": "net/sched/cls_api.c:324",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
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
      "addr": 18446744071593901328,
      "name": "tcf_proto_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594280208,
      "name": "tcf_proto_put",
      "external": false,
      "loc": "net/sched/cls_api.c:426",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
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
      "addr": 18446744071594280208,
      "name": "tcf_proto_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595079136,
      "name": "tcf_proto_put",
      "external": false,
      "loc": "net/sched/cls_api.c:426",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
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
      "addr": 18446744071595079136,
      "name": "tcf_proto_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502485000,
      "name": "tcf_proto_put",
      "external": false,
      "loc": "net/sched/cls_api.c:304",
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
        "net/sched/cls_api.c:tcf_chain_tp_delete_empty",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_chain_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502485000,
      "name": "tcf_proto_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235200412,
      "name": "tcf_proto_put",
      "external": false,
      "loc": "net/sched/cls_api.c:304",
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
        "net/sched/cls_api.c:tcf_chain_tp_delete_empty",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_chain_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235200412,
      "name": "tcf_proto_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296049088,
      "name": "tcf_proto_put",
      "external": false,
      "loc": "net/sched/cls_api.c:304",
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
        "net/sched/cls_api.c:tcf_chain_tp_delete_empty",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_chain_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296049088,
      "name": "tcf_proto_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
  "name": "tcf_proto_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278675336,
      "name": "tcf_proto_put",
      "external": false,
      "loc": "net/sched/cls_api.c:304",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_tp_delete_empty",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_chain_flush"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588500096,
      "name": "tcf_proto_put",
      "external": false,
      "loc": "net/sched/cls_api.c:304",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
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
      "addr": 18446744071588500096,
      "name": "tcf_proto_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588212096,
      "name": "tcf_proto_put",
      "external": false,
      "loc": "net/sched/cls_api.c:304",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
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
      "addr": 18446744071588212096,
      "name": "tcf_proto_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588832272,
      "name": "tcf_proto_put",
      "external": false,
      "loc": "net/sched/cls_api.c:304",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
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
      "addr": 18446744071588832272,
      "name": "tcf_proto_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```

```json
{
  "name": "tcf_proto_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588975632,
      "name": "tcf_proto_put",
      "external": false,
      "loc": "net/sched/cls_api.c:304",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
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
      "addr": 18446744071588975632,
      "name": "tcf_proto_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void tcf_proto_put(struct tcf_proto * tp, bool rtnl_held, struct netlink_ext_ack * extack)
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
