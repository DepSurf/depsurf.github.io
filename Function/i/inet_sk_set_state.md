# Function: <code>inet_sk_set_state</code>

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
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588456256,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1278",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456256,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588650704,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1278",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588650704,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589064224,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1284",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589064224,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589288544,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1284",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589288544,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590264400,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1316",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590264400,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590317440,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1314",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590317440,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590233408,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1318",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590233408,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591016320,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1320",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591016320,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592662496,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1315",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592662496,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594529952,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1335",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594529952,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594922112,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1334",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594922112,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595733744,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1354",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595733744,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502919712,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1284",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502919712,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235611516,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1284",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235611516,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296589712,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1284",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296589712,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279011828,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1284",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279011828,
      "name": "inet_sk_set_state",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588894720,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1284",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588894720,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588606656,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1284",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588606656,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589331104,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1284",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589331104,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void inet_sk_set_state(struct sock * sk, int state)
```

```json
{
  "name": "inet_sk_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589372128,
      "name": "inet_sk_set_state",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1284",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372128,
      "name": "inet_sk_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void inet_sk_set_state(struct sock * sk, int state)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
