# Function: <code>blkg_rwstat_add_aux</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
void blkg_rwstat_add_aux(struct blkg_rwstat * to, struct blkg_rwstat * from)
```

```json
{
  "name": "blkg_rwstat_add_aux",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582872368,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:673",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    },
    {
      "addr": 18446744071582900624,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:673",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:cfq_pd_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582872368,
      "name": "blkg_rwstat_add_aux",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    },
    {
      "addr": 18446744071582900624,
      "name": "blkg_rwstat_add_aux",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate ❓</summary>

```c
void blkg_rwstat_add_aux(struct blkg_rwstat * to, struct blkg_rwstat * from)
```

```json
{
  "name": "blkg_rwstat_add_aux",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583158336,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:674",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    },
    {
      "addr": 18446744071583187632,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:674",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:cfq_pd_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583158336,
      "name": "blkg_rwstat_add_aux",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071583187632,
      "name": "blkg_rwstat_add_aux",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
void blkg_rwstat_add_aux(struct blkg_rwstat * to, struct blkg_rwstat * from)
```

```json
{
  "name": "blkg_rwstat_add_aux",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583270416,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:664",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    },
    {
      "addr": 18446744071583300800,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:664",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:cfq_pd_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583270416,
      "name": "blkg_rwstat_add_aux",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071583300800,
      "name": "blkg_rwstat_add_aux",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
void blkg_rwstat_add_aux(struct blkg_rwstat * to, struct blkg_rwstat * from)
```

```json
{
  "name": "blkg_rwstat_add_aux",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583325584,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:664",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    },
    {
      "addr": 18446744071583362880,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:664",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:cfq_pd_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583325584,
      "name": "blkg_rwstat_add_aux",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071583362880,
      "name": "blkg_rwstat_add_aux",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
void blkg_rwstat_add_aux(struct blkg_rwstat * to, struct blkg_rwstat * from)
```

```json
{
  "name": "blkg_rwstat_add_aux",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583508704,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:660",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy"
      ]
    },
    {
      "addr": 18446744071583543424,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:660",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:cfq_pd_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583508704,
      "name": "blkg_rwstat_add_aux",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071583543424,
      "name": "blkg_rwstat_add_aux",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_rwstat_add_aux",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583727460,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:678",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583771406,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:678",
      "file": "block/cfq-iosched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:cfq_pd_offline",
        "block/cfq-iosched.c:cfq_pd_offline"
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
  "name": "blkg_rwstat_add_aux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583833109,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:744",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy"
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
  "name": "blkg_rwstat_add_aux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584023248,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:687",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy"
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
  "name": "blkg_rwstat_add_aux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584126848,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:689",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_rwstat_add_aux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495973720,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:689",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy"
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
  "name": "blkg_rwstat_add_aux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229318160,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:689",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy"
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
  "name": "blkg_rwstat_add_aux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290196780,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:689",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy"
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
  "name": "blkg_rwstat_add_aux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275075034,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:689",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy"
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
  "name": "blkg_rwstat_add_aux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584095584,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:689",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy"
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
  "name": "blkg_rwstat_add_aux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584031344,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:689",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy"
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
  "name": "blkg_rwstat_add_aux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584079344,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:689",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy"
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
  "name": "blkg_rwstat_add_aux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584183760,
      "name": "blkg_rwstat_add_aux",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:689",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void blkg_rwstat_add_aux(struct blkg_rwstat * to, struct blkg_rwstat * from)
```
</details>
</li>
</ul>
