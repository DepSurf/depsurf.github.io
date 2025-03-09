# Function: <code>tcp_recvmsg_locked</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int tcp_recvmsg_locked(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, struct scm_timestamping_internal * tss, int * cmsg_flags)
```

```json
{
  "name": "tcp_recvmsg_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_recvmsg_locked",
      "external": false,
      "loc": "net/ipv4/tcp.c:2254",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:receive_fallback_to_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590076400,
      "name": "tcp_recvmsg_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2529
    },
    {
      "addr": 18446744071591634356,
      "name": "tcp_recvmsg_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int tcp_recvmsg_locked(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, struct scm_timestamping_internal * tss, int * cmsg_flags)
```

```json
{
  "name": "tcp_recvmsg_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_recvmsg_locked",
      "external": false,
      "loc": "net/ipv4/tcp.c:2297",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:receive_fallback_to_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589990864,
      "name": "tcp_recvmsg_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2500
    },
    {
      "addr": 18446744071591577759,
      "name": "tcp_recvmsg_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int tcp_recvmsg_locked(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, struct scm_timestamping_internal * tss, int * cmsg_flags)
```

```json
{
  "name": "tcp_recvmsg_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_recvmsg_locked",
      "external": false,
      "loc": "net/ipv4/tcp.c:2297",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:receive_fallback_to_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590760800,
      "name": "tcp_recvmsg_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2520
    },
    {
      "addr": 18446744071592715500,
      "name": "tcp_recvmsg_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
int tcp_recvmsg_locked(struct sock * sk, struct msghdr * msg, size_t len, int flags, struct scm_timestamping_internal * tss, int * cmsg_flags)
```

```json
{
  "name": "tcp_recvmsg_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_recvmsg_locked",
      "external": false,
      "loc": "net/ipv4/tcp.c:2324",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:receive_fallback_to_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592393584,
      "name": "tcp_recvmsg_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2385
    },
    {
      "addr": 18446744071594601765,
      "name": "tcp_recvmsg_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int tcp_recvmsg_locked(struct sock * sk, struct msghdr * msg, size_t len, int flags, struct scm_timestamping_internal * tss, int * cmsg_flags)
```

```json
{
  "name": "tcp_recvmsg_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_recvmsg_locked",
      "external": false,
      "loc": "net/ipv4/tcp.c:2424",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:receive_fallback_to_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594244656,
      "name": "tcp_recvmsg_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2447
    },
    {
      "addr": 18446744071596337338,
      "name": "tcp_recvmsg_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int tcp_recvmsg_locked(struct sock * sk, struct msghdr * msg, size_t len, int flags, struct scm_timestamping_internal * tss, int * cmsg_flags)
```

```json
{
  "name": "tcp_recvmsg_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_recvmsg_locked",
      "external": false,
      "loc": "net/ipv4/tcp.c:2310",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:receive_fallback_to_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594630784,
      "name": "tcp_recvmsg_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2457
    },
    {
      "addr": 18446744071596866897,
      "name": "tcp_recvmsg_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int tcp_recvmsg_locked(struct sock * sk, struct msghdr * msg, size_t len, int flags, struct scm_timestamping_internal * tss, int * cmsg_flags)
```

```json
{
  "name": "tcp_recvmsg_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_recvmsg_locked",
      "external": false,
      "loc": "net/ipv4/tcp.c:2317",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:receive_fallback_to_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595433872,
      "name": "tcp_recvmsg_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2521
    },
    {
      "addr": 18446744071597791805,
      "name": "tcp_recvmsg_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int tcp_recvmsg_locked(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, struct scm_timestamping_internal * tss, int * cmsg_flags)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nonblock</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, msg, len, nonblock, flags, tss, cmsg_flags</code> ➡️ <code>sk, msg, len, flags, tss, cmsg_flags</code>
</li>
</ul>
</details>
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
