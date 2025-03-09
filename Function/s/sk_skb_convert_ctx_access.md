# Function: <code>sk_skb_convert_ctx_access</code>

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
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587641008,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:4446",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587641008,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587969232,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:6598",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587969232,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588121200,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:7399",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588121200,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588440864,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:8220",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588440864,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588647392,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:8307",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588647392,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589509008,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:8621",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589509008,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589512672,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:9489",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589512672,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589411568,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:9635",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589411568,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590120416,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:9789",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590120416,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
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
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591704512,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:10296",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591704512,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593457552,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:10501",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593457552,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593923536,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:10651",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593923536,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
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
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594706880,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:10742",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594706880,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502191576,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:8307",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502191576,
      "name": "sk_skb_convert_ctx_access",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234939140,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:8307",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234939140,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295674736,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:8307",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295674736,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278446996,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:8307",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278446996,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588254128,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:8307",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588254128,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587966944,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:8307",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587966944,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588585952,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:8307",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588585952,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
```

```json
{
  "name": "sk_skb_convert_ctx_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588723440,
      "name": "sk_skb_convert_ctx_access",
      "external": false,
      "loc": "net/core/filter.c:8307",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588723440,
      "name": "sk_skb_convert_ctx_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn * si, struct bpf_insn * insn_buf, struct bpf_prog * prog, u32 * target_size)
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
