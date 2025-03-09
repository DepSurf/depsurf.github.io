# Function: <code>free_reserved_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int free_reserved_area(void * start, void * end, int poison, char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580504352,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:5792",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580504352,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
long unsigned int free_reserved_area(void * start, void * end, int poison, char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580586336,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:6419",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580586336,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
long unsigned int free_reserved_area(void * start, void * end, int poison, char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580653248,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:6458",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580653248,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
long unsigned int free_reserved_area(void * start, void * end, int poison, char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580686128,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:6753",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580686128,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
long unsigned int free_reserved_area(void * start, void * end, int poison, char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580769104,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:6766",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580769104,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int free_reserved_area(void * start, void * end, int poison, char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:6934",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580921133,
      "name": "free_reserved_area.cold.114",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580905312,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:7239",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997079,
      "name": "free_reserved_area.cold.118",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580979968,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:7441",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:free_initmem",
        "init/initramfs.c:free_initrd_mem",
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581418548,
      "name": "free_reserved_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071581411344,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:7471",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:free_initmem",
        "init/initramfs.c:free_initrd_mem",
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581479499,
      "name": "free_reserved_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071581472368,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:7500",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:free_initmem",
        "init/initramfs.c:free_initrd_mem",
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684489,
      "name": "free_reserved_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071581678400,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:7646",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:free_initmem",
        "init/initramfs.c:free_initrd_mem",
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591331389,
      "name": "free_reserved_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071581726224,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:7864",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:free_initmem",
        "init/initramfs.c:free_initrd_mem",
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591273536,
      "name": "free_reserved_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071581748368,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:8106",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:free_initmem",
        "init/initramfs.c:free_initrd_mem",
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592207517,
      "name": "free_reserved_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582028096,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:8292",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:free_initmem",
        "init/initramfs.c:free_initrd_mem",
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593985128,
      "name": "free_reserved_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582455360,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582969200,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:8466",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:free_initmem",
        "init/initramfs.c:free_initrd_mem",
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582969200,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583181632,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:5529",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:free_initmem",
        "init/initramfs.c:free_initrd_mem",
        "arch/x86/mm/init.c:free_initrd_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583181632,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583365664,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:5671",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:free_initmem",
        "init/initramfs.c:free_initrd_mem",
        "arch/x86/mm/init.c:free_initrd_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583365664,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492882760,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:7471",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:free_initmem",
        "init/initramfs.c:free_initrd_mem",
        "arch/arm64/mm/init.c:free_initrd_mem",
        "arch/arm64/mm/init.c:free_initmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492882760,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226682452,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:7471",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:free_initmem",
        "init/initramfs.c:free_initrd_mem",
        "arch/arm/mm/init.c:free_initrd_mem",
        "arch/arm/mm/init.c:free_initmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226682452,
      "name": "free_reserved_area",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286279040,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:7471",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:free_initmem",
        "init/initramfs.c:free_initrd_mem",
        "arch/powerpc/kernel/fadump.c:fadump_free_cpu_notes_buf",
        "arch/powerpc/mm/mem.c:free_initmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286279040,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272823854,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:7471",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:free_initmem",
        "init/initramfs.c:free_initrd_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272823854,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:7471",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:free_initmem",
        "init/initramfs.c:free_initrd_mem",
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448347,
      "name": "free_reserved_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071581441216,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:7471",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:free_initmem",
        "init/initramfs.c:free_initrd_mem",
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390715,
      "name": "free_reserved_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071581383600,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:7471",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:free_initmem",
        "init/initramfs.c:free_initrd_mem",
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581439547,
      "name": "free_reserved_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071581432416,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
long unsigned int free_reserved_area(void * start, void * end, int poison, const char * s)
```

```json
{
  "name": "free_reserved_area",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "free_reserved_area",
      "external": true,
      "loc": "mm/page_alloc.c:7471",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:free_initmem",
        "init/initramfs.c:free_initrd_mem",
        "arch/x86/mm/init.c:free_init_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581504043,
      "name": "free_reserved_area.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071581496912,
      "name": "free_reserved_area",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
<b>Param type changed. </b>
<code>char * s</code> ➡️ <code>const char * s</code>
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
