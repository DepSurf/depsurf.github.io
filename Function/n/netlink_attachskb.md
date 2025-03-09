# Function: <code>netlink_attachskb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586505424,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1723",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:SyS_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586505424,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586948240,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1114",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:SyS_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586948240,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587143216,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1131",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:SyS_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587143216,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587273472,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1165",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587273472,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587793488,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1178",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587793488,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588136080,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1217",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588136080,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588318832,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1210",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588318832,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588716992,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1202",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588716992,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588940848,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1203",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588940848,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589831664,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1203",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589831664,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589868112,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1204",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589868112,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589774112,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1214",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589774112,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590533504,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1219",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590533504,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592142112,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1219",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592142112,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593966416,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1239",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593966416,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594343344,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1239",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594343344,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595143104,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1241",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595143104,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 570
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502539104,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1203",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502539104,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235247244,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1203",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235247244,
      "name": "netlink_attachskb",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296113408,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1203",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296113408,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278704026,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1203",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__se_sys_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278704026,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588547232,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1203",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588547232,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588259216,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1203",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588259216,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588879408,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1203",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588879408,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int netlink_attachskb(struct sock * sk, struct sk_buff * skb, long int * timeo, struct sock * ssk)
```

```json
{
  "name": "netlink_attachskb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589021472,
      "name": "netlink_attachskb",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1203",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:do_mq_notify",
        "net/netlink/af_netlink.c:netlink_unicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589021472,
      "name": "netlink_attachskb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
