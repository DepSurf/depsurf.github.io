# Function: <code>tcp_fastopen_no_cookie</code>

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
bool tcp_fastopen_no_cookie(const struct sock * sk, const struct dst_entry * dst, int flag)
```

```json
{
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588021280,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:312",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588021280,
      "name": "tcp_fastopen_no_cookie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool tcp_fastopen_no_cookie(const struct sock * sk, const struct dst_entry * dst, int flag)
```

```json
{
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588372336,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:312",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588372336,
      "name": "tcp_fastopen_no_cookie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
bool tcp_fastopen_no_cookie(const struct sock * sk, const struct dst_entry * dst, int flag)
```

```json
{
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588562704,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:312",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588562704,
      "name": "tcp_fastopen_no_cookie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
bool tcp_fastopen_no_cookie(const struct sock * sk, const struct dst_entry * dst, int flag)
```

```json
{
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588973824,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:325",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588973824,
      "name": "tcp_fastopen_no_cookie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589200386,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:325",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
bool tcp_fastopen_no_cookie(const struct sock * sk, const struct dst_entry * dst, int flag)
```

```json
{
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590169664,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:348",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590169664,
      "name": "tcp_fastopen_no_cookie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
bool tcp_fastopen_no_cookie(const struct sock * sk, const struct dst_entry * dst, int flag)
```

```json
{
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590218816,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:348",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590218816,
      "name": "tcp_fastopen_no_cookie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
bool tcp_fastopen_no_cookie(const struct sock * sk, const struct dst_entry * dst, int flag)
```

```json
{
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590132912,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:348",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590132912,
      "name": "tcp_fastopen_no_cookie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590914601,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:337",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592556117,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:331",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594415605,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:332",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594804949,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:334",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595616149,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:334",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502820348,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:325",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool tcp_fastopen_no_cookie(const struct sock * sk, const struct dst_entry * dst, int flag)
```

```json
{
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235519796,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:325",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235519796,
      "name": "tcp_fastopen_no_cookie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296467920,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:325",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278934452,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:325",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588806770,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:325",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588518706,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:325",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589242946,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:325",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
  "name": "tcp_fastopen_no_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589283506,
      "name": "tcp_fastopen_no_cookie",
      "external": false,
      "loc": "net/ipv4/tcp_fastopen.c:325",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_check",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
bool tcp_fastopen_no_cookie(const struct sock * sk, const struct dst_entry * dst, int flag)
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
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
bool tcp_fastopen_no_cookie(const struct sock * sk, const struct dst_entry * dst, int flag)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool tcp_fastopen_no_cookie(const struct sock * sk, const struct dst_entry * dst, int flag)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
bool tcp_fastopen_no_cookie(const struct sock * sk, const struct dst_entry * dst, int flag)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
bool tcp_fastopen_no_cookie(const struct sock * sk, const struct dst_entry * dst, int flag)
```
</details>
</li>
</ul>
