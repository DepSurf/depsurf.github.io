# Function: <code>security_lock_kernel_down</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int security_lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "security_lock_kernel_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583389392,
      "name": "security_lock_kernel_down",
      "external": true,
      "loc": "security/security.c:2614",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389392,
      "name": "security_lock_kernel_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "security_lock_kernel_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583727360,
      "name": "security_lock_kernel_down",
      "external": true,
      "loc": "security/security.c:2985",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727360,
      "name": "security_lock_kernel_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "security_lock_kernel_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583847552,
      "name": "security_lock_kernel_down",
      "external": true,
      "loc": "security/security.c:3003",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583847552,
      "name": "security_lock_kernel_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "security_lock_kernel_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583873392,
      "name": "security_lock_kernel_down",
      "external": true,
      "loc": "security/security.c:3066",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583873392,
      "name": "security_lock_kernel_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "security_lock_kernel_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584237168,
      "name": "security_lock_kernel_down",
      "external": true,
      "loc": "security/security.c:3074",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584237168,
      "name": "security_lock_kernel_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "security_lock_kernel_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584843616,
      "name": "security_lock_kernel_down",
      "external": true,
      "loc": "security/security.c:3152",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584843616,
      "name": "security_lock_kernel_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "security_lock_kernel_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585545600,
      "name": "security_lock_kernel_down",
      "external": true,
      "loc": "security/security.c:3132",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585545600,
      "name": "security_lock_kernel_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "security_lock_kernel_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585776256,
      "name": "security_lock_kernel_down",
      "external": true,
      "loc": "security/security.c:5595",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585776256,
      "name": "security_lock_kernel_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "security_lock_kernel_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586025248,
      "name": "security_lock_kernel_down",
      "external": true,
      "loc": "security/security.c:5736",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586025248,
      "name": "security_lock_kernel_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int security_lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "security_lock_kernel_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495139776,
      "name": "security_lock_kernel_down",
      "external": true,
      "loc": "security/security.c:2614",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/arm-init.c:efi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495139776,
      "name": "security_lock_kernel_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int security_lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "security_lock_kernel_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228527656,
      "name": "security_lock_kernel_down",
      "external": true,
      "loc": "security/security.c:2614",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/arm-init.c:efi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228527656,
      "name": "security_lock_kernel_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int security_lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "security_lock_kernel_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289056352,
      "name": "security_lock_kernel_down",
      "external": true,
      "loc": "security/security.c:2614",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/setup-common.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289056352,
      "name": "security_lock_kernel_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int security_lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "security_lock_kernel_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274389800,
      "name": "security_lock_kernel_down",
      "external": true,
      "loc": "security/security.c:2614",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274389800,
      "name": "security_lock_kernel_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int security_lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "security_lock_kernel_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583358128,
      "name": "security_lock_kernel_down",
      "external": true,
      "loc": "security/security.c:2614",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583358128,
      "name": "security_lock_kernel_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "security_lock_kernel_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583295232,
      "name": "security_lock_kernel_down",
      "external": true,
      "loc": "security/security.c:2614",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583295232,
      "name": "security_lock_kernel_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "security_lock_kernel_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583341904,
      "name": "security_lock_kernel_down",
      "external": true,
      "loc": "security/security.c:2614",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583341904,
      "name": "security_lock_kernel_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_lock_kernel_down(const char * where, enum lockdown_reason level)
```

```json
{
  "name": "security_lock_kernel_down",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583437088,
      "name": "security_lock_kernel_down",
      "external": true,
      "loc": "security/security.c:2614",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583437088,
      "name": "security_lock_kernel_down",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int security_lock_kernel_down(const char * where, enum lockdown_reason level)
```
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
