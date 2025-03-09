# Function: <code>_bpf_setsockopt</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int _bpf_setsockopt(struct sock * sk, int level, int optname, char * optval, int optlen, u32 flags)
```

```json
{
  "name": "_bpf_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_bpf_setsockopt",
      "external": false,
      "loc": "net/core/filter.c:4288",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_ops_setsockopt",
        "net/core/filter.c:bpf_sock_addr_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589502976,
      "name": "_bpf_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1039
    },
    {
      "addr": 18446744071589540373,
      "name": "_bpf_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int _bpf_setsockopt(struct sock * sk, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "_bpf_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_bpf_setsockopt",
      "external": false,
      "loc": "net/core/filter.c:4693",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_ops_setsockopt",
        "net/core/filter.c:bpf_sock_addr_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589505360,
      "name": "_bpf_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1525
    },
    {
      "addr": 18446744071591630689,
      "name": "_bpf_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int _bpf_setsockopt(struct sock * sk, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "_bpf_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_bpf_setsockopt",
      "external": false,
      "loc": "net/core/filter.c:4642",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_ops_setsockopt",
        "net/core/filter.c:bpf_sock_addr_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589403472,
      "name": "_bpf_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1544
    },
    {
      "addr": 18446744071591574122,
      "name": "_bpf_setsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int _bpf_setsockopt(struct sock * sk, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "_bpf_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_bpf_setsockopt",
      "external": false,
      "loc": "net/core/filter.c:4724",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_ops_setsockopt",
        "net/core/filter.c:bpf_sock_addr_setsockopt",
        "net/core/filter.c:bpf_sk_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590170160,
      "name": "_bpf_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1638
    },
    {
      "addr": 18446744071592703671,
      "name": "_bpf_setsockopt.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int _bpf_setsockopt(struct sock * sk, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "_bpf_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_bpf_setsockopt",
      "external": false,
      "loc": "net/core/filter.c:5017",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_ops_setsockopt",
        "net/core/filter.c:bpf_sock_addr_setsockopt",
        "net/core/filter.c:bpf_sk_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591732992,
      "name": "_bpf_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1696
    },
    {
      "addr": 18446744071594590219,
      "name": "_bpf_setsockopt.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_bpf_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593512762,
      "name": "_bpf_setsockopt",
      "external": false,
      "loc": "net/core/filter.c:5297",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_ops_setsockopt",
        "net/core/filter.c:bpf_sock_addr_setsockopt",
        "net/core/filter.c:bpf_sk_setsockopt"
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
  "name": "_bpf_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593973306,
      "name": "_bpf_setsockopt",
      "external": false,
      "loc": "net/core/filter.c:5351",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_ops_setsockopt",
        "net/core/filter.c:bpf_sock_addr_setsockopt",
        "net/core/filter.c:bpf_sk_setsockopt"
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
  "name": "_bpf_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594757354,
      "name": "_bpf_setsockopt",
      "external": false,
      "loc": "net/core/filter.c:5425",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_ops_setsockopt",
        "net/core/filter.c:bpf_sock_addr_setsockopt",
        "net/core/filter.c:bpf_sk_setsockopt"
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int _bpf_setsockopt(struct sock * sk, int level, int optname, char * optval, int optlen, u32 flags)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int _bpf_setsockopt(struct sock * sk, int level, int optname, char * optval, int optlen)
```
</details>
</li>
</ul>
