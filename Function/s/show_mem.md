# Function: <code>show_mem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void show_mem(unsigned int filter)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582979632,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:12",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc_failed",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582979632,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
void show_mem(unsigned int filter)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583268800,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:12",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:warn_alloc_failed",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268800,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void show_mem(unsigned int filter)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583387568,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:12",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583387568,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588237536,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:12",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588237536,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588788960,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:12",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588788960,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589167194,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:12",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589167194,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589397146,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:12",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589397146,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589853220,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:12",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589853220,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590079012,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:11",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590079012,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585076867,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:11",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585076867,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591382224,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:11",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591382224,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591324659,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:11",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:panic_show_mem",
        "kernel/panic.c:panic",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591324659,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592344134,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:11",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:panic_show_mem",
        "kernel/panic.c:panic",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592344134,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594205702,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:11",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:panic_show_mem",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594205702,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_mem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578854605,
      "name": "show_mem",
      "external": false,
      "loc": "include/linux/mm.h:2753",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:panic_show_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579803956,
      "name": "show_mem",
      "external": false,
      "loc": "include/linux/mm.h:2753",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589700213,
      "name": "show_mem",
      "external": false,
      "loc": "include/linux/mm.h:2753",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_handle_showmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589723413,
      "name": "show_mem",
      "external": false,
      "loc": "include/linux/mm.h:2753",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:fn_show_mem"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_mem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619234142,
      "name": "show_mem",
      "external": false,
      "loc": "include/linux/mm.h:3072",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:do_populate_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:dir_add",
        "init/initramfs.c:find_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579852089,
      "name": "show_mem",
      "external": false,
      "loc": "include/linux/mm.h:3072",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590004901,
      "name": "show_mem",
      "external": false,
      "loc": "include/linux/mm.h:3072",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_handle_showmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590028245,
      "name": "show_mem",
      "external": false,
      "loc": "include/linux/mm.h:3072",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:fn_show_mem"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_mem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621524284,
      "name": "show_mem",
      "external": false,
      "loc": "include/linux/mm.h:3198",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:do_populate_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:dir_add",
        "init/initramfs.c:find_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579889892,
      "name": "show_mem",
      "external": false,
      "loc": "include/linux/mm.h:3198",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590343333,
      "name": "show_mem",
      "external": false,
      "loc": "include/linux/mm.h:3198",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_handle_showmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590366773,
      "name": "show_mem",
      "external": false,
      "loc": "include/linux/mm.h:3198",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503857676,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:11",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503857676,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236478360,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:11",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236478360,
      "name": "show_mem",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297713916,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:11",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/xmon/xmon.c:cmds",
        "kernel/panic.c:panic",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297713916,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279748742,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:11",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279748742,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589681268,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:11",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589681268,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589407060,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:11",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589407060,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590124644,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:11",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590124644,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void show_mem(unsigned int filter, nodemask_t * nodemask)
```

```json
{
  "name": "show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590175028,
      "name": "show_mem",
      "external": true,
      "loc": "lib/show_mem.c:11",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590175028,
      "name": "show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>nodemask_t * nodemask</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void show_mem(unsigned int filter, nodemask_t * nodemask)
```
</details>
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
