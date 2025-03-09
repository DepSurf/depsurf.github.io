# Function: <code>vmemmap_p4d_populate</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588304547,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:211",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588304547,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588869901,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:225",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588869901,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589248901,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:203",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589248901,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589491187,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:192",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589491187,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589952158,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:192",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589952158,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590179692,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:192",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590179692,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591197991,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:191",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591197991,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591692882,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:195",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591692882,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591635377,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:195",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591635377,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592809407,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:549",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592809407,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594710601,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:610",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_populate_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594710601,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596455872,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:220",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_populate_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596455872,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596997200,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:220",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_populate_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596997200,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597926672,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:220",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_populate_hugepages",
        "mm/sparse-vmemmap.c:vmemmap_populate_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597926672,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
pgd_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503922512,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:192",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503922512,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
pgd_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297818152,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:192",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297818152,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270897356,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:192",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270897356,
      "name": "vmemmap_p4d_populate",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 12
    }
  ]
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
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589781980,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:192",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589781980,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589504547,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:192",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589504547,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590225388,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:192",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590225388,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```

```json
{
  "name": "vmemmap_p4d_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590275746,
      "name": "vmemmap_p4d_populate",
      "external": true,
      "loc": "mm/sparse-vmemmap.c:192",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "mm/sparse-vmemmap.c:vmemmap_populate_basepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590275746,
      "name": "vmemmap_p4d_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```
</details>
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>p4d_t *</code> ➡️ <code>pgd_t *</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
p4d_t * vmemmap_p4d_populate(pgd_t * pgd, long unsigned int addr, int node)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>p4d_t *</code> ➡️ <code>pgd_t *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
