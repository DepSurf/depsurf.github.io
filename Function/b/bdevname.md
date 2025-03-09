# Function: <code>bdevname</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582831056,
      "name": "bdevname",
      "external": true,
      "loc": "block/partition-generic.c:46",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/super.c:mount_bdev",
        "fs/buffer.c:do_thaw_one",
        "fs/buffer.c:__find_get_block_slow",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_table_any_congested"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582831056,
      "name": "bdevname",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583110672,
      "name": "bdevname",
      "external": true,
      "loc": "block/partition-generic.c:47",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583110672,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583222176,
      "name": "bdevname",
      "external": true,
      "loc": "block/partition-generic.c:47",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583222176,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583276208,
      "name": "bdevname",
      "external": true,
      "loc": "block/partition-generic.c:46",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583276208,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583456464,
      "name": "bdevname",
      "external": true,
      "loc": "block/partition-generic.c:47",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583456464,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583667872,
      "name": "bdevname",
      "external": true,
      "loc": "block/partition-generic.c:47",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:device_no_partial_completion",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583667872,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583774976,
      "name": "bdevname",
      "external": true,
      "loc": "block/partition-generic.c:47",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:device_no_partial_completion",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583774976,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583964816,
      "name": "bdevname",
      "external": true,
      "loc": "block/partition-generic.c:47",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:device_no_partial_completion",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964816,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584068176,
      "name": "bdevname",
      "external": true,
      "loc": "block/partition-generic.c:47",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:device_no_partial_completion",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584068176,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584456992,
      "name": "bdevname",
      "external": true,
      "loc": "block/genhd.c:89",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:bdev_write_inode",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/blk-settings.c:disk_stack_limits",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:hot_add_disk",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:analyze_sbs",
        "drivers/md/md.c:analyze_sbs",
        "drivers/md/md.c:analyze_sbs",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:device_no_partial_completion",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584456992,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584573840,
      "name": "bdevname",
      "external": true,
      "loc": "block/genhd.c:106",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:bdev_write_inode",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/blk-settings.c:disk_stack_limits",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:hot_add_disk",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:md_add_new_disk",
        "drivers/md/md.c:md_add_new_disk",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:analyze_sbs",
        "drivers/md/md.c:analyze_sbs",
        "drivers/md/md.c:analyze_sbs",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584573840,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584604816,
      "name": "bdevname",
      "external": true,
      "loc": "block/genhd.c:103",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/bio.c:bio_devname",
        "block/blk-settings.c:disk_stack_limits",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:hot_add_disk",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:md_add_new_disk",
        "drivers/md/md.c:md_add_new_disk",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:analyze_sbs",
        "drivers/md/md.c:analyze_sbs",
        "drivers/md/md.c:analyze_sbs",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584604816,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bdevname",
      "external": true,
      "loc": "block/genhd.c:107",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bio.c:bio_devname",
        "block/blk-lib.c:__blkdev_issue_discard",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:hot_add_disk",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:md_add_new_disk",
        "drivers/md/md.c:md_add_new_disk",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:analyze_sbs",
        "drivers/md/md.c:analyze_sbs",
        "drivers/md/md.c:analyze_sbs",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592315000,
      "name": "bdevname.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585015728,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bdevname",
      "external": true,
      "loc": "block/genhd.c:111",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/bdev.c:blkdev_flush_mapping",
        "block/blk-lib.c:__blkdev_issue_discard",
        "drivers/md/md.c:bind_rdev_to_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594099472,
      "name": "bdevname.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585731712,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
    }
  ]
}
```
</details>
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
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495911448,
      "name": "bdevname",
      "external": true,
      "loc": "block/partition-generic.c:47",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:device_no_partial_completion",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495911448,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229253960,
      "name": "bdevname",
      "external": true,
      "loc": "block/partition-generic.c:47",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:autorun_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:device_no_partial_completion",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229253960,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290120704,
      "name": "bdevname",
      "external": true,
      "loc": "block/partition-generic.c:47",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:device_no_partial_completion",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290120704,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275025508,
      "name": "bdevname",
      "external": true,
      "loc": "block/partition-generic.c:47",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:device_no_partial_completion",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275025508,
      "name": "bdevname",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584036912,
      "name": "bdevname",
      "external": true,
      "loc": "block/partition-generic.c:47",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:device_no_partial_completion",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584036912,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583972672,
      "name": "bdevname",
      "external": true,
      "loc": "block/partition-generic.c:47",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:device_no_partial_completion",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972672,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584020672,
      "name": "bdevname",
      "external": true,
      "loc": "block/partition-generic.c:47",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:device_no_partial_completion",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020672,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
const char * bdevname(struct block_device * bdev, char * buf)
```

```json
{
  "name": "bdevname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584123216,
      "name": "bdevname",
      "external": true,
      "loc": "block/partition-generic.c:47",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "kernel/trace/blktrace.c:blk_trace_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/mmp.c:kmmpd",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__bdev_dax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_seq_show",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:export_rdev",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/md.c:super_1_load",
        "drivers/md/dm-table.c:dm_table_any_congested",
        "drivers/md/dm-table.c:device_no_partial_completion",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:dm_set_device_limits",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid",
        "drivers/md/dm-table.c:device_area_is_invalid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123216,
      "name": "bdevname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
const char * bdevname(struct block_device * bdev, char * buf)
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
