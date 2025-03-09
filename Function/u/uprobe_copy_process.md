# Function: <code>uprobe_copy_process</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580453056,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1477",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580453056,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580528528,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1483",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580528528,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580592544,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1484",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580592544,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580622560,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1490",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580622560,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580703472,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1490",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703472,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1490",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580839237,
      "name": "uprobe_copy_process.cold.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580835856,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1760",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907906,
      "name": "uprobe_copy_process.cold.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580904288,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1748",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581005740,
      "name": "uprobe_copy_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581002016,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1800",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581060591,
      "name": "uprobe_copy_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581056864,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1799",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581241716,
      "name": "uprobe_copy_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581238992,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1799",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591323823,
      "name": "uprobe_copy_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581281760,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1797",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591265712,
      "name": "uprobe_copy_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581298688,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1798",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592188631,
      "name": "uprobe_copy_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581543824,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1793",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593963729,
      "name": "uprobe_copy_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581894624,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582328000,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1797",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582328000,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 621
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
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582529232,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1794",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582529232,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 621
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
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582698192,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1794",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582698192,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 711
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
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492415160,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1800",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492415160,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226298820,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1800",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226298820,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285681824,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1800",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285681824,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_copy_process",
      "external": false,
      "loc": "include/linux/uprobes.h:197",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1800",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029439,
      "name": "uprobe_copy_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581025712,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1800",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580975519,
      "name": "uprobe_copy_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071580971808,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1800",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581020639,
      "name": "uprobe_copy_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581016912,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
```

```json
{
  "name": "uprobe_copy_process",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uprobe_copy_process",
      "external": true,
      "loc": "kernel/events/uprobes.c:1800",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581081981,
      "name": "uprobe_copy_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581078224,
      "name": "uprobe_copy_process",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
void uprobe_copy_process(struct task_struct * t, long unsigned int flags)
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
