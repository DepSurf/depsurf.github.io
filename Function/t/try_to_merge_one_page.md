# Function: <code>try_to_merge_one_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580832555,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1016",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_with_ksm_page"
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
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580958367,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:977",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_with_ksm_page"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581032032,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1006",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581032032,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1929
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581078896,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1164",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078896,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1963
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581190272,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1175",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581190272,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1885
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581335936,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1205",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581335936,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2049
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581419696,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1203",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581419696,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2104
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581530576,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1219",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581530576,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581595488,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1201",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595488,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581810128,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1201",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581810128,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581857728,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1202",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581857728,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581892832,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1200",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892832,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582187536,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1196",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582187536,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582648816,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1216",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582648816,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583171168,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1232",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583171168,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583387248,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1276",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583387248,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583629616,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1475",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629616,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 570
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493034080,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1201",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493034080,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1372
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226751464,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1201",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226751464,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286468736,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1201",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286468736,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272910346,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1201",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272910346,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1024
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581564224,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1201",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581564224,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581505792,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1201",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505792,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581555536,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1201",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581555536,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
```

```json
{
  "name": "try_to_merge_one_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581620576,
      "name": "try_to_merge_one_page",
      "external": false,
      "loc": "mm/ksm.c:1201",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581620576,
      "name": "try_to_merge_one_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int try_to_merge_one_page(struct vm_area_struct * vma, struct page * page, struct page * kpage)
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
