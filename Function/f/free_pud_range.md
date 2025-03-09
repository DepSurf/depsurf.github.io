# Function: <code>free_pud_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580666903,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:435",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
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
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580776807,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:447",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
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
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580841585,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:445",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
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
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580887174,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:477",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
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
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580981593,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:478",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
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
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581116339,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:493",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
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
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581195107,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:236",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
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
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
```

```json
{
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581262368,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:238",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:free_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581262368,
      "name": "free_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
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
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
```

```json
{
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581321104,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:238",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:free_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321104,
      "name": "free_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
```

```json
{
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581515904,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:256",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:free_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581515904,
      "name": "free_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1177
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
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
```

```json
{
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581560832,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:258",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:free_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581560832,
      "name": "free_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1146
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
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
```

```json
{
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581584976,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:270",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:free_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581584976,
      "name": "free_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1164
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
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
```

```json
{
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581852320,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:269",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:free_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581852320,
      "name": "free_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1125
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
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
```

```json
{
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582245728,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:273",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:free_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582245728,
      "name": "free_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1155
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
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
```

```json
{
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582733248,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:217",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:free_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582733248,
      "name": "free_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1166
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
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
```

```json
{
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582952032,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:232",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:free_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582952032,
      "name": "free_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1175
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
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
```

```json
{
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583134304,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:230",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:free_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583134304,
      "name": "free_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1175
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
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492733568,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:238",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226563892,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:238",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
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
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286080948,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:238",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272722518,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:238",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
```

```json
{
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581289952,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:238",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:free_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581289952,
      "name": "free_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581240021,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:238",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pgd_range"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
```

```json
{
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581281152,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:238",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:free_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581281152,
      "name": "free_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
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
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
```

```json
{
  "name": "free_pud_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581344992,
      "name": "free_pud_range",
      "external": false,
      "loc": "mm/memory.c:238",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:free_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581344992,
      "name": "free_pud_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
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
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void free_pud_range(struct mmu_gather * tlb, p4d_t * p4d, long unsigned int addr, long unsigned int end, long unsigned int floor, long unsigned int ceiling)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
