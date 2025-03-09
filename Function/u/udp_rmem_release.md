# Function: <code>udp_rmem_release</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void udp_rmem_release(struct sock * sk, int size, int partial)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587384256,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1178",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock",
        "net/ipv4/udp.c:udp_skb_destructor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587384256,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587518736,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1194",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock",
        "net/ipv4/udp.c:udp_skb_dtor_locked",
        "net/ipv4/udp.c:udp_skb_destructor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587518736,
      "name": "udp_rmem_release",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588041600,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1202",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock",
        "net/ipv4/udp.c:udp_skb_dtor_locked",
        "net/ipv4/udp.c:udp_skb_destructor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588041600,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588402800,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1272",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock",
        "net/ipv4/udp.c:udp_skb_dtor_locked",
        "net/ipv4/udp.c:udp_skb_destructor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588402800,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588595184,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1340",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock",
        "net/ipv4/udp.c:udp_skb_dtor_locked",
        "net/ipv4/udp.c:udp_skb_destructor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588595184,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589006736,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1327",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock",
        "net/ipv4/udp.c:udp_skb_dtor_locked",
        "net/ipv4/udp.c:udp_skb_destructor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589006736,
      "name": "udp_rmem_release",
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589230688,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1361",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock",
        "net/ipv4/udp.c:udp_skb_dtor_locked",
        "net/ipv4/udp.c:udp_skb_destructor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589230688,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590198672,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1367",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590198672,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590249168,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1417",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590249168,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590167280,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1436",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590167280,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590947712,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1437",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590947712,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592583344,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1437",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592583344,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594446128,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1448",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594446128,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594837600,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1420",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594837600,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595647664,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1395",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595647664,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502851384,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1361",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock",
        "net/ipv4/udp.c:udp_skb_dtor_locked",
        "net/ipv4/udp.c:udp_skb_destructor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502851384,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235542140,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1361",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock",
        "net/ipv4/udp.c:udp_skb_dtor_locked",
        "net/ipv4/udp.c:udp_skb_destructor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235542140,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296495024,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1361",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock",
        "net/ipv4/udp.c:udp_destruct_sock",
        "net/ipv4/udp.c:udp_skb_dtor_locked",
        "net/ipv4/udp.c:udp_skb_destructor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296495024,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278960824,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1361",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock",
        "net/ipv4/udp.c:udp_skb_dtor_locked",
        "net/ipv4/udp.c:udp_skb_destructor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278960824,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588837072,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1361",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock",
        "net/ipv4/udp.c:udp_skb_dtor_locked",
        "net/ipv4/udp.c:udp_skb_destructor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588837072,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588549008,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1361",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock",
        "net/ipv4/udp.c:udp_skb_dtor_locked",
        "net/ipv4/udp.c:udp_skb_destructor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588549008,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589273248,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1361",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock",
        "net/ipv4/udp.c:udp_skb_dtor_locked",
        "net/ipv4/udp.c:udp_skb_destructor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589273248,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
void udp_rmem_release(struct sock * sk, int size, int partial, bool rx_queue_lock_held)
```

```json
{
  "name": "udp_rmem_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589302304,
      "name": "udp_rmem_release",
      "external": false,
      "loc": "net/ipv4/udp.c:1361",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/udp.c:udp_destruct_sock",
        "net/ipv4/udp.c:udp_skb_dtor_locked",
        "net/ipv4/udp.c:udp_skb_destructor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589302304,
      "name": "udp_rmem_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
void udp_rmem_release(struct sock * sk, int size, int partial)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool rx_queue_lock_held</code>
</li>
</ul>
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
