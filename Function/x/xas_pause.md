# Function: <code>xas_pause</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589424064,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:944",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_layout_busy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589424064,
      "name": "xas_pause",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589881680,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:963",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_layout_busy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589881680,
      "name": "xas_pause",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590107600,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:964",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_layout_busy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590107600,
      "name": "xas_pause",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585110672,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:964",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_layout_busy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585110672,
      "name": "xas_pause",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585259856,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:1114",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_layout_busy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585259856,
      "name": "xas_pause",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585143456,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:1115",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_layout_busy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585143456,
      "name": "xas_pause",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:1115",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_layout_busy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592344517,
      "name": "xas_pause.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585593904,
      "name": "xas_pause",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:1122",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/khugepaged.c:khugepaged_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_layout_busy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594206103,
      "name": "xas_pause.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071586750240,
      "name": "xas_pause",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:1122",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_layout_busy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596375069,
      "name": "xas_pause.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071595914048,
      "name": "xas_pause",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:1120",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "mm/filemap.c:filemap_cachestat",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/madvise.c:shmem_swapin_range",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_layout_busy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596904590,
      "name": "xas_pause.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071596431824,
      "name": "xas_pause",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:1120",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_may_map",
        "mm/filemap.c:filemap_cachestat",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/madvise.c:shmem_swapin_range",
        "mm/khugepaged.c:hpage_collapse_scan_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_iomap_iter",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_layout_busy_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597829683,
      "name": "xas_pause.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071597327184,
      "name": "xas_pause",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503889080,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:964",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_layout_busy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503889080,
      "name": "xas_pause",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236517740,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:964",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236517740,
      "name": "xas_pause",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297754272,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:964",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_layout_busy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297754272,
      "name": "xas_pause",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279779806,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:964",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_layout_busy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279779806,
      "name": "xas_pause",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589709856,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:964",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_layout_busy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589709856,
      "name": "xas_pause",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589435648,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:964",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_layout_busy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589435648,
      "name": "xas_pause",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590153232,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:964",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_layout_busy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590153232,
      "name": "xas_pause",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void xas_pause(struct xa_state * xas)
```

```json
{
  "name": "xas_pause",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590203632,
      "name": "xas_pause",
      "external": true,
      "loc": "lib/xarray.c:964",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:tag_pages_for_writeback",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_partial_swap_usage",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:dax_layout_busy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590203632,
      "name": "xas_pause",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void xas_pause(struct xa_state * xas)
```
</details>
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
