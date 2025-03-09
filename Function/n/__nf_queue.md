# Function: <code>__nf_queue</code>

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
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587160550,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:110",
      "file": "net/netfilter/nf_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
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
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587291895,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:113",
      "file": "net/netfilter/nf_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
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
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587813353,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:114",
      "file": "net/netfilter/nf_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
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
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588156373,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:142",
      "file": "net/netfilter/nf_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
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
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588339589,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:158",
      "file": "net/netfilter/nf_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
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
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588739749,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:158",
      "file": "net/netfilter/nf_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
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
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588963541,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:158",
      "file": "net/netfilter/nf_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
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
int __nf_queue(struct sk_buff * skb, const struct nf_hook_state * state, unsigned int index, unsigned int queuenum)
```

```json
{
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589918608,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:155",
      "file": "net/netfilter/nf_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_queue.c:nf_reinject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589918608,
      "name": "__nf_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 677
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
int __nf_queue(struct sk_buff * skb, const struct nf_hook_state * state, unsigned int index, unsigned int queuenum)
```

```json
{
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589959552,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:155",
      "file": "net/netfilter/nf_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_queue.c:nf_reinject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589959552,
      "name": "__nf_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 677
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
int __nf_queue(struct sk_buff * skb, const struct nf_hook_state * state, unsigned int index, unsigned int queuenum)
```

```json
{
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589874320,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:155",
      "file": "net/netfilter/nf_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_queue.c:nf_reinject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589874320,
      "name": "__nf_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 677
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __nf_queue(struct sk_buff * skb, const struct nf_hook_state * state, unsigned int index, unsigned int queuenum)
```

```json
{
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:158",
      "file": "net/netfilter/nf_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_queue.c:nf_reinject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590637728,
      "name": "__nf_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 803
    },
    {
      "addr": 18446744071592713222,
      "name": "__nf_queue.cold",
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __nf_queue(struct sk_buff * skb, const struct nf_hook_state * state, unsigned int index, unsigned int queuenum)
```

```json
{
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:158",
      "file": "net/netfilter/nf_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_queue.c:nf_reinject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592261600,
      "name": "__nf_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 827
    },
    {
      "addr": 18446744071594599241,
      "name": "__nf_queue.cold",
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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __nf_queue(struct sk_buff * skb, const struct nf_hook_state * state, unsigned int index, unsigned int queuenum)
```

```json
{
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:158",
      "file": "net/netfilter/nf_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_queue.c:nf_reinject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594096176,
      "name": "__nf_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 827
    },
    {
      "addr": 18446744071596334996,
      "name": "__nf_queue.cold",
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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int __nf_queue(struct sk_buff * skb, const struct nf_hook_state * state, unsigned int index, unsigned int queuenum)
```

```json
{
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:158",
      "file": "net/netfilter/nf_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_queue.c:nf_reinject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594481280,
      "name": "__nf_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
    },
    {
      "addr": 18446744071596864666,
      "name": "__nf_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int __nf_queue(struct sk_buff * skb, const struct nf_hook_state * state, unsigned int index, unsigned int queuenum)
```

```json
{
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:156",
      "file": "net/netfilter/nf_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_queue.c:nf_reinject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595283440,
      "name": "__nf_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 910
    },
    {
      "addr": 18446744071597789739,
      "name": "__nf_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502566308,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:158",
      "file": "net/netfilter/nf_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
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
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235272588,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:158",
      "file": "net/netfilter/nf_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
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
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296148680,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:158",
      "file": "net/netfilter/nf_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
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
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278724822,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:158",
      "file": "net/netfilter/nf_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
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
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588569925,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:158",
      "file": "net/netfilter/nf_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
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
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588281909,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:158",
      "file": "net/netfilter/nf_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
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
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588902101,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:158",
      "file": "net/netfilter/nf_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
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
  "name": "__nf_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589044661,
      "name": "__nf_queue",
      "external": false,
      "loc": "net/netfilter/nf_queue.c:158",
      "file": "net/netfilter/nf_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
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
int __nf_queue(struct sk_buff * skb, const struct nf_hook_state * state, unsigned int index, unsigned int queuenum)
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
