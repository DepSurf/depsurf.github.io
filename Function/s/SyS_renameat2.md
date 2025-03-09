# Function: <code>SyS_renameat2</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_renameat2(long int olddfd, long int oldname, long int newdfd, long int newname, long int flags)
```

```json
{
  "name": "SyS_renameat2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581064608,
      "name": "SyS_renameat2",
      "external": true,
      "loc": "fs/namei.c:4320",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:SyS_renameat",
        "fs/namei.c:SyS_rename"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581064608,
      "name": "SyS_renameat2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1481
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
long int SyS_renameat2(long int olddfd, long int oldname, long int newdfd, long int newname, long int flags)
```

```json
{
  "name": "SyS_renameat2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581228501,
      "name": "SyS_renameat2",
      "external": true,
      "loc": "fs/namei.c:4474",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581225904,
      "name": "SyS_renameat2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1518
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
long int SyS_renameat2(long int olddfd, long int oldname, long int newdfd, long int newname, long int flags)
```

```json
{
  "name": "SyS_renameat2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581306165,
      "name": "SyS_renameat2",
      "external": true,
      "loc": "fs/namei.c:4418",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581303584,
      "name": "SyS_renameat2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1513
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
long int SyS_renameat2(long int olddfd, long int oldname, long int newdfd, long int newname, long int flags)
```

```json
{
  "name": "SyS_renameat2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581355624,
      "name": "SyS_renameat2",
      "external": true,
      "loc": "fs/namei.c:4484",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581353152,
      "name": "SyS_renameat2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1460
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
long int SyS_renameat2(long int olddfd, long int oldname, long int newdfd, long int newname, long int flags)
```

```json
{
  "name": "SyS_renameat2",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581497080,
      "name": "SyS_renameat2",
      "external": true,
      "loc": "fs/namei.c:4480",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:SyS_rename",
        "fs/namei.c:SyS_renameat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581494608,
      "name": "SyS_renameat2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1463
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
long int SyS_renameat2(long int olddfd, long int oldname, long int newdfd, long int newname, long int flags)
```
</details>
</li>
</ul>
