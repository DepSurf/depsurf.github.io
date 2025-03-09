# Function: <code>efi_get_embedded_fw</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int efi_get_embedded_fw(const char * name, const u8 * * data, size_t * size)
```

```json
{
  "name": "efi_get_embedded_fw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589076653,
      "name": "efi_get_embedded_fw",
      "external": true,
      "loc": "drivers/firmware/efi/embedded-firmware.c:125",
      "file": "drivers/firmware/efi/embedded-firmware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589076653,
      "name": "efi_get_embedded_fw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071589076512,
      "name": "efi_get_embedded_fw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int efi_get_embedded_fw(const char * name, const u8 * * data, size_t * size)
```

```json
{
  "name": "efi_get_embedded_fw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591611476,
      "name": "efi_get_embedded_fw",
      "external": true,
      "loc": "drivers/firmware/efi/embedded-firmware.c:122",
      "file": "drivers/firmware/efi/embedded-firmware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591611476,
      "name": "efi_get_embedded_fw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071589079168,
      "name": "efi_get_embedded_fw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int efi_get_embedded_fw(const char * name, const u8 * * data, size_t * size)
```

```json
{
  "name": "efi_get_embedded_fw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591554690,
      "name": "efi_get_embedded_fw",
      "external": true,
      "loc": "drivers/firmware/efi/embedded-firmware.c:122",
      "file": "drivers/firmware/efi/embedded-firmware.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591554690,
      "name": "efi_get_embedded_fw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071588965568,
      "name": "efi_get_embedded_fw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int efi_get_embedded_fw(const char * name, const u8 * * data, size_t * size)
```

```json
{
  "name": "efi_get_embedded_fw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_get_embedded_fw",
      "external": true,
      "loc": "drivers/firmware/efi/embedded-firmware.c:122",
      "file": "drivers/firmware/efi/embedded-firmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592674407,
      "name": "efi_get_embedded_fw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071589675104,
      "name": "efi_get_embedded_fw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int efi_get_embedded_fw(const char * name, const u8 * * data, size_t * size)
```

```json
{
  "name": "efi_get_embedded_fw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_get_embedded_fw",
      "external": true,
      "loc": "drivers/firmware/efi/embedded-firmware.c:122",
      "file": "drivers/firmware/efi/embedded-firmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594559643,
      "name": "efi_get_embedded_fw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071591179616,
      "name": "efi_get_embedded_fw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int efi_get_embedded_fw(const char * name, const u8 * * data, size_t * size)
```

```json
{
  "name": "efi_get_embedded_fw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_get_embedded_fw",
      "external": true,
      "loc": "drivers/firmware/efi/embedded-firmware.c:122",
      "file": "drivers/firmware/efi/embedded-firmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596318578,
      "name": "efi_get_embedded_fw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071592903040,
      "name": "efi_get_embedded_fw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int efi_get_embedded_fw(const char * name, const u8 * * data, size_t * size)
```

```json
{
  "name": "efi_get_embedded_fw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_get_embedded_fw",
      "external": true,
      "loc": "drivers/firmware/efi/embedded-firmware.c:122",
      "file": "drivers/firmware/efi/embedded-firmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596848208,
      "name": "efi_get_embedded_fw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071593341648,
      "name": "efi_get_embedded_fw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int efi_get_embedded_fw(const char * name, const u8 * * data, size_t * size)
```

```json
{
  "name": "efi_get_embedded_fw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_get_embedded_fw",
      "external": true,
      "loc": "drivers/firmware/efi/embedded-firmware.c:122",
      "file": "drivers/firmware/efi/embedded-firmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597773133,
      "name": "efi_get_embedded_fw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071594095328,
      "name": "efi_get_embedded_fw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int efi_get_embedded_fw(const char * name, const u8 * * data, size_t * size)
```
</details>
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
