# Function: <code>queue_iova</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```

```json
{
  "name": "queue_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585308656,
      "name": "queue_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:541",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585308656,
      "name": "queue_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```

```json
{
  "name": "queue_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585549568,
      "name": "queue_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:541",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585549568,
      "name": "queue_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```

```json
{
  "name": "queue_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585673984,
      "name": "queue_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:550",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585673984,
      "name": "queue_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```

```json
{
  "name": "queue_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585900736,
      "name": "queue_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:549",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585900736,
      "name": "queue_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```

```json
{
  "name": "queue_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043648,
      "name": "queue_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:549",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043648,
      "name": "queue_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```

```json
{
  "name": "queue_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586792672,
      "name": "queue_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:549",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free_iova",
        "drivers/iommu/intel/iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586792672,
      "name": "queue_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```

```json
{
  "name": "queue_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586975600,
      "name": "queue_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:564",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586975600,
      "name": "queue_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```

```json
{
  "name": "queue_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586857920,
      "name": "queue_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:629",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586857920,
      "name": "queue_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```

```json
{
  "name": "queue_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587420896,
      "name": "queue_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:631",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587420896,
      "name": "queue_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_iova",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588720080,
      "name": "queue_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:170",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free_iova"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_iova",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590204080,
      "name": "queue_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:173",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free_iova"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_iova",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590525536,
      "name": "queue_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:174",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free_iova"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void queue_iova(struct iommu_dma_cookie * cookie, long unsigned int pfn, long unsigned int pages, struct list_head * freelist)
```

```json
{
  "name": "queue_iova",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590876416,
      "name": "queue_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:200",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590876416,
      "name": "queue_iova",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```

```json
{
  "name": "queue_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498862904,
      "name": "queue_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:549",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_free_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498862904,
      "name": "queue_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```

```json
{
  "name": "queue_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585804624,
      "name": "queue_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:549",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585804624,
      "name": "queue_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```

```json
{
  "name": "queue_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585663808,
      "name": "queue_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:549",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585663808,
      "name": "queue_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```

```json
{
  "name": "queue_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585993664,
      "name": "queue_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:549",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585993664,
      "name": "queue_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```

```json
{
  "name": "queue_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586102480,
      "name": "queue_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:549",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586102480,
      "name": "queue_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```
</details>
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
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void queue_iova(struct iommu_dma_cookie * cookie, long unsigned int pfn, long unsigned int pages, struct list_head * freelist)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void queue_iova(struct iova_domain * iovad, long unsigned int pfn, long unsigned int pages, long unsigned int data)
```
</details>
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
