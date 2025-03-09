# Function: <code>follow_page_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, unsigned int * page_mask)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580657488,
      "name": "follow_page_mask",
      "external": true,
      "loc": "mm/gup.c:177",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:break_ksm",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:SyS_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580657488,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 888
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
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, unsigned int * page_mask)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580765728,
      "name": "follow_page_mask",
      "external": true,
      "loc": "mm/gup.c:214",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:SyS_move_pages",
        "mm/migrate.c:do_pages_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580765728,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1303
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
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, unsigned int * page_mask)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580831296,
      "name": "follow_page_mask",
      "external": true,
      "loc": "mm/gup.c:224",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:SYSC_move_pages",
        "mm/migrate.c:do_pages_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580831296,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, unsigned int * page_mask)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580873792,
      "name": "follow_page_mask",
      "external": true,
      "loc": "mm/gup.c:363",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:SYSC_move_pages",
        "mm/migrate.c:do_pages_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580873792,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1492
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, unsigned int * page_mask)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580969920,
      "name": "follow_page_mask",
      "external": true,
      "loc": "mm/gup.c:381",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:SYSC_move_pages",
        "mm/migrate.c:do_pages_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969920,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, unsigned int * page_mask)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581103056,
      "name": "follow_page_mask",
      "external": true,
      "loc": "mm/gup.c:397",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:break_ksm",
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:do_pages_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103056,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1900
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
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581182832,
      "name": "follow_page_mask",
      "external": true,
      "loc": "mm/gup.c:402",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581182832,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1956
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581255104,
      "name": "follow_page_mask",
      "external": false,
      "loc": "mm/gup.c:519",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581255104,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581313776,
      "name": "follow_page_mask",
      "external": false,
      "loc": "mm/gup.c:518",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581313776,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
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
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581503600,
      "name": "follow_page_mask",
      "external": false,
      "loc": "mm/gup.c:752",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503600,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581543760,
      "name": "follow_page_mask",
      "external": false,
      "loc": "mm/gup.c:716",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543760,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581566848,
      "name": "follow_page_mask",
      "external": false,
      "loc": "mm/gup.c:801",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566848,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "follow_page_mask",
      "external": false,
      "loc": "mm/gup.c:824",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831632,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
    },
    {
      "addr": 18446744071592198381,
      "name": "follow_page_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "follow_page_mask",
      "external": false,
      "loc": "mm/gup.c:845",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224800,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071593974885,
      "name": "follow_page_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "follow_page_mask",
      "external": false,
      "loc": "mm/gup.c:779",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582714560,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071596031241,
      "name": "follow_page_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "follow_page_mask",
      "external": false,
      "loc": "mm/gup.c:809",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582928624,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    },
    {
      "addr": 18446744071596553229,
      "name": "follow_page_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "follow_page_mask",
      "external": false,
      "loc": "mm/gup.c:811",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583102752,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    },
    {
      "addr": 18446744071597457001,
      "name": "follow_page_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492721000,
      "name": "follow_page_mask",
      "external": false,
      "loc": "mm/gup.c:518",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492721000,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
  "name": "follow_page_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226552244,
      "name": "follow_page_mask",
      "external": false,
      "loc": "mm/gup.c:518",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
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
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286064832,
      "name": "follow_page_mask",
      "external": false,
      "loc": "mm/gup.c:518",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286064832,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 808
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
  "name": "follow_page_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272714082,
      "name": "follow_page_mask",
      "external": false,
      "loc": "mm/gup.c:518",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272714082,
      "name": "follow_page_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581282624,
      "name": "follow_page_mask",
      "external": false,
      "loc": "mm/gup.c:518",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581282624,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581228640,
      "name": "follow_page_mask",
      "external": false,
      "loc": "mm/gup.c:518",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581228640,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581273824,
      "name": "follow_page_mask",
      "external": false,
      "loc": "mm/gup.c:518",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581273824,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
```

```json
{
  "name": "follow_page_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581337696,
      "name": "follow_page_mask",
      "external": false,
      "loc": "mm/gup.c:518",
      "file": "mm/gup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581337696,
      "name": "follow_page_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct follow_page_context * ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int * page_mask</code>
</li>
</ul>
</details>
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
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
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
struct page * follow_page_mask(struct vm_area_struct * vma, long unsigned int address, unsigned int flags, struct follow_page_context * ctx)
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
