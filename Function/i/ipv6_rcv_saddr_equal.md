# Function: <code>ipv6_rcv_saddr_equal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ipv6_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587108752,
      "name": "ipv6_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv6/udp.c:79",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587108752,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int ipv6_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587704352,
      "name": "ipv6_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:282",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587704352,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int ipv6_rcv_saddr_equal(const struct sock * sk, const struct sock * sk2, bool match_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587918912,
      "name": "ipv6_rcv_saddr_equal",
      "external": true,
      "loc": "net/ipv6/inet6_hashtables.c:285",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict",
        "net/ipv6/inet6_connection_sock.c:inet6_csk_bind_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587918912,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587364528,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:42",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587364528,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587884704,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:42",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587884704,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588231456,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:37",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588231456,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588418624,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:37",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588418624,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588822448,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:33",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588822448,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589045600,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:33",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589045600,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_sk1_wildcard, bool match_sk2_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590006960,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:34",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590006960,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_sk1_wildcard, bool match_sk2_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590049472,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:34",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590049472,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_sk1_wildcard, bool match_sk2_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589964240,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:34",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589964240,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_sk1_wildcard, bool match_sk2_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590731328,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:34",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590731328,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_sk1_wildcard, bool match_sk2_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592360880,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:34",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592360880,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_sk1_wildcard, bool match_sk2_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594206704,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:34",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594206704,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_sk1_wildcard, bool match_sk2_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594593728,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:34",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594593728,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_sk1_wildcard, bool match_sk2_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595397328,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:34",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_update_fastreuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595397328,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502657592,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:33",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502657592,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235360412,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:33",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235360412,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296260016,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:33",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296260016,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278796898,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:33",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278796898,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588651984,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:33",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588651984,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588363968,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:33",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588363968,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589088160,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:33",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589088160,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
bool ipv6_rcv_saddr_equal(const struct in6_addr * sk1_rcv_saddr6, const struct in6_addr * sk2_rcv_saddr6, __be32 sk1_rcv_saddr, __be32 sk2_rcv_saddr, bool sk1_ipv6only, bool sk2_ipv6only, bool match_wildcard)
```

```json
{
  "name": "ipv6_rcv_saddr_equal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589127760,
      "name": "ipv6_rcv_saddr_equal",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:33",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589127760,
      "name": "ipv6_rcv_saddr_equal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool match_wildcard</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct in6_addr * sk1_rcv_saddr6</code>
</li>
<li>
<b>Param added. </b>
<code>const struct in6_addr * sk2_rcv_saddr6</code>
</li>
<li>
<b>Param added. </b>
<code>__be32 sk1_rcv_saddr</code>
</li>
<li>
<b>Param added. </b>
<code>__be32 sk2_rcv_saddr</code>
</li>
<li>
<b>Param added. </b>
<code>bool sk1_ipv6only</code>
</li>
<li>
<b>Param added. </b>
<code>bool sk2_ipv6only</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct sock * sk</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct sock * sk2</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, sk2, match_wildcard</code> ➡️ <code>sk1_rcv_saddr6, sk2_rcv_saddr6, sk1_rcv_saddr, sk2_rcv_saddr, sk1_ipv6only, sk2_ipv6only, match_wildcard</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool match_sk1_wildcard</code>
</li>
<li>
<b>Param added. </b>
<code>bool match_sk2_wildcard</code>
</li>
<li>
<b>Param removed. </b>
<code>bool match_wildcard</code>
</li>
</ul>
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
