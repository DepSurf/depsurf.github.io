# Function: <code>cr4_read_shadow</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cr4_read_shadow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579347782,
      "name": "cr4_read_shadow",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:290",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush"
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
  "name": "cr4_read_shadow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579359478,
      "name": "cr4_read_shadow",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:335",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush"
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
  "name": "cr4_read_shadow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579386918,
      "name": "cr4_read_shadow",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush"
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
  "name": "cr4_read_shadow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579402403,
      "name": "cr4_read_shadow",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:325",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush"
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
  "name": "cr4_read_shadow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579405670,
      "name": "cr4_read_shadow",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:341",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush"
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
long unsigned int cr4_read_shadow()
```

```json
{
  "name": "cr4_read_shadow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579147840,
      "name": "cr4_read_shadow",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:412",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:itlb_multihit_show_state",
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579147840,
      "name": "cr4_read_shadow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 9
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
long unsigned int cr4_read_shadow()
```

```json
{
  "name": "cr4_read_shadow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579144928,
      "name": "cr4_read_shadow",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:414",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:itlb_multihit_show_state",
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579144928,
      "name": "cr4_read_shadow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 9
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
long unsigned int cr4_read_shadow()
```

```json
{
  "name": "cr4_read_shadow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579151280,
      "name": "cr4_read_shadow",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:413",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:itlb_multihit_show_state",
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579151280,
      "name": "cr4_read_shadow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 9
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
long unsigned int cr4_read_shadow()
```

```json
{
  "name": "cr4_read_shadow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579179792,
      "name": "cr4_read_shadow",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:421",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:itlb_multihit_show_state",
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579179792,
      "name": "cr4_read_shadow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 9
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
long unsigned int cr4_read_shadow()
```

```json
{
  "name": "cr4_read_shadow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579226624,
      "name": "cr4_read_shadow",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:477",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:itlb_multihit_show_state",
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579226624,
      "name": "cr4_read_shadow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long unsigned int cr4_read_shadow()
```

```json
{
  "name": "cr4_read_shadow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579285072,
      "name": "cr4_read_shadow",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:478",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:itlb_multihit_show_state",
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579285072,
      "name": "cr4_read_shadow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long unsigned int cr4_read_shadow()
```

```json
{
  "name": "cr4_read_shadow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291648,
      "name": "cr4_read_shadow",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:466",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:itlb_multihit_show_state",
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291648,
      "name": "cr4_read_shadow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long unsigned int cr4_read_shadow()
```

```json
{
  "name": "cr4_read_shadow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579320560,
      "name": "cr4_read_shadow",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:447",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:itlb_multihit_show_state",
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320560,
      "name": "cr4_read_shadow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
  "name": "cr4_read_shadow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579401574,
      "name": "cr4_read_shadow",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:341",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush"
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
  "name": "cr4_read_shadow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579331024,
      "name": "cr4_read_shadow",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:341",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush"
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
  "name": "cr4_read_shadow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579401494,
      "name": "cr4_read_shadow",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:341",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush"
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
  "name": "cr4_read_shadow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579410182,
      "name": "cr4_read_shadow",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:341",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:initialize_tlbstate_and_flush"
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
long unsigned int cr4_read_shadow()
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
