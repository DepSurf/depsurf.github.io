# Function: <code>process_fetch_insn</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
int process_fetch_insn(struct fetch_insn * code, struct pt_regs * regs, void * dest, void * base)
```

```json
{
  "name": "process_fetch_insn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580637856,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:907",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    },
    {
      "addr": 18446744071580663680,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:201",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580637856,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1112
    },
    {
      "addr": 18446744071580663680,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1079
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
int process_fetch_insn(struct fetch_insn * code, struct pt_regs * regs, void * dest, void * base)
```

```json
{
  "name": "process_fetch_insn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580699104,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:942",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    },
    {
      "addr": 18446744071580734480,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:226",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580699104,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1377
    },
    {
      "addr": 18446744071580734480,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1493
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
int process_fetch_insn(struct fetch_insn * code, struct pt_regs * regs, void * dest, void * base)
```

```json
{
  "name": "process_fetch_insn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580747392,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:1126",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    },
    {
      "addr": 18446744071580785216,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:220",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580747392,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1388
    },
    {
      "addr": 18446744071580785216,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1542
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int process_fetch_insn(struct fetch_insn * code, struct pt_regs * regs, void * dest, void * base)
```

```json
{
  "name": "process_fetch_insn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580860688,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:1308",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    },
    {
      "addr": 18446744071580902640,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:220",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860688,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1842
    },
    {
      "addr": 18446744071580902640,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1537
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int process_fetch_insn(struct fetch_insn * code, struct pt_regs * regs, void * dest, void * base)
```

```json
{
  "name": "process_fetch_insn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580852832,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:1328",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    },
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:220",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852832,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1842
    },
    {
      "addr": 18446744071580896976,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1993
    },
    {
      "addr": 18446744071591322883,
      "name": "process_fetch_insn.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int process_fetch_insn(struct fetch_insn * code, struct pt_regs * regs, void * dest, void * base)
```

```json
{
  "name": "process_fetch_insn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580858064,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:1333",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    },
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:220",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580858064,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1705
    },
    {
      "addr": 18446744071580900800,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1987
    },
    {
      "addr": 18446744071591264747,
      "name": "process_fetch_insn.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int process_fetch_insn(struct fetch_insn * code, void * rec, void * dest, void * base)
```

```json
{
  "name": "process_fetch_insn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_eprobe.c:364",
      "file": "kernel/trace/trace_eprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__eprobe_trace_func"
      ]
    },
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:1327",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    },
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:216",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580981520,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1502
    },
    {
      "addr": 18446744071592175900,
      "name": "process_fetch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    },
    {
      "addr": 18446744071581058512,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1858
    },
    {
      "addr": 18446744071592178436,
      "name": "process_fetch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    },
    {
      "addr": 18446744071581097872,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2121
    },
    {
      "addr": 18446744071592179323,
      "name": "process_fetch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int process_fetch_insn(struct fetch_insn * code, void * rec, void * dest, void * base)
```

```json
{
  "name": "process_fetch_insn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_eprobe.c:421",
      "file": "kernel/trace/trace_eprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__eprobe_trace_func"
      ]
    },
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:1323",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    },
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:217",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581226880,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1606
    },
    {
      "addr": 18446744071593949552,
      "name": "process_fetch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
    },
    {
      "addr": 18446744071581316016,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1871
    },
    {
      "addr": 18446744071593952175,
      "name": "process_fetch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
    },
    {
      "addr": 18446744071581359152,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2016
    },
    {
      "addr": 18446744071593953121,
      "name": "process_fetch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int process_fetch_insn(struct fetch_insn * code, void * rec, void * dest, void * base)
```

```json
{
  "name": "process_fetch_insn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_eprobe.c:427",
      "file": "kernel/trace/trace_eprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__eprobe_trace_func"
      ]
    },
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:1277",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    },
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:218",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581551504,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2242
    },
    {
      "addr": 18446744071596008314,
      "name": "process_fetch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071581650000,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2525
    },
    {
      "addr": 18446744071596010693,
      "name": "process_fetch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071581693312,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2363
    },
    {
      "addr": 18446744071596011727,
      "name": "process_fetch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int process_fetch_insn(struct fetch_insn * code, void * rec, void * dest, void * base)
```

```json
{
  "name": "process_fetch_insn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_eprobe.c:389",
      "file": "kernel/trace/trace_eprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__eprobe_trace_func"
      ]
    },
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:1240",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    },
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:219",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher"
      ]
    },
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_fprobe.c:132",
      "file": "kernel/trace/trace_fprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_fprobe.c:fexit_perf_func",
        "kernel/trace/trace_fprobe.c:fexit_perf_func",
        "kernel/trace/trace_fprobe.c:fentry_perf_func",
        "kernel/trace/trace_fprobe.c:fentry_perf_func",
        "kernel/trace/trace_fprobe.c:fexit_trace_func",
        "kernel/trace/trace_fprobe.c:fexit_trace_func",
        "kernel/trace/trace_fprobe.c:fentry_trace_func",
        "kernel/trace/trace_fprobe.c:fentry_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668032,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2040
    },
    {
      "addr": 18446744071596526693,
      "name": "process_fetch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071581788896,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2123
    },
    {
      "addr": 18446744071596529751,
      "name": "process_fetch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071581838304,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2317
    },
    {
      "addr": 18446744071596530821,
      "name": "process_fetch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    },
    {
      "addr": 18446744071581863536,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2081
    },
    {
      "addr": 18446744071596531591,
      "name": "process_fetch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int process_fetch_insn(struct fetch_insn * code, void * rec, void * dest, void * base)
```

```json
{
  "name": "process_fetch_insn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_eprobe.c:393",
      "file": "kernel/trace/trace_eprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__eprobe_trace_func"
      ]
    },
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:1306",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    },
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:214",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher"
      ]
    },
    {
      "addr": 0,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_fprobe.c:132",
      "file": "kernel/trace/trace_fprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_fprobe.c:fexit_perf_func",
        "kernel/trace/trace_fprobe.c:fexit_perf_func",
        "kernel/trace/trace_fprobe.c:fentry_perf_func",
        "kernel/trace/trace_fprobe.c:fentry_perf_func",
        "kernel/trace/trace_fprobe.c:fexit_trace_func",
        "kernel/trace/trace_fprobe.c:fexit_trace_func",
        "kernel/trace/trace_fprobe.c:fentry_trace_func",
        "kernel/trace/trace_fprobe.c:fentry_trace_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784176,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2040
    },
    {
      "addr": 18446744071597427305,
      "name": "process_fetch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071581910240,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2123
    },
    {
      "addr": 18446744071597430403,
      "name": "process_fetch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    },
    {
      "addr": 18446744071581961776,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1925
    },
    {
      "addr": 18446744071597431459,
      "name": "process_fetch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    },
    {
      "addr": 18446744071581986496,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2081
    },
    {
      "addr": 18446744071597432325,
      "name": "process_fetch_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
int process_fetch_insn(struct fetch_insn * code, struct pt_regs * regs, void * dest, void * base)
```

```json
{
  "name": "process_fetch_insn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492052216,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:1126",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    },
    {
      "addr": 18446603336492097376,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:220",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492052216,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1408
    },
    {
      "addr": 18446603336492097376,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1516
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
int process_fetch_insn(struct fetch_insn * code, struct pt_regs * regs, void * dest, void * base)
```

```json
{
  "name": "process_fetch_insn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225951812,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:1126",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    },
    {
      "addr": 3225997556,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:220",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225951812,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1352
    },
    {
      "addr": 3225997556,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1760
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
int process_fetch_insn(struct fetch_insn * code, struct pt_regs * regs, void * dest, void * base)
```

```json
{
  "name": "process_fetch_insn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285224928,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:1126",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    },
    {
      "addr": 13835058055285299344,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:220",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285224928,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1696
    },
    {
      "addr": 13835058055285299344,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2164
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
int process_fetch_insn(struct fetch_insn * code, struct pt_regs * regs, void * dest, void * base)
```

```json
{
  "name": "process_fetch_insn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580716192,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:1126",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    },
    {
      "addr": 18446744071580754016,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:220",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580716192,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1388
    },
    {
      "addr": 18446744071580754016,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1542
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
int process_fetch_insn(struct fetch_insn * code, struct pt_regs * regs, void * dest, void * base)
```

```json
{
  "name": "process_fetch_insn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580662400,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:1126",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    },
    {
      "addr": 18446744071580700208,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:220",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580662400,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1388
    },
    {
      "addr": 18446744071580700208,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1542
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
int process_fetch_insn(struct fetch_insn * code, struct pt_regs * regs, void * dest, void * base)
```

```json
{
  "name": "process_fetch_insn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580707440,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:1126",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    },
    {
      "addr": 18446744071580745264,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:220",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580707440,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1388
    },
    {
      "addr": 18446744071580745264,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1542
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
int process_fetch_insn(struct fetch_insn * code, struct pt_regs * regs, void * dest, void * base)
```

```json
{
  "name": "process_fetch_insn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580765392,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:1126",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kprobe_perf_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kretprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func",
        "kernel/trace/trace_kprobe.c:kprobe_trace_func"
      ]
    },
    {
      "addr": 18446744071580803280,
      "name": "process_fetch_insn",
      "external": false,
      "loc": "kernel/trace/trace_uprobe.c:220",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uretprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher",
        "kernel/trace/trace_uprobe.c:uprobe_dispatcher"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580765392,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1388
    },
    {
      "addr": 18446744071580803280,
      "name": "process_fetch_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1542
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int process_fetch_insn(struct fetch_insn * code, struct pt_regs * regs, void * dest, void * base)
```
</details>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * rec</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pt_regs * regs</code>
</li>
</ul>
</details>
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
int process_fetch_insn(struct fetch_insn * code, struct pt_regs * regs, void * dest, void * base)
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
