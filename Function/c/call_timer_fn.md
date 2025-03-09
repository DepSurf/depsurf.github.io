# Function: <code>call_timer_fn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list * timer, void (*)(long unsigned int) fn, long unsigned int data)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579812624,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1153",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579812624,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
void call_timer_fn(struct timer_list * timer, void (*)(long unsigned int) fn, long unsigned int data)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579842992,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1273",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579842992,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
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
void call_timer_fn(struct timer_list * timer, void (*)(long unsigned int) fn, long unsigned int data)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872592,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1283",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872592,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
void call_timer_fn(struct timer_list * timer, void (*)(long unsigned int) fn, long unsigned int data)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579881584,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1256",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579881584,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579924816,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1294",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579924816,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579971312,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1302",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579971312,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580018384,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1301",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580018384,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn, long unsigned int baseclk)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580062640,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1296",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062640,
      "name": "call_timer_fn",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn, long unsigned int baseclk)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111696,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1378",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111696,
      "name": "call_timer_fn",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn, long unsigned int baseclk)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580173408,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1390",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580173408,
      "name": "call_timer_fn",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn, long unsigned int baseclk)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580158656,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1391",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158656,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn, long unsigned int baseclk)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580163136,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1409",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163136,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn, long unsigned int baseclk)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1395",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307856,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071592151233,
      "name": "call_timer_fn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn, long unsigned int baseclk)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1448",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:__run_timers",
        "kernel/time/timer.c:__run_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580519936,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071593926198,
      "name": "call_timer_fn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn, long unsigned int baseclk)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1674",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:__run_timers",
        "kernel/time/timer.c:__run_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580775248,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071595994377,
      "name": "call_timer_fn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn, long unsigned int baseclk)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1674",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:__run_timers",
        "kernel/time/timer.c:__run_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580858032,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071596512676,
      "name": "call_timer_fn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn, long unsigned int baseclk)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1674",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:__run_timers",
        "kernel/time/timer.c:__run_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580948480,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
    },
    {
      "addr": 18446744071597411930,
      "name": "call_timer_fn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn, long unsigned int baseclk)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491328888,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1378",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491328888,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn, long unsigned int baseclk)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225319396,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1378",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225319396,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn, long unsigned int baseclk)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284253536,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1378",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284253536,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn, long unsigned int baseclk)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271826860,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1378",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271826860,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn, long unsigned int baseclk)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580080896,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1378",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080896,
      "name": "call_timer_fn",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn, long unsigned int baseclk)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580025712,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1378",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580025712,
      "name": "call_timer_fn",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn, long unsigned int baseclk)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071968,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1378",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071968,
      "name": "call_timer_fn",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void call_timer_fn(struct timer_list * timer, void (*)(struct timer_list *) fn, long unsigned int baseclk)
```

```json
{
  "name": "call_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122784,
      "name": "call_timer_fn",
      "external": false,
      "loc": "kernel/time/timer.c:1378",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq",
        "kernel/time/timer.c:run_timer_softirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122784,
      "name": "call_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int data</code>
</li>
<li>
<b>Param type changed. </b>
<code>void (*)(long unsigned int) fn</code> ➡️ <code>void (*)(struct timer_list *) fn</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int baseclk</code>
</li>
</ul>
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
