# Function: <code>anon_vma_clone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580727520,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:257",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:copy_vma",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580727520,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580846800,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:258",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580846800,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917296,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:257",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917296,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580961632,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:259",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580961632,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581063952,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:260",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063952,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581202880,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:261",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581202880,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581286592,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:261",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581286592,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581361024,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:261",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581361024,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581420704,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:262",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581420704,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581622448,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:274",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581622448,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668656,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:274",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668656,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581690896,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:274",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581690896,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581962288,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:275",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581962288,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582382256,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:279",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582382256,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582885680,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:279",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:vma_expand",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582885680,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583100528,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:281",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_expand",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583100528,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583283248,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:281",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_expand",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583283248,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492820856,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:262",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492820856,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226627760,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:262",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226627760,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286204160,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:262",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286204160,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272778964,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:262",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272778964,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581389552,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:262",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581389552,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581332256,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:262",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581332256,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581380752,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:262",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581380752,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
int anon_vma_clone(struct vm_area_struct * dst, struct vm_area_struct * src)
```

```json
{
  "name": "anon_vma_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581444608,
      "name": "anon_vma_clone",
      "external": true,
      "loc": "mm/rmap.c:262",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:copy_vma",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581444608,
      "name": "anon_vma_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
