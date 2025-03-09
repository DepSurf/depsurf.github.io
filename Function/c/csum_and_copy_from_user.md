# Function: <code>csum_and_copy_from_user</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
__wsum csum_and_copy_from_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```

```json
{
  "name": "csum_and_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585124800,
      "name": "csum_and_copy_from_user",
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
      "addr": 18446744071585124800,
      "name": "csum_and_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
__wsum csum_and_copy_from_user(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_and_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585275952,
      "name": "csum_and_copy_from_user",
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
      "addr": 18446744071585275952,
      "name": "csum_and_copy_from_user",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
__wsum csum_and_copy_from_user(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_and_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585159456,
      "name": "csum_and_copy_from_user",
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
      "addr": 18446744071585159456,
      "name": "csum_and_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
__wsum csum_and_copy_from_user(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_and_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585612304,
      "name": "csum_and_copy_from_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:24",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585612304,
      "name": "csum_and_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
__wsum csum_and_copy_from_user(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_and_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586769008,
      "name": "csum_and_copy_from_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:24",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586769008,
      "name": "csum_and_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
__wsum csum_and_copy_from_user(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_and_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595934096,
      "name": "csum_and_copy_from_user",
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
      "addr": 18446744071595934096,
      "name": "csum_and_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
__wsum csum_and_copy_from_user(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_and_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596452480,
      "name": "csum_and_copy_from_user",
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
      "addr": 18446744071596452480,
      "name": "csum_and_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
__wsum csum_and_copy_from_user(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_and_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597347520,
      "name": "csum_and_copy_from_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:22",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:csum_and_copy_from_iter_full",
        "net/core/skbuff.c:csum_and_copy_from_iter_full"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597347520,
      "name": "csum_and_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "csum_and_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496119968,
      "name": "csum_and_copy_from_user",
      "external": false,
      "loc": "include/net/checksum.h:26",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "csum_and_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229444680,
      "name": "csum_and_copy_from_user",
      "external": false,
      "loc": "include/net/checksum.h:26",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
__wsum csum_and_copy_from_user(const void * src, void * dst, int len, __wsum sum, int * err_ptr)
```

```json
{
  "name": "csum_and_copy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282859856,
      "name": "csum_and_copy_from_user",
      "external": true,
      "loc": "arch/powerpc/lib/checksum_wrappers.c:14",
      "file": "arch/powerpc/lib/checksum_wrappers.c",
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
      "addr": 13835058055282859856,
      "name": "csum_and_copy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "csum_and_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275182208,
      "name": "csum_and_copy_from_user",
      "external": false,
      "loc": "include/net/checksum.h:26",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
__wsum csum_and_copy_from_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
__wsum csum_and_copy_from_user(const void * src, void * dst, int len, __wsum sum, int * err_ptr)
```
</details>
</li>
</ul>
