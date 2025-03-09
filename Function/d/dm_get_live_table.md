# Function: <code>dm_get_live_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585792720,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:738",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_get_live_table_for_ioctl",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_prep_fn",
        "drivers/md/dm.c:dm_request_fn",
        "drivers/md/dm.c:dm_mq_queue_rq"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:dm_get_inactive_table",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585804544,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586198768,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:572",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_blk_direct_access",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_get_inactive_table",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_request_fn",
        "drivers/md/dm-rq.c:dm_old_prep_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586199920,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586403248,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:572",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_blk_direct_access",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_get_inactive_table",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_request_fn",
        "drivers/md/dm-rq.c:dm_old_prep_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586404400,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586506220,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:570",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_get_inactive_table",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586507824,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586973174,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:577",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_get_inactive_table",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586975344,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587269501,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:669",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_get_inactive_table",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587272080,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587449933,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:724",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_get_inactive_table",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587452576,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587722429,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:704",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_get_inactive_table",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587726592,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587926605,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:704",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_get_inactive_table",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587930944,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588780157,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:717",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588784048,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588800126,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:713",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588802544,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588685006,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:718",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_keyslot_evict",
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588687424,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589369477,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:598",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio_begin",
        "drivers/md/dm-zone.c:dm_blk_report_zones",
        "drivers/md/dm-table.c:dm_keyslot_evict",
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589371504,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590844168,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:682",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio_begin",
        "drivers/md/dm-zone.c:dm_blk_report_zones",
        "drivers/md/dm-table.c:dm_keyslot_evict",
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590851312,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592535384,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:676",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio_begin",
        "drivers/md/dm-zone.c:dm_blk_report_zones",
        "drivers/md/dm-table.c:dm_keyslot_evict",
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592541728,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592967000,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:683",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio_begin",
        "drivers/md/dm-zone.c:dm_blk_report_zones",
        "drivers/md/dm-table.c:dm_keyslot_evict",
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592972960,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593717128,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:685",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio_begin",
        "drivers/md/dm-zone.c:dm_blk_report_zones",
        "drivers/md/dm-table.c:dm_keyslot_evict",
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593722896,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501163648,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:704",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_get_inactive_table",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501166616,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233674808,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:704",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_get_live_or_inactive_table",
        "drivers/md/dm-ioctl.c:dm_get_inactive_table",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233676400,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294674072,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:704",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_get_inactive_table",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294678480,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277870098,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:704",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_get_inactive_table",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277874588,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587557581,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:704",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_get_inactive_table",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587561920,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587325677,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:704",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_get_inactive_table",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587330000,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587882749,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:704",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_get_inactive_table",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587887088,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_table * dm_get_live_table(struct mapped_device * md, int * srcu_idx)
```

```json
{
  "name": "dm_get_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587999789,
      "name": "dm_get_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:704",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_get_live_target",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_get_inactive_table",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588002384,
      "name": "dm_get_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
