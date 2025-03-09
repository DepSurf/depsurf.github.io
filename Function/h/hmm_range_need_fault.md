# Function: <code>hmm_range_need_fault</code>

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
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581545046,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:404",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581542688,
      "name": "hmm_range_need_fault.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581628098,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:422",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581627168,
      "name": "hmm_range_need_fault.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581748952,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:414",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581743120,
      "name": "hmm_range_need_fault.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581821064,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:357",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581816896,
      "name": "hmm_range_need_fault.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int hmm_range_need_fault(const struct hmm_vma_walk * hmm_vma_walk, const long unsigned int * hmm_pfns, long unsigned int npages, long unsigned int cpu_flags)
```

```json
{
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582034896,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:118",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_test",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_handle_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582034896,
      "name": "hmm_range_need_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int hmm_range_need_fault(const struct hmm_vma_walk * hmm_vma_walk, const long unsigned int * hmm_pfns, long unsigned int npages, long unsigned int cpu_flags)
```

```json
{
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582083744,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:119",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_test",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_handle_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582083744,
      "name": "hmm_range_need_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int hmm_range_need_fault(const struct hmm_vma_walk * hmm_vma_walk, const long unsigned int * hmm_pfns, long unsigned int npages, long unsigned int cpu_flags)
```

```json
{
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582108912,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:119",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_test",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582108912,
      "name": "hmm_range_need_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int hmm_range_need_fault(const struct hmm_vma_walk * hmm_vma_walk, const long unsigned int * hmm_pfns, long unsigned int npages, long unsigned int cpu_flags)
```

```json
{
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582425136,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:121",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_test",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582425136,
      "name": "hmm_range_need_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int hmm_range_need_fault(const struct hmm_vma_walk * hmm_vma_walk, const long unsigned int * hmm_pfns, long unsigned int npages, long unsigned int cpu_flags)
```

```json
{
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582940752,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:121",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_test",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940752,
      "name": "hmm_range_need_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int hmm_range_need_fault(const struct hmm_vma_walk * hmm_vma_walk, const long unsigned int * hmm_pfns, long unsigned int npages, long unsigned int cpu_flags)
```

```json
{
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583497520,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:121",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_test",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583497520,
      "name": "hmm_range_need_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int hmm_range_need_fault(const struct hmm_vma_walk * hmm_vma_walk, const long unsigned int * hmm_pfns, long unsigned int npages, long unsigned int cpu_flags)
```

```json
{
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583712528,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:121",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_test",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583712528,
      "name": "hmm_range_need_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int hmm_range_need_fault(const struct hmm_vma_walk * hmm_vma_walk, const long unsigned int * hmm_pfns, long unsigned int npages, long unsigned int cpu_flags)
```

```json
{
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583912784,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:121",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_test",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_handle_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583912784,
      "name": "hmm_range_need_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493282648,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:357",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole",
        "mm/hmm.c:hmm_vma_walk_hole"
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
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226886848,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:357",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hole",
        "mm/hmm.c:hmm_vma_walk_hole"
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
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286818624,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:357",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286814752,
      "name": "hmm_range_need_fault.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273030778,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:357",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hole",
        "mm/hmm.c:hmm_vma_walk_hole"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581789800,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:357",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785632,
      "name": "hmm_range_need_fault.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581727483,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:357",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581723792,
      "name": "hmm_range_need_fault.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581781112,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:357",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581776944,
      "name": "hmm_range_need_fault.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hmm_range_need_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581850120,
      "name": "hmm_range_need_fault",
      "external": false,
      "loc": "mm/hmm.c:357",
      "file": "mm/hmm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ],
      "caller_func": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581845904,
      "name": "hmm_range_need_fault.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
unsigned int hmm_range_need_fault(const struct hmm_vma_walk * hmm_vma_walk, const long unsigned int * hmm_pfns, long unsigned int npages, long unsigned int cpu_flags)
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
