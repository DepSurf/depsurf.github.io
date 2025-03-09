# Function: <code>xen_cleanmfnmap_p4d</code>

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
  "name": "xen_cleanmfnmap_p4d",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596305747,
      "name": "xen_cleanmfnmap_p4d",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1170",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
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
  "name": "xen_cleanmfnmap_p4d",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602623639,
      "name": "xen_cleanmfnmap_p4d",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1143",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
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
  "name": "xen_cleanmfnmap_p4d",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602792304,
      "name": "xen_cleanmfnmap_p4d",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1172",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
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
  "name": "xen_cleanmfnmap_p4d",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604586169,
      "name": "xen_cleanmfnmap_p4d",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1182",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
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
  "name": "xen_cleanmfnmap_p4d",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604681574,
      "name": "xen_cleanmfnmap_p4d",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1182",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
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
  "name": "xen_cleanmfnmap_p4d",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604694016,
      "name": "xen_cleanmfnmap_p4d",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1182",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
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
void xen_cleanmfnmap_p4d(p4d_t * p4d, bool unpin)
```

```json
{
  "name": "xen_cleanmfnmap_p4d",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609045065,
      "name": "xen_cleanmfnmap_p4d",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1182",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609045065,
      "name": "xen_cleanmfnmap_p4d",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 117
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
void xen_cleanmfnmap_p4d(p4d_t * p4d, bool unpin)
```

```json
{
  "name": "xen_cleanmfnmap_p4d",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612108421,
      "name": "xen_cleanmfnmap_p4d",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1086",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612108421,
      "name": "xen_cleanmfnmap_p4d",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 117
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
void xen_cleanmfnmap_p4d(p4d_t * p4d, bool unpin)
```

```json
{
  "name": "xen_cleanmfnmap_p4d",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614248106,
      "name": "xen_cleanmfnmap_p4d",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1086",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614248106,
      "name": "xen_cleanmfnmap_p4d",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 140
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
void xen_cleanmfnmap_p4d(p4d_t * p4d, bool unpin)
```

```json
{
  "name": "xen_cleanmfnmap_p4d",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615168228,
      "name": "xen_cleanmfnmap_p4d",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1086",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615168228,
      "name": "xen_cleanmfnmap_p4d",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 140
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
void xen_cleanmfnmap_p4d(p4d_t * p4d, bool unpin)
```

```json
{
  "name": "xen_cleanmfnmap_p4d",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616934274,
      "name": "xen_cleanmfnmap_p4d",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1092",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616934274,
      "name": "xen_cleanmfnmap_p4d",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 148
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
void xen_cleanmfnmap_p4d(p4d_t * p4d, bool unpin)
```

```json
{
  "name": "xen_cleanmfnmap_p4d",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627539600,
      "name": "xen_cleanmfnmap_p4d",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1092",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627539600,
      "name": "xen_cleanmfnmap_p4d",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 848
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
void xen_cleanmfnmap_p4d(p4d_t * p4d, bool unpin)
```

```json
{
  "name": "xen_cleanmfnmap_p4d",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619285776,
      "name": "xen_cleanmfnmap_p4d",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1101",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619285776,
      "name": "xen_cleanmfnmap_p4d",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 842
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
void xen_cleanmfnmap_p4d(p4d_t * p4d, bool unpin)
```

```json
{
  "name": "xen_cleanmfnmap_p4d",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621578272,
      "name": "xen_cleanmfnmap_p4d",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1101",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621578272,
      "name": "xen_cleanmfnmap_p4d",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 842
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
  "name": "xen_cleanmfnmap_p4d",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604620297,
      "name": "xen_cleanmfnmap_p4d",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1182",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_cleanmfnmap_p4d",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604698112,
      "name": "xen_cleanmfnmap_p4d",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1182",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
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
  "name": "xen_cleanmfnmap_p4d",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604698118,
      "name": "xen_cleanmfnmap_p4d",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1182",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
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
void xen_cleanmfnmap_p4d(p4d_t * p4d, bool unpin)
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
