# Function: <code>s_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579135392,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce-severity.c:302",
      "file": "arch/x86/kernel/cpu/mcheck/mce-severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579938400,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:528",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580228560,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:2969",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580734928,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:2616",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579135392,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579938400,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071580228560,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
    },
    {
      "addr": 18446744071580734928,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
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
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579135088,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce-severity.c:350",
      "file": "arch/x86/kernel/cpu/mcheck/mce-severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579969056,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:552",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580265552,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:3306",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580853888,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:2637",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579135088,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579969056,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071580265552,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
    },
    {
      "addr": 18446744071580853888,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
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
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579142160,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce-severity.c:350",
      "file": "arch/x86/kernel/cpu/mcheck/mce-severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579999552,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:552",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580308576,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:3530",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580922096,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:2631",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142160,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579999552,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071580308576,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
    },
    {
      "addr": 18446744071580922096,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
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
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579140528,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce-severity.c:350",
      "file": "arch/x86/kernel/cpu/mcheck/mce-severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580006384,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:583",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580322208,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:3760",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580966416,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:2701",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140528,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580006384,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071580322208,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
    },
    {
      "addr": 18446744071580966416,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579155472,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce-severity.c:349",
      "file": "arch/x86/kernel/cpu/mcheck/mce-severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580052848,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:615",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580375344,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:3769",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581068080,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:2693",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579155472,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580052848,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071580375344,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    },
    {
      "addr": 18446744071581068080,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579166976,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce-severity.c:362",
      "file": "arch/x86/kernel/cpu/mcheck/mce-severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580109904,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:569",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580436704,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:3775",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581206528,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:2680",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579166976,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580109904,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071580436704,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071581206528,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
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
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579156432,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:363",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580156912,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:592",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580492304,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:3779",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581290736,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:2682",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156432,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580156912,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071580492304,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071581290736,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
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
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579168464,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:364",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580202976,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:595",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580547952,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:3982",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581364640,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:3455",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579168464,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580202976,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071580547952,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071581364640,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
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
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579170896,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:364",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580251312,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:595",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580595552,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4008",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581424176,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:3482",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579170896,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580251312,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071580595552,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071581424176,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579188560,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:368",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580319808,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:594",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580694496,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4178",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581625728,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:3531",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188560,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580319808,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071580694496,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071581625728,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 738
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
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579184096,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:444",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580304944,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:628",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580685296,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4246",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581681104,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:3516",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579184096,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580304944,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071580685296,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071581681104,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
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
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579190480,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:440",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580308496,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:679",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580689440,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4573",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581706096,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:3783",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579190480,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580308496,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071580689440,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071581706096,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579225632,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:440",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580461872,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:743",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580864702,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4647",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581977968,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:3894",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579225632,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580461872,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071580864624,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    },
    {
      "addr": 18446744071592170630,
      "name": "s_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071581977968,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579276832,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:429",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580654656,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:767",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581094424,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4642",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582386400,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:4063",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276832,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071580654656,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071581094336,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    },
    {
      "addr": 18446744071593944326,
      "name": "s_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582386400,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579341504,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:431",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580922720,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:840",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581402104,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4666",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582891520,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:4122",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579341504,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071580922720,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071581402016,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    },
    {
      "addr": 18446744071596005257,
      "name": "s_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582891520,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579350384,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:431",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581010112,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:781",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581496917,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4770",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583106720,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:4373",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350384,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071581010112,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071581496832,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    },
    {
      "addr": 18446744071596523669,
      "name": "s_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071583106720,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 622
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579380272,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:431",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581105984,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:779",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4732",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583289344,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:4373",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579380272,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071581105984,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071581607616,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
    },
    {
      "addr": 18446744071597424421,
      "name": "s_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071583289344,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 622
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
int s_show(struct seq_file * m, void * p)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491493376,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:595",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491893456,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4008",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492826216,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:3482",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491493376,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446603336491893456,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    },
    {
      "addr": 18446603336492826216,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 804
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
int s_show(struct seq_file * m, void * p)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225474896,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:595",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225835836,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4008",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226632032,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:3482",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225474896,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 3225835836,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 3226632032,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
int s_show(struct seq_file * m, void * p)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284450736,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:595",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284976576,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4008",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286210048,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:3482",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284450736,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 13835058055284976576,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
    },
    {
      "addr": 13835058055286210048,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1024
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
int s_show(struct seq_file * m, void * p)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271936798,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:595",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272182422,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4008",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272782078,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:3482",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271936798,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446743936272182422,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446743936272782078,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579171152,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:364",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580220112,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:595",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580564352,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4008",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581393024,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:3482",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579171152,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580220112,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071580564352,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071581393024,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579102928,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:364",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580167552,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:595",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580511056,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4008",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581335600,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:3482",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579102928,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580167552,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071580511056,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071581335600,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579170816,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:364",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580211584,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:595",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580555600,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4008",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581384224,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:3482",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579170816,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580211584,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071580555600,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071581384224,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
int s_show(struct seq_file * f, void * data)
```

```json
{
  "name": "s_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579176000,
      "name": "s_show",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/severity.c:364",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580264288,
      "name": "s_show",
      "external": false,
      "loc": "kernel/kallsyms.c:595",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580612320,
      "name": "s_show",
      "external": false,
      "loc": "kernel/trace/trace.c:4008",
      "file": "kernel/trace/trace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581448544,
      "name": "s_show",
      "external": false,
      "loc": "mm/vmalloc.c:3482",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579176000,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071580264288,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071580612320,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071581448544,
      "name": "s_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
