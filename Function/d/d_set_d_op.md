# Function: <code>d_set_d_op</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581083968,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1662",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:__shmem_file_setup",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581083968,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581246928,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1698",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:__shmem_file_setup",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246928,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581324624,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1707",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:__shmem_file_setup",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581324624,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581379952,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1737",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379952,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581521392,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1749",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581521392,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581680336,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1757",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/hugetlbfs/inode.c:hugetlb_file_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680336,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581767056,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1760",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581767056,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581884080,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1834",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581884080,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956448,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1834",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956448,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582188944,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1855",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582188944,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582236448,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1862",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/libfs.c:generic_set_encrypted_ci_d_ops",
        "fs/libfs.c:generic_set_encrypted_ci_d_ops",
        "fs/libfs.c:generic_set_encrypted_ci_d_ops",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582236448,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582262192,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1889",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/libfs.c:generic_set_encrypted_ci_d_ops",
        "fs/libfs.c:generic_set_encrypted_ci_d_ops",
        "fs/libfs.c:generic_set_encrypted_ci_d_ops",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582262192,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582579984,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1890",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/libfs.c:generic_set_encrypted_ci_d_ops",
        "fs/libfs.c:generic_set_encrypted_ci_d_ops",
        "fs/libfs.c:generic_set_encrypted_ci_d_ops",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582579984,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583109936,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1915",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583109936,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583678208,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1915",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583678208,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583895872,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1915",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583895872,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584102864,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1775",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_alloc_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584102864,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493453192,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1834",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493453192,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227021560,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1834",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_fill_cache",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227021560,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287007936,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1834",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_fill_cache",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287007936,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273137040,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1834",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_fill_cache",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273137040,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581925184,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1834",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581925184,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581862768,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1834",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581862768,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581916496,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1834",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581916496,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void d_set_d_op(struct dentry * dentry, const struct dentry_operations * op)
```

```json
{
  "name": "d_set_d_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581986160,
      "name": "d_set_d_op",
      "external": true,
      "loc": "fs/dcache.c:1834",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file_pseudo",
        "fs/dcache.c:__d_alloc",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581986160,
      "name": "d_set_d_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
