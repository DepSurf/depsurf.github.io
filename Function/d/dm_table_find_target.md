# Function: <code>dm_table_find_target</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585818800,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1178",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__send_changing_extent_only",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:dm_request_fn",
        "drivers/md/dm.c:dm_mq_queue_rq",
        "drivers/md/dm-ioctl.c:target_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585818800,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586212656,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1280",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__send_changing_extent_only",
        "drivers/md/dm.c:dm_blk_direct_access",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586212656,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586417152,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1281",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__send_changing_extent_only",
        "drivers/md/dm.c:dm_blk_direct_access",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586417152,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586520928,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1332",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_changing_extent_only",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586520928,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586988352,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1334",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:__send_changing_extent_only",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586988352,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587286064,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1372",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587286064,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587466080,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1352",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587466080,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587739376,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1365",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587739376,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587943648,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1363",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587943648,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588796336,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1339",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588796336,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588814128,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1278",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588814128,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588700400,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1474",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588700400,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589389024,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1469",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589389024,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590865456,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1461",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590865456,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592558032,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1470",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592558032,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592988416,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1454",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592988416,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593739232,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1476",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_split_and_process_bio",
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593739232,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501182592,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1363",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501182592,
      "name": "dm_table_find_target",
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233689776,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1363",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233689776,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294695728,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1363",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294695728,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277885946,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1363",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277885946,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587574624,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1363",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587574624,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587342704,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1363",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587342704,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587899792,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1363",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587899792,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct dm_target * dm_table_find_target(struct dm_table * t, sector_t sector)
```

```json
{
  "name": "dm_table_find_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588015056,
      "name": "dm_table_find_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1363",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_blk_report_zones",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588015056,
      "name": "dm_table_find_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
