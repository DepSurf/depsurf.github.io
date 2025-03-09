# Function: <code>amd_iommu_init_pci</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595269758,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1355",
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
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595452757,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1560",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int amd_iommu_init_pci()
```

```json
{
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595698667,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1680",
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
      "addr": 18446744071595698667,
      "name": "amd_iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1788
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
int amd_iommu_init_pci()
```

```json
{
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596629839,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1692",
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
      "addr": 18446744071596629839,
      "name": "amd_iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1856
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
int amd_iommu_init_pci()
```

```json
{
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602960014,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1837",
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
      "addr": 18446744071602960014,
      "name": "amd_iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1847
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603133133,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1838",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state"
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
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604937575,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1871",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_go_to_state"
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
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605046325,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1858",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605083146,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1878",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int amd_iommu_init_pci()
```

```json
{
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609363618,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1865",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609363618,
      "name": "amd_iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 150
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
int amd_iommu_init_pci()
```

```json
{
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612435878,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1979",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612435878,
      "name": "amd_iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 322
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
int amd_iommu_init_pci()
```

```json
{
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614576632,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1932",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614576632,
      "name": "amd_iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 544
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
int amd_iommu_init_pci()
```

```json
{
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615531649,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1946",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615531649,
      "name": "amd_iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 565
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
int amd_iommu_init_pci()
```

```json
{
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617336885,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1953",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617336885,
      "name": "amd_iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 613
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
int amd_iommu_init_pci()
```

```json
{
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628067888,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:2162",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628067888,
      "name": "amd_iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 820
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
int amd_iommu_init_pci()
```

```json
{
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619833920,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:2199",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619833920,
      "name": "amd_iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 826
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
int amd_iommu_init_pci()
```

```json
{
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622142608,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:2195",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:state_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622142608,
      "name": "amd_iommu_init_pci",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 780
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604982769,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1878",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604947070,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1878",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605063469,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1878",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_iommu_init_pci",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605087340,
      "name": "amd_iommu_init_pci",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1878",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int amd_iommu_init_pci()
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int amd_iommu_init_pci()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int amd_iommu_init_pci()
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
