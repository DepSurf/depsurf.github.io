# Function: <code>__tcf_chain_put</code>

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
void __tcf_chain_put(struct tcf_chain * chain, bool by_act)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588277728,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:323",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:tcf_chain_flush",
        "net/sched/cls_api.c:tcf_chain_put_by_act"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588277728,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
void __tcf_chain_put(struct tcf_chain * chain, bool by_act, bool explicitly_created)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588669472,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:466",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_chain_put_by_act",
        "net/sched/cls_api.c:tcf_proto_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588669472,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
void __tcf_chain_put(struct tcf_chain * chain, bool by_act, bool explicitly_created)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588892912,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:518",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_chain_put_by_act",
        "net/sched/cls_api.c:tcf_proto_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588892912,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
void __tcf_chain_put(struct tcf_chain * chain, bool by_act, bool explicitly_created)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589781024,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:533",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:tcf_chain0_head_change_cb_add",
        "net/sched/cls_api.c:tcf_chain_put_by_act",
        "net/sched/cls_api.c:tcf_proto_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589781024,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
void __tcf_chain_put(struct tcf_chain * chain, bool by_act, bool explicitly_created)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589816304,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:533",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:tcf_chain0_head_change_cb_add",
        "net/sched/cls_api.c:tcf_chain_put_by_act",
        "net/sched/cls_api.c:tcf_proto_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589816304,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
void __tcf_chain_put(struct tcf_chain * chain, bool by_act, bool explicitly_created)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589717744,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:533",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:tcf_chain_put_by_act",
        "net/sched/cls_api.c:tcf_proto_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589717744,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __tcf_chain_put(struct tcf_chain * chain, bool by_act, bool explicitly_created)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:533",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:tcf_chain_put_by_act",
        "net/sched/cls_api.c:tcf_proto_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590475968,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
    },
    {
      "addr": 18446744071592710463,
      "name": "__tcf_chain_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __tcf_chain_put(struct tcf_chain * chain, bool by_act, bool explicitly_created)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:550",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:tcf_chain_put_by_act",
        "net/sched/cls_api.c:tcf_proto_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592081168,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
    },
    {
      "addr": 18446744071594596734,
      "name": "__tcf_chain_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __tcf_chain_put(struct tcf_chain * chain, bool by_act, bool explicitly_created)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:552",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:tcf_chain_put_by_act",
        "net/sched/cls_api.c:tcf_proto_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593900432,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
    },
    {
      "addr": 18446744071596332936,
      "name": "__tcf_chain_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __tcf_chain_put(struct tcf_chain * chain, bool by_act, bool explicitly_created)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:655",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:tcf_chain_put_by_act",
        "net/sched/cls_api.c:tcf_proto_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594279088,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
    },
    {
      "addr": 18446744071596861779,
      "name": "__tcf_chain_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __tcf_chain_put(struct tcf_chain * chain, bool by_act, bool explicitly_created)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:656",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:tcf_chain_put_by_act",
        "net/sched/cls_api.c:tcf_proto_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595077904,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
    },
    {
      "addr": 18446744071597786865,
      "name": "__tcf_chain_put.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void __tcf_chain_put(struct tcf_chain * chain, bool by_act, bool explicitly_created)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502484192,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:518",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_chain_put_by_act",
        "net/sched/cls_api.c:tcf_proto_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502484192,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
void __tcf_chain_put(struct tcf_chain * chain, bool by_act, bool explicitly_created)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235199656,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:518",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_chain_put_by_act",
        "net/sched/cls_api.c:tcf_proto_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235199656,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
void __tcf_chain_put(struct tcf_chain * chain, bool by_act, bool explicitly_created)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296047872,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:518",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_chain_put_by_act",
        "net/sched/cls_api.c:tcf_proto_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296047872,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
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
void __tcf_chain_put(struct tcf_chain * chain, bool by_act, bool explicitly_created)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278664614,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:518",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_chain_put_by_act",
        "net/sched/cls_api.c:tcf_proto_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278664614,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void __tcf_chain_put(struct tcf_chain * chain, bool by_act, bool explicitly_created)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588499296,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:518",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_chain_put_by_act",
        "net/sched/cls_api.c:tcf_proto_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588499296,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
void __tcf_chain_put(struct tcf_chain * chain, bool by_act, bool explicitly_created)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588211296,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:518",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_chain_put_by_act",
        "net/sched/cls_api.c:tcf_proto_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588211296,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
void __tcf_chain_put(struct tcf_chain * chain, bool by_act, bool explicitly_created)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588831472,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:518",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_chain_put_by_act",
        "net/sched/cls_api.c:tcf_proto_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588831472,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
void __tcf_chain_put(struct tcf_chain * chain, bool by_act, bool explicitly_created)
```

```json
{
  "name": "__tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588974832,
      "name": "__tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:518",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_chain_put_by_act",
        "net/sched/cls_api.c:tcf_proto_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588974832,
      "name": "__tcf_chain_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
void __tcf_chain_put(struct tcf_chain * chain, bool by_act)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool explicitly_created</code>
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
