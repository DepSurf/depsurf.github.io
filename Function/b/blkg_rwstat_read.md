# Function: <code>blkg_rwstat_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
struct blkg_rwstat blkg_rwstat_read(struct blkg_rwstat * rwstat)
```

```json
{
  "name": "blkg_rwstat_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582871968,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:625",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_prfill_rwstat",
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_rwstat_add_aux"
      ]
    },
    {
      "addr": 18446744071582900448,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:625",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:blkg_rwstat_add_aux",
        "block/cfq-iosched.c:blkg_rwstat_total"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582871968,
      "name": "blkg_rwstat_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071582900448,
      "name": "blkg_rwstat_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
struct blkg_rwstat blkg_rwstat_read(struct blkg_rwstat * rwstat)
```

```json
{
  "name": "blkg_rwstat_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583157936,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:626",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat",
        "block/blk-cgroup.c:blkg_rwstat_add_aux"
      ]
    },
    {
      "addr": 18446744071583187456,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:626",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:blkg_rwstat_add_aux",
        "block/cfq-iosched.c:blkg_rwstat_total"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583157936,
      "name": "blkg_rwstat_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071583187456,
      "name": "blkg_rwstat_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
struct blkg_rwstat blkg_rwstat_read(struct blkg_rwstat * rwstat)
```

```json
{
  "name": "blkg_rwstat_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583270016,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:616",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat",
        "block/blk-cgroup.c:blkg_rwstat_add_aux"
      ]
    },
    {
      "addr": 18446744071583300624,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:616",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:blkg_rwstat_add_aux",
        "block/cfq-iosched.c:blkg_rwstat_total"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583270016,
      "name": "blkg_rwstat_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071583300624,
      "name": "blkg_rwstat_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
struct blkg_rwstat blkg_rwstat_read(struct blkg_rwstat * rwstat)
```

```json
{
  "name": "blkg_rwstat_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583325184,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:616",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat",
        "block/blk-cgroup.c:blkg_rwstat_add_aux"
      ]
    },
    {
      "addr": 18446744071583362704,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:616",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:blkg_rwstat_add_aux",
        "block/cfq-iosched.c:blkg_rwstat_total"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583325184,
      "name": "blkg_rwstat_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071583362704,
      "name": "blkg_rwstat_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
struct blkg_rwstat blkg_rwstat_read(struct blkg_rwstat * rwstat)
```

```json
{
  "name": "blkg_rwstat_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583508304,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:612",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat",
        "block/blk-cgroup.c:blkg_rwstat_add_aux"
      ]
    },
    {
      "addr": 18446744071583543248,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:612",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:blkg_rwstat_add_aux",
        "block/cfq-iosched.c:blkg_rwstat_total"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583508304,
      "name": "blkg_rwstat_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071583543248,
      "name": "blkg_rwstat_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate ❓</summary>

```c
struct blkg_rwstat blkg_rwstat_read(struct blkg_rwstat * rwstat)
```

```json
{
  "name": "blkg_rwstat_read",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583722736,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:630",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat"
      ]
    },
    {
      "addr": 18446744071583758128,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:630",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:blkg_rwstat_total"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583722736,
      "name": "blkg_rwstat_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071583758128,
      "name": "blkg_rwstat_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
struct blkg_rwstat blkg_rwstat_read(struct blkg_rwstat * rwstat)
```

```json
{
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583829232,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:696",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583829232,
      "name": "blkg_rwstat_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584019991,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:640",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat"
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
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584123559,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:642",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat"
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
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584531189,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "block/blk-cgroup-rwstat.h:89",
      "file": "block/blk-cgroup-rwstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup-rwstat.c:blkg_prfill_rwstat"
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
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584641173,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "block/blk-cgroup-rwstat.h:89",
      "file": "block/blk-cgroup-rwstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup-rwstat.c:blkg_prfill_rwstat"
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
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584669409,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "block/blk-cgroup-rwstat.h:89",
      "file": "block/blk-cgroup-rwstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup-rwstat.c:blkg_prfill_rwstat"
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
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585086009,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "block/blk-cgroup-rwstat.h:89",
      "file": "block/blk-cgroup-rwstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup-rwstat.c:blkg_prfill_rwstat"
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
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585812825,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "block/blk-cgroup-rwstat.h:89",
      "file": "block/blk-cgroup-rwstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup-rwstat.c:blkg_prfill_rwstat"
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
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586594761,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "block/blk-cgroup-rwstat.h:89",
      "file": "block/blk-cgroup-rwstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup-rwstat.c:blkg_prfill_rwstat"
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
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586852971,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "block/blk-cgroup-rwstat.h:89",
      "file": "block/blk-cgroup-rwstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup-rwstat.c:blkg_prfill_rwstat"
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
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587130299,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "block/blk-cgroup-rwstat.h:89",
      "file": "block/blk-cgroup-rwstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup-rwstat.c:blkg_prfill_rwstat"
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
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495970180,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:642",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat"
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
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229312668,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:642",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat"
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
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290191876,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:642",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat"
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
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275072750,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:642",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat"
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
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584092295,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:642",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat"
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
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584028055,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:642",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat"
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
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584076055,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:642",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat"
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
  "name": "blkg_rwstat_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584178871,
      "name": "blkg_rwstat_read",
      "external": false,
      "loc": "include/linux/blk-cgroup.h:642",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_prfill_rwstat_field",
        "block/blk-cgroup.c:blkg_prfill_rwstat"
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
struct blkg_rwstat blkg_rwstat_read(struct blkg_rwstat * rwstat)
```
</details>
</li>
</ul>
