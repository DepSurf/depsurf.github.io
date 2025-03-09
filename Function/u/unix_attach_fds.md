# Function: <code>unix_attach_fds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586965086,
      "name": "unix_attach_fds",
      "external": false,
      "loc": "net/unix/af_unix.c:1533",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_scm_to_skb"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587411454,
      "name": "unix_attach_fds",
      "external": false,
      "loc": "net/unix/af_unix.c:1521",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_scm_to_skb"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587614750,
      "name": "unix_attach_fds",
      "external": false,
      "loc": "net/unix/af_unix.c:1526",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_scm_to_skb"
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
  "name": "unix_attach_fds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587764280,
      "name": "unix_attach_fds",
      "external": false,
      "loc": "net/unix/af_unix.c:1533",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_scm_to_skb"
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
  "name": "unix_attach_fds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588293076,
      "name": "unix_attach_fds",
      "external": false,
      "loc": "net/unix/af_unix.c:1532",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_scm_to_skb"
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
  "name": "unix_attach_fds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588646468,
      "name": "unix_attach_fds",
      "external": false,
      "loc": "net/unix/af_unix.c:1522",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_scm_to_skb"
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
  "name": "unix_attach_fds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588862468,
      "name": "unix_attach_fds",
      "external": false,
      "loc": "net/unix/af_unix.c:1539",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_scm_to_skb"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589322560,
      "name": "unix_attach_fds",
      "external": true,
      "loc": "net/unix/scm.c:103",
      "file": "net/unix/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_scm_to_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589322560,
      "name": "unix_attach_fds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589546800,
      "name": "unix_attach_fds",
      "external": true,
      "loc": "net/unix/scm.c:103",
      "file": "net/unix/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_scm_to_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589546800,
      "name": "unix_attach_fds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590549872,
      "name": "unix_attach_fds",
      "external": true,
      "loc": "net/unix/scm.c:103",
      "file": "net/unix/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590549872,
      "name": "unix_attach_fds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590609568,
      "name": "unix_attach_fds",
      "external": true,
      "loc": "net/unix/scm.c:104",
      "file": "net/unix/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590609568,
      "name": "unix_attach_fds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590534976,
      "name": "unix_attach_fds",
      "external": true,
      "loc": "net/unix/scm.c:104",
      "file": "net/unix/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590534976,
      "name": "unix_attach_fds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591345056,
      "name": "unix_attach_fds",
      "external": true,
      "loc": "net/unix/scm.c:106",
      "file": "net/unix/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591345056,
      "name": "unix_attach_fds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593017472,
      "name": "unix_attach_fds",
      "external": true,
      "loc": "net/unix/scm.c:106",
      "file": "net/unix/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593017472,
      "name": "unix_attach_fds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594907920,
      "name": "unix_attach_fds",
      "external": true,
      "loc": "net/unix/scm.c:106",
      "file": "net/unix/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594907920,
      "name": "unix_attach_fds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595299488,
      "name": "unix_attach_fds",
      "external": true,
      "loc": "net/unix/scm.c:107",
      "file": "net/unix/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595299488,
      "name": "unix_attach_fds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596140992,
      "name": "unix_attach_fds",
      "external": true,
      "loc": "net/unix/scm.c:105",
      "file": "net/unix/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596140992,
      "name": "unix_attach_fds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503219032,
      "name": "unix_attach_fds",
      "external": true,
      "loc": "net/unix/scm.c:103",
      "file": "net/unix/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_scm_to_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503219032,
      "name": "unix_attach_fds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235888712,
      "name": "unix_attach_fds",
      "external": true,
      "loc": "net/unix/scm.c:103",
      "file": "net/unix/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_scm_to_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235888712,
      "name": "unix_attach_fds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296955536,
      "name": "unix_attach_fds",
      "external": true,
      "loc": "net/unix/scm.c:103",
      "file": "net/unix/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_scm_to_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296955536,
      "name": "unix_attach_fds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279252606,
      "name": "unix_attach_fds",
      "external": true,
      "loc": "net/unix/scm.c:103",
      "file": "net/unix/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279252606,
      "name": "unix_attach_fds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589151168,
      "name": "unix_attach_fds",
      "external": true,
      "loc": "net/unix/scm.c:103",
      "file": "net/unix/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_scm_to_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589151168,
      "name": "unix_attach_fds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588876160,
      "name": "unix_attach_fds",
      "external": true,
      "loc": "net/unix/scm.c:103",
      "file": "net/unix/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_scm_to_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588876160,
      "name": "unix_attach_fds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589588032,
      "name": "unix_attach_fds",
      "external": true,
      "loc": "net/unix/scm.c:103",
      "file": "net/unix/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_scm_to_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589588032,
      "name": "unix_attach_fds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```

```json
{
  "name": "unix_attach_fds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589635840,
      "name": "unix_attach_fds",
      "external": true,
      "loc": "net/unix/scm.c:103",
      "file": "net/unix/scm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_scm_to_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589635840,
      "name": "unix_attach_fds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int unix_attach_fds(struct scm_cookie * scm, struct sk_buff * skb)
```
</details>
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
