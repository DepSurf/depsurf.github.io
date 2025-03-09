# Function: <code>effective_prot</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "effective_prot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579367052,
      "name": "effective_prot",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:328",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
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
  "name": "effective_prot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579394685,
      "name": "effective_prot",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:354",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
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
  "name": "effective_prot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579408971,
      "name": "effective_prot",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:351",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
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
  "name": "effective_prot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579412155,
      "name": "effective_prot",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:351",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
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
void effective_prot(struct ptdump_state * pt_st, int level, u64 val)
```

```json
{
  "name": "effective_prot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579440944,
      "name": "effective_prot",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:251",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579440944,
      "name": "effective_prot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void effective_prot(struct ptdump_state * pt_st, int level, u64 val)
```

```json
{
  "name": "effective_prot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579439200,
      "name": "effective_prot",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:251",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579439200,
      "name": "effective_prot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void effective_prot(struct ptdump_state * pt_st, int level, u64 val)
```

```json
{
  "name": "effective_prot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441984,
      "name": "effective_prot",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:251",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441984,
      "name": "effective_prot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void effective_prot(struct ptdump_state * pt_st, int level, u64 val)
```

```json
{
  "name": "effective_prot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506368,
      "name": "effective_prot",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:251",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506368,
      "name": "effective_prot",
      "section": ".text",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void effective_prot(struct ptdump_state * pt_st, int level, u64 val)
```

```json
{
  "name": "effective_prot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588560,
      "name": "effective_prot",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:251",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588560,
      "name": "effective_prot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void effective_prot(struct ptdump_state * pt_st, int level, u64 val)
```

```json
{
  "name": "effective_prot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579699136,
      "name": "effective_prot",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:251",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579699136,
      "name": "effective_prot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void effective_prot(struct ptdump_state * pt_st, int level, u64 val)
```

```json
{
  "name": "effective_prot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579713008,
      "name": "effective_prot",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:251",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713008,
      "name": "effective_prot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void effective_prot(struct ptdump_state * pt_st, int level, u64 val)
```

```json
{
  "name": "effective_prot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579747728,
      "name": "effective_prot",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:251",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579747728,
      "name": "effective_prot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
  "name": "effective_prot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579407995,
      "name": "effective_prot",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:351",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
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
  "name": "effective_prot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579337725,
      "name": "effective_prot",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:351",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core",
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
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
  "name": "effective_prot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579407915,
      "name": "effective_prot",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:351",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
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
  "name": "effective_prot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579416779,
      "name": "effective_prot",
      "external": false,
      "loc": "arch/x86/mm/dump_pagetables.c:351",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level",
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
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
void effective_prot(struct ptdump_state * pt_st, int level, u64 val)
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
