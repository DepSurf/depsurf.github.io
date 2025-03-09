# Function: <code>SyS_futimesat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_futimesat(long int dfd, long int filename, long int utimes)
```

```json
{
  "name": "SyS_futimesat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581208736,
      "name": "SyS_futimesat",
      "external": true,
      "loc": "fs/utimes.c:203",
      "file": "fs/utimes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/utimes.c:SyS_utimes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581208736,
      "name": "SyS_futimesat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
long int SyS_futimesat(long int dfd, long int filename, long int utimes)
```

```json
{
  "name": "SyS_futimesat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581373653,
      "name": "SyS_futimesat",
      "external": true,
      "loc": "fs/utimes.c:204",
      "file": "fs/utimes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/utimes.c:SyS_utimes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373392,
      "name": "SyS_futimesat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
long int SyS_futimesat(long int dfd, long int filename, long int utimes)
```

```json
{
  "name": "SyS_futimesat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581451397,
      "name": "SyS_futimesat",
      "external": true,
      "loc": "fs/utimes.c:189",
      "file": "fs/utimes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/utimes.c:SyS_utimes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581451136,
      "name": "SyS_futimesat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
long int SyS_futimesat(long int dfd, long int filename, long int utimes)
```

```json
{
  "name": "SyS_futimesat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581505487,
      "name": "SyS_futimesat",
      "external": true,
      "loc": "fs/utimes.c:185",
      "file": "fs/utimes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/utimes.c:SyS_utimes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505216,
      "name": "SyS_futimesat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
long int SyS_futimesat(long int dfd, long int filename, long int utimes)
```

```json
{
  "name": "SyS_futimesat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581647631,
      "name": "SyS_futimesat",
      "external": true,
      "loc": "fs/utimes.c:187",
      "file": "fs/utimes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/utimes.c:SyS_utimes"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647360,
      "name": "SyS_futimesat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
long int SyS_futimesat(long int dfd, long int filename, long int utimes)
```
</details>
</li>
</ul>
