# Function: <code>zstd_is_error</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int zstd_is_error(size_t code)
```

```json
{
  "name": "zstd_is_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586481328,
      "name": "zstd_is_error",
      "external": true,
      "loc": "lib/zstd/zstd_decompress_module.c:21",
      "file": "lib/zstd/zstd_decompress_module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/zstd_wrapper.c:zstd_uncompress",
        "security/apparmor/apparmorfs.c:rawdata_open",
        "security/apparmor/policy_unpack.c:compress_zstd",
        "lib/decompress_unzstd.c:handle_zstd_error",
        "drivers/base/firmware_loader/main.c:fw_decompress_zstd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586481328,
      "name": "zstd_is_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
unsigned int zstd_is_error(size_t code)
```

```json
{
  "name": "zstd_is_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587666896,
      "name": "zstd_is_error",
      "external": true,
      "loc": "lib/zstd/zstd_decompress_module.c:21",
      "file": "lib/zstd/zstd_decompress_module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/zstd_wrapper.c:zstd_uncompress",
        "security/apparmor/apparmorfs.c:decompress_zstd",
        "security/apparmor/policy_unpack.c:compress_zstd",
        "drivers/base/firmware_loader/main.c:fw_decompress_zstd",
        "lib/decompress_unzstd.c:handle_zstd_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587666896,
      "name": "zstd_is_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
unsigned int zstd_is_error(size_t code)
```

```json
{
  "name": "zstd_is_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587932224,
      "name": "zstd_is_error",
      "external": true,
      "loc": "lib/zstd/zstd_decompress_module.c:21",
      "file": "lib/zstd/zstd_decompress_module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/zstd_wrapper.c:zstd_uncompress",
        "security/apparmor/apparmorfs.c:decompress_zstd",
        "security/apparmor/policy_unpack.c:compress_zstd",
        "drivers/base/firmware_loader/main.c:fw_decompress_zstd",
        "lib/decompress_unzstd.c:handle_zstd_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587932224,
      "name": "zstd_is_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
unsigned int zstd_is_error(size_t code)
```

```json
{
  "name": "zstd_is_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588267008,
      "name": "zstd_is_error",
      "external": true,
      "loc": "lib/zstd/zstd_decompress_module.c:21",
      "file": "lib/zstd/zstd_decompress_module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/zstd_wrapper.c:zstd_uncompress",
        "security/apparmor/apparmorfs.c:decompress_zstd",
        "security/apparmor/policy_unpack.c:compress_zstd",
        "drivers/base/firmware_loader/main.c:fw_decompress_zstd",
        "lib/decompress_unzstd.c:handle_zstd_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588267008,
      "name": "zstd_is_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
unsigned int zstd_is_error(size_t code)
```
</details>
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
