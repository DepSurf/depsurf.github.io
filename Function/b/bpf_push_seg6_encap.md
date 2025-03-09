# Function: <code>bpf_push_seg6_encap</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587963248,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:4482",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587963248,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588113632,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:4767",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588113632,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588431184,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:4912",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588431184,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588636768,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:4921",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588636768,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589524688,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:5048",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589524688,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589533664,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:5600",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589533664,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589430848,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:5702",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589430848,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590157104,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:5826",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590157104,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591716496,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:6135",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591716496,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593503632,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:6149",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593503632,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593966992,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:6228",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593966992,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594751616,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:6318",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594751616,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502182224,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:4921",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502182224,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234929644,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:4921",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234929644,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295658880,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:4921",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295658880,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278437428,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:4921",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278437428,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588243504,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:4921",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588243504,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587956320,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:4921",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587956320,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588575328,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:4921",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588575328,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```

```json
{
  "name": "bpf_push_seg6_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588712816,
      "name": "bpf_push_seg6_encap",
      "external": false,
      "loc": "net/core/filter.c:4921",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_in_push_encap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588712816,
      "name": "bpf_push_seg6_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int bpf_push_seg6_encap(struct sk_buff * skb, u32 type, void * hdr, u32 len)
```
</details>
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
