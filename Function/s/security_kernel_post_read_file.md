# Function: <code>security_kernel_post_read_file</code>

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
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582457072,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:935",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582457072,
      "name": "security_kernel_post_read_file",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582549536,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:956",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582549536,
      "name": "security_kernel_post_read_file",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582635648,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1593",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582635648,
      "name": "security_kernel_post_read_file",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582789456,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1555",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582789456,
      "name": "security_kernel_post_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582989104,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1059",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582989104,
      "name": "security_kernel_post_read_file",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583100736,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1656",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583100736,
      "name": "security_kernel_post_read_file",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583286016,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1675",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583286016,
      "name": "security_kernel_post_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583391392,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1714",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583391392,
      "name": "security_kernel_post_read_file",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583730896,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1898",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583730896,
      "name": "security_kernel_post_read_file",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583851088,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1901",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernel_read_file.c:kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583851088,
      "name": "security_kernel_post_read_file",
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
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583876352,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1951",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernel_read_file.c:kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583876352,
      "name": "security_kernel_post_read_file",
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
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584240528,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1959",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernel_read_file.c:kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584240528,
      "name": "security_kernel_post_read_file",
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
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584846656,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1964",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernel_read_file.c:kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584846656,
      "name": "security_kernel_post_read_file",
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
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585549024,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:2011",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernel_read_file.c:kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585549024,
      "name": "security_kernel_post_read_file",
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
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585779648,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:3222",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernel_read_file.c:kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585779648,
      "name": "security_kernel_post_read_file",
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
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586028192,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:3294",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/kernel_read_file.c:kernel_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586028192,
      "name": "security_kernel_post_read_file",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495142336,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1714",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495142336,
      "name": "security_kernel_post_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228530096,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1714",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228530096,
      "name": "security_kernel_post_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289060800,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1714",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289060800,
      "name": "security_kernel_post_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274391738,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1714",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274391738,
      "name": "security_kernel_post_read_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583360128,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1714",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583360128,
      "name": "security_kernel_post_read_file",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583297232,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1714",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583297232,
      "name": "security_kernel_post_read_file",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583343904,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1714",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583343904,
      "name": "security_kernel_post_read_file",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
```

```json
{
  "name": "security_kernel_post_read_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583439088,
      "name": "security_kernel_post_read_file",
      "external": true,
      "loc": "security/security.c:1714",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_read_file",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439088,
      "name": "security_kernel_post_read_file",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int security_kernel_post_read_file(struct file * file, char * buf, loff_t size, enum kernel_read_file_id id)
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
