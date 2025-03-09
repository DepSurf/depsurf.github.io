# Function: <code>s_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579135248,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce-severity.c:291",
      "file": "arch/x86/kernel/cpu/mcheck/mce-severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579939264,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:508",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580221296,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:2390",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071580276432,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:900",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580731408,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:2574",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579135248,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071579939264,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580221296,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071580276432,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071580731408,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579134944,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce-severity.c:339",
      "file": "arch/x86/kernel/cpu/mcheck/mce-severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579970064,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:532",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580258128,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:2727",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071580321317,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:935",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580850304,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:2595",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579134944,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579970064,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580258128,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071580319776,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580850304,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579142016,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce-severity.c:339",
      "file": "arch/x86/kernel/cpu/mcheck/mce-severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580000560,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:532",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580301184,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:2951",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071580367314,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:904",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580921808,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:2596",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142016,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071580000560,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580301184,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071580365936,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071580921808,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579140384,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce-severity.c:339",
      "file": "arch/x86/kernel/cpu/mcheck/mce-severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580007488,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:563",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580314512,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3163",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071580378721,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:944",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580966128,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:2666",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140384,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071580007488,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580314512,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071580377616,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580966128,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579155328,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce-severity.c:338",
      "file": "arch/x86/kernel/cpu/mcheck/mce-severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580054112,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:595",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580367648,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3172",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071580433953,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:944",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581067792,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:2658",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579155328,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071580054112,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580367648,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071580432800,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071581067792,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579166832,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce-severity.c:351",
      "file": "arch/x86/kernel/cpu/mcheck/mce-severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580111152,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:549",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580429072,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3178",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071580495713,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:942",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581206240,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:2645",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579166832,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071580111152,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580429072,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071580494608,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071581206240,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579156288,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:352",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580159344,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:572",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580484720,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3180",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071580553425,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:943",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581290448,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:2647",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156288,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071580159344,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580484720,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071580552320,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071581290448,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579168320,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:353",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580205424,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:575",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580540272,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3355",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071580610641,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:936",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581364528,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:3420",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579168320,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071580205424,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071580540272,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071580609296,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071581364528,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579170752,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:353",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580253760,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:575",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580587840,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3381",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071580658353,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:937",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581424928,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:3431",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579170752,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071580253760,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071580587840,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071580656192,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071581424928,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579188400,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:357",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580322400,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:574",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580687472,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3546",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071580758993,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1011",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626480,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:3478",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188400,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580322400,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071580687472,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071580758224,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071581626480,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579183648,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:433",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580307680,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:608",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580678272,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3614",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071580747041,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1012",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672160,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:3466",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183648,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580307680,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071580678272,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071580746272,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071581672160,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579190080,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:429",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580311216,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:659",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580681568,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3947",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071580751569,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1219",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581694416,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:3733",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579190080,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580311216,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071580681568,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071580751056,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071581694416,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579225152,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:429",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580464752,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:723",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580856176,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4019",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071580935217,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1220",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581966592,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:3844",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579225152,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071580464752,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071580856176,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071580934560,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071581966592,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579276288,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:418",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580658112,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:747",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581085632,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4022",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071581175297,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1240",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582385280,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:4013",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276288,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071580658112,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071581085632,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071581174672,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071582385280,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579340880,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:420",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580927584,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:820",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581392992,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4046",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071581490529,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1255",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582892080,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:4072",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579340880,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071580927584,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071581392992,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071581489824,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071582892080,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579349760,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:420",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581011056,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:761",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581487744,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4140",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071581608481,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1251",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583107360,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:4323",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579349760,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071581011056,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071581487744,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071581607776,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071583107360,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579379648,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:420",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581106928,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:759",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581598592,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:4108",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071581721585,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:1260",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583289984,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:4323",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379648,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071581106928,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071581598592,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071581720416,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071583289984,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491496312,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:575",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491885496,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3381",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446603336491962624,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:937",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492827024,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:3431",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491496312,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446603336491885496,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446603336491961096,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446603336492827024,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225477828,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:575",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225827940,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3381",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 3225898248,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:937",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3226632612,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:3431",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225477828,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 3225827940,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 3225896628,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 3226632612,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284454912,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:575",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284965664,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3381",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 13835058055285073176,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:937",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286211072,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:3431",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284454912,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 13835058055284965664,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 13835058055285067888,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 13835058055286211072,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271939146,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:575",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272175512,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3381",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446743936272236754,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:937",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272782562,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:3431",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271939146,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446743936272175512,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446743936272234684,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446743936272782562,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579171008,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:353",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580222560,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:575",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580556640,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3381",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071580627153,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:937",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393776,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:3431",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579171008,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071580222560,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071580556640,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071580624992,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071581393776,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579102784,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:353",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580170000,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:575",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580503344,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3381",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071580573393,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:937",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581336352,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:3431",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579102784,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071580170000,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071580503344,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071580571248,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071581336352,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579170672,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:353",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580214032,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:575",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580547888,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3381",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071580618401,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:937",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384976,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:3431",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579170672,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071580214032,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071580547888,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071580616240,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071581384976,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void * s_next(struct seq_file * f, void * data, loff_t * pos)
```

```json
{
  "name": "s_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579175856,
      "name": "s_next",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:353",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580266736,
      "name": "s_next",
      "external": false,
      "loc": "kernel/kallsyms.c:575",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580604608,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace.c:3381",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:s_start"
      ]
    },
    {
      "addr": 18446744071580675889,
      "name": "s_next",
      "external": false,
      "loc": "kernel/trace/trace_events.c:937",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:s_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581449296,
      "name": "s_next",
      "external": false,
      "loc": "mm/vmalloc.c:3431",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579175856,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071580266736,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071580604608,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071580673728,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071581449296,
      "name": "s_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct seq_file * m</code>
</li>
<li>
<b>Param added. </b>
<code>void * p</code>
</li>
<li>
<b>Param removed. </b>
<code>struct seq_file * f</code>
</li>
<li>
<b>Param removed. </b>
<code>void * data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct seq_file * m</code>
</li>
<li>
<b>Param added. </b>
<code>void * p</code>
</li>
<li>
<b>Param removed. </b>
<code>struct seq_file * f</code>
</li>
<li>
<b>Param removed. </b>
<code>void * data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct seq_file * m</code>
</li>
<li>
<b>Param added. </b>
<code>void * p</code>
</li>
<li>
<b>Param removed. </b>
<code>struct seq_file * f</code>
</li>
<li>
<b>Param removed. </b>
<code>void * data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct seq_file * m</code>
</li>
<li>
<b>Param added. </b>
<code>void * p</code>
</li>
<li>
<b>Param removed. </b>
<code>struct seq_file * f</code>
</li>
<li>
<b>Param removed. </b>
<code>void * data</code>
</li>
</ul>
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
