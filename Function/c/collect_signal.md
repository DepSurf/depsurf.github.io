# Function: <code>collect_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579423959,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:506",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__dequeue_signal"
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
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579435942,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:506",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__dequeue_signal"
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
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579456294,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:508",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__dequeue_signal"
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
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579444627,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:514",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__dequeue_signal"
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
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579472941,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:516",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__dequeue_signal"
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
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579489593,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:518",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__dequeue_signal"
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
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579523081,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:552",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__dequeue_signal"
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
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579542767,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:562",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__dequeue_signal"
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
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579568879,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:567",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__dequeue_signal"
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
void collect_signal(int sig, struct sigpending * list, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579600464,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:567",
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
      "addr": 18446744071579600464,
      "name": "collect_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
void collect_signal(int sig, struct sigpending * list, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579580672,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:568",
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
      "addr": 18446744071579580672,
      "name": "collect_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
void collect_signal(int sig, struct sigpending * list, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579586080,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:567",
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
      "addr": 18446744071579586080,
      "name": "collect_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
void collect_signal(int sig, struct sigpending * list, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:568",
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
      "addr": 18446744071579661328,
      "name": "collect_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071592101565,
      "name": "collect_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void collect_signal(int sig, struct sigpending * list, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:568",
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
      "addr": 18446744071579762656,
      "name": "collect_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071593869335,
      "name": "collect_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void collect_signal(int sig, struct sigpending * list, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:568",
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
      "addr": 18446744071579895424,
      "name": "collect_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071595974864,
      "name": "collect_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void collect_signal(int sig, struct sigpending * list, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:573",
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
      "addr": 18446744071579944832,
      "name": "collect_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071596492384,
      "name": "collect_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void collect_signal(int sig, struct sigpending * list, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:564",
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
      "addr": 18446744071579984224,
      "name": "collect_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071597389145,
      "name": "collect_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void collect_signal(int sig, struct sigpending * list, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490726968,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:567",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490726968,
      "name": "collect_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
void collect_signal(int sig, struct sigpending * list, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224782476,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:567",
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
      "addr": 3224782476,
      "name": "collect_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
void collect_signal(int sig, struct sigpending * list, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283552800,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:567",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal",
        "kernel/signal.c:dequeue_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283552800,
      "name": "collect_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
void collect_signal(int sig, struct sigpending * list, kernel_siginfo_t * info, bool * resched_timer)
```

```json
{
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271439916,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:567",
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
      "addr": 18446743936271439916,
      "name": "collect_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579545183,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:567",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__dequeue_signal"
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
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579473919,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:567",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__dequeue_signal"
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
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579542463,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:567",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__dequeue_signal"
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
  "name": "collect_signal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579575455,
      "name": "collect_signal",
      "external": false,
      "loc": "kernel/signal.c:567",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__dequeue_signal"
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
void collect_signal(int sig, struct sigpending * list, kernel_siginfo_t * info, bool * resched_timer)
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void collect_signal(int sig, struct sigpending * list, kernel_siginfo_t * info, bool * resched_timer)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void collect_signal(int sig, struct sigpending * list, kernel_siginfo_t * info, bool * resched_timer)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void collect_signal(int sig, struct sigpending * list, kernel_siginfo_t * info, bool * resched_timer)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void collect_signal(int sig, struct sigpending * list, kernel_siginfo_t * info, bool * resched_timer)
```
</details>
</li>
</ul>
