# Function: <code>__sk_msg_free</code>

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
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588178800,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:171",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588178800,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:180",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588504880,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071588507703,
      "name": "__sk_msg_free.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588713728,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:180",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588713728,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589580608,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:181",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589580608,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589589536,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:183",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589589536,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589647520,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:183",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589647520,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590403056,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:183",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590403056,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591998608,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:192",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_skb_ingress_enqueue",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591998608,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593809808,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:192",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_skb_ingress_enqueue",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593809808,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594184096,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:193",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_skb_ingress_enqueue",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594184096,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594980432,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:193",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_skb_ingress_enqueue",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594980432,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502273976,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:180",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502273976,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235017900,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:180",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235017900,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295776128,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:180",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295776128,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278510320,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:180",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278510320,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588320464,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:180",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588320464,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588033248,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:180",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588033248,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588652288,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:180",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588652288,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
```

```json
{
  "name": "__sk_msg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588792096,
      "name": "__sk_msg_free",
      "external": false,
      "loc": "net/core/skmsg.c:180",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg",
        "net/core/skmsg.c:sk_msg_free_nocharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588792096,
      "name": "__sk_msg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
int __sk_msg_free(struct sock * sk, struct sk_msg * msg, u32 i, bool charge)
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
