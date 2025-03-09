# Function: <code>compat_ifreq_ioctl</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_ifreq_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587831143,
      "name": "compat_ifreq_ioctl",
      "external": false,
      "loc": "net/socket.c:2994",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_ifreq_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588134079,
      "name": "compat_ifreq_ioctl",
      "external": false,
      "loc": "net/socket.c:3173",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_ifreq_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588341785,
      "name": "compat_ifreq_ioctl",
      "external": false,
      "loc": "net/socket.c:3253",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_ifreq_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589201101,
      "name": "compat_ifreq_ioctl",
      "external": false,
      "loc": "net/socket.c:3287",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl_trans"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int compat_ifreq_ioctl(struct net * net, struct socket * sock, unsigned int cmd, struct compat_ifreq * uifr32)
```

```json
{
  "name": "compat_ifreq_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589189776,
      "name": "compat_ifreq_ioctl",
      "external": false,
      "loc": "net/socket.c:3281",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:compat_sock_ioctl_trans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589189776,
      "name": "compat_ifreq_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_ifreq_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589091986,
      "name": "compat_ifreq_ioctl",
      "external": false,
      "loc": "net/socket.c:3267",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl_trans"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "compat_ifreq_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501850072,
      "name": "compat_ifreq_ioctl",
      "external": false,
      "loc": "net/socket.c:3253",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "compat_ifreq_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295251052,
      "name": "compat_ifreq_ioctl",
      "external": false,
      "loc": "net/socket.c:3253",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_ifreq_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587948569,
      "name": "compat_ifreq_ioctl",
      "external": false,
      "loc": "net/socket.c:3253",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_ifreq_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587661673,
      "name": "compat_ifreq_ioctl",
      "external": false,
      "loc": "net/socket.c:3253",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_ifreq_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588280345,
      "name": "compat_ifreq_ioctl",
      "external": false,
      "loc": "net/socket.c:3253",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_ifreq_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588415497,
      "name": "compat_ifreq_ioctl",
      "external": false,
      "loc": "net/socket.c:3253",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:compat_sock_ioctl"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int compat_ifreq_ioctl(struct net * net, struct socket * sock, unsigned int cmd, struct compat_ifreq * uifr32)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int compat_ifreq_ioctl(struct net * net, struct socket * sock, unsigned int cmd, struct compat_ifreq * uifr32)
```
</details>
</li>
</ul>
