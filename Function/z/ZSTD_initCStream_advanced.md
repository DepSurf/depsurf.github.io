# Function: <code>ZSTD_initCStream_advanced</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_initCStream_advanced",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584924538,
      "name": "ZSTD_initCStream_advanced",
      "external": false,
      "loc": "lib/zstd/compress.c:3055",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_initCStream_usingCDict"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_initCStream_advanced",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585046223,
      "name": "ZSTD_initCStream_advanced",
      "external": false,
      "loc": "lib/zstd/compress.c:3055",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_initCStream_usingCDict"
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
size_t ZSTD_initCStream_advanced(ZSTD_CStream * zcs, const void * dict, size_t dictSize, ZSTD_parameters params, long long unsigned int pss)
```

```json
{
  "name": "ZSTD_initCStream_advanced",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586299328,
      "name": "ZSTD_initCStream_advanced",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:4029",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586299328,
      "name": "ZSTD_initCStream_advanced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
size_t ZSTD_initCStream_advanced(ZSTD_CStream * zcs, const void * dict, size_t dictSize, ZSTD_parameters params, long long unsigned int pss)
```

```json
{
  "name": "ZSTD_initCStream_advanced",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587304864,
      "name": "ZSTD_initCStream_advanced",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:5145",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587304864,
      "name": "ZSTD_initCStream_advanced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
size_t ZSTD_initCStream_advanced(ZSTD_CStream * zcs, const void * dict, size_t dictSize, ZSTD_parameters params, long long unsigned int pss)
```

```json
{
  "name": "ZSTD_initCStream_advanced",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587569792,
      "name": "ZSTD_initCStream_advanced",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:5145",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587569792,
      "name": "ZSTD_initCStream_advanced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
size_t ZSTD_initCStream_advanced(ZSTD_CStream * zcs, const void * dict, size_t dictSize, ZSTD_parameters params, long long unsigned int pss)
```

```json
{
  "name": "ZSTD_initCStream_advanced",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587904576,
      "name": "ZSTD_initCStream_advanced",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:5145",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587904576,
      "name": "ZSTD_initCStream_advanced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
size_t ZSTD_initCStream_advanced(ZSTD_CStream * zcs, const void * dict, size_t dictSize, ZSTD_parameters params, long long unsigned int pss)
```
</details>
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
