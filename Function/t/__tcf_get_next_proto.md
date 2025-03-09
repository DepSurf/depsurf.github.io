# Function: <code>__tcf_get_next_proto</code>

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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "__tcf_get_next_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588668272,
      "name": "__tcf_get_next_proto",
      "external": false,
      "loc": "net/sched/cls_api.c:1074",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588668272,
      "name": "__tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "__tcf_get_next_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588896848,
      "name": "__tcf_get_next_proto",
      "external": false,
      "loc": "net/sched/cls_api.c:988",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588896848,
      "name": "__tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "__tcf_get_next_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589778496,
      "name": "__tcf_get_next_proto",
      "external": false,
      "loc": "net/sched/cls_api.c:951",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589778496,
      "name": "__tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "__tcf_get_next_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589813744,
      "name": "__tcf_get_next_proto",
      "external": false,
      "loc": "net/sched/cls_api.c:953",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589813744,
      "name": "__tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "__tcf_get_next_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589721488,
      "name": "__tcf_get_next_proto",
      "external": false,
      "loc": "net/sched/cls_api.c:953",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589721488,
      "name": "__tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "__tcf_get_next_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcf_get_next_proto",
      "external": false,
      "loc": "net/sched/cls_api.c:954",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590479744,
      "name": "__tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071592710532,
      "name": "__tcf_get_next_proto.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "__tcf_get_next_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcf_get_next_proto",
      "external": false,
      "loc": "net/sched/cls_api.c:971",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592078256,
      "name": "__tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071594596598,
      "name": "__tcf_get_next_proto.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "__tcf_get_next_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcf_get_next_proto",
      "external": false,
      "loc": "net/sched/cls_api.c:973",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593898880,
      "name": "__tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071596332873,
      "name": "__tcf_get_next_proto.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "__tcf_get_next_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcf_get_next_proto",
      "external": false,
      "loc": "net/sched/cls_api.c:1078",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594275136,
      "name": "__tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071596861691,
      "name": "__tcf_get_next_proto.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "__tcf_get_next_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcf_get_next_proto",
      "external": false,
      "loc": "net/sched/cls_api.c:1080",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595073264,
      "name": "__tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    },
    {
      "addr": 18446744071597786777,
      "name": "__tcf_get_next_proto.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "__tcf_get_next_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502487120,
      "name": "__tcf_get_next_proto",
      "external": false,
      "loc": "net/sched/cls_api.c:988",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502487120,
      "name": "__tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "__tcf_get_next_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235191368,
      "name": "__tcf_get_next_proto",
      "external": false,
      "loc": "net/sched/cls_api.c:988",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235191368,
      "name": "__tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "__tcf_get_next_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296044880,
      "name": "__tcf_get_next_proto",
      "external": false,
      "loc": "net/sched/cls_api.c:988",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296044880,
      "name": "__tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "__tcf_get_next_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278663046,
      "name": "__tcf_get_next_proto",
      "external": false,
      "loc": "net/sched/cls_api.c:988",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278663046,
      "name": "__tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "__tcf_get_next_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588503232,
      "name": "__tcf_get_next_proto",
      "external": false,
      "loc": "net/sched/cls_api.c:988",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588503232,
      "name": "__tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "__tcf_get_next_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588215232,
      "name": "__tcf_get_next_proto",
      "external": false,
      "loc": "net/sched/cls_api.c:988",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588215232,
      "name": "__tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "__tcf_get_next_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588835408,
      "name": "__tcf_get_next_proto",
      "external": false,
      "loc": "net/sched/cls_api.c:988",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588835408,
      "name": "__tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
```

```json
{
  "name": "__tcf_get_next_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588966336,
      "name": "__tcf_get_next_proto",
      "external": false,
      "loc": "net/sched/cls_api.c:988",
      "file": "net/sched/cls_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tcf_chain_dump",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tcf_block_playback_offloads",
        "net/sched/cls_api.c:tcf_block_playback_offloads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588966336,
      "name": "__tcf_get_next_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
struct tcf_proto * __tcf_get_next_proto(struct tcf_chain * chain, struct tcf_proto * tp)
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
