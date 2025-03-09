# Function: <code>bpf_sk_storage_clone</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int bpf_sk_storage_clone(const struct sock * sk, struct sock * newsk)
```

```json
{
  "name": "bpf_sk_storage_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588846560,
      "name": "bpf_sk_storage_clone",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:773",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588846560,
      "name": "bpf_sk_storage_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int bpf_sk_storage_clone(const struct sock * sk, struct sock * newsk)
```

```json
{
  "name": "bpf_sk_storage_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589732208,
      "name": "bpf_sk_storage_clone",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:777",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589732208,
      "name": "bpf_sk_storage_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
int bpf_sk_storage_clone(const struct sock * sk, struct sock * newsk)
```

```json
{
  "name": "bpf_sk_storage_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589766224,
      "name": "bpf_sk_storage_clone",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:187",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589766224,
      "name": "bpf_sk_storage_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
int bpf_sk_storage_clone(const struct sock * sk, struct sock * newsk)
```

```json
{
  "name": "bpf_sk_storage_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589669808,
      "name": "bpf_sk_storage_clone",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:187",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589669808,
      "name": "bpf_sk_storage_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
int bpf_sk_storage_clone(const struct sock * sk, struct sock * newsk)
```

```json
{
  "name": "bpf_sk_storage_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590426752,
      "name": "bpf_sk_storage_clone",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:187",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590426752,
      "name": "bpf_sk_storage_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int bpf_sk_storage_clone(const struct sock * sk, struct sock * newsk)
```

```json
{
  "name": "bpf_sk_storage_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592026208,
      "name": "bpf_sk_storage_clone",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:189",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592026208,
      "name": "bpf_sk_storage_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
int bpf_sk_storage_clone(const struct sock * sk, struct sock * newsk)
```

```json
{
  "name": "bpf_sk_storage_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593842224,
      "name": "bpf_sk_storage_clone",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:160",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593842224,
      "name": "bpf_sk_storage_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
int bpf_sk_storage_clone(const struct sock * sk, struct sock * newsk)
```

```json
{
  "name": "bpf_sk_storage_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594216576,
      "name": "bpf_sk_storage_clone",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:154",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594216576,
      "name": "bpf_sk_storage_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
int bpf_sk_storage_clone(const struct sock * sk, struct sock * newsk)
```

```json
{
  "name": "bpf_sk_storage_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595013952,
      "name": "bpf_sk_storage_clone",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:154",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595013952,
      "name": "bpf_sk_storage_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
int bpf_sk_storage_clone(const struct sock * sk, struct sock * newsk)
```

```json
{
  "name": "bpf_sk_storage_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502420096,
      "name": "bpf_sk_storage_clone",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:773",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502420096,
      "name": "bpf_sk_storage_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int bpf_sk_storage_clone(const struct sock * sk, struct sock * newsk)
```

```json
{
  "name": "bpf_sk_storage_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235155180,
      "name": "bpf_sk_storage_clone",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:773",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235155180,
      "name": "bpf_sk_storage_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int bpf_sk_storage_clone(const struct sock * sk, struct sock * newsk)
```

```json
{
  "name": "bpf_sk_storage_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295972752,
      "name": "bpf_sk_storage_clone",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:773",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295972752,
      "name": "bpf_sk_storage_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int bpf_sk_storage_clone(const struct sock * sk, struct sock * newsk)
```

```json
{
  "name": "bpf_sk_storage_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278625306,
      "name": "bpf_sk_storage_clone",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:773",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278625306,
      "name": "bpf_sk_storage_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int bpf_sk_storage_clone(const struct sock * sk, struct sock * newsk)
```

```json
{
  "name": "bpf_sk_storage_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588452944,
      "name": "bpf_sk_storage_clone",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:773",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588452944,
      "name": "bpf_sk_storage_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int bpf_sk_storage_clone(const struct sock * sk, struct sock * newsk)
```

```json
{
  "name": "bpf_sk_storage_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588165632,
      "name": "bpf_sk_storage_clone",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:773",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588165632,
      "name": "bpf_sk_storage_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int bpf_sk_storage_clone(const struct sock * sk, struct sock * newsk)
```

```json
{
  "name": "bpf_sk_storage_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588785120,
      "name": "bpf_sk_storage_clone",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:773",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588785120,
      "name": "bpf_sk_storage_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int bpf_sk_storage_clone(const struct sock * sk, struct sock * newsk)
```

```json
{
  "name": "bpf_sk_storage_clone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588925744,
      "name": "bpf_sk_storage_clone",
      "external": true,
      "loc": "net/core/bpf_sk_storage.c:773",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clone_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588925744,
      "name": "bpf_sk_storage_clone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int bpf_sk_storage_clone(const struct sock * sk, struct sock * newsk)
```
</details>
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
