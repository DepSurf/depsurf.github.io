# Function: <code>legacy_clone_args_valid</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args * kargs)
```

```json
{
  "name": "legacy_clone_args_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579476687,
      "name": "legacy_clone_args_valid",
      "external": true,
      "loc": "kernel/fork.c:2420",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579477024,
      "name": "legacy_clone_args_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args * kargs)
```

```json
{
  "name": "legacy_clone_args_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579502751,
      "name": "legacy_clone_args_valid",
      "external": true,
      "loc": "kernel/fork.c:2405",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503072,
      "name": "legacy_clone_args_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args * kargs)
```

```json
{
  "name": "legacy_clone_args_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579531173,
      "name": "legacy_clone_args_valid",
      "external": true,
      "loc": "kernel/fork.c:2492",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__do_sys_clone"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579531344,
      "name": "legacy_clone_args_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args * kargs)
```

```json
{
  "name": "legacy_clone_args_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490636020,
      "name": "legacy_clone_args_valid",
      "external": true,
      "loc": "kernel/fork.c:2405",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__arm64_sys_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490636096,
      "name": "legacy_clone_args_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args * kargs)
```

```json
{
  "name": "legacy_clone_args_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224713716,
      "name": "legacy_clone_args_valid",
      "external": true,
      "loc": "kernel/fork.c:2405",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__se_sys_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224713168,
      "name": "legacy_clone_args_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args * kargs)
```

```json
{
  "name": "legacy_clone_args_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283454880,
      "name": "legacy_clone_args_valid",
      "external": true,
      "loc": "kernel/fork.c:2405",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__se_sys_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283454992,
      "name": "legacy_clone_args_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args * kargs)
```

```json
{
  "name": "legacy_clone_args_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271390622,
      "name": "legacy_clone_args_valid",
      "external": true,
      "loc": "kernel/fork.c:2405",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__se_sys_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271390408,
      "name": "legacy_clone_args_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args * kargs)
```

```json
{
  "name": "legacy_clone_args_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579476415,
      "name": "legacy_clone_args_valid",
      "external": true,
      "loc": "kernel/fork.c:2405",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476736,
      "name": "legacy_clone_args_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args * kargs)
```

```json
{
  "name": "legacy_clone_args_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579405311,
      "name": "legacy_clone_args_valid",
      "external": true,
      "loc": "kernel/fork.c:2405",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405632,
      "name": "legacy_clone_args_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args * kargs)
```

```json
{
  "name": "legacy_clone_args_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579476335,
      "name": "legacy_clone_args_valid",
      "external": true,
      "loc": "kernel/fork.c:2405",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476656,
      "name": "legacy_clone_args_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args * kargs)
```

```json
{
  "name": "legacy_clone_args_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579508207,
      "name": "legacy_clone_args_valid",
      "external": true,
      "loc": "kernel/fork.c:2405",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
      ],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_clone",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508528,
      "name": "legacy_clone_args_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args * kargs)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
bool legacy_clone_args_valid(const struct kernel_clone_args * kargs)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
