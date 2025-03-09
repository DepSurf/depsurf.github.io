# Function: <code>walk_pte_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580745709,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:6",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580864915,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:6",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580906883,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:6",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580952243,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:6",
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
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581052945,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:7",
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
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581192725,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:7",
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
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581275885,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:7",
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
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581350324,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:7",
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
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581408909,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:7",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int walk_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581606944,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:41",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581606944,
      "name": "walk_pte_range",
      "section": ".text",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int walk_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581654368,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:41",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581654368,
      "name": "walk_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
int walk_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581675856,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:41",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581675856,
      "name": "walk_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int walk_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:41",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581945040,
      "name": "walk_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
    },
    {
      "addr": 18446744071592201127,
      "name": "walk_pte_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int walk_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:41",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582354336,
      "name": "walk_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
    },
    {
      "addr": 18446744071593977826,
      "name": "walk_pte_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
bool walk_pte_range(pmd_t * pmd, long unsigned int start, long unsigned int end, struct mm_walk * args)
```

```json
{
  "name": "walk_pte_range",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/vmscan.c:3915",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:walk_pmd_range"
      ]
    },
    {
      "addr": 0,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:41",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582507872,
      "name": "walk_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 826
    },
    {
      "addr": 18446744071596026248,
      "name": "walk_pte_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582856304,
      "name": "walk_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
    },
    {
      "addr": 18446744071596033773,
      "name": "walk_pte_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
bool walk_pte_range(pmd_t * pmd, long unsigned int start, long unsigned int end, struct mm_walk * args)
```

```json
{
  "name": "walk_pte_range",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/vmscan.c:4003",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:walk_pmd_range"
      ]
    },
    {
      "addr": 0,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:41",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582704960,
      "name": "walk_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
    },
    {
      "addr": 18446744071596548333,
      "name": "walk_pte_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583071888,
      "name": "walk_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
    },
    {
      "addr": 18446744071596555819,
      "name": "walk_pte_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
bool walk_pte_range(pmd_t * pmd, long unsigned int start, long unsigned int end, struct mm_walk * args)
```

```json
{
  "name": "walk_pte_range",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/vmscan.c:3322",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:walk_pmd_range"
      ]
    },
    {
      "addr": 0,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:41",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582874480,
      "name": "walk_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 778
    },
    {
      "addr": 18446744071597451964,
      "name": "walk_pte_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583253872,
      "name": "walk_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
    },
    {
      "addr": 18446744071597459963,
      "name": "walk_pte_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492808780,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:7",
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
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226620184,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:7",
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
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286188868,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:7",
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
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272771726,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:7",
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
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581377757,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:7",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581321613,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:7",
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
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581368957,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:7",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "walk_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581432829,
      "name": "walk_pte_range",
      "external": false,
      "loc": "mm/pagewalk.c:7",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int walk_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
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
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int start</code>
</li>
<li>
<b>Param added. </b>
<code>struct mm_walk * args</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_walk * walk</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
