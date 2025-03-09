# Function: <code>sk_psock_verdict_apply</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588175626,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:668",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_read"
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
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588502241,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:680",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_read"
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
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588710641,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:689",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_read"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589581853,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:749",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_read"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void sk_psock_verdict_apply(struct sk_psock * psock, struct sk_buff * skb, int verdict)
```

```json
{
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589589376,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:828",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589589376,
      "name": "sk_psock_verdict_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int sk_psock_verdict_apply(struct sk_psock * psock, struct sk_buff * skb, int verdict)
```

```json
{
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589651216,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:957",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589651216,
      "name": "sk_psock_verdict_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
int sk_psock_verdict_apply(struct sk_psock * psock, struct sk_buff * skb, int verdict)
```

```json
{
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590408192,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:953",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590408192,
      "name": "sk_psock_verdict_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int sk_psock_verdict_apply(struct sk_psock * psock, struct sk_buff * skb, int verdict)
```

```json
{
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592000448,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:973",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592000448,
      "name": "sk_psock_verdict_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
int sk_psock_verdict_apply(struct sk_psock * psock, struct sk_buff * skb, int verdict)
```

```json
{
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593819984,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:980",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593819984,
      "name": "sk_psock_verdict_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
int sk_psock_verdict_apply(struct sk_psock * psock, struct sk_buff * skb, int verdict)
```

```json
{
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594192976,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:970",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594192976,
      "name": "sk_psock_verdict_apply",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int sk_psock_verdict_apply(struct sk_psock * psock, struct sk_buff * skb, int verdict)
```

```json
{
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594988400,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:976",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594988400,
      "name": "sk_psock_verdict_apply",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502277120,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:689",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_read"
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
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235014952,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:689",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_read"
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
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295770576,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:689",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_read"
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
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278507448,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:689",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_read"
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
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588317377,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:689",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_read"
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
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588030161,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:689",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_read"
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
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588649201,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:689",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_read"
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
  "name": "sk_psock_verdict_apply",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588789004,
      "name": "sk_psock_verdict_apply",
      "external": false,
      "loc": "net/core/skmsg.c:689",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_read"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void sk_psock_verdict_apply(struct sk_psock * psock, struct sk_buff * skb, int verdict)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
