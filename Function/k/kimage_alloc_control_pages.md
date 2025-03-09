# Function: <code>kimage_alloc_control_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579946304,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:451",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec.c:kimage_alloc_init",
        "kernel/kexec.c:kimage_alloc_init",
        "kernel/kexec.c:kimage_alloc_init",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946304,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579977328,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:471",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579977328,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580007824,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:473",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007824,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
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
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580015328,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:468",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015328,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580062416,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:478",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/kexec_file.c:SyS_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062416,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580119584,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:478",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580119584,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580166560,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:483",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580166560,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580212480,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:481",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580212480,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580260880,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:483",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580260880,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580331591,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:483",
      "file": "kernel/kexec_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo"
      ],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec.c:kimage_alloc_init",
        "kernel/kexec.c:kimage_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331488,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580317063,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:482",
      "file": "kernel/kexec_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo"
      ],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec.c:kimage_alloc_init",
        "kernel/kexec.c:kimage_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580316960,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580320535,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:483",
      "file": "kernel/kexec_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo"
      ],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec.c:kimage_alloc_init",
        "kernel/kexec.c:kimage_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580320432,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580475479,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:484",
      "file": "kernel/kexec_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo"
      ],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580475376,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580669351,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:484",
      "file": "kernel/kexec_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo"
      ],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec.c:kimage_alloc_init",
        "kernel/kexec.c:kimage_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669216,
      "name": "kimage_alloc_control_pages",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580939675,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:484",
      "file": "kernel/kexec_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo"
      ],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec.c:kimage_alloc_init",
        "kernel/kexec.c:kimage_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580939520,
      "name": "kimage_alloc_control_pages",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581026715,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:485",
      "file": "kernel/kexec_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo"
      ],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec.c:kimage_alloc_init",
        "kernel/kexec.c:kimage_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581026560,
      "name": "kimage_alloc_control_pages",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581124923,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:473",
      "file": "kernel/kexec_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo"
      ],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec.c:kimage_alloc_init",
        "kernel/kexec.c:kimage_alloc_init",
        "kernel/kexec_file.c:__do_sys_kexec_file_load",
        "kernel/kexec_file.c:__do_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581124768,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491503776,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:483",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__arm64_sys_kexec_file_load",
        "kernel/kexec_file.c:__arm64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491503776,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225485128,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:483",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225485128,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284463696,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:483",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:__se_sys_kexec_file_load",
        "kernel/kexec_file.c:__se_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284463696,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580229680,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:483",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580229680,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580177168,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:483",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580177168,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580221152,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:483",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580221152,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
```

```json
{
  "name": "kimage_alloc_control_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580273984,
      "name": "kimage_alloc_control_pages",
      "external": true,
      "loc": "kernel/kexec_core.c:483",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page",
        "kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580273984,
      "name": "kimage_alloc_control_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct page * kimage_alloc_control_pages(struct kimage * image, unsigned int order)
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
