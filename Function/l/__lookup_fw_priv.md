# Function: <code>__lookup_fw_priv</code>

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
struct fw_priv * __lookup_fw_priv(const char * fw_name)
```

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585766672,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:197",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585766672,
      "name": "__lookup_fw_priv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
struct fw_priv * __lookup_fw_priv(const char * fw_name)
```

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585899872,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:197",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585899872,
      "name": "__lookup_fw_priv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
struct fw_priv * __lookup_fw_priv(const char * fw_name)
```

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586138176,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:198",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586138176,
      "name": "__lookup_fw_priv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct fw_priv * __lookup_fw_priv(const char * fw_name)
```

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586286656,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:198",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586286656,
      "name": "__lookup_fw_priv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587058979,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:198",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:__device_uncache_fw_images"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587143155,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:212",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:__device_uncache_fw_images"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587030312,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:213",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587597784,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:214",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588936391,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:155",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590450551,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:155",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590770695,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:155",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591113239,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:156",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
struct fw_priv * __lookup_fw_priv(const char * fw_name)
```

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499118048,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:198",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499118048,
      "name": "__lookup_fw_priv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
struct fw_priv * __lookup_fw_priv(const char * fw_name)
```

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231666864,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:198",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231666864,
      "name": "__lookup_fw_priv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
struct fw_priv * __lookup_fw_priv(const char * fw_name)
```

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292303808,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:198",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292303808,
      "name": "__lookup_fw_priv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276439410,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:198",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
struct fw_priv * __lookup_fw_priv(const char * fw_name)
```

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586049904,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:198",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586049904,
      "name": "__lookup_fw_priv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct fw_priv * __lookup_fw_priv(const char * fw_name)
```

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585895856,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:198",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585895856,
      "name": "__lookup_fw_priv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct fw_priv * __lookup_fw_priv(const char * fw_name)
```

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586236672,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:198",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586236672,
      "name": "__lookup_fw_priv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct fw_priv * __lookup_fw_priv(const char * fw_name)
```

```json
{
  "name": "__lookup_fw_priv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586345648,
      "name": "__lookup_fw_priv",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:198",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586345648,
      "name": "__lookup_fw_priv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct fw_priv * __lookup_fw_priv(const char * fw_name)
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
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct fw_priv * __lookup_fw_priv(const char * fw_name)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct fw_priv * __lookup_fw_priv(const char * fw_name)
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
