# Function: <code>fpu_sync_fpstate</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void fpu_sync_fpstate(struct fpu * fpu)
```

```json
{
  "name": "fpu_sync_fpstate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579146064,
      "name": "fpu_sync_fpstate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:192",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/regset.c:fpregs_get",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/regset.c:xfpregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146064,
      "name": "fpu_sync_fpstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void fpu_sync_fpstate(struct fpu * fpu)
```

```json
{
  "name": "fpu_sync_fpstate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579185648,
      "name": "fpu_sync_fpstate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:461",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/regset.c:fpregs_get",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/regset.c:xfpregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579185648,
      "name": "fpu_sync_fpstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void fpu_sync_fpstate(struct fpu * fpu)
```

```json
{
  "name": "fpu_sync_fpstate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579241200,
      "name": "fpu_sync_fpstate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:458",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/regset.c:fpregs_get",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/regset.c:xfpregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579241200,
      "name": "fpu_sync_fpstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void fpu_sync_fpstate(struct fpu * fpu)
```

```json
{
  "name": "fpu_sync_fpstate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579247856,
      "name": "fpu_sync_fpstate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:458",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/regset.c:fpregs_get",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/regset.c:xfpregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579247856,
      "name": "fpu_sync_fpstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void fpu_sync_fpstate(struct fpu * fpu)
```

```json
{
  "name": "fpu_sync_fpstate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276816,
      "name": "fpu_sync_fpstate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:459",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/fpu/regset.c:fpregs_get",
        "arch/x86/kernel/fpu/regset.c:ssp_get",
        "arch/x86/kernel/fpu/regset.c:xstateregs_get",
        "arch/x86/kernel/fpu/regset.c:xfpregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276816,
      "name": "fpu_sync_fpstate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void fpu_sync_fpstate(struct fpu * fpu)
```
</details>
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
