# Function: <code>skb_queue_head</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586205584,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:2460",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586205584,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586626400,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:2458",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586626400,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586810928,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:2453",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "drivers/net/ppp/ppp_generic.c:ppp_channel_push",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586810928,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586935264,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:2493",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_rehold_skb",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586935264,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587428320,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:2872",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_rehold_skb",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587428320,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587732736,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:2888",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_rehold_skb",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587732736,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587866992,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:2947",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_rehold_skb",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587866992,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588171664,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:3113",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_rehold_skb",
        "fs/io_uring.c:__io_uring_register",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588171664,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588376864,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:3119",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_rehold_skb",
        "fs/io_uring.c:__io_uring_register",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376864,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589239456,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:3118",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_rehold_skb",
        "fs/io_uring.c:__io_sqe_files_scm",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589239456,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589238848,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:3136",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_rehold_skb",
        "fs/io_uring.c:__io_sqe_files_scm",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589238848,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589132640,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:3222",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_rehold_skb",
        "fs/io_uring.c:__io_sqe_files_scm",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589132640,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589852336,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:3294",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__io_sqe_files_scm",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589852336,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591376880,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:3343",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591376880,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593137536,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:3547",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:__io_scm_file_account",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593137536,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593590384,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:3717",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rsrc.c:__io_scm_file_account",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "drivers/net/wwan/wwan_core.c:wwan_port_fops_read",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593590384,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594363168,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:3838",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594363168,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501901824,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:3119",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_rehold_skb",
        "fs/io_uring.c:__arm64_sys_io_uring_register",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501901824,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234650896,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:3119",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_rehold_skb",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234650896,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295296112,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:3119",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_rehold_skb",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "drivers/net/ppp/ppp_generic.c:__ppp_channel_push",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295296112,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278205812,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:3119",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_rehold_skb",
        "fs/io_uring.c:__se_sys_io_uring_register",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278205812,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587983648,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:3119",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_rehold_skb",
        "fs/io_uring.c:__io_uring_register",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587983648,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587696752,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:3119",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_rehold_skb",
        "fs/io_uring.c:__io_uring_register",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587696752,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588315424,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:3119",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_rehold_skb",
        "fs/io_uring.c:__io_uring_register",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588315424,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void skb_queue_head(struct sk_buff_head * list, struct sk_buff * newsk)
```

```json
{
  "name": "skb_queue_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588450656,
      "name": "skb_queue_head",
      "external": true,
      "loc": "net/core/skbuff.c:3119",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_queue",
        "kernel/audit.c:kauditd_rehold_skb",
        "fs/io_uring.c:__io_uring_register",
        "net/core/netpoll.c:queue_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588450656,
      "name": "skb_queue_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
