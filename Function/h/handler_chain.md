# Function: <code>handler_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580454725,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:1742",
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
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580530216,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:1753",
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
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580594204,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:1755",
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
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580624281,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:1761",
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
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580705199,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:1761",
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
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580837463,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:1761",
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
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580905910,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:2031",
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
void handler_chain(struct uprobe * uprobe, struct pt_regs * regs)
```

```json
{
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:2019",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:handle_swbp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581002624,
      "name": "handler_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 903
    },
    {
      "addr": 18446744071581005774,
      "name": "handler_chain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581057833,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:2071",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void handler_chain(struct uprobe * uprobe, struct pt_regs * regs)
```

```json
{
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581240368,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:2073",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:handle_swbp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581240368,
      "name": "handler_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
void handler_chain(struct uprobe * uprobe, struct pt_regs * regs)
```

```json
{
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581283136,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:2073",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:handle_swbp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581283136,
      "name": "handler_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
void handler_chain(struct uprobe * uprobe, struct pt_regs * regs)
```

```json
{
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581300016,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:2071",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:handle_swbp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581300016,
      "name": "handler_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
void handler_chain(struct uprobe * uprobe, struct pt_regs * regs)
```

```json
{
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581545152,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:2072",
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
      "addr": 18446744071581545152,
      "name": "handler_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
void handler_chain(struct uprobe * uprobe, struct pt_regs * regs)
```

```json
{
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581896096,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:2067",
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
      "addr": 18446744071581896096,
      "name": "handler_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582330132,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:2072",
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
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582531363,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:2068",
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
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582700371,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:2068",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void handler_chain(struct uprobe * uprobe, struct pt_regs * regs)
```

```json
{
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492415920,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:2071",
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
      "addr": 18446603336492415920,
      "name": "handler_chain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 932
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226299776,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:2071",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285683172,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:2071",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581026681,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:2071",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580972777,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:2071",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581017881,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:2071",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handler_chain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581079193,
      "name": "handler_chain",
      "external": false,
      "loc": "kernel/events/uprobes.c:2071",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void handler_chain(struct uprobe * uprobe, struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
void handler_chain(struct uprobe * uprobe, struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void handler_chain(struct uprobe * uprobe, struct pt_regs * regs)
```
</details>
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
void handler_chain(struct uprobe * uprobe, struct pt_regs * regs)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void handler_chain(struct uprobe * uprobe, struct pt_regs * regs)
```
</details>
</li>
</ul>
