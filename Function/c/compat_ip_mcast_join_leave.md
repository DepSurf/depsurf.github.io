# Function: <code>compat_ip_mcast_join_leave</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int compat_ip_mcast_join_leave(struct sock * sk, int optname, sockptr_t optval, int optlen)
```

```json
{
  "name": "compat_ip_mcast_join_leave",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590027648,
      "name": "compat_ip_mcast_join_leave",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:866",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590027648,
      "name": "compat_ip_mcast_join_leave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
int compat_ip_mcast_join_leave(struct sock * sk, int optname, sockptr_t optval, int optlen)
```

```json
{
  "name": "compat_ip_mcast_join_leave",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589942080,
      "name": "compat_ip_mcast_join_leave",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:866",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589942080,
      "name": "compat_ip_mcast_join_leave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
int compat_ip_mcast_join_leave(struct sock * sk, int optname, sockptr_t optval, int optlen)
```

```json
{
  "name": "compat_ip_mcast_join_leave",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590708928,
      "name": "compat_ip_mcast_join_leave",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:866",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590708928,
      "name": "compat_ip_mcast_join_leave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
int compat_ip_mcast_join_leave(struct sock * sk, int optname, sockptr_t optval, int optlen)
```

```json
{
  "name": "compat_ip_mcast_join_leave",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592340576,
      "name": "compat_ip_mcast_join_leave",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:868",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592340576,
      "name": "compat_ip_mcast_join_leave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
int compat_ip_mcast_join_leave(struct sock * sk, int optname, sockptr_t optval, int optlen)
```

```json
{
  "name": "compat_ip_mcast_join_leave",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594175648,
      "name": "compat_ip_mcast_join_leave",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:869",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594175648,
      "name": "compat_ip_mcast_join_leave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
int compat_ip_mcast_join_leave(struct sock * sk, int optname, sockptr_t optval, int optlen)
```

```json
{
  "name": "compat_ip_mcast_join_leave",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594562720,
      "name": "compat_ip_mcast_join_leave",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:876",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594562720,
      "name": "compat_ip_mcast_join_leave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int compat_ip_mcast_join_leave(struct sock * sk, int optname, sockptr_t optval, int optlen)
```

```json
{
  "name": "compat_ip_mcast_join_leave",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595365360,
      "name": "compat_ip_mcast_join_leave",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:867",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595365360,
      "name": "compat_ip_mcast_join_leave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int compat_ip_mcast_join_leave(struct sock * sk, int optname, sockptr_t optval, int optlen)
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
