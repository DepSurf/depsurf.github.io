# Function: <code>sk_lookup</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588121424,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5018",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_sk_lookup",
        "net/core/filter.c:__bpf_sk_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588121424,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588440928,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5198",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588440928,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588647456,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5207",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588647456,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589510112,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5334",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589510112,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589514640,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5886",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589514640,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589413584,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5988",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589413584,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:6112",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590140832,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
    },
    {
      "addr": 18446744071592702073,
      "name": "sk_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:6420",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591693392,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
    },
    {
      "addr": 18446744071594588641,
      "name": "sk_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:6434",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593485152,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
    },
    {
      "addr": 18446744071596327040,
      "name": "sk_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:6513",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593950320,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
    },
    {
      "addr": 18446744071596857297,
      "name": "sk_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:6603",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594733120,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
    },
    {
      "addr": 18446744071597782294,
      "name": "sk_lookup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502191728,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5207",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502191728,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
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
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234939248,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5207",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234939248,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295674832,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5207",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295674832,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278447112,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5207",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278447112,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588254192,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5207",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588254192,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587967008,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5207",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587967008,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588586016,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5207",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588586016,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```

```json
{
  "name": "sk_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588723504,
      "name": "sk_lookup",
      "external": false,
      "loc": "net/core/filter.c:5207",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:__bpf_skc_lookup",
        "net/core/filter.c:__bpf_skc_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588723504,
      "name": "sk_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct sock * sk_lookup(struct net * net, struct bpf_sock_tuple * tuple, int dif, int sdif, u8 family, u8 proto)
```
</details>
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
