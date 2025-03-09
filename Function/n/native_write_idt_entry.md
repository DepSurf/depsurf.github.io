# Function: <code>native_write_idt_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578960804,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:119",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_write_idt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256544,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:119",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256544,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578957380,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:119",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_write_idt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255600,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:119",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255600,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578959460,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:119",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_write_idt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269120,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:119",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269120,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:152",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579266448,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:152",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266448,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:141",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579283136,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:141",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579283136,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:141",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579294592,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:141",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294592,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:141",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579319248,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:141",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579319248,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:141",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579334320,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:141",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334320,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:141",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579338528,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:141",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338528,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:136",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579368368,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:136",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579368368,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:136",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:136",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579367376,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:136",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367376,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:136",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:136",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579372064,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:136",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579372064,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:137",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:137",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579433328,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:137",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433328,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578847987,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:137",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579044585,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:137",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593847106,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:137",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593847106,
      "name": "native_write_idt_entry.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071579502592,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578848067,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:137",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579071408,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:137",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry"
      ]
    },
    {
      "addr": 18446744071579600192,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:137",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579071408,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071579600192,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579071232,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:137",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry"
      ]
    },
    {
      "addr": 18446744071579148208,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:137",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579612608,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:137",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148208,
      "name": "native_write_idt_entry.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579071232,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071579612608,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579096464,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:137",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_idt_entry"
      ]
    },
    {
      "addr": 18446744071579177488,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:137",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579642320,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:137",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579177488,
      "name": "native_write_idt_entry.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579096464,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071579642320,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:141",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579334432,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:141",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334432,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
  "name": "native_write_idt_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578985510,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:141",
      "file": "arch/x86/kernel/idt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/idt.c:idt_setup_from_table"
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
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:141",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579334352,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:141",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334352,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```

```json
{
  "name": "native_write_idt_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:141",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579342704,
      "name": "native_write_idt_entry",
      "external": false,
      "loc": "arch/x86/include/asm/desc.h:141",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579342704,
      "name": "native_write_idt_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
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
void native_write_idt_entry(gate_desc * idt, int entry, const gate_desc * gate)
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
