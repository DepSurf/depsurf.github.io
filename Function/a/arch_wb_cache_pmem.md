# Function: <code>arch_wb_cache_pmem</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581493644,
      "name": "arch_wb_cache_pmem",
      "external": false,
      "loc": "arch/x86/include/asm/pmem.h:63",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:__dax_zero_page_range",
        "fs/dax.c:dax_do_io"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581576185,
      "name": "arch_wb_cache_pmem",
      "external": false,
      "loc": "arch/x86/include/asm/pmem.h:60",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor",
        "fs/dax.c:__dax_zero_page_range"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588271504,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:100",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588271504,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588827248,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:100",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588827248,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589205344,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:120",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589205344,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589446928,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:120",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589446928,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589904832,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:101",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589904832,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590130816,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:101",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590130816,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585135088,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:102",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585135088,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585286432,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:81",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585286432,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585170160,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:81",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585170160,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585623856,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:81",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585623856,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586782976,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:79",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586782976,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595949280,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:39",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595949280,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596466736,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:40",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596466736,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597361728,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:40",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597361728,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490343224,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/arm64/mm/flush.c:81",
      "file": "arch/arm64/mm/flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490343224,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282851200,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/powerpc/lib/pmem.c:15",
      "file": "arch/powerpc/lib/pmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282851200,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589733072,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:101",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589733072,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589458752,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:101",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589458752,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590176448,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:101",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590176448,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void arch_wb_cache_pmem(void * addr, size_t size)
```

```json
{
  "name": "arch_wb_cache_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590226896,
      "name": "arch_wb_cache_pmem",
      "external": true,
      "loc": "arch/x86/lib/usercopy_64.c:101",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/super.c:dax_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590226896,
      "name": "arch_wb_cache_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void arch_wb_cache_pmem(void * addr, size_t size)
```
</details>
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
void arch_wb_cache_pmem(void * addr, size_t size)
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
void arch_wb_cache_pmem(void * addr, size_t size)
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
