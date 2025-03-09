# Function: <code>sk_storage_alloc</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588622884,
      "name": "sk_storage_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:324",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:sk_storage_update"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int sk_storage_alloc(struct sock * sk, struct bpf_sk_storage_map * smap, struct bpf_sk_storage_elem * first_selem)
```

```json
{
  "name": "sk_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588843728,
      "name": "sk_storage_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:326",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588843728,
      "name": "sk_storage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
  "name": "sk_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589732533,
      "name": "sk_storage_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:327",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589729328,
      "name": "sk_storage_alloc.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int sk_storage_alloc(struct sock * sk, struct bpf_sk_storage_map * smap, struct bpf_sk_storage_elem * first_selem)
```

```json
{
  "name": "sk_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502417928,
      "name": "sk_storage_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:326",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502417928,
      "name": "sk_storage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "sk_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235155468,
      "name": "sk_storage_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:326",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235153564,
      "name": "sk_storage_alloc.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int sk_storage_alloc(struct sock * sk, struct bpf_sk_storage_map * smap, struct bpf_sk_storage_elem * first_selem)
```

```json
{
  "name": "sk_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295969888,
      "name": "sk_storage_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:326",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295969888,
      "name": "sk_storage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
int sk_storage_alloc(struct sock * sk, struct bpf_sk_storage_map * smap, struct bpf_sk_storage_elem * first_selem)
```

```json
{
  "name": "sk_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278622738,
      "name": "sk_storage_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:326",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278622738,
      "name": "sk_storage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
int sk_storage_alloc(struct sock * sk, struct bpf_sk_storage_map * smap, struct bpf_sk_storage_elem * first_selem)
```

```json
{
  "name": "sk_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588450112,
      "name": "sk_storage_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:326",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588450112,
      "name": "sk_storage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int sk_storage_alloc(struct sock * sk, struct bpf_sk_storage_map * smap, struct bpf_sk_storage_elem * first_selem)
```

```json
{
  "name": "sk_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588162800,
      "name": "sk_storage_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:326",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588162800,
      "name": "sk_storage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int sk_storage_alloc(struct sock * sk, struct bpf_sk_storage_map * smap, struct bpf_sk_storage_elem * first_selem)
```

```json
{
  "name": "sk_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588782288,
      "name": "sk_storage_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:326",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588782288,
      "name": "sk_storage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int sk_storage_alloc(struct sock * sk, struct bpf_sk_storage_map * smap, struct bpf_sk_storage_elem * first_selem)
```

```json
{
  "name": "sk_storage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588922880,
      "name": "sk_storage_alloc",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:326",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:sk_storage_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588922880,
      "name": "sk_storage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int sk_storage_alloc(struct sock * sk, struct bpf_sk_storage_map * smap, struct bpf_sk_storage_elem * first_selem)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int sk_storage_alloc(struct sock * sk, struct bpf_sk_storage_map * smap, struct bpf_sk_storage_elem * first_selem)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int sk_storage_alloc(struct sock * sk, struct bpf_sk_storage_map * smap, struct bpf_sk_storage_elem * first_selem)
```
</details>
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
