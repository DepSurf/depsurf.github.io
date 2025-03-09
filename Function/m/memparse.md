# Function: <code>memparse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582945408,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:127",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:parse_reservelow",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "arch/x86/mm/hugetlbpage.c:setup_hugepagesz",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/page_alloc.c:cmdline_parse_kernelcore",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/hugetlb.c:hugetlb_default_setup",
        "mm/page_counter.c:page_counter_memparse",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:store_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582945408,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583232640,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:127",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:parse_reservelow",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "arch/x86/mm/hugetlbpage.c:setup_hugepagesz",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/hugetlb.c:hugetlb_default_setup",
        "mm/page_counter.c:page_counter_memparse",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:store_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583232640,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583347696,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:127",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:parse_reservelow",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "arch/x86/mm/hugetlbpage.c:setup_hugepagesz",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/hugetlb.c:hugetlb_default_setup",
        "mm/page_counter.c:page_counter_memparse",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:store_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583347696,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588198720,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:128",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:parse_reservelow",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "arch/x86/mm/hugetlbpage.c:setup_hugepagesz",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/hugetlb.c:hugetlb_default_setup",
        "mm/page_counter.c:page_counter_memparse",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:store_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588198720,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588747520,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:128",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:parse_reservelow",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "arch/x86/mm/hugetlbpage.c:setup_hugepagesz",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/hugetlb.c:hugetlb_default_setup",
        "mm/page_counter.c:page_counter_memparse",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:store_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588747520,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589125328,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:128",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:parse_reservelow",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "arch/x86/mm/hugetlbpage.c:setup_hugepagesz",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/page_alloc.c:cmdline_parse_core",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/hugetlb.c:hugetlb_default_setup",
        "mm/page_counter.c:page_counter_memparse",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:store_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589125328,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589359968,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:128",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd",
        "init/do_mounts_initrd.c:early_initrd",
        "arch/x86/kernel/setup.c:parse_reservelow",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "arch/x86/mm/hugetlbpage.c:setup_hugepagesz",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/page_alloc.c:cmdline_parse_core",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/hugetlb.c:hugetlb_default_setup",
        "mm/page_counter.c:page_counter_memparse",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:store_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589359968,
      "name": "memparse",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589817024,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:125",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd",
        "init/do_mounts_initrd.c:early_initrd",
        "arch/x86/xen/time.c:parse_xen_timer_slop",
        "arch/x86/kernel/setup.c:parse_reservelow",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "arch/x86/mm/hugetlbpage.c:setup_hugepagesz",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/shmem.c:shmem_parse_options",
        "mm/page_alloc.c:cmdline_parse_core",
        "mm/hugetlb.c:hugetlb_default_setup",
        "mm/page_counter.c:page_counter_memparse",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:store_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589817024,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590043344,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:125",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd",
        "init/do_mounts_initrd.c:early_initrd",
        "arch/x86/xen/time.c:parse_xen_timer_slop",
        "arch/x86/kernel/setup.c:parse_reservelow",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "arch/x86/mm/hugetlbpage.c:setup_hugepagesz",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/page_alloc.c:cmdline_parse_core",
        "mm/hugetlb.c:hugetlb_default_setup",
        "mm/page_counter.c:page_counter_memparse",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:store_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590043344,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585036976,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:125",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrdmem",
        "init/do_mounts_initrd.c:early_initrdmem",
        "arch/x86/xen/time.c:parse_xen_timer_slop",
        "arch/x86/kernel/setup.c:parse_reservelow",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/dma/pool.c:early_coherent_pool",
        "kernel/crash_core.c:parse_crashkernel_suffix",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/page_alloc.c:cmdline_parse_core",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/page_counter.c:page_counter_memparse",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:parse_subpart",
        "block/cmdline-parser.c:parse_subpart",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:store_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585036976,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585188928,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:137",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrdmem",
        "init/do_mounts_initrd.c:early_initrdmem",
        "arch/x86/xen/time.c:parse_xen_timer_slop",
        "arch/x86/kernel/setup.c:parse_reservelow",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/dma/pool.c:early_coherent_pool",
        "kernel/crash_core.c:parse_crashkernel_suffix",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/page_alloc.c:cmdline_parse_core",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/page_counter.c:page_counter_memparse",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:parse_subpart",
        "block/cmdline-parser.c:parse_subpart",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:store_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585188928,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585071872,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:150",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrdmem",
        "init/do_mounts_initrd.c:early_initrdmem",
        "arch/x86/xen/time.c:parse_xen_timer_slop",
        "arch/x86/kernel/setup.c:parse_reservelow",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/dma/pool.c:early_coherent_pool",
        "kernel/crash_core.c:parse_crashkernel_suffix",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/page_alloc.c:cmdline_parse_core",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/page_counter.c:page_counter_memparse",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:parse_subpart",
        "block/cmdline-parser.c:parse_subpart",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:store_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585071872,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585518560,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:150",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrdmem",
        "init/do_mounts_initrd.c:early_initrdmem",
        "arch/x86/xen/time.c:parse_xen_timer_slop",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/dma/pool.c:early_coherent_pool",
        "kernel/crash_core.c:parse_crashkernel_suffix",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/page_alloc.c:cmdline_parse_core",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/page_counter.c:page_counter_memparse",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/partitions/cmdline.c:parse_subpart",
        "block/partitions/cmdline.c:parse_subpart",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:target_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585518560,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586670768,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:150",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrdmem",
        "init/do_mounts_initrd.c:early_initrdmem",
        "arch/x86/xen/time.c:parse_xen_timer_slop",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/dma/pool.c:early_coherent_pool",
        "kernel/crash_core.c:parse_crashkernel_suffix",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/page_alloc.c:cmdline_parse_core",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/hugetlb.c:demote_size_store",
        "mm/page_counter.c:page_counter_memparse",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/partitions/cmdline.c:parse_subpart",
        "block/partitions/cmdline.c:parse_subpart",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:target_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586670768,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595750192,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:150",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd",
        "init/do_mounts_initrd.c:early_initrd",
        "arch/x86/xen/time.c:parse_xen_timer_slop",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/dma/pool.c:early_coherent_pool",
        "kernel/crash_core.c:parse_crashkernel_suffix",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/hugetlb.c:demote_size_store",
        "mm/page_counter.c:page_counter_memparse",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/partitions/cmdline.c:parse_subpart",
        "block/partitions/cmdline.c:parse_subpart",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:target_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595750192,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596274496,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:150",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd",
        "init/do_mounts_initrd.c:early_initrd",
        "arch/x86/xen/time.c:parse_xen_timer_slop",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/dma/pool.c:early_coherent_pool",
        "kernel/crash_core.c:parse_crashkernel_suffix",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/mm_init.c:cmdline_parse_movablecore",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/hugetlb.c:demote_size_store",
        "mm/page_counter.c:page_counter_memparse",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/partitions/cmdline.c:parse_subpart",
        "block/partitions/cmdline.c:parse_subpart",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:target_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596274496,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597159232,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:150",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd",
        "init/do_mounts_initrd.c:early_initrd",
        "arch/x86/xen/time.c:parse_xen_timer_slop",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/dma/pool.c:early_coherent_pool",
        "kernel/crash_core.c:__parse_crashkernel",
        "kernel/crash_core.c:__parse_crashkernel",
        "kernel/crash_core.c:parse_crashkernel_suffix",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/crash_core.c:parse_crashkernel_mem",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/mm_init.c:cmdline_parse_movablecore",
        "mm/hugetlb.c:default_hugepagesz_setup",
        "mm/hugetlb.c:hugepagesz_setup",
        "mm/hugetlb.c:demote_size_store",
        "mm/page_counter.c:page_counter_memparse",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/partitions/cmdline.c:parse_subpart",
        "block/partitions/cmdline.c:parse_subpart",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:target_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597159232,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503804264,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:125",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd",
        "init/do_mounts_initrd.c:early_initrd",
        "arch/arm64/mm/init.c:early_mem",
        "arch/arm64/mm/hugetlbpage.c:setup_hugepagesz",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/dma/contiguous.c:early_cma",
        "kernel/dma/contiguous.c:early_cma",
        "kernel/dma/contiguous.c:early_cma",
        "kernel/dma/remap.c:early_coherent_pool",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/page_alloc.c:cmdline_parse_core",
        "mm/hugetlb.c:hugetlb_default_setup",
        "mm/page_counter.c:page_counter_memparse",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:store_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503804264,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236427268,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:125",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd",
        "init/do_mounts_initrd.c:early_initrd",
        "arch/arm/kernel/setup.c:early_mem",
        "arch/arm/kernel/setup.c:early_mem",
        "arch/arm/mm/dma-mapping.c:early_coherent_pool",
        "arch/arm/mm/mmu.c:early_vmalloc",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/dma/contiguous.c:early_cma",
        "kernel/dma/contiguous.c:early_cma",
        "kernel/dma/contiguous.c:early_cma",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/page_counter.c:page_counter_memparse",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/mtd/parsers/cmdlinepart.c:newpart",
        "drivers/mtd/parsers/cmdlinepart.c:newpart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236427268,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297643024,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:125",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd",
        "init/do_mounts_initrd.c:early_initrd",
        "arch/powerpc/kernel/prom.c:early_parse_mem",
        "arch/powerpc/kernel/fadump.c:early_fadump_reserve_mem",
        "arch/powerpc/mm/numa.c:fake_numa_create_new_node",
        "arch/powerpc/mm/hugetlbpage.c:hugepage_setup_sz",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/page_alloc.c:cmdline_parse_core",
        "mm/hugetlb.c:hugetlb_default_setup",
        "mm/page_counter.c:page_counter_memparse",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297643024,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279701472,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:125",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd",
        "init/do_mounts_initrd.c:early_initrd",
        "arch/riscv/mm/hugetlbpage.c:setup_hugepagesz",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/dma/contiguous.c:early_cma",
        "kernel/dma/contiguous.c:early_cma",
        "kernel/dma/contiguous.c:early_cma",
        "kernel/trace/trace.c:set_buf_size",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/page_alloc.c:cmdline_parse_core",
        "mm/hugetlb.c:hugetlb_default_setup",
        "mm/page_counter.c:page_counter_memparse",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279701472,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589645600,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:125",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd",
        "init/do_mounts_initrd.c:early_initrd",
        "arch/x86/xen/time.c:parse_xen_timer_slop",
        "arch/x86/kernel/setup.c:parse_reservelow",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "arch/x86/mm/hugetlbpage.c:setup_hugepagesz",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/dma/contiguous.c:early_cma",
        "kernel/dma/contiguous.c:early_cma",
        "kernel/dma/contiguous.c:early_cma",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/page_alloc.c:cmdline_parse_core",
        "mm/hugetlb.c:hugetlb_default_setup",
        "mm/page_counter.c:page_counter_memparse",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589645600,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589371472,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:125",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd",
        "init/do_mounts_initrd.c:early_initrd",
        "arch/x86/kernel/setup.c:parse_reservelow",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "arch/x86/mm/hugetlbpage.c:setup_hugepagesz",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/page_alloc.c:cmdline_parse_core",
        "mm/hugetlb.c:hugetlb_default_setup",
        "mm/page_counter.c:page_counter_memparse",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589371472,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590088976,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:125",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd",
        "init/do_mounts_initrd.c:early_initrd",
        "arch/x86/xen/time.c:parse_xen_timer_slop",
        "arch/x86/kernel/setup.c:parse_reservelow",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "arch/x86/mm/hugetlbpage.c:setup_hugepagesz",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/page_alloc.c:cmdline_parse_core",
        "mm/hugetlb.c:hugetlb_default_setup",
        "mm/page_counter.c:page_counter_memparse",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:store_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590088976,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
