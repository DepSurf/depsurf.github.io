# Function: <code>mpx_unmap_tables</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpx_unmap_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579328372,
      "name": "mpx_unmap_tables",
      "external": false,
      "loc": "arch/x86/mm/mpx.c:974",
      "file": "arch/x86/mm/mpx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
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
  "name": "mpx_unmap_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579333812,
      "name": "mpx_unmap_tables",
      "external": false,
      "loc": "arch/x86/mm/mpx.c:974",
      "file": "arch/x86/mm/mpx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
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
  "name": "mpx_unmap_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579349092,
      "name": "mpx_unmap_tables",
      "external": false,
      "loc": "arch/x86/mm/mpx.c:973",
      "file": "arch/x86/mm/mpx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
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
  "name": "mpx_unmap_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579342916,
      "name": "mpx_unmap_tables",
      "external": false,
      "loc": "arch/x86/mm/mpx.c:966",
      "file": "arch/x86/mm/mpx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
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
  "name": "mpx_unmap_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579368046,
      "name": "mpx_unmap_tables",
      "external": false,
      "loc": "arch/x86/mm/mpx.c:860",
      "file": "arch/x86/mm/mpx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
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
  "name": "mpx_unmap_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579380606,
      "name": "mpx_unmap_tables",
      "external": false,
      "loc": "arch/x86/mm/mpx.c:860",
      "file": "arch/x86/mm/mpx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
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
  "name": "mpx_unmap_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579408174,
      "name": "mpx_unmap_tables",
      "external": false,
      "loc": "arch/x86/mm/mpx.c:848",
      "file": "arch/x86/mm/mpx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int mpx_unmap_tables(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "mpx_unmap_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579421696,
      "name": "mpx_unmap_tables",
      "external": false,
      "loc": "arch/x86/mm/mpx.c:848",
      "file": "arch/x86/mm/mpx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579421696,
      "name": "mpx_unmap_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1171
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
int mpx_unmap_tables(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "mpx_unmap_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579424864,
      "name": "mpx_unmap_tables",
      "external": false,
      "loc": "arch/x86/mm/mpx.c:848",
      "file": "arch/x86/mm/mpx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424864,
      "name": "mpx_unmap_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1171
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
int mpx_unmap_tables(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "mpx_unmap_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579420704,
      "name": "mpx_unmap_tables",
      "external": false,
      "loc": "arch/x86/mm/mpx.c:848",
      "file": "arch/x86/mm/mpx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420704,
      "name": "mpx_unmap_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1171
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
int mpx_unmap_tables(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "mpx_unmap_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579349840,
      "name": "mpx_unmap_tables",
      "external": false,
      "loc": "arch/x86/mm/mpx.c:848",
      "file": "arch/x86/mm/mpx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579349840,
      "name": "mpx_unmap_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1171
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
int mpx_unmap_tables(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "mpx_unmap_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579420624,
      "name": "mpx_unmap_tables",
      "external": false,
      "loc": "arch/x86/mm/mpx.c:848",
      "file": "arch/x86/mm/mpx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420624,
      "name": "mpx_unmap_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1171
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
int mpx_unmap_tables(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "mpx_unmap_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579429696,
      "name": "mpx_unmap_tables",
      "external": false,
      "loc": "arch/x86/mm/mpx.c:848",
      "file": "arch/x86/mm/mpx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579429696,
      "name": "mpx_unmap_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1196
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int mpx_unmap_tables(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int mpx_unmap_tables(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int mpx_unmap_tables(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int mpx_unmap_tables(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int mpx_unmap_tables(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int mpx_unmap_tables(struct mm_struct * mm, long unsigned int start, long unsigned int end)
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
