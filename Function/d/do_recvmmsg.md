# Function: <code>do_recvmmsg</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587834512,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2343",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587834512,
      "name": "do_recvmmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 747
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
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588138352,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2554",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588138352,
      "name": "do_recvmmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
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
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588338288,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2634",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588338288,
      "name": "do_recvmmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589208048,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2668",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589208048,
      "name": "do_recvmmsg",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589207184,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2663",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589207184,
      "name": "do_recvmmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 735
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
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589100784,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2647",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589100784,
      "name": "do_recvmmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 739
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
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589818432,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2720",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589818432,
      "name": "do_recvmmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 739
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
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591338752,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2796",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591338752,
      "name": "do_recvmmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 835
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
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593094064,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2784",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593094064,
      "name": "do_recvmmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 835
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
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593546272,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2822",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593546272,
      "name": "do_recvmmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 835
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
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594318560,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2892",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__ia32_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/socket.c:__x64_sys_recvmmsg_time32",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__ia32_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg",
        "net/socket.c:__x64_sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594318560,
      "name": "do_recvmmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 835
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
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501840680,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2634",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501840680,
      "name": "do_recvmmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1132
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
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234617928,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2634",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234617928,
      "name": "do_recvmmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
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
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295239072,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2634",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295239072,
      "name": "do_recvmmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1104
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
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278178034,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2634",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278178034,
      "name": "do_recvmmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587945072,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2634",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587945072,
      "name": "do_recvmmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587658176,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2634",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587658176,
      "name": "do_recvmmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588276848,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2634",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588276848,
      "name": "do_recvmmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```

```json
{
  "name": "do_recvmmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588412144,
      "name": "do_recvmmsg",
      "external": false,
      "loc": "net/socket.c:2634",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg",
        "net/socket.c:__sys_recvmmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588412144,
      "name": "do_recvmmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr * mmsg, unsigned int vlen, unsigned int flags, struct timespec64 * timeout)
```
</details>
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
