# Function: <code>check_cached_key</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct key * check_cached_key(struct keyring_search_context * ctx)
```

```json
{
  "name": "check_cached_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583242800,
      "name": "check_cached_key",
      "external": false,
      "loc": "security/keys/request_key.c:22",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583242800,
      "name": "check_cached_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
struct key * check_cached_key(struct keyring_search_context * ctx)
```

```json
{
  "name": "check_cached_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583348624,
      "name": "check_cached_key",
      "external": false,
      "loc": "security/keys/request_key.c:22",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583348624,
      "name": "check_cached_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
struct key * check_cached_key(struct keyring_search_context * ctx)
```

```json
{
  "name": "check_cached_key",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583684797,
      "name": "check_cached_key",
      "external": false,
      "loc": "security/keys/request_key.c:22",
      "file": "security/keys/request_key.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:request_key_rcu"
      ],
      "caller_func": [
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583684528,
      "name": "check_cached_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
struct key * check_cached_key(struct keyring_search_context * ctx)
```

```json
{
  "name": "check_cached_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583806160,
      "name": "check_cached_key",
      "external": false,
      "loc": "security/keys/request_key.c:22",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583806160,
      "name": "check_cached_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
struct key * check_cached_key(struct keyring_search_context * ctx)
```

```json
{
  "name": "check_cached_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583830416,
      "name": "check_cached_key",
      "external": false,
      "loc": "security/keys/request_key.c:22",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583830416,
      "name": "check_cached_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
struct key * check_cached_key(struct keyring_search_context * ctx)
```

```json
{
  "name": "check_cached_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584193536,
      "name": "check_cached_key",
      "external": false,
      "loc": "security/keys/request_key.c:22",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584193536,
      "name": "check_cached_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
struct key * check_cached_key(struct keyring_search_context * ctx)
```

```json
{
  "name": "check_cached_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584794768,
      "name": "check_cached_key",
      "external": false,
      "loc": "security/keys/request_key.c:22",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584794768,
      "name": "check_cached_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
struct key * check_cached_key(struct keyring_search_context * ctx)
```

```json
{
  "name": "check_cached_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585492368,
      "name": "check_cached_key",
      "external": false,
      "loc": "security/keys/request_key.c:22",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585492368,
      "name": "check_cached_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
struct key * check_cached_key(struct keyring_search_context * ctx)
```

```json
{
  "name": "check_cached_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585723776,
      "name": "check_cached_key",
      "external": false,
      "loc": "security/keys/request_key.c:22",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585723776,
      "name": "check_cached_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
struct key * check_cached_key(struct keyring_search_context * ctx)
```

```json
{
  "name": "check_cached_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585970960,
      "name": "check_cached_key",
      "external": false,
      "loc": "security/keys/request_key.c:22",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585970960,
      "name": "check_cached_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
struct key * check_cached_key(struct keyring_search_context * ctx)
```

```json
{
  "name": "check_cached_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495092760,
      "name": "check_cached_key",
      "external": false,
      "loc": "security/keys/request_key.c:22",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495092760,
      "name": "check_cached_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
struct key * check_cached_key(struct keyring_search_context * ctx)
```

```json
{
  "name": "check_cached_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228486220,
      "name": "check_cached_key",
      "external": false,
      "loc": "security/keys/request_key.c:22",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228486220,
      "name": "check_cached_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
struct key * check_cached_key(struct keyring_search_context * ctx)
```

```json
{
  "name": "check_cached_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288994000,
      "name": "check_cached_key",
      "external": false,
      "loc": "security/keys/request_key.c:22",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288994000,
      "name": "check_cached_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
struct key * check_cached_key(struct keyring_search_context * ctx)
```

```json
{
  "name": "check_cached_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274354740,
      "name": "check_cached_key",
      "external": false,
      "loc": "security/keys/request_key.c:22",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274354740,
      "name": "check_cached_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
struct key * check_cached_key(struct keyring_search_context * ctx)
```

```json
{
  "name": "check_cached_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583317360,
      "name": "check_cached_key",
      "external": false,
      "loc": "security/keys/request_key.c:22",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583317360,
      "name": "check_cached_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
struct key * check_cached_key(struct keyring_search_context * ctx)
```

```json
{
  "name": "check_cached_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583254464,
      "name": "check_cached_key",
      "external": false,
      "loc": "security/keys/request_key.c:22",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583254464,
      "name": "check_cached_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
  "name": "check_cached_key",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "check_cached_key",
      "external": false,
      "loc": "security/keys/request_key.c:22",
      "file": "security/keys/request_key.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct key * check_cached_key(struct keyring_search_context * ctx)
```

```json
{
  "name": "check_cached_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583396016,
      "name": "check_cached_key",
      "external": false,
      "loc": "security/keys/request_key.c:22",
      "file": "security/keys/request_key.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583396016,
      "name": "check_cached_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct key * check_cached_key(struct keyring_search_context * ctx)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
struct key * check_cached_key(struct keyring_search_context * ctx)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
