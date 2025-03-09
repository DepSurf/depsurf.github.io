# Function: <code>native_read_cr0</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578960120,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579256048,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256048,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578957032,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579255104,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255104,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578959112,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:18",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579268656,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:18",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268656,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578971912,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:18",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579265264,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:18",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265264,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578974616,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:19",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579282112,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:19",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579282112,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578976920,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:19",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579293600,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:19",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293600,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578975496,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:19",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579318592,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:19",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579318592,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578981784,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579333824,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579333824,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578984584,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579338064,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338064,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578994904,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:24",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579367792,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:24",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367792,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
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
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578996856,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:26",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579366816,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:26",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366816,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
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
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579005496,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:26",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579371184,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:26",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371184,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
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
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579022872,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:26",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579432400,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:26",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432400,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
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
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579041964,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:26",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579501408,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:26",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501408,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
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
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579071676,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:26",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579598512,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:26",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598512,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
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
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579071484,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:26",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579611264,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:26",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611264,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
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
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579096716,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:26",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579641040,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:26",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641040,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578984936,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579333968,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579333968,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578977406,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__show_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578981797,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_device_not_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604617288,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130166,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181837,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587640852,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578984520,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579333888,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579333888,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int native_read_cr0()
```

```json
{
  "name": "native_read_cr0",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578985176,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579342240,
      "name": "native_read_cr0",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:23",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579342240,
      "name": "native_read_cr0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long unsigned int native_read_cr0()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int native_read_cr0()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int native_read_cr0()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int native_read_cr0()
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
long unsigned int native_read_cr0()
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
