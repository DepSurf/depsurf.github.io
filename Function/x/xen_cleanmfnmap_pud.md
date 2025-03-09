# Function: <code>xen_cleanmfnmap_pud</code>

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
  "name": "xen_cleanmfnmap_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596305764,
      "name": "xen_cleanmfnmap_pud",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1148",
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
  "name": "xen_cleanmfnmap_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602623663,
      "name": "xen_cleanmfnmap_pud",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1121",
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
  "name": "xen_cleanmfnmap_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602792378,
      "name": "xen_cleanmfnmap_pud",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1150",
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
  "name": "xen_cleanmfnmap_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604586243,
      "name": "xen_cleanmfnmap_pud",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1160",
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
  "name": "xen_cleanmfnmap_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604681636,
      "name": "xen_cleanmfnmap_pud",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1160",
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
  "name": "xen_cleanmfnmap_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604694078,
      "name": "xen_cleanmfnmap_pud",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1160",
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
void xen_cleanmfnmap_pud(pud_t * pud, bool unpin)
```

```json
{
  "name": "xen_cleanmfnmap_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609044854,
      "name": "xen_cleanmfnmap_pud",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1160",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609044854,
      "name": "xen_cleanmfnmap_pud",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 211
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
void xen_cleanmfnmap_pud(pud_t * pud, bool unpin)
```

```json
{
  "name": "xen_cleanmfnmap_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612108210,
      "name": "xen_cleanmfnmap_pud",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1064",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612108210,
      "name": "xen_cleanmfnmap_pud",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 211
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
void xen_cleanmfnmap_pud(pud_t * pud, bool unpin)
```

```json
{
  "name": "xen_cleanmfnmap_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614247687,
      "name": "xen_cleanmfnmap_pud",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1064",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614247687,
      "name": "xen_cleanmfnmap_pud",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 419
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
void xen_cleanmfnmap_pud(pud_t * pud, bool unpin)
```

```json
{
  "name": "xen_cleanmfnmap_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615167809,
      "name": "xen_cleanmfnmap_pud",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1064",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615167809,
      "name": "xen_cleanmfnmap_pud",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 419
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
void xen_cleanmfnmap_pud(pud_t * pud, bool unpin)
```

```json
{
  "name": "xen_cleanmfnmap_pud",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616933834,
      "name": "xen_cleanmfnmap_pud",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1070",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616933834,
      "name": "xen_cleanmfnmap_pud",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 440
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
  "name": "xen_cleanmfnmap_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627539701,
      "name": "xen_cleanmfnmap_pud",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1070",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
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
  "name": "xen_cleanmfnmap_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619285877,
      "name": "xen_cleanmfnmap_pud",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1079",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
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
  "name": "xen_cleanmfnmap_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621578373,
      "name": "xen_cleanmfnmap_pud",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1079",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
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
  "name": "xen_cleanmfnmap_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604620359,
      "name": "xen_cleanmfnmap_pud",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1160",
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
  "name": "xen_cleanmfnmap_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604698174,
      "name": "xen_cleanmfnmap_pud",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1160",
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
  "name": "xen_cleanmfnmap_pud",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604698180,
      "name": "xen_cleanmfnmap_pud",
      "external": false,
      "loc": "arch/x86/xen/mmu_pv.c:1160",
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
void xen_cleanmfnmap_pud(pud_t * pud, bool unpin)
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
void xen_cleanmfnmap_pud(pud_t * pud, bool unpin)
```
</details>
</li>
</ul>
