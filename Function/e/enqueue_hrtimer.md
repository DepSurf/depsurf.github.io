# Function: <code>enqueue_hrtimer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579822704,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:876",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822704,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851984,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:866",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851984,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880960,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:866",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880960,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890176,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:839",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890176,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579934688,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:839",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934688,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579981680,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:950",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981680,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580028480,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:941",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028480,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071360,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:940",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071360,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580120896,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:961",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580120896,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580181344,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:961",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__run_hrtimer",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181344,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580166832,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:978",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__run_hrtimer",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580166832,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170960,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:978",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170960,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1080",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315376,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071592151324,
      "name": "enqueue_hrtimer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1080",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580526400,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071593926311,
      "name": "enqueue_hrtimer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1080",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580782304,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071595994488,
      "name": "enqueue_hrtimer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1083",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865312,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071596512807,
      "name": "enqueue_hrtimer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:1083",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_cpu_dying",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:__hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954976,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    },
    {
      "addr": 18446744071597412131,
      "name": "enqueue_hrtimer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491339720,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:961",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491339720,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225330880,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:961",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225330880,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284267040,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:961",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284267040,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271837348,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:961",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580090096,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:961",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090096,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580035424,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:961",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035424,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580081168,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:961",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081168,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
```

```json
{
  "name": "enqueue_hrtimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580132672,
      "name": "enqueue_hrtimer",
      "external": false,
      "loc": "kernel/time/hrtimer.c:961",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:__hrtimer_run_queues",
        "kernel/time/hrtimer.c:hrtimer_start_range_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132672,
      "name": "enqueue_hrtimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum hrtimer_mode mode</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int enqueue_hrtimer(struct hrtimer * timer, struct hrtimer_clock_base * base, enum hrtimer_mode mode)
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
