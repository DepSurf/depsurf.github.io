# Function: <code>validate_xstate_header</code>

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
int validate_xstate_header(const struct xstate_header * hdr)
```

```json
{
  "name": "validate_xstate_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579085488,
      "name": "validate_xstate_header",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:481",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085488,
      "name": "validate_xstate_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int validate_xstate_header(const struct xstate_header * hdr)
```

```json
{
  "name": "validate_xstate_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579090864,
      "name": "validate_xstate_header",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:481",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090864,
      "name": "validate_xstate_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int validate_xstate_header(const struct xstate_header * hdr)
```

```json
{
  "name": "validate_xstate_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579096176,
      "name": "validate_xstate_header",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:481",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579096176,
      "name": "validate_xstate_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int validate_xstate_header(const struct xstate_header * hdr)
```

```json
{
  "name": "validate_xstate_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579106592,
      "name": "validate_xstate_header",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:475",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579106592,
      "name": "validate_xstate_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int validate_xstate_header(const struct xstate_header * hdr)
```

```json
{
  "name": "validate_xstate_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579108416,
      "name": "validate_xstate_header",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:475",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108416,
      "name": "validate_xstate_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int validate_xstate_header(const struct xstate_header * hdr)
```

```json
{
  "name": "validate_xstate_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579108800,
      "name": "validate_xstate_header",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:475",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108800,
      "name": "validate_xstate_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int validate_xstate_header(const struct xstate_header * hdr)
```

```json
{
  "name": "validate_xstate_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579041184,
      "name": "validate_xstate_header",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:475",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579041184,
      "name": "validate_xstate_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int validate_xstate_header(const struct xstate_header * hdr)
```

```json
{
  "name": "validate_xstate_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579108352,
      "name": "validate_xstate_header",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:475",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108352,
      "name": "validate_xstate_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int validate_xstate_header(const struct xstate_header * hdr)
```

```json
{
  "name": "validate_xstate_header",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579113424,
      "name": "validate_xstate_header",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:475",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579113424,
      "name": "validate_xstate_header",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int validate_xstate_header(const struct xstate_header * hdr)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int validate_xstate_header(const struct xstate_header * hdr)
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
int validate_xstate_header(const struct xstate_header * hdr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int validate_xstate_header(const struct xstate_header * hdr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int validate_xstate_header(const struct xstate_header * hdr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int validate_xstate_header(const struct xstate_header * hdr)
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
