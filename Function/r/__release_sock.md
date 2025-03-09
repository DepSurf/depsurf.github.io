# Function: <code>__release_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586193968,
      "name": "__release_sock",
      "external": false,
      "loc": "net/core/sock.c:1993",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:release_sock"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586616336,
      "name": "__release_sock",
      "external": false,
      "loc": "net/core/sock.c:2050",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586616336,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586800416,
      "name": "__release_sock",
      "external": false,
      "loc": "net/core/sock.c:2048",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586800416,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586923776,
      "name": "__release_sock",
      "external": false,
      "loc": "net/core/sock.c:2207",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586923776,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587415888,
      "name": "__release_sock",
      "external": false,
      "loc": "net/core/sock.c:2245",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587415888,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587719360,
      "name": "__release_sock",
      "external": false,
      "loc": "net/core/sock.c:2326",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587719360,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587858256,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2268",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587858256,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588162816,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2411",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588162816,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588368096,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2426",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588368096,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589232640,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2534",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589232640,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589231728,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2526",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:__tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589231728,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589125184,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2549",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:__tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589125184,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589844000,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2672",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:__tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589844000,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591365248,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2835",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:__tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591365248,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593120000,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2914",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:__tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593120000,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593572688,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2975",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:__tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593572688,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594345280,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2956",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:__tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594345280,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501877960,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2426",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501877960,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234641868,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2426",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234641868,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295284896,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2426",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295284896,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278199754,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2426",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278199754,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587974880,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2426",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587974880,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587687984,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2426",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587687984,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588306656,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2426",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588306656,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void __release_sock(struct sock * sk)
```

```json
{
  "name": "__release_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588441872,
      "name": "__release_sock",
      "external": true,
      "loc": "net/core/sock.c:2426",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:release_sock",
        "net/core/sock.c:__sk_flush_backlog",
        "net/ipv4/tcp.c:tcp_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588441872,
      "name": "__release_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void __release_sock(struct sock * sk)
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
