# Function: <code>congestion_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580608304,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:931",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:throttle_vm_writeout",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580608304,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580711680,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:950",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page-writeback.c:throttle_vm_writeout",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/extents.c:ext4_ext_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580711680,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580777504,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:956",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/extents.c:ext4_ext_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580777504,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580813312,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:1001",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580813312,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580903408,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:1016",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580903408,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581039312,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:1014",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581039312,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581116896,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:1017",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581116896,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581181520,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:1004",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581181520,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581239648,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:1085",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581239648,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581428640,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:1083",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581428640,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581471888,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:952",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581471888,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581492032,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:951",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581492032,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581750896,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:1034",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581750896,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
    }
  ]
}
```
</details>
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492635944,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:1085",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492635944,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226480972,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:1085",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226480972,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285953280,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:1085",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285953280,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272653998,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:1085",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272653998,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581208496,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:1085",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581208496,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581155248,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:1085",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581155248,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581199696,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:1085",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581199696,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
long int congestion_wait(int sync, long int timeout)
```

```json
{
  "name": "congestion_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581262976,
      "name": "congestion_wait",
      "external": true,
      "loc": "mm/backing-dev.c:1085",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:do_writepages",
        "mm/vmscan.c:shrink_node",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/memcontrol.c:mem_cgroup_force_empty_write",
        "fs/ext4/extents.c:ext4_ext_truncate",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581262976,
      "name": "congestion_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
long int congestion_wait(int sync, long int timeout)
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
