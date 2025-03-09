# Function: <code>attach_to_pi_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int attach_to_pi_state(u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579891760,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:892",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:futex_requeue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891760,
      "name": "attach_to_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int attach_to_pi_state(u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579921456,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:972",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579921456,
      "name": "attach_to_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int attach_to_pi_state(u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952112,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:981",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952112,
      "name": "attach_to_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int attach_to_pi_state(u32 * uaddr, u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579965552,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:1024",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965552,
      "name": "attach_to_pi_state",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int attach_to_pi_state(u32 * uaddr, u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009952,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:1051",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009952,
      "name": "attach_to_pi_state",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int attach_to_pi_state(u32 * uaddr, u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580059840,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:1033",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059840,
      "name": "attach_to_pi_state",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int attach_to_pi_state(u32 * uaddr, u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580108896,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:1041",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580108896,
      "name": "attach_to_pi_state",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int attach_to_pi_state(u32 * uaddr, u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:1056",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153920,
      "name": "attach_to_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071580166525,
      "name": "attach_to_pi_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int attach_to_pi_state(u32 * uaddr, u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580202016,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:1078",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580202016,
      "name": "attach_to_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int attach_to_pi_state(u32 * uaddr, u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580270576,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:1006",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580270576,
      "name": "attach_to_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int attach_to_pi_state(u32 * uaddr, u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580256144,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:1003",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580256144,
      "name": "attach_to_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
int attach_to_pi_state(u32 * uaddr, u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580260864,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:1003",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580260864,
      "name": "attach_to_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580414267,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:1061",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_lock_pi_atomic"
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
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580634652,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex/pi.c:202",
      "file": "kernel/futex/pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/futex/pi.c:futex_lock_pi_atomic"
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
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580901132,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex/pi.c:202",
      "file": "kernel/futex/pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/futex/pi.c:futex_lock_pi_atomic"
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
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580985100,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex/pi.c:202",
      "file": "kernel/futex/pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/futex/pi.c:futex_lock_pi_atomic"
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
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581080684,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex/pi.c:203",
      "file": "kernel/futex/pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/futex/pi.c:futex_lock_pi_atomic"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int attach_to_pi_state(u32 * uaddr, u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491439544,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:1078",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491439544,
      "name": "attach_to_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int attach_to_pi_state(u32 * uaddr, u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225423288,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:1078",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225423288,
      "name": "attach_to_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
int attach_to_pi_state(u32 * uaddr, u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284386816,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:1078",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284386816,
      "name": "attach_to_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
int attach_to_pi_state(u32 * uaddr, u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271898888,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:1078",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271898888,
      "name": "attach_to_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
int attach_to_pi_state(u32 * uaddr, u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170816,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:1078",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170816,
      "name": "attach_to_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int attach_to_pi_state(u32 * uaddr, u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580117104,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:1078",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580117104,
      "name": "attach_to_pi_state",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int attach_to_pi_state(u32 * uaddr, u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580162288,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:1078",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580162288,
      "name": "attach_to_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int attach_to_pi_state(u32 * uaddr, u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```

```json
{
  "name": "attach_to_pi_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580209440,
      "name": "attach_to_pi_state",
      "external": false,
      "loc": "kernel/futex.c:1078",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_lock_pi_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580209440,
      "name": "attach_to_pi_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
<code>u32 * uaddr</code>
</li>
<li>
<b>Param reordered. </b>
<code>uval, pi_state, ps</code> ➡️ <code>uaddr, uval, pi_state, ps</code>
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
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int attach_to_pi_state(u32 * uaddr, u32 uval, struct futex_pi_state * pi_state, struct futex_pi_state * * ps)
```
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
