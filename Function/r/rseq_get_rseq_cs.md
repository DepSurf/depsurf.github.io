# Function: <code>rseq_get_rseq_cs</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580852975,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:115",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580921439,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:115",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581017424,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:115",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581072688,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:115",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int rseq_get_rseq_cs(struct task_struct * t, struct rseq_cs * rseq_cs)
```

```json
{
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:115",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:rseq_ip_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581253072,
      "name": "rseq_get_rseq_cs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
    },
    {
      "addr": 18446744071581254951,
      "name": "rseq_get_rseq_cs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int rseq_get_rseq_cs(struct task_struct * t, struct rseq_cs * rseq_cs)
```

```json
{
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:115",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:rseq_ip_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295200,
      "name": "rseq_get_rseq_cs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
    },
    {
      "addr": 18446744071591323971,
      "name": "rseq_get_rseq_cs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int rseq_get_rseq_cs(struct task_struct * t, struct rseq_cs * rseq_cs)
```

```json
{
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:122",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:rseq_ip_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581313072,
      "name": "rseq_get_rseq_cs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    },
    {
      "addr": 18446744071591265860,
      "name": "rseq_get_rseq_cs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:122",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:rseq_ip_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558304,
      "name": "rseq_get_rseq_cs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
    },
    {
      "addr": 18446744071592189032,
      "name": "rseq_get_rseq_cs.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:122",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:rseq_ip_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581910512,
      "name": "rseq_get_rseq_cs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
    },
    {
      "addr": 18446744071593964134,
      "name": "rseq_get_rseq_cs.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582345520,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:123",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:rseq_ip_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582345520,
      "name": "rseq_get_rseq_cs.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
int rseq_get_rseq_cs(struct task_struct * t, struct rseq_cs * rseq_cs)
```

```json
{
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582548976,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:152",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:rseq_ip_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582548976,
      "name": "rseq_get_rseq_cs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
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
int rseq_get_rseq_cs(struct task_struct * t, struct rseq_cs * rseq_cs)
```

```json
{
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582719568,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:152",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:rseq_ip_fixup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582719568,
      "name": "rseq_get_rseq_cs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492435320,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:115",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226309972,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:115",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:rseq_ip_fixup"
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
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285704692,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:115",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581041536,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:115",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580988816,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:115",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581032736,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:115",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
  "name": "rseq_get_rseq_cs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581093330,
      "name": "rseq_get_rseq_cs",
      "external": false,
      "loc": "kernel/rseq.c:115",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:rseq_ip_fixup"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int rseq_get_rseq_cs(struct task_struct * t, struct rseq_cs * rseq_cs)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int rseq_get_rseq_cs(struct task_struct * t, struct rseq_cs * rseq_cs)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int rseq_get_rseq_cs(struct task_struct * t, struct rseq_cs * rseq_cs)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
