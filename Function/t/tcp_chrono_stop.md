# Function: <code>tcp_chrono_stop</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587311680,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2139",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587311680,
      "name": "tcp_chrono_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587443312,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2226",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587443312,
      "name": "tcp_chrono_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587964320,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2277",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587964320,
      "name": "tcp_chrono_stop",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588313760,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2260",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588313760,
      "name": "tcp_chrono_stop",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588502832,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2286",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588502832,
      "name": "tcp_chrono_stop",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588913344,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2314",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588913344,
      "name": "tcp_chrono_stop",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589137104,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2333",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589137104,
      "name": "tcp_chrono_stop",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590108336,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2396",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590108336,
      "name": "tcp_chrono_stop",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590155664,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2566",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590155664,
      "name": "tcp_chrono_stop",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590069312,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2567",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590069312,
      "name": "tcp_chrono_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590843200,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2567",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590843200,
      "name": "tcp_chrono_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592478768,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2567",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_remove_empty_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592478768,
      "name": "tcp_chrono_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594334560,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2569",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_remove_empty_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594334560,
      "name": "tcp_chrono_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594721088,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2611",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_remove_empty_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594721088,
      "name": "tcp_chrono_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595525968,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2668",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_remove_empty_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595525968,
      "name": "tcp_chrono_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502753080,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2333",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502753080,
      "name": "tcp_chrono_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235457320,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2333",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235457320,
      "name": "tcp_chrono_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296380864,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2333",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296380864,
      "name": "tcp_chrono_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278876850,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2333",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278876850,
      "name": "tcp_chrono_stop",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588743488,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2333",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588743488,
      "name": "tcp_chrono_stop",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588455440,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2333",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588455440,
      "name": "tcp_chrono_stop",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589179664,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2333",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589179664,
      "name": "tcp_chrono_stop",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```

```json
{
  "name": "tcp_chrono_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589219728,
      "name": "tcp_chrono_stop",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2333",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589219728,
      "name": "tcp_chrono_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void tcp_chrono_stop(struct sock * sk, const enum tcp_chrono type)
```
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
