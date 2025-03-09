# Function: <code>clock_was_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579822902,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:753",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64",
        "kernel/time/timekeeping.c:timekeeping_set_tai_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:do_adjtimex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579826224,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579851638,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:743",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_set_tai_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855024,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579880246,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:743",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_set_tai_offset",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883728,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579889782,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:744",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892576,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579934294,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:746",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937152,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579981877,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:857",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984496,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580028677,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:848",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580031152,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580071557,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:847",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580074432,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580121093,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:868",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580123616,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580181301,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:868",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580184560,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580166229,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:885",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169360,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580170917,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:885",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580173888,
      "name": "clock_was_set",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void clock_was_set(unsigned int bases)
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:945",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592151455,
      "name": "clock_was_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071580318896,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 571
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
void clock_was_set(unsigned int bases)
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:945",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593926442,
      "name": "clock_was_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071580530288,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 614
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
void clock_was_set(unsigned int bases)
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:945",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595994620,
      "name": "clock_was_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071580786448,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
void clock_was_set(unsigned int bases)
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:947",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596512939,
      "name": "clock_was_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580869632,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
void clock_was_set(unsigned int bases)
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:947",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:clock_was_set_work",
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset",
        "kernel/time/timekeeping.c:do_settimeofday64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597412266,
      "name": "clock_was_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580960128,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491338552,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:868",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491342976,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225332012,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:868",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225336448,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284268956,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:868",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284273296,
      "name": "clock_was_set",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271836264,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:868",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271839148,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580090293,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:868",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580092816,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580035621,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:868",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038144,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580081365,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:868",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083888,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void clock_was_set()
```

```json
{
  "name": "clock_was_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580132901,
      "name": "clock_was_set",
      "external": true,
      "loc": "kernel/time/hrtimer.c:868",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:clock_was_set_work"
      ],
      "caller_func": [
        "kernel/time/timekeeping.c:do_adjtimex",
        "kernel/time/timekeeping.c:timekeeping_inject_sleeptime64",
        "kernel/time/timekeeping.c:timekeeping_inject_offset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580135600,
      "name": "clock_was_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int bases</code>
</li>
</ul>
</details>
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
