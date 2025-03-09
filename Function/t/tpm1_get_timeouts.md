# Function: <code>tpm1_get_timeouts</code>

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
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585623936,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:345",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585623936,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:342",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585847024,
      "name": "tpm1_get_timeouts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071585844272,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 709
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
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:342",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585989584,
      "name": "tpm1_get_timeouts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071585986832,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 709
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
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:342",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586730691,
      "name": "tpm1_get_timeouts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071586728064,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 773
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
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:342",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591470179,
      "name": "tpm1_get_timeouts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071586823360,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 773
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
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:342",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591411446,
      "name": "tpm1_get_timeouts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    },
    {
      "addr": 18446744071586703344,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 773
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
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:342",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592463280,
      "name": "tpm1_get_timeouts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
    },
    {
      "addr": 18446744071587252784,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1003
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
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:342",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594333080,
      "name": "tpm1_get_timeouts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
    },
    {
      "addr": 18446744071588561792,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1157
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
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:342",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596239606,
      "name": "tpm1_get_timeouts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071590015072,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1645
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:342",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596767779,
      "name": "tpm1_get_timeouts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071590324384,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1628
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:342",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597676440,
      "name": "tpm1_get_timeouts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071590665776,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1623
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
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498781904,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:342",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498781904,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1040
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
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231396496,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:342",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231396496,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1060
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
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291973664,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:342",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291973664,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1244
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
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276276694,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:342",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276276694,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1376
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
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:342",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585750560,
      "name": "tpm1_get_timeouts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071585747808,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 709
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
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:342",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585609744,
      "name": "tpm1_get_timeouts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071585606992,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 709
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
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:342",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585939600,
      "name": "tpm1_get_timeouts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071585936848,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 709
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
int tpm1_get_timeouts(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_get_timeouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_get_timeouts",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:342",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_timeouts",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586047536,
      "name": "tpm1_get_timeouts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    },
    {
      "addr": 18446744071586044832,
      "name": "tpm1_get_timeouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 709
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
int tpm1_get_timeouts(struct tpm_chip * chip)
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
