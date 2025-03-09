# Function: <code>get_user_ifreq</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int get_user_ifreq(struct ifreq * ifr, void * * ifrdata, void * arg)
```

```json
{
  "name": "get_user_ifreq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589808752,
      "name": "get_user_ifreq",
      "external": true,
      "loc": "net/socket.c:3158",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_do_ioctl",
        "net/ipv4/af_inet.c:inet_ioctl",
        "net/ipv4/af_inet.c:inet_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589808752,
      "name": "get_user_ifreq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int get_user_ifreq(struct ifreq * ifr, void * * ifrdata, void * arg)
```

```json
{
  "name": "get_user_ifreq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591320896,
      "name": "get_user_ifreq",
      "external": true,
      "loc": "net/socket.c:3234",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_do_ioctl",
        "net/ipv4/af_inet.c:inet_ioctl",
        "net/ipv4/af_inet.c:inet_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591320896,
      "name": "get_user_ifreq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int get_user_ifreq(struct ifreq * ifr, void * * ifrdata, void * arg)
```

```json
{
  "name": "get_user_ifreq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593074496,
      "name": "get_user_ifreq",
      "external": true,
      "loc": "net/socket.c:3222",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_do_ioctl",
        "net/ipv4/af_inet.c:inet_ioctl",
        "net/ipv4/af_inet.c:inet_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593074496,
      "name": "get_user_ifreq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int get_user_ifreq(struct ifreq * ifr, void * * ifrdata, void * arg)
```

```json
{
  "name": "get_user_ifreq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593526000,
      "name": "get_user_ifreq",
      "external": true,
      "loc": "net/socket.c:3260",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_do_ioctl",
        "net/ipv4/af_inet.c:inet_ioctl",
        "net/ipv4/af_inet.c:inet_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593526000,
      "name": "get_user_ifreq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int get_user_ifreq(struct ifreq * ifr, void * * ifrdata, void * arg)
```

```json
{
  "name": "get_user_ifreq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594297424,
      "name": "get_user_ifreq",
      "external": true,
      "loc": "net/socket.c:3330",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:compat_sock_ioctl_trans",
        "net/socket.c:sock_ioctl",
        "net/socket.c:sock_do_ioctl",
        "net/ipv4/af_inet.c:inet_ioctl",
        "net/ipv4/af_inet.c:inet_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594297424,
      "name": "get_user_ifreq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int get_user_ifreq(struct ifreq * ifr, void * * ifrdata, void * arg)
```
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
