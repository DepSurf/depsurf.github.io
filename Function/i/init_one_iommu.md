# Function: <code>init_one_iommu</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_one_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596282378,
      "name": "init_one_iommu",
      "external": false,
      "loc": "arch/x86/events/amd/iommu.c:419",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "init_one_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602598633,
      "name": "init_one_iommu",
      "external": false,
      "loc": "arch/x86/events/amd/iommu.c:419",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "init_one_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602766999,
      "name": "init_one_iommu",
      "external": false,
      "loc": "arch/x86/events/amd/iommu.c:419",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
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
  "name": "init_one_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604561238,
      "name": "init_one_iommu",
      "external": false,
      "loc": "arch/x86/events/amd/iommu.c:419",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
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
  "name": "init_one_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604655280,
      "name": "init_one_iommu",
      "external": false,
      "loc": "arch/x86/events/amd/iommu.c:412",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
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
  "name": "init_one_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604667679,
      "name": "init_one_iommu",
      "external": false,
      "loc": "arch/x86/events/amd/iommu.c:412",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
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
int init_one_iommu(unsigned int idx)
```

```json
{
  "name": "init_one_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609018056,
      "name": "init_one_iommu",
      "external": false,
      "loc": "arch/x86/events/amd/iommu.c:412",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609018056,
      "name": "init_one_iommu",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 433
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
int init_one_iommu(unsigned int idx)
```

```json
{
  "name": "init_one_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612080357,
      "name": "init_one_iommu",
      "external": false,
      "loc": "arch/x86/events/amd/iommu.c:412",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612080357,
      "name": "init_one_iommu",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 433
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
int init_one_iommu(unsigned int idx)
```

```json
{
  "name": "init_one_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614218940,
      "name": "init_one_iommu",
      "external": false,
      "loc": "arch/x86/events/amd/iommu.c:418",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614218940,
      "name": "init_one_iommu",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 433
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
int init_one_iommu(unsigned int idx)
```

```json
{
  "name": "init_one_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615137135,
      "name": "init_one_iommu",
      "external": false,
      "loc": "arch/x86/events/amd/iommu.c:418",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615137135,
      "name": "init_one_iommu",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 433
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
int init_one_iommu(unsigned int idx)
```

```json
{
  "name": "init_one_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616901163,
      "name": "init_one_iommu",
      "external": false,
      "loc": "arch/x86/events/amd/iommu.c:418",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616901163,
      "name": "init_one_iommu",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 414
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
int init_one_iommu(unsigned int idx)
```

```json
{
  "name": "init_one_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627496432,
      "name": "init_one_iommu",
      "external": false,
      "loc": "arch/x86/events/amd/iommu.c:418",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627496432,
      "name": "init_one_iommu",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 454
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
int init_one_iommu(unsigned int idx)
```

```json
{
  "name": "init_one_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619240560,
      "name": "init_one_iommu",
      "external": false,
      "loc": "arch/x86/events/amd/iommu.c:418",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619240560,
      "name": "init_one_iommu",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 454
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
int init_one_iommu(unsigned int idx)
```

```json
{
  "name": "init_one_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621530624,
      "name": "init_one_iommu",
      "external": false,
      "loc": "arch/x86/events/amd/iommu.c:418",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621530624,
      "name": "init_one_iommu",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 501
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
  "name": "init_one_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604593951,
      "name": "init_one_iommu",
      "external": false,
      "loc": "arch/x86/events/amd/iommu.c:412",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
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
  "name": "init_one_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604585605,
      "name": "init_one_iommu",
      "external": false,
      "loc": "arch/x86/events/amd/iommu.c:412",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
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
  "name": "init_one_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604671775,
      "name": "init_one_iommu",
      "external": false,
      "loc": "arch/x86/events/amd/iommu.c:412",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
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
  "name": "init_one_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604671795,
      "name": "init_one_iommu",
      "external": false,
      "loc": "arch/x86/events/amd/iommu.c:412",
      "file": "arch/x86/events/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init"
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
int init_one_iommu(unsigned int idx)
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
