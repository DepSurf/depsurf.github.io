# Function: <code>second_overflow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int second_overflow(long unsigned int secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579856480,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:393",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:update_wall_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856480,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579885536,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:398",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:update_wall_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579885536,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579897296,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:398",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:update_wall_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897296,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579905808,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:398",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:update_wall_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905808,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 729
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
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579951264,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:399",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:update_wall_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951264,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 735
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:399",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:update_wall_time",
        "kernel/time/timekeeping.c:update_wall_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001495,
      "name": "second_overflow.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579998880,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:398",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047831,
      "name": "second_overflow.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071580045232,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
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
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:400",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091450,
      "name": "second_overflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071580088848,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:400",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580140410,
      "name": "second_overflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071580137808,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:400",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580202097,
      "name": "second_overflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071580200144,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:400",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591311515,
      "name": "second_overflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071580184832,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:400",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591253787,
      "name": "second_overflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071580189248,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 693
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
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:400",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592154127,
      "name": "second_overflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    },
    {
      "addr": 18446744071580335520,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 774
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
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:400",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593929134,
      "name": "second_overflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    },
    {
      "addr": 18446744071580548400,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:400",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595997162,
      "name": "second_overflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071580805856,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 827
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
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:400",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596515492,
      "name": "second_overflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071580889008,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 836
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
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:400",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597414819,
      "name": "second_overflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071580979440,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 836
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
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491359752,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:400",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491359752,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225357664,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:400",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225357664,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
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
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284292512,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:400",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284292512,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1260
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
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271851460,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:400",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271851460,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:400",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580109610,
      "name": "second_overflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071580107008,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:400",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054922,
      "name": "second_overflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071580052320,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:400",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100682,
      "name": "second_overflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071580098080,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int second_overflow(time64_t secs)
```

```json
{
  "name": "second_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "second_overflow",
      "external": true,
      "loc": "kernel/time/ntp.c:400",
      "file": "kernel/time/ntp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_advance",
        "kernel/time/timekeeping.c:timekeeping_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152426,
      "name": "second_overflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071580149824,
      "name": "second_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int secs</code> ➡️ <code>time64_t secs</code>
</li>
</ul>
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
