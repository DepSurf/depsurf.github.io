# Function: <code>tpm1_pm_suspend</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585626304,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:732",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585626304,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:722",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585847553,
      "name": "tpm1_pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071585846576,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:722",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585990113,
      "name": "tpm1_pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071585989136,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:737",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586731211,
      "name": "tpm1_pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071586730288,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:737",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591470699,
      "name": "tpm1_pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071586825584,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:737",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591411966,
      "name": "tpm1_pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071586705568,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:737",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592463911,
      "name": "tpm1_pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071587255232,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:737",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594333818,
      "name": "tpm1_pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588564528,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590018512,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:742",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590018512,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590327808,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:742",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590327808,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590669200,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:742",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590669200,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498784896,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:722",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498784896,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231399592,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:722",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231399592,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291977424,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:722",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291977424,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276280540,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:722",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276280540,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:722",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585751089,
      "name": "tpm1_pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071585750112,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:722",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585610273,
      "name": "tpm1_pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071585609296,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:722",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585940129,
      "name": "tpm1_pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071585939152,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
```

```json
{
  "name": "tpm1_pm_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_pm_suspend",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:722",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586048054,
      "name": "tpm1_pm_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071586047104,
      "name": "tpm1_pm_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int tpm1_pm_suspend(struct tpm_chip * chip, u32 tpm_suspend_pcr)
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
