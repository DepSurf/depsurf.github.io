# Function: <code>vma_wants_writenotify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vma_wants_writenotify(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580703856,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1493",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703856,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vma_wants_writenotify(struct vm_area_struct * vma)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580818048,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1384",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580818048,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580883568,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1537",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580883568,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580927856,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1554",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580927856,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581027504,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1570",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581027504,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581162288,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1629",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581162288,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581242160,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1653",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581242160,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581316672,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1655",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581316672,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581375776,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1663",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581375776,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581574480,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1639",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581574480,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581620016,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1678",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581620016,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581642432,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1682",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581642432,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581910416,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1668",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581910416,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582315648,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1677",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582315648,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582812832,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1501",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_numa_page",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812832,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583026496,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1492",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_numa_page",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/userfaultfd.c:uffd_wp_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583026496,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583209232,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1519",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_numa_page",
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/userfaultfd.c:uffd_wp_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583209232,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492781832,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1663",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492781832,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226598388,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1663",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226598388,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286150272,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1663",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286150272,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272754186,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1663",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272754186,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581344624,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1663",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581344624,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581288336,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1663",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288336,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581335824,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1663",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581335824,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int vma_wants_writenotify(struct vm_area_struct * vma, pgprot_t vm_page_prot)
```

```json
{
  "name": "vma_wants_writenotify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581399776,
      "name": "vma_wants_writenotify",
      "external": true,
      "loc": "mm/mmap.c:1663",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_set_page_prot",
        "mm/mprotect.c:mprotect_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581399776,
      "name": "vma_wants_writenotify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>pgprot_t vm_page_prot</code>
</li>
</ul>
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
