# Function: <code>inet_rcv_saddr_equal</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587367056,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:97",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587367056,
      "name": "inet_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587887088,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:97",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587887088,
      "name": "inet_rcv_saddr_equal",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588233920,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:92",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588233920,
      "name": "inet_rcv_saddr_equal",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588421072,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:92",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588421072,
      "name": "inet_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588825008,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:88",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588825008,
      "name": "inet_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589048160,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:88",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589048160,
      "name": "inet_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590009904,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:91",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_reuseport_add_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_reuseport_add_sock",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590009904,
      "name": "inet_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590052464,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:91",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:inet_reuseport_add_sock",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_reuseport_add_sock",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590052464,
      "name": "inet_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589966928,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:91",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589966928,
      "name": "inet_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590734016,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:91",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590734016,
      "name": "inet_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592363728,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:91",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592363728,
      "name": "inet_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594209776,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:91",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594209776,
      "name": "inet_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594596752,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:91",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594596752,
      "name": "inet_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595400304,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:91",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595400304,
      "name": "inet_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502660272,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:88",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502660272,
      "name": "inet_rcv_saddr_equal",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235363288,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:88",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235363288,
      "name": "inet_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296263728,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:88",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296263728,
      "name": "inet_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278799588,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:88",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278799588,
      "name": "inet_rcv_saddr_equal",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588654544,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:88",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588654544,
      "name": "inet_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588366528,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:88",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588366528,
      "name": "inet_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589090720,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:88",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589090720,
      "name": "inet_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "inet_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589130368,
      "name": "inet_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:88",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_hashtables.c:__inet_hash",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/inet_connection_sock.c:inet_csk_bind_conflict",
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_lport_inuse2",
        "net/ipv4/udp.c:udp_lib_lport_inuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589130368,
      "name": "inet_rcv_saddr_equal",
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int inet_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
