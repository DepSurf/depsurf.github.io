# Function: <code>iommu_write_l2</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void iommu_write_l2(struct amd_iommu * iommu, u8 address, u32 val)
```

```json
{
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584294352,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:276",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584294352,
      "name": "iommu_write_l2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void iommu_write_l2(struct amd_iommu * iommu, u8 address, u32 val)
```

```json
{
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584640432,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:295",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584640432,
      "name": "iommu_write_l2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void iommu_write_l2(struct amd_iommu * iommu, u8 address, u32 val)
```

```json
{
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584826624,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:300",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584826624,
      "name": "iommu_write_l2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584918297,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:307",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci"
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
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585339609,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:336",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci"
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
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585580147,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:336",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci"
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
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585705347,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:339",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci"
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
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585933255,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:324",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci"
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
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586076391,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:325",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci"
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
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586821491,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:325",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:iommu_apply_resume_quirks",
        "drivers/iommu/amd/init.c:iommu_init_pci"
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
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586879923,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:343",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:iommu_apply_resume_quirks",
        "drivers/iommu/amd/init.c:iommu_init_pci"
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
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586756275,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:339",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:iommu_apply_resume_quirks",
        "drivers/iommu/amd/init.c:iommu_init_pci"
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
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587308258,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:356",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:iommu_apply_resume_quirks",
        "drivers/iommu/amd/init.c:iommu_init_pci"
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
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588622824,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:360",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:iommu_apply_resume_quirks",
        "drivers/iommu/amd/init.c:iommu_init_pci"
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
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590087208,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:352",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:iommu_apply_resume_quirks",
        "drivers/iommu/amd/init.c:iommu_init_pci"
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
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590399384,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:360",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:iommu_apply_resume_quirks",
        "drivers/iommu/amd/init.c:iommu_init_pci"
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
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590742696,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:345",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:iommu_apply_resume_quirks",
        "drivers/iommu/amd/init.c:iommu_init_pci"
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
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585837511,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:325",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci"
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
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585696551,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:325",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci"
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
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586026407,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:325",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci"
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
  "name": "iommu_write_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586134359,
      "name": "iommu_write_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:325",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_resume",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void iommu_write_l2(struct amd_iommu * iommu, u8 address, u32 val)
```
</details>
</li>
</ul>
