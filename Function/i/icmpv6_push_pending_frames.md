# Function: <code>icmpv6_push_pending_frames</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587132960,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:239",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587132960,
      "name": "icmpv6_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587584544,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:239",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587584544,
      "name": "icmpv6_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587788768,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:240",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587788768,
      "name": "icmpv6_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587945904,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:253",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587945904,
      "name": "icmpv6_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588481584,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:253",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588481584,
      "name": "icmpv6_push_pending_frames",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588845152,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:253",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588845152,
      "name": "icmpv6_push_pending_frames",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589068688,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:255",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589068688,
      "name": "icmpv6_push_pending_frames",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589522896,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:250",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589522896,
      "name": "icmpv6_push_pending_frames",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589746976,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:250",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589746976,
      "name": "icmpv6_push_pending_frames",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590765168,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:269",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590765168,
      "name": "icmpv6_push_pending_frames",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590824512,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:275",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590824512,
      "name": "icmpv6_push_pending_frames",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590751648,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:275",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590751648,
      "name": "icmpv6_push_pending_frames",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591568560,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:276",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591568560,
      "name": "icmpv6_push_pending_frames",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593259504,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:268",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593259504,
      "name": "icmpv6_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595161872,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:268",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595161872,
      "name": "icmpv6_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595557232,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:272",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595557232,
      "name": "icmpv6_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596399936,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:272",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596399936,
      "name": "icmpv6_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503441880,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:250",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503441880,
      "name": "icmpv6_push_pending_frames",
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
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236100176,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:250",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236100176,
      "name": "icmpv6_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297224576,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:250",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297224576,
      "name": "icmpv6_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279428360,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:250",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279428360,
      "name": "icmpv6_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589351344,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:250",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589351344,
      "name": "icmpv6_push_pending_frames",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589076336,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:250",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589076336,
      "name": "icmpv6_push_pending_frames",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589788208,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:250",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589788208,
      "name": "icmpv6_push_pending_frames",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock * sk, struct flowi6 * fl6, struct icmp6hdr * thdr, int len)
```

```json
{
  "name": "icmpv6_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589838944,
      "name": "icmpv6_push_pending_frames",
      "external": true,
      "loc": "net/ipv6/icmp.c:250",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589838944,
      "name": "icmpv6_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
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
