# Function: <code>arch_ima_get_secureboot</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
bool arch_ima_get_secureboot()
```

```json
{
  "name": "arch_ima_get_secureboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_ima_get_secureboot",
      "external": true,
      "loc": "arch/x86/kernel/ima_arch.c:42",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579339997,
      "name": "arch_ima_get_secureboot.cold.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071579339712,
      "name": "arch_ima_get_secureboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
bool arch_ima_get_secureboot()
```

```json
{
  "name": "arch_ima_get_secureboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_ima_get_secureboot",
      "external": true,
      "loc": "arch/x86/kernel/ima_arch.c:56",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355309,
      "name": "arch_ima_get_secureboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071579354928,
      "name": "arch_ima_get_secureboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
bool arch_ima_get_secureboot()
```

```json
{
  "name": "arch_ima_get_secureboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_ima_get_secureboot",
      "external": true,
      "loc": "arch/x86/kernel/ima_arch.c:54",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359581,
      "name": "arch_ima_get_secureboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071579359264,
      "name": "arch_ima_get_secureboot",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_ima_get_secureboot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_ima_get_secureboot",
      "external": false,
      "loc": "include/linux/ima.h:38",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_ima_get_secureboot",
      "external": false,
      "loc": "include/linux/ima.h:38",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "arch_ima_get_secureboot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_ima_get_secureboot",
      "external": false,
      "loc": "include/linux/ima.h:49",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_ima_get_secureboot",
      "external": false,
      "loc": "include/linux/ima.h:49",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "arch_ima_get_secureboot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_ima_get_secureboot",
      "external": false,
      "loc": "include/linux/ima.h:55",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_ima_get_secureboot",
      "external": false,
      "loc": "include/linux/ima.h:55",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "arch_ima_get_secureboot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_ima_get_secureboot",
      "external": false,
      "loc": "include/linux/ima.h:57",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_ima_get_secureboot",
      "external": false,
      "loc": "include/linux/ima.h:57",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool arch_ima_get_secureboot()
```

```json
{
  "name": "arch_ima_get_secureboot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585434005,
      "name": "arch_ima_get_secureboot",
      "external": true,
      "loc": "security/integrity/ima/ima_efi.c:33",
      "file": "security/integrity/ima/ima_efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_efi.c:arch_get_ima_policy"
      ],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/ima/ima_main.c:ima_load_data",
        "security/integrity/ima/ima_appraise.c:ima_appraise_parse_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594092418,
      "name": "arch_ima_get_secureboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585433872,
      "name": "arch_ima_get_secureboot",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool arch_ima_get_secureboot()
```

```json
{
  "name": "arch_ima_get_secureboot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586191205,
      "name": "arch_ima_get_secureboot",
      "external": true,
      "loc": "security/integrity/ima/ima_efi.c:33",
      "file": "security/integrity/ima/ima_efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_efi.c:arch_get_ima_policy"
      ],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/ima/ima_main.c:ima_load_data",
        "security/integrity/ima/ima_appraise.c:ima_appraise_parse_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596103208,
      "name": "arch_ima_get_secureboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586191056,
      "name": "arch_ima_get_secureboot",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool arch_ima_get_secureboot()
```

```json
{
  "name": "arch_ima_get_secureboot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586428933,
      "name": "arch_ima_get_secureboot",
      "external": true,
      "loc": "security/integrity/ima/ima_efi.c:33",
      "file": "security/integrity/ima/ima_efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_efi.c:arch_get_ima_policy"
      ],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/ima/ima_main.c:ima_load_data",
        "security/integrity/ima/ima_appraise.c:ima_appraise_parse_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596626314,
      "name": "arch_ima_get_secureboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586428784,
      "name": "arch_ima_get_secureboot",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool arch_ima_get_secureboot()
```

```json
{
  "name": "arch_ima_get_secureboot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586694085,
      "name": "arch_ima_get_secureboot",
      "external": true,
      "loc": "security/integrity/ima/ima_efi.c:33",
      "file": "security/integrity/ima/ima_efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_efi.c:arch_get_ima_policy"
      ],
      "caller_func": [
        "security/integrity/platform_certs/load_uefi.c:load_uefi_certs",
        "security/integrity/ima/ima_main.c:ima_load_data",
        "security/integrity/ima/ima_appraise.c:ima_appraise_parse_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597531956,
      "name": "arch_ima_get_secureboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586693936,
      "name": "arch_ima_get_secureboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "arch_ima_get_secureboot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_ima_get_secureboot",
      "external": false,
      "loc": "include/linux/ima.h:37",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool arch_ima_get_secureboot()
```

```json
{
  "name": "arch_ima_get_secureboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282709904,
      "name": "arch_ima_get_secureboot",
      "external": true,
      "loc": "arch/powerpc/kernel/ima_arch.c:10",
      "file": "arch/powerpc/kernel/ima_arch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282709904,
      "name": "arch_ima_get_secureboot",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
bool arch_ima_get_secureboot()
```

```json
{
  "name": "arch_ima_get_secureboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_ima_get_secureboot",
      "external": true,
      "loc": "arch/x86/kernel/ima_arch.c:54",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355485,
      "name": "arch_ima_get_secureboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071579355168,
      "name": "arch_ima_get_secureboot",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
bool arch_ima_get_secureboot()
```

```json
{
  "name": "arch_ima_get_secureboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_ima_get_secureboot",
      "external": true,
      "loc": "arch/x86/kernel/ima_arch.c:54",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287757,
      "name": "arch_ima_get_secureboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071579287440,
      "name": "arch_ima_get_secureboot",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
bool arch_ima_get_secureboot()
```

```json
{
  "name": "arch_ima_get_secureboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_ima_get_secureboot",
      "external": true,
      "loc": "arch/x86/kernel/ima_arch.c:54",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355405,
      "name": "arch_ima_get_secureboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071579355088,
      "name": "arch_ima_get_secureboot",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
bool arch_ima_get_secureboot()
```

```json
{
  "name": "arch_ima_get_secureboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_ima_get_secureboot",
      "external": true,
      "loc": "arch/x86/kernel/ima_arch.c:54",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579363853,
      "name": "arch_ima_get_secureboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071579363536,
      "name": "arch_ima_get_secureboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
bool arch_ima_get_secureboot()
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
bool arch_ima_get_secureboot()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool arch_ima_get_secureboot()
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool arch_ima_get_secureboot()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool arch_ima_get_secureboot()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool arch_ima_get_secureboot()
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
