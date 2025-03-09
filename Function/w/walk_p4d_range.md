# Function: <code>walk_p4d_range</code>

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
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580951398,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:116",
      "file": "mm/pagewalk.c",
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
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581052745,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:117",
      "file": "mm/pagewalk.c",
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
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581191682,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:117",
      "file": "mm/pagewalk.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581274807,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:117",
      "file": "mm/pagewalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
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
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581349271,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:117",
      "file": "mm/pagewalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
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
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581409373,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:120",
      "file": "mm/pagewalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
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
int walk_p4d_range(pgd_t * pgd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581608928,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:168",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pagewalk.c:walk_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581608928,
      "name": "walk_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int walk_p4d_range(pgd_t * pgd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581656320,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:168",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pagewalk.c:walk_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581656320,
      "name": "walk_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int walk_p4d_range(pgd_t * pgd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581677824,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:168",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pagewalk.c:walk_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677824,
      "name": "walk_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int walk_p4d_range(pgd_t * pgd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581947008,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:213",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pagewalk.c:walk_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581947008,
      "name": "walk_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int walk_p4d_range(pgd_t * pgd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582356272,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:213",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pagewalk.c:walk_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582356272,
      "name": "walk_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
int walk_p4d_range(pgd_t * pgd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582858240,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:213",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pagewalk.c:walk_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582858240,
      "name": "walk_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
int walk_p4d_range(pgd_t * pgd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583073744,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:229",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pagewalk.c:walk_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583073744,
      "name": "walk_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
int walk_p4d_range(pgd_t * pgd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583255792,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:229",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/pagewalk.c:walk_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583255792,
      "name": "walk_p4d_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492808460,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:120",
      "file": "mm/pagewalk.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226619984,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:120",
      "file": "mm/pagewalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286187696,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:120",
      "file": "mm/pagewalk.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272771560,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:120",
      "file": "mm/pagewalk.c",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581378221,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:120",
      "file": "mm/pagewalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
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
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581320608,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:120",
      "file": "mm/pagewalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
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
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581369421,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:120",
      "file": "mm/pagewalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
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
  "name": "walk_p4d_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581433293,
      "name": "walk_p4d_range",
      "external": false,
      "loc": "mm/pagewalk.c:120",
      "file": "mm/pagewalk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
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
int walk_p4d_range(pgd_t * pgd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
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