long long unsigned int memparse(const char * ptr, char * * retptr)
```

```json
{
  "name": "memparse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590139232,
      "name": "memparse",
      "external": true,
      "loc": "lib/cmdline.c:125",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:early_initrd",
        "init/do_mounts_initrd.c:early_initrd",
        "arch/x86/xen/time.c:parse_xen_timer_slop",
        "arch/x86/kernel/setup.c:parse_reservelow",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memopt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_gran_size_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:parse_mtrr_chunk_size_opt",
        "arch/x86/kernel/mpparse.c:parse_alloc_mptable_opt",
        "arch/x86/kernel/apic/x2apic_uv_x.c:parse_mem_block_size",
        "arch/x86/kernel/check.c:set_corruption_check_size",
        "arch/x86/mm/hugetlbpage.c:setup_hugepagesz",
        "kernel/printk/printk.c:log_buf_len_setup",
        "kernel/trace/trace.c:set_buf_size",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "kernel/crash_dump.c:setup_elfcorehdr",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/shmem.c:shmem_parse_one",
        "mm/page_alloc.c:cmdline_parse_core",
        "mm/hugetlb.c:hugetlb_default_setup",
        "mm/page_counter.c:page_counter_memparse",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "fs/hugetlbfs/inode.c:hugetlbfs_parse_param",
        "security/integrity/ima/ima_crypto.c:param_set_bufsize",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "block/cmdline-parser.c:cmdline_parts_parse",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/pci/pci.c:pci_setup",
        "drivers/virtio/virtio_mmio.c:vm_cmdline_set",
        "drivers/xen/xen-balloon.c:store_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590139232,
      "name": "memparse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
