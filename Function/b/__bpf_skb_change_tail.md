# Function: <code>__bpf_skb_change_tail</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587977109,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:2910",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588135829,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3098",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
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
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588451477,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3233",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588658037,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3235",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589522789,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3277",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589529761,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3684",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __bpf_skb_change_tail(struct sk_buff * skb, u32 new_len, u64 flags)
```

```json
{
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589433472,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3685",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589433472,
      "name": "__bpf_skb_change_tail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int __bpf_skb_change_tail(struct sk_buff * skb, u32 new_len, u64 flags)
```

```json
{
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590146864,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3654",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590146864,
      "name": "__bpf_skb_change_tail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __bpf_skb_change_tail(struct sk_buff * skb, u32 new_len, u64 flags)
```

```json
{
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591705488,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3655",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591705488,
      "name": "__bpf_skb_change_tail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __bpf_skb_change_tail(struct sk_buff * skb, u32 new_len, u64 flags)
```

```json
{
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593491840,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3665",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593491840,
      "name": "__bpf_skb_change_tail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __bpf_skb_change_tail(struct sk_buff * skb, u32 new_len, u64 flags)
```

```json
{
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593948256,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3710",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593948256,
      "name": "__bpf_skb_change_tail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __bpf_skb_change_tail(struct sk_buff * skb, u32 new_len, u64 flags)
```

```json
{
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594731040,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3744",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594731040,
      "name": "__bpf_skb_change_tail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
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
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502202172,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3235",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
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
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234952592,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3235",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
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
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295685512,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3235",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
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
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278460944,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3235",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588264773,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3235",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587977589,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3235",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588596597,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3235",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_skb_change_tail",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588734261,
      "name": "__bpf_skb_change_tail",
      "external": false,
      "loc": "net/core/filter.c:3235",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:sk_skb_change_tail",
        "net/core/filter.c:bpf_skb_change_tail",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int __bpf_skb_change_tail(struct sk_buff * skb, u32 new_len, u64 flags)
```
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
