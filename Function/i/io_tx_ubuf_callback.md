# Function: <code>io_tx_ubuf_callback</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_tx_ubuf_callback(struct sk_buff * skb, struct ubuf_info * uarg, bool success)
```

```json
{
  "name": "io_tx_ubuf_callback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586861471,
      "name": "io_tx_ubuf_callback",
      "external": false,
      "loc": "io_uring/notif.c:27",
      "file": "io_uring/notif.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/notif.c:io_tx_ubuf_callback_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586861280,
      "name": "io_tx_ubuf_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void io_tx_ubuf_callback(struct sk_buff * skb, struct ubuf_info * uarg, bool success)
```

```json
{
  "name": "io_tx_ubuf_callback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587127663,
      "name": "io_tx_ubuf_callback",
      "external": false,
      "loc": "io_uring/notif.c:27",
      "file": "io_uring/notif.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/notif.c:io_tx_ubuf_callback_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587127472,
      "name": "io_tx_ubuf_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void io_tx_ubuf_callback(struct sk_buff * skb, struct ubuf_info * uarg, bool success)
```

```json
{
  "name": "io_tx_ubuf_callback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587406735,
      "name": "io_tx_ubuf_callback",
      "external": false,
      "loc": "io_uring/notif.c:27",
      "file": "io_uring/notif.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/notif.c:io_tx_ubuf_callback_ext"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587406544,
      "name": "io_tx_ubuf_callback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void io_tx_ubuf_callback(struct sk_buff * skb, struct ubuf_info * uarg, bool success)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
