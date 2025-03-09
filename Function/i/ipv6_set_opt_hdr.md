# Function: <code>ipv6_set_opt_hdr</code>

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
int ipv6_set_opt_hdr(struct sock * sk, int optname, sockptr_t optval, int optlen)
```

```json
{
  "name": "ipv6_set_opt_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590772096,
      "name": "ipv6_set_opt_hdr",
      "external": false,
      "loc": "net/ipv6/ipv6_sockglue.c:318",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590772096,
      "name": "ipv6_set_opt_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 780
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
int ipv6_set_opt_hdr(struct sock * sk, int optname, sockptr_t optval, int optlen)
```

```json
{
  "name": "ipv6_set_opt_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590699104,
      "name": "ipv6_set_opt_hdr",
      "external": false,
      "loc": "net/ipv6/ipv6_sockglue.c:318",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590699104,
      "name": "ipv6_set_opt_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 774
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
int ipv6_set_opt_hdr(struct sock * sk, int optname, sockptr_t optval, int optlen)
```

```json
{
  "name": "ipv6_set_opt_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipv6_set_opt_hdr",
      "external": false,
      "loc": "net/ipv6/ipv6_sockglue.c:318",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591515024,
      "name": "ipv6_set_opt_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 783
    },
    {
      "addr": 18446744071592739834,
      "name": "ipv6_set_opt_hdr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int ipv6_set_opt_hdr(struct sock * sk, int optname, sockptr_t optval, int optlen)
```

```json
{
  "name": "ipv6_set_opt_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipv6_set_opt_hdr",
      "external": false,
      "loc": "net/ipv6/ipv6_sockglue.c:320",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593200528,
      "name": "ipv6_set_opt_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 796
    },
    {
      "addr": 18446744071594626423,
      "name": "ipv6_set_opt_hdr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int ipv6_set_opt_hdr(struct sock * sk, int optname, sockptr_t optval, int optlen)
```

```json
{
  "name": "ipv6_set_opt_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipv6_set_opt_hdr",
      "external": false,
      "loc": "net/ipv6/ipv6_sockglue.c:320",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595096912,
      "name": "ipv6_set_opt_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 859
    },
    {
      "addr": 18446744071596360389,
      "name": "ipv6_set_opt_hdr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
int ipv6_set_opt_hdr(struct sock * sk, int optname, sockptr_t optval, int optlen)
```

```json
{
  "name": "ipv6_set_opt_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipv6_set_opt_hdr",
      "external": false,
      "loc": "net/ipv6/ipv6_sockglue.c:320",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595490720,
      "name": "ipv6_set_opt_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 866
    },
    {
      "addr": 18446744071596889057,
      "name": "ipv6_set_opt_hdr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int ipv6_set_opt_hdr(struct sock * sk, int optname, sockptr_t optval, int optlen)
```

```json
{
  "name": "ipv6_set_opt_hdr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipv6_set_opt_hdr",
      "external": false,
      "loc": "net/ipv6/ipv6_sockglue.c:320",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596334048,
      "name": "ipv6_set_opt_hdr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 866
    },
    {
      "addr": 18446744071597813426,
      "name": "ipv6_set_opt_hdr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int ipv6_set_opt_hdr(struct sock * sk, int optname, sockptr_t optval, int optlen)
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
