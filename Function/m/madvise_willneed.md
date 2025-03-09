# Function: <code>madvise_willneed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580752138,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:220",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:SyS_madvise"
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
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580873609,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:224",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:SyS_madvise"
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
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580941577,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:224",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:SyS_madvise"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long int madvise_willneed(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580982976,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:261",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:SyS_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580982976,
      "name": "madvise_willneed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
long int madvise_willneed(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581085872,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:273",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:SyS_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581085872,
      "name": "madvise_willneed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
long int madvise_willneed(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581224016,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:273",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581224016,
      "name": "madvise_willneed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
long int madvise_willneed(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581307552,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:273",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581307552,
      "name": "madvise_willneed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
long int madvise_willneed(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581420240,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:273",
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
      "addr": 18446744071581420240,
      "name": "madvise_willneed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581482019,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:253",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_madvise"
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
long int madvise_willneed(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581687952,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:254",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581687952,
      "name": "madvise_willneed",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581733625,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:258",
      "file": "mm/madvise.c",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581761755,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:258",
      "file": "mm/madvise.c",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582044348,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:260",
      "file": "mm/madvise.c",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582483791,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:275",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_vma_behavior"
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
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582997689,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:274",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_vma_behavior"
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
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583206288,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:280",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_vma_behavior"
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
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583441856,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:261",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_vma_behavior"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492900696,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:253",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__arm64_sys_madvise"
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
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226698324,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:253",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286302016,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:253",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272831112,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:253",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581450867,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:253",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_madvise"
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
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581393187,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:253",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_madvise"
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
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581442067,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:253",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_madvise"
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
  "name": "madvise_willneed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581506547,
      "name": "madvise_willneed",
      "external": false,
      "loc": "mm/madvise.c:253",
      "file": "mm/madvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__do_sys_madvise"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
long int madvise_willneed(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start, long unsigned int end)
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
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
long int madvise_willneed(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long int madvise_willneed(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start, long unsigned int end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
long int madvise_willneed(struct vm_area_struct * vma, struct vm_area_struct * * prev, long unsigned int start, long unsigned int end)
```
</details>
</li>
</ul>
