# Function: <code>igrab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581104720,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1191",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "fs/notify/inode_mark.c:fsnotify_set_inode_mark_mask_locked",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fat/inode.c:fat_iget",
        "fs/fat/nfs.c:fat_dget",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581104720,
      "name": "igrab",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581270128,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1200",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "kernel/events/core.c:perf_event_set_addr_filter",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/inode_mark.c:fsnotify_set_inode_mark_mask_locked",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fat/inode.c:fat_iget",
        "fs/fat/nfs.c:fat_dget",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581270128,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581348112,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1218",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "kernel/events/core.c:perf_event_set_addr_filter",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/inode_mark.c:fsnotify_set_inode_mark_mask_locked",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/fat/inode.c:fat_iget",
        "fs/fat/nfs.c:fat_dget",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581348112,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581403504,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1219",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fat/inode.c:fat_iget",
        "fs/fat/nfs.c:fat_dget",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:dax_get_by_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581403504,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581545120,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1219",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:create_trace_uprobe",
        "kernel/events/core.c:perf_event_parse_addr_filter",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fat/inode.c:fat_iget",
        "fs/fat/nfs.c:fat_dget",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:dax_get_by_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581545120,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581701552,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1240",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:dax_get_by_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581701552,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581788160,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1271",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:dax_get_by_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581788160,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581906688,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1284",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/mark.c:fsnotify_add_mark_list",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:dax_get_by_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581906688,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581979184,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1295",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:dax_get_by_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581979184,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582212160,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1293",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/mark.c:fsnotify_add_mark_list",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fat/inode.c:fat_iget",
        "fs/fat/nfs.c:fat_dget",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:dax_get_by_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582212160,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582259664,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1292",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/block_dev.c:__blkdev_get",
        "fs/notify/mark.c:fsnotify_add_mark_list",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fat/inode.c:fat_iget",
        "fs/fat/nfs.c:fat_dget",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:dax_get_by_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582259664,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582285248,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1299",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/block_dev.c:__blkdev_get",
        "fs/notify/mark.c:fsnotify_add_mark_list",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fat/inode.c:fat_iget",
        "fs/fat/nfs.c:fat_dget",
        "fs/fuse/file.c:fuse_file_release",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:dax_get_by_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582285248,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582603728,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1303",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/fat/inode.c:fat_iget",
        "fs/fat/nfs.c:fat_dget",
        "fs/fuse/file.c:fuse_file_release",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:dax_get_by_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582603728,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583128336,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1384",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/fat/inode.c:fat_iget",
        "fs/fat/nfs.c:fat_dget",
        "fs/fuse/file.c:fuse_file_release",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:fs_dax_get_by_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583128336,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583698688,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1386",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/fat/inode.c:fat_iget",
        "fs/fat/nfs.c:fat_dget",
        "fs/fuse/file.c:fuse_file_release",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:fs_dax_get_by_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583698688,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583916560,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1430",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fat/inode.c:fat_iget",
        "fs/fat/nfs.c:fat_dget",
        "fs/fuse/file.c:fuse_file_release",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:fs_dax_get_by_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583916560,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584122336,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1378",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/proc/inode.c:proc_invalidate_siblings_dcache",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fat/inode.c:fat_iget",
        "fs/fat/nfs.c:fat_dget",
        "fs/fuse/file.c:fuse_file_release",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:fs_dax_get_by_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584122336,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493485984,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1295",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/mark.c:fsnotify_add_mark_list",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:dax_get_by_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493485984,
      "name": "igrab",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227048028,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1295",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_list",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fat/inode.c:fat_iget",
        "fs/fat/nfs.c:fat_dget",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:dax_get_by_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227048028,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287046160,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1295",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/mark.c:fsnotify_add_mark_list",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fat/inode.c:fat_iget",
        "fs/fat/nfs.c:fat_dget",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:dax_get_by_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287046160,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273163280,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1295",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_add_mark_list",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:dax_get_by_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273163280,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581947920,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1295",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:dax_get_by_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581947920,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581885488,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1295",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:dax_get_by_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885488,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581939232,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1295",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:dax_get_by_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581939232,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct inode * igrab(struct inode * inode)
```

```json
{
  "name": "igrab",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582003632,
      "name": "igrab",
      "external": true,
      "loc": "fs/inode.c:1295",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_unused_huge_shrink",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/fdinfo.c:fanotify_fdinfo",
        "fs/notify/fdinfo.c:inotify_fdinfo",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/super.c:ext4_quota_off",
        "fs/fuse/file.c:fuse_release_common",
        "security/selinux/hooks.c:sb_finish_set_opts",
        "drivers/dax/super.c:dax_get_by_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582003632,
      "name": "igrab",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
