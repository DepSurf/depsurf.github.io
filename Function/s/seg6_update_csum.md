# Function: <code>seg6_update_csum</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587843169,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:294",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587999510,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:294",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588536102,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:327",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588900434,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:327",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589123910,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:327",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589576349,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:323",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589800733,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:323",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void seg6_update_csum(struct sk_buff * skb)
```

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590820240,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:324",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590820240,
      "name": "seg6_update_csum",
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
void seg6_update_csum(struct sk_buff * skb)
```

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590880288,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:324",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590880288,
      "name": "seg6_update_csum",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590812521,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:323",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591631305,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:334",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593325072,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:340",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595230592,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:340",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595626523,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:337",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596473947,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:339",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503506544,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:323",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236158364,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:323",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297297844,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:323",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279478170,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:323",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589405101,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:323",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589130093,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:323",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589841965,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:323",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seg6_update_csum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589893245,
      "name": "seg6_update_csum",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:323",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_srh_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void seg6_update_csum(struct sk_buff * skb)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void seg6_update_csum(struct sk_buff * skb)
```
</details>
</li>
</ul>
