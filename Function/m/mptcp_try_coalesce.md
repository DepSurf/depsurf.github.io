# Function: <code>mptcp_try_coalesce</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool mptcp_try_coalesce(struct sock * sk, struct sk_buff * to, struct sk_buff * from)
```

```json
{
  "name": "mptcp_try_coalesce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591142720,
      "name": "mptcp_try_coalesce",
      "external": false,
      "loc": "net/mptcp/protocol.c:130",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591142720,
      "name": "mptcp_try_coalesce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
bool mptcp_try_coalesce(struct sock * sk, struct sk_buff * to, struct sk_buff * from)
```

```json
{
  "name": "mptcp_try_coalesce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591073744,
      "name": "mptcp_try_coalesce",
      "external": false,
      "loc": "net/mptcp/protocol.c:124",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591073744,
      "name": "mptcp_try_coalesce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
bool mptcp_try_coalesce(struct sock * sk, struct sk_buff * to, struct sk_buff * from)
```

```json
{
  "name": "mptcp_try_coalesce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_try_coalesce",
      "external": false,
      "loc": "net/mptcp/protocol.c:129",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591916944,
      "name": "mptcp_try_coalesce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071592751611,
      "name": "mptcp_try_coalesce.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
bool mptcp_try_coalesce(struct sock * sk, struct sk_buff * to, struct sk_buff * from)
```

```json
{
  "name": "mptcp_try_coalesce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_try_coalesce",
      "external": false,
      "loc": "net/mptcp/protocol.c:139",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593641392,
      "name": "mptcp_try_coalesce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071594638554,
      "name": "mptcp_try_coalesce.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
bool mptcp_try_coalesce(struct sock * sk, struct sk_buff * to, struct sk_buff * from)
```

```json
{
  "name": "mptcp_try_coalesce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_try_coalesce",
      "external": false,
      "loc": "net/mptcp/protocol.c:130",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595572416,
      "name": "mptcp_try_coalesce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071596368000,
      "name": "mptcp_try_coalesce.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
bool mptcp_try_coalesce(struct sock * sk, struct sk_buff * to, struct sk_buff * from)
```

```json
{
  "name": "mptcp_try_coalesce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_try_coalesce",
      "external": false,
      "loc": "net/mptcp/protocol.c:144",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596081568,
      "name": "mptcp_try_coalesce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071596897767,
      "name": "mptcp_try_coalesce.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool mptcp_try_coalesce(struct sock * sk, struct sk_buff * to, struct sk_buff * from)
```

```json
{
  "name": "mptcp_try_coalesce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_try_coalesce",
      "external": false,
      "loc": "net/mptcp/protocol.c:132",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596949824,
      "name": "mptcp_try_coalesce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    },
    {
      "addr": 18446744071597823090,
      "name": "mptcp_try_coalesce.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool mptcp_try_coalesce(struct sock * sk, struct sk_buff * to, struct sk_buff * from)
```
</details>
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
