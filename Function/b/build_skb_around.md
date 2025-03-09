# Function: <code>build_skb_around</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "build_skb_around",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588174192,
      "name": "build_skb_around",
      "external": true,
      "loc": "net/core/skbuff.c:343",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588174192,
      "name": "build_skb_around",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "build_skb_around",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588379328,
      "name": "build_skb_around",
      "external": true,
      "loc": "net/core/skbuff.c:343",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588379328,
      "name": "build_skb_around",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "build_skb_around",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589247568,
      "name": "build_skb_around",
      "external": true,
      "loc": "net/core/skbuff.c:344",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589247568,
      "name": "build_skb_around",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "build_skb_around",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589247216,
      "name": "build_skb_around",
      "external": true,
      "loc": "net/core/skbuff.c:349",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589247216,
      "name": "build_skb_around",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "build_skb_around",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589143552,
      "name": "build_skb_around",
      "external": true,
      "loc": "net/core/skbuff.c:273",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_build_skb_from_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589143552,
      "name": "build_skb_around",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "build_skb_around",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589863552,
      "name": "build_skb_around",
      "external": true,
      "loc": "net/core/skbuff.c:275",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_build_skb_from_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589863552,
      "name": "build_skb_around",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "build_skb_around",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591389088,
      "name": "build_skb_around",
      "external": true,
      "loc": "net/core/skbuff.c:273",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_build_skb_from_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591389088,
      "name": "build_skb_around",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "build_skb_around",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593155232,
      "name": "build_skb_around",
      "external": true,
      "loc": "net/core/skbuff.c:411",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_build_skb_from_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593155232,
      "name": "build_skb_around",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "build_skb_around",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593608768,
      "name": "build_skb_around",
      "external": true,
      "loc": "net/core/skbuff.c:479",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_build_skb_from_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593608768,
      "name": "build_skb_around",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "build_skb_around",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594384672,
      "name": "build_skb_around",
      "external": true,
      "loc": "net/core/skbuff.c:480",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:__xdp_build_skb_from_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594384672,
      "name": "build_skb_around",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "build_skb_around",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501890672,
      "name": "build_skb_around",
      "external": true,
      "loc": "net/core/skbuff.c:343",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501890672,
      "name": "build_skb_around",
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
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "build_skb_around",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234652608,
      "name": "build_skb_around",
      "external": true,
      "loc": "net/core/skbuff.c:343",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234652608,
      "name": "build_skb_around",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "build_skb_around",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295300112,
      "name": "build_skb_around",
      "external": true,
      "loc": "net/core/skbuff.c:343",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295300112,
      "name": "build_skb_around",
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
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "build_skb_around",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278207012,
      "name": "build_skb_around",
      "external": true,
      "loc": "net/core/skbuff.c:343",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278207012,
      "name": "build_skb_around",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "build_skb_around",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587986112,
      "name": "build_skb_around",
      "external": true,
      "loc": "net/core/skbuff.c:343",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587986112,
      "name": "build_skb_around",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "build_skb_around",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587699216,
      "name": "build_skb_around",
      "external": true,
      "loc": "net/core/skbuff.c:343",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587699216,
      "name": "build_skb_around",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "build_skb_around",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588317888,
      "name": "build_skb_around",
      "external": true,
      "loc": "net/core/skbuff.c:343",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588317888,
      "name": "build_skb_around",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
```

```json
{
  "name": "build_skb_around",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588453232,
      "name": "build_skb_around",
      "external": true,
      "loc": "net/core/skbuff.c:343",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588453232,
      "name": "build_skb_around",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct sk_buff * build_skb_around(struct sk_buff * skb, void * data, unsigned int frag_size)
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
