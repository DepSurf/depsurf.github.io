# Function: <code>tcf_chain_put</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcf_chain_put(struct tcf_chain * chain)
```

```json
{
  "name": "tcf_chain_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587245091,
      "name": "tcf_chain_put",
      "external": true,
      "loc": "net/sched/cls_api.c:247",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_tfilter"
      ],
      "caller_func": [
        "net/sched/act_api.c:free_tcf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587241936,
      "name": "tcf_chain_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcf_chain_put(struct tcf_chain * chain)
```

```json
{
  "name": "tcf_chain_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587761681,
      "name": "tcf_chain_put",
      "external": true,
      "loc": "net/sched/cls_api.c:249",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/cls_api.c:tcf_chain_tp_remove",
        "net/sched/cls_api.c:tcf_block_put_ext",
        "net/sched/cls_api.c:tcf_block_put_ext",
        "net/sched/cls_api.c:tcf_chain_flush"
      ],
      "caller_func": [
        "net/sched/act_api.c:free_tcf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587755456,
      "name": "tcf_chain_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcf_chain_put(struct tcf_chain * chain)
```

```json
{
  "name": "tcf_chain_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588100936,
      "name": "tcf_chain_put",
      "external": true,
      "loc": "net/sched/cls_api.c:265",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_chain_flush"
      ],
      "caller_func": [
        "net/sched/act_api.c:__tcf_idr_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588094976,
      "name": "tcf_chain_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588282543,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:339",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put",
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
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588678259,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:513",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_proto_destroy"
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
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588903763,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:565",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_proto_destroy"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589795210,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:580",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:tcf_chain0_head_change_cb_add",
        "net/sched/cls_api.c:tcf_proto_destroy"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589830666,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:580",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:tcf_chain0_head_change_cb_add",
        "net/sched/cls_api.c:tcf_proto_destroy"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589736815,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:580",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "net/sched/cls_api.c:tcf_proto_destroy"
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
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590495455,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:580",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "net/sched/cls_api.c:tcf_proto_destroy"
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
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592091077,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:597",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "net/sched/cls_api.c:tcf_proto_destroy"
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
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593911871,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:599",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "net/sched/cls_api.c:tcf_proto_destroy"
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
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594296295,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:704",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "net/sched/cls_api.c:tcf_proto_destroy"
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
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595095556,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:704",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "net/sched/cls_api.c:tcf_proto_destroy"
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
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502496276,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:565",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_proto_destroy"
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
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235210684,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:565",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_proto_destroy"
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
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296063820,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:565",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_proto_destroy"
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
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278674258,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:565",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_proto_destroy"
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
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588510147,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:565",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_proto_destroy"
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
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588222147,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:565",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_proto_destroy"
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
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588842323,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:565",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_proto_destroy"
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
  "name": "tcf_chain_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588986451,
      "name": "tcf_chain_put",
      "external": false,
      "loc": "net/sched/cls_api.c:565",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/cls_api.c:tcf_proto_destroy"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void tcf_chain_put(struct tcf_chain * chain)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void tcf_chain_put(struct tcf_chain * chain)
```
</details>
</li>
</ul>
