# Function: <code>vma_adjust</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert)
```

```json
{
  "name": "vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580699776,
      "name": "vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:727",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:SyS_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580699776,
      "name": "vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1939
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
int vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert)
```

```json
{
  "name": "vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580813984,
      "name": "vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:619",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:SyS_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580813984,
      "name": "vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2026
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580881765,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:1983",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580903577,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:1983",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:SyS_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252135,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:1983",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580929351,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2054",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580948054,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2054",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:SyS_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581301617,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2054",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581029076,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2163",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581048854,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2163",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:SyS_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581441601,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2163",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581163807,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2252",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581186440,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2252",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581600289,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2252",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581243711,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2323",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581269381,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2323",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581686305,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2323",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581318250,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2318",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581344007,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2318",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581804455,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2318",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581377370,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581403351,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581876919,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581576618,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2537",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602619,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2537",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582102789,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2537",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581622122,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2547",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581649803,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2547",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582149429,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2547",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581643469,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2543",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581671039,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2543",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582174165,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2543",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581911466,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2572",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581940325,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2572",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582491509,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2572",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582317724,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2650",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582349335,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2650",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583013782,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2650",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582815119,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2818",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582850851,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2818",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583577172,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2818",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492784256,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492804876,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__arm64_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493349956,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226599964,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 3226617612,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__se_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 3226942588,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:setup_arg_pages",
        "fs/exec.c:setup_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286152328,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286181024,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__se_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286895868,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272755804,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272769824,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__se_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273076766,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581346218,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581372199,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581845655,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581289930,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315607,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581783319,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581337418,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363399,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581836967,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
  "name": "vma_adjust",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581401370,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581427303,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581906263,
      "name": "vma_adjust",
      "external": false,
      "loc": "include/linux/mm.h:2290",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert)
```
</details>
</li>
</ul>
