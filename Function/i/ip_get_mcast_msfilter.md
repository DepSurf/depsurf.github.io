# Function: <code>ip_get_mcast_msfilter</code>

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
int ip_get_mcast_msfilter(struct sock * sk, void * optval, int * optlen, int len)
```

```json
{
  "name": "ip_get_mcast_msfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590026000,
      "name": "ip_get_mcast_msfilter",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1456",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590026000,
      "name": "ip_get_mcast_msfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int ip_get_mcast_msfilter(struct sock * sk, void * optval, int * optlen, int len)
```

```json
{
  "name": "ip_get_mcast_msfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589940448,
      "name": "ip_get_mcast_msfilter",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1456",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589940448,
      "name": "ip_get_mcast_msfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
int ip_get_mcast_msfilter(struct sock * sk, void * optval, int * optlen, int len)
```

```json
{
  "name": "ip_get_mcast_msfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590707520,
      "name": "ip_get_mcast_msfilter",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1456",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590707520,
      "name": "ip_get_mcast_msfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
int ip_get_mcast_msfilter(struct sock * sk, void * optval, int * optlen, int len)
```

```json
{
  "name": "ip_get_mcast_msfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592336416,
      "name": "ip_get_mcast_msfilter",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1467",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592336416,
      "name": "ip_get_mcast_msfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int ip_get_mcast_msfilter(struct sock * sk, sockptr_t optval, sockptr_t optlen, int len)
```

```json
{
  "name": "ip_get_mcast_msfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594176352,
      "name": "ip_get_mcast_msfilter",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1468",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594176352,
      "name": "ip_get_mcast_msfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
int ip_get_mcast_msfilter(struct sock * sk, sockptr_t optval, sockptr_t optlen, int len)
```

```json
{
  "name": "ip_get_mcast_msfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594563456,
      "name": "ip_get_mcast_msfilter",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1490",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594563456,
      "name": "ip_get_mcast_msfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
int ip_get_mcast_msfilter(struct sock * sk, sockptr_t optval, sockptr_t optlen, int len)
```

```json
{
  "name": "ip_get_mcast_msfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595366752,
      "name": "ip_get_mcast_msfilter",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1441",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595366752,
      "name": "ip_get_mcast_msfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
int ip_get_mcast_msfilter(struct sock * sk, void * optval, int * optlen, int len)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void * optval</code> ➡️ <code>sockptr_t optval</code>
</li>
<li>
<b>Param type changed. </b>
<code>int * optlen</code> ➡️ <code>sockptr_t optlen</code>
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
