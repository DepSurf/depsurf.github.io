# Function: <code>compress_zstd</code>

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
int compress_zstd(const char * src, size_t slen, char * * dst, size_t * dlen)
```

```json
{
  "name": "compress_zstd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585255760,
      "name": "compress_zstd",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:1319",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585255760,
      "name": "compress_zstd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
int compress_zstd(const char * src, size_t slen, char * * dst, size_t * dlen)
```

```json
{
  "name": "compress_zstd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585989856,
      "name": "compress_zstd",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:1310",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585989856,
      "name": "compress_zstd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
int compress_zstd(const char * src, size_t slen, char * * dst, size_t * dlen)
```

```json
{
  "name": "compress_zstd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586222272,
      "name": "compress_zstd",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:1339",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586222272,
      "name": "compress_zstd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int compress_zstd(const char * src, size_t slen, char * * dst, size_t * dlen)
```

```json
{
  "name": "compress_zstd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586474832,
      "name": "compress_zstd",
      "external": false,
      "loc": "security/apparmor/policy_unpack.c:1373",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_unpack.c:aa_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586474832,
      "name": "compress_zstd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int compress_zstd(const char * src, size_t slen, char * * dst, size_t * dlen)
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
