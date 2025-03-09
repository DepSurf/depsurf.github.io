# Function: <code>pmd_mkinvalid</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_mkinvalid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579444325,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611908,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:628",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
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
  "name": "pmd_mkinvalid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579441925,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:627",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659236,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:627",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pmd_t pmd_mkinvalid(pmd_t pmd)
```

```json
{
  "name": "pmd_mkinvalid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579444805,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:627",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679888,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:627",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581679888,
      "name": "pmd_mkinvalid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pmd_t pmd_mkinvalid(pmd_t pmd)
```

```json
{
  "name": "pmd_mkinvalid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579509605,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:598",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581949168,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:598",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581949168,
      "name": "pmd_mkinvalid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pmd_t pmd_mkinvalid(pmd_t pmd)
```

```json
{
  "name": "pmd_mkinvalid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579555161,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:601",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_invalidate_ad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579593183,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:601",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582358560,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:601",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582358560,
      "name": "pmd_mkinvalid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pmd_t pmd_mkinvalid(pmd_t pmd)
```

```json
{
  "name": "pmd_mkinvalid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579661977,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:618",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_invalidate_ad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579704368,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:618",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582860784,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:618",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582860784,
      "name": "pmd_mkinvalid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_mkinvalid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579676153,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:619",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_invalidate_ad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579717856,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:619",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583077846,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:619",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
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
  "name": "pmd_mkinvalid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579710281,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:788",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_invalidate_ad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579752427,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:788",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583260102,
      "name": "pmd_mkinvalid",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:788",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
pmd_t pmd_mkinvalid(pmd_t pmd)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
pmd_t pmd_mkinvalid(pmd_t pmd)
```
</details>
</li>
</ul>
