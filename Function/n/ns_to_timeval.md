# Function: <code>ns_to_timeval</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct timeval ns_to_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579807920,
      "name": "ns_to_timeval",
      "external": true,
      "loc": "kernel/time/time.c:414",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:do_setitimer",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestamp",
        "net/core/sock.c:sock_get_timestamp",
        "net/compat.c:compat_sock_get_timestamp",
        "net/compat.c:compat_sock_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807920,
      "name": "ns_to_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct timeval ns_to_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579835776,
      "name": "ns_to_timeval",
      "external": true,
      "loc": "kernel/time/time.c:421",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/itimer.c:itimer_get_remtime",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestamp",
        "net/core/sock.c:sock_get_timestamp",
        "net/compat.c:compat_sock_get_timestamp",
        "net/compat.c:compat_sock_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835776,
      "name": "ns_to_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct timeval ns_to_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579864832,
      "name": "ns_to_timeval",
      "external": true,
      "loc": "kernel/time/time.c:421",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/itimer.c:itimer_get_remtime",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestamp",
        "net/core/sock.c:sock_get_timestamp",
        "net/compat.c:compat_sock_get_timestamp",
        "net/compat.c:compat_sock_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579864832,
      "name": "ns_to_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct timeval ns_to_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579873696,
      "name": "ns_to_timeval",
      "external": true,
      "loc": "kernel/time/time.c:511",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/itimer.c:itimer_get_remtime",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestamp",
        "net/core/sock.c:sock_get_timestamp",
        "net/compat.c:compat_sock_get_timestamp",
        "net/compat.c:compat_sock_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873696,
      "name": "ns_to_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct timeval ns_to_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579917120,
      "name": "ns_to_timeval",
      "external": true,
      "loc": "kernel/time/time.c:479",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/itimer.c:itimer_get_remtime",
        "drivers/input/evdev.c:evdev_pass_values",
        "drivers/input/evdev.c:__evdev_queue_syn_dropped",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestamp",
        "net/core/sock.c:sock_get_timestamp",
        "net/compat.c:compat_sock_get_timestamp",
        "net/compat.c:compat_sock_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917120,
      "name": "ns_to_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct timeval ns_to_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579962768,
      "name": "ns_to_timeval",
      "external": true,
      "loc": "kernel/time/time.c:479",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/itimer.c:itimer_get_remtime",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestamp",
        "net/core/sock.c:sock_get_timestamp",
        "net/compat.c:compat_sock_get_timestamp",
        "net/compat.c:compat_sock_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962768,
      "name": "ns_to_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct timeval ns_to_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009824,
      "name": "ns_to_timeval",
      "external": true,
      "loc": "kernel/time/time.c:417",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/itimer.c:itimer_get_remtime",
        "net/socket.c:__sock_recv_timestamp",
        "net/core/sock.c:sock_get_timestamp",
        "net/core/sock.c:sock_get_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009824,
      "name": "ns_to_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
struct timeval ns_to_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580053136,
      "name": "ns_to_timeval",
      "external": true,
      "loc": "kernel/time/time.c:485",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/itimer.c:itimer_get_remtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053136,
      "name": "ns_to_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct timeval ns_to_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580102192,
      "name": "ns_to_timeval",
      "external": true,
      "loc": "kernel/time/time.c:485",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/itimer.c:itimer_get_remtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580102192,
      "name": "ns_to_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct timeval ns_to_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491311416,
      "name": "ns_to_timeval",
      "external": true,
      "loc": "kernel/time/time.c:485",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/itimer.c:itimer_get_remtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491311416,
      "name": "ns_to_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct timeval ns_to_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225307708,
      "name": "ns_to_timeval",
      "external": true,
      "loc": "kernel/time/time.c:485",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:itimer_get_remtime",
        "fs/binfmt_elf_fdpic.c:fill_prstatus",
        "fs/binfmt_elf_fdpic.c:fill_prstatus",
        "fs/binfmt_elf_fdpic.c:fill_prstatus",
        "fs/binfmt_elf_fdpic.c:fill_prstatus",
        "fs/binfmt_elf_fdpic.c:fill_prstatus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225307708,
      "name": "ns_to_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct timeval ns_to_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284239040,
      "name": "ns_to_timeval",
      "external": true,
      "loc": "kernel/time/time.c:485",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/itimer.c:itimer_get_remtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284239040,
      "name": "ns_to_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct timeval ns_to_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271820914,
      "name": "ns_to_timeval",
      "external": true,
      "loc": "kernel/time/time.c:485",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:itimer_get_remtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271820914,
      "name": "ns_to_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct timeval ns_to_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071392,
      "name": "ns_to_timeval",
      "external": true,
      "loc": "kernel/time/time.c:485",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/itimer.c:itimer_get_remtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071392,
      "name": "ns_to_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct timeval ns_to_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580016208,
      "name": "ns_to_timeval",
      "external": true,
      "loc": "kernel/time/time.c:485",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/itimer.c:itimer_get_remtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016208,
      "name": "ns_to_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct timeval ns_to_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580062464,
      "name": "ns_to_timeval",
      "external": true,
      "loc": "kernel/time/time.c:485",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/itimer.c:itimer_get_remtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062464,
      "name": "ns_to_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct timeval ns_to_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580113232,
      "name": "ns_to_timeval",
      "external": true,
      "loc": "kernel/time/time.c:485",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/time/itimer.c:do_setitimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:set_cpu_itimer",
        "kernel/time/itimer.c:do_getitimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:get_cpu_itimer",
        "kernel/time/itimer.c:itimer_get_remtime",
        "kernel/time/itimer.c:itimer_get_remtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580113232,
      "name": "ns_to_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct timeval ns_to_timeval(const s64 nsec)
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
