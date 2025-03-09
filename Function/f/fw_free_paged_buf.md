# Function: <code>fw_free_paged_buf</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fw_free_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_free_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586139311,
      "name": "fw_free_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:271",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586138720,
      "name": "fw_free_paged_buf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071586141216,
      "name": "fw_free_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fw_free_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_free_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586287791,
      "name": "fw_free_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:271",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586287200,
      "name": "fw_free_paged_buf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071586289696,
      "name": "fw_free_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fw_free_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_free_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587056466,
      "name": "fw_free_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:278",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587055824,
      "name": "fw_free_paged_buf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071587060064,
      "name": "fw_free_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void fw_free_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_free_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587140742,
      "name": "fw_free_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:299",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587140240,
      "name": "fw_free_paged_buf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071587144560,
      "name": "fw_free_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void fw_free_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_free_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587028101,
      "name": "fw_free_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:300",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587027552,
      "name": "fw_free_paged_buf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071587031664,
      "name": "fw_free_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void fw_free_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_free_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587595408,
      "name": "fw_free_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:301",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587594832,
      "name": "fw_free_paged_buf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071587598720,
      "name": "fw_free_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void fw_free_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_free_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588933283,
      "name": "fw_free_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:238",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/firmware_loader/sysfs.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588932448,
      "name": "fw_free_paged_buf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    },
    {
      "addr": 18446744071588936816,
      "name": "fw_free_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void fw_free_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_free_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590447285,
      "name": "fw_free_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:238",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/firmware_loader/sysfs.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590446416,
      "name": "fw_free_paged_buf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    },
    {
      "addr": 18446744071590451024,
      "name": "fw_free_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void fw_free_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_free_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590767395,
      "name": "fw_free_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:238",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/firmware_loader/sysfs.c:firmware_loading_store",
        "drivers/base/firmware_loader/sysfs_upload.c:fw_upload_start",
        "drivers/base/firmware_loader/sysfs_upload.c:fw_upload_main"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590766448,
      "name": "fw_free_paged_buf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071590771168,
      "name": "fw_free_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void fw_free_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_free_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591109779,
      "name": "fw_free_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:239",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/firmware_loader/sysfs.c:firmware_loading_store",
        "drivers/base/firmware_loader/sysfs_upload.c:fw_upload_start",
        "drivers/base/firmware_loader/sysfs_upload.c:fw_upload_main"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591108832,
      "name": "fw_free_paged_buf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    },
    {
      "addr": 18446744071591113712,
      "name": "fw_free_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void fw_free_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_free_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499119316,
      "name": "fw_free_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:271",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:free_fw_priv"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:free_fw_priv",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499118704,
      "name": "fw_free_paged_buf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446603336499121712,
      "name": "fw_free_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void fw_free_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_free_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231668652,
      "name": "fw_free_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:271",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:free_fw_priv"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:free_fw_priv",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231668088,
      "name": "fw_free_paged_buf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 3231670128,
      "name": "fw_free_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void fw_free_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_free_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292306316,
      "name": "fw_free_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:271",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:free_fw_priv"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:free_fw_priv",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292305504,
      "name": "fw_free_paged_buf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 13835058055292309632,
      "name": "fw_free_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void fw_free_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_free_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276436888,
      "name": "fw_free_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:271",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276436428,
      "name": "fw_free_paged_buf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446743936276437828,
      "name": "fw_free_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fw_free_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_free_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586051039,
      "name": "fw_free_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:271",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586050448,
      "name": "fw_free_paged_buf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071586052944,
      "name": "fw_free_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fw_free_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_free_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585896991,
      "name": "fw_free_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:271",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585896400,
      "name": "fw_free_paged_buf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071585898896,
      "name": "fw_free_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fw_free_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_free_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586238363,
      "name": "fw_free_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:271",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:__free_fw_priv"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586237216,
      "name": "fw_free_paged_buf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071586239088,
      "name": "fw_free_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fw_free_paged_buf(struct fw_priv * fw_priv)
```

```json
{
  "name": "fw_free_paged_buf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586347119,
      "name": "fw_free_paged_buf",
      "external": true,
      "loc": "drivers/base/firmware_loader/main.c:271",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv"
      ],
      "caller_func": [
        "drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/firmware_loader/fallback.c:firmware_loading_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586346528,
      "name": "fw_free_paged_buf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071586348688,
      "name": "fw_free_paged_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void fw_free_paged_buf(struct fw_priv * fw_priv)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
