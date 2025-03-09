# Function: <code>__ipv6_sock_ac_close</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __ipv6_sock_ac_close(struct sock * sk)
```

```json
{
  "name": "__ipv6_sock_ac_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590559360,
      "name": "__ipv6_sock_ac_close",
      "external": true,
      "loc": "net/ipv6/anycast.c:186",
      "file": "net/ipv6/anycast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590559360,
      "name": "__ipv6_sock_ac_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void __ipv6_sock_ac_close(struct sock * sk)
```

```json
{
  "name": "__ipv6_sock_ac_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590619296,
      "name": "__ipv6_sock_ac_close",
      "external": true,
      "loc": "net/ipv6/anycast.c:186",
      "file": "net/ipv6/anycast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590619296,
      "name": "__ipv6_sock_ac_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void __ipv6_sock_ac_close(struct sock * sk)
```

```json
{
  "name": "__ipv6_sock_ac_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590544768,
      "name": "__ipv6_sock_ac_close",
      "external": true,
      "loc": "net/ipv6/anycast.c:186",
      "file": "net/ipv6/anycast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590544768,
      "name": "__ipv6_sock_ac_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void __ipv6_sock_ac_close(struct sock * sk)
```

```json
{
  "name": "__ipv6_sock_ac_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ipv6_sock_ac_close",
      "external": true,
      "loc": "net/ipv6/anycast.c:186",
      "file": "net/ipv6/anycast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592735339,
      "name": "__ipv6_sock_ac_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071591355664,
      "name": "__ipv6_sock_ac_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void __ipv6_sock_ac_close(struct sock * sk)
```

```json
{
  "name": "__ipv6_sock_ac_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ipv6_sock_ac_close",
      "external": true,
      "loc": "net/ipv6/anycast.c:186",
      "file": "net/ipv6/anycast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594621868,
      "name": "__ipv6_sock_ac_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071593028208,
      "name": "__ipv6_sock_ac_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
void __ipv6_sock_ac_close(struct sock * sk)
```

```json
{
  "name": "__ipv6_sock_ac_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ipv6_sock_ac_close",
      "external": true,
      "loc": "net/ipv6/anycast.c:186",
      "file": "net/ipv6/anycast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596356524,
      "name": "__ipv6_sock_ac_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071594919424,
      "name": "__ipv6_sock_ac_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
void __ipv6_sock_ac_close(struct sock * sk)
```

```json
{
  "name": "__ipv6_sock_ac_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ipv6_sock_ac_close",
      "external": true,
      "loc": "net/ipv6/anycast.c:186",
      "file": "net/ipv6/anycast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596885331,
      "name": "__ipv6_sock_ac_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071595311136,
      "name": "__ipv6_sock_ac_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void __ipv6_sock_ac_close(struct sock * sk)
```

```json
{
  "name": "__ipv6_sock_ac_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ipv6_sock_ac_close",
      "external": true,
      "loc": "net/ipv6/anycast.c:186",
      "file": "net/ipv6/anycast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/anycast.c:ipv6_sock_ac_close",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597809948,
      "name": "__ipv6_sock_ac_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071596153040,
      "name": "__ipv6_sock_ac_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __ipv6_sock_ac_close(struct sock * sk)
```
</details>
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
