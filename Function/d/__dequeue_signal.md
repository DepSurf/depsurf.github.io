# Function: <code>__dequeue_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending * pending, sigset_t * mask, siginfo_t * info)
```

```json
{
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579423904,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:543",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579423904,
      "name": "__dequeue_signal",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending * pending, sigset_t * mask, siginfo_t * info)
```

```json
{
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579435888,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:543",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435888,
      "name": "__dequeue_signal",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending * pending, sigset_t * mask, siginfo_t * info)
```

```json
{
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579456240,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:545",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456240,
      "name": "__dequeue_signal",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending * pending, sigset_t * mask, siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579444576,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:558",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444576,
      "name": "__dequeue_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
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
int __dequeue_signal(struct sigpending * pending, sigset_t * mask, siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579472880,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:560",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579472880,
      "name": "__dequeue_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending * pending, sigset_t * mask, siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579489536,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:563",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489536,
      "name": "__dequeue_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
int __dequeue_signal(struct sigpending * pending, sigset_t * mask, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523024,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:597",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523024,
      "name": "__dequeue_signal",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending * pending, sigset_t * mask, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542704,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:607",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542704,
      "name": "__dequeue_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int __dequeue_signal(struct sigpending * pending, sigset_t * mask, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568816,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:612",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568816,
      "name": "__dequeue_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579602674,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:612",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579582882,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:613",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579590066,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:612",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579667506,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:613",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
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
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579763131,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:613",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
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
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579895883,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:613",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
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
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579945291,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:618",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
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
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579984683,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:609",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
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
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490727364,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:612",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
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
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224783340,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:612",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
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
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283553228,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:612",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271441336,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:612",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __dequeue_signal(struct sigpending * pending, sigset_t * mask, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579545120,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:612",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545120,
      "name": "__dequeue_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int __dequeue_signal(struct sigpending * pending, sigset_t * mask, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579473856,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:612",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579473856,
      "name": "__dequeue_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int __dequeue_signal(struct sigpending * pending, sigset_t * mask, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542400,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:612",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542400,
      "name": "__dequeue_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
int __dequeue_signal(struct sigpending * pending, sigset_t * mask, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "__dequeue_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579575392,
      "name": "__dequeue_signal",
      "external": false,
      "loc": "kernel/signal.c:612",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579575392,
      "name": "__dequeue_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool * resched_timer</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>siginfo_t * info</code> ➡️ <code>kernel_siginfo_t * info</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int __dequeue_signal(struct sigpending * pending, sigset_t * mask, kernel_siginfo_t * info, bool * resched_timer)
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
int __dequeue_signal(struct sigpending * pending, sigset_t * mask, kernel_siginfo_t * info, bool * resched_timer)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __dequeue_signal(struct sigpending * pending, sigset_t * mask, kernel_siginfo_t * info, bool * resched_timer)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __dequeue_signal(struct sigpending * pending, sigset_t * mask, kernel_siginfo_t * info, bool * resched_timer)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __dequeue_signal(struct sigpending * pending, sigset_t * mask, kernel_siginfo_t * info, bool * resched_timer)
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
