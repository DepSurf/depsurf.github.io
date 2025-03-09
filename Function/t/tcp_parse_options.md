# Function: <code>tcp_parse_options</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tcp_parse_options(const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586629328,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3697",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586629328,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1020
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
void tcp_parse_options(const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587077216,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3755",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587077216,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1016
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
void tcp_parse_options(const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587267200,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3771",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587267200,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
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
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587399248,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3727",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587399248,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 795
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
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587920496,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3691",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587920496,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 875
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3775",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588307206,
      "name": "tcp_parse_options.cold.77",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071588269200,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 773
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3774",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588496040,
      "name": "tcp_parse_options.cold.83",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071588457984,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 773
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3789",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588904772,
      "name": "tcp_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071588864144,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 797
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3839",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589128894,
      "name": "tcp_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071589088448,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 797
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3833",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590096020,
      "name": "tcp_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071590052560,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3962",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591634540,
      "name": "tcp_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071590097760,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 831
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3969",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591577916,
      "name": "tcp_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071590011664,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4003",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592716176,
      "name": "tcp_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071590782720,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4021",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594602406,
      "name": "tcp_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071592414608,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594269200,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4035",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594269200,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 905
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
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594655296,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4040",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594655296,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 886
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
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595459360,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4118",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595459360,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 886
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
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502703624,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3839",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502703624,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 844
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
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235405364,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3839",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235405364,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1036
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
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296318304,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3839",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296318304,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1284
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
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278834400,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3839",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278834400,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 912
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3839",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588735278,
      "name": "tcp_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071588694832,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 797
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3839",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588447262,
      "name": "tcp_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071588406816,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 797
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3839",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589171454,
      "name": "tcp_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071589131008,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 797
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void tcp_parse_options(const struct net * net, const struct sk_buff * skb, struct tcp_options_received * opt_rx, int estab, struct tcp_fastopen_cookie * foc)
```

```json
{
  "name": "tcp_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_parse_options",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3839",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv6/syncookies.c:cookie_v6_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589211497,
      "name": "tcp_parse_options.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071589170832,
      "name": "tcp_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 797
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct net * net</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, opt_rx, estab, foc</code> ➡️ <code>net, skb, opt_rx, estab, foc</code>
</li>
</ul>
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
