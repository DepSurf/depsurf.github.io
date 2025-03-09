# Function: <code>madvise_free_single_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580870256,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:410",
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
      "addr": 18446744071580870256,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580938176,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:411",
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
      "addr": 18446744071580938176,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580982160,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:448",
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
      "addr": 18446744071580982160,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581084864,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:458",
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
      "addr": 18446744071581084864,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581223664,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:458",
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
      "addr": 18446744071581223664,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581306512,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:458",
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
      "addr": 18446744071581306512,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581419168,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:458",
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
      "addr": 18446744071581419168,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581480496,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:699",
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
      "addr": 18446744071581480496,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581684880,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:700",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684880,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581730640,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:705",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581730640,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581759216,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:706",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581759216,
      "name": "madvise_free_single_vma",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582041264,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:708",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041264,
      "name": "madvise_free_single_vma",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582472736,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:731",
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
      "addr": 18446744071582472736,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582986176,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:751",
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
      "addr": 18446744071582986176,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583197696,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:765",
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
      "addr": 18446744071583197696,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583434304,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:759",
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
      "addr": 18446744071583434304,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 827
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492899832,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:699",
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
      "addr": 18446603336492899832,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226694772,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:699",
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
      "addr": 3226694772,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286299040,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:699",
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
      "addr": 13835058055286299040,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272829974,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:699",
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
      "addr": 18446743936272829974,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581449344,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:699",
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
      "addr": 18446744071581449344,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581391712,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:699",
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
      "addr": 18446744071581391712,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581440544,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:699",
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
      "addr": 18446744071581440544,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```

```json
{
  "name": "madvise_free_single_vma",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581505040,
      "name": "madvise_free_single_vma",
      "external": false,
      "loc": "mm/madvise.c:699",
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
      "addr": 18446744071581505040,
      "name": "madvise_free_single_vma",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int madvise_free_single_vma(struct vm_area_struct * vma, long unsigned int start_addr, long unsigned int end_addr)
```
</details>
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
