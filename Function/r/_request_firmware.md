# Function: <code>_request_firmware</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, unsigned int opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584478016,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_class.c:1118",
      "file": "drivers/base/firmware_class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:request_firmware",
        "drivers/base/firmware_class.c:request_firmware_direct",
        "drivers/base/firmware_class.c:request_firmware_work_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584478016,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2801
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, unsigned int opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584823584,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_class.c:1133",
      "file": "drivers/base/firmware_class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:request_firmware_work_func",
        "drivers/base/firmware_class.c:request_firmware_into_buf",
        "drivers/base/firmware_class.c:request_firmware_direct",
        "drivers/base/firmware_class.c:request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584823584,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2865
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
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, unsigned int opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585016992,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_class.c:1168",
      "file": "drivers/base/firmware_class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:request_firmware_work_func",
        "drivers/base/firmware_class.c:request_firmware_into_buf",
        "drivers/base/firmware_class.c:request_firmware_direct",
        "drivers/base/firmware_class.c:request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585016992,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2641
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
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, unsigned int opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585102640,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_class.c:1191",
      "file": "drivers/base/firmware_class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:request_firmware_work_func",
        "drivers/base/firmware_class.c:request_firmware_into_buf",
        "drivers/base/firmware_class.c:request_firmware_direct",
        "drivers/base/firmware_class.c:request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585102640,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2216
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
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, unsigned int opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585528528,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_class.c:1198",
      "file": "drivers/base/firmware_class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:request_firmware_work_func",
        "drivers/base/firmware_class.c:request_firmware_into_buf",
        "drivers/base/firmware_class.c:request_firmware_direct",
        "drivers/base/firmware_class.c:request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585528528,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2311
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
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, enum fw_opt opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585769440,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:559",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585769440,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1410
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
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, enum fw_opt opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585902656,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:567",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585902656,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1448
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, enum fw_opt opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:751",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586142416,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1037
    },
    {
      "addr": 18446744071586144377,
      "name": "_request_firmware.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, enum fw_opt opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:751",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586290896,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1037
    },
    {
      "addr": 18446744071586292857,
      "name": "_request_firmware.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, u32 opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:755",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:cache_firmware",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:firmware_request_platform",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587061344,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 18446744071587062804,
      "name": "_request_firmware.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, size_t offset, u32 opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:790",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:cache_firmware",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:request_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:firmware_request_platform",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587145856,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
    },
    {
      "addr": 18446744071591490006,
      "name": "_request_firmware.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, size_t offset, u32 opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:794",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:request_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:firmware_request_platform",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033040,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
    },
    {
      "addr": 18446744071591433031,
      "name": "_request_firmware.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, size_t offset, u32 opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:793",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:request_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:firmware_request_platform",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587600064,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 765
    },
    {
      "addr": 18446744071592493763,
      "name": "_request_firmware.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, size_t offset, u32 opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:796",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:request_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:firmware_request_platform",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588938192,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 953
    },
    {
      "addr": 18446744071594363888,
      "name": "_request_firmware.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, size_t offset, u32 opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590452544,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:796",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:request_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:firmware_request_platform",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590452544,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
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
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, size_t offset, u32 opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590772784,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:849",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:request_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:firmware_request_platform",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590772784,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 988
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
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, size_t offset, u32 opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591115328,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:850",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:request_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:firmware_request_platform",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591115328,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1036
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
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, enum fw_opt opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499123256,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:751",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499123256,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
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
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, enum fw_opt opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231671364,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:751",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231671364,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1120
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
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, enum fw_opt opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292311488,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:751",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292311488,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1776
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
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, enum fw_opt opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276438760,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:751",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_firmware_into_buf",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276438760,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1098
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, enum fw_opt opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:751",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586054144,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1037
    },
    {
      "addr": 18446744071586056105,
      "name": "_request_firmware.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, enum fw_opt opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:751",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585900096,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1037
    },
    {
      "addr": 18446744071585902057,
      "name": "_request_firmware.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, enum fw_opt opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:751",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586239840,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1472
    },
    {
      "addr": 18446744071586242128,
      "name": "_request_firmware.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int _request_firmware(const struct firmware * * firmware_p, const char * name, struct device * device, void * buf, size_t size, enum fw_opt opt_flags)
```

```json
{
  "name": "_request_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_request_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:751",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:request_firmware_direct",
        "drivers/base/firmware_loader/main.c:firmware_request_nowarn",
        "drivers/base/firmware_loader/main.c:request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586349888,
      "name": "_request_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1026
    },
    {
      "addr": 18446744071586351849,
      "name": "_request_firmware.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * buf</code>
</li>
<li>
<b>Param added. </b>
<code>size_t size</code>
</li>
<li>
<b>Param reordered. </b>
<code>firmware_p, name, device, opt_flags</code> ➡️ <code>firmware_p, name, device, buf, size, opt_flags</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int opt_flags</code> ➡️ <code>enum fw_opt opt_flags</code>
</li>
</ul>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum fw_opt opt_flags</code> ➡️ <code>u32 opt_flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t offset</code>
</li>
<li>
<b>Param reordered. </b>
<code>firmware_p, name, device, buf, size, opt_flags</code> ➡️ <code>firmware_p, name, device, buf, size, offset, opt_flags</code>
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
