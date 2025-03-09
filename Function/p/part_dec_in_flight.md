# Function: <code>part_dec_in_flight</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "part_dec_in_flight",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582713644,
      "name": "part_dec_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:403",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:generic_end_io_acct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582754365,
      "name": "part_dec_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:403",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582783766,
      "name": "part_dec_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:403",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:attempt_merge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584705392,
      "name": "part_dec_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:403",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:nd_iostat_end"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "part_dec_in_flight",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582991010,
      "name": "part_dec_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:387",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:generic_end_io_acct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583032247,
      "name": "part_dec_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:387",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583062109,
      "name": "part_dec_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:387",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585053315,
      "name": "part_dec_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:387",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:nd_iostat_end"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "part_dec_in_flight",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583095954,
      "name": "part_dec_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:378",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:generic_end_io_acct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583137102,
      "name": "part_dec_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:378",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583169238,
      "name": "part_dec_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:378",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "part_dec_in_flight",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583152370,
      "name": "part_dec_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:372",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:generic_end_io_acct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583193924,
      "name": "part_dec_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:372",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583226218,
      "name": "part_dec_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:372",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:attempt_merge"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void part_dec_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_dec_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583449664,
      "name": "part_dec_in_flight",
      "external": true,
      "loc": "block/genhd.c:58",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/blk-merge.c:attempt_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583449664,
      "name": "part_dec_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void part_dec_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_dec_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583660896,
      "name": "part_dec_in_flight",
      "external": true,
      "loc": "block/genhd.c:58",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583660896,
      "name": "part_dec_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void part_dec_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_dec_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583767200,
      "name": "part_dec_in_flight",
      "external": true,
      "loc": "block/genhd.c:58",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583767200,
      "name": "part_dec_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void part_dec_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_dec_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583956672,
      "name": "part_dec_in_flight",
      "external": true,
      "loc": "block/genhd.c:59",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583956672,
      "name": "part_dec_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void part_dec_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_dec_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584060144,
      "name": "part_dec_in_flight",
      "external": true,
      "loc": "block/genhd.c:59",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584060144,
      "name": "part_dec_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void part_dec_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_dec_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495901536,
      "name": "part_dec_in_flight",
      "external": true,
      "loc": "block/genhd.c:59",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495901536,
      "name": "part_dec_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void part_dec_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_dec_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229244660,
      "name": "part_dec_in_flight",
      "external": true,
      "loc": "block/genhd.c:59",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229244660,
      "name": "part_dec_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void part_dec_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_dec_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290108640,
      "name": "part_dec_in_flight",
      "external": true,
      "loc": "block/genhd.c:59",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290108640,
      "name": "part_dec_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void part_dec_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_dec_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275017364,
      "name": "part_dec_in_flight",
      "external": true,
      "loc": "block/genhd.c:59",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275017364,
      "name": "part_dec_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void part_dec_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_dec_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584028880,
      "name": "part_dec_in_flight",
      "external": true,
      "loc": "block/genhd.c:59",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028880,
      "name": "part_dec_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void part_dec_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_dec_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583964672,
      "name": "part_dec_in_flight",
      "external": true,
      "loc": "block/genhd.c:59",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964672,
      "name": "part_dec_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void part_dec_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_dec_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584012640,
      "name": "part_dec_in_flight",
      "external": true,
      "loc": "block/genhd.c:59",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584012640,
      "name": "part_dec_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void part_dec_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_dec_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584115168,
      "name": "part_dec_in_flight",
      "external": true,
      "loc": "block/genhd.c:59",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584115168,
      "name": "part_dec_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void part_dec_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void part_dec_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
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
