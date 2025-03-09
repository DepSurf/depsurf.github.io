# Function: <code>has_iova_flush_queue</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool has_iova_flush_queue(struct iova_domain * iovad)
```

```json
{
  "name": "has_iova_flush_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585898805,
      "name": "has_iova_flush_queue",
      "external": true,
      "loc": "drivers/iommu/iova.c:57",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:put_iova_domain"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585901872,
      "name": "has_iova_flush_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool has_iova_flush_queue(struct iova_domain * iovad)
```

```json
{
  "name": "has_iova_flush_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586041669,
      "name": "has_iova_flush_queue",
      "external": true,
      "loc": "drivers/iommu/iova.c:57",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:put_iova_domain"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586044816,
      "name": "has_iova_flush_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
bool has_iova_flush_queue(struct iova_domain * iovad)
```

```json
{
  "name": "has_iova_flush_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586789957,
      "name": "has_iova_flush_queue",
      "external": true,
      "loc": "drivers/iommu/iova.c:57",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:put_iova_domain"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586793552,
      "name": "has_iova_flush_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
bool has_iova_flush_queue(struct iova_domain * iovad)
```

```json
{
  "name": "has_iova_flush_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586973077,
      "name": "has_iova_flush_queue",
      "external": true,
      "loc": "drivers/iommu/iova.c:58",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:put_iova_domain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586975904,
      "name": "has_iova_flush_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "has_iova_flush_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586854488,
      "name": "has_iova_flush_queue",
      "external": false,
      "loc": "drivers/iommu/iova.c:76",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:put_iova_domain"
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
  "name": "has_iova_flush_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587416204,
      "name": "has_iova_flush_queue",
      "external": false,
      "loc": "drivers/iommu/iova.c:76",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:put_iova_domain"
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool has_iova_flush_queue(struct iova_domain * iovad)
```

```json
{
  "name": "has_iova_flush_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498859084,
      "name": "has_iova_flush_queue",
      "external": true,
      "loc": "drivers/iommu/iova.c:57",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:put_iova_domain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498864400,
      "name": "has_iova_flush_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool has_iova_flush_queue(struct iova_domain * iovad)
```

```json
{
  "name": "has_iova_flush_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585802645,
      "name": "has_iova_flush_queue",
      "external": true,
      "loc": "drivers/iommu/iova.c:57",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:put_iova_domain"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805792,
      "name": "has_iova_flush_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool has_iova_flush_queue(struct iova_domain * iovad)
```

```json
{
  "name": "has_iova_flush_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585661829,
      "name": "has_iova_flush_queue",
      "external": true,
      "loc": "drivers/iommu/iova.c:57",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:put_iova_domain"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585664976,
      "name": "has_iova_flush_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
bool has_iova_flush_queue(struct iova_domain * iovad)
```

```json
{
  "name": "has_iova_flush_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585991685,
      "name": "has_iova_flush_queue",
      "external": true,
      "loc": "drivers/iommu/iova.c:57",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:put_iova_domain"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585994832,
      "name": "has_iova_flush_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
bool has_iova_flush_queue(struct iova_domain * iovad)
```

```json
{
  "name": "has_iova_flush_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586100069,
      "name": "has_iova_flush_queue",
      "external": true,
      "loc": "drivers/iommu/iova.c:57",
      "file": "drivers/iommu/iova.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:put_iova_domain"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586102800,
      "name": "has_iova_flush_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
bool has_iova_flush_queue(struct iova_domain * iovad)
```
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool has_iova_flush_queue(struct iova_domain * iovad)
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
bool has_iova_flush_queue(struct iova_domain * iovad)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool has_iova_flush_queue(struct iova_domain * iovad)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool has_iova_flush_queue(struct iova_domain * iovad)
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
