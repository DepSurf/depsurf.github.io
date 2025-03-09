# Function: <code>__fw_state_wait_common</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __fw_state_wait_common(struct fw_state * fw_st, long int timeout)
```

```json
{
  "name": "__fw_state_wait_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585012416,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_class.c:130",
      "file": "drivers/base/firmware_class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585012416,
      "name": "__fw_state_wait_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
int __fw_state_wait_common(struct fw_state * fw_st, long int timeout)
```

```json
{
  "name": "__fw_state_wait_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585097760,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_class.c:129",
      "file": "drivers/base/firmware_class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585097760,
      "name": "__fw_state_wait_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int __fw_state_wait_common(struct fw_state * fw_st, long int timeout)
```

```json
{
  "name": "__fw_state_wait_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585523584,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_class.c:131",
      "file": "drivers/base/firmware_class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585523584,
      "name": "__fw_state_wait_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585769758,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:88",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585774506,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:88",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585903498,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:88",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585908129,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:88",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586143110,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586146999,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586291590,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586295461,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587059672,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:94",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587064463,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:94",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback"
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
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587144396,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:99",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587149369,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:99",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback"
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
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587031500,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:99",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587036675,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:99",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback"
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
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587600489,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:99",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587603987,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:99",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback"
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
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588938895,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:100",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588940548,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:100",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback"
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
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590453274,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:98",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590455082,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:98",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback"
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
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590773514,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:98",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590775322,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:98",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback"
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
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591116106,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:99",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591117940,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:99",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499124092,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499128152,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231672156,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 3231675892,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292312788,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292317636,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276439538,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276442620,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586054838,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586058709,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585900790,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585904661,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586240760,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586244773,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fw_state_wait_common",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586350573,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:_request_firmware"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586354373,
      "name": "__fw_state_wait_common",
      "external": false,
      "loc": "drivers/base/firmware_loader/firmware.h:90",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int __fw_state_wait_common(struct fw_state * fw_st, long int timeout)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int __fw_state_wait_common(struct fw_state * fw_st, long int timeout)
```
</details>
</li>
</ul>
