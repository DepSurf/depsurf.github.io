# Function: <code>sk_psock_bpf_run</code>

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
  "name": "sk_psock_bpf_run",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588174957,
      "name": "sk_psock_bpf_run",
      "external": false,
      "loc": "net/core/skmsg.c:640",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read"
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
  "name": "sk_psock_bpf_run",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588501936,
      "name": "sk_psock_bpf_run",
      "external": false,
      "loc": "net/core/skmsg.c:652",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588501936,
      "name": "sk_psock_bpf_run.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
  "name": "sk_psock_bpf_run",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588710336,
      "name": "sk_psock_bpf_run",
      "external": false,
      "loc": "net/core/skmsg.c:661",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588710336,
      "name": "sk_psock_bpf_run.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_psock_bpf_run",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589579971,
      "name": "sk_psock_bpf_run",
      "external": false,
      "loc": "net/core/skmsg.c:660",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read"
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
  "name": "sk_psock_bpf_run",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589590619,
      "name": "sk_psock_bpf_run",
      "external": false,
      "loc": "net/core/skmsg.c:747",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_verdict_recv",
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read"
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sk_psock_bpf_run",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502276744,
      "name": "sk_psock_bpf_run",
      "external": false,
      "loc": "net/core/skmsg.c:661",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502276744,
      "name": "sk_psock_bpf_run.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int sk_psock_bpf_run(struct sk_psock * psock, struct bpf_prog * prog, struct sk_buff * skb)
```

```json
{
  "name": "sk_psock_bpf_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235014520,
      "name": "sk_psock_bpf_run",
      "external": false,
      "loc": "net/core/skmsg.c:661",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235014520,
      "name": "sk_psock_bpf_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int sk_psock_bpf_run(struct sk_psock * psock, struct bpf_prog * prog, struct sk_buff * skb)
```

```json
{
  "name": "sk_psock_bpf_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295770032,
      "name": "sk_psock_bpf_run",
      "external": false,
      "loc": "net/core/skmsg.c:661",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295770032,
      "name": "sk_psock_bpf_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int sk_psock_bpf_run(struct sk_psock * psock, struct bpf_prog * prog, struct sk_buff * skb)
```

```json
{
  "name": "sk_psock_bpf_run",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278507090,
      "name": "sk_psock_bpf_run",
      "external": false,
      "loc": "net/core/skmsg.c:661",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278507090,
      "name": "sk_psock_bpf_run",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
  "name": "sk_psock_bpf_run",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588317072,
      "name": "sk_psock_bpf_run",
      "external": false,
      "loc": "net/core/skmsg.c:661",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588317072,
      "name": "sk_psock_bpf_run.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
  "name": "sk_psock_bpf_run",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588029856,
      "name": "sk_psock_bpf_run",
      "external": false,
      "loc": "net/core/skmsg.c:661",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588029856,
      "name": "sk_psock_bpf_run.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
  "name": "sk_psock_bpf_run",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588648896,
      "name": "sk_psock_bpf_run",
      "external": false,
      "loc": "net/core/skmsg.c:661",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588648896,
      "name": "sk_psock_bpf_run.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
  "name": "sk_psock_bpf_run",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588788624,
      "name": "sk_psock_bpf_run",
      "external": false,
      "loc": "net/core/skmsg.c:661",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_strp_parse",
        "net/core/skmsg.c:sk_psock_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588788624,
      "name": "sk_psock_bpf_run.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int sk_psock_bpf_run(struct sk_psock * psock, struct bpf_prog * prog, struct sk_buff * skb)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int sk_psock_bpf_run(struct sk_psock * psock, struct bpf_prog * prog, struct sk_buff * skb)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int sk_psock_bpf_run(struct sk_psock * psock, struct bpf_prog * prog, struct sk_buff * skb)
```
</details>
</li>
</ul>
