# Function: <code>devlink_alloc</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct devlink * devlink_alloc(const struct devlink_ops * ops, size_t priv_size)
```

```json
{
  "name": "devlink_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_alloc",
      "external": true,
      "loc": "net/core/devlink.c:5512",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588619510,
      "name": "devlink_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071588607728,
      "name": "devlink_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct devlink * devlink_alloc(const struct devlink_ops * ops, size_t priv_size)
```

```json
{
  "name": "devlink_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588831440,
      "name": "devlink_alloc",
      "external": true,
      "loc": "net/core/devlink.c:6168",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588831440,
      "name": "devlink_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
struct devlink * devlink_alloc(const struct devlink_ops * ops, size_t priv_size)
```

```json
{
  "name": "devlink_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589683040,
      "name": "devlink_alloc",
      "external": true,
      "loc": "net/core/devlink.c:7098",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589683040,
      "name": "devlink_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct devlink * devlink_alloc(const struct devlink_ops * ops, size_t priv_size)
```

```json
{
  "name": "devlink_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589712704,
      "name": "devlink_alloc",
      "external": true,
      "loc": "net/core/devlink.c:7968",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589712704,
      "name": "devlink_alloc.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    },
    {
      "addr": 18446744071589713040,
      "name": "devlink_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct devlink * devlink_alloc(const struct devlink_ops * ops, size_t priv_size)
```

```json
{
  "name": "devlink_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589575632,
      "name": "devlink_alloc",
      "external": true,
      "loc": "net/core/devlink.c:8187",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589575632,
      "name": "devlink_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
    }
  ]
}
```
</details>
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
struct devlink * devlink_alloc(const struct devlink_ops * ops, size_t priv_size)
```

```json
{
  "name": "devlink_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502367440,
      "name": "devlink_alloc",
      "external": true,
      "loc": "net/core/devlink.c:6168",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502367440,
      "name": "devlink_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
struct devlink * devlink_alloc(const struct devlink_ops * ops, size_t priv_size)
```

```json
{
  "name": "devlink_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235123576,
      "name": "devlink_alloc",
      "external": true,
      "loc": "net/core/devlink.c:6168",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235123576,
      "name": "devlink_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct devlink * devlink_alloc(const struct devlink_ops * ops, size_t priv_size)
```

```json
{
  "name": "devlink_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295951440,
      "name": "devlink_alloc",
      "external": true,
      "loc": "net/core/devlink.c:6168",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295951440,
      "name": "devlink_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct devlink * devlink_alloc(const struct devlink_ops * ops, size_t priv_size)
```

```json
{
  "name": "devlink_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278591064,
      "name": "devlink_alloc",
      "external": true,
      "loc": "net/core/devlink.c:6168",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278591064,
      "name": "devlink_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct devlink * devlink_alloc(const struct devlink_ops * ops, size_t priv_size)
```

```json
{
  "name": "devlink_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588437824,
      "name": "devlink_alloc",
      "external": true,
      "loc": "net/core/devlink.c:6168",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588437824,
      "name": "devlink_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
struct devlink * devlink_alloc(const struct devlink_ops * ops, size_t priv_size)
```

```json
{
  "name": "devlink_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588150512,
      "name": "devlink_alloc",
      "external": true,
      "loc": "net/core/devlink.c:6168",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588150512,
      "name": "devlink_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
struct devlink * devlink_alloc(const struct devlink_ops * ops, size_t priv_size)
```

```json
{
  "name": "devlink_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588770000,
      "name": "devlink_alloc",
      "external": true,
      "loc": "net/core/devlink.c:6168",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588770000,
      "name": "devlink_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
struct devlink * devlink_alloc(const struct devlink_ops * ops, size_t priv_size)
```

```json
{
  "name": "devlink_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588910528,
      "name": "devlink_alloc",
      "external": true,
      "loc": "net/core/devlink.c:6168",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588910528,
      "name": "devlink_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
struct devlink * devlink_alloc(const struct devlink_ops * ops, size_t priv_size)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
struct devlink * devlink_alloc(const struct devlink_ops * ops, size_t priv_size)
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
