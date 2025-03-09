# Function: <code>apparmor_secmark_check</code>

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
int apparmor_secmark_check(struct aa_label * label, char * op, u32 request, u32 secid, struct sock * sk)
```

```json
{
  "name": "apparmor_secmark_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584150752,
      "name": "apparmor_secmark_check",
      "external": true,
      "loc": "security/apparmor/net.c:312",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inet_conn_request",
        "security/apparmor/lsm.c:apparmor_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584150752,
      "name": "apparmor_secmark_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
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
int apparmor_secmark_check(struct aa_label * label, char * op, u32 request, u32 secid, const struct sock * sk)
```

```json
{
  "name": "apparmor_secmark_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584269088,
      "name": "apparmor_secmark_check",
      "external": true,
      "loc": "security/apparmor/net.c:314",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inet_conn_request",
        "security/apparmor/lsm.c:apparmor_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584269088,
      "name": "apparmor_secmark_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
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
int apparmor_secmark_check(struct aa_label * label, char * op, u32 request, u32 secid, const struct sock * sk)
```

```json
{
  "name": "apparmor_secmark_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584294336,
      "name": "apparmor_secmark_check",
      "external": true,
      "loc": "security/apparmor/net.c:314",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inet_conn_request",
        "security/apparmor/lsm.c:apparmor_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584294336,
      "name": "apparmor_secmark_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 794
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
int apparmor_secmark_check(struct aa_label * label, char * op, u32 request, u32 secid, const struct sock * sk)
```

```json
{
  "name": "apparmor_secmark_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584680768,
      "name": "apparmor_secmark_check",
      "external": true,
      "loc": "security/apparmor/net.c:314",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_inet_conn_request",
        "security/apparmor/lsm.c:apparmor_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584680768,
      "name": "apparmor_secmark_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 794
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
int apparmor_secmark_check(struct aa_label * label, char * op, u32 request, u32 secid, const struct sock * sk)
```

```json
{
  "name": "apparmor_secmark_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585340672,
      "name": "apparmor_secmark_check",
      "external": true,
      "loc": "security/apparmor/net.c:317",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_ip_postroute",
        "security/apparmor/lsm.c:apparmor_inet_conn_request",
        "security/apparmor/lsm.c:apparmor_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585340672,
      "name": "apparmor_secmark_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 879
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
int apparmor_secmark_check(struct aa_label * label, char * op, u32 request, u32 secid, const struct sock * sk)
```

```json
{
  "name": "apparmor_secmark_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586081440,
      "name": "apparmor_secmark_check",
      "external": true,
      "loc": "security/apparmor/net.c:323",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_ip_postroute",
        "security/apparmor/lsm.c:apparmor_inet_conn_request",
        "security/apparmor/lsm.c:apparmor_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586081440,
      "name": "apparmor_secmark_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 849
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
int apparmor_secmark_check(struct aa_label * label, char * op, u32 request, u32 secid, const struct sock * sk)
```

```json
{
  "name": "apparmor_secmark_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586316800,
      "name": "apparmor_secmark_check",
      "external": true,
      "loc": "security/apparmor/net.c:323",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_ip_postroute",
        "security/apparmor/lsm.c:apparmor_inet_conn_request",
        "security/apparmor/lsm.c:apparmor_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586316800,
      "name": "apparmor_secmark_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 826
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
int apparmor_secmark_check(struct aa_label * label, char * op, u32 request, u32 secid, const struct sock * sk)
```

```json
{
  "name": "apparmor_secmark_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586573440,
      "name": "apparmor_secmark_check",
      "external": true,
      "loc": "security/apparmor/net.c:326",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_ip_postroute",
        "security/apparmor/lsm.c:apparmor_inet_conn_request",
        "security/apparmor/lsm.c:apparmor_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586573440,
      "name": "apparmor_secmark_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 826
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
int apparmor_secmark_check(struct aa_label * label, char * op, u32 request, u32 secid, struct sock * sk)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sock * sk</code> ➡️ <code>const struct sock * sk</code>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
