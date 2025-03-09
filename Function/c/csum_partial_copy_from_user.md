# Function: <code>csum_partial_copy_from_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
__wsum csum_partial_copy_from_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```

```json
{
  "name": "csum_partial_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587330928,
      "name": "csum_partial_copy_from_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:23",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587330928,
      "name": "csum_partial_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
__wsum csum_partial_copy_from_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```

```json
{
  "name": "csum_partial_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587829296,
      "name": "csum_partial_copy_from_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:24",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587829296,
      "name": "csum_partial_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
__wsum csum_partial_copy_from_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```

```json
{
  "name": "csum_partial_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588044608,
      "name": "csum_partial_copy_from_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:24",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588044608,
      "name": "csum_partial_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
__wsum csum_partial_copy_from_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```

```json
{
  "name": "csum_partial_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588264720,
      "name": "csum_partial_copy_from_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:24",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588264720,
      "name": "csum_partial_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
__wsum csum_partial_copy_from_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```

```json
{
  "name": "csum_partial_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588817248,
      "name": "csum_partial_copy_from_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:24",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588817248,
      "name": "csum_partial_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
__wsum csum_partial_copy_from_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```

```json
{
  "name": "csum_partial_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589195392,
      "name": "csum_partial_copy_from_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:24",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589195392,
      "name": "csum_partial_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
__wsum csum_partial_copy_from_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```

```json
{
  "name": "csum_partial_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589436848,
      "name": "csum_partial_copy_from_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:24",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589436848,
      "name": "csum_partial_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
__wsum csum_partial_copy_from_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```

```json
{
  "name": "csum_partial_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589894864,
      "name": "csum_partial_copy_from_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:24",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589894864,
      "name": "csum_partial_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
__wsum csum_partial_copy_from_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```

```json
{
  "name": "csum_partial_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590120816,
      "name": "csum_partial_copy_from_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:24",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590120816,
      "name": "csum_partial_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
__wsum csum_partial_copy_from_user(const void * src, void * dst, int len, __wsum sum, int * csum_err)
```

```json
{
  "name": "csum_partial_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496325400,
      "name": "csum_partial_copy_from_user",
      "external": true,
      "loc": "lib/checksum.c:152",
      "file": "lib/checksum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496325400,
      "name": "csum_partial_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
  "name": "csum_partial_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "csum_partial_copy_from_user",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236417184,
      "name": "csum_partial_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
__wsum csum_partial_copy_from_user(const void * src, void * dst, int len, __wsum sum, int * csum_err)
```

```json
{
  "name": "csum_partial_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275377126,
      "name": "csum_partial_copy_from_user",
      "external": true,
      "loc": "lib/checksum.c:152",
      "file": "lib/checksum.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275377126,
      "name": "csum_partial_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
__wsum csum_partial_copy_from_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```

```json
{
  "name": "csum_partial_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589723072,
      "name": "csum_partial_copy_from_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:24",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589723072,
      "name": "csum_partial_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
__wsum csum_partial_copy_from_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```

```json
{
  "name": "csum_partial_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589448848,
      "name": "csum_partial_copy_from_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:24",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589448848,
      "name": "csum_partial_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
__wsum csum_partial_copy_from_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```

```json
{
  "name": "csum_partial_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590166448,
      "name": "csum_partial_copy_from_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:24",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590166448,
      "name": "csum_partial_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
__wsum csum_partial_copy_from_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```

```json
{
  "name": "csum_partial_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590216960,
      "name": "csum_partial_copy_from_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:24",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590216960,
      "name": "csum_partial_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
__wsum csum_partial_copy_from_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>__wsum sum</code>
</li>
<li>
<b>Param added. </b>
<code>int * csum_err</code>
</li>
<li>
<b>Param removed. </b>
<code>__wsum isum</code>
</li>
<li>
<b>Param removed. </b>
<code>int * errp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
__wsum csum_partial_copy_from_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
__wsum csum_partial_copy_from_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>__wsum sum</code>
</li>
<li>
<b>Param added. </b>
<code>int * csum_err</code>
</li>
<li>
<b>Param removed. </b>
<code>__wsum isum</code>
</li>
<li>
<b>Param removed. </b>
<code>int * errp</code>
</li>
</ul>
</details>
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
