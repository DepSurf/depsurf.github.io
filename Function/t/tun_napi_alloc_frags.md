# Function: <code>tun_napi_alloc_frags</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586180319,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1292",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
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
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586441616,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1480",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
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
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586588150,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1471",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
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
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586841400,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1462",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
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
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586992872,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1462",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
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
struct sk_buff * tun_napi_alloc_frags(struct tun_file * tfile, size_t len, const struct iov_iter * it)
```

```json
{
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587804320,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1427",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587804320,
      "name": "tun_napi_alloc_frags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
struct sk_buff * tun_napi_alloc_frags(struct tun_file * tfile, size_t len, const struct iov_iter * it)
```

```json
{
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587862080,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1358",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587862080,
      "name": "tun_napi_alloc_frags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
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
struct sk_buff * tun_napi_alloc_frags(struct tun_file * tfile, size_t len, const struct iov_iter * it)
```

```json
{
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587740336,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1369",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587740336,
      "name": "tun_napi_alloc_frags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
struct sk_buff * tun_napi_alloc_frags(struct tun_file * tfile, size_t len, const struct iov_iter * it)
```

```json
{
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588335584,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1425",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588335584,
      "name": "tun_napi_alloc_frags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 627
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
struct sk_buff * tun_napi_alloc_frags(struct tun_file * tfile, size_t len, const struct iov_iter * it)
```

```json
{
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589734848,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1453",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589734848,
      "name": "tun_napi_alloc_frags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 800
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
struct sk_buff * tun_napi_alloc_frags(struct tun_file * tfile, size_t len, const struct iov_iter * it)
```

```json
{
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591358080,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1455",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591358080,
      "name": "tun_napi_alloc_frags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
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
struct sk_buff * tun_napi_alloc_frags(struct tun_file * tfile, size_t len, const struct iov_iter * it)
```

```json
{
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591718672,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1460",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591718672,
      "name": "tun_napi_alloc_frags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 859
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
struct sk_buff * tun_napi_alloc_frags(struct tun_file * tfile, size_t len, const struct iov_iter * it)
```

```json
{
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592462384,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1461",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592462384,
      "name": "tun_napi_alloc_frags",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 830
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
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499987820,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1462",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
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
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232515780,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1462",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
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
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293311224,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1462",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
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
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277062704,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1462",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
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
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586749896,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1462",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
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
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586617112,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1462",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
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
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586947432,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1462",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
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
  "name": "tun_napi_alloc_frags",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587047016,
      "name": "tun_napi_alloc_frags",
      "external": false,
      "loc": "drivers/net/tun.c:1462",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user"
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
struct sk_buff * tun_napi_alloc_frags(struct tun_file * tfile, size_t len, const struct iov_iter * it)
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
