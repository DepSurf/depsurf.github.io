# Function: <code>irte_ga_set_affinity</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584808032,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3932",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584808032,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584898688,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:4070",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584898688,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585319248,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3863",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585319248,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585558112,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3923",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585558112,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585682672,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3989",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585682672,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585909280,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3970",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585909280,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586052480,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:4025",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586052480,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586805392,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3450",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586805392,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586864640,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3541",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586864640,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586740736,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2907",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586740736,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587295968,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2975",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587295968,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588609648,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3001",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588609648,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void irte_ga_set_affinity(struct amd_iommu * iommu, void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590071872,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3156",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590071872,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void irte_ga_set_affinity(struct amd_iommu * iommu, void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590374928,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3194",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590374928,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
void irte_ga_set_affinity(struct amd_iommu * iommu, void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590721392,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:3245",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590721392,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585813456,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:4025",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585813456,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585672640,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:4025",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585672640,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586002496,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:4025",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586002496,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```

```json
{
  "name": "irte_ga_set_affinity",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586110784,
      "name": "irte_ga_set_affinity",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:4025",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586110784,
      "name": "irte_ga_set_affinity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct amd_iommu * iommu</code>
</li>
<li>
<b>Param reordered. </b>
<code>entry, devid, index, vector, dest_apicid</code> ➡️ <code>iommu, entry, devid, index, vector, dest_apicid</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void irte_ga_set_affinity(void * entry, u16 devid, u16 index, u8 vector, u32 dest_apicid)
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
