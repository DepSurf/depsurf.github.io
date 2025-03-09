# Function: <code>SyS_get_mempolicy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_get_mempolicy(long int policy, long int nmask, long int maxnode, long int addr, long int flags)
```

```json
{
  "name": "SyS_get_mempolicy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580817568,
      "name": "SyS_get_mempolicy",
      "external": true,
      "loc": "mm/mempolicy.c:1435",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:compat_SyS_get_mempolicy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580817568,
      "name": "SyS_get_mempolicy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
long int SyS_get_mempolicy(long int policy, long int nmask, long int maxnode, long int addr, long int flags)
```

```json
{
  "name": "SyS_get_mempolicy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580943271,
      "name": "SyS_get_mempolicy",
      "external": true,
      "loc": "mm/mempolicy.c:1467",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:compat_SyS_get_mempolicy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580942976,
      "name": "SyS_get_mempolicy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
long int SyS_get_mempolicy(long int policy, long int nmask, long int maxnode, long int addr, long int flags)
```

```json
{
  "name": "SyS_get_mempolicy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581013736,
      "name": "SyS_get_mempolicy",
      "external": true,
      "loc": "mm/mempolicy.c:1469",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:C_SYSC_get_mempolicy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581015824,
      "name": "SyS_get_mempolicy",
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
long int SyS_get_mempolicy(long int policy, long int nmask, long int maxnode, long int addr, long int flags)
```

```json
{
  "name": "SyS_get_mempolicy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581061143,
      "name": "SyS_get_mempolicy",
      "external": true,
      "loc": "mm/mempolicy.c:1398",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:C_SYSC_get_mempolicy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581061840,
      "name": "SyS_get_mempolicy",
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
long int SyS_get_mempolicy(long int policy, long int nmask, long int maxnode, long int addr, long int flags)
```

```json
{
  "name": "SyS_get_mempolicy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581172231,
      "name": "SyS_get_mempolicy",
      "external": true,
      "loc": "mm/mempolicy.c:1455",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:C_SYSC_get_mempolicy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172928,
      "name": "SyS_get_mempolicy",
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
long int SyS_get_mempolicy(long int policy, long int nmask, long int maxnode, long int addr, long int flags)
```
</details>
</li>
</ul>
