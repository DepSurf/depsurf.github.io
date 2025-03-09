# Function: <code>copy_xstate_to_kernel</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int copy_xstate_to_kernel(void * kbuf, struct xregs_state * xsave, unsigned int offset_start, unsigned int size_total)
```

```json
{
  "name": "copy_xstate_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579085872,
      "name": "copy_xstate_to_kernel",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:989",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085872,
      "name": "copy_xstate_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 916
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int copy_xstate_to_kernel(void * kbuf, struct xregs_state * xsave, unsigned int offset_start, unsigned int size_total)
```

```json
{
  "name": "copy_xstate_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579091248,
      "name": "copy_xstate_to_kernel",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:989",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579091248,
      "name": "copy_xstate_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 903
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
int copy_xstate_to_kernel(void * kbuf, struct xregs_state * xsave, unsigned int offset_start, unsigned int size_total)
```

```json
{
  "name": "copy_xstate_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579096496,
      "name": "copy_xstate_to_kernel",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:987",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579096496,
      "name": "copy_xstate_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 903
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
int copy_xstate_to_kernel(void * kbuf, struct xregs_state * xsave, unsigned int offset_start, unsigned int size_total)
```

```json
{
  "name": "copy_xstate_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579106976,
      "name": "copy_xstate_to_kernel",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:977",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579106976,
      "name": "copy_xstate_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 905
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
int copy_xstate_to_kernel(void * kbuf, struct xregs_state * xsave, unsigned int offset_start, unsigned int size_total)
```

```json
{
  "name": "copy_xstate_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579108800,
      "name": "copy_xstate_to_kernel",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:977",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108800,
      "name": "copy_xstate_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 905
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
int copy_xstate_to_kernel(void * kbuf, struct xregs_state * xsave, unsigned int offset_start, unsigned int size_total)
```

```json
{
  "name": "copy_xstate_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579122032,
      "name": "copy_xstate_to_kernel",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1047",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579122032,
      "name": "copy_xstate_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void copy_xstate_to_kernel(struct membuf to, struct xregs_state * xsave)
```

```json
{
  "name": "copy_xstate_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579122208,
      "name": "copy_xstate_to_kernel",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1075",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579122208,
      "name": "copy_xstate_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
void copy_xstate_to_kernel(struct membuf to, struct xregs_state * xsave)
```

```json
{
  "name": "copy_xstate_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579128416,
      "name": "copy_xstate_to_kernel",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:1100",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579128416,
      "name": "copy_xstate_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1783
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int copy_xstate_to_kernel(void * kbuf, struct xregs_state * xsave, unsigned int offset_start, unsigned int size_total)
```

```json
{
  "name": "copy_xstate_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579109184,
      "name": "copy_xstate_to_kernel",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:977",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579109184,
      "name": "copy_xstate_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 905
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
int copy_xstate_to_kernel(void * kbuf, struct xregs_state * xsave, unsigned int offset_start, unsigned int size_total)
```

```json
{
  "name": "copy_xstate_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579041568,
      "name": "copy_xstate_to_kernel",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:977",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579041568,
      "name": "copy_xstate_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 905
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
int copy_xstate_to_kernel(void * kbuf, struct xregs_state * xsave, unsigned int offset_start, unsigned int size_total)
```

```json
{
  "name": "copy_xstate_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579108736,
      "name": "copy_xstate_to_kernel",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:977",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108736,
      "name": "copy_xstate_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 905
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
int copy_xstate_to_kernel(void * kbuf, struct xregs_state * xsave, unsigned int offset_start, unsigned int size_total)
```

```json
{
  "name": "copy_xstate_to_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579113824,
      "name": "copy_xstate_to_kernel",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:977",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579113824,
      "name": "copy_xstate_to_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 905
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int copy_xstate_to_kernel(void * kbuf, struct xregs_state * xsave, unsigned int offset_start, unsigned int size_total)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct membuf to</code>
</li>
<li>
<b>Param removed. </b>
<code>void * kbuf</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int offset_start</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int size_total</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void copy_xstate_to_kernel(struct membuf to, struct xregs_state * xsave)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int copy_xstate_to_kernel(void * kbuf, struct xregs_state * xsave, unsigned int offset_start, unsigned int size_total)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int copy_xstate_to_kernel(void * kbuf, struct xregs_state * xsave, unsigned int offset_start, unsigned int size_total)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int copy_xstate_to_kernel(void * kbuf, struct xregs_state * xsave, unsigned int offset_start, unsigned int size_total)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int copy_xstate_to_kernel(void * kbuf, struct xregs_state * xsave, unsigned int offset_start, unsigned int size_total)
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
