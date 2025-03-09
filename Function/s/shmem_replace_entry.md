# Function: <code>shmem_replace_entry</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int shmem_replace_entry(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```

```json
{
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581073248,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:336",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581073248,
      "name": "shmem_replace_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int shmem_replace_entry(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```

```json
{
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136656,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:341",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136656,
      "name": "shmem_replace_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int shmem_replace_entry(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```

```json
{
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194400,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:356",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194400,
      "name": "shmem_replace_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581389789,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:355",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_delete_from_page_cache"
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
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581432781,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:414",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_delete_from_page_cache"
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
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581452589,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:414",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage"
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
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581706893,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:411",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage"
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
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582089535,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:409",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage"
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
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582559112,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:406",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_writepage"
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
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582765237,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:407",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_writepage"
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
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582940965,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:473",
      "file": "mm/shmem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_writepage"
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
int shmem_replace_entry(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```

```json
{
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492577368,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:356",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492577368,
      "name": "shmem_replace_entry",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int shmem_replace_entry(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```

```json
{
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226437736,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:356",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226437736,
      "name": "shmem_replace_entry",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int shmem_replace_entry(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```

```json
{
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285885952,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:356",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285885952,
      "name": "shmem_replace_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int shmem_replace_entry(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```

```json
{
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272616346,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:356",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272616346,
      "name": "shmem_replace_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int shmem_replace_entry(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```

```json
{
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581163248,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:356",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581163248,
      "name": "shmem_replace_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int shmem_replace_entry(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```

```json
{
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581110096,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:356",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581110096,
      "name": "shmem_replace_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int shmem_replace_entry(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```

```json
{
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581154448,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:356",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581154448,
      "name": "shmem_replace_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int shmem_replace_entry(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```

```json
{
  "name": "shmem_replace_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581217376,
      "name": "shmem_replace_entry",
      "external": false,
      "loc": "mm/shmem.c:356",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581217376,
      "name": "shmem_replace_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int shmem_replace_entry(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
```
</details>
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
int shmem_replace_entry(struct address_space * mapping, long unsigned int index, void * expected, void * replacement)
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
