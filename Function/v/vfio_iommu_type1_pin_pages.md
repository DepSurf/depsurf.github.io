# Function: <code>vfio_iommu_type1_pin_pages</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int vfio_iommu_type1_pin_pages(void * iommu_data, long unsigned int * user_pfn, int npage, int prot, long unsigned int * phys_pfn)
```

```json
{
  "name": "vfio_iommu_type1_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_iommu_type1_pin_pages",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:541",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587054608,
      "name": "vfio_iommu_type1_pin_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
    },
    {
      "addr": 18446744071587061215,
      "name": "vfio_iommu_type1_pin_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int vfio_iommu_type1_pin_pages(void * iommu_data, struct iommu_group * iommu_group, long unsigned int * user_pfn, int npage, int prot, long unsigned int * phys_pfn)
```

```json
{
  "name": "vfio_iommu_type1_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587891488,
      "name": "vfio_iommu_type1_pin_pages",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:631",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587891488,
      "name": "vfio_iommu_type1_pin_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1084
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
int vfio_iommu_type1_pin_pages(void * iommu_data, struct iommu_group * iommu_group, long unsigned int * user_pfn, int npage, int prot, long unsigned int * phys_pfn)
```

```json
{
  "name": "vfio_iommu_type1_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587956944,
      "name": "vfio_iommu_type1_pin_pages",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:654",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587956944,
      "name": "vfio_iommu_type1_pin_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1148
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
int vfio_iommu_type1_pin_pages(void * iommu_data, struct iommu_group * iommu_group, long unsigned int * user_pfn, int npage, int prot, long unsigned int * phys_pfn)
```

```json
{
  "name": "vfio_iommu_type1_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_iommu_type1_pin_pages",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:832",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587829664,
      "name": "vfio_iommu_type1_pin_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1490
    },
    {
      "addr": 18446744071591476748,
      "name": "vfio_iommu_type1_pin_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int vfio_iommu_type1_pin_pages(void * iommu_data, struct iommu_group * iommu_group, long unsigned int * user_pfn, int npage, int prot, long unsigned int * phys_pfn)
```

```json
{
  "name": "vfio_iommu_type1_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_iommu_type1_pin_pages",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:833",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588436416,
      "name": "vfio_iommu_type1_pin_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1493
    },
    {
      "addr": 18446744071592549131,
      "name": "vfio_iommu_type1_pin_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int vfio_iommu_type1_pin_pages(void * iommu_data, struct iommu_group * iommu_group, long unsigned int * user_pfn, int npage, int prot, long unsigned int * phys_pfn)
```

```json
{
  "name": "vfio_iommu_type1_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_iommu_type1_pin_pages",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:831",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589839952,
      "name": "vfio_iommu_type1_pin_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1610
    },
    {
      "addr": 18446744071594428550,
      "name": "vfio_iommu_type1_pin_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int vfio_iommu_type1_pin_pages(void * iommu_data, long unsigned int * user_pfn, int npage, int prot, long unsigned int * phys_pfn)
```

```json
{
  "name": "vfio_iommu_type1_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_iommu_type1_pin_pages",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:541",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586702528,
      "name": "vfio_iommu_type1_pin_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
    },
    {
      "addr": 18446744071586709135,
      "name": "vfio_iommu_type1_pin_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int vfio_iommu_type1_pin_pages(void * iommu_data, long unsigned int * user_pfn, int npage, int prot, long unsigned int * phys_pfn)
```

```json
{
  "name": "vfio_iommu_type1_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_iommu_type1_pin_pages",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:541",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009168,
      "name": "vfio_iommu_type1_pin_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
    },
    {
      "addr": 18446744071587015775,
      "name": "vfio_iommu_type1_pin_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int vfio_iommu_type1_pin_pages(void * iommu_data, long unsigned int * user_pfn, int npage, int prot, long unsigned int * phys_pfn)
```

```json
{
  "name": "vfio_iommu_type1_pin_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_iommu_type1_pin_pages",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:541",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587116336,
      "name": "vfio_iommu_type1_pin_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
    },
    {
      "addr": 18446744071587122943,
      "name": "vfio_iommu_type1_pin_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int vfio_iommu_type1_pin_pages(void * iommu_data, long unsigned int * user_pfn, int npage, int prot, long unsigned int * phys_pfn)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iommu_group * iommu_group</code>
</li>
<li>
<b>Param reordered. </b>
<code>iommu_data, user_pfn, npage, prot, phys_pfn</code> ➡️ <code>iommu_data, iommu_group, user_pfn, npage, prot, phys_pfn</code>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int vfio_iommu_type1_pin_pages(void * iommu_data, struct iommu_group * iommu_group, long unsigned int * user_pfn, int npage, int prot, long unsigned int * phys_pfn)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int vfio_iommu_type1_pin_pages(void * iommu_data, long unsigned int * user_pfn, int npage, int prot, long unsigned int * phys_pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_iommu_type1_pin_pages(void * iommu_data, long unsigned int * user_pfn, int npage, int prot, long unsigned int * phys_pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int vfio_iommu_type1_pin_pages(void * iommu_data, long unsigned int * user_pfn, int npage, int prot, long unsigned int * phys_pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int vfio_iommu_type1_pin_pages(void * iommu_data, long unsigned int * user_pfn, int npage, int prot, long unsigned int * phys_pfn)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int vfio_iommu_type1_pin_pages(void * iommu_data, long unsigned int * user_pfn, int npage, int prot, long unsigned int * phys_pfn)
```
</details>
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
