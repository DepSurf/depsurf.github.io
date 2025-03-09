# Function: <code>pasid_flush_caches</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pasid_flush_caches(struct intel_iommu * iommu, struct pasid_entry * pte, int pasid, u16 did)
```

```json
{
  "name": "pasid_flush_caches",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586870544,
      "name": "pasid_flush_caches",
      "external": false,
      "loc": "drivers/iommu/intel/pasid.c:516",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_nested",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586870544,
      "name": "pasid_flush_caches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void pasid_flush_caches(struct intel_iommu * iommu, struct pasid_entry * pte, u32 pasid, u16 did)
```

```json
{
  "name": "pasid_flush_caches",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586919344,
      "name": "pasid_flush_caches",
      "external": false,
      "loc": "drivers/iommu/intel/pasid.c:524",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_nested",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586919344,
      "name": "pasid_flush_caches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void pasid_flush_caches(struct intel_iommu * iommu, struct pasid_entry * pte, u32 pasid, u16 did)
```

```json
{
  "name": "pasid_flush_caches",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586800912,
      "name": "pasid_flush_caches",
      "external": false,
      "loc": "drivers/iommu/intel/pasid.c:543",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_nested",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586800912,
      "name": "pasid_flush_caches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void pasid_flush_caches(struct intel_iommu * iommu, struct pasid_entry * pte, u32 pasid, u16 did)
```

```json
{
  "name": "pasid_flush_caches",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587357856,
      "name": "pasid_flush_caches",
      "external": false,
      "loc": "drivers/iommu/intel/pasid.c:547",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_nested",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587357856,
      "name": "pasid_flush_caches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pasid_flush_caches(struct intel_iommu * iommu, struct pasid_entry * pte, u32 pasid, u16 did)
```

```json
{
  "name": "pasid_flush_caches",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588669520,
      "name": "pasid_flush_caches",
      "external": false,
      "loc": "drivers/iommu/intel/pasid.c:484",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588669520,
      "name": "pasid_flush_caches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pasid_flush_caches(struct intel_iommu * iommu, struct pasid_entry * pte, u32 pasid, u16 did)
```

```json
{
  "name": "pasid_flush_caches",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590142560,
      "name": "pasid_flush_caches",
      "external": false,
      "loc": "drivers/iommu/intel/pasid.c:493",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590142560,
      "name": "pasid_flush_caches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void pasid_flush_caches(struct intel_iommu * iommu, struct pasid_entry * pte, u32 pasid, u16 did)
```

```json
{
  "name": "pasid_flush_caches",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590456880,
      "name": "pasid_flush_caches",
      "external": false,
      "loc": "drivers/iommu/intel/pasid.c:484",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590456880,
      "name": "pasid_flush_caches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void pasid_flush_caches(struct intel_iommu * iommu, struct pasid_entry * pte, u32 pasid, u16 did)
```

```json
{
  "name": "pasid_flush_caches",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590804592,
      "name": "pasid_flush_caches",
      "external": false,
      "loc": "drivers/iommu/intel/pasid.c:270",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_nested",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590804592,
      "name": "pasid_flush_caches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void pasid_flush_caches(struct intel_iommu * iommu, struct pasid_entry * pte, int pasid, u16 did)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int pasid</code> ➡️ <code>u32 pasid</code>
</li>
</ul>
</details>
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
