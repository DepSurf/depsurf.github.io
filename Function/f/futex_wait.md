# Function: <code>futex_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894544,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2269",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_wait_restart",
        "kernel/futex.c:do_futex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894544,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579925584,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2393",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579925584,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579956288,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2402",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956288,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579960816,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2488",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579960816,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580007824,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2629",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007824,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580061872,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2611",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580061872,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580108192,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2679",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580108192,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580153184,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2710",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153184,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580200992,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2802",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580200992,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580269456,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2715",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580269456,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580252016,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2683",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252016,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580257216,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2682",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580257216,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580408464,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2929",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580408464,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580644752,
      "name": "futex_wait",
      "external": true,
      "loc": "kernel/futex/waitwake.c:632",
      "file": "kernel/futex/waitwake.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/syscalls.c:do_futex",
        "kernel/futex/waitwake.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580644752,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580911392,
      "name": "futex_wait",
      "external": true,
      "loc": "kernel/futex/waitwake.c:632",
      "file": "kernel/futex/waitwake.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/syscalls.c:do_futex",
        "kernel/futex/waitwake.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580911392,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580995296,
      "name": "futex_wait",
      "external": true,
      "loc": "kernel/futex/waitwake.c:632",
      "file": "kernel/futex/waitwake.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/syscalls.c:do_futex",
        "kernel/futex/waitwake.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995296,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581091776,
      "name": "futex_wait",
      "external": true,
      "loc": "kernel/futex/waitwake.c:688",
      "file": "kernel/futex/waitwake.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/syscalls.c:do_futex",
        "kernel/futex/waitwake.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581091776,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491438832,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2802",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491438832,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225429220,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2802",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225429220,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284385904,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2802",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284385904,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271896668,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2802",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271896668,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580169792,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2802",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169792,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580120320,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2802",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580120320,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580161264,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2802",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580161264,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
int futex_wait(u32 * uaddr, unsigned int flags, u32 val, ktime_t * abs_time, u32 bitset)
```

```json
{
  "name": "futex_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580215392,
      "name": "futex_wait",
      "external": false,
      "loc": "kernel/futex.c:2802",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:futex_wait_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215392,
      "name": "futex_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 594
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
