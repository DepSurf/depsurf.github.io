# Function: <code>inet_csk_update_fastreuse</code>

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
void inet_csk_update_fastreuse(struct inet_bind_bucket * tb, struct sock * sk)
```

```json
{
  "name": "inet_csk_update_fastreuse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590015392,
      "name": "inet_csk_update_fastreuse",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:299",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590015392,
      "name": "inet_csk_update_fastreuse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
void inet_csk_update_fastreuse(struct inet_bind_bucket * tb, struct sock * sk)
```

```json
{
  "name": "inet_csk_update_fastreuse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590058032,
      "name": "inet_csk_update_fastreuse",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:299",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590058032,
      "name": "inet_csk_update_fastreuse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
void inet_csk_update_fastreuse(struct inet_bind_bucket * tb, struct sock * sk)
```

```json
{
  "name": "inet_csk_update_fastreuse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589972640,
      "name": "inet_csk_update_fastreuse",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:299",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589972640,
      "name": "inet_csk_update_fastreuse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
void inet_csk_update_fastreuse(struct inet_bind_bucket * tb, struct sock * sk)
```

```json
{
  "name": "inet_csk_update_fastreuse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_csk_update_fastreuse",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:307",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592714916,
      "name": "inet_csk_update_fastreuse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071590741968,
      "name": "inet_csk_update_fastreuse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
void inet_csk_update_fastreuse(struct inet_bind_bucket * tb, struct sock * sk)
```

```json
{
  "name": "inet_csk_update_fastreuse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_csk_update_fastreuse",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:311",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594601007,
      "name": "inet_csk_update_fastreuse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071592372656,
      "name": "inet_csk_update_fastreuse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
void inet_csk_update_fastreuse(struct inet_bind_bucket * tb, struct sock * sk)
```

```json
{
  "name": "inet_csk_update_fastreuse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_csk_update_fastreuse",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:431",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596336741,
      "name": "inet_csk_update_fastreuse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071594220576,
      "name": "inet_csk_update_fastreuse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
void inet_csk_update_fastreuse(struct inet_bind_bucket * tb, struct sock * sk)
```

```json
{
  "name": "inet_csk_update_fastreuse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_csk_update_fastreuse",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:452",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596866347,
      "name": "inet_csk_update_fastreuse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071594607744,
      "name": "inet_csk_update_fastreuse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
void inet_csk_update_fastreuse(struct inet_bind_bucket * tb, struct sock * sk)
```

```json
{
  "name": "inet_csk_update_fastreuse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "inet_csk_update_fastreuse",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:450",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_inherit_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597791422,
      "name": "inet_csk_update_fastreuse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071595411424,
      "name": "inet_csk_update_fastreuse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
void inet_csk_update_fastreuse(struct inet_bind_bucket * tb, struct sock * sk)
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
