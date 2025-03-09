# Function: <code>fw_get_filesystem_firmware</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584478809,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_class.c:325",
      "file": "drivers/base/firmware_class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:_request_firmware"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584824270,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_class.c:318",
      "file": "drivers/base/firmware_class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:_request_firmware"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585017452,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_class.c:386",
      "file": "drivers/base/firmware_class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:_request_firmware"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585103299,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_class.c:382",
      "file": "drivers/base/firmware_class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:_request_firmware"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585529236,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_class.c:386",
      "file": "drivers/base/firmware_class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:_request_firmware"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585770041,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:290",
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
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585903166,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:296",
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
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:457",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586138816,
      "name": "fw_get_filesystem_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
    },
    {
      "addr": 18446744071586144272,
      "name": "fw_get_filesystem_firmware.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:457",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586287296,
      "name": "fw_get_filesystem_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
    },
    {
      "addr": 18446744071586292752,
      "name": "fw_get_filesystem_firmware.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:462",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587055936,
      "name": "fw_get_filesystem_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
    },
    {
      "addr": 18446744071587062666,
      "name": "fw_get_filesystem_firmware.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:483",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587140352,
      "name": "fw_get_filesystem_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
    },
    {
      "addr": 18446744071591489867,
      "name": "fw_get_filesystem_firmware.cold",
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
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:484",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587027664,
      "name": "fw_get_filesystem_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 707
    },
    {
      "addr": 18446744071591432891,
      "name": "fw_get_filesystem_firmware.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:485",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587594944,
      "name": "fw_get_filesystem_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 810
    },
    {
      "addr": 18446744071592493605,
      "name": "fw_get_filesystem_firmware.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:488",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588932800,
      "name": "fw_get_filesystem_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 833
    },
    {
      "addr": 18446744071594363739,
      "name": "fw_get_filesystem_firmware.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590446800,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:488",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590446800,
      "name": "fw_get_filesystem_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 839
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
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590766832,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:488",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590766832,
      "name": "fw_get_filesystem_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 951
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
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591109216,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:489",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591109216,
      "name": "fw_get_filesystem_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 951
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
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499118800,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:457",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499118800,
      "name": "fw_get_filesystem_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231668188,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:457",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231668188,
      "name": "fw_get_filesystem_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
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
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292305664,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:457",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292305664,
      "name": "fw_get_filesystem_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 900
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
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276436526,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:457",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276436526,
      "name": "fw_get_filesystem_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
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
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:457",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586050544,
      "name": "fw_get_filesystem_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
    },
    {
      "addr": 18446744071586056000,
      "name": "fw_get_filesystem_firmware.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:457",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585896496,
      "name": "fw_get_filesystem_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
    },
    {
      "addr": 18446744071585901952,
      "name": "fw_get_filesystem_firmware.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586240378,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:457",
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
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```

```json
{
  "name": "fw_get_filesystem_firmware",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fw_get_filesystem_firmware",
      "external": false,
      "loc": "drivers/base/firmware_loader/main.c:457",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586346624,
      "name": "fw_get_filesystem_firmware",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
    },
    {
      "addr": 18446744071586351744,
      "name": "fw_get_filesystem_firmware.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
int fw_get_filesystem_firmware(struct device * device, struct fw_priv * fw_priv, const char * suffix, int (*)(struct device *, struct fw_priv *, size_t, const void *) decompress)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
