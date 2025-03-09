# Function: <code>sk_psock_drop</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588181136,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:574",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_unref",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588181136,
      "name": "sk_psock_drop",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588507152,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:586",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_unref",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588507152,
      "name": "sk_psock_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588715744,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:595",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_unref",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588715744,
      "name": "sk_psock_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589582832,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:596",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_link_no_progs",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589582832,
      "name": "sk_psock_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589594064,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:681",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_link_no_progs",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589594064,
      "name": "sk_psock_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589654256,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:820",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_close",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_unref",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/udp_bpf.c:udp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589654256,
      "name": "sk_psock_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590410848,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:815",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_close",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_unref",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/udp_bpf.c:udp_bpf_recvmsg",
        "net/unix/unix_bpf.c:unix_bpf_recvmsg",
        "net/unix/unix_bpf.c:unix_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590410848,
      "name": "sk_psock_drop",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592007696,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:835",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_close",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_unref",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/udp_bpf.c:udp_bpf_recvmsg",
        "net/unix/unix_bpf.c:unix_bpf_recvmsg",
        "net/unix/unix_bpf.c:unix_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592007696,
      "name": "sk_psock_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593821840,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:839",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_close",
        "net/core/sock_map.c:sock_map_destroy",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_unref",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/udp_bpf.c:udp_bpf_recvmsg",
        "net/unix/unix_bpf.c:unix_bpf_recvmsg",
        "net/unix/unix_bpf.c:unix_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593821840,
      "name": "sk_psock_drop",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594196256,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:829",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_close",
        "net/core/sock_map.c:sock_map_destroy",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_unref",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594196256,
      "name": "sk_psock_drop",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594993184,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:835",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_close",
        "net/core/sock_map.c:sock_map_destroy",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_unref",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594993184,
      "name": "sk_psock_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502279944,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:595",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_unref",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502279944,
      "name": "sk_psock_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235020036,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:595",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_unref",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235020036,
      "name": "sk_psock_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295779376,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:595",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_unref",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295779376,
      "name": "sk_psock_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278512688,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:595",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_unref",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278512688,
      "name": "sk_psock_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588322480,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:595",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_unref",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588322480,
      "name": "sk_psock_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588035264,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:595",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_unref",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588035264,
      "name": "sk_psock_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588654304,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:595",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_unref",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588654304,
      "name": "sk_psock_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```

```json
{
  "name": "sk_psock_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588794112,
      "name": "sk_psock_drop",
      "external": true,
      "loc": "net/core/skmsg.c:595",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_unref",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588794112,
      "name": "sk_psock_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void sk_psock_drop(struct sock * sk, struct sk_psock * psock)
```
</details>
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
