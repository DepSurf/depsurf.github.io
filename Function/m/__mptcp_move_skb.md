# Function: <code>__mptcp_move_skb</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __mptcp_move_skb(struct mptcp_sock * msk, struct sock * ssk, struct sk_buff * skb, unsigned int offset, size_t copy_len)
```

```json
{
  "name": "__mptcp_move_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591081344,
      "name": "__mptcp_move_skb",
      "external": false,
      "loc": "net/mptcp/protocol.c:142",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591081344,
      "name": "__mptcp_move_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
bool __mptcp_move_skb(struct mptcp_sock * msk, struct sock * ssk, struct sk_buff * skb, unsigned int offset, size_t copy_len)
```

```json
{
  "name": "__mptcp_move_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591153920,
      "name": "__mptcp_move_skb",
      "external": false,
      "loc": "net/mptcp/protocol.c:274",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591153920,
      "name": "__mptcp_move_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
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
bool __mptcp_move_skb(struct mptcp_sock * msk, struct sock * ssk, struct sk_buff * skb, unsigned int offset, size_t copy_len)
```

```json
{
  "name": "__mptcp_move_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591086416,
      "name": "__mptcp_move_skb",
      "external": false,
      "loc": "net/mptcp/protocol.c:268",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591086416,
      "name": "__mptcp_move_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
bool __mptcp_move_skb(struct mptcp_sock * msk, struct sock * ssk, struct sk_buff * skb, unsigned int offset, size_t copy_len)
```

```json
{
  "name": "__mptcp_move_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591924432,
      "name": "__mptcp_move_skb",
      "external": false,
      "loc": "net/mptcp/protocol.c:273",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591924432,
      "name": "__mptcp_move_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
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
bool __mptcp_move_skb(struct mptcp_sock * msk, struct sock * ssk, struct sk_buff * skb, unsigned int offset, size_t copy_len)
```

```json
{
  "name": "__mptcp_move_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593648736,
      "name": "__mptcp_move_skb",
      "external": false,
      "loc": "net/mptcp/protocol.c:344",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593648736,
      "name": "__mptcp_move_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
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
bool __mptcp_move_skb(struct mptcp_sock * msk, struct sock * ssk, struct sk_buff * skb, unsigned int offset, size_t copy_len)
```

```json
{
  "name": "__mptcp_move_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595584688,
      "name": "__mptcp_move_skb",
      "external": false,
      "loc": "net/mptcp/protocol.c:336",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595584688,
      "name": "__mptcp_move_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
bool __mptcp_move_skb(struct mptcp_sock * msk, struct sock * ssk, struct sk_buff * skb, unsigned int offset, size_t copy_len)
```

```json
{
  "name": "__mptcp_move_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596094352,
      "name": "__mptcp_move_skb",
      "external": false,
      "loc": "net/mptcp/protocol.c:350",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596094352,
      "name": "__mptcp_move_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
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
bool __mptcp_move_skb(struct mptcp_sock * msk, struct sock * ssk, struct sk_buff * skb, unsigned int offset, size_t copy_len)
```

```json
{
  "name": "__mptcp_move_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596963296,
      "name": "__mptcp_move_skb",
      "external": false,
      "loc": "net/mptcp/protocol.c:338",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596963296,
      "name": "__mptcp_move_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __mptcp_move_skb(struct mptcp_sock * msk, struct sock * ssk, struct sk_buff * skb, unsigned int offset, size_t copy_len)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
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
