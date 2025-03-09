# Function: <code>blk_queue_flag_set</code>

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
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583553456,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:79",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_queue_dying",
        "block/blk-sysfs.c:queue_wc_store",
        "block/blk-sysfs.c:queue_poll_store",
        "block/blk-sysfs.c:queue_store_iostats",
        "block/blk-sysfs.c:queue_store_random",
        "block/blk-sysfs.c:queue_store_nonrot",
        "block/blk-settings.c:blk_queue_flush_queueable",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/scsi_lib.c:scsi_old_alloc_queue",
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
      "addr": 18446744071583553456,
      "name": "blk_queue_flag_set",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583688582,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:75",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_set_queue_dying"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/bsg-lib.c:bsg_setup_queue",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
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
      "addr": 18446744071583674592,
      "name": "blk_queue_flag_set",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583872390,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:76",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_set_queue_dying"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583863312,
      "name": "blk_queue_flag_set",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583975286,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:78",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_set_queue_dying"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583966192,
      "name": "blk_queue_flag_set",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584362742,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:81",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_set_queue_dying"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584354480,
      "name": "blk_queue_flag_set",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584479563,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:80",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_set_queue_dying"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-integrity.c:blk_integrity_register",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
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
      "addr": 18446744071584472384,
      "name": "blk_queue_flag_set",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584514187,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:81",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_set_queue_dying"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-integrity.c:blk_integrity_register",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_config_discard",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
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
      "addr": 18446744071584507296,
      "name": "blk_queue_flag_set",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584927315,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:79",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-integrity.c:blk_integrity_register",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_config_discard",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/md.c:md_run",
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
      "addr": 18446744071584917952,
      "name": "blk_queue_flag_set",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585632659,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:81",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "block/mq-deadline.c:dd_init_sched",
        "block/blk-integrity.c:blk_integrity_register",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
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
      "addr": 18446744071585619712,
      "name": "blk_queue_flag_set",
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
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586389808,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:79",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_destroy_queue",
        "block/blk-mq.c:blk_mq_quiesce_tagset",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/genhd.c:del_gendisk",
        "block/blk-iocost.c:ioc_qos_write",
        "block/mq-deadline.c:dd_init_sched",
        "block/blk-integrity.c:blk_integrity_register",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
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
      "addr": 18446744071586389808,
      "name": "blk_queue_flag_set",
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
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586636608,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:79",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_destroy_queue",
        "block/blk-mq.c:blk_mq_quiesce_tagset",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/genhd.c:blk_mark_disk_dead",
        "block/blk-iocost.c:ioc_qos_write",
        "block/mq-deadline.c:dd_init_sched",
        "block/blk-integrity.c:blk_integrity_register",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/virtio_blk.c:virtblk_probe_zoned_device",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_setup_md_queue",
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
      "addr": 18446744071586636608,
      "name": "blk_queue_flag_set",
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
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586907488,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:80",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_destroy_queue",
        "block/blk-mq.c:blk_mq_quiesce_tagset",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/genhd.c:__blk_mark_disk_dead",
        "block/blk-iocost.c:ioc_qos_write",
        "block/mq-deadline.c:dd_init_sched",
        "block/blk-integrity.c:blk_integrity_register",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/virtio_blk.c:virtblk_probe_zoned_device",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_block_characteristics",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/dm.c:dm_setup_md_queue",
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
      "addr": 18446744071586907488,
      "name": "blk_queue_flag_set",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495795884,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:78",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_set_queue_dying"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/mmc/core/queue.c:mmc_init_queue",
        "drivers/mmc/core/queue.c:mmc_init_queue",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495795256,
      "name": "blk_queue_flag_set",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229148112,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:78",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_set_queue_dying"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev",
        "drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/mmc/core/queue.c:mmc_init_queue",
        "drivers/mmc/core/queue.c:mmc_init_queue",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229147516,
      "name": "blk_queue_flag_set",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289979512,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:78",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_set_queue_dying"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289968288,
      "name": "blk_queue_flag_set",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274937468,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:78",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_set_queue_dying"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/mmc/core/queue.c:mmc_init_queue",
        "drivers/mmc/core/queue.c:mmc_init_queue",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274931430,
      "name": "blk_queue_flag_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583944022,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:78",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_set_queue_dying"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583934928,
      "name": "blk_queue_flag_set",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583880966,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:78",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_set_queue_dying"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/nvdimm/pmem.c:pmem_attach_disk",
        "drivers/nvdimm/pmem.c:pmem_attach_disk",
        "drivers/nvdimm/blk.c:nd_blk_probe",
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871872,
      "name": "blk_queue_flag_set",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583927782,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:78",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_set_queue_dying"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583918688,
      "name": "blk_queue_flag_set",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
```

```json
{
  "name": "blk_queue_flag_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584029174,
      "name": "blk_queue_flag_set",
      "external": true,
      "loc": "block/blk-core.c:78",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_set_queue_dying"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
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
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_quiesce_queue",
        "block/blk-stat.c:blk_stat_enable_accounting",
        "block/blk-stat.c:blk_stat_add_callback",
        "block/blk-iocost.c:ioc_qos_write",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:__loop_update_dio",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_config_discard",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/md/md.c:md_run",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020080,
      "name": "blk_queue_flag_set",
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
void blk_queue_flag_set(unsigned int flag, struct request_queue * q)
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
