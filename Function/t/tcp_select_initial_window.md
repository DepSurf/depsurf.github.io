# Function: <code>tcp_select_initial_window</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tcp_select_initial_window(int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586661072,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:208",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586661072,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void tcp_select_initial_window(int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587107168,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:205",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587107168,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
void tcp_select_initial_window(int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587304832,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:205",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587304832,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
void tcp_select_initial_window(int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587436176,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:206",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587436176,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587957376,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:191",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587957376,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588307552,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:204",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588307552,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588497088,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:204",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588497088,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588905472,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:204",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588905472,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589129520,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:207",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589129520,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590096480,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:208",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590096480,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590142464,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:208",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590142464,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590056976,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:208",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590056976,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590831024,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:208",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590831024,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592467104,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:206",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592467104,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594321664,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:206",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594321664,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594708064,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:206",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594708064,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595512672,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:205",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595512672,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502744960,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:207",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502744960,
      "name": "tcp_select_initial_window",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235448792,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:207",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235448792,
      "name": "tcp_select_initial_window",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296370416,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:207",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296370416,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278869412,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:207",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278869412,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588735904,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:207",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588735904,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588447888,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:207",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588447888,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589172080,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:207",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589172080,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void tcp_select_initial_window(const struct sock * sk, int __space, __u32 mss, __u32 * rcv_wnd, __u32 * window_clamp, int wscale_ok, __u8 * rcv_wscale, __u32 init_rcv_wnd)
```

```json
{
  "name": "tcp_select_initial_window",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589212112,
      "name": "tcp_select_initial_window",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:207",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589212112,
      "name": "tcp_select_initial_window",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sock * sk</code>
</li>
<li>
<b>Param reordered. </b>
<code>__space, mss, rcv_wnd, window_clamp, wscale_ok, rcv_wscale, init_rcv_wnd</code> ➡️ <code>sk, __space, mss, rcv_wnd, window_clamp, wscale_ok, rcv_wscale, init_rcv_wnd</code>
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
