# Function: <code>remove_p4d_table</code>

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
  "name": "remove_p4d_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588292004,
      "name": "remove_p4d_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1058",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable"
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
  "name": "remove_p4d_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588857113,
      "name": "remove_p4d_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1066",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable"
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
  "name": "remove_p4d_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589234884,
      "name": "remove_p4d_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1080",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable"
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
  "name": "remove_p4d_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589478733,
      "name": "remove_p4d_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1073",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable"
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
  "name": "remove_p4d_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589939219,
      "name": "remove_p4d_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1140",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable"
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
  "name": "remove_p4d_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590166771,
      "name": "remove_p4d_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1140",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable"
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
void remove_p4d_table(p4d_t * p4d_start, long unsigned int addr, long unsigned int end, struct vmem_altmap * altmap, bool direct)
```

```json
{
  "name": "remove_p4d_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591183073,
      "name": "remove_p4d_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1148",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591183073,
      "name": "remove_p4d_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void remove_p4d_table(p4d_t * p4d_start, long unsigned int addr, long unsigned int end, struct vmem_altmap * altmap, bool direct)
```

```json
{
  "name": "remove_p4d_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591678426,
      "name": "remove_p4d_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1142",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591678426,
      "name": "remove_p4d_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void remove_p4d_table(p4d_t * p4d_start, long unsigned int addr, long unsigned int end, struct vmem_altmap * altmap, bool direct)
```

```json
{
  "name": "remove_p4d_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591622016,
      "name": "remove_p4d_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1184",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591622016,
      "name": "remove_p4d_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
void remove_p4d_table(p4d_t * p4d_start, long unsigned int addr, long unsigned int end, struct vmem_altmap * altmap, bool direct)
```

```json
{
  "name": "remove_p4d_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592795262,
      "name": "remove_p4d_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1185",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592795262,
      "name": "remove_p4d_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
void remove_p4d_table(p4d_t * p4d_start, long unsigned int addr, long unsigned int end, struct vmem_altmap * altmap, bool direct)
```

```json
{
  "name": "remove_p4d_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594695153,
      "name": "remove_p4d_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1185",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594695153,
      "name": "remove_p4d_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
void remove_p4d_table(p4d_t * p4d_start, long unsigned int addr, long unsigned int end, struct vmem_altmap * altmap, bool direct)
```

```json
{
  "name": "remove_p4d_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596432832,
      "name": "remove_p4d_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1186",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596432832,
      "name": "remove_p4d_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
void remove_p4d_table(p4d_t * p4d_start, long unsigned int addr, long unsigned int end, struct vmem_altmap * altmap, bool direct)
```

```json
{
  "name": "remove_p4d_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596973600,
      "name": "remove_p4d_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1186",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596973600,
      "name": "remove_p4d_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
void remove_p4d_table(p4d_t * p4d_start, long unsigned int addr, long unsigned int end, struct vmem_altmap * altmap, bool direct)
```

```json
{
  "name": "remove_p4d_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597902032,
      "name": "remove_p4d_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1186",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597902032,
      "name": "remove_p4d_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
  "name": "remove_p4d_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589769059,
      "name": "remove_p4d_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1140",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable"
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
  "name": "remove_p4d_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589491817,
      "name": "remove_p4d_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1140",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable"
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
  "name": "remove_p4d_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590212467,
      "name": "remove_p4d_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1140",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable"
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
  "name": "remove_p4d_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590262835,
      "name": "remove_p4d_table",
      "external": false,
      "loc": "arch/x86/mm/init_64.c:1140",
      "file": "arch/x86/mm/init_64.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable"
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
void remove_p4d_table(p4d_t * p4d_start, long unsigned int addr, long unsigned int end, struct vmem_altmap * altmap, bool direct)
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
