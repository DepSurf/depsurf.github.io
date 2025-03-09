# Function: <code>__strp_recv</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588654720,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:100",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588654720,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1699
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589020960,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:99",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589020960,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1733
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589246288,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:99",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589246288,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1684
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:97",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589701424,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1530
    },
    {
      "addr": 18446744071589703080,
      "name": "__strp_recv.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589925760,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:97",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589925760,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1555
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590954992,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:97",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590954992,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1584
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591019584,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:97",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591019584,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1584
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590950144,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:97",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590950144,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1584
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591786400,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:89",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591786400,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1584
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593496016,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:89",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593496016,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1683
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595414464,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:89",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595414464,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1676
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595920624,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:89",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595920624,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1672
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596781680,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:89",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596781680,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1672
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503652168,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:97",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503652168,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1460
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236293428,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:97",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236293428,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1540
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297472928,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:97",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297472928,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1912
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279594708,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:97",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279594708,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1246
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589530128,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:97",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589530128,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1555
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589256192,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:97",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589256192,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1555
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589971392,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:97",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589971392,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1555
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
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```

```json
{
  "name": "__strp_recv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590021024,
      "name": "__strp_recv",
      "external": false,
      "loc": "net/strparser/strparser.c:97",
      "file": "net/strparser/strparser.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/strparser/strparser.c:strp_recv",
        "net/strparser/strparser.c:strp_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590021024,
      "name": "__strp_recv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1555
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int __strp_recv(read_descriptor_t * desc, struct sk_buff * orig_skb, unsigned int orig_offset, size_t orig_len, size_t max_msg_size, long int timeo)
```
</details>
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
