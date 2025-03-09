# Function: <code>ptrace_regset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ptrace_regset(struct task_struct * task, int req, unsigned int type, struct iovec * kiov)
```

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414672,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:825",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414672,
      "name": "ptrace_regset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int ptrace_regset(struct task_struct * task, int req, unsigned int type, struct iovec * kiov)
```

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426944,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:830",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426944,
      "name": "ptrace_regset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int ptrace_regset(struct task_struct * task, int req, unsigned int type, struct iovec * kiov)
```

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579446352,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:840",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579446352,
      "name": "ptrace_regset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int ptrace_regset(struct task_struct * task, int req, unsigned int type, struct iovec * kiov)
```

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579434336,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:855",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579434336,
      "name": "ptrace_regset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
int ptrace_regset(struct task_struct * task, int req, unsigned int type, struct iovec * kiov)
```

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579462704,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:853",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462704,
      "name": "ptrace_regset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579475504,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:853",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579475504,
      "name": "ptrace_regset.isra.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579509568,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:853",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509568,
      "name": "ptrace_regset.isra.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579529184,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:874",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529184,
      "name": "ptrace_regset.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579555328,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:879",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555328,
      "name": "ptrace_regset.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
int ptrace_regset(struct task_struct * task, int req, unsigned int type, struct iovec * kiov)
```

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579586240,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:879",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579586240,
      "name": "ptrace_regset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
int ptrace_regset(struct task_struct * task, int req, unsigned int type, struct iovec * kiov)
```

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579566240,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:873",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566240,
      "name": "ptrace_regset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
int ptrace_regset(struct task_struct * task, int req, unsigned int type, struct iovec * kiov)
```

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571760,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:908",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571760,
      "name": "ptrace_regset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int ptrace_regset(struct task_struct * task, int req, unsigned int type, struct iovec * kiov)
```

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579645008,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:908",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645008,
      "name": "ptrace_regset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int ptrace_regset(struct task_struct * task, int req, unsigned int type, struct iovec * kiov)
```

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579741024,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:907",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741024,
      "name": "ptrace_regset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
int ptrace_regset(struct task_struct * task, int req, unsigned int type, struct iovec * kiov)
```

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872384,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:907",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872384,
      "name": "ptrace_regset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
int ptrace_regset(struct task_struct * task, int req, unsigned int type, struct iovec * kiov)
```

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579922480,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:908",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579922480,
      "name": "ptrace_regset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int ptrace_regset(struct task_struct * task, int req, unsigned int type, struct iovec * kiov)
```

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579961728,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:891",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579961728,
      "name": "ptrace_regset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490708616,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:879",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490708616,
      "name": "ptrace_regset.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224776132,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:879",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_request"
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
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283533152,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:879",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283533152,
      "name": "ptrace_regset.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271436574,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:879",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_request"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579531632,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:879",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579531632,
      "name": "ptrace_regset.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579460432,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:879",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460432,
      "name": "ptrace_regset.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579528912,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:879",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528912,
      "name": "ptrace_regset.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_regset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579562400,
      "name": "ptrace_regset",
      "external": false,
      "loc": "kernel/ptrace.c:879",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562400,
      "name": "ptrace_regset.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int ptrace_regset(struct task_struct * task, int req, unsigned int type, struct iovec * kiov)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ptrace_regset(struct task_struct * task, int req, unsigned int type, struct iovec * kiov)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
