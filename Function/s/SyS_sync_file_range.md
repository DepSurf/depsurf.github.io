# Function: <code>SyS_sync_file_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_sync_file_range(long int fd, long long int offset, long long int nbytes, long int flags)
```

```json
{
  "name": "SyS_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581206880,
      "name": "SyS_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:282",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:SyS_sync_file_range2"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206880,
      "name": "SyS_sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_sync_file_range(long int fd, long long int offset, long long int nbytes, long int flags)
```

```json
{
  "name": "SyS_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581371909,
      "name": "SyS_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:282",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:SyS_sync_file_range2"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371552,
      "name": "SyS_sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_sync_file_range(long int fd, long long int offset, long long int nbytes, long int flags)
```

```json
{
  "name": "SyS_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581449701,
      "name": "SyS_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:283",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:SyS_sync_file_range2"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581449344,
      "name": "SyS_sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_sync_file_range(long int fd, long long int offset, long long int nbytes, long int flags)
```

```json
{
  "name": "SyS_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581503797,
      "name": "SyS_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:283",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:SyS_sync_file_range2"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503472,
      "name": "SyS_sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_sync_file_range(long int fd, long long int offset, long long int nbytes, long int flags)
```

```json
{
  "name": "SyS_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581645925,
      "name": "SyS_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:284",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:SyS_sync_file_range2"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581645616,
      "name": "SyS_sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
    }
  ]
}
```
</details>
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
long int SyS_sync_file_range(long int fd, long long int offset, long long int nbytes, long int flags)
```
</details>
</li>
</ul>
