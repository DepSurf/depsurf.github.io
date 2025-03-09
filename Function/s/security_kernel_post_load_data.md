# Function: <code>security_kernel_post_load_data</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int security_kernel_post_load_data(char * buf, loff_t size, enum kernel_load_data_id id, char * description)
```

```json
{
  "name": "security_kernel_post_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583851280,
      "name": "security_kernel_post_load_data",
      "external": true,
      "loc": "security/security.c:1924",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_init_module",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583851280,
      "name": "security_kernel_post_load_data",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int security_kernel_post_load_data(char * buf, loff_t size, enum kernel_load_data_id id, char * description)
```

```json
{
  "name": "security_kernel_post_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583876544,
      "name": "security_kernel_post_load_data",
      "external": true,
      "loc": "security/security.c:1974",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_init_module",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583876544,
      "name": "security_kernel_post_load_data",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int security_kernel_post_load_data(char * buf, loff_t size, enum kernel_load_data_id id, char * description)
```

```json
{
  "name": "security_kernel_post_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584240720,
      "name": "security_kernel_post_load_data",
      "external": true,
      "loc": "security/security.c:1982",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__do_sys_init_module",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584240720,
      "name": "security_kernel_post_load_data",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int security_kernel_post_load_data(char * buf, loff_t size, enum kernel_load_data_id id, char * description)
```

```json
{
  "name": "security_kernel_post_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584846912,
      "name": "security_kernel_post_load_data",
      "external": true,
      "loc": "security/security.c:1987",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:__do_sys_init_module",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform",
        "drivers/base/firmware_loader/sysfs.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584846912,
      "name": "security_kernel_post_load_data",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int security_kernel_post_load_data(char * buf, loff_t size, enum kernel_load_data_id id, char * description)
```

```json
{
  "name": "security_kernel_post_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585549312,
      "name": "security_kernel_post_load_data",
      "external": true,
      "loc": "security/security.c:2034",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:__do_sys_init_module",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform",
        "drivers/base/firmware_loader/sysfs.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585549312,
      "name": "security_kernel_post_load_data",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int security_kernel_post_load_data(char * buf, loff_t size, enum kernel_load_data_id id, char * description)
```

```json
{
  "name": "security_kernel_post_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585779936,
      "name": "security_kernel_post_load_data",
      "external": true,
      "loc": "security/security.c:3268",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:__do_sys_init_module",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform",
        "drivers/base/firmware_loader/sysfs.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585779936,
      "name": "security_kernel_post_load_data",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int security_kernel_post_load_data(char * buf, loff_t size, enum kernel_load_data_id id, char * description)
```

```json
{
  "name": "security_kernel_post_load_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586028480,
      "name": "security_kernel_post_load_data",
      "external": true,
      "loc": "security/security.c:3340",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:__do_sys_init_module",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform",
        "drivers/base/firmware_loader/sysfs.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586028480,
      "name": "security_kernel_post_load_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int security_kernel_post_load_data(char * buf, loff_t size, enum kernel_load_data_id id, char * description)
```
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
