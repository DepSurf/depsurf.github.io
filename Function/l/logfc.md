# Function: <code>logfc</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void logfc(struct fs_context * fc, const char * fmt, void (anon))
```

```json
{
  "name": "logfc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "logfc",
      "external": true,
      "loc": "fs/fs_context.c:390",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/root.c:proc_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582035542,
      "name": "logfc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071582031776,
      "name": "logfc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
void logfc(struct fs_context * fc, const char * fmt, void (anon))
```

```json
{
  "name": "logfc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "logfc",
      "external": true,
      "loc": "fs/fs_context.c:388",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/root.c:proc_parse_param",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582113318,
      "name": "logfc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071582109712,
      "name": "logfc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
void logfc(struct fc_log * log, const char * prefix, char level, const char * fmt, void (anon))
```

```json
{
  "name": "logfc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "logfc",
      "external": true,
      "loc": "fs/fs_context.c:362",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_parser.c:fs_param_is_fd",
        "fs/fs_parser.c:fs_param_is_blob",
        "fs/fs_parser.c:fs_param_is_string",
        "fs/fs_parser.c:fs_param_is_u64",
        "fs/fs_parser.c:fs_param_is_s32",
        "fs/fs_parser.c:fs_param_is_u32",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:__fs_parse",
        "fs/fs_parser.c:__fs_parse",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582350313,
      "name": "logfc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071582346608,
      "name": "logfc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
void logfc(struct fc_log * log, const char * prefix, char level, const char * fmt, void (anon))
```

```json
{
  "name": "logfc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "logfc",
      "external": true,
      "loc": "fs/fs_context.c:362",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_parser.c:fs_param_is_fd",
        "fs/fs_parser.c:fs_param_is_blob",
        "fs/fs_parser.c:fs_param_is_string",
        "fs/fs_parser.c:fs_param_is_u64",
        "fs/fs_parser.c:fs_param_is_s32",
        "fs/fs_parser.c:fs_param_is_u32",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:__fs_parse",
        "fs/fs_parser.c:__fs_parse",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591340235,
      "name": "logfc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071582398240,
      "name": "logfc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
void logfc(struct fc_log * log, const char * prefix, char level, const char * fmt, void (anon))
```

```json
{
  "name": "logfc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "logfc",
      "external": true,
      "loc": "fs/fs_context.c:362",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_parser.c:fs_param_is_fd",
        "fs/fs_parser.c:fs_param_is_blob",
        "fs/fs_parser.c:fs_param_is_string",
        "fs/fs_parser.c:fs_param_is_u64",
        "fs/fs_parser.c:fs_param_is_s32",
        "fs/fs_parser.c:fs_param_is_u32",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:__fs_parse",
        "fs/fs_parser.c:__fs_parse",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591282912,
      "name": "logfc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071582425520,
      "name": "logfc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void logfc(struct fc_log * log, const char * prefix, char level, const char * fmt, void (anon))
```

```json
{
  "name": "logfc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "logfc",
      "external": true,
      "loc": "fs/fs_context.c:385",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:vfs_parse_fs_param_source",
        "fs/fs_context.c:vfs_parse_fs_param_source",
        "fs/fs_parser.c:fs_param_is_fd",
        "fs/fs_parser.c:fs_param_is_blob",
        "fs/fs_parser.c:fs_param_is_string",
        "fs/fs_parser.c:fs_param_is_u64",
        "fs/fs_parser.c:fs_param_is_s32",
        "fs/fs_parser.c:fs_param_is_u32",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:__fs_parse",
        "fs/fs_parser.c:__fs_parse",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592231342,
      "name": "logfc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071582748384,
      "name": "logfc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
void logfc(struct fc_log * log, const char * prefix, char level, const char * fmt, void (anon))
```

```json
{
  "name": "logfc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "logfc",
      "external": true,
      "loc": "fs/fs_context.c:385",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:vfs_parse_fs_param",
        "fs/fs_context.c:vfs_parse_fs_param",
        "fs/fs_context.c:vfs_parse_fs_param_source",
        "fs/fs_context.c:vfs_parse_fs_param_source",
        "fs/fs_parser.c:fs_param_is_fd",
        "fs/fs_parser.c:fs_param_is_blob",
        "fs/fs_parser.c:fs_param_is_string",
        "fs/fs_parser.c:fs_param_is_u32",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:__fs_parse",
        "fs/fs_parser.c:__fs_parse",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594011326,
      "name": "logfc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071583295728,
      "name": "logfc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
void logfc(struct fc_log * log, const char * prefix, char level, const char * fmt, void (anon))
```

```json
{
  "name": "logfc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583880288,
      "name": "logfc",
      "external": true,
      "loc": "fs/fs_context.c:385",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:vfs_parse_fs_param",
        "fs/fs_context.c:vfs_parse_fs_param",
        "fs/fs_context.c:vfs_parse_fs_param_source",
        "fs/fs_context.c:vfs_parse_fs_param_source",
        "fs/fs_parser.c:fs_param_is_fd",
        "fs/fs_parser.c:fs_param_is_blob",
        "fs/fs_parser.c:fs_param_is_string",
        "fs/fs_parser.c:fs_param_is_u32",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:__fs_parse",
        "fs/fs_parser.c:__fs_parse",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583880288,
      "name": "logfc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
void logfc(struct fc_log * log, const char * prefix, char level, const char * fmt, void (anon))
```

```json
{
  "name": "logfc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584101952,
      "name": "logfc",
      "external": true,
      "loc": "fs/fs_context.c:406",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:vfs_parse_fs_param",
        "fs/fs_context.c:vfs_parse_fs_param",
        "fs/fs_context.c:vfs_parse_fs_param_source",
        "fs/fs_context.c:vfs_parse_fs_param_source",
        "fs/fs_parser.c:fs_param_is_fd",
        "fs/fs_parser.c:fs_param_is_blob",
        "fs/fs_parser.c:fs_param_is_string",
        "fs/fs_parser.c:fs_param_is_u32",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:__fs_parse",
        "fs/fs_parser.c:__fs_parse",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584101952,
      "name": "logfc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
void logfc(struct fc_log * log, const char * prefix, char level, const char * fmt, void (anon))
```

```json
{
  "name": "logfc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584318096,
      "name": "logfc",
      "external": true,
      "loc": "fs/fs_context.c:436",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/bpf/inode.c:bpf_parse_param",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:setup_bdev_super",
        "fs/super.c:setup_bdev_super",
        "fs/super.c:sget_fc",
        "fs/super.c:sget_fc",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:vfs_parse_fs_param",
        "fs/fs_context.c:vfs_parse_fs_param",
        "fs/fs_context.c:vfs_parse_fs_param_source",
        "fs/fs_context.c:vfs_parse_fs_param_source",
        "fs/fs_parser.c:fs_param_is_fd",
        "fs/fs_parser.c:fs_param_is_blob",
        "fs/fs_parser.c:fs_param_is_string",
        "fs/fs_parser.c:fs_param_is_u32",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:__fs_parse",
        "fs/fs_parser.c:__fs_parse",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/proc/root.c:proc_parse_param",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584318096,
      "name": "logfc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
void logfc(struct fs_context * fc, const char * fmt, void (anon))
```

```json
{
  "name": "logfc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493649776,
      "name": "logfc",
      "external": true,
      "loc": "fs/fs_context.c:388",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/root.c:proc_parse_param",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493649776,
      "name": "logfc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
void logfc(struct fs_context * fc, const char * fmt, void (anon))
```

```json
{
  "name": "logfc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227184464,
      "name": "logfc",
      "external": true,
      "loc": "fs/fs_context.c:388",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/root.c:proc_parse_param",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "drivers/mtd/mtdsuper.c:get_tree_mtd",
        "drivers/mtd/mtdsuper.c:get_tree_mtd",
        "drivers/mtd/mtdsuper.c:get_tree_mtd",
        "drivers/mtd/mtdsuper.c:get_tree_mtd",
        "drivers/mtd/mtdsuper.c:mtd_get_sb_by_nr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227184464,
      "name": "logfc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
void logfc(struct fs_context * fc, const char * fmt, void (anon))
```

```json
{
  "name": "logfc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287242112,
      "name": "logfc",
      "external": true,
      "loc": "fs/fs_context.c:388",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/root.c:proc_parse_param",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287242112,
      "name": "logfc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 712
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
void logfc(struct fs_context * fc, const char * fmt, void (anon))
```

```json
{
  "name": "logfc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273281404,
      "name": "logfc",
      "external": true,
      "loc": "fs/fs_context.c:388",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/root.c:proc_parse_param",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273281404,
      "name": "logfc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
void logfc(struct fs_context * fc, const char * fmt, void (anon))
```

```json
{
  "name": "logfc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "logfc",
      "external": true,
      "loc": "fs/fs_context.c:388",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/root.c:proc_parse_param",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582082054,
      "name": "logfc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071582078448,
      "name": "logfc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
void logfc(struct fs_context * fc, const char * fmt, void (anon))
```

```json
{
  "name": "logfc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "logfc",
      "external": true,
      "loc": "fs/fs_context.c:388",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/root.c:proc_parse_param",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019574,
      "name": "logfc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071582015968,
      "name": "logfc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
void logfc(struct fs_context * fc, const char * fmt, void (anon))
```

```json
{
  "name": "logfc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "logfc",
      "external": true,
      "loc": "fs/fs_context.c:388",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/root.c:proc_parse_param",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582073334,
      "name": "logfc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071582069728,
      "name": "logfc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
void logfc(struct fs_context * fc, const char * fmt, void (anon))
```

```json
{
  "name": "logfc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "logfc",
      "external": true,
      "loc": "fs/fs_context.c:388",
      "file": "fs/fs_context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:check_cgroupfs_options",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "kernel/cgroup/cgroup-v1.c:cgroup1_parse_param",
        "mm/shmem.c:shmem_reconfigure",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_lookup_param",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/fs_parser.c:fs_parse",
        "fs/proc/root.c:proc_parse_param",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param",
        "fs/fuse/inode.c:fuse_parse_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582145094,
      "name": "logfc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071582141488,
      "name": "logfc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
void logfc(struct fs_context * fc, const char * fmt, void (anon))
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fc_log * log</code>
</li>
<li>
<b>Param added. </b>
<code>const char * prefix</code>
</li>
<li>
<b>Param added. </b>
<code>char level</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fs_context * fc</code>
</li>
<li>
<b>Param reordered. </b>
<code>fc, fmt, (anon)</code> ➡️ <code>log, prefix, level, fmt, (anon)</code>
</li>
</ul>
</details>
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
