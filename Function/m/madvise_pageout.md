# Function: <code>madvise_pageout</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long int madvise_pageout(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_pageout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581480208,
      "name": "madvise_pageout",
      "external": false,
      "loc": "mm/madvise.c:540",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581480208,
      "name": "madvise_pageout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
long int madvise_pageout(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_pageout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581686400,
      "name": "madvise_pageout",
      "external": false,
      "loc": "mm/madvise.c:541",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581686400,
      "name": "madvise_pageout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
long int madvise_pageout(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_pageout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581731888,
      "name": "madvise_pageout",
      "external": false,
      "loc": "mm/madvise.c:546",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581731888,
      "name": "madvise_pageout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
long int madvise_pageout(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_pageout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581760416,
      "name": "madvise_pageout",
      "external": false,
      "loc": "mm/madvise.c:547",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581760416,
      "name": "madvise_pageout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
long int madvise_pageout(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_pageout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582042464,
      "name": "madvise_pageout",
      "external": false,
      "loc": "mm/madvise.c:549",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582042464,
      "name": "madvise_pageout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
long int madvise_pageout(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_pageout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582471408,
      "name": "madvise_pageout",
      "external": false,
      "loc": "mm/madvise.c:569",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_vma_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471408,
      "name": "madvise_pageout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
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
long int madvise_pageout(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_pageout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582987312,
      "name": "madvise_pageout",
      "external": false,
      "loc": "mm/madvise.c:581",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_vma_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582987312,
      "name": "madvise_pageout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
long int madvise_pageout(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_pageout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583198848,
      "name": "madvise_pageout",
      "external": false,
      "loc": "mm/madvise.c:593",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_vma_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583198848,
      "name": "madvise_pageout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
long int madvise_pageout(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_pageout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583433040,
      "name": "madvise_pageout",
      "external": false,
      "loc": "mm/madvise.c:590",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_vma_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583433040,
      "name": "madvise_pageout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long int madvise_pageout(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_pageout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492899512,
      "name": "madvise_pageout",
      "external": false,
      "loc": "mm/madvise.c:540",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__arm64_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492899512,
      "name": "madvise_pageout",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "madvise_pageout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226697740,
      "name": "madvise_pageout",
      "external": false,
      "loc": "mm/madvise.c:540",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__se_sys_madvise"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int madvise_pageout(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_pageout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286298640,
      "name": "madvise_pageout",
      "external": false,
      "loc": "mm/madvise.c:540",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__se_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286298640,
      "name": "madvise_pageout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
long int madvise_pageout(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_pageout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272828392,
      "name": "madvise_pageout",
      "external": false,
      "loc": "mm/madvise.c:540",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__se_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272828392,
      "name": "madvise_pageout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
long int madvise_pageout(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_pageout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581449056,
      "name": "madvise_pageout",
      "external": false,
      "loc": "mm/madvise.c:540",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581449056,
      "name": "madvise_pageout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
long int madvise_pageout(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_pageout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581391424,
      "name": "madvise_pageout",
      "external": false,
      "loc": "mm/madvise.c:540",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581391424,
      "name": "madvise_pageout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
long int madvise_pageout(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_pageout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581440256,
      "name": "madvise_pageout",
      "external": false,
      "loc": "mm/madvise.c:540",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581440256,
      "name": "madvise_pageout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
long int madvise_pageout(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_pageout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581504752,
      "name": "madvise_pageout",
      "external": false,
      "loc": "mm/madvise.c:540",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581504752,
      "name": "madvise_pageout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
long int madvise_pageout(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start_addr, long unsigned int end_addr)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int madvise_pageout(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start_addr, long unsigned int end_addr)
```
</details>
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
