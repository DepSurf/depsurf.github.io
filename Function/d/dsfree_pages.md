# Function: <code>dsfree_pages</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dsfree_pages(const void * buffer, size_t size)
```

```json
{
  "name": "dsfree_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578902136,
      "name": "dsfree_pages",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:328",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_bts_buffer"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_pebs_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578901856,
      "name": "dsfree_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dsfree_pages(const void * buffer, size_t size)
```

```json
{
  "name": "dsfree_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578904120,
      "name": "dsfree_pages",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:328",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_bts_buffer"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_pebs_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578903840,
      "name": "dsfree_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dsfree_pages(const void * buffer, size_t size)
```

```json
{
  "name": "dsfree_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578905352,
      "name": "dsfree_pages",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:328",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_bts_buffer"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_pebs_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578905072,
      "name": "dsfree_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
  "name": "dsfree_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578914375,
      "name": "dsfree_pages",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:328",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer"
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
  "name": "dsfree_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578916135,
      "name": "dsfree_pages",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:328",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer"
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
  "name": "dsfree_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578920994,
      "name": "dsfree_pages",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:329",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578915024,
      "name": "dsfree_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void dsfree_pages(const void * buffer, size_t size)
```

```json
{
  "name": "dsfree_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578915906,
      "name": "dsfree_pages",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:329",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_bts_buffer"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578911440,
      "name": "dsfree_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void dsfree_pages(const void * buffer, size_t size)
```

```json
{
  "name": "dsfree_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578920114,
      "name": "dsfree_pages",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:394",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_bts_buffer"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578915424,
      "name": "dsfree_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void dsfree_pages(const void * buffer, size_t size)
```

```json
{
  "name": "dsfree_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578924021,
      "name": "dsfree_pages",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:394",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_bts_buffer"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578918880,
      "name": "dsfree_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void dsfree_pages(const void * buffer, size_t size)
```

```json
{
  "name": "dsfree_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578925382,
      "name": "dsfree_pages",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:443",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_bts_buffer"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578925456,
      "name": "dsfree_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void dsfree_pages(const void * buffer, size_t size)
```

```json
{
  "name": "dsfree_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578941990,
      "name": "dsfree_pages",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:450",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_bts_buffer"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578942080,
      "name": "dsfree_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void dsfree_pages(const void * buffer, size_t size)
```

```json
{
  "name": "dsfree_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578940358,
      "name": "dsfree_pages",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:498",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_bts_buffer"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578940448,
      "name": "dsfree_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void dsfree_pages(const void * buffer, size_t size)
```

```json
{
  "name": "dsfree_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578963718,
      "name": "dsfree_pages",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:503",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_bts_buffer"
      ],
      "caller_func": [
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:alloc_pebs_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578963808,
      "name": "dsfree_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
  "name": "dsfree_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578916135,
      "name": "dsfree_pages",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:328",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer"
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
  "name": "dsfree_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578911431,
      "name": "dsfree_pages",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:328",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer"
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
  "name": "dsfree_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578916071,
      "name": "dsfree_pages",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:328",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer"
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
  "name": "dsfree_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578916599,
      "name": "dsfree_pages",
      "external": false,
      "loc": "arch/x86/events/intel/ds.c:328",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:reserve_ds_buffers",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_bts_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer",
        "arch/x86/events/intel/ds.c:release_pebs_buffer"
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void dsfree_pages(const void * buffer, size_t size)
```
</details>
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
void dsfree_pages(const void * buffer, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void dsfree_pages(const void * buffer, size_t size)
```
</details>
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
