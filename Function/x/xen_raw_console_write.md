# Function: <code>xen_raw_console_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584086016,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:636",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_start_kernel",
        "arch/x86/xen/enlighten.c:xen_start_kernel",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu.c:xen_pt_check_e820",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584086016,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584416864,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:669",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_start_kernel",
        "arch/x86/xen/enlighten.c:xen_start_kernel",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584416864,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584599264,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:669",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_start_kernel",
        "arch/x86/xen/enlighten.c:xen_start_kernel",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584599264,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584681808,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:669",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584681808,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585094304,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:656",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585094304,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585328016,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:656",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585328016,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585451472,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:656",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585451472,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585667312,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:656",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585667312,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585808288,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:656",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585808288,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586539408,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:656",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586539408,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586650624,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:656",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586650624,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586534592,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:656",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586534592,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587073008,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:688",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587073008,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588376480,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:689",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376480,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589798832,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:701",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589798832,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590104176,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:716",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590104176,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590443616,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:734",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590443616,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498529112,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:656",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498529112,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585569280,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:656",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585569280,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585758688,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:656",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585758688,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void xen_raw_console_write(const char * str)
```

```json
{
  "name": "xen_raw_console_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585866592,
      "name": "xen_raw_console_write",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_xen.c:656",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_pt_check_e820",
        "drivers/tty/hvc/hvc_xen.c:xen_raw_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585866592,
      "name": "xen_raw_console_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_raw_console_write(const char * str)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_raw_console_write(const char * str)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_raw_console_write(const char * str)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void xen_raw_console_write(const char * str)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
