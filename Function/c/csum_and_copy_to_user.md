# Function: <code>csum_and_copy_to_user</code>

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
__wsum csum_and_copy_to_user(const void * src, void * dst, int len, __wsum isum, int * errp)
```

```json
{
  "name": "csum_and_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585125040,
      "name": "csum_and_copy_to_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:85",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585125040,
      "name": "csum_and_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
__wsum csum_and_copy_to_user(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_and_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585275824,
      "name": "csum_and_copy_to_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:49",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585275824,
      "name": "csum_and_copy_to_user",
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
__wsum csum_and_copy_to_user(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_and_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585159360,
      "name": "csum_and_copy_to_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:49",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585159360,
      "name": "csum_and_copy_to_user",
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
__wsum csum_and_copy_to_user(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_and_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585612208,
      "name": "csum_and_copy_to_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:49",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585612208,
      "name": "csum_and_copy_to_user",
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
__wsum csum_and_copy_to_user(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_and_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586769104,
      "name": "csum_and_copy_to_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:48",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586769104,
      "name": "csum_and_copy_to_user",
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
__wsum csum_and_copy_to_user(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_and_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595934208,
      "name": "csum_and_copy_to_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:48",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595934208,
      "name": "csum_and_copy_to_user",
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
__wsum csum_and_copy_to_user(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_and_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596452608,
      "name": "csum_and_copy_to_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:48",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596452608,
      "name": "csum_and_copy_to_user",
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
__wsum csum_and_copy_to_user(const void * src, void * dst, int len)
```

```json
{
  "name": "csum_and_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597347648,
      "name": "csum_and_copy_to_user",
      "external": true,
      "loc": "arch/x86/lib/csum-wrappers_64.c:44",
      "file": "arch/x86/lib/csum-wrappers_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:csum_and_copy_to_iter",
        "net/core/datagram.c:csum_and_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597347648,
      "name": "csum_and_copy_to_user",
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
  "name": "csum_and_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496129888,
      "name": "csum_and_copy_to_user",
      "external": false,
      "loc": "include/net/checksum.h:40",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
      ],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496113328,
      "name": "csum_and_copy_to_user.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
  "name": "csum_and_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229452560,
      "name": "csum_and_copy_to_user",
      "external": false,
      "loc": "include/net/checksum.h:40",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter"
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
__wsum csum_and_copy_to_user(const void * src, void * dst, int len, __wsum sum, int * err_ptr)
```

```json
{
  "name": "csum_and_copy_to_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282859424,
      "name": "csum_and_copy_to_user",
      "external": true,
      "loc": "arch/powerpc/lib/checksum_wrappers.c:57",
      "file": "arch/powerpc/lib/checksum_wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282859424,
      "name": "csum_and_copy_to_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
  "name": "csum_and_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275188924,
      "name": "csum_and_copy_to_user",
      "external": false,
      "loc": "include/net/checksum.h:40",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter"
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
__wsum csum_and_copy_to_user(const void * src, void * dst, int len, __wsum isum, int * errp)
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
__wsum csum_and_copy_to_user(const void * src, void * dst, int len, __wsum sum, int * err_ptr)
```
</details>
</li>
</ul>
