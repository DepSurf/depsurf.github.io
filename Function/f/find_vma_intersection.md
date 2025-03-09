# Function: <code>find_vma_intersection</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580708291,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2053",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:SyS_brk",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580815699,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2053",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580976970,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2053",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582168875,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2053",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580825138,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2175",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:SyS_brk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580941089,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2175",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581131384,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2175",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582384968,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2175",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580890642,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2161",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:SyS_brk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581013046,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2161",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:SYSC_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581206449,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2161",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582477158,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2161",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580935786,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2240",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581060405,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2240",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:SYSC_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255145,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2240",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582557980,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2240",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581035546,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2349",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581171434,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2349",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:SYSC_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581387310,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2349",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582709906,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2349",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581170688,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2438",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581316026,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2438",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537758,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2438",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582905868,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2438",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581250969,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2511",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400043,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2511",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581623806,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2511",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583014189,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2511",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581325891,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2505",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512185,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2505",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581736107,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2505",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583196131,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2505",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581385235,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581576553,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809627,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583301939,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587050086,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581581142,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2689",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786273,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2689",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582030421,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2689",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583633116,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2689",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587881267,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2689",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581626845,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2689",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581831165,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2689",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582079130,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2689",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583753834,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2689",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587943555,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2689",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581650331,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581861683,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583777940,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587825164,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581911894,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2723",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584140100,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2723",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582318177,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2798",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584737970,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2798",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_area_struct * find_vma_intersection(struct mm_struct * mm, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582818692,
      "name": "find_vma_intersection",
      "external": true,
      "loc": "mm/mmap.c:1811",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_mmap"
      ],
      "caller_func": [
        "mm/gup.c:__mm_populate",
        "mm/gup.c:__mm_populate",
        "mm/mremap.c:__do_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582804256,
      "name": "find_vma_intersection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_area_struct * find_vma_intersection(struct mm_struct * mm, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583033080,
      "name": "find_vma_intersection",
      "external": true,
      "loc": "mm/mmap.c:1839",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:vma_merge"
      ],
      "caller_func": [
        "mm/gup.c:__mm_populate",
        "mm/gup.c:__mm_populate",
        "mm/mremap.c:__do_sys_mremap",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583017872,
      "name": "find_vma_intersection",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_area_struct * find_vma_intersection(struct mm_struct * mm, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583214440,
      "name": "find_vma_intersection",
      "external": true,
      "loc": "mm/mmap.c:1871",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:insert_vm_struct",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:vma_merge"
      ],
      "caller_func": [
        "mm/gup.c:__mm_populate",
        "mm/gup.c:__mm_populate",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583197520,
      "name": "find_vma_intersection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490401292,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:__gfn_to_pfn_memslot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490461956,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "virt/kvm/arm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/mmu.c:user_mem_abort"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492791212,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493013364,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493276012,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495040520,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226606660,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 3226881356,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 3228442096,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286161552,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286440244,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286803720,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288927264,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272761104,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273026688,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274317154,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581354083,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581545289,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581778363,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583270675,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581297795,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581486937,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581716523,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583207811,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586698006,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581345283,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581536601,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581769675,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254707,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587004646,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_vma_intersection",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581409219,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581601630,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581838539,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583349246,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587111814,
      "name": "find_vma_intersection",
      "external": false,
      "loc": "include/linux/mm.h:2479",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct vm_area_struct * find_vma_intersection(struct mm_struct * mm, long unsigned int start_addr, long unsigned int end_addr)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
