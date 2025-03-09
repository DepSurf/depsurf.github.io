# Function: <code>handle_swbp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580454053,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:1857",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580529525,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:1868",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580593513,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:1870",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580623312,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:1876",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580704224,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:1876",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580836706,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:1876",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580905138,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:2146",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void handle_swbp(struct pt_regs * regs)
```

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:2134",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003536,
      "name": "handle_swbp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1383
    },
    {
      "addr": 18446744071581005848,
      "name": "handle_swbp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void handle_swbp(struct pt_regs * regs)
```

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:2186",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581057472,
      "name": "handle_swbp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2416
    },
    {
      "addr": 18446744071581060625,
      "name": "handle_swbp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void handle_swbp(struct pt_regs * regs)
```

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581240640,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:2188",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581240640,
      "name": "handle_swbp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
void handle_swbp(struct pt_regs * regs)
```

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581283408,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:2188",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581283408,
      "name": "handle_swbp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
void handle_swbp(struct pt_regs * regs)
```

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:2186",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581300544,
      "name": "handle_swbp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
    },
    {
      "addr": 18446744071591265794,
      "name": "handle_swbp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581545908,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:2187",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581896839,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:2182",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582329935,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:2187",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
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
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582531167,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:2183",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
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
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582700207,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:2183",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492417152,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:2186",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void handle_swbp(struct pt_regs * regs)
```

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226299492,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:2186",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226299492,
      "name": "handle_swbp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2376
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
void handle_swbp(struct pt_regs * regs)
```

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285682736,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:2186",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285682736,
      "name": "handle_swbp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3028
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void handle_swbp(struct pt_regs * regs)
```

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:2186",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581026320,
      "name": "handle_swbp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2416
    },
    {
      "addr": 18446744071581029473,
      "name": "handle_swbp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void handle_swbp(struct pt_regs * regs)
```

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:2186",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580972416,
      "name": "handle_swbp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2416
    },
    {
      "addr": 18446744071580975553,
      "name": "handle_swbp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void handle_swbp(struct pt_regs * regs)
```

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:2186",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581017520,
      "name": "handle_swbp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2416
    },
    {
      "addr": 18446744071581020673,
      "name": "handle_swbp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void handle_swbp(struct pt_regs * regs)
```

```json
{
  "name": "handle_swbp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handle_swbp",
      "external": false,
      "loc": "kernel/events/uprobes.c:2186",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078832,
      "name": "handle_swbp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2399
    },
    {
      "addr": 18446744071581082015,
      "name": "handle_swbp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void handle_swbp(struct pt_regs * regs)
```
</details>
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
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void handle_swbp(struct pt_regs * regs)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void handle_swbp(struct pt_regs * regs)
```
</details>
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
void handle_swbp(struct pt_regs * regs)
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
