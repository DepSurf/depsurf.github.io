# Function: <code>ns_to_kernel_old_timeval</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579962896,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:491",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962896,
      "name": "ns_to_kernel_old_timeval",
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009952,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:429",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009952,
      "name": "ns_to_kernel_old_timeval",
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580053264,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:497",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053264,
      "name": "ns_to_kernel_old_timeval",
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580102320,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:497",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580102320,
      "name": "ns_to_kernel_old_timeval",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580165168,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:452",
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
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165168,
      "name": "ns_to_kernel_old_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580149312,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:452",
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
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "fs/compat_binfmt_elf.c:fill_prstatus",
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149312,
      "name": "ns_to_kernel_old_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580154000,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:452",
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
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580154000,
      "name": "ns_to_kernel_old_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580298528,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:452",
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
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580298528,
      "name": "ns_to_kernel_old_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580507248,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:452",
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
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507248,
      "name": "ns_to_kernel_old_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580761040,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:452",
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
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761040,
      "name": "ns_to_kernel_old_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580843712,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:452",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580843712,
      "name": "ns_to_kernel_old_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580933104,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:470",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:getrusage",
        "kernel/sys.c:getrusage",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info",
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933104,
      "name": "ns_to_kernel_old_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491311568,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:497",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491311568,
      "name": "ns_to_kernel_old_timeval",
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225307860,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:497",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225307860,
      "name": "ns_to_kernel_old_timeval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284239200,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:497",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284239200,
      "name": "ns_to_kernel_old_timeval",
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271820990,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:497",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271820990,
      "name": "ns_to_kernel_old_timeval",
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071520,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:497",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071520,
      "name": "ns_to_kernel_old_timeval",
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580016336,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:497",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016336,
      "name": "ns_to_kernel_old_timeval",
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580062592,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:497",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062592,
      "name": "ns_to_kernel_old_timeval",
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
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec)
```

```json
{
  "name": "ns_to_kernel_old_timeval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580113360,
      "name": "ns_to_kernel_old_timeval",
      "external": true,
      "loc": "kernel/time/time.c:497",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sock_recv_timestamp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580113360,
      "name": "ns_to_kernel_old_timeval",
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
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct __kernel_old_timeval ns_to_kernel_old_timeval(const s64 nsec)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const s64 nsec</code> ➡️ <code>s64 nsec</code>
</li>
</ul>
</details>
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
