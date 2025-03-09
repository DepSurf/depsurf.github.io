# Function: <code>__ia32_sys_socketcall</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int __ia32_sys_socketcall(const struct pt_regs * regs)
```

```json
{
  "name": "__ia32_sys_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587708640,
      "name": "__ia32_sys_socketcall",
      "external": true,
      "loc": "net/socket.c:2519",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587708640,
      "name": "__ia32_sys_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long int __ia32_sys_socketcall(const struct pt_regs * regs)
```

```json
{
  "name": "__ia32_sys_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587841616,
      "name": "__ia32_sys_socketcall",
      "external": true,
      "loc": "net/socket.c:2527",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587841616,
      "name": "__ia32_sys_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 833
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long int __ia32_sys_socketcall(const struct pt_regs * regs)
```

```json
{
  "name": "__ia32_sys_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588145680,
      "name": "__ia32_sys_socketcall",
      "external": true,
      "loc": "net/socket.c:2738",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588145680,
      "name": "__ia32_sys_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 840
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long int __ia32_sys_socketcall(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579679168,
      "name": "__ia32_sys_socketcall",
      "external": true,
      "loc": "kernel/sys_ni.c:363",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588350944,
      "name": "__ia32_sys_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 833
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int __ia32_sys_socketcall(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589212528,
      "name": "__ia32_sys_socketcall",
      "external": true,
      "loc": "kernel/sys_ni.c:363",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589212528,
      "name": "__ia32_sys_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long int __ia32_sys_socketcall(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589211632,
      "name": "__ia32_sys_socketcall",
      "external": true,
      "loc": "kernel/sys_ni.c:366",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589211632,
      "name": "__ia32_sys_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long int __ia32_sys_socketcall(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589105168,
      "name": "__ia32_sys_socketcall",
      "external": true,
      "loc": "kernel/sys_ni.c:372",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589105168,
      "name": "__ia32_sys_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long int __ia32_sys_socketcall(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589822880,
      "name": "__ia32_sys_socketcall",
      "external": true,
      "loc": "kernel/sys_ni.c:370",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589822880,
      "name": "__ia32_sys_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long int __ia32_sys_socketcall(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591343808,
      "name": "__ia32_sys_socketcall",
      "external": true,
      "loc": "kernel/sys_ni.c:373",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591343808,
      "name": "__ia32_sys_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int __ia32_sys_socketcall(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593099376,
      "name": "__ia32_sys_socketcall",
      "external": true,
      "loc": "kernel/sys_ni.c:373",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593099376,
      "name": "__ia32_sys_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int __ia32_sys_socketcall(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593551584,
      "name": "__ia32_sys_socketcall",
      "external": true,
      "loc": "kernel/sys_ni.c:266",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593551584,
      "name": "__ia32_sys_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
long int __ia32_sys_socketcall(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594323872,
      "name": "__ia32_sys_socketcall",
      "external": true,
      "loc": "kernel/sys_ni.c:284",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594323872,
      "name": "__ia32_sys_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int __ia32_sys_socketcall(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655488,
      "name": "__ia32_sys_socketcall",
      "external": true,
      "loc": "kernel/sys_ni.c:363",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587957728,
      "name": "__ia32_sys_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 833
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long int __ia32_sys_socketcall(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579583840,
      "name": "__ia32_sys_socketcall",
      "external": true,
      "loc": "kernel/sys_ni.c:363",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587670832,
      "name": "__ia32_sys_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 833
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long int __ia32_sys_socketcall(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579652752,
      "name": "__ia32_sys_socketcall",
      "external": true,
      "loc": "kernel/sys_ni.c:363",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588289504,
      "name": "__ia32_sys_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 833
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long int __ia32_sys_socketcall(const struct pt_regs * __unused)
```

```json
{
  "name": "__ia32_sys_socketcall",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686608,
      "name": "__ia32_sys_socketcall",
      "external": true,
      "loc": "kernel/sys_ni.c:363",
      "file": "kernel/sys_ni.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588424576,
      "name": "__ia32_sys_socketcall",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 833
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long int __ia32_sys_socketcall(const struct pt_regs * regs)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct pt_regs * __unused</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct pt_regs * regs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long int __ia32_sys_socketcall(const struct pt_regs * __unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int __ia32_sys_socketcall(const struct pt_regs * __unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int __ia32_sys_socketcall(const struct pt_regs * __unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int __ia32_sys_socketcall(const struct pt_regs * __unused)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
