# Function: <code>run_bpf_filter</code>

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
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588154189,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:223",
      "file": "net/core/sock_reuseport.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
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
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588475372,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:225",
      "file": "net/core/sock_reuseport.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
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
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588680796,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:225",
      "file": "net/core/sock_reuseport.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
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
struct sock * run_bpf_filter(struct sock_reuseport * reuse, u16 socks, struct bpf_prog * prog, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589546672,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:217",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589546672,
      "name": "run_bpf_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
struct sock * run_bpf_filter(struct sock_reuseport * reuse, u16 socks, struct bpf_prog * prog, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589555696,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:217",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589555696,
      "name": "run_bpf_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
struct sock * run_bpf_filter(struct sock_reuseport * reuse, u16 socks, struct bpf_prog * prog, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589453424,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:217",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589453424,
      "name": "run_bpf_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
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
struct sock * run_bpf_filter(struct sock_reuseport * reuse, u16 socks, struct bpf_prog * prog, struct sk_buff * skb, int hdr_len)
```

```json
{
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590189312,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:412",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590189312,
      "name": "run_bpf_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591753158,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:412",
      "file": "net/core/sock_reuseport.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593543000,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:498",
      "file": "net/core/sock_reuseport.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594012072,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:498",
      "file": "net/core/sock_reuseport.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594798440,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:498",
      "file": "net/core/sock_reuseport.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502234328,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:225",
      "file": "net/core/sock_reuseport.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
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
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234980256,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:225",
      "file": "net/core/sock_reuseport.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
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
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295725208,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:225",
      "file": "net/core/sock_reuseport.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
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
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278477116,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:225",
      "file": "net/core/sock_reuseport.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
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
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588287532,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:225",
      "file": "net/core/sock_reuseport.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
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
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588000348,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:225",
      "file": "net/core/sock_reuseport.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
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
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588619356,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:225",
      "file": "net/core/sock_reuseport.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
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
  "name": "run_bpf_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588757159,
      "name": "run_bpf_filter",
      "external": false,
      "loc": "net/core/sock_reuseport.c:225",
      "file": "net/core/sock_reuseport.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_select_sock"
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
struct sock * run_bpf_filter(struct sock_reuseport * reuse, u16 socks, struct bpf_prog * prog, struct sk_buff * skb, int hdr_len)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct sock * run_bpf_filter(struct sock_reuseport * reuse, u16 socks, struct bpf_prog * prog, struct sk_buff * skb, int hdr_len)
```
</details>
</li>
</ul>
