# Function: <code>bpfilter_ip_set_sockopt</code>

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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588531024,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:28",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588531024,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588727184,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:54",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588727184,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589159216,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:52",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589159216,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589383200,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:52",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589383200,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590369744,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:52",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590369744,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590427184,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:54",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590427184,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590352528,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:54",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590352528,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591141856,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:54",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591141856,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592796640,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:54",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592796640,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594670928,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:54",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594670928,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595063216,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:45",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_sockglue.c:ip_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595063216,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503026408,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:52",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503026408,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235715756,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:52",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235715756,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296724560,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:52",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296724560,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279096610,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:52",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279096610,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588989376,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:52",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588989376,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588701312,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:52",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588701312,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589425760,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:52",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589425760,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "bpfilter_ip_set_sockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589469328,
      "name": "bpfilter_ip_set_sockopt",
      "external": true,
      "loc": "net/ipv4/bpfilter/sockopt.c:52",
      "file": "net/ipv4/bpfilter/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589469328,
      "name": "bpfilter_ip_set_sockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, char * optval, unsigned int optlen)
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * optval</code> ➡️ <code>sockptr_t optval</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int bpfilter_ip_set_sockopt(struct sock * sk, int optname, sockptr_t optval, unsigned int optlen)
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
