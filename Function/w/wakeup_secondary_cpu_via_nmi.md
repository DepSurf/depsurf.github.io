# Function: <code>wakeup_secondary_cpu_via_nmi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579179184,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:657",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579179184,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579179600,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:676",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579179600,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579190176,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:700",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579190176,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579188464,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:703",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188464,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579204240,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:640",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579204240,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:693",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219903,
      "name": "wakeup_secondary_cpu_via_nmi.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579215856,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:694",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579243593,
      "name": "wakeup_secondary_cpu_via_nmi.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579239536,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:746",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579257652,
      "name": "wakeup_secondary_cpu_via_nmi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579254096,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:746",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259316,
      "name": "wakeup_secondary_cpu_via_nmi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579255808,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:759",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286277,
      "name": "wakeup_secondary_cpu_via_nmi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579283040,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:754",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591258738,
      "name": "wakeup_secondary_cpu_via_nmi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579290320,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:755",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591201868,
      "name": "wakeup_secondary_cpu_via_nmi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579293040,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:757",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592072642,
      "name": "wakeup_secondary_cpu_via_nmi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579339952,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:800",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593839199,
      "name": "wakeup_secondary_cpu_via_nmi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579400848,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:798",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595965332,
      "name": "wakeup_secondary_cpu_via_nmi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071579481056,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:746",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258020,
      "name": "wakeup_secondary_cpu_via_nmi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579254512,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:746",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579193209,
      "name": "wakeup_secondary_cpu_via_nmi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579189744,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:746",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259220,
      "name": "wakeup_secondary_cpu_via_nmi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579255712,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```

```json
{
  "name": "wakeup_secondary_cpu_via_nmi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wakeup_secondary_cpu_via_nmi",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:746",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:do_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579264820,
      "name": "wakeup_secondary_cpu_via_nmi.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579261280,
      "name": "wakeup_secondary_cpu_via_nmi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip)
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
