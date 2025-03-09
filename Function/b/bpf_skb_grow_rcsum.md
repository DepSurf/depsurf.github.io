# Function: <code>bpf_skb_grow_rcsum</code>

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
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587018189,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:2130",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_change_tail"
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
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587147235,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:2287",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_change_tail"
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
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587657918,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:2352",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_change_tail"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int bpf_skb_grow_rcsum(struct sk_buff * skb, unsigned int new_len)
```

```json
{
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587976896,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:2894",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587976896,
      "name": "bpf_skb_grow_rcsum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588136271,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3082",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
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
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588451935,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3217",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int bpf_skb_grow_rcsum(struct sk_buff * skb, unsigned int new_len)
```

```json
{
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588633872,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3219",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588633872,
      "name": "bpf_skb_grow_rcsum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int bpf_skb_grow_rcsum(struct sk_buff * skb, unsigned int new_len)
```

```json
{
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589516672,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3261",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589516672,
      "name": "bpf_skb_grow_rcsum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
int bpf_skb_grow_rcsum(struct sk_buff * skb, unsigned int new_len)
```

```json
{
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589523264,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3668",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589523264,
      "name": "bpf_skb_grow_rcsum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589433831,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3669",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590147223,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3638",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591705886,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3639",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593492238,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3649",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593948656,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3694",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594731440,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3728",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502202652,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3219",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
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
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234952984,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3219",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
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
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295686112,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3219",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
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
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278461218,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3219",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int bpf_skb_grow_rcsum(struct sk_buff * skb, unsigned int new_len)
```

```json
{
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588240608,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3219",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588240608,
      "name": "bpf_skb_grow_rcsum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int bpf_skb_grow_rcsum(struct sk_buff * skb, unsigned int new_len)
```

```json
{
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587953424,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3219",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587953424,
      "name": "bpf_skb_grow_rcsum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int bpf_skb_grow_rcsum(struct sk_buff * skb, unsigned int new_len)
```

```json
{
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588572432,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3219",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588572432,
      "name": "bpf_skb_grow_rcsum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int bpf_skb_grow_rcsum(struct sk_buff * skb, unsigned int new_len)
```

```json
{
  "name": "bpf_skb_grow_rcsum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588709920,
      "name": "bpf_skb_grow_rcsum",
      "external": false,
      "loc": "net/core/filter.c:3219",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588709920,
      "name": "bpf_skb_grow_rcsum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int bpf_skb_grow_rcsum(struct sk_buff * skb, unsigned int new_len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int bpf_skb_grow_rcsum(struct sk_buff * skb, unsigned int new_len)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int bpf_skb_grow_rcsum(struct sk_buff * skb, unsigned int new_len)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int bpf_skb_grow_rcsum(struct sk_buff * skb, unsigned int new_len)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int bpf_skb_grow_rcsum(struct sk_buff * skb, unsigned int new_len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int bpf_skb_grow_rcsum(struct sk_buff * skb, unsigned int new_len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int bpf_skb_grow_rcsum(struct sk_buff * skb, unsigned int new_len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int bpf_skb_grow_rcsum(struct sk_buff * skb, unsigned int new_len)
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
