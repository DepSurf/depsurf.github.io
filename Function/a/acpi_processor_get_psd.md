# Function: <code>acpi_processor_get_psd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583757359,
      "name": "acpi_processor_get_psd",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:529",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
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
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584083341,
      "name": "acpi_processor_get_psd",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:529",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
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
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584225694,
      "name": "acpi_processor_get_psd",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:538",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
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
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584297813,
      "name": "acpi_processor_get_psd",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:536",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
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
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584697019,
      "name": "acpi_processor_get_psd",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:536",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```

```json
{
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_psd",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:537",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584924929,
      "name": "acpi_processor_get_psd.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071584920896,
      "name": "acpi_processor_get_psd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```

```json
{
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_psd",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:537",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585028833,
      "name": "acpi_processor_get_psd.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071585024800,
      "name": "acpi_processor_get_psd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```

```json
{
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_psd",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:524",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585232595,
      "name": "acpi_processor_get_psd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071585228544,
      "name": "acpi_processor_get_psd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```

```json
{
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_psd",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:510",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585369323,
      "name": "acpi_processor_get_psd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071585365184,
      "name": "acpi_processor_get_psd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```

```json
{
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_psd",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:510",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586077376,
      "name": "acpi_processor_get_psd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071586073520,
      "name": "acpi_processor_get_psd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```

```json
{
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_psd",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:509",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591439662,
      "name": "acpi_processor_get_psd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071586194976,
      "name": "acpi_processor_get_psd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```

```json
{
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_psd",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:507",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591380853,
      "name": "acpi_processor_get_psd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071586070272,
      "name": "acpi_processor_get_psd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```

```json
{
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_psd",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:505",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592417426,
      "name": "acpi_processor_get_psd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071586564992,
      "name": "acpi_processor_get_psd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```

```json
{
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_psd",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:505",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594285101,
      "name": "acpi_processor_get_psd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071587824032,
      "name": "acpi_processor_get_psd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```

```json
{
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589164464,
      "name": "acpi_processor_get_psd",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:501",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589164464,
      "name": "acpi_processor_get_psd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```

```json
{
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589457840,
      "name": "acpi_processor_get_psd",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:523",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589457840,
      "name": "acpi_processor_get_psd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```

```json
{
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589765840,
      "name": "acpi_processor_get_psd",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:523",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589765840,
      "name": "acpi_processor_get_psd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```

```json
{
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497640056,
      "name": "acpi_processor_get_psd",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:510",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497640056,
      "name": "acpi_processor_get_psd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```

```json
{
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_psd",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:510",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585168656,
      "name": "acpi_processor_get_psd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071585165040,
      "name": "acpi_processor_get_psd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```

```json
{
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_psd",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:510",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585082896,
      "name": "acpi_processor_get_psd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071585079232,
      "name": "acpi_processor_get_psd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```

```json
{
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_psd",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:510",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585320907,
      "name": "acpi_processor_get_psd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071585316768,
      "name": "acpi_processor_get_psd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```

```json
{
  "name": "acpi_processor_get_psd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_psd",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:510",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance",
        "drivers/xen/xen-acpi-processor.c:read_acpi_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585427051,
      "name": "acpi_processor_get_psd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071585422912,
      "name": "acpi_processor_get_psd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package * pdomain)
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
