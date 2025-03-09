# Function: <code>aa_label_strn_parse</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583339232,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1859",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/secid.c:apparmor_secctx_to_secid",
        "security/apparmor/label.c:aa_label_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583339232,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1122
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583457904,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1860",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:aa_label_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583457904,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1122
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583643552,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1856",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:aa_label_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583643552,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1141
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583749840,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1885",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:aa_label_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583749840,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1141
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584138304,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1882",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/secid.c:apparmor_secctx_to_secid",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/net.c:apparmor_secmark_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584138304,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1566
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584256752,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1882",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/secid.c:apparmor_secctx_to_secid",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/net.c:apparmor_secmark_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584256752,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1584
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584281696,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1882",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/secid.c:apparmor_secctx_to_secid",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/net.c:apparmor_secmark_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584281696,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1644
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584667776,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1882",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/secid.c:apparmor_secctx_to_secid",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/net.c:apparmor_secmark_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584667776,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1644
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1891",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/secid.c:apparmor_secctx_to_secid",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/net.c:apparmor_secmark_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594088186,
      "name": "aa_label_strn_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585326416,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1849
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586066720,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1885",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/secid.c:apparmor_secctx_to_secid",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/net.c:apparmor_secmark_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586066720,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1845
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586301584,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1885",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/secid.c:apparmor_secctx_to_secid",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/net.c:apparmor_secmark_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586301584,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1827
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586558176,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1891",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/secid.c:apparmor_secctx_to_secid",
        "security/apparmor/label.c:aa_label_parse",
        "security/apparmor/net.c:apparmor_secmark_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586558176,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1826
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495549344,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1885",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:aa_label_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495549344,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1076
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228913100,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1885",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:aa_label_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228913100,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1188
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289637296,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1885",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:aa_label_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289637296,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1504
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274721510,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1885",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:aa_label_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274721510,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 824
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583718576,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1885",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:aa_label_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718576,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1141
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583655632,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1885",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:aa_label_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583655632,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1141
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583702352,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1885",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:aa_label_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583702352,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1141
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
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```

```json
{
  "name": "aa_label_strn_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583802640,
      "name": "aa_label_strn_parse",
      "external": true,
      "loc": "security/apparmor/label.c:1885",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:aa_label_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583802640,
      "name": "aa_label_strn_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1141
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct aa_label * aa_label_strn_parse(struct aa_label * base, const char * str, size_t n, gfp_t gfp, bool create, bool force_stack)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
