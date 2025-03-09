# Function: <code>compat_ip_get_mcast_msfilter</code>

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
int compat_ip_get_mcast_msfilter(struct sock * sk, void * optval, int * optlen, int len)
```

```json
{
  "name": "compat_ip_get_mcast_msfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590025488,
      "name": "compat_ip_get_mcast_msfilter",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1482",
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
      "addr": 18446744071590025488,
      "name": "compat_ip_get_mcast_msfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int compat_ip_get_mcast_msfilter(struct sock * sk, void * optval, int * optlen, int len)
```

```json
{
  "name": "compat_ip_get_mcast_msfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589939936,
      "name": "compat_ip_get_mcast_msfilter",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1482",
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
      "addr": 18446744071589939936,
      "name": "compat_ip_get_mcast_msfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
int compat_ip_get_mcast_msfilter(struct sock * sk, void * optval, int * optlen, int len)
```

```json
{
  "name": "compat_ip_get_mcast_msfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590707008,
      "name": "compat_ip_get_mcast_msfilter",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1482",
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
      "addr": 18446744071590707008,
      "name": "compat_ip_get_mcast_msfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
int compat_ip_get_mcast_msfilter(struct sock * sk, void * optval, int * optlen, int len)
```

```json
{
  "name": "compat_ip_get_mcast_msfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592335808,
      "name": "compat_ip_get_mcast_msfilter",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1493",
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
      "addr": 18446744071592335808,
      "name": "compat_ip_get_mcast_msfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int compat_ip_get_mcast_msfilter(struct sock * sk, sockptr_t optval, sockptr_t optlen, int len)
```

```json
{
  "name": "compat_ip_get_mcast_msfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594176864,
      "name": "compat_ip_get_mcast_msfilter",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1495",
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
      "addr": 18446744071594176864,
      "name": "compat_ip_get_mcast_msfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int compat_ip_get_mcast_msfilter(struct sock * sk, sockptr_t optval, sockptr_t optlen, int len)
```

```json
{
  "name": "compat_ip_get_mcast_msfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594563936,
      "name": "compat_ip_get_mcast_msfilter",
      "external": false,
      "loc": "net/ipv4/ip_sockglue.c:1517",
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
      "addr": 18446744071594563936,
      "name": "compat_ip_get_mcast_msfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 790
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
int compat_ip_get_mcast_msfilter(struct sock * sk, sockptr_t optval, sockptr_t optlen, int len)
```

```json
{
  "name": "compat_ip_get_mcast_msfilter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595367232,
      "name": "compat_ip_get_mcast_msfilter",
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
      "addr": 18446744071595367232,
      "name": "compat_ip_get_mcast_msfilter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 790
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
int compat_ip_get_mcast_msfilter(struct sock * sk, void * optval, int * optlen, int len)
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
