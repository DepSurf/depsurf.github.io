# Function: <code>choose_new_asid</code>

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
  "name": "choose_new_asid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579346031,
      "name": "choose_new_asid",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:67",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "choose_new_asid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579357711,
      "name": "choose_new_asid",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:67",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "choose_new_asid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579384890,
      "name": "choose_new_asid",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:75",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "choose_new_asid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579400422,
      "name": "choose_new_asid",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:76",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "choose_new_asid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579403734,
      "name": "choose_new_asid",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:76",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
void choose_new_asid(struct mm_struct * next, u64 next_tlb_gen, u16 * new_asid, bool * need_flush)
```

```json
{
  "name": "choose_new_asid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579412240,
      "name": "choose_new_asid",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:206",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579412240,
      "name": "choose_new_asid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void choose_new_asid(struct mm_struct * next, u64 next_tlb_gen, u16 * new_asid, bool * need_flush)
```

```json
{
  "name": "choose_new_asid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579412912,
      "name": "choose_new_asid",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:205",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579412912,
      "name": "choose_new_asid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "choose_new_asid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579417047,
      "name": "choose_new_asid",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:206",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "choose_new_asid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579479985,
      "name": "choose_new_asid",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:213",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "choose_new_asid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579558930,
      "name": "choose_new_asid",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:214",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "choose_new_asid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579666178,
      "name": "choose_new_asid",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:214",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "choose_new_asid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579679959,
      "name": "choose_new_asid",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:218",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "choose_new_asid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579714407,
      "name": "choose_new_asid",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:219",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "choose_new_asid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579399638,
      "name": "choose_new_asid",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:76",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "choose_new_asid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579329095,
      "name": "choose_new_asid",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:76",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "choose_new_asid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579399558,
      "name": "choose_new_asid",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:76",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
  "name": "choose_new_asid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579408054,
      "name": "choose_new_asid",
      "external": false,
      "loc": "arch/x86/mm/tlb.c:76",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
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
void choose_new_asid(struct mm_struct * next, u64 next_tlb_gen, u16 * new_asid, bool * need_flush)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void choose_new_asid(struct mm_struct * next, u64 next_tlb_gen, u16 * new_asid, bool * need_flush)
```
</details>
</li>
</ul>
