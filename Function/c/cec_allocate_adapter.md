# Function: <code>cec_allocate_adapter</code>

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
struct cec_adapter * cec_allocate_adapter(const struct cec_adap_ops * ops, void * priv, const char * name, u32 caps, u8 available_las)
```

```json
{
  "name": "cec_allocate_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587248048,
      "name": "cec_allocate_adapter",
      "external": true,
      "loc": "drivers/media/cec/cec-core.c:251",
      "file": "drivers/media/cec/cec-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587248048,
      "name": "cec_allocate_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 621
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct cec_adapter * cec_allocate_adapter(const struct cec_adap_ops * ops, void * priv, const char * name, u32 caps, u8 available_las)
```

```json
{
  "name": "cec_allocate_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_allocate_adapter",
      "external": true,
      "loc": "drivers/media/cec/cec-core.c:253",
      "file": "drivers/media/cec/cec-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587516163,
      "name": "cec_allocate_adapter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071587514832,
      "name": "cec_allocate_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct cec_adapter * cec_allocate_adapter(const struct cec_adap_ops * ops, void * priv, const char * name, u32 caps, u8 available_las)
```

```json
{
  "name": "cec_allocate_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_allocate_adapter",
      "external": true,
      "loc": "drivers/media/cec/cec-core.c:253",
      "file": "drivers/media/cec/cec-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587719248,
      "name": "cec_allocate_adapter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071587717888,
      "name": "cec_allocate_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
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
struct cec_adapter * cec_allocate_adapter(const struct cec_adap_ops * ops, void * priv, const char * name, u32 caps, u8 available_las)
```

```json
{
  "name": "cec_allocate_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500893888,
      "name": "cec_allocate_adapter",
      "external": true,
      "loc": "drivers/media/cec/cec-core.c:253",
      "file": "drivers/media/cec/cec-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-pin.c:cec_pin_allocate_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500893888,
      "name": "cec_allocate_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
struct cec_adapter * cec_allocate_adapter(const struct cec_adap_ops * ops, void * priv, const char * name, u32 caps, u8 available_las)
```

```json
{
  "name": "cec_allocate_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233412932,
      "name": "cec_allocate_adapter",
      "external": true,
      "loc": "drivers/media/cec/cec-core.c:253",
      "file": "drivers/media/cec/cec-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233412932,
      "name": "cec_allocate_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
struct cec_adapter * cec_allocate_adapter(const struct cec_adap_ops * ops, void * priv, const char * name, u32 caps, u8 available_las)
```

```json
{
  "name": "cec_allocate_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294350432,
      "name": "cec_allocate_adapter",
      "external": true,
      "loc": "drivers/media/cec/cec-core.c:253",
      "file": "drivers/media/cec/cec-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294350432,
      "name": "cec_allocate_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
struct cec_adapter * cec_allocate_adapter(const struct cec_adap_ops * ops, void * priv, const char * name, u32 caps, u8 available_las)
```

```json
{
  "name": "cec_allocate_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277674944,
      "name": "cec_allocate_adapter",
      "external": true,
      "loc": "drivers/media/cec/cec-core.c:253",
      "file": "drivers/media/cec/cec-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277674944,
      "name": "cec_allocate_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct cec_adapter * cec_allocate_adapter(const struct cec_adap_ops * ops, void * priv, const char * name, u32 caps, u8 available_las)
```

```json
{
  "name": "cec_allocate_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_allocate_adapter",
      "external": true,
      "loc": "drivers/media/cec/cec-core.c:253",
      "file": "drivers/media/cec/cec-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587360192,
      "name": "cec_allocate_adapter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071587358832,
      "name": "cec_allocate_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct cec_adapter * cec_allocate_adapter(const struct cec_adap_ops * ops, void * priv, const char * name, u32 caps, u8 available_las)
```

```json
{
  "name": "cec_allocate_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_allocate_adapter",
      "external": true,
      "loc": "drivers/media/cec/cec-core.c:253",
      "file": "drivers/media/cec/cec-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587128416,
      "name": "cec_allocate_adapter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071587127056,
      "name": "cec_allocate_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct cec_adapter * cec_allocate_adapter(const struct cec_adap_ops * ops, void * priv, const char * name, u32 caps, u8 available_las)
```

```json
{
  "name": "cec_allocate_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_allocate_adapter",
      "external": true,
      "loc": "drivers/media/cec/cec-core.c:253",
      "file": "drivers/media/cec/cec-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587675392,
      "name": "cec_allocate_adapter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071587674032,
      "name": "cec_allocate_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct cec_adapter * cec_allocate_adapter(const struct cec_adap_ops * ops, void * priv, const char * name, u32 caps, u8 available_las)
```

```json
{
  "name": "cec_allocate_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_allocate_adapter",
      "external": true,
      "loc": "drivers/media/cec/cec-core.c:253",
      "file": "drivers/media/cec/cec-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-pin.c:cec_pin_allocate_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587781776,
      "name": "cec_allocate_adapter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071587780416,
      "name": "cec_allocate_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
struct cec_adapter * cec_allocate_adapter(const struct cec_adap_ops * ops, void * priv, const char * name, u32 caps, u8 available_las)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct cec_adapter * cec_allocate_adapter(const struct cec_adap_ops * ops, void * priv, const char * name, u32 caps, u8 available_las)
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
