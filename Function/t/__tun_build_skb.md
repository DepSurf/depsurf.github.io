# Function: <code>__tun_build_skb</code>

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
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586577760,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1613",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586577760,
      "name": "__tun_build_skb.isra.56",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586829424,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1604",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586829424,
      "name": "__tun_build_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586975504,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1604",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586975504,
      "name": "__tun_build_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
struct sk_buff * __tun_build_skb(struct tun_file * tfile, struct page_frag * alloc_frag, char * buf, int buflen, int len, int pad)
```

```json
{
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587803616,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1569",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587803616,
      "name": "__tun_build_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct sk_buff * __tun_build_skb(struct tun_file * tfile, struct page_frag * alloc_frag, char * buf, int buflen, int len, int pad)
```

```json
{
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587861376,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1500",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587861376,
      "name": "__tun_build_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct sk_buff * __tun_build_skb(struct tun_file * tfile, struct page_frag * alloc_frag, char * buf, int buflen, int len, int pad)
```

```json
{
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587739488,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1511",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587739488,
      "name": "__tun_build_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
struct sk_buff * __tun_build_skb(struct tun_file * tfile, struct page_frag * alloc_frag, char * buf, int buflen, int len, int pad)
```

```json
{
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588334736,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1567",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588334736,
      "name": "__tun_build_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
struct sk_buff * __tun_build_skb(struct tun_file * tfile, struct page_frag * alloc_frag, char * buf, int buflen, int len, int pad)
```

```json
{
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589734640,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1595",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589734640,
      "name": "__tun_build_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
struct sk_buff * __tun_build_skb(struct tun_file * tfile, struct page_frag * alloc_frag, char * buf, int buflen, int len, int pad)
```

```json
{
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591356672,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1598",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591356672,
      "name": "__tun_build_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
struct sk_buff * __tun_build_skb(struct tun_file * tfile, struct page_frag * alloc_frag, char * buf, int buflen, int len, int pad)
```

```json
{
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591718448,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1604",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591718448,
      "name": "__tun_build_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
struct sk_buff * __tun_build_skb(struct tun_file * tfile, struct page_frag * alloc_frag, char * buf, int buflen, int len, int pad)
```

```json
{
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592462160,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1607",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592462160,
      "name": "__tun_build_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499968456,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1604",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499968456,
      "name": "__tun_build_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
struct sk_buff * __tun_build_skb(struct tun_file * tfile, struct page_frag * alloc_frag, char * buf, int buflen, int len, int pad)
```

```json
{
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232511580,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1604",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232511580,
      "name": "__tun_build_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293296368,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1604",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293296368,
      "name": "__tun_build_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277046190,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1604",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277046190,
      "name": "__tun_build_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586732512,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1604",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586732512,
      "name": "__tun_build_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586599728,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1604",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586599728,
      "name": "__tun_build_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586930064,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1604",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586930064,
      "name": "__tun_build_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tun_build_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587037696,
      "name": "__tun_build_skb",
      "external": false,
      "loc": "drivers/net/tun.c:1604",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587037696,
      "name": "__tun_build_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct sk_buff * __tun_build_skb(struct tun_file * tfile, struct page_frag * alloc_frag, char * buf, int buflen, int len, int pad)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct sk_buff * __tun_build_skb(struct tun_file * tfile, struct page_frag * alloc_frag, char * buf, int buflen, int len, int pad)
```
</details>
</li>
</ul>
