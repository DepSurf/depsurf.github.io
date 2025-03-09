# Function: <code>dm_put_live_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585792767,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:745",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_get_live_table_for_ioctl",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_pr_register",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_prep_fn",
        "drivers/md/dm.c:dm_prep_fn",
        "drivers/md/dm.c:dm_request_fn",
        "drivers/md/dm.c:dm_mq_queue_rq",
        "drivers/md/dm.c:dm_mq_queue_rq"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585804592,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586198890,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:579",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_blk_direct_access",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_request_fn",
        "drivers/md/dm-rq.c:dm_old_prep_fn",
        "drivers/md/dm-rq.c:dm_old_prep_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586199968,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586403370,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:579",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_blk_direct_access",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_request_fn",
        "drivers/md/dm-rq.c:dm_old_request_fn",
        "drivers/md/dm-rq.c:dm_old_prep_fn",
        "drivers/md/dm-rq.c:dm_old_prep_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586404448,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586506346,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:577",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_flush",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_request_fn",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586507872,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586973333,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:584",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl",
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_request_fn",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586975392,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587262364,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:676",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_old_request_fn",
        "drivers/md/dm-rq.c:dm_old_request_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587272128,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587442636,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:731",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587452624,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587721135,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:711",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587726640,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587925311,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:711",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587930992,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588775775,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:724",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
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
      "addr": 18446744071588784096,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588795833,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:720",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
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
      "addr": 18446744071588802592,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588681145,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:725",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_keyslot_evict",
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
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
      "addr": 18446744071588687472,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589365017,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:605",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio_begin",
        "drivers/md/dm-zone.c:dm_blk_report_zones",
        "drivers/md/dm-table.c:dm_keyslot_evict",
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
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
      "addr": 18446744071589371552,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590840337,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:690",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio_begin",
        "drivers/md/dm-zone.c:dm_blk_report_zones",
        "drivers/md/dm-table.c:dm_keyslot_evict",
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590851376,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592532049,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:684",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio_begin",
        "drivers/md/dm-zone.c:dm_blk_report_zones",
        "drivers/md/dm-table.c:dm_keyslot_evict",
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592541808,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592961963,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:691",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio_begin",
        "drivers/md/dm-zone.c:dm_blk_report_zones",
        "drivers/md/dm-table.c:dm_keyslot_evict",
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592973040,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593712091,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:693",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_submit_bio",
        "drivers/md/dm.c:dm_dax_recovery_write",
        "drivers/md/dm.c:dm_dax_zero_page_range",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": [
        "drivers/md/dm-zone.c:dm_zone_map_bio_begin",
        "drivers/md/dm-zone.c:dm_blk_report_zones",
        "drivers/md/dm-table.c:dm_keyslot_evict",
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:dm_hash_rename",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593722976,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501154104,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:711",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501166672,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233672440,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:711",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233676448,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294672112,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:711",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294678576,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277868644,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:711",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277874644,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587556287,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:711",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587561968,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587324383,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:711",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587330048,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587881455,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:711",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587887136,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void dm_put_live_table(struct mapped_device * md, int srcu_idx)
```

```json
{
  "name": "dm_put_live_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587997871,
      "name": "dm_put_live_table",
      "external": true,
      "loc": "drivers/md/dm.c:711",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_make_request",
        "drivers/md/dm.c:dm_dax_copy_to_iter",
        "drivers/md/dm.c:dm_dax_copy_from_iter",
        "drivers/md/dm.c:dm_dax_supported",
        "drivers/md/dm.c:dm_dax_direct_access",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm.c:dm_prepare_ioctl",
        "drivers/md/dm.c:dm_blk_report_zones"
      ],
      "caller_func": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:target_message",
        "drivers/md/dm-ioctl.c:table_status",
        "drivers/md/dm-ioctl.c:table_deps",
        "drivers/md/dm-ioctl.c:dev_wait",
        "drivers/md/dm-ioctl.c:dev_rename",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__dev_status",
        "drivers/md/dm-ioctl.c:__hash_remove",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588002432,
      "name": "dm_put_live_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
