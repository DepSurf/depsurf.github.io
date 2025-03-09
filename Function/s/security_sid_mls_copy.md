# Function: <code>security_sid_mls_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_sid_mls_copy(u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582358144,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2732",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect",
        "security/selinux/hooks.c:selinux_ip_postroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582358144,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 631
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
int security_sid_mls_copy(u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582579248,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2726",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582579248,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 631
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
int security_sid_mls_copy(u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582672464,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2726",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582672464,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 631
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
int security_sid_mls_copy(u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582765216,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2842",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582765216,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
int security_sid_mls_copy(u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582921232,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2852",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582921232,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
int security_sid_mls_copy(struct selinux_state * state, u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2977",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583124855,
      "name": "security_sid_mls_copy.cold.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071583119792,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int security_sid_mls_copy(struct selinux_state * state, u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2943",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583241010,
      "name": "security_sid_mls_copy.cold.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071583235808,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
int security_sid_mls_copy(struct selinux_state * state, u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2956",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583428063,
      "name": "security_sid_mls_copy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071583422576,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 621
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
int security_sid_mls_copy(struct selinux_state * state, u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2963",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583533969,
      "name": "security_sid_mls_copy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071583528480,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 621
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
int security_sid_mls_copy(struct selinux_state * state, u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:3002",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583883322,
      "name": "security_sid_mls_copy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071583877728,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
int security_sid_mls_copy(struct selinux_state * state, u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:3120",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591366804,
      "name": "security_sid_mls_copy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071583998544,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 611
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
int security_sid_mls_copy(struct selinux_state * state, u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:3198",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591309794,
      "name": "security_sid_mls_copy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071584026192,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 719
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
int security_sid_mls_copy(struct selinux_state * state, u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:3205",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592300934,
      "name": "security_sid_mls_copy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071584396336,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 759
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
int security_sid_mls_copy(struct selinux_state * state, u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:3207",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594082259,
      "name": "security_sid_mls_copy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071585022464,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 835
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
int security_sid_mls_copy(struct selinux_state * state, u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:3200",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596097118,
      "name": "security_sid_mls_copy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585740064,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 910
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
int security_sid_mls_copy(u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:3147",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596620303,
      "name": "security_sid_mls_copy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071585970736,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
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
int security_sid_mls_copy(u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:3156",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597525973,
      "name": "security_sid_mls_copy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071586219760,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
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
int security_sid_mls_copy(struct selinux_state * state, u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495297352,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2963",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495297352,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
int security_sid_mls_copy(struct selinux_state * state, u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228678248,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2963",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228678248,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
int security_sid_mls_copy(struct selinux_state * state, u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289284352,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2963",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289284352,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 928
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
int security_sid_mls_copy(struct selinux_state * state, u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274518138,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2963",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274518138,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 586
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
int security_sid_mls_copy(struct selinux_state * state, u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2963",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583502705,
      "name": "security_sid_mls_copy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071583497216,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 621
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
int security_sid_mls_copy(struct selinux_state * state, u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2963",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439761,
      "name": "security_sid_mls_copy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071583434272,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 621
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
int security_sid_mls_copy(struct selinux_state * state, u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2963",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583486481,
      "name": "security_sid_mls_copy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071583480992,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 621
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
int security_sid_mls_copy(struct selinux_state * state, u32 sid, u32 mls_sid, u32 * new_sid)
```

```json
{
  "name": "security_sid_mls_copy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_sid_mls_copy",
      "external": true,
      "loc": "security/selinux/ss/services.c:2963",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_unix_stream_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583582845,
      "name": "security_sid_mls_copy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071583577168,
      "name": "security_sid_mls_copy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_state * state</code>
</li>
<li>
<b>Param reordered. </b>
<code>sid, mls_sid, new_sid</code> ➡️ <code>state, sid, mls_sid, new_sid</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state * state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, sid, mls_sid, new_sid</code> ➡️ <code>sid, mls_sid, new_sid</code>
</li>
</ul>
</details>
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
