# Function: <code>remap_pfn_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580682320,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:1694",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "mm/memory.c:vm_iomap_memory",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "fs/proc/vmcore.c:mmap_vmcore",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/char/agp/frontend.c:agp_mmap",
        "drivers/base/dma-mapping.c:dma_common_mmap",
        "arch/x86/pci/i386.c:pci_mmap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580682320,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1063
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580795456,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:1756",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_iomap_memory",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/char/agp/frontend.c:agp_mmap",
        "drivers/base/dma-mapping.c:dma_common_mmap",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "arch/x86/pci/i386.c:pci_mmap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580795456,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1072
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580859728,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:1756",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_iomap_memory",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/char/agp/frontend.c:agp_mmap",
        "drivers/base/dma-mapping.c:dma_common_mmap",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "arch/x86/pci/i386.c:pci_mmap_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580859728,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1070
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580904528,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:1942",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_iomap_memory",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/char/agp/frontend.c:agp_mmap",
        "drivers/base/dma-mapping.c:dma_common_mmap",
        "drivers/usb/core/devio.c:usbdev_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580904528,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1092
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581004160,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:2059",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:vm_iomap_memory",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/char/agp/frontend.c:agp_mmap",
        "drivers/base/dma-mapping.c:dma_common_mmap",
        "drivers/usb/core/devio.c:usbdev_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581004160,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1208
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581134608,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:2101",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_common_mmap",
        "mm/memory.c:vm_iomap_memory",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/char/agp/frontend.c:agp_mmap",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "net/xdp/xsk.c:xsk_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581134608,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1220
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581217424,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:1837",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "kernel/dma/mapping.c:dma_common_mmap",
        "mm/memory.c:vm_iomap_memory",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/char/agp/frontend.c:agp_mmap",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "net/xdp/xsk.c:xsk_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581217424,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1243
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581290688,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:1892",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "kernel/dma/mapping.c:dma_common_mmap",
        "kernel/dma/coherent.c:__dma_mmap_from_coherent",
        "mm/memory.c:vm_iomap_memory",
        "fs/io_uring.c:io_uring_mmap",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/char/agp/frontend.c:agp_mmap",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "net/xdp/xsk.c:xsk_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581290688,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1271
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581349424,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:1897",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "kernel/dma/mapping.c:dma_common_mmap",
        "mm/memory.c:vm_iomap_memory",
        "fs/io_uring.c:io_uring_mmap",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/char/agp/frontend.c:agp_mmap",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "net/xdp/xsk.c:xsk_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581349424,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1271
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581546656,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:2096",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "kernel/dma/mapping.c:dma_common_mmap",
        "kernel/dma/direct.c:dma_direct_mmap",
        "mm/memory.c:vm_iomap_memory",
        "fs/io_uring.c:io_uring_mmap",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "security/selinux/selinuxfs.c:sel_mmap_handle_status",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/char/agp/frontend.c:agp_mmap",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_fault",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "net/xdp/xsk.c:xsk_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581546656,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1065
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581589904,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:2270",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "kernel/dma/direct.c:dma_direct_mmap",
        "kernel/dma/ops_helpers.c:dma_common_mmap",
        "mm/memory.c:vm_iomap_memory",
        "fs/io_uring.c:io_uring_mmap",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "security/selinux/selinuxfs.c:sel_mmap_handle_status",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_mmap",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_fault",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "net/xdp/xsk.c:xsk_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581589904,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1113
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581613552,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:2345",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "kernel/dma/mapping.c:dma_mmap_pages",
        "kernel/dma/direct.c:dma_direct_mmap",
        "kernel/dma/ops_helpers.c:dma_common_mmap",
        "mm/memory.c:vm_iomap_memory",
        "fs/io_uring.c:io_uring_mmap",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "security/selinux/selinuxfs.c:sel_mmap_handle_status",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_mmap",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_fault",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "net/xdp/xsk.c:xsk_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581613552,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581880592,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:2440",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "kernel/dma/mapping.c:dma_mmap_pages",
        "kernel/dma/direct.c:dma_direct_mmap",
        "kernel/dma/ops_helpers.c:dma_common_mmap",
        "mm/memory.c:vm_iomap_memory",
        "fs/io_uring.c:io_uring_mmap",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "security/selinux/selinuxfs.c:sel_mmap_handle_status",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_mmap",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_mmap_fault",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "net/xdp/xsk.c:xsk_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581880592,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582280368,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:2533",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "kernel/dma/mapping.c:dma_mmap_pages",
        "kernel/dma/direct.c:dma_direct_mmap",
        "kernel/dma/ops_helpers.c:dma_common_mmap",
        "mm/memory.c:vm_iomap_memory",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "security/selinux/selinuxfs.c:sel_mmap_handle_status",
        "io_uring/io_uring.c:io_uring_mmap",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_mmap",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_mmap_fault",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "net/xdp/xsk.c:xsk_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582280368,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582772896,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:2504",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "kernel/dma/mapping.c:dma_mmap_pages",
        "kernel/dma/direct.c:dma_direct_mmap",
        "kernel/dma/ops_helpers.c:dma_common_mmap",
        "mm/memory.c:vm_iomap_memory",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "security/selinux/selinuxfs.c:sel_mmap_handle_status",
        "io_uring/io_uring.c:io_uring_mmap",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_mmap",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "net/xdp/xsk.c:xsk_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582772896,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582989072,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:2504",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "kernel/dma/mapping.c:dma_mmap_pages",
        "kernel/dma/direct.c:dma_direct_mmap",
        "kernel/dma/ops_helpers.c:dma_common_mmap",
        "mm/memory.c:vm_iomap_memory",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "security/selinux/selinuxfs.c:sel_mmap_handle_status",
        "io_uring/io_uring.c:io_uring_mmap",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_mmap",
        "drivers/usb/core/devio.c:usbdev_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582989072,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583164320,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:2527",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "kernel/dma/mapping.c:dma_mmap_pages",
        "kernel/dma/direct.c:dma_direct_mmap",
        "kernel/dma/ops_helpers.c:dma_common_mmap",
        "mm/memory.c:vm_iomap_memory",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "security/selinux/selinuxfs.c:sel_mmap_handle_status",
        "io_uring/io_uring.c:io_uring_mmap",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_mmap",
        "drivers/usb/core/devio.c:usbdev_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583164320,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492755024,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:1897",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_common_mmap",
        "kernel/dma/coherent.c:__dma_mmap_from_coherent",
        "mm/memory.c:vm_iomap_memory",
        "fs/io_uring.c:io_uring_mmap",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_of_vram_mmap",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "net/xdp/xsk.c:xsk_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492755024,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 944
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226564944,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:1897",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_common_mmap",
        "kernel/dma/coherent.c:__dma_mmap_from_coherent",
        "mm/memory.c:vm_iomap_memory",
        "fs/io_uring.c:io_uring_mmap",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/video/fbdev/amba-clcd.c:clcdfb_of_vram_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "net/xdp/xsk.c:xsk_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226564944,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286116000,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:1897",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/proc_powerpc.c:page_map_mmap",
        "arch/powerpc/kernel/pci-common.c:pci_mmap_legacy_page_range",
        "kernel/dma/mapping.c:dma_common_mmap",
        "kernel/dma/coherent.c:__dma_mmap_from_coherent",
        "mm/memory.c:vm_iomap_memory",
        "fs/io_uring.c:io_uring_mmap",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "security/selinux/selinuxfs.c:sel_mmap_handle_status",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/char/mem.c:mmap_mem",
        "drivers/char/agp/frontend.c:agp_mmap",
        "drivers/char/agp/frontend.c:agp_mmap",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap",
        "drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_npu2_mmap",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "net/xdp/xsk.c:xsk_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286116000,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1648
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272737046,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:1897",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_common_mmap",
        "kernel/dma/coherent.c:__dma_mmap_from_coherent",
        "mm/memory.c:vm_iomap_memory",
        "fs/io_uring.c:io_uring_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "net/xdp/xsk.c:xsk_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272737046,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581318272,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:1897",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "kernel/dma/mapping.c:dma_common_mmap",
        "mm/memory.c:vm_iomap_memory",
        "fs/io_uring.c:io_uring_mmap",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/char/agp/frontend.c:agp_mmap",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "net/xdp/xsk.c:xsk_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581318272,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1271
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581262400,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:1897",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "kernel/dma/mapping.c:dma_common_mmap",
        "mm/memory.c:vm_iomap_memory",
        "fs/io_uring.c:io_uring_mmap",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/char/mem.c:mmap_mem",
        "drivers/char/agp/frontend.c:agp_mmap",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "net/xdp/xsk.c:xsk_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581262400,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1220
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581309472,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:1897",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "kernel/dma/mapping.c:dma_common_mmap",
        "mm/memory.c:vm_iomap_memory",
        "fs/io_uring.c:io_uring_mmap",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/char/agp/frontend.c:agp_mmap",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "net/xdp/xsk.c:xsk_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581309472,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1271
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
int remap_pfn_range(struct vm_area_struct * vma, long unsigned int addr, long unsigned int pfn, long unsigned int size, pgprot_t prot)
```

```json
{
  "name": "remap_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581373472,
      "name": "remap_pfn_range",
      "external": true,
      "loc": "mm/memory.c:1897",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap",
        "kernel/dma/mapping.c:dma_common_mmap",
        "mm/memory.c:vm_iomap_memory",
        "fs/io_uring.c:io_uring_mmap",
        "fs/proc/vmcore.c:mmap_vmcore",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap",
        "drivers/char/mem.c:mmap_mem",
        "drivers/char/agp/frontend.c:agp_mmap",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "net/xdp/xsk.c:xsk_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373472,
      "name": "remap_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1269
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
