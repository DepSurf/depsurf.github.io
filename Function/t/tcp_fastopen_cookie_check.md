# Function: <code>tcp_fastopen_cookie_check</code>

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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587501024,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:331",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587501024,
      "name": "tcp_fastopen_cookie_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588023296,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:379",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588023296,
      "name": "tcp_fastopen_cookie_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588374320,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:379",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588374320,
      "name": "tcp_fastopen_cookie_check",
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588564688,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:379",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588564688,
      "name": "tcp_fastopen_cookie_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588975872,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:406",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588975872,
      "name": "tcp_fastopen_cookie_check",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589200288,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:406",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589200288,
      "name": "tcp_fastopen_cookie_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590172560,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:429",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590172560,
      "name": "tcp_fastopen_cookie_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590221776,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:429",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590221776,
      "name": "tcp_fastopen_cookie_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590136032,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:429",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590136032,
      "name": "tcp_fastopen_cookie_check",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590916144,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:417",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590916144,
      "name": "tcp_fastopen_cookie_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592556048,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:411",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592556048,
      "name": "tcp_fastopen_cookie_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594415536,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:412",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594415536,
      "name": "tcp_fastopen_cookie_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594804880,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:414",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594804880,
      "name": "tcp_fastopen_cookie_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595616080,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:414",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595616080,
      "name": "tcp_fastopen_cookie_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502820208,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:406",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502820208,
      "name": "tcp_fastopen_cookie_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235522028,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:406",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235522028,
      "name": "tcp_fastopen_cookie_check",
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296467776,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:406",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296467776,
      "name": "tcp_fastopen_cookie_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278934332,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:406",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278934332,
      "name": "tcp_fastopen_cookie_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588806672,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:406",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588806672,
      "name": "tcp_fastopen_cookie_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588518608,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:406",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588518608,
      "name": "tcp_fastopen_cookie_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589242848,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:406",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589242848,
      "name": "tcp_fastopen_cookie_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```

```json
{
  "name": "tcp_fastopen_cookie_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589283408,
      "name": "tcp_fastopen_cookie_check",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:406",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589283408,
      "name": "tcp_fastopen_cookie_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
bool tcp_fastopen_cookie_check(struct sock * sk, u16 * mss, struct tcp_fastopen_cookie * cookie)
```
</details>
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
