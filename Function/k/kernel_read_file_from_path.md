# Function: <code>kernel_read_file_from_path</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int kernel_read_file_from_path(char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581177520,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/exec.c:958",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "drivers/base/firmware_class.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581177520,
      "name": "kernel_read_file_from_path",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int kernel_read_file_from_path(char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581254640,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/exec.c:963",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "drivers/base/firmware_class.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581254640,
      "name": "kernel_read_file_from_path",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int kernel_read_file_from_path(char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581304048,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/exec.c:989",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "drivers/base/firmware_class.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581304048,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int kernel_read_file_from_path(const char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581444192,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/exec.c:970",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "drivers/base/firmware_class.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581444192,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int kernel_read_file_from_path(const char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581602720,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/exec.c:974",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581602720,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int kernel_read_file_from_path(const char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581689408,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/exec.c:977",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581689408,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int kernel_read_file_from_path(const char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581807520,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/exec.c:978",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581807520,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int kernel_read_file_from_path(const char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581880112,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/exec.c:978",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581880112,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int kernel_read_file_from_path(const char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582105568,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/exec.c:1003",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_read_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582105568,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int kernel_read_file_from_path(const char * path, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582408080,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/kernel_read_file.c:127",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_read_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582408080,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int kernel_read_file_from_path(const char * path, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582435280,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/kernel_read_file.c:127",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_read_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435280,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int kernel_read_file_from_path(const char * path, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582758048,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/kernel_read_file.c:127",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_read_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582758048,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int kernel_read_file_from_path(const char * path, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583306848,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/kernel_read_file.c:127",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_read_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583306848,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
ssize_t kernel_read_file_from_path(const char * path, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583892448,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/kernel_read_file.c:127",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_read_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583892448,
      "name": "kernel_read_file_from_path",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
ssize_t kernel_read_file_from_path(const char * path, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584114320,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/kernel_read_file.c:127",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_read_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584114320,
      "name": "kernel_read_file_from_path",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
ssize_t kernel_read_file_from_path(const char * path, loff_t offset, void * * buf, size_t buf_size, size_t * file_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584330672,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/kernel_read_file.c:127",
      "file": "fs/kernel_read_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_read_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584330672,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int kernel_read_file_from_path(const char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493353448,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/exec.c:978",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493353448,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int kernel_read_file_from_path(const char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226945068,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/exec.c:978",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226945068,
      "name": "kernel_read_file_from_path",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int kernel_read_file_from_path(const char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286901248,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/exec.c:978",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286901248,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int kernel_read_file_from_path(const char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273080226,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/exec.c:978",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273080226,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int kernel_read_file_from_path(const char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581848848,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/exec.c:978",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581848848,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int kernel_read_file_from_path(const char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581786512,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/exec.c:978",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786512,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int kernel_read_file_from_path(const char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581840160,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/exec.c:978",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581840160,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int kernel_read_file_from_path(const char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```

```json
{
  "name": "kernel_read_file_from_path",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581909664,
      "name": "kernel_read_file_from_path",
      "external": true,
      "loc": "fs/exec.c:978",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/digsig.c:integrity_load_x509",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581909664,
      "name": "kernel_read_file_from_path",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int kernel_read_file_from_path(char * path, void * * buf, loff_t * size, loff_t max_size, enum kernel_read_file_id id)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * path</code> ➡️ <code>const char * path</code>
</li>
</ul>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
