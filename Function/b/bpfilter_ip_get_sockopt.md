# Function: <code>bpfilter_ip_get_sockopt</code>

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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588531056,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:34",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588531056,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588727216,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:60",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588727216,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589159248,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:58",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589159248,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589383232,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:58",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589383232,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590369776,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:58",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590369776,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590427216,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:60",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590427216,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590352560,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:60",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590352560,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591141888,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:60",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591141888,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592796688,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:60",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592796688,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594670992,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:60",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594670992,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595063280,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:51",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595063280,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503026488,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:58",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503026488,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235715800,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:58",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235715800,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296724592,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:58",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296724592,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279096678,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:58",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279096678,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588989408,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:58",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588989408,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588701344,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:58",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588701344,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589425792,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:58",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589425792,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
```

```json
{
  "name": "bpfilter_ip_get_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589469360,
      "name": "bpfilter_ip_get_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:58",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:compat_ip_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589469360,
      "name": "bpfilter_ip_get_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int bpfilter_ip_get_sockopt(struct sock * sk, int optname, char * optval, int * optlen)
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
