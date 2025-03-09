# Function: <code>dm_process_bio</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
blk_qc_t dm_process_bio(struct mapped_device * md, struct dm_table * map, struct bio * bio)
```

```json
{
  "name": "dm_process_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587449872,
      "name": "dm_process_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1733",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587449872,
      "name": "dm_process_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
blk_qc_t dm_process_bio(struct mapped_device * md, struct dm_table * map, struct bio * bio)
```

```json
{
  "name": "dm_process_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587720048,
      "name": "dm_process_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1738",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587720048,
      "name": "dm_process_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
blk_qc_t dm_process_bio(struct mapped_device * md, struct dm_table * map, struct bio * bio)
```

```json
{
  "name": "dm_process_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587924624,
      "name": "dm_process_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1738",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587924624,
      "name": "dm_process_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
blk_qc_t dm_process_bio(struct mapped_device * md, struct dm_table * map, struct bio * bio)
```

```json
{
  "name": "dm_process_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588779872,
      "name": "dm_process_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1731",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588779872,
      "name": "dm_process_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
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
blk_qc_t dm_process_bio(struct mapped_device * md, struct dm_table * map, struct bio * bio)
```

```json
{
  "name": "dm_process_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501163032,
      "name": "dm_process_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1738",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501163032,
      "name": "dm_process_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
blk_qc_t dm_process_bio(struct mapped_device * md, struct dm_table * map, struct bio * bio)
```

```json
{
  "name": "dm_process_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233671424,
      "name": "dm_process_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1738",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233671424,
      "name": "dm_process_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
blk_qc_t dm_process_bio(struct mapped_device * md, struct dm_table * map, struct bio * bio)
```

```json
{
  "name": "dm_process_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294671168,
      "name": "dm_process_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1738",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294671168,
      "name": "dm_process_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
blk_qc_t dm_process_bio(struct mapped_device * md, struct dm_table * map, struct bio * bio)
```

```json
{
  "name": "dm_process_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277867720,
      "name": "dm_process_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1738",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277867720,
      "name": "dm_process_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
blk_qc_t dm_process_bio(struct mapped_device * md, struct dm_table * map, struct bio * bio)
```

```json
{
  "name": "dm_process_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587555600,
      "name": "dm_process_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1738",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587555600,
      "name": "dm_process_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
blk_qc_t dm_process_bio(struct mapped_device * md, struct dm_table * map, struct bio * bio)
```

```json
{
  "name": "dm_process_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587323696,
      "name": "dm_process_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1738",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587323696,
      "name": "dm_process_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
blk_qc_t dm_process_bio(struct mapped_device * md, struct dm_table * map, struct bio * bio)
```

```json
{
  "name": "dm_process_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587880768,
      "name": "dm_process_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1738",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587880768,
      "name": "dm_process_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
blk_qc_t dm_process_bio(struct mapped_device * md, struct dm_table * map, struct bio * bio)
```

```json
{
  "name": "dm_process_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587999184,
      "name": "dm_process_bio",
      "external": false,
      "loc": "drivers/md/dm.c:1738",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587999184,
      "name": "dm_process_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
blk_qc_t dm_process_bio(struct mapped_device * md, struct dm_table * map, struct bio * bio)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
blk_qc_t dm_process_bio(struct mapped_device * md, struct dm_table * map, struct bio * bio)
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
