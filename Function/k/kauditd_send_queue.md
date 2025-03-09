# Function: <code>kauditd_send_queue</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580105856,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:681",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105856,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580158512,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:681",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158512,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580218224,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:724",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580218224,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580270672,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:720",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580270672,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580321536,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:707",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580321536,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580370336,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:707",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580370336,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580444464,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:709",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580444464,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580432624,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:714",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580432624,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580436832,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:714",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580436832,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *, int) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580601232,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:736",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580601232,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *, int) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580804944,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:737",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580804944,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *, int) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090560,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:735",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090560,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *, int) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581182176,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:735",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581182176,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *, int) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581287888,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:746",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287888,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491634608,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:707",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491634608,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225587616,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:707",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225587616,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284628320,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:707",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284628320,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272031386,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:707",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272031386,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580339136,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:707",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580339136,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580286304,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:707",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580286304,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580330384,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:707",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580330384,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *) err_hook)
```

```json
{
  "name": "kauditd_send_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580385616,
      "name": "kauditd_send_queue",
      "external": false,
      "loc": "kernel/audit.c:707",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580385616,
      "name": "kauditd_send_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int kauditd_send_queue(struct sock * sk, u32 portid, struct sk_buff_head * queue, unsigned int retry_limit, void (*)(struct sk_buff *) skb_hook, void (*)(struct sk_buff *) err_hook)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void (*)(struct sk_buff *) err_hook</code> ➡️ <code>void (*)(struct sk_buff *, int) err_hook</code>
</li>
</ul>
</details>
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
