# Function: <code>tcp_try_rmem_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586637872,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4321",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586637872,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1049
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587080192,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4385",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587080192,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1089
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587279872,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4412",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587279872,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587413104,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4371",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587413104,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1041
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587947584,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4348",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587947584,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1056
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4448",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588297456,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1071
    },
    {
      "addr": 18446744071588307424,
      "name": "tcp_try_rmem_schedule.cold.82",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4465",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588486336,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1065
    },
    {
      "addr": 18446744071588496230,
      "name": "tcp_try_rmem_schedule.cold.87",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588893632,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4478",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588893632,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1073
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589117712,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4528",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589117712,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1083
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590062544,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4557",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590062544,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590108432,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4695",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590108432,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590022768,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4705",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590022768,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1055
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590792128,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4739",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590792128,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1052
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4758",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592426064,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1252
    },
    {
      "addr": 18446744071594602573,
      "name": "tcp_try_rmem_schedule.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4771",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594280016,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1159
    },
    {
      "addr": 18446744071596337906,
      "name": "tcp_try_rmem_schedule.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4776",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594666176,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1167
    },
    {
      "addr": 18446744071596867472,
      "name": "tcp_try_rmem_schedule.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595472688,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4907",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595472688,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1118
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502733672,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4528",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502733672,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235437472,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4528",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235437472,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1224
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296356320,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4528",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296356320,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1476
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278859222,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4528",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278859222,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 974
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588724096,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4528",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588724096,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1083
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588436080,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4528",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588436080,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1083
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589160272,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4528",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589160272,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1083
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
int tcp_try_rmem_schedule(struct sock * sk, struct sk_buff * skb, unsigned int size)
```

```json
{
  "name": "tcp_try_rmem_schedule",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589200240,
      "name": "tcp_try_rmem_schedule",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4528",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589200240,
      "name": "tcp_try_rmem_schedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1083
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
