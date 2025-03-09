# Function: <code>inet_twsk_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586592448,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:77",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586592448,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587036016,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:77",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036016,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587232096,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:77",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587232096,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587363712,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:77",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587363712,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587883776,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:76",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_time_wait",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587883776,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588230480,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:76",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588230480,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588417648,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:76",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588417648,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588821568,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:77",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588821568,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589044784,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:77",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589044784,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590005968,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:77",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590005968,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590048560,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:77",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590048560,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589963328,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:77",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589963328,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590730416,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:77",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590730416,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592360525,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:79",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge"
      ],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592359728,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594205104,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:87",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594205104,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594592096,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:84",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594592096,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595395680,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:82",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595395680,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502656128,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:77",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502656128,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235359540,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:77",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235359540,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296258608,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:77",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296258608,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278796558,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:77",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278795876,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588651168,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:77",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588651168,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588363152,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:77",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588363152,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589087344,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:77",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589087344,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void inet_twsk_put(struct inet_timewait_sock * tw)
```

```json
{
  "name": "inet_twsk_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589126896,
      "name": "inet_twsk_put",
      "external": true,
      "loc": "net/ipv4/inet_timewait_sock.c:77",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_minisocks.c:tcp_timewait_state_process",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589126896,
      "name": "inet_twsk_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
