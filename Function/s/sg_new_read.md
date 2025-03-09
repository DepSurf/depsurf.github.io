# Function: <code>sg_new_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584887072,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:546",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_read",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584887072,
      "name": "sg_new_read.isra.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585249536,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:546",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585249536,
      "name": "sg_new_read.isra.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585449312,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:535",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585449312,
      "name": "sg_new_read.isra.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585536080,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:535",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585536080,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585966512,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:535",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585966512,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586214560,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:570",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586214560,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586356704,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:570",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586356704,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586600080,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:565",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586600080,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586747520,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:565",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586747520,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587554384,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:559",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587554384,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587619280,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:559",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587619280,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587500528,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:559",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587500528,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588077184,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:562",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588077184,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589442688,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:558",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589442688,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591020000,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:558",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591020000,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591373760,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:558",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591373760,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591724208,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:558",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591724208,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499670584,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:565",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499670584,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1016
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232114780,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:565",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232114780,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292987456,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:565",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292987456,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276841500,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:565",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276841500,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586438000,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:565",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586438000,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586314256,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:565",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586314256,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586702080,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:565",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586702080,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```

```json
{
  "name": "sg_new_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586808080,
      "name": "sg_new_read",
      "external": false,
      "loc": "drivers/scsi/sg.c:565",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586808080,
      "name": "sg_new_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
ssize_t sg_new_read(Sg_fd * sfp, char * buf, size_t count, Sg_request * srp)
```
</details>
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
