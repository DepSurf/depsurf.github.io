# Function: <code>inet_csk_bind_conflict</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586593344,
      "name": "inet_csk_bind_conflict",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:46",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586593344,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587036944,
      "name": "inet_csk_bind_conflict",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:47",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036944,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587233024,
      "name": "inet_csk_bind_conflict",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:47",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587233024,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587367184,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:128",
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
      "addr": 18446744071587367184,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587887216,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:128",
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
      "addr": 18446744071587887216,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588234048,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:123",
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
      "addr": 18446744071588234048,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588421200,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:132",
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
      "addr": 18446744071588421200,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588825152,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:128",
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
      "addr": 18446744071588825152,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589048304,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:128",
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
      "addr": 18446744071589048304,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590010048,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:133",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_find_open_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590010048,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590052608,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:133",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_find_open_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590052608,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589967072,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:133",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_find_open_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589967072,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590734160,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:133",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_find_open_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590734160,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592363936,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:133",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592363936,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, const struct inet_bind2_bucket * tb2, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594210000,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:214",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594210000,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, const struct inet_bind2_bucket * tb2, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594596976,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:235",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594596976,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, const struct inet_bind2_bucket * tb2, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595402096,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:235",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595402096,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502660456,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:128",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502660456,
      "name": "inet_csk_bind_conflict.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235363452,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:128",
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
      "addr": 3235363452,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296263920,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:128",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296263920,
      "name": "inet_csk_bind_conflict.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278799744,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:128",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port",
        "net/ipv4/inet_connection_sock.c:inet_csk_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278799744,
      "name": "inet_csk_bind_conflict.isra.0",
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588654688,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:128",
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
      "addr": 18446744071588654688,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588366672,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:128",
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
      "addr": 18446744071588366672,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589090864,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:128",
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
      "addr": 18446744071589090864,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```

```json
{
  "name": "inet_csk_bind_conflict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589130512,
      "name": "inet_csk_bind_conflict",
      "external": false,
      "loc": "net/ipv4/inet_connection_sock.c:128",
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
      "addr": 18446744071589130512,
      "name": "inet_csk_bind_conflict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool reuseport_ok</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct inet_bind2_bucket * tb2</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, tb, relax, reuseport_ok</code> ➡️ <code>sk, tb, tb2, relax, reuseport_ok</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int inet_csk_bind_conflict(const struct sock * sk, const struct inet_bind_bucket * tb, bool relax, bool reuseport_ok)
```
</details>
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
