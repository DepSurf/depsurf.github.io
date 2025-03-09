# Function: <code>tcp_write_xmit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586670368,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2020",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586670368,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3790
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587116672,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2039",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587116672,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3970
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587315024,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2171",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587315024,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3950
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587446672,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2258",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587446672,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3790
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587967888,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2309",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587967888,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3898
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588317472,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2292",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588317472,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4001
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588506464,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2318",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588506464,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4097
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588921712,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2346",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588921712,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2943
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589145616,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2365",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589145616,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2961
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590115280,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2428",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590115280,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1845
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590163008,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2598",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590163008,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1840
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590077040,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2599",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590077040,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2409
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2599",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590851264,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2821
    },
    {
      "addr": 18446744071592719071,
      "name": "tcp_write_xmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2599",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592487536,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2703
    },
    {
      "addr": 18446744071594605570,
      "name": "tcp_write_xmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594343344,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2601",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594343344,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2135
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594730624,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2643",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594730624,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2736
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595535968,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2700",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595535968,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2744
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502761440,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2365",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502761440,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2764
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235465736,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2365",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235465736,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3056
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296391504,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2365",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296391504,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3608
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278884364,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2365",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278884364,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2356
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588752000,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2365",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588752000,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2961
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588463952,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2365",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588463952,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2961
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589188176,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2365",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589188176,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2961
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
bool tcp_write_xmit(struct sock * sk, unsigned int mss_now, int nonagle, int push_one, gfp_t gfp)
```

```json
{
  "name": "tcp_write_xmit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589228240,
      "name": "tcp_write_xmit",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2365",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_push_one",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589228240,
      "name": "tcp_write_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2961
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
