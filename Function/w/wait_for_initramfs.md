# Function: <code>wait_for_initramfs</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void wait_for_initramfs()
```

```json
{
  "name": "wait_for_initramfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578861621,
      "name": "wait_for_initramfs",
      "external": true,
      "loc": "init/initramfs.c:710",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/initramfs.c:populate_rootfs",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591180581,
      "name": "wait_for_initramfs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071578861600,
      "name": "wait_for_initramfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void wait_for_initramfs()
```

```json
{
  "name": "wait_for_initramfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578861702,
      "name": "wait_for_initramfs",
      "external": true,
      "loc": "init/initramfs.c:711",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/initramfs.c:populate_rootfs",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592036764,
      "name": "wait_for_initramfs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071578861680,
      "name": "wait_for_initramfs",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void wait_for_initramfs()
```

```json
{
  "name": "wait_for_initramfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578852758,
      "name": "wait_for_initramfs",
      "external": true,
      "loc": "init/initramfs.c:737",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/initramfs.c:populate_rootfs",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593802580,
      "name": "wait_for_initramfs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071578852736,
      "name": "wait_for_initramfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void wait_for_initramfs()
```

```json
{
  "name": "wait_for_initramfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578854694,
      "name": "wait_for_initramfs",
      "external": true,
      "loc": "init/initramfs.c:737",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/initramfs.c:populate_rootfs",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595950071,
      "name": "wait_for_initramfs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071578854672,
      "name": "wait_for_initramfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void wait_for_initramfs()
```

```json
{
  "name": "wait_for_initramfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578852614,
      "name": "wait_for_initramfs",
      "external": true,
      "loc": "init/initramfs.c:730",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/initramfs.c:populate_rootfs",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596467376,
      "name": "wait_for_initramfs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071578852592,
      "name": "wait_for_initramfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void wait_for_initramfs()
```

```json
{
  "name": "wait_for_initramfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578852710,
      "name": "wait_for_initramfs",
      "external": true,
      "loc": "init/initramfs.c:746",
      "file": "init/initramfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable",
        "init/initramfs.c:populate_rootfs",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597362368,
      "name": "wait_for_initramfs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071578852688,
      "name": "wait_for_initramfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void wait_for_initramfs()
```
</details>
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
