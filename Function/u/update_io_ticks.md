# Function: <code>update_io_ticks</code>

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
void update_io_ticks(struct hd_struct * part, long unsigned int now)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583669024,
      "name": "update_io_ticks",
      "external": true,
      "loc": "block/bio.c:1664",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583669024,
      "name": "update_io_ticks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void update_io_ticks(struct hd_struct * part, long unsigned int now)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583857616,
      "name": "update_io_ticks",
      "external": true,
      "loc": "block/bio.c:1713",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583857616,
      "name": "update_io_ticks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void update_io_ticks(struct hd_struct * part, long unsigned int now)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583960272,
      "name": "update_io_ticks",
      "external": true,
      "loc": "block/bio.c:1755",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583960272,
      "name": "update_io_ticks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void update_io_ticks(struct hd_struct * part, long unsigned int now, bool end)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584360432,
      "name": "update_io_ticks",
      "external": false,
      "loc": "block/blk-core.c:1393",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:disk_end_io_acct",
        "block/blk-core.c:disk_start_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584360432,
      "name": "update_io_ticks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
void update_io_ticks(struct block_device * part, long unsigned int now, bool end)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584476832,
      "name": "update_io_ticks",
      "external": false,
      "loc": "block/blk-core.c:1265",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__part_end_io_acct",
        "block/blk-core.c:__part_start_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584476832,
      "name": "update_io_ticks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void update_io_ticks(struct block_device * part, long unsigned int now, bool end)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584511728,
      "name": "update_io_ticks",
      "external": false,
      "loc": "block/blk-core.c:1250",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__part_end_io_acct",
        "block/blk-core.c:__part_start_io_acct",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584511728,
      "name": "update_io_ticks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void update_io_ticks(struct block_device * part, long unsigned int now, bool end)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584923536,
      "name": "update_io_ticks",
      "external": false,
      "loc": "block/blk-core.c:1227",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:__part_end_io_acct",
        "block/blk-core.c:__part_start_io_acct",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584923536,
      "name": "update_io_ticks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void update_io_ticks(struct block_device * part, long unsigned int now, bool end)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585634752,
      "name": "update_io_ticks",
      "external": true,
      "loc": "block/blk-core.c:984",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:bdev_end_io_acct",
        "block/blk-core.c:bdev_start_io_acct",
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_execute_rq",
        "block/blk-mq.c:blk_execute_rq_nowait",
        "block/blk-mq.c:__blk_account_io_done",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585634752,
      "name": "update_io_ticks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void update_io_ticks(struct block_device * part, long unsigned int now, bool end)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586405920,
      "name": "update_io_ticks",
      "external": true,
      "loc": "block/blk-core.c:934",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:bdev_end_io_acct",
        "block/blk-core.c:bdev_start_io_acct",
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_execute_rq",
        "block/blk-mq.c:blk_execute_rq_nowait",
        "block/blk-mq.c:__blk_account_io_done",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586405920,
      "name": "update_io_ticks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void update_io_ticks(struct block_device * part, long unsigned int now, bool end)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586653200,
      "name": "update_io_ticks",
      "external": true,
      "loc": "block/blk-core.c:937",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:bdev_end_io_acct",
        "block/blk-core.c:bio_start_io_acct",
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_execute_rq",
        "block/blk-mq.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_account_io_done",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586653200,
      "name": "update_io_ticks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void update_io_ticks(struct block_device * part, long unsigned int now, bool end)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586924464,
      "name": "update_io_ticks",
      "external": true,
      "loc": "block/blk-core.c:972",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:bdev_end_io_acct",
        "block/blk-core.c:bio_start_io_acct",
        "block/blk-mq.c:blk_insert_cloned_request",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_execute_rq",
        "block/blk-mq.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_account_io_done",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586924464,
      "name": "update_io_ticks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void update_io_ticks(struct hd_struct * part, long unsigned int now)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495781968,
      "name": "update_io_ticks",
      "external": true,
      "loc": "block/bio.c:1755",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495781968,
      "name": "update_io_ticks",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void update_io_ticks(struct hd_struct * part, long unsigned int now)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229133864,
      "name": "update_io_ticks",
      "external": true,
      "loc": "block/bio.c:1755",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229133864,
      "name": "update_io_ticks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void update_io_ticks(struct hd_struct * part, long unsigned int now)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289958688,
      "name": "update_io_ticks",
      "external": true,
      "loc": "block/bio.c:1755",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289958688,
      "name": "update_io_ticks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void update_io_ticks(struct hd_struct * part, long unsigned int now)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274925736,
      "name": "update_io_ticks",
      "external": true,
      "loc": "block/bio.c:1755",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274925736,
      "name": "update_io_ticks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void update_io_ticks(struct hd_struct * part, long unsigned int now)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583929008,
      "name": "update_io_ticks",
      "external": true,
      "loc": "block/bio.c:1755",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583929008,
      "name": "update_io_ticks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void update_io_ticks(struct hd_struct * part, long unsigned int now)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583865952,
      "name": "update_io_ticks",
      "external": true,
      "loc": "block/bio.c:1755",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583865952,
      "name": "update_io_ticks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void update_io_ticks(struct hd_struct * part, long unsigned int now)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583912768,
      "name": "update_io_ticks",
      "external": true,
      "loc": "block/bio.c:1755",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583912768,
      "name": "update_io_ticks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void update_io_ticks(struct hd_struct * part, long unsigned int now)
```

```json
{
  "name": "update_io_ticks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584014064,
      "name": "update_io_ticks",
      "external": true,
      "loc": "block/bio.c:1755",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:generic_end_io_acct",
        "block/bio.c:generic_start_io_acct",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014064,
      "name": "update_io_ticks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void update_io_ticks(struct hd_struct * part, long unsigned int now)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool end</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct hd_struct * part</code> ➡️ <code>struct block_device * part</code>
</li>
</ul>
</details>
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
