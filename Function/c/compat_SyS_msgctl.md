# Function: <code>compat_SyS_msgctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int compat_SyS_msgctl(long int first, long int second, long int uptr)
```

```json
{
  "name": "compat_SyS_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582139532,
      "name": "compat_SyS_msgctl",
      "external": true,
      "loc": "ipc/compat.c:498",
      "file": "ipc/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/compat.c:compat_SyS_ipc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582139808,
      "name": "compat_SyS_msgctl",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int compat_SyS_msgctl(long int first, long int second, long int uptr)
```

```json
{
  "name": "compat_SyS_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582355580,
      "name": "compat_SyS_msgctl",
      "external": true,
      "loc": "ipc/compat.c:498",
      "file": "ipc/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/compat.c:compat_SyS_ipc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582355856,
      "name": "compat_SyS_msgctl",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int compat_SyS_msgctl(long int first, long int second, long int uptr)
```

```json
{
  "name": "compat_SyS_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582446956,
      "name": "compat_SyS_msgctl",
      "external": true,
      "loc": "ipc/compat.c:498",
      "file": "ipc/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/compat.c:compat_SyS_ipc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582447232,
      "name": "compat_SyS_msgctl",
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
long int compat_SyS_msgctl(long int first, long int second, long int uptr)
```

```json
{
  "name": "compat_SyS_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582526111,
      "name": "compat_SyS_msgctl",
      "external": true,
      "loc": "ipc/compat.c:498",
      "file": "ipc/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/compat.c:compat_SyS_ipc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582526384,
      "name": "compat_SyS_msgctl",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long int compat_SyS_msgctl(long int msqid, long int cmd, long int uptr)
```

```json
{
  "name": "compat_SyS_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582685520,
      "name": "compat_SyS_msgctl",
      "external": true,
      "loc": "ipc/msg.c:641",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582685520,
      "name": "compat_SyS_msgctl",
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long int msqid</code>
</li>
<li>
<b>Param added. </b>
<code>long int cmd</code>
</li>
<li>
<b>Param removed. </b>
<code>long int first</code>
</li>
<li>
<b>Param removed. </b>
<code>long int second</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
long int compat_SyS_msgctl(long int msqid, long int cmd, long int uptr)
```
</details>
</li>
</ul>
