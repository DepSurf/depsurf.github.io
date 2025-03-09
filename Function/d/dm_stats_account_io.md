# Function: <code>dm_stats_account_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585845984,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:625",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dm_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585845984,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
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
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586240608,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:624",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-rq.c:dm_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586240608,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 774
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
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586446624,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:625",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-rq.c:dm_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586446624,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 774
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
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586552512,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:620",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-rq.c:dm_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586552512,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 766
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
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587020032,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:621",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-rq.c:dm_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587020032,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
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
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587318496,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:622",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-rq.c:dm_start_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587318496,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 745
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
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587498752,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:622",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587498752,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 723
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:622",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587776263,
      "name": "dm_stats_account_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587773744,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:622",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587980796,
      "name": "dm_stats_account_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587978320,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:622",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:end_io_acct",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_done",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588835118,
      "name": "dm_stats_account_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588833664,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:622",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm.c:end_io_acct",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_done",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591593657,
      "name": "dm_stats_account_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588850112,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:622",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_done",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591536792,
      "name": "dm_stats_account_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588736880,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:622",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dm_io_dec_pending",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592650644,
      "name": "dm_stats_account_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071589427344,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int start_time, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590905456,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:653",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_io_acct",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590905456,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int start_time, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592601888,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:653",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_io_acct",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592601888,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int start_time, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593032464,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:663",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_io_acct",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593032464,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int start_time, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593783840,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:672",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_io_acct",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593783840,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501222288,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:622",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501222288,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 816
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
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233725792,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:622",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233725792,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1320
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
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294748432,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:622",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294748432,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 980
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
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277916928,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:622",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277916928,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:622",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587611772,
      "name": "dm_stats_account_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587609296,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:622",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587379788,
      "name": "dm_stats_account_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587377312,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:622",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587936940,
      "name": "dm_stats_account_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587934464,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void dm_stats_account_io(struct dm_stats * stats, long unsigned int bi_rw, sector_t bi_sector, unsigned int bi_sectors, bool end, long unsigned int duration_jiffies, struct dm_stats_aux * stats_aux)
```

```json
{
  "name": "dm_stats_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_stats_account_io",
      "external": true,
      "loc": "drivers/md/dm-stats.c:622",
      "file": "drivers/md/dm-stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:alloc_io",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588052204,
      "name": "dm_stats_account_io.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588049680,
      "name": "dm_stats_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int start_time</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int duration_jiffies</code>
</li>
</ul>
</details>
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
