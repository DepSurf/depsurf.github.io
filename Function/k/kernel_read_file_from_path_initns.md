# Function: <code>kernel_read_file_from_path_initns</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int kernel_read_file_from_path_initns(const char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path_initns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582110320,
      "name": "kernel_read_file_from_path_initns",
      "external": true,
      "loc": "fs/exec.c:1022",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582110320,
      "name": "kernel_read_file_from_path_initns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int kernel_read_file_from_path_initns(const char * path, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path_initns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582408368,
      "name": "kernel_read_file_from_path_initns",
      "external": true,
      "loc": "fs/kernel_read_file.c:147",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582408368,
      "name": "kernel_read_file_from_path_initns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int kernel_read_file_from_path_initns(const char * path, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path_initns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582435568,
      "name": "kernel_read_file_from_path_initns",
      "external": true,
      "loc": "fs/kernel_read_file.c:147",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435568,
      "name": "kernel_read_file_from_path_initns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int kernel_read_file_from_path_initns(const char * path, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path_initns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582758336,
      "name": "kernel_read_file_from_path_initns",
      "external": true,
      "loc": "fs/kernel_read_file.c:147",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582758336,
      "name": "kernel_read_file_from_path_initns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
int kernel_read_file_from_path_initns(const char * path, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path_initns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583307008,
      "name": "kernel_read_file_from_path_initns",
      "external": true,
      "loc": "fs/kernel_read_file.c:147",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583307008,
      "name": "kernel_read_file_from_path_initns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
ssize_t kernel_read_file_from_path_initns(const char * path, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path_initns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583892624,
      "name": "kernel_read_file_from_path_initns",
      "external": true,
      "loc": "fs/kernel_read_file.c:147",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583892624,
      "name": "kernel_read_file_from_path_initns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
ssize_t kernel_read_file_from_path_initns(const char * path, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path_initns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584114496,
      "name": "kernel_read_file_from_path_initns",
      "external": true,
      "loc": "fs/kernel_read_file.c:147",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584114496,
      "name": "kernel_read_file_from_path_initns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
ssize_t kernel_read_file_from_path_initns(const char * path, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path_initns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584330848,
      "name": "kernel_read_file_from_path_initns",
      "external": true,
      "loc": "fs/kernel_read_file.c:147",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584330848,
      "name": "kernel_read_file_from_path_initns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int kernel_read_file_from_path_initns(const char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>loff_t offset</code>
</li>
<li>
<b>Param added. </b>
<code>size_t buf_size</code>
</li>
<li>
<b>Param added. </b>
<code>size_t * file_size</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t * size</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t max_size</code>
</li>
<li>
<b>Param reordered. </b>
<code>path, buf, size, max_size, id</code> ➡️ <code>path, offset, buf, buf_size, file_size, id</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
