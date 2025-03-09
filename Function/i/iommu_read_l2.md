# Function: <code>iommu_read_l2</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u32 iommu_read_l2(struct amd_iommu * iommu, u8 address)
```

```json
{
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586139011,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:267",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586139011,
      "name": "iommu_read_l2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
u32 iommu_read_l2(struct amd_iommu * iommu, u8 address)
```

```json
{
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586552766,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:286",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/amd_iommu_init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586552766,
      "name": "iommu_read_l2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
u32 iommu_read_l2(struct amd_iommu * iommu, u8 address)
```

```json
{
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586734176,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:291",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586734176,
      "name": "iommu_read_l2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596630851,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:298",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
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
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602961051,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:327",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
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
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585581493,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:327",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
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
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604936629,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:330",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
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
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605040543,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:315",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
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
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605077097,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:316",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
u32 iommu_read_l2(struct amd_iommu * iommu, u8 address)
```

```json
{
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586822734,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:316",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586822734,
      "name": "iommu_read_l2",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
u32 iommu_read_l2(struct amd_iommu * iommu, u8 address)
```

```json
{
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591475131,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:334",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591475131,
      "name": "iommu_read_l2",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
u32 iommu_read_l2(struct amd_iommu * iommu, u8 address)
```

```json
{
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591416368,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:330",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591416368,
      "name": "iommu_read_l2",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
u32 iommu_read_l2(struct amd_iommu * iommu, u8 address)
```

```json
{
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592469715,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:347",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592469715,
      "name": "iommu_read_l2",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
u32 iommu_read_l2(struct amd_iommu * iommu, u8 address)
```

```json
{
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594339504,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:351",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594339504,
      "name": "iommu_read_l2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071628067318,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:343",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:iommu_init_pci",
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
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619833381,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:351",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:iommu_init_pci",
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
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071622142042,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:336",
      "file": "drivers/iommu/amd/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/init.c:iommu_init_pci",
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
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604976720,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:316",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
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
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604941021,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:316",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
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
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605057420,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:316",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
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
  "name": "iommu_read_l2",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605081291,
      "name": "iommu_read_l2",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:316",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
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
u32 iommu_read_l2(struct amd_iommu * iommu, u8 address)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
u32 iommu_read_l2(struct amd_iommu * iommu, u8 address)
```
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
u32 iommu_read_l2(struct amd_iommu * iommu, u8 address)
```
</details>
</li>
</ul>
