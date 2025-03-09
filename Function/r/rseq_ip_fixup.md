# Function: <code>rseq_ip_fixup</code>

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
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580852963,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:221",
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
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580921427,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:221",
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
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581017424,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:221",
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
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581072688,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:221",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int rseq_ip_fixup(struct pt_regs * regs)
```

```json
{
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581253920,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:221",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581253920,
      "name": "rseq_ip_fixup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
int rseq_ip_fixup(struct pt_regs * regs)
```

```json
{
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581296032,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:221",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296032,
      "name": "rseq_ip_fixup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
int rseq_ip_fixup(struct pt_regs * regs)
```

```json
{
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581313616,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:237",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581313616,
      "name": "rseq_ip_fixup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
int rseq_ip_fixup(struct pt_regs * regs)
```

```json
{
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581558848,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:237",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558848,
      "name": "rseq_ip_fixup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
int rseq_ip_fixup(struct pt_regs * regs)
```

```json
{
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581911152,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:237",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911152,
      "name": "rseq_ip_fixup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
int rseq_ip_fixup(struct pt_regs * regs)
```

```json
{
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582346160,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:245",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582346160,
      "name": "rseq_ip_fixup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
int rseq_ip_fixup(struct pt_regs * regs)
```

```json
{
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582549632,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:274",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582549632,
      "name": "rseq_ip_fixup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
int rseq_ip_fixup(struct pt_regs * regs)
```

```json
{
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582720224,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:274",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582720224,
      "name": "rseq_ip_fixup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492435292,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:221",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int rseq_ip_fixup(struct pt_regs * regs)
```

```json
{
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226309904,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:221",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226309904,
      "name": "rseq_ip_fixup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285704676,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:221",
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
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581041536,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:221",
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
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580988816,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:221",
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
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581032736,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:221",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int rseq_ip_fixup(struct pt_regs * regs)
```

```json
{
  "name": "rseq_ip_fixup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rseq_ip_fixup",
      "external": false,
      "loc": "kernel/rseq.c:221",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093264,
      "name": "rseq_ip_fixup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1021
    },
    {
      "addr": 18446744071581095321,
      "name": "rseq_ip_fixup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int rseq_ip_fixup(struct pt_regs * regs)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int rseq_ip_fixup(struct pt_regs * regs)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➕</summary>

```c
int rseq_ip_fixup(struct pt_regs * regs)
```
</details>
</li>
</ul>
