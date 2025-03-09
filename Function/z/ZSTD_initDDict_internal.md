# Function: <code>ZSTD_initDDict_internal</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
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
size_t ZSTD_initDDict_internal(ZSTD_DDict * ddict, const void * dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType)
```

```json
{
  "name": "ZSTD_initDDict_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586514112,
      "name": "ZSTD_initDDict_internal",
      "external": false,
      "loc": "lib/zstd/decompress/zstd_ddict.c:117",
      "file": "lib/zstd/decompress/zstd_ddict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_initStaticDDict",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_byReference",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_advanced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586514112,
      "name": "ZSTD_initDDict_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
size_t ZSTD_initDDict_internal(ZSTD_DDict * ddict, const void * dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType)
```

```json
{
  "name": "ZSTD_initDDict_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587710496,
      "name": "ZSTD_initDDict_internal",
      "external": false,
      "loc": "lib/zstd/decompress/zstd_ddict.c:117",
      "file": "lib/zstd/decompress/zstd_ddict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_initStaticDDict",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_byReference",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_advanced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587710496,
      "name": "ZSTD_initDDict_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
size_t ZSTD_initDDict_internal(ZSTD_DDict * ddict, const void * dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType)
```

```json
{
  "name": "ZSTD_initDDict_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587976064,
      "name": "ZSTD_initDDict_internal",
      "external": false,
      "loc": "lib/zstd/decompress/zstd_ddict.c:117",
      "file": "lib/zstd/decompress/zstd_ddict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_initStaticDDict",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_byReference",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_advanced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587976064,
      "name": "ZSTD_initDDict_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
size_t ZSTD_initDDict_internal(ZSTD_DDict * ddict, const void * dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType)
```

```json
{
  "name": "ZSTD_initDDict_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588310848,
      "name": "ZSTD_initDDict_internal",
      "external": false,
      "loc": "lib/zstd/decompress/zstd_ddict.c:117",
      "file": "lib/zstd/decompress/zstd_ddict.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_initStaticDDict",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_byReference",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_advanced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588310848,
      "name": "ZSTD_initDDict_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
size_t ZSTD_initDDict_internal(ZSTD_DDict * ddict, const void * dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType)
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
