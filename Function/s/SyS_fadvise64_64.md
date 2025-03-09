# Function: <code>SyS_fadvise64_64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_fadvise64_64(long int fd, long long int offset, long long int len, long int advice)
```

```json
{
  "name": "SyS_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580750319,
      "name": "SyS_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:28",
      "file": "mm/fadvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749664,
      "name": "SyS_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
long int SyS_fadvise64_64(long int fd, long long int offset, long long int len, long int advice)
```

```json
{
  "name": "SyS_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580869519,
      "name": "SyS_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:28",
      "file": "mm/fadvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:SyS_fadvise64"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580868832,
      "name": "SyS_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
long int SyS_fadvise64_64(long int fd, long long int offset, long long int len, long int advice)
```

```json
{
  "name": "SyS_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580937439,
      "name": "SyS_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:28",
      "file": "mm/fadvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:SyS_fadvise64"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936736,
      "name": "SyS_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
long int SyS_fadvise64_64(long int fd, long long int offset, long long int len, long int advice)
```

```json
{
  "name": "SyS_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580981423,
      "name": "SyS_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:28",
      "file": "mm/fadvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:SyS_fadvise64"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980736,
      "name": "SyS_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 643
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
long int SyS_fadvise64_64(long int fd, long long int offset, long long int len, long int advice)
```

```json
{
  "name": "SyS_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581084143,
      "name": "SyS_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:29",
      "file": "mm/fadvise.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/fadvise.c:SyS_fadvise64"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581083472,
      "name": "SyS_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
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
long int SyS_fadvise64_64(long int fd, long long int offset, long long int len, long int advice)
```
</details>
</li>
</ul>
