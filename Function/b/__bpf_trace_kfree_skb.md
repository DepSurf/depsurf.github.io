# Function: <code>__bpf_trace_kfree_skb</code>

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
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588034016,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:15",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588034016,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588201664,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:15",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588201664,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588529104,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:15",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588529104,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588737632,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:15",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588737632,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589605936,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:15",
      "file": "net/core/net-traces.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589605936,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589620944,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:15",
      "file": "net/core/net-traces.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589620944,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589509488,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:15",
      "file": "net/core/net-traces.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589509488,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590250992,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:15",
      "file": "net/core/net-traces.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590250992,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location, enum skb_drop_reason reason)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591838128,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:101",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591838128,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location, enum skb_drop_reason reason)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593636352,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:24",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593636352,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location, enum skb_drop_reason reason)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594112448,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:24",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594112448,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location, enum skb_drop_reason reason)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594907088,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:24",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594907088,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502299912,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:15",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502299912,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235042704,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:15",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235042704,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295811232,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:15",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295811232,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588344368,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:15",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588344368,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588057072,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:15",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588057072,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588676192,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:15",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588676192,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location)
```

```json
{
  "name": "__bpf_trace_kfree_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588816080,
      "name": "__bpf_trace_kfree_skb",
      "external": false,
      "loc": "include/trace/events/skb.h:15",
      "file": "net/core/net-traces.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588816080,
      "name": "__bpf_trace_kfree_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum skb_drop_reason reason</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __bpf_trace_kfree_skb(void * __data, struct sk_buff * skb, void * location)
```
</details>
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
