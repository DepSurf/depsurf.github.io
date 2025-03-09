# Function: <code>__vma_adjust</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580879312,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:664",
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
      "addr": 18446744071580879312,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2162
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580923984,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:680",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
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
      "addr": 18446744071580923984,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2097
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581023632,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:681",
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
      "addr": 18446744071581023632,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2097
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581158576,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:690",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581158576,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1993
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581238320,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:714",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581238320,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1993
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581312640,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:716",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581312640,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2065
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581371488,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:717",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371488,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2362
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570048,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:697",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__do_sys_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570048,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2618
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581615552,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:739",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__do_sys_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581615552,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2741
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581637936,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:743",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__do_sys_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581637936,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2733
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581905712,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:740",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__do_sys_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581905712,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2763
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582310656,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:746",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__do_sys_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582310656,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2894
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582807504,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:615",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__do_sys_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582807504,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2954
    }
  ]
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492778008,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:717",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__arm64_sys_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492778008,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2124
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226594432,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:717",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__se_sys_mremap",
        "fs/exec.c:setup_arg_pages",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226594432,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2452
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286145200,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:717",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__se_sys_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286145200,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2748
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272751526,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:717",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__se_sys_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272751526,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1482
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581340336,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:717",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581340336,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2362
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581284048,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:717",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581284048,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2362
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581331536,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:717",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581331536,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2362
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
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```

```json
{
  "name": "__vma_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581395488,
      "name": "__vma_adjust",
      "external": true,
      "loc": "mm/mmap.c:717",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395488,
      "name": "__vma_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2362
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int __vma_adjust(struct vm_area_struct * vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct * insert, struct vm_area_struct * expand)
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
