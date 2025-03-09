# Function: <code>__sk_msg_free_partial</code>

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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588179136,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:202",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588179136,
      "name": "__sk_msg_free_partial",
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:211",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588505200,
      "name": "__sk_msg_free_partial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    },
    {
      "addr": 18446744071588507726,
      "name": "__sk_msg_free_partial.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588714048,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:210",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588714048,
      "name": "__sk_msg_free_partial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589580912,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:211",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589580912,
      "name": "__sk_msg_free_partial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589591536,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:213",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589591536,
      "name": "__sk_msg_free_partial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589650288,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:213",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589650288,
      "name": "__sk_msg_free_partial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590406576,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:213",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590406576,
      "name": "__sk_msg_free_partial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592006208,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:222",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592006208,
      "name": "__sk_msg_free_partial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593817328,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:222",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593817328,
      "name": "__sk_msg_free_partial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594194256,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:223",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594194256,
      "name": "__sk_msg_free_partial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594990560,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:223",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594990560,
      "name": "__sk_msg_free_partial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502274336,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:210",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502274336,
      "name": "__sk_msg_free_partial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235018244,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:210",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235018244,
      "name": "__sk_msg_free_partial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295776544,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:210",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295776544,
      "name": "__sk_msg_free_partial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278510632,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:210",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278510632,
      "name": "__sk_msg_free_partial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588320784,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:210",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588320784,
      "name": "__sk_msg_free_partial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588033568,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:210",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588033568,
      "name": "__sk_msg_free_partial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588652608,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:210",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588652608,
      "name": "__sk_msg_free_partial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
```

```json
{
  "name": "__sk_msg_free_partial",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588792416,
      "name": "__sk_msg_free_partial",
      "external": false,
      "loc": "net/core/skmsg.c:210",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_free_partial_nocharge",
        "net/core/skmsg.c:sk_msg_free_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588792416,
      "name": "__sk_msg_free_partial",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void __sk_msg_free_partial(struct sock * sk, struct sk_msg * msg, u32 bytes, bool charge)
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
