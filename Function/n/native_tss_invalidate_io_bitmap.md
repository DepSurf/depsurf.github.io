# Function: <code>native_tss_invalidate_io_bitmap</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_tss_invalidate_io_bitmap()
```

```json
{
  "name": "native_tss_invalidate_io_bitmap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578993628,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579108502,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:native_tss_update_io_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368320,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579368320,
      "name": "native_tss_invalidate_io_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_tss_invalidate_io_bitmap()
```

```json
{
  "name": "native_tss_invalidate_io_bitmap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578995548,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579108326,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:native_tss_update_io_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367328,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367328,
      "name": "native_tss_invalidate_io_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_tss_invalidate_io_bitmap()
```

```json
{
  "name": "native_tss_invalidate_io_bitmap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579004188,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579114928,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:native_tss_update_io_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371680,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371680,
      "name": "native_tss_invalidate_io_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_tss_invalidate_io_bitmap()
```

```json
{
  "name": "native_tss_invalidate_io_bitmap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579021884,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140224,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:native_tss_update_io_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579432944,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432944,
      "name": "native_tss_invalidate_io_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_tss_invalidate_io_bitmap()
```

```json
{
  "name": "native_tss_invalidate_io_bitmap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579040301,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579177874,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:native_tss_update_io_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579501840,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501840,
      "name": "native_tss_invalidate_io_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_tss_invalidate_io_bitmap()
```

```json
{
  "name": "native_tss_invalidate_io_bitmap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579069885,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579232648,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:native_tss_update_io_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579599120,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599120,
      "name": "native_tss_invalidate_io_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_tss_invalidate_io_bitmap()
```

```json
{
  "name": "native_tss_invalidate_io_bitmap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579069709,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579238520,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:native_tss_update_io_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579611840,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611840,
      "name": "native_tss_invalidate_io_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_tss_invalidate_io_bitmap()
```

```json
{
  "name": "native_tss_invalidate_io_bitmap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579094797,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267389,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:native_tss_update_io_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579641552,
      "name": "native_tss_invalidate_io_bitmap",
      "external": false,
      "loc": "arch/x86/include/asm/io_bitmap.h:22",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641552,
      "name": "native_tss_invalidate_io_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void native_tss_invalidate_io_bitmap()
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
