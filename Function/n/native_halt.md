# Function: <code>native_halt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579183264,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:52",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256304,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:52",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256304,
      "name": "native_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
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
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579183275,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:52",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255360,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:52",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255360,
      "name": "native_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
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
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579193787,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588101488,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:56",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588101488,
      "name": "native_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
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
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579191995,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:56",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588327120,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:56",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588327120,
      "name": "native_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
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
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579075913,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:57",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207796,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:57",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588893248,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:57",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588893248,
      "name": "native_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
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
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579081321,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:60",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219172,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:60",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589271456,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:60",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589271456,
      "name": "native_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
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
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579086745,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:60",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579242852,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:60",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589514304,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:60",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589514304,
      "name": "native_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
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
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579096491,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256852,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589973408,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589973408,
      "name": "native_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579098471,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258516,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590200816,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590200816,
      "name": "native_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579110949,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284932,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591216752,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591216752,
      "name": "native_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579110789,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292260,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591711264,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591711264,
      "name": "native_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579117445,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:54",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294932,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:54",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591658656,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:54",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591658656,
      "name": "native_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579142869,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:54",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342052,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:54",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592832336,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:54",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592832336,
      "name": "native_halt",
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
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579180451,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:54",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403124,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:54",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594741776,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:54",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594741776,
      "name": "native_halt",
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
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579235442,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:54",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579483684,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:54",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596494080,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:54",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596494080,
      "name": "native_halt",
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
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579241287,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:51",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579496090,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:51",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead",
        "arch/x86/kernel/smpboot.c:mwait_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579611232,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:51",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611232,
      "name": "native_halt",
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
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579270135,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:51",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579525834,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:51",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead",
        "arch/x86/kernel/smpboot.c:mwait_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579641008,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:51",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641008,
      "name": "native_halt",
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579098855,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257220,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589803104,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589803104,
      "name": "native_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579031297,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055176,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579183852,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:crash_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192438,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264055,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604691567,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/mm/extable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/extable.c:early_fixup_exception"
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
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579098407,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258420,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590246512,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590246512,
      "name": "native_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
void native_halt()
```

```json
{
  "name": "native_halt",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579102855,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264020,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590297664,
      "name": "native_halt",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:63",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590297664,
      "name": "native_halt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
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
void native_halt()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void native_halt()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void native_halt()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void native_halt()
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
void native_halt()
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
