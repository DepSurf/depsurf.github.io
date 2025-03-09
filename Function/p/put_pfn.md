# Function: <code>put_pfn</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int put_pfn(long unsigned int pfn, int prot)
```

```json
{
  "name": "put_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587051296,
      "name": "put_pfn",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:326",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587051296,
      "name": "put_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int put_pfn(long unsigned int pfn, int prot)
```

```json
{
  "name": "put_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587891406,
      "name": "put_pfn",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:407",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote"
      ],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587881504,
      "name": "put_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int put_pfn(long unsigned int pfn, int prot)
```

```json
{
  "name": "put_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587957931,
      "name": "put_pfn",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:420",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote"
      ],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587942112,
      "name": "put_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int put_pfn(long unsigned int pfn, int prot)
```

```json
{
  "name": "put_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587825928,
      "name": "put_pfn",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:458",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin",
        "drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin"
      ],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587827840,
      "name": "put_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int put_pfn(long unsigned int pfn, int prot)
```

```json
{
  "name": "put_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588430824,
      "name": "put_pfn",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:459",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin",
        "drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin"
      ],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588432784,
      "name": "put_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
  "name": "put_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589841118,
      "name": "put_pfn",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:457",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin",
        "drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int put_pfn(long unsigned int pfn, int prot)
```

```json
{
  "name": "put_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586699216,
      "name": "put_pfn",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:326",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586699216,
      "name": "put_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int put_pfn(long unsigned int pfn, int prot)
```

```json
{
  "name": "put_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587005856,
      "name": "put_pfn",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:326",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587005856,
      "name": "put_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int put_pfn(long unsigned int pfn, int prot)
```

```json
{
  "name": "put_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587113024,
      "name": "put_pfn",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:326",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587113024,
      "name": "put_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int put_pfn(long unsigned int pfn, int prot)
```
</details>
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
int put_pfn(long unsigned int pfn, int prot)
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
int put_pfn(long unsigned int pfn, int prot)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int put_pfn(long unsigned int pfn, int prot)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int put_pfn(long unsigned int pfn, int prot)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int put_pfn(long unsigned int pfn, int prot)
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
int put_pfn(long unsigned int pfn, int prot)
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
