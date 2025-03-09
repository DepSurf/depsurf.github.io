# Function: <code>idle_inject_timer_fn</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686896,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:280",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686896,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579673104,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:286",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673104,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579703792,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:286",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579703792,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579648176,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:303",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579648176,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579685808,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:303",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587773600,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:105",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685808,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071587773600,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579719536,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:304",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588078512,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:105",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719536,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071588078512,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579762048,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:304",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588284320,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:105",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579762048,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071588284320,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579795584,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:321",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589164912,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:107",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579795584,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071589164912,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579786400,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:345",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589161136,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:108",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786400,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071589161136,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579794528,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:351",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589055024,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:108",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579794528,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071589055024,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890496,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:351",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589773024,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:108",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890496,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071589773024,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580085440,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:348",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591283088,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:108",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085440,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071591283088,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580256912,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:348",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593032624,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:108",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580256912,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071593032624,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580322912,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:327",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593484688,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:124",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580322912,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071593484688,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580376848,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:357",
      "file": "kernel/sched/build_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594231936,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:124",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580376848,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071594231936,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490940784,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:304",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501755840,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:105",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490940784,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446603336501755840,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224959100,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:304",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234308140,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:105",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224959100,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 3234308140,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283795952,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:304",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055295201696,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:105",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283795952,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 13835058055295201696,
      "name": "idle_inject_timer_fn",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271571948,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:304",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271571948,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579737968,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:304",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737968,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668384,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:304",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668384,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579722416,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:304",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588221376,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:105",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579722416,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071588221376,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```

```json
{
  "name": "idle_inject_timer_fn",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579769840,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "kernel/sched/idle.c:304",
      "file": "kernel/sched/idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588356672,
      "name": "idle_inject_timer_fn",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:105",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579769840,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071588356672,
      "name": "idle_inject_timer_fn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
enum hrtimer_restart idle_inject_timer_fn(struct hrtimer * timer)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
