# Function: <code>swake_up_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579661664,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:19",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/swait.c:swake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661664,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579685936,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:19",
      "file": "kernel/sched/swait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/swait.c:swake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685936,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579672294,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:19",
      "file": "kernel/sched/swait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:swake_up"
      ],
      "caller_func": [
        "kernel/sched/swait.c:swake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672176,
      "name": "swake_up_locked.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579672224,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579703044,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:20",
      "file": "kernel/sched/swait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:swake_up"
      ],
      "caller_func": [
        "kernel/sched/swait.c:swake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702944,
      "name": "swake_up_locked.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579702992,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579737291,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:22",
      "file": "kernel/sched/swait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:swake_up"
      ],
      "caller_func": [
        "kernel/sched/swait.c:swake_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737184,
      "name": "swake_up_locked.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579737232,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579777115,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:22",
      "file": "kernel/sched/swait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:swake_up_one"
      ],
      "caller_func": [
        "kernel/sched/swait.c:swake_up_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579777008,
      "name": "swake_up_locked.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579777056,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579804797,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:22",
      "file": "kernel/sched/swait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:swake_up_one"
      ],
      "caller_func": [
        "kernel/sched/swait.c:swake_up_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804688,
      "name": "swake_up_locked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579804736,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579852365,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:22",
      "file": "kernel/sched/swait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:swake_up_one"
      ],
      "caller_func": [
        "kernel/sched/swait.c:swake_up_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852256,
      "name": "swake_up_locked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579852304,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579891166,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:22",
      "file": "kernel/sched/swait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:swake_up_one",
        "kernel/sched/swait.c:swake_up_one",
        "kernel/sched/swait.c:swake_up_all_locked",
        "kernel/sched/swait.c:swake_up_all_locked"
      ],
      "caller_func": [
        "kernel/sched/completion.c:complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891472,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579885550,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:22",
      "file": "kernel/sched/swait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:swake_up_one",
        "kernel/sched/swait.c:swake_up_one",
        "kernel/sched/swait.c:swake_up_all_locked",
        "kernel/sched/swait.c:swake_up_all_locked"
      ],
      "caller_func": [
        "kernel/sched/completion.c:complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886112,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579894734,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:22",
      "file": "kernel/sched/swait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:swake_up_one",
        "kernel/sched/swait.c:swake_up_one",
        "kernel/sched/swait.c:swake_up_all_locked",
        "kernel/sched/swait.c:swake_up_all_locked"
      ],
      "caller_func": [
        "kernel/sched/completion.c:complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895056,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580009550,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:22",
      "file": "kernel/sched/swait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:swake_up_one",
        "kernel/sched/swait.c:swake_up_one",
        "kernel/sched/swait.c:swake_up_all_locked",
        "kernel/sched/swait.c:swake_up_all_locked"
      ],
      "caller_func": [
        "kernel/sched/completion.c:complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009840,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580163773,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:21",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:swake_up_one",
        "kernel/sched/build_utility.c:swake_up_one",
        "kernel/sched/build_utility.c:complete_all",
        "kernel/sched/build_utility.c:complete_all",
        "kernel/sched/build_utility.c:complete",
        "kernel/sched/build_utility.c:complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163648,
      "name": "swake_up_locked",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580340029,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:21",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:swake_up_one",
        "kernel/sched/build_utility.c:swake_up_one",
        "kernel/sched/build_utility.c:complete_all",
        "kernel/sched/build_utility.c:complete_all",
        "kernel/sched/build_utility.c:complete",
        "kernel/sched/build_utility.c:complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580339344,
      "name": "swake_up_locked",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580407901,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:21",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:swake_up_one",
        "kernel/sched/build_utility.c:swake_up_one",
        "kernel/sched/build_utility.c:complete_all",
        "kernel/sched/build_utility.c:complete_all",
        "kernel/sched/build_utility.c:complete",
        "kernel/sched/build_utility.c:complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580406704,
      "name": "swake_up_locked",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void swake_up_locked(struct swait_queue_head * q, int wake_flags)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580465837,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:21",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:swake_up_one",
        "kernel/sched/build_utility.c:swake_up_one",
        "kernel/sched/build_utility.c:complete_all",
        "kernel/sched/build_utility.c:complete_all",
        "kernel/sched/build_utility.c:complete",
        "kernel/sched/build_utility.c:complete",
        "kernel/sched/build_utility.c:complete_on_current_cpu",
        "kernel/sched/build_utility.c:complete_on_current_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580465008,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491046496,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:22",
      "file": "kernel/sched/swait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:swake_up_one"
      ],
      "caller_func": [
        "kernel/sched/swait.c:swake_up_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491045536,
      "name": "swake_up_locked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446603336491045608,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225053704,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:22",
      "file": "kernel/sched/swait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:swake_up_one"
      ],
      "caller_func": [
        "kernel/sched/swait.c:swake_up_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225053560,
      "name": "swake_up_locked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 3225053616,
      "name": "swake_up_locked",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283923652,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:22",
      "file": "kernel/sched/swait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:swake_up_one"
      ],
      "caller_func": [
        "kernel/sched/swait.c:swake_up_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283923456,
      "name": "swake_up_locked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 13835058055283923552,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271643946,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:22",
      "file": "kernel/sched/swait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:swake_up_one"
      ],
      "caller_func": [
        "kernel/sched/swait.c:swake_up_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271643802,
      "name": "swake_up_locked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446743936271643860,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579824717,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:22",
      "file": "kernel/sched/swait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:swake_up_one"
      ],
      "caller_func": [
        "kernel/sched/swait.c:swake_up_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824608,
      "name": "swake_up_locked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579824656,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579759309,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:22",
      "file": "kernel/sched/swait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:swake_up_one"
      ],
      "caller_func": [
        "kernel/sched/swait.c:swake_up_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579759200,
      "name": "swake_up_locked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579759248,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579812733,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:22",
      "file": "kernel/sched/swait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:swake_up_one"
      ],
      "caller_func": [
        "kernel/sched/swait.c:swake_up_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579812624,
      "name": "swake_up_locked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579812672,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void swake_up_locked(struct swait_queue_head * q)
```

```json
{
  "name": "swake_up_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579858093,
      "name": "swake_up_locked",
      "external": true,
      "loc": "kernel/sched/swait.c:22",
      "file": "kernel/sched/swait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/swait.c:swake_up_one"
      ],
      "caller_func": [
        "kernel/sched/swait.c:swake_up_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857984,
      "name": "swake_up_locked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579858032,
      "name": "swake_up_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void swake_up_locked(struct swait_queue_head * q)
```
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int wake_flags</code>
</li>
</ul>
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
