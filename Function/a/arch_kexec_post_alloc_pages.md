# Function: <code>arch_kexec_post_alloc_pages</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```

```json
{
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579248864,
      "name": "arch_kexec_post_alloc_pages",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:609",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579248864,
      "name": "arch_kexec_post_alloc_pages",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```

```json
{
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579260992,
      "name": "arch_kexec_post_alloc_pages",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:559",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579260992,
      "name": "arch_kexec_post_alloc_pages",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```

```json
{
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579284752,
      "name": "arch_kexec_post_alloc_pages",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:559",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_alloc_control_pages",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579284752,
      "name": "arch_kexec_post_alloc_pages",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```

```json
{
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579299840,
      "name": "arch_kexec_post_alloc_pages",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:666",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_alloc_control_pages",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299840,
      "name": "arch_kexec_post_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```

```json
{
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579305392,
      "name": "arch_kexec_post_alloc_pages",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:666",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_alloc_control_pages",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305392,
      "name": "arch_kexec_post_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```

```json
{
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579334912,
      "name": "arch_kexec_post_alloc_pages",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:599",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_load_crash_segment",
        "kernel/kexec_core.c:kimage_alloc_crash_control_pages",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334912,
      "name": "arch_kexec_post_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```

```json
{
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579336496,
      "name": "arch_kexec_post_alloc_pages",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:599",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_load_crash_segment",
        "kernel/kexec_core.c:kimage_alloc_crash_control_pages",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579336496,
      "name": "arch_kexec_post_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```

```json
{
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579339200,
      "name": "arch_kexec_post_alloc_pages",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:599",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_load_crash_segment",
        "kernel/kexec_core.c:kimage_alloc_crash_control_pages",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579339200,
      "name": "arch_kexec_post_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```

```json
{
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579394576,
      "name": "arch_kexec_post_alloc_pages",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:570",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_load_crash_segment",
        "kernel/kexec_core.c:kimage_alloc_crash_control_pages",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394576,
      "name": "arch_kexec_post_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```

```json
{
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461152,
      "name": "arch_kexec_post_alloc_pages",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:579",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_load_crash_segment",
        "kernel/kexec_core.c:kimage_alloc_crash_control_pages",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461152,
      "name": "arch_kexec_post_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```

```json
{
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550560,
      "name": "arch_kexec_post_alloc_pages",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:579",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_load_crash_segment",
        "kernel/kexec_core.c:kimage_alloc_crash_control_pages",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550560,
      "name": "arch_kexec_post_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```

```json
{
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565712,
      "name": "arch_kexec_post_alloc_pages",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:568",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_load_crash_segment",
        "kernel/kexec_core.c:kimage_alloc_crash_control_pages",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565712,
      "name": "arch_kexec_post_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```

```json
{
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579593248,
      "name": "arch_kexec_post_alloc_pages",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:565",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_load_crash_segment",
        "kernel/kexec_core.c:kimage_alloc_crash_control_pages",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579593248,
      "name": "arch_kexec_post_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_kexec_post_alloc_pages",
      "external": false,
      "loc": "include/linux/kexec.h:386",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225485788,
      "name": "arch_kexec_post_alloc_pages",
      "external": false,
      "loc": "include/linux/kexec.h:386",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_control_pages"
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
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_kexec_post_alloc_pages",
      "external": false,
      "loc": "include/linux/kexec.h:386",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```

```json
{
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579301200,
      "name": "arch_kexec_post_alloc_pages",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:666",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_alloc_control_pages",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301200,
      "name": "arch_kexec_post_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```

```json
{
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579236640,
      "name": "arch_kexec_post_alloc_pages",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:666",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_alloc_control_pages",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236640,
      "name": "arch_kexec_post_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```

```json
{
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579302400,
      "name": "arch_kexec_post_alloc_pages",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:666",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_alloc_control_pages",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302400,
      "name": "arch_kexec_post_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```

```json
{
  "name": "arch_kexec_post_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579311232,
      "name": "arch_kexec_post_alloc_pages",
      "external": true,
      "loc": "arch/x86/kernel/machine_kexec_64.c:666",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_alloc_control_pages",
        "kernel/kexec_core.c:kimage_alloc_pages",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579311232,
      "name": "arch_kexec_post_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int arch_kexec_post_alloc_pages(void * vaddr, unsigned int pages, gfp_t gfp)
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
