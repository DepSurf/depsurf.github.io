# Function: <code>strscpy_pad</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strscpy_pad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589861488,
      "name": "strscpy_pad",
      "external": true,
      "loc": "lib/string.c:259",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589861488,
      "name": "strscpy_pad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strscpy_pad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590087296,
      "name": "strscpy_pad",
      "external": true,
      "loc": "lib/string.c:261",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590087296,
      "name": "strscpy_pad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strscpy_pad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585085152,
      "name": "strscpy_pad",
      "external": true,
      "loc": "lib/string.c:261",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585085152,
      "name": "strscpy_pad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strscpy_pad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585234288,
      "name": "strscpy_pad",
      "external": true,
      "loc": "lib/string.c:260",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585234288,
      "name": "strscpy_pad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strscpy_pad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585117120,
      "name": "strscpy_pad",
      "external": true,
      "loc": "lib/string.c:260",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585117120,
      "name": "strscpy_pad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strscpy_pad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585565840,
      "name": "strscpy_pad",
      "external": true,
      "loc": "lib/string.c:261",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585565840,
      "name": "strscpy_pad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strscpy_pad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586106832,
      "name": "strscpy_pad",
      "external": true,
      "loc": "lib/string_helpers.c:787",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:get_kthread_comm",
        "fs/exec.c:__set_task_comm",
        "fs/exec.c:__get_task_comm",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586106832,
      "name": "strscpy_pad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strscpy_pad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587092208,
      "name": "strscpy_pad",
      "external": true,
      "loc": "lib/string_helpers.c:831",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kthread.c:get_kthread_comm",
        "fs/exec.c:__set_task_comm",
        "fs/exec.c:__get_task_comm",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587092208,
      "name": "strscpy_pad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strscpy_pad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587352320,
      "name": "strscpy_pad",
      "external": true,
      "loc": "lib/string_helpers.c:831",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/kthread.c:get_kthread_comm",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "fs/exec.c:__set_task_comm",
        "fs/exec.c:__get_task_comm",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587352320,
      "name": "strscpy_pad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strscpy_pad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587638640,
      "name": "strscpy_pad",
      "external": true,
      "loc": "lib/string_helpers.c:848",
      "file": "lib/string_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/kthread.c:get_kthread_comm",
        "kernel/bpf/helpers.c:bpf_get_current_comm",
        "fs/exec.c:__set_task_comm",
        "fs/exec.c:__get_task_comm",
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_flush_foreign",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:perf_trace_inode_switch_wbs",
        "fs/fs-writeback.c:perf_trace_inode_foreign_history",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:perf_trace_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_flush_foreign",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_inode_switch_wbs",
        "fs/fs-writeback.c:trace_event_raw_event_inode_foreign_history",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_folio_template",
        "drivers/gpu/drm/drm_modes.c:drm_mode_convert_umode",
        "drivers/gpu/drm/drm_modes.c:drm_mode_convert_to_umode",
        "drivers/gpu/drm/drm_property.c:drm_mode_getproperty_ioctl",
        "drivers/gpu/drm/drm_property.c:drm_property_add_enum",
        "drivers/gpu/drm/drm_property.c:drm_property_create",
        "drivers/md/dm-ioctl.c:retrieve_status",
        "net/core/dev_ioctl.c:generic_hwtstamp_ioctl_lower"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587638640,
      "name": "strscpy_pad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strscpy_pad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503865504,
      "name": "strscpy_pad",
      "external": true,
      "loc": "lib/string.c:261",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503865504,
      "name": "strscpy_pad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strscpy_pad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236493184,
      "name": "strscpy_pad",
      "external": true,
      "loc": "lib/string.c:261",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "sound/soc/soc-generic-dmaengine-pcm.c:dmaengine_pcm_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236493184,
      "name": "strscpy_pad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strscpy_pad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297724720,
      "name": "strscpy_pad",
      "external": true,
      "loc": "lib/string.c:261",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297724720,
      "name": "strscpy_pad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strscpy_pad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279761294,
      "name": "strscpy_pad",
      "external": true,
      "loc": "lib/string.c:261",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279761294,
      "name": "strscpy_pad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strscpy_pad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589689552,
      "name": "strscpy_pad",
      "external": true,
      "loc": "lib/string.c:261",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589689552,
      "name": "strscpy_pad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strscpy_pad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589415344,
      "name": "strscpy_pad",
      "external": true,
      "loc": "lib/string.c:261",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589415344,
      "name": "strscpy_pad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strscpy_pad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590132928,
      "name": "strscpy_pad",
      "external": true,
      "loc": "lib/string.c:261",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590132928,
      "name": "strscpy_pad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strscpy_pad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590183312,
      "name": "strscpy_pad",
      "external": true,
      "loc": "lib/string.c:261",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:perf_trace_writeback_single_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:perf_trace_balance_dirty_pages",
        "fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:perf_trace_writeback_queue_io",
        "fs/fs-writeback.c:perf_trace_wbc_class",
        "fs/fs-writeback.c:perf_trace_writeback_bdi_register",
        "fs/fs-writeback.c:perf_trace_writeback_class",
        "fs/fs-writeback.c:perf_trace_writeback_work_class",
        "fs/fs-writeback.c:perf_trace_writeback_write_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_dirty_inode_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:perf_trace_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue",
        "fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages",
        "fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io",
        "fs/fs-writeback.c:trace_event_raw_event_wbc_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_bdi_register",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_work_class",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_dirty_inode_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template",
        "fs/fs-writeback.c:trace_event_raw_event_writeback_page_template"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590183312,
      "name": "strscpy_pad",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
ssize_t strscpy_pad(char * dest, const char * src, size_t count)
```
</details>
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
