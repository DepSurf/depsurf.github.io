# Function: <code>ktime_get_clocktai</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579822848,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:196",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579831014,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:196",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580391425,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:196",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_tai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822848,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579851488,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:212",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579859718,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:212",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580459169,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:212",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_tai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851488,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579880096,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:212",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579915430,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:212",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580521617,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:212",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_tai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880096,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579889408,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:201",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579924694,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:201",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580554209,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:201",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_tai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889408,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579933920,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:81",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579970118,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:81",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580634977,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:81",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_tai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933920,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579981824,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:91",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580017829,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:91",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580761536,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:91",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_tai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981824,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580028624,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580065013,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580828352,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_tai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028624,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580071504,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580108661,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580923312,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_clocktai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071504,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580121040,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580157829,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977504,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_clocktai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121040,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580180992,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580219013,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai_ktime",
        "kernel/time/posix-timers.c:posix_get_tai_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581144032,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_clocktai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180992,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580165920,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:105",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580203269,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:105",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai_ktime",
        "kernel/time/posix-timers.c:posix_get_tai_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581184080,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:105",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_clocktai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165920,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580170480,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580208565,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai_ktime",
        "kernel/time/posix-timers.c:posix_get_tai_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581202448,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_clocktai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170480,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580314848,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580356085,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai_ktime",
        "kernel/time/posix-timers.c:posix_get_tai_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581442096,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_clocktai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580314848,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580525712,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580570757,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai_ktime",
        "kernel/time/posix-timers.c:posix_get_tai_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581783312,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_clocktai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580525712,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580781520,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580831317,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai_ktime",
        "kernel/time/posix-timers.c:posix_get_tai_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582209056,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_clocktai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781520,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580864512,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580914869,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai_ktime",
        "kernel/time/posix-timers.c:posix_get_tai_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582409072,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_clocktai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864512,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580955184,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:107",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581005477,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:107",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai_ktime",
        "kernel/time/posix-timers.c:posix_get_tai_timespec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582577296,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:107",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_clocktai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955184,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491338464,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491379520,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492326224,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_clocktai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491338464,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225331920,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225379220,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai"
      ],
      "caller_func": []
    },
    {
      "addr": 3226218276,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_clocktai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225331920,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284268784,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284320112,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285572500,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_clocktai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284268784,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271836168,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271867540,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272451086,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_clocktai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271836168,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580090240,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580127029,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580946304,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_clocktai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090240,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580035568,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580072325,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580892368,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_clocktai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035568,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580081312,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580118101,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580937552,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_clocktai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081312,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
ktime_t ktime_get_clocktai()
```

```json
{
  "name": "ktime_get_clocktai",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580132848,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580169957,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:posix_get_tai"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580999136,
      "name": "ktime_get_clocktai",
      "external": false,
      "loc": "include/linux/timekeeping.h:106",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:ktime_get_clocktai_ns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132848,
      "name": "ktime_get_clocktai",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
