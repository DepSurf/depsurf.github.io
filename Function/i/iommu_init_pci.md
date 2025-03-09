# Function: <code>iommu_init_pci</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595269778,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1226",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:state_next"
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
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595452777,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1431",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:state_next"
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
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595698717,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1538",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596629902,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1549",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602960031,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1694",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585580541,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1694",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585580541,
      "name": "iommu_init_pci",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1515
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
int iommu_init_pci(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604935667,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1725",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604935667,
      "name": "iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1525
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
int iommu_init_pci(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605039525,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1712",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605039525,
      "name": "iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1570
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
int iommu_init_pci(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605076014,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1732",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605076014,
      "name": "iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1635
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
int iommu_init_pci(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609362512,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1727",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609362512,
      "name": "iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1106
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
int iommu_init_pci(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612435059,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1842",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612435059,
      "name": "iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 819
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
int iommu_init_pci(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614575292,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1796",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614575292,
      "name": "iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1340
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
int iommu_init_pci(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615530396,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1807",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615530396,
      "name": "iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1253
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
int iommu_init_pci(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617335656,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1814",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617335656,
      "name": "iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1229
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628066288,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:2008",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628066288,
      "name": "iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1576
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619832368,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:2043",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619832368,
      "name": "iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1528
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622141120,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:2057",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622141120,
      "name": "iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1469
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int iommu_init_pci(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604975637,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1732",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604975637,
      "name": "iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1635
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
int iommu_init_pci(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604939938,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1732",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604939938,
      "name": "iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1635
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
int iommu_init_pci(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605056337,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1732",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605056337,
      "name": "iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1635
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
int iommu_init_pci(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605080208,
      "name": "iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1732",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605080208,
      "name": "iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1635
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int iommu_init_pci(struct amd_iommu * iommu)
```
</details>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
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
int iommu_init_pci(struct amd_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int iommu_init_pci(struct amd_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int iommu_init_pci(struct amd_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int iommu_init_pci(struct amd_iommu * iommu)
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
