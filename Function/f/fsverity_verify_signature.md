# Function: <code>fsverity_verify_signature</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int fsverity_verify_signature(const struct fsverity_info * vi, const struct fsverity_descriptor * desc, size_t desc_size)
```

```json
{
  "name": "fsverity_verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_verify_signature",
      "external": true,
      "loc": "fs/verity/signature.c:37",
      "file": "fs/verity/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582325700,
      "name": "fsverity_verify_signature.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071582325376,
      "name": "fsverity_verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int fsverity_verify_signature(const struct fsverity_info * vi, const struct fsverity_descriptor * desc, size_t desc_size)
```

```json
{
  "name": "fsverity_verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_verify_signature",
      "external": true,
      "loc": "fs/verity/signature.c:40",
      "file": "fs/verity/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582615092,
      "name": "fsverity_verify_signature.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071582614768,
      "name": "fsverity_verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int fsverity_verify_signature(const struct fsverity_info * vi, const struct fsverity_descriptor * desc, size_t desc_size)
```

```json
{
  "name": "fsverity_verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_verify_signature",
      "external": true,
      "loc": "fs/verity/signature.c:40",
      "file": "fs/verity/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591344251,
      "name": "fsverity_verify_signature.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071582686320,
      "name": "fsverity_verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int fsverity_verify_signature(const struct fsverity_info * vi, const u8 * signature, size_t sig_size)
```

```json
{
  "name": "fsverity_verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_verify_signature",
      "external": true,
      "loc": "fs/verity/signature.c:40",
      "file": "fs/verity/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591287039,
      "name": "fsverity_verify_signature.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582716320,
      "name": "fsverity_verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int fsverity_verify_signature(const struct fsverity_info * vi, const u8 * signature, size_t sig_size)
```

```json
{
  "name": "fsverity_verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_verify_signature",
      "external": true,
      "loc": "fs/verity/signature.c:40",
      "file": "fs/verity/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592243976,
      "name": "fsverity_verify_signature.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071583043216,
      "name": "fsverity_verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int fsverity_verify_signature(const struct fsverity_info * vi, const u8 * signature, size_t sig_size)
```

```json
{
  "name": "fsverity_verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_verify_signature",
      "external": true,
      "loc": "fs/verity/signature.c:40",
      "file": "fs/verity/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594023027,
      "name": "fsverity_verify_signature.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071583518672,
      "name": "fsverity_verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int fsverity_verify_signature(const struct fsverity_info * vi, const u8 * signature, size_t sig_size)
```

```json
{
  "name": "fsverity_verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584117520,
      "name": "fsverity_verify_signature",
      "external": true,
      "loc": "fs/verity/signature.c:40",
      "file": "fs/verity/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584117520,
      "name": "fsverity_verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
int fsverity_verify_signature(const struct fsverity_info * vi, const u8 * signature, size_t sig_size)
```

```json
{
  "name": "fsverity_verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584344288,
      "name": "fsverity_verify_signature",
      "external": true,
      "loc": "fs/verity/signature.c:48",
      "file": "fs/verity/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584344288,
      "name": "fsverity_verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
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
int fsverity_verify_signature(const struct fsverity_info * vi, const u8 * signature, size_t sig_size)
```

```json
{
  "name": "fsverity_verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584562624,
      "name": "fsverity_verify_signature",
      "external": true,
      "loc": "fs/verity/signature.c:48",
      "file": "fs/verity/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584562624,
      "name": "fsverity_verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
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
int fsverity_verify_signature(const struct fsverity_info * vi, const struct fsverity_descriptor * desc, size_t desc_size)
```

```json
{
  "name": "fsverity_verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493906752,
      "name": "fsverity_verify_signature",
      "external": true,
      "loc": "fs/verity/signature.c:37",
      "file": "fs/verity/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493906752,
      "name": "fsverity_verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
int fsverity_verify_signature(const struct fsverity_info * vi, const struct fsverity_descriptor * desc, size_t desc_size)
```

```json
{
  "name": "fsverity_verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227385276,
      "name": "fsverity_verify_signature",
      "external": true,
      "loc": "fs/verity/signature.c:37",
      "file": "fs/verity/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227385276,
      "name": "fsverity_verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
int fsverity_verify_signature(const struct fsverity_info * vi, const struct fsverity_descriptor * desc, size_t desc_size)
```

```json
{
  "name": "fsverity_verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287544784,
      "name": "fsverity_verify_signature",
      "external": true,
      "loc": "fs/verity/signature.c:37",
      "file": "fs/verity/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287544784,
      "name": "fsverity_verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
int fsverity_verify_signature(const struct fsverity_info * vi, const struct fsverity_descriptor * desc, size_t desc_size)
```

```json
{
  "name": "fsverity_verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273462498,
      "name": "fsverity_verify_signature",
      "external": true,
      "loc": "fs/verity/signature.c:37",
      "file": "fs/verity/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273462498,
      "name": "fsverity_verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
int fsverity_verify_signature(const struct fsverity_info * vi, const struct fsverity_descriptor * desc, size_t desc_size)
```

```json
{
  "name": "fsverity_verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_verify_signature",
      "external": true,
      "loc": "fs/verity/signature.c:37",
      "file": "fs/verity/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582294436,
      "name": "fsverity_verify_signature.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071582294112,
      "name": "fsverity_verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int fsverity_verify_signature(const struct fsverity_info * vi, const struct fsverity_descriptor * desc, size_t desc_size)
```

```json
{
  "name": "fsverity_verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_verify_signature",
      "external": true,
      "loc": "fs/verity/signature.c:37",
      "file": "fs/verity/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232196,
      "name": "fsverity_verify_signature.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071582231872,
      "name": "fsverity_verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int fsverity_verify_signature(const struct fsverity_info * vi, const struct fsverity_descriptor * desc, size_t desc_size)
```

```json
{
  "name": "fsverity_verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_verify_signature",
      "external": true,
      "loc": "fs/verity/signature.c:37",
      "file": "fs/verity/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582284916,
      "name": "fsverity_verify_signature.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071582284592,
      "name": "fsverity_verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int fsverity_verify_signature(const struct fsverity_info * vi, const struct fsverity_descriptor * desc, size_t desc_size)
```

```json
{
  "name": "fsverity_verify_signature",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_verify_signature",
      "external": true,
      "loc": "fs/verity/signature.c:37",
      "file": "fs/verity/signature.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582363508,
      "name": "fsverity_verify_signature.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071582363184,
      "name": "fsverity_verify_signature",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int fsverity_verify_signature(const struct fsverity_info * vi, const struct fsverity_descriptor * desc, size_t desc_size)
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const u8 * signature</code>
</li>
<li>
<b>Param added. </b>
<code>size_t sig_size</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct fsverity_descriptor * desc</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t desc_size</code>
</li>
</ul>
</details>
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
