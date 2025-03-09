# Function: <code>part_inc_in_flight</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "part_inc_in_flight",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582713454,
      "name": "part_inc_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:396",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:generic_start_io_acct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582755309,
      "name": "part_inc_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:396",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584705161,
      "name": "part_inc_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:396",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:__nd_iostat_start"
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
  "name": "part_inc_in_flight",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582990822,
      "name": "part_inc_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:380",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:generic_start_io_acct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583033231,
      "name": "part_inc_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:380",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585053080,
      "name": "part_inc_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:380",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:__nd_iostat_start"
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
  "name": "part_inc_in_flight",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583095766,
      "name": "part_inc_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:371",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:generic_start_io_acct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583138176,
      "name": "part_inc_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:371",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "part_inc_in_flight",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583152182,
      "name": "part_inc_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:365",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:generic_start_io_acct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583195158,
      "name": "part_inc_in_flight",
      "external": false,
      "loc": "include/linux/genhd.h:365",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
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
void part_inc_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_inc_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583449584,
      "name": "part_inc_in_flight",
      "external": true,
      "loc": "block/genhd.c:48",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583449584,
      "name": "part_inc_in_flight",
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
void part_inc_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_inc_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583660816,
      "name": "part_inc_in_flight",
      "external": true,
      "loc": "block/genhd.c:48",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583660816,
      "name": "part_inc_in_flight",
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
void part_inc_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_inc_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583767088,
      "name": "part_inc_in_flight",
      "external": true,
      "loc": "block/genhd.c:48",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583767088,
      "name": "part_inc_in_flight",
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
void part_inc_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_inc_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583956560,
      "name": "part_inc_in_flight",
      "external": true,
      "loc": "block/genhd.c:49",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583956560,
      "name": "part_inc_in_flight",
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
void part_inc_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_inc_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584060032,
      "name": "part_inc_in_flight",
      "external": true,
      "loc": "block/genhd.c:49",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584060032,
      "name": "part_inc_in_flight",
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
void part_inc_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_inc_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495901320,
      "name": "part_inc_in_flight",
      "external": true,
      "loc": "block/genhd.c:49",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495901320,
      "name": "part_inc_in_flight",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void part_inc_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_inc_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229244472,
      "name": "part_inc_in_flight",
      "external": true,
      "loc": "block/genhd.c:49",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229244472,
      "name": "part_inc_in_flight",
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
void part_inc_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_inc_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290108400,
      "name": "part_inc_in_flight",
      "external": true,
      "loc": "block/genhd.c:49",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290108400,
      "name": "part_inc_in_flight",
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
void part_inc_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_inc_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275017220,
      "name": "part_inc_in_flight",
      "external": true,
      "loc": "block/genhd.c:49",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275017220,
      "name": "part_inc_in_flight",
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
void part_inc_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_inc_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584028768,
      "name": "part_inc_in_flight",
      "external": true,
      "loc": "block/genhd.c:49",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028768,
      "name": "part_inc_in_flight",
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
void part_inc_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_inc_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583964560,
      "name": "part_inc_in_flight",
      "external": true,
      "loc": "block/genhd.c:49",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964560,
      "name": "part_inc_in_flight",
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
void part_inc_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_inc_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584012528,
      "name": "part_inc_in_flight",
      "external": true,
      "loc": "block/genhd.c:49",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584012528,
      "name": "part_inc_in_flight",
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
void part_inc_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
```

```json
{
  "name": "part_inc_in_flight",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584115056,
      "name": "part_inc_in_flight",
      "external": true,
      "loc": "block/genhd.c:49",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584115056,
      "name": "part_inc_in_flight",
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
void part_inc_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
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
void part_inc_in_flight(struct request_queue * q, struct hd_struct * part, int rw)
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
