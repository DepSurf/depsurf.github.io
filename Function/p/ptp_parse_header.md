# Function: <code>ptp_parse_header</code>

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
struct ptp_header * ptp_parse_header(struct sk_buff * skb, unsigned int type)
```

```json
{
  "name": "ptp_parse_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589662992,
      "name": "ptp_parse_header",
      "external": true,
      "loc": "net/core/ptp_classifier.c:110",
      "file": "net/core/ptp_classifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589662992,
      "name": "ptp_parse_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
struct ptp_header * ptp_parse_header(struct sk_buff * skb, unsigned int type)
```

```json
{
  "name": "ptp_parse_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589554576,
      "name": "ptp_parse_header",
      "external": true,
      "loc": "net/core/ptp_classifier.c:110",
      "file": "net/core/ptp_classifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589554576,
      "name": "ptp_parse_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct ptp_header * ptp_parse_header(struct sk_buff * skb, unsigned int type)
```

```json
{
  "name": "ptp_parse_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590299360,
      "name": "ptp_parse_header",
      "external": true,
      "loc": "net/core/ptp_classifier.c:110",
      "file": "net/core/ptp_classifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590299360,
      "name": "ptp_parse_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct ptp_header * ptp_parse_header(struct sk_buff * skb, unsigned int type)
```

```json
{
  "name": "ptp_parse_header",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591883285,
      "name": "ptp_parse_header",
      "external": true,
      "loc": "net/core/ptp_classifier.c:110",
      "file": "net/core/ptp_classifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/ptp_classifier.c:ptp_msg_is_sync"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591882976,
      "name": "ptp_parse_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct ptp_header * ptp_parse_header(struct sk_buff * skb, unsigned int type)
```

```json
{
  "name": "ptp_parse_header",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593684965,
      "name": "ptp_parse_header",
      "external": true,
      "loc": "net/core/ptp_classifier.c:110",
      "file": "net/core/ptp_classifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/ptp_classifier.c:ptp_msg_is_sync"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593684624,
      "name": "ptp_parse_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct ptp_header * ptp_parse_header(struct sk_buff * skb, unsigned int type)
```

```json
{
  "name": "ptp_parse_header",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594165605,
      "name": "ptp_parse_header",
      "external": true,
      "loc": "net/core/ptp_classifier.c:110",
      "file": "net/core/ptp_classifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/ptp_classifier.c:ptp_msg_is_sync"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594165296,
      "name": "ptp_parse_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct ptp_header * ptp_parse_header(struct sk_buff * skb, unsigned int type)
```

```json
{
  "name": "ptp_parse_header",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594962165,
      "name": "ptp_parse_header",
      "external": true,
      "loc": "net/core/ptp_classifier.c:110",
      "file": "net/core/ptp_classifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/ptp_classifier.c:ptp_msg_is_sync"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594961856,
      "name": "ptp_parse_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct ptp_header * ptp_parse_header(struct sk_buff * skb, unsigned int type)
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
