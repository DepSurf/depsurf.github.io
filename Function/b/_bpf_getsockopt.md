# Function: <code>_bpf_getsockopt</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int _bpf_getsockopt(struct sock * sk, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "_bpf_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589502592,
      "name": "_bpf_getsockopt",
      "external": false,
      "loc": "net/core/filter.c:4463",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_ops_getsockopt",
        "net/core/filter.c:bpf_sock_addr_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589502592,
      "name": "_bpf_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
int _bpf_getsockopt(struct sock * sk, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "_bpf_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589504992,
      "name": "_bpf_getsockopt",
      "external": false,
      "loc": "net/core/filter.c:4923",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_ops_getsockopt",
        "net/core/filter.c:bpf_sock_addr_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589504992,
      "name": "_bpf_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
int _bpf_getsockopt(struct sock * sk, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "_bpf_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589402976,
      "name": "_bpf_getsockopt",
      "external": false,
      "loc": "net/core/filter.c:4879",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_ops_getsockopt",
        "net/core/filter.c:bpf_sock_addr_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589402976,
      "name": "_bpf_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
int _bpf_getsockopt(struct sock * sk, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "_bpf_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_bpf_getsockopt",
      "external": false,
      "loc": "net/core/filter.c:4963",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_ops_getsockopt",
        "net/core/filter.c:bpf_sock_addr_getsockopt",
        "net/core/filter.c:bpf_sk_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590172176,
      "name": "_bpf_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
    },
    {
      "addr": 18446744071592703755,
      "name": "_bpf_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int _bpf_getsockopt(struct sock * sk, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "_bpf_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_bpf_getsockopt",
      "external": false,
      "loc": "net/core/filter.c:5263",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sock_ops_getsockopt",
        "net/core/filter.c:bpf_sock_addr_getsockopt",
        "net/core/filter.c:bpf_sk_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591737296,
      "name": "_bpf_getsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 629
    },
    {
      "addr": 18446744071594590303,
      "name": "_bpf_getsockopt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
  "name": "_bpf_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593517665,
      "name": "_bpf_getsockopt",
      "external": false,
      "loc": "net/core/filter.c:5334",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_ops_getsockopt",
        "net/core/filter.c:bpf_sock_addr_getsockopt",
        "net/core/filter.c:bpf_sk_getsockopt"
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
  "name": "_bpf_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593984961,
      "name": "_bpf_getsockopt",
      "external": false,
      "loc": "net/core/filter.c:5388",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_ops_getsockopt",
        "net/core/filter.c:bpf_sock_addr_getsockopt",
        "net/core/filter.c:bpf_sk_getsockopt"
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
  "name": "_bpf_getsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594768977,
      "name": "_bpf_getsockopt",
      "external": false,
      "loc": "net/core/filter.c:5462",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_sock_ops_getsockopt",
        "net/core/filter.c:bpf_sock_addr_getsockopt",
        "net/core/filter.c:bpf_sk_getsockopt"
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
int _bpf_getsockopt(struct sock * sk, int level, int optname, char * optval, int optlen)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int _bpf_getsockopt(struct sock * sk, int level, int optname, char * optval, int optlen)
```
</details>
</li>
</ul>
