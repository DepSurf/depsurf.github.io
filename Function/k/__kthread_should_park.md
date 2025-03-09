# Function: <code>__kthread_should_park</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __kthread_should_park(struct task_struct * k)
```

```json
{
  "name": "__kthread_should_park",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579642003,
      "name": "__kthread_should_park",
      "external": true,
      "loc": "kernel/kthread.c:107",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_should_park"
      ],
      "caller_func": [
        "kernel/softirq.c:ksoftirqd_running"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644644,
      "name": "__kthread_should_park.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579641888,
      "name": "__kthread_should_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __kthread_should_park(struct task_struct * k)
```

```json
{
  "name": "__kthread_should_park",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579664031,
      "name": "__kthread_should_park",
      "external": true,
      "loc": "kernel/kthread.c:107",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_should_park"
      ],
      "caller_func": [
        "kernel/softirq.c:ksoftirqd_running"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663968,
      "name": "__kthread_should_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __kthread_should_park(struct task_struct * k)
```

```json
{
  "name": "__kthread_should_park",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579699071,
      "name": "__kthread_should_park",
      "external": true,
      "loc": "kernel/kthread.c:114",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_should_park"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698896,
      "name": "__kthread_should_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __kthread_should_park(struct task_struct * k)
```

```json
{
  "name": "__kthread_should_park",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579677087,
      "name": "__kthread_should_park",
      "external": true,
      "loc": "kernel/kthread.c:115",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_should_park"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676912,
      "name": "__kthread_should_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __kthread_should_park(struct task_struct * k)
```

```json
{
  "name": "__kthread_should_park",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579683599,
      "name": "__kthread_should_park",
      "external": true,
      "loc": "kernel/kthread.c:140",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_should_park"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683424,
      "name": "__kthread_should_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __kthread_should_park(struct task_struct * k)
```

```json
{
  "name": "__kthread_should_park",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579760223,
      "name": "__kthread_should_park",
      "external": true,
      "loc": "kernel/kthread.c:140",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_should_park"
      ],
      "caller_func": [
        "kernel/softirq.c:irq_exit",
        "kernel/softirq.c:irq_exit_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760160,
      "name": "__kthread_should_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __kthread_should_park(struct task_struct * k)
```

```json
{
  "name": "__kthread_should_park",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579866799,
      "name": "__kthread_should_park",
      "external": true,
      "loc": "kernel/kthread.c:161",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_should_park"
      ],
      "caller_func": [
        "kernel/softirq.c:__irq_exit_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866736,
      "name": "__kthread_should_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __kthread_should_park(struct task_struct * k)
```

```json
{
  "name": "__kthread_should_park",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580009263,
      "name": "__kthread_should_park",
      "external": true,
      "loc": "kernel/kthread.c:161",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_should_park"
      ],
      "caller_func": [
        "kernel/softirq.c:__irq_exit_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009184,
      "name": "__kthread_should_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __kthread_should_park(struct task_struct * k)
```

```json
{
  "name": "__kthread_should_park",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580063103,
      "name": "__kthread_should_park",
      "external": true,
      "loc": "kernel/kthread.c:162",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_should_park"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580063024,
      "name": "__kthread_should_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__kthread_should_park",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580105663,
      "name": "__kthread_should_park",
      "external": false,
      "loc": "kernel/kthread.c:162",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_should_park"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool __kthread_should_park(struct task_struct * k)
```

```json
{
  "name": "__kthread_should_park",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490840428,
      "name": "__kthread_should_park",
      "external": true,
      "loc": "kernel/kthread.c:107",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_should_park"
      ],
      "caller_func": [
        "kernel/softirq.c:ksoftirqd_running"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490840320,
      "name": "__kthread_should_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool __kthread_should_park(struct task_struct * k)
```

```json
{
  "name": "__kthread_should_park",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224869536,
      "name": "__kthread_should_park",
      "external": true,
      "loc": "kernel/kthread.c:107",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:ksoftirqd_running",
        "kernel/kthread.c:kthread_should_park"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224869536,
      "name": "__kthread_should_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool __kthread_should_park(struct task_struct * k)
```

```json
{
  "name": "__kthread_should_park",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283683180,
      "name": "__kthread_should_park",
      "external": true,
      "loc": "kernel/kthread.c:107",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_should_park"
      ],
      "caller_func": [
        "kernel/softirq.c:ksoftirqd_running"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283683072,
      "name": "__kthread_should_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool __kthread_should_park(struct task_struct * k)
```

```json
{
  "name": "__kthread_should_park",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271509926,
      "name": "__kthread_should_park",
      "external": true,
      "loc": "kernel/kthread.c:107",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_should_park"
      ],
      "caller_func": [
        "kernel/softirq.c:ksoftirqd_running"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271509852,
      "name": "__kthread_should_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool __kthread_should_park(struct task_struct * k)
```

```json
{
  "name": "__kthread_should_park",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579640351,
      "name": "__kthread_should_park",
      "external": true,
      "loc": "kernel/kthread.c:107",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_should_park"
      ],
      "caller_func": [
        "kernel/softirq.c:ksoftirqd_running"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640288,
      "name": "__kthread_should_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool __kthread_should_park(struct task_struct * k)
```

```json
{
  "name": "__kthread_should_park",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579568751,
      "name": "__kthread_should_park",
      "external": true,
      "loc": "kernel/kthread.c:107",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_should_park"
      ],
      "caller_func": [
        "kernel/softirq.c:ksoftirqd_running"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568688,
      "name": "__kthread_should_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool __kthread_should_park(struct task_struct * k)
```

```json
{
  "name": "__kthread_should_park",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579637615,
      "name": "__kthread_should_park",
      "external": true,
      "loc": "kernel/kthread.c:107",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_should_park"
      ],
      "caller_func": [
        "kernel/softirq.c:ksoftirqd_running"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637552,
      "name": "__kthread_should_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool __kthread_should_park(struct task_struct * k)
```

```json
{
  "name": "__kthread_should_park",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579671455,
      "name": "__kthread_should_park",
      "external": true,
      "loc": "kernel/kthread.c:107",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_should_park"
      ],
      "caller_func": [
        "kernel/softirq.c:ksoftirqd_running"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671392,
      "name": "__kthread_should_park",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool __kthread_should_park(struct task_struct * k)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
bool __kthread_should_park(struct task_struct * k)
```
</details>
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
