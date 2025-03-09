# Function: <code>generic_start_io_acct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void generic_start_io_acct(int rw, long unsigned int sectors, struct hd_struct * part)
```

```json
{
  "name": "generic_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582713264,
      "name": "generic_start_io_acct",
      "external": true,
      "loc": "block/bio.c:1675",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582713264,
      "name": "generic_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void generic_start_io_acct(int rw, long unsigned int sectors, struct hd_struct * part)
```

```json
{
  "name": "generic_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582990624,
      "name": "generic_start_io_acct",
      "external": true,
      "loc": "block/bio.c:1674",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582990624,
      "name": "generic_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void generic_start_io_acct(int rw, long unsigned int sectors, struct hd_struct * part)
```

```json
{
  "name": "generic_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583095568,
      "name": "generic_start_io_acct",
      "external": true,
      "loc": "block/bio.c:1729",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583095568,
      "name": "generic_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void generic_start_io_acct(int rw, long unsigned int sectors, struct hd_struct * part)
```

```json
{
  "name": "generic_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583151984,
      "name": "generic_start_io_acct",
      "external": true,
      "loc": "block/bio.c:1735",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583151984,
      "name": "generic_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void generic_start_io_acct(struct request_queue * q, int rw, long unsigned int sectors, struct hd_struct * part)
```

```json
{
  "name": "generic_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583327136,
      "name": "generic_start_io_acct",
      "external": true,
      "loc": "block/bio.c:1699",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583327136,
      "name": "generic_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void generic_start_io_acct(struct request_queue * q, int rw, long unsigned int sectors, struct hd_struct * part)
```

```json
{
  "name": "generic_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583535936,
      "name": "generic_start_io_acct",
      "external": true,
      "loc": "block/bio.c:1756",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:alloc_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583535936,
      "name": "generic_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void generic_start_io_acct(struct request_queue * q, int op, long unsigned int sectors, struct hd_struct * part)
```

```json
{
  "name": "generic_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583669168,
      "name": "generic_start_io_acct",
      "external": true,
      "loc": "block/bio.c:1680",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:alloc_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583669168,
      "name": "generic_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void generic_start_io_acct(struct request_queue * q, int op, long unsigned int sectors, struct hd_struct * part)
```

```json
{
  "name": "generic_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583857728,
      "name": "generic_start_io_acct",
      "external": true,
      "loc": "block/bio.c:1729",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:alloc_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583857728,
      "name": "generic_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void generic_start_io_acct(struct request_queue * q, int op, long unsigned int sectors, struct hd_struct * part)
```

```json
{
  "name": "generic_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583960384,
      "name": "generic_start_io_acct",
      "external": true,
      "loc": "block/bio.c:1771",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:alloc_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583960384,
      "name": "generic_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void generic_start_io_acct(struct request_queue * q, int op, long unsigned int sectors, struct hd_struct * part)
```

```json
{
  "name": "generic_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495782160,
      "name": "generic_start_io_acct",
      "external": true,
      "loc": "block/bio.c:1771",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:alloc_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495782160,
      "name": "generic_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void generic_start_io_acct(struct request_queue * q, int op, long unsigned int sectors, struct hd_struct * part)
```

```json
{
  "name": "generic_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229134028,
      "name": "generic_start_io_acct",
      "external": true,
      "loc": "block/bio.c:1771",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:alloc_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229134028,
      "name": "generic_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void generic_start_io_acct(struct request_queue * q, int op, long unsigned int sectors, struct hd_struct * part)
```

```json
{
  "name": "generic_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289958848,
      "name": "generic_start_io_acct",
      "external": true,
      "loc": "block/bio.c:1771",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:alloc_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289958848,
      "name": "generic_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void generic_start_io_acct(struct request_queue * q, int op, long unsigned int sectors, struct hd_struct * part)
```

```json
{
  "name": "generic_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274925870,
      "name": "generic_start_io_acct",
      "external": true,
      "loc": "block/bio.c:1771",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:alloc_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274925870,
      "name": "generic_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void generic_start_io_acct(struct request_queue * q, int op, long unsigned int sectors, struct hd_struct * part)
```

```json
{
  "name": "generic_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583929120,
      "name": "generic_start_io_acct",
      "external": true,
      "loc": "block/bio.c:1771",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:alloc_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583929120,
      "name": "generic_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void generic_start_io_acct(struct request_queue * q, int op, long unsigned int sectors, struct hd_struct * part)
```

```json
{
  "name": "generic_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583866064,
      "name": "generic_start_io_acct",
      "external": true,
      "loc": "block/bio.c:1771",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/pmem.c:pmem_make_request",
        "drivers/nvdimm/btt.c:btt_make_request",
        "drivers/md/dm.c:alloc_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583866064,
      "name": "generic_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void generic_start_io_acct(struct request_queue * q, int op, long unsigned int sectors, struct hd_struct * part)
```

```json
{
  "name": "generic_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583912880,
      "name": "generic_start_io_acct",
      "external": true,
      "loc": "block/bio.c:1771",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:alloc_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583912880,
      "name": "generic_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void generic_start_io_acct(struct request_queue * q, int op, long unsigned int sectors, struct hd_struct * part)
```

```json
{
  "name": "generic_start_io_acct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584014176,
      "name": "generic_start_io_acct",
      "external": true,
      "loc": "block/bio.c:1771",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:alloc_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014176,
      "name": "generic_start_io_acct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue * q</code>
</li>
<li>
<b>Param reordered. </b>
<code>rw, sectors, part</code> ➡️ <code>q, rw, sectors, part</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
</ul>
</details>
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
void generic_start_io_acct(struct request_queue * q, int op, long unsigned int sectors, struct hd_struct * part)
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
