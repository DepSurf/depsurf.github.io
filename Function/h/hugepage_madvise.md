# Function: <code>hugepage_madvise</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580909424,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/huge_memory.c:1995",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:SyS_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580909424,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581059904,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:301",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:SyS_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581059904,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581135168,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:303",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:SyS_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581135168,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581182352,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:305",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:SyS_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581182352,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581311520,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:306",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:SyS_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581311520,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581458256,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:306",
      "file": "mm/khugepaged.c",
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
      "addr": 18446744071581458256,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581541936,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:306",
      "file": "mm/khugepaged.c",
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
      "addr": 18446744071581541936,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581650960,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:306",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581650960,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581719568,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:313",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581719568,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581938704,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:342",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581938704,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581985696,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:347",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581985696,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582013456,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:347",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582013456,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582316176,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:347",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582316176,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582808064,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:347",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_vma_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582808064,
      "name": "hugepage_madvise",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583348896,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:352",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_vma_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583348896,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583568160,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:355",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_vma_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583568160,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583760752,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:349",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_vma_behavior"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583760752,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493166968,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:313",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__arm64_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493166968,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
  "name": "hugepage_madvise",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226699484,
      "name": "hugepage_madvise",
      "external": false,
      "loc": "include/linux/huge_mm.h:344",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
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
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286660368,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:313",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__se_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286660368,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
  "name": "hugepage_madvise",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272831996,
      "name": "hugepage_madvise",
      "external": false,
      "loc": "include/linux/huge_mm.h:344",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581688304,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:313",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581688304,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581627360,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:313",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581627360,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581679616,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:313",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581679616,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```

```json
{
  "name": "hugepage_madvise",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581746336,
      "name": "hugepage_madvise",
      "external": true,
      "loc": "mm/khugepaged.c:313",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:__do_sys_madvise"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581746336,
      "name": "hugepage_madvise",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int hugepage_madvise(struct vm_area_struct * vma, long unsigned int * vm_flags, int advice)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
