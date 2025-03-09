# Function: <code>__thp_get_unmapped_area</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int __thp_get_unmapped_area(struct file * filp, long unsigned int len, loff_t off, long unsigned int flags, long unsigned int size)
```

```json
{
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581099632,
      "name": "__thp_get_unmapped_area",
      "external": true,
      "loc": "mm/huge_memory.c:502",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:thp_get_unmapped_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581099632,
      "name": "__thp_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
long unsigned int __thp_get_unmapped_area(struct file * filp, long unsigned int len, loff_t off, long unsigned int flags, long unsigned int size)
```

```json
{
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581148432,
      "name": "__thp_get_unmapped_area",
      "external": true,
      "loc": "mm/huge_memory.c:504",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:thp_get_unmapped_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581148432,
      "name": "__thp_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
long unsigned int __thp_get_unmapped_area(struct file * filp, long unsigned int len, loff_t off, long unsigned int flags, long unsigned int size)
```

```json
{
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581268928,
      "name": "__thp_get_unmapped_area",
      "external": true,
      "loc": "mm/huge_memory.c:504",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:thp_get_unmapped_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268928,
      "name": "__thp_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long unsigned int __thp_get_unmapped_area(struct file * filp, long unsigned int len, loff_t off, long unsigned int flags, long unsigned int size)
```

```json
{
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581417760,
      "name": "__thp_get_unmapped_area",
      "external": true,
      "loc": "mm/huge_memory.c:501",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:thp_get_unmapped_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581417760,
      "name": "__thp_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long unsigned int __thp_get_unmapped_area(struct file * filp, long unsigned int len, loff_t off, long unsigned int flags, long unsigned int size)
```

```json
{
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581503824,
      "name": "__thp_get_unmapped_area",
      "external": true,
      "loc": "mm/huge_memory.c:511",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:thp_get_unmapped_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503824,
      "name": "__thp_get_unmapped_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581605608,
      "name": "__thp_get_unmapped_area",
      "external": false,
      "loc": "mm/huge_memory.c:516",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:thp_get_unmapped_area"
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
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581676169,
      "name": "__thp_get_unmapped_area",
      "external": false,
      "loc": "mm/huge_memory.c:522",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:thp_get_unmapped_area"
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
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581894201,
      "name": "__thp_get_unmapped_area",
      "external": false,
      "loc": "mm/huge_memory.c:533",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:thp_get_unmapped_area"
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
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581940041,
      "name": "__thp_get_unmapped_area",
      "external": false,
      "loc": "mm/huge_memory.c:526",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:thp_get_unmapped_area"
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
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581965529,
      "name": "__thp_get_unmapped_area",
      "external": false,
      "loc": "mm/huge_memory.c:543",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:thp_get_unmapped_area"
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
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582268201,
      "name": "__thp_get_unmapped_area",
      "external": false,
      "loc": "mm/huge_memory.c:543",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:thp_get_unmapped_area"
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
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582749250,
      "name": "__thp_get_unmapped_area",
      "external": false,
      "loc": "mm/huge_memory.c:541",
      "file": "mm/huge_memory.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583282402,
      "name": "__thp_get_unmapped_area",
      "external": false,
      "loc": "mm/huge_memory.c:602",
      "file": "mm/huge_memory.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583501874,
      "name": "__thp_get_unmapped_area",
      "external": false,
      "loc": "mm/huge_memory.c:601",
      "file": "mm/huge_memory.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583696038,
      "name": "__thp_get_unmapped_area",
      "external": false,
      "loc": "mm/huge_memory.c:807",
      "file": "mm/huge_memory.c",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286597244,
      "name": "__thp_get_unmapped_area",
      "external": false,
      "loc": "mm/huge_memory.c:522",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:thp_get_unmapped_area"
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
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581644905,
      "name": "__thp_get_unmapped_area",
      "external": false,
      "loc": "mm/huge_memory.c:522",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:thp_get_unmapped_area"
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
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581585769,
      "name": "__thp_get_unmapped_area",
      "external": false,
      "loc": "mm/huge_memory.c:522",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:thp_get_unmapped_area"
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
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581636217,
      "name": "__thp_get_unmapped_area",
      "external": false,
      "loc": "mm/huge_memory.c:522",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:thp_get_unmapped_area"
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
  "name": "__thp_get_unmapped_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581703193,
      "name": "__thp_get_unmapped_area",
      "external": false,
      "loc": "mm/huge_memory.c:522",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:thp_get_unmapped_area"
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
long unsigned int __thp_get_unmapped_area(struct file * filp, long unsigned int len, loff_t off, long unsigned int flags, long unsigned int size)
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
long unsigned int __thp_get_unmapped_area(struct file * filp, long unsigned int len, loff_t off, long unsigned int flags, long unsigned int size)
```
</details>
</li>
</ul>
