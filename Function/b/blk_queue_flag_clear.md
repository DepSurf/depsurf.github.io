# Function: <code>blk_queue_flag_clear</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583553520,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:94",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_clear_preempt_only",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-sysfs.c:queue_store_iostats",
        "block/blk-sysfs.c:queue_store_random",
        "block/blk-sysfs.c:queue_store_nonrot",
        "block/blk-settings.c:blk_queue_flush_queueable",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-stat.c:blk_stat_remove_callback",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583553520,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583674624,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:86",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_store_iostats",
        "block/blk-sysfs.c:queue_store_random",
        "block/blk-sysfs.c:queue_store_nonrot",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_flush_queueable",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-stat.c:blk_stat_remove_callback",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583674624,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583863344,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:87",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_store_iostats",
        "block/blk-sysfs.c:queue_store_random",
        "block/blk-sysfs.c:queue_store_nonrot",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-stat.c:blk_stat_remove_callback",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:disable_discard",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583863344,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583966224,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:89",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_store_iostats",
        "block/blk-sysfs.c:queue_store_random",
        "block/blk-sysfs.c:queue_store_nonrot",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:disable_discard",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583966224,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584354512,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:92",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_store_iostats",
        "block/blk-sysfs.c:queue_store_random",
        "block/blk-sysfs.c:queue_store_nonrot",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584354512,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584472416,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:91",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_stable_writes_store",
        "block/blk-sysfs.c:queue_iostats_store",
        "block/blk-sysfs.c:queue_random_store",
        "block/blk-sysfs.c:queue_nonrot_store",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-integrity.c:blk_integrity_unregister",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584472416,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584507328,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:92",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_stable_writes_store",
        "block/blk-sysfs.c:queue_iostats_store",
        "block/blk-sysfs.c:queue_random_store",
        "block/blk-sysfs.c:queue_nonrot_store",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-integrity.c:blk_integrity_unregister",
        "block/blk-zoned.c:blk_queue_clear_zone_settings",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_config_discard",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584507328,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584917984,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:90",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_stable_writes_store",
        "block/blk-sysfs.c:queue_iostats_store",
        "block/blk-sysfs.c:queue_random_store",
        "block/blk-sysfs.c:queue_nonrot_store",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/genhd.c:del_gendisk",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-integrity.c:blk_integrity_unregister",
        "block/blk-zoned.c:blk_queue_clear_zone_settings",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_config_discard",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/scsi/sd.c:sd_read_block_limits",
        "drivers/scsi/sd.c:sd_done",
        "drivers/scsi/sd.c:provisioning_mode_store",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584917984,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585619744,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:92",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_stable_writes_store",
        "block/blk-sysfs.c:queue_iostats_store",
        "block/blk-sysfs.c:queue_random_store",
        "block/blk-sysfs.c:queue_nonrot_store",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_unquiesce_queue",
        "block/blk-stat.c:blk_stat_disable_accounting",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/genhd.c:del_gendisk",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-integrity.c:blk_integrity_unregister",
        "block/blk-zoned.c:blk_queue_clear_zone_settings",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/md/md.c:hot_add_disk",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585619744,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586389856,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:90",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_disable",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_stable_writes_store",
        "block/blk-sysfs.c:queue_iostats_store",
        "block/blk-sysfs.c:queue_random_store",
        "block/blk-sysfs.c:queue_nonrot_store",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_unquiesce_queue",
        "block/blk-stat.c:blk_stat_disable_accounting",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/genhd.c:del_gendisk",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-integrity.c:blk_integrity_unregister",
        "block/blk-zoned.c:disk_clear_zone_settings",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/md/md.c:hot_add_disk",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586389856,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586636656,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:90",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_disable",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_stable_writes_store",
        "block/blk-sysfs.c:queue_iostats_store",
        "block/blk-sysfs.c:queue_random_store",
        "block/blk-sysfs.c:queue_nonrot_store",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_disable_accounting",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/genhd.c:del_gendisk",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-integrity.c:blk_integrity_unregister",
        "block/blk-zoned.c:disk_clear_zone_settings",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/md/md.c:hot_add_disk",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586636656,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586907536,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:91",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_disable",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_stable_writes_store",
        "block/blk-sysfs.c:queue_iostats_store",
        "block/blk-sysfs.c:queue_random_store",
        "block/blk-sysfs.c:queue_nonrot_store",
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_disable_accounting",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/genhd.c:del_gendisk",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-integrity.c:blk_integrity_unregister",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/md/md.c:hot_add_disk",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586907536,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495795344,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:89",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_store_iostats",
        "block/blk-sysfs.c:queue_store_random",
        "block/blk-sysfs.c:queue_store_nonrot",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:disable_discard",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495795344,
      "name": "blk_queue_flag_clear",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229147548,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:89",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_store_iostats",
        "block/blk-sysfs.c:queue_store_random",
        "block/blk-sysfs.c:queue_store_nonrot",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:disable_discard",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229147548,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289968368,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:89",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_store_iostats",
        "block/blk-sysfs.c:queue_store_random",
        "block/blk-sysfs.c:queue_store_nonrot",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:disable_discard",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289968368,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274931506,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:89",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_store_iostats",
        "block/blk-sysfs.c:queue_store_random",
        "block/blk-sysfs.c:queue_store_nonrot",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:disable_discard",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274931506,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583934960,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:89",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_store_iostats",
        "block/blk-sysfs.c:queue_store_random",
        "block/blk-sysfs.c:queue_store_nonrot",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/nvme/host/core.c:nvme_update_disk_info",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:disable_discard",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583934960,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583871904,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:89",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_store_iostats",
        "block/blk-sysfs.c:queue_store_random",
        "block/blk-sysfs.c:queue_store_nonrot",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/nvme/host/core.c:nvme_update_disk_info",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:disable_discard",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871904,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583918720,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:89",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_store_iostats",
        "block/blk-sysfs.c:queue_store_random",
        "block/blk-sysfs.c:queue_store_nonrot",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:disable_discard",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583918720,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_clear",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584020112,
      "name": "blk_queue_flag_clear",
      "external": true,
      "loc": "block/blk-core.c:89",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_rq_affinity_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_nomerges_store",
        "block/blk-sysfs.c:queue_store_iostats",
        "block/blk-sysfs.c:queue_store_random",
        "block/blk-sysfs.c:queue_store_nonrot",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-settings.c:blk_queue_write_cache",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:disable_discard",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020112,
      "name": "blk_queue_flag_clear",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void blk_queue_flag_clear(unsigned int flag, struct request_queue * q)
```
</details>
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
