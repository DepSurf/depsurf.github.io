# Function: <code>__do_sys_remap_file_pages</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581173168,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2817",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages"
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
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581253488,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2879",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages"
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
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581328368,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2885",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages"
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
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581387776,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2891",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_remap_file_pages(long unsigned int start, long unsigned int size, long unsigned int prot, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2901",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581583728,
      "name": "__do_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
    },
    {
      "addr": 18446744071581587399,
      "name": "__do_sys_remap_file_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_remap_file_pages(long unsigned int start, long unsigned int size, long unsigned int prot, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2964",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581629632,
      "name": "__do_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
    },
    {
      "addr": 18446744071591328379,
      "name": "__do_sys_remap_file_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_remap_file_pages(long unsigned int start, long unsigned int size, long unsigned int prot, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2968",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581653376,
      "name": "__do_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    },
    {
      "addr": 18446744071591270621,
      "name": "__do_sys_remap_file_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_remap_file_pages(long unsigned int start, long unsigned int size, long unsigned int prot, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2940",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581921376,
      "name": "__do_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 731
    },
    {
      "addr": 18446744071592200455,
      "name": "__do_sys_remap_file_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_remap_file_pages(long unsigned int start, long unsigned int size, long unsigned int prot, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2940",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582327872,
      "name": "__do_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 840
    },
    {
      "addr": 18446744071593977079,
      "name": "__do_sys_remap_file_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_remap_file_pages(long unsigned int start, long unsigned int size, long unsigned int prot, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2811",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582827568,
      "name": "__do_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 894
    },
    {
      "addr": 18446744071596032997,
      "name": "__do_sys_remap_file_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_remap_file_pages(long unsigned int start, long unsigned int size, long unsigned int prot, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2925",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583042944,
      "name": "__do_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 762
    },
    {
      "addr": 18446744071596554947,
      "name": "__do_sys_remap_file_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_remap_file_pages(long unsigned int start, long unsigned int size, long unsigned int prot, long unsigned int pgoff, long unsigned int flags)
```

```json
{
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:3014",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583224768,
      "name": "__do_sys_remap_file_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 761
    },
    {
      "addr": 18446744071597459052,
      "name": "__do_sys_remap_file_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492793444,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2891",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__arm64_sys_remap_file_pages"
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
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226609216,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2891",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__se_sys_remap_file_pages"
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
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286164356,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2891",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__se_sys_remap_file_pages"
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
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272762814,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2891",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__se_sys_remap_file_pages"
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
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581356624,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2891",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages"
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
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581300336,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2891",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages"
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
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581347824,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2891",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages"
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
  "name": "__do_sys_remap_file_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581411760,
      "name": "__do_sys_remap_file_pages",
      "external": false,
      "loc": "mm/mmap.c:2891",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages"
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
long int __do_sys_remap_file_pages(long unsigned int start, long unsigned int size, long unsigned int prot, long unsigned int pgoff, long unsigned int flags)
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
