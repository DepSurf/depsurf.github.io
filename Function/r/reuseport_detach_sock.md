# Function: <code>reuseport_detach_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586840304,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:144",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_destruct",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash",
        "net/ipv4/udp.c:udp_lib_unhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586840304,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587031232,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:143",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_destruct",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash",
        "net/ipv4/udp.c:udp_lib_unhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587031232,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587159392,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:143",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_destruct",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587159392,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587667872,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:155",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_destruct",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587667872,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587994752,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:155",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_destruct",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587994752,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588153888,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:192",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_destruct",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588153888,
      "name": "reuseport_detach_sock",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588475088,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:194",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_destruct",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588475088,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588680512,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:194",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_destruct",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588680512,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589546240,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:183",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_free",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589546240,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589555264,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:183",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_free",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589555264,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589453264,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:183",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_free",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589453264,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590190448,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:342",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_free",
        "net/core/sock_reuseport.c:reuseport_stop_listen_sock",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590190448,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591753552,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:342",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:__sk_free",
        "net/core/sock_reuseport.c:reuseport_stop_listen_sock",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591753552,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593544656,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:428",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_destruct",
        "net/core/sock_reuseport.c:reuseport_stop_listen_sock",
        "net/ipv4/udp.c:udp_lib_rehash",
        "net/ipv4/udp.c:udp_lib_unhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593544656,
      "name": "reuseport_detach_sock",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594013728,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:428",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_destruct",
        "net/core/sock_reuseport.c:reuseport_stop_listen_sock",
        "net/ipv4/udp.c:udp_lib_rehash",
        "net/ipv4/udp.c:udp_lib_unhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594013728,
      "name": "reuseport_detach_sock",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594800096,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:428",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_destruct",
        "net/core/sock_reuseport.c:reuseport_stop_listen_sock",
        "net/ipv4/udp.c:udp_lib_rehash",
        "net/ipv4/udp.c:udp_lib_unhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594800096,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502235448,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:194",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_destruct",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502235448,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234979940,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:194",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_destruct",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234979940,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295724736,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:194",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_destruct",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295724736,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278476840,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:194",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_destruct",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278476840,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588287248,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:194",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_destruct",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588287248,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588000064,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:194",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_destruct",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588000064,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588619072,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:194",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_destruct",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588619072,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void reuseport_detach_sock(struct sock * sk)
```

```json
{
  "name": "reuseport_detach_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588756864,
      "name": "reuseport_detach_sock",
      "external": true,
      "loc": "net/core/sock_reuseport.c:194",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_destruct",
        "net/ipv4/inet_hashtables.c:inet_unhash",
        "net/ipv4/udp.c:udp_lib_rehash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588756864,
      "name": "reuseport_detach_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void reuseport_detach_sock(struct sock * sk)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
