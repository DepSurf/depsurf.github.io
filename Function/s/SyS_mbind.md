# Function: <code>SyS_mbind</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_mbind(long int start, long int len, long int mode, long int nmask, long int maxnode, long int flags)
```

```json
{
  "name": "SyS_mbind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580822159,
      "name": "SyS_mbind",
      "external": true,
      "loc": "mm/mempolicy.c:1298",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:compat_SyS_mbind"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822304,
      "name": "SyS_mbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
long int SyS_mbind(long int start, long int len, long int mode, long int nmask, long int maxnode, long int flags)
```

```json
{
  "name": "SyS_mbind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580947577,
      "name": "SyS_mbind",
      "external": true,
      "loc": "mm/mempolicy.c:1330",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:compat_SyS_mbind"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580947712,
      "name": "SyS_mbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
long int SyS_mbind(long int start, long int len, long int mode, long int nmask, long int maxnode, long int flags)
```

```json
{
  "name": "SyS_mbind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581020185,
      "name": "SyS_mbind",
      "external": true,
      "loc": "mm/mempolicy.c:1332",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:C_SYSC_mbind"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581019936,
      "name": "SyS_mbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long int SyS_mbind(long int start, long int len, long int mode, long int nmask, long int maxnode, long int flags)
```

```json
{
  "name": "SyS_mbind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581066071,
      "name": "SyS_mbind",
      "external": true,
      "loc": "mm/mempolicy.c:1261",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:C_SYSC_mbind"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065840,
      "name": "SyS_mbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long int SyS_mbind(long int start, long int len, long int mode, long int nmask, long int maxnode, long int flags)
```

```json
{
  "name": "SyS_mbind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581177255,
      "name": "SyS_mbind",
      "external": true,
      "loc": "mm/mempolicy.c:1324",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:C_SYSC_mbind"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581177024,
      "name": "SyS_mbind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long int SyS_mbind(long int start, long int len, long int mode, long int nmask, long int maxnode, long int flags)
```
</details>
</li>
</ul>
