# Function: <code>security_kernel_load_data</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int security_kernel_load_data(enum kernel_load_data_id id)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583100848,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:1668",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_init_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583100848,
      "name": "security_kernel_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int security_kernel_load_data(enum kernel_load_data_id id)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583286144,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:1687",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_init_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583286144,
      "name": "security_kernel_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int security_kernel_load_data(enum kernel_load_data_id id)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583391504,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:1726",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_init_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583391504,
      "name": "security_kernel_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int security_kernel_load_data(enum kernel_load_data_id id)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583731008,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:1910",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_init_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731008,
      "name": "security_kernel_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int security_kernel_load_data(enum kernel_load_data_id id, bool contents)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583851200,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:1913",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_init_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583851200,
      "name": "security_kernel_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int security_kernel_load_data(enum kernel_load_data_id id, bool contents)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583876464,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:1963",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_init_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583876464,
      "name": "security_kernel_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int security_kernel_load_data(enum kernel_load_data_id id, bool contents)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584240640,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:1971",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_init_module",
        "kernel/kexec.c:__do_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584240640,
      "name": "security_kernel_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int security_kernel_load_data(enum kernel_load_data_id id, bool contents)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584846800,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:1976",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:__do_sys_init_module",
        "kernel/kexec.c:__do_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584846800,
      "name": "security_kernel_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int security_kernel_load_data(enum kernel_load_data_id id, bool contents)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585549184,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:2023",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:__do_sys_init_module",
        "kernel/kexec.c:__do_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585549184,
      "name": "security_kernel_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int security_kernel_load_data(enum kernel_load_data_id id, bool contents)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585779808,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:3243",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:__do_sys_init_module",
        "kernel/kexec.c:__do_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585779808,
      "name": "security_kernel_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int security_kernel_load_data(enum kernel_load_data_id id, bool contents)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586028352,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:3315",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:__do_sys_init_module",
        "kernel/kexec.c:__do_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586028352,
      "name": "security_kernel_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int security_kernel_load_data(enum kernel_load_data_id id)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495142472,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:1726",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_init_module",
        "kernel/kexec.c:__arm64_compat_sys_kexec_load",
        "kernel/kexec.c:__arm64_sys_kexec_load",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495142472,
      "name": "security_kernel_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int security_kernel_load_data(enum kernel_load_data_id id)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228530240,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:1726",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__se_sys_init_module",
        "kernel/kexec.c:__se_sys_kexec_load",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228530240,
      "name": "security_kernel_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int security_kernel_load_data(enum kernel_load_data_id id)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289060976,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:1726",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_init_module",
        "kernel/kexec.c:__se_compat_sys_kexec_load",
        "kernel/kexec.c:__se_sys_kexec_load",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289060976,
      "name": "security_kernel_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int security_kernel_load_data(enum kernel_load_data_id id)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274391836,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:1726",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_init_module",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274391836,
      "name": "security_kernel_load_data",
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
int security_kernel_load_data(enum kernel_load_data_id id)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583360240,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:1726",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_init_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583360240,
      "name": "security_kernel_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int security_kernel_load_data(enum kernel_load_data_id id)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583297344,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:1726",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_init_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583297344,
      "name": "security_kernel_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int security_kernel_load_data(enum kernel_load_data_id id)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583344016,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:1726",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_init_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344016,
      "name": "security_kernel_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int security_kernel_load_data(enum kernel_load_data_id id)
```

```json
{
  "name": "security_kernel_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583439200,
      "name": "security_kernel_load_data",
      "external": true,
      "loc": "security/security.c:1726",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_init_module",
        "kernel/kexec.c:__x32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_compat_sys_kexec_load",
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439200,
      "name": "security_kernel_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int security_kernel_load_data(enum kernel_load_data_id id)
```
</details>
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
<code>bool contents</code>
</li>
</ul>
</details>
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
