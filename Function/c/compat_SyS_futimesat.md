# Function: <code>compat_SyS_futimesat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int compat_SyS_futimesat(long int dfd, long int filename, long int t)
```

```json
{
  "name": "compat_SyS_futimesat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581352544,
      "name": "compat_SyS_futimesat",
      "external": true,
      "loc": "fs/compat.c:105",
      "file": "fs/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat.c:compat_SyS_utimes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581352544,
      "name": "compat_SyS_futimesat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
long int compat_SyS_futimesat(long int dfd, long int filename, long int t)
```

```json
{
  "name": "compat_SyS_futimesat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581533857,
      "name": "compat_SyS_futimesat",
      "external": true,
      "loc": "fs/compat.c:105",
      "file": "fs/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat.c:compat_SyS_utimes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581533584,
      "name": "compat_SyS_futimesat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
long int compat_SyS_futimesat(long int dfd, long int filename, long int t)
```

```json
{
  "name": "compat_SyS_futimesat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581619793,
      "name": "compat_SyS_futimesat",
      "external": true,
      "loc": "fs/compat.c:91",
      "file": "fs/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/compat.c:compat_SyS_utimes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581619520,
      "name": "compat_SyS_futimesat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
long int compat_SyS_futimesat(long int dfd, long int filename, long int t)
```

```json
{
  "name": "compat_SyS_futimesat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581506347,
      "name": "compat_SyS_futimesat",
      "external": true,
      "loc": "fs/utimes.c:254",
      "file": "fs/utimes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/utimes.c:compat_SyS_utimes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581506048,
      "name": "compat_SyS_futimesat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
long int compat_SyS_futimesat(long int dfd, long int filename, long int t)
```

```json
{
  "name": "compat_SyS_futimesat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581648491,
      "name": "compat_SyS_futimesat",
      "external": true,
      "loc": "fs/utimes.c:256",
      "file": "fs/utimes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/utimes.c:compat_SyS_utimes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648192,
      "name": "compat_SyS_futimesat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
long int compat_SyS_futimesat(long int dfd, long int filename, long int t)
```
</details>
</li>
</ul>
