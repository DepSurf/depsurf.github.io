# Function: <code>update_wall_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579853248,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2034",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/tick-common.c:tick_periodic",
        "kernel/time/tick-sched.c:tick_do_update_jiffies64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853248,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1945
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579882464,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2039",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/tick-common.c:tick_periodic",
        "kernel/time/tick-sched.c:tick_do_update_jiffies64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882464,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1913
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894224,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2051",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894224,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1913
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579902880,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2040",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902880,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1768
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579947840,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2075",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947840,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1771
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2028",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:xtime_update",
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998301,
      "name": "update_wall_time.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071579995840,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1416
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580044612,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2125",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:xtime_update"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580043552,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580088101,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2135",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:xtime_update"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580086880,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580137189,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2135",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:xtime_update"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580135968,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580198709,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2134",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:xtime_update"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580197488,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580182464,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2197",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580182464,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580186928,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2208",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580186928,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580333136,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2208",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580333136,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580545872,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2229",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545872,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580803104,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2229",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580803104,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580886256,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2229",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580886256,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976688,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2229",
      "file": "kernel/time/timekeeping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976688,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491358636,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2135",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:xtime_update"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491357216,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225356732,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2135",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:xtime_update"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225355216,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284291756,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2135",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:xtime_update"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284290032,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271850788,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2135",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:xtime_update"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271849612,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580106389,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2135",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:xtime_update"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105168,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580051701,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2135",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:xtime_update"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050480,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580097461,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2135",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:xtime_update"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096240,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void update_wall_time()
```

```json
{
  "name": "update_wall_time",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580149203,
      "name": "update_wall_time",
      "external": true,
      "loc": "kernel/time/timekeeping.c:2135",
      "file": "kernel/time/timekeeping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:xtime_update"
      ],
      "caller_func": [
        "kernel/time/tick-common.c:tick_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147984,
      "name": "update_wall_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
