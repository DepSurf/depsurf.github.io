# Function: <code>iovec_from_user</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iovec * iovec_from_user(const struct iovec * uvec, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_iov, bool compat)
```

```json
{
  "name": "iovec_from_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584779568,
      "name": "iovec_from_user",
      "external": true,
      "loc": "lib/iov_iter.c:1705",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "lib/iov_iter.c:__import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584779568,
      "name": "iovec_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct iovec * iovec_from_user(const struct iovec * uvec, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_iov, bool compat)
```

```json
{
  "name": "iovec_from_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584823966,
      "name": "iovec_from_user",
      "external": true,
      "loc": "lib/iov_iter.c:1993",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:__import_iovec"
      ],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "lib/iov_iter.c:__import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788528,
      "name": "iovec_from_user.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071584823888,
      "name": "iovec_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct iovec * iovec_from_user(const struct iovec * uvec, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_iov, bool compat)
```

```json
{
  "name": "iovec_from_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585242126,
      "name": "iovec_from_user",
      "external": true,
      "loc": "lib/iov_iter.c:1851",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:__import_iovec"
      ],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "lib/iov_iter.c:__import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585220928,
      "name": "iovec_from_user.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071585242048,
      "name": "iovec_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct iovec * iovec_from_user(const struct iovec * uvec, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_iov, bool compat)
```

```json
{
  "name": "iovec_from_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586082990,
      "name": "iovec_from_user",
      "external": true,
      "loc": "lib/iov_iter.c:1900",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:__import_iovec"
      ],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "lib/iov_iter.c:__import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586059808,
      "name": "iovec_from_user.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071586082880,
      "name": "iovec_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct iovec * iovec_from_user(const struct iovec * uvec, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_iov, bool compat)
```

```json
{
  "name": "iovec_from_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587063982,
      "name": "iovec_from_user",
      "external": true,
      "loc": "lib/iov_iter.c:1752",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:__import_iovec"
      ],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "lib/iov_iter.c:__import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587044368,
      "name": "iovec_from_user.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071587063856,
      "name": "iovec_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct iovec * iovec_from_user(const struct iovec * uvec, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_iov, bool compat)
```

```json
{
  "name": "iovec_from_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587321964,
      "name": "iovec_from_user",
      "external": true,
      "loc": "lib/iov_iter.c:1384",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:__import_iovec"
      ],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "lib/iov_iter.c:__import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587302016,
      "name": "iovec_from_user.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071587321680,
      "name": "iovec_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct iovec * iovec_from_user(const struct iovec * uvec, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_iov, bool compat)
```

```json
{
  "name": "iovec_from_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587604924,
      "name": "iovec_from_user",
      "external": true,
      "loc": "lib/iov_iter.c:1209",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:__import_iovec"
      ],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw",
        "lib/iov_iter.c:__import_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587589808,
      "name": "iovec_from_user.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071587604784,
      "name": "iovec_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct iovec * iovec_from_user(const struct iovec * uvec, long unsigned int nr_segs, long unsigned int fast_segs, struct iovec * fast_iov, bool compat)
```
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
