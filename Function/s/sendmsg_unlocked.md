# Function: <code>sendmsg_unlocked</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sendmsg_unlocked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "sendmsg_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589136048,
      "name": "sendmsg_unlocked",
      "external": false,
      "loc": "net/core/skbuff.c:2507",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_send_sock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589135232,
      "name": "sendmsg_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int sendmsg_unlocked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "sendmsg_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589856000,
      "name": "sendmsg_unlocked",
      "external": false,
      "loc": "net/core/skbuff.c:2579",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_send_sock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589855184,
      "name": "sendmsg_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sendmsg_unlocked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "sendmsg_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591381089,
      "name": "sendmsg_unlocked",
      "external": false,
      "loc": "net/core/skbuff.c:2628",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_send_sock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591380256,
      "name": "sendmsg_unlocked",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sendmsg_unlocked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "sendmsg_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593141985,
      "name": "sendmsg_unlocked",
      "external": false,
      "loc": "net/core/skbuff.c:2834",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_send_sock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593141120,
      "name": "sendmsg_unlocked",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sendmsg_unlocked(struct sock * sk, struct msghdr * msg)
```

```json
{
  "name": "sendmsg_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593594991,
      "name": "sendmsg_unlocked",
      "external": false,
      "loc": "net/core/skbuff.c:3012",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_send_sock",
        "net/core/skbuff.c:__skb_send_sock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593594048,
      "name": "sendmsg_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sendmsg_unlocked(struct sock * sk, struct msghdr * msg)
```

```json
{
  "name": "sendmsg_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594367903,
      "name": "sendmsg_unlocked",
      "external": false,
      "loc": "net/core/skbuff.c:3100",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__skb_send_sock",
        "net/core/skbuff.c:__skb_send_sock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594366960,
      "name": "sendmsg_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int sendmsg_unlocked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct kvec * vec</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t num</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
