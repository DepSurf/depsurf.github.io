# Function: <code>arch_pick_mmap_base</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void arch_pick_mmap_base(long unsigned int * base, long unsigned int * legacy_base, long unsigned int random_factor, long unsigned int task_size)
```

```json
{
  "name": "arch_pick_mmap_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579313440,
      "name": "arch_pick_mmap_base",
      "external": false,
      "loc": "arch/x86/mm/mmap.c:126",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313440,
      "name": "arch_pick_mmap_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
void arch_pick_mmap_base(long unsigned int * base, long unsigned int * legacy_base, long unsigned int random_factor, long unsigned int task_size)
```

```json
{
  "name": "arch_pick_mmap_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579336096,
      "name": "arch_pick_mmap_base",
      "external": false,
      "loc": "arch/x86/mm/mmap.c:128",
      "file": "arch/x86/mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579336096,
      "name": "arch_pick_mmap_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
  "name": "arch_pick_mmap_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579347518,
      "name": "arch_pick_mmap_base",
      "external": false,
      "loc": "arch/x86/mm/mmap.c:129",
      "file": "arch/x86/mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
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
  "name": "arch_pick_mmap_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579374462,
      "name": "arch_pick_mmap_base",
      "external": false,
      "loc": "arch/x86/mm/mmap.c:129",
      "file": "arch/x86/mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
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
  "name": "arch_pick_mmap_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579389915,
      "name": "arch_pick_mmap_base",
      "external": false,
      "loc": "arch/x86/mm/mmap.c:116",
      "file": "arch/x86/mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
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
  "name": "arch_pick_mmap_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579393227,
      "name": "arch_pick_mmap_base",
      "external": false,
      "loc": "arch/x86/mm/mmap.c:116",
      "file": "arch/x86/mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_pick_mmap_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579407390,
      "name": "arch_pick_mmap_base",
      "external": false,
      "loc": "arch/x86/mm/mmap.c:118",
      "file": "arch/x86/mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
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
  "name": "arch_pick_mmap_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579407870,
      "name": "arch_pick_mmap_base",
      "external": false,
      "loc": "arch/x86/mm/mmap.c:118",
      "file": "arch/x86/mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_pick_mmap_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579411217,
      "name": "arch_pick_mmap_base",
      "external": false,
      "loc": "arch/x86/mm/mmap.c:118",
      "file": "arch/x86/mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
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
  "name": "arch_pick_mmap_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579474010,
      "name": "arch_pick_mmap_base",
      "external": false,
      "loc": "arch/x86/mm/mmap.c:118",
      "file": "arch/x86/mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
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
  "name": "arch_pick_mmap_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579551575,
      "name": "arch_pick_mmap_base",
      "external": false,
      "loc": "arch/x86/mm/mmap.c:118",
      "file": "arch/x86/mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
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
  "name": "arch_pick_mmap_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579658183,
      "name": "arch_pick_mmap_base",
      "external": false,
      "loc": "arch/x86/mm/mmap.c:118",
      "file": "arch/x86/mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
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
  "name": "arch_pick_mmap_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579672407,
      "name": "arch_pick_mmap_base",
      "external": false,
      "loc": "arch/x86/mm/mmap.c:118",
      "file": "arch/x86/mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
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
  "name": "arch_pick_mmap_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579706295,
      "name": "arch_pick_mmap_base",
      "external": false,
      "loc": "arch/x86/mm/mmap.c:118",
      "file": "arch/x86/mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
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
  "name": "arch_pick_mmap_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579389131,
      "name": "arch_pick_mmap_base",
      "external": false,
      "loc": "arch/x86/mm/mmap.c:116",
      "file": "arch/x86/mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
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
  "name": "arch_pick_mmap_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579318683,
      "name": "arch_pick_mmap_base",
      "external": false,
      "loc": "arch/x86/mm/mmap.c:116",
      "file": "arch/x86/mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
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
  "name": "arch_pick_mmap_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579389051,
      "name": "arch_pick_mmap_base",
      "external": false,
      "loc": "arch/x86/mm/mmap.c:116",
      "file": "arch/x86/mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
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
  "name": "arch_pick_mmap_base",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579397579,
      "name": "arch_pick_mmap_base",
      "external": false,
      "loc": "arch/x86/mm/mmap.c:116",
      "file": "arch/x86/mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout",
        "arch/x86/mm/mmap.c:arch_pick_mmap_layout"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void arch_pick_mmap_base(long unsigned int * base, long unsigned int * legacy_base, long unsigned int random_factor, long unsigned int task_size)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void arch_pick_mmap_base(long unsigned int * base, long unsigned int * legacy_base, long unsigned int random_factor, long unsigned int task_size)
```
</details>
</li>
</ul>
