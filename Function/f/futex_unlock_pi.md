# Function: <code>futex_unlock_pi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579905074,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:2496",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/futex.c:do_futex"
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
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579934786,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:2620",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/futex.c:do_futex"
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
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579965490,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:2629",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/futex.c:do_futex"
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
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579971311,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:2769",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/futex.c:do_futex"
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
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580017813,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:2913",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/futex.c:do_futex"
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
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580069805,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:2895",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/futex.c:do_futex"
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
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580118565,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:2967",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/futex.c:do_futex"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:2983",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580154592,
      "name": "futex_unlock_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 873
    },
    {
      "addr": 18446744071580166544,
      "name": "futex_unlock_pi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580202688,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:3084",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580202688,
      "name": "futex_unlock_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 891
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
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580271824,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:2997",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580271824,
      "name": "futex_unlock_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580256432,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:2944",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580256432,
      "name": "futex_unlock_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580261152,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:2943",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580261152,
      "name": "futex_unlock_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
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
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580412192,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:3189",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580412192,
      "name": "futex_unlock_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 755
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
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580636704,
      "name": "futex_unlock_pi",
      "external": true,
      "loc": "kernel/futex/pi.c:1100",
      "file": "kernel/futex/pi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/syscalls.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580636704,
      "name": "futex_unlock_pi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 817
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
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580903232,
      "name": "futex_unlock_pi",
      "external": true,
      "loc": "kernel/futex/pi.c:1100",
      "file": "kernel/futex/pi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/syscalls.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580903232,
      "name": "futex_unlock_pi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 817
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
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580987184,
      "name": "futex_unlock_pi",
      "external": true,
      "loc": "kernel/futex/pi.c:1100",
      "file": "kernel/futex/pi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/syscalls.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580987184,
      "name": "futex_unlock_pi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 810
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
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581082816,
      "name": "futex_unlock_pi",
      "external": true,
      "loc": "kernel/futex/pi.c:1112",
      "file": "kernel/futex/pi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/syscalls.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082816,
      "name": "futex_unlock_pi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 829
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
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491436088,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:3084",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491436088,
      "name": "futex_unlock_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1436
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
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225427656,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:3084",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225427656,
      "name": "futex_unlock_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1120
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
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284383296,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:3084",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284383296,
      "name": "futex_unlock_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1724
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
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271900282,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:3084",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271900282,
      "name": "futex_unlock_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1176
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
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580171488,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:3084",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580171488,
      "name": "futex_unlock_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 891
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
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580121040,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:3084",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121040,
      "name": "futex_unlock_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 885
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
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580162960,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:3084",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580162960,
      "name": "futex_unlock_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 891
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
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```

```json
{
  "name": "futex_unlock_pi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580217680,
      "name": "futex_unlock_pi",
      "external": false,
      "loc": "kernel/futex.c:3084",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217680,
      "name": "futex_unlock_pi",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 916
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int futex_unlock_pi(u32 * uaddr, unsigned int flags)
```
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
