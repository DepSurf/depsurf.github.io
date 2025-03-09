# Function: <code>FSE_count_parallel_wksp</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t FSE_count_parallel_wksp(unsigned int * count, unsigned int * maxSymbolValuePtr, const void * source, size_t sourceSize, unsigned int checkMax, const unsigned int * workSpace)
```

```json
{
  "name": "FSE_count_parallel_wksp",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584794556,
      "name": "FSE_count_parallel_wksp",
      "external": false,
      "loc": "lib/zstd/fse_compress.c:357",
      "file": "lib/zstd/fse_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_compress.c:FSE_count_wksp"
      ],
      "caller_func": [
        "lib/zstd/fse_compress.c:FSE_count_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584791168,
      "name": "FSE_count_parallel_wksp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t FSE_count_parallel_wksp(unsigned int * count, unsigned int * maxSymbolValuePtr, const void * source, size_t sourceSize, unsigned int checkMax, const unsigned int * workSpace)
```

```json
{
  "name": "FSE_count_parallel_wksp",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584907969,
      "name": "FSE_count_parallel_wksp",
      "external": false,
      "loc": "lib/zstd/fse_compress.c:357",
      "file": "lib/zstd/fse_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_compress.c:FSE_count_wksp"
      ],
      "caller_func": [
        "lib/zstd/fse_compress.c:FSE_count_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584904576,
      "name": "FSE_count_parallel_wksp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
    }
  ]
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
size_t FSE_count_parallel_wksp(unsigned int * count, unsigned int * maxSymbolValuePtr, const void * source, size_t sourceSize, unsigned int checkMax, const unsigned int * workSpace)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
size_t FSE_count_parallel_wksp(unsigned int * count, unsigned int * maxSymbolValuePtr, const void * source, size_t sourceSize, unsigned int checkMax, const unsigned int * workSpace)
```
</details>
</li>
</ul>
