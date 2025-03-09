# Function: <code>send_sig_mceerr</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579497520,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1546",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497520,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530992,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1632",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530992,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1720",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570095,
      "name": "send_sig_mceerr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579557504,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579583648,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1725",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579583648,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579617760,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1721",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617760,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579598064,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1722",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598064,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579603536,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1724",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579603536,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579678688,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1761",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:kill_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579678688,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579772832,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1762",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:kill_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579772832,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579904960,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1763",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:kill_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904960,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579954688,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1769",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:kill_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579954688,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993984,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1760",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:kill_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993984,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490747176,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1725",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/mmu.c:user_mem_abort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490747176,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224796884,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1725",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224796884,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283571856,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1725",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283571856,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271451142,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1725",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271451142,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579559952,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1725",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559952,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579488608,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1725",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488608,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579557232,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1725",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579557232,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "send_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579590608,
      "name": "send_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1725",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590608,
      "name": "send_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int send_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
