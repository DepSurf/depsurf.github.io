# Function: <code>pcpu_get_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580617232,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:33",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_populate_chunk",
        "mm/percpu.c:pcpu_balance_workfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580617232,
      "name": "pcpu_get_pages.isra.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580720176,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:33",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580720176,
      "name": "pcpu_get_pages.isra.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580785952,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:33",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580785952,
      "name": "pcpu_get_pages.isra.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
struct page * * pcpu_get_pages()
```

```json
{
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580824480,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:32",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580824480,
      "name": "pcpu_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
struct page * * pcpu_get_pages()
```

```json
{
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580912592,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:32",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580912592,
      "name": "pcpu_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
struct page * * pcpu_get_pages()
```

```json
{
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581050320,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:32",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581050320,
      "name": "pcpu_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
struct page * * pcpu_get_pages()
```

```json
{
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581128000,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:32",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581128000,
      "name": "pcpu_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
struct page * * pcpu_get_pages()
```

```json
{
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581192816,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:31",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581192816,
      "name": "pcpu_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
struct page * * pcpu_get_pages()
```

```json
{
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581251264,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:31",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581251264,
      "name": "pcpu_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581444442,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:31",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
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
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581487343,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:31",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
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
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581511356,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:32",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
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
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581770511,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:32",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_reclaim_populated",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_populate_chunk"
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
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582149786,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:32",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_reclaim_populated",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_populate_chunk"
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
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582628181,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:32",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_reclaim_populated",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_populate_chunk"
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
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582837045,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:32",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_reclaim_populated",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_populate_chunk"
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
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583011989,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:32",
      "file": "mm/percpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_reclaim_populated",
        "mm/percpu.c:pcpu_balance_free",
        "mm/percpu.c:pcpu_populate_chunk"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct page * * pcpu_get_pages()
```

```json
{
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492650152,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:31",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492650152,
      "name": "pcpu_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct page * * pcpu_get_pages()
```

```json
{
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226491660,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:31",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226491660,
      "name": "pcpu_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct page * * pcpu_get_pages()
```

```json
{
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285969520,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:31",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285969520,
      "name": "pcpu_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct page * * pcpu_get_pages()
```

```json
{
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272664296,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:31",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272664296,
      "name": "pcpu_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
struct page * * pcpu_get_pages()
```

```json
{
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581220112,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:31",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581220112,
      "name": "pcpu_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
struct page * * pcpu_get_pages()
```

```json
{
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581166816,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:31",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166816,
      "name": "pcpu_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
struct page * * pcpu_get_pages()
```

```json
{
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581211312,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:31",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581211312,
      "name": "pcpu_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
struct page * * pcpu_get_pages()
```

```json
{
  "name": "pcpu_get_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581274704,
      "name": "pcpu_get_pages",
      "external": false,
      "loc": "mm/percpu-vm.c:31",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_balance_workfn",
        "mm/percpu.c:pcpu_populate_chunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274704,
      "name": "pcpu_get_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
struct page * * pcpu_get_pages()
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct page * * pcpu_get_pages()
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
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
