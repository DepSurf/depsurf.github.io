# Function: <code>down_write_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579672352,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:60",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672352,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691120,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:82",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691120,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579718832,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:82",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_shmem",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718832,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579714688,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:83",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_shmem",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579714688,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579747296,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:100",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_shmem",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579747296,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579781664,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:100",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_shmem",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579781664,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579828304,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:100",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_shmem",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828304,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859744,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1526",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_shmem",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859744,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908432,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1560",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908432,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952288,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1557",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:retract_page_tables",
        "fs/locks.c:generic_add_lease",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952288,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579942272,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1432",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:retract_page_tables",
        "fs/locks.c:generic_add_lease",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942272,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579949984,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1432",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:retract_page_tables",
        "fs/locks.c:generic_add_lease",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949984,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580079184,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1549",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:retract_page_tables",
        "fs/locks.c:generic_add_lease",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580079184,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580215328,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1578",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:retract_page_tables",
        "fs/locks.c:generic_add_lease",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_dev_set_hot_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215328,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580407952,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1599",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/hugetlb.c:hugetlb_vma_trylock_write",
        "mm/khugepaged.c:retract_page_tables",
        "fs/locks.c:generic_add_lease",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580407952,
      "name": "down_write_trylock",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580476720,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1599",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/hugetlb.c:hugetlb_vma_trylock_write",
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:retract_page_tables",
        "fs/locks.c:generic_add_lease",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580476720,
      "name": "down_write_trylock",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580536544,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1605",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/hugetlb.c:hugetlb_vma_trylock_write",
        "mm/hugetlb.c:hugetlb_vma_trylock_write",
        "mm/userfaultfd.c:move_pages_pte",
        "fs/locks.c:generic_add_lease",
        "fs/ext4/file.c:ext4_dax_write_iter",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty",
        "fs/fuse/dax.c:fuse_dax_write_iter",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580536544,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491110352,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1560",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_file",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491110352,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225116768,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1560",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_mark_inode_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225116768,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284001568,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1560",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_mark_inode_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284001568,
      "name": "down_write_trylock",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271689836,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1560",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_mark_inode_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271689836,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880544,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1560",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880544,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815536,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1560",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815536,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579868704,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1560",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868704,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int down_write_trylock(struct rw_semaphore * sem)
```

```json
{
  "name": "down_write_trylock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579914128,
      "name": "down_write_trylock",
      "external": true,
      "loc": "kernel/locking/rwsem.c:1560",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_file",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "drivers/acpi/cppc_acpi.c:cppc_set_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914128,
      "name": "down_write_trylock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
