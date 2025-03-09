# Function: <code>is_canonical_address</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_canonical_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585375085,
      "name": "is_canonical_address",
      "external": false,
      "loc": "drivers/iommu/intel-svm.c:555",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread"
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
  "name": "is_canonical_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585618358,
      "name": "is_canonical_address",
      "external": false,
      "loc": "drivers/iommu/intel-svm.c:572",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread"
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
  "name": "is_canonical_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585746056,
      "name": "is_canonical_address",
      "external": false,
      "loc": "drivers/iommu/intel-svm.c:507",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread"
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
  "name": "is_canonical_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585977913,
      "name": "is_canonical_address",
      "external": false,
      "loc": "drivers/iommu/intel-svm.c:527",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread"
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
  "name": "is_canonical_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586124921,
      "name": "is_canonical_address",
      "external": false,
      "loc": "drivers/iommu/intel-svm.c:523",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool is_canonical_address(u64 addr)
```

```json
{
  "name": "is_canonical_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586877936,
      "name": "is_canonical_address",
      "external": false,
      "loc": "drivers/iommu/intel/svm.c:704",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/svm.c:prq_event_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586877936,
      "name": "is_canonical_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
bool is_canonical_address(u64 addr)
```

```json
{
  "name": "is_canonical_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586926864,
      "name": "is_canonical_address",
      "external": false,
      "loc": "drivers/iommu/intel/svm.c:780",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/iommu/intel/svm.c:prq_event_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586926864,
      "name": "is_canonical_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
  "name": "is_canonical_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586810971,
      "name": "is_canonical_address",
      "external": false,
      "loc": "drivers/iommu/intel/svm.c:733",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:prq_event_thread"
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
  "name": "is_canonical_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587369749,
      "name": "is_canonical_address",
      "external": false,
      "loc": "drivers/iommu/intel/svm.c:723",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:prq_event_thread"
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
  "name": "is_canonical_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588680818,
      "name": "is_canonical_address",
      "external": false,
      "loc": "drivers/iommu/intel/svm.c:502",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:prq_event_thread"
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
  "name": "is_canonical_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590158429,
      "name": "is_canonical_address",
      "external": false,
      "loc": "drivers/iommu/intel/svm.c:468",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:prq_event_thread"
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
  "name": "is_canonical_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590472669,
      "name": "is_canonical_address",
      "external": false,
      "loc": "drivers/iommu/intel/svm.c:454",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:prq_event_thread"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_canonical_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590822589,
      "name": "is_canonical_address",
      "external": false,
      "loc": "drivers/iommu/intel/svm.c:452",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:prq_event_thread"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_canonical_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585885289,
      "name": "is_canonical_address",
      "external": false,
      "loc": "drivers/iommu/intel-svm.c:523",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread"
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
  "name": "is_canonical_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585745065,
      "name": "is_canonical_address",
      "external": false,
      "loc": "drivers/iommu/intel-svm.c:523",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread"
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
  "name": "is_canonical_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586074937,
      "name": "is_canonical_address",
      "external": false,
      "loc": "drivers/iommu/intel-svm.c:523",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread"
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
  "name": "is_canonical_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586183175,
      "name": "is_canonical_address",
      "external": false,
      "loc": "drivers/iommu/intel-svm.c:523",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool is_canonical_address(u64 addr)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool is_canonical_address(u64 addr)
```
</details>
</li>
</ul>
