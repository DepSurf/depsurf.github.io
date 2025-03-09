# Function: <code>tpm1_do_selftest</code>

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
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585625792,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:637",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585625792,
      "name": "tpm1_do_selftest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:627",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585847427,
      "name": "tpm1_do_selftest.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071585846160,
      "name": "tpm1_do_selftest",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:627",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585989987,
      "name": "tpm1_do_selftest.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071585988720,
      "name": "tpm1_do_selftest",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:642",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586731085,
      "name": "tpm1_do_selftest.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071586729904,
      "name": "tpm1_do_selftest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:642",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591470573,
      "name": "tpm1_do_selftest.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071586825200,
      "name": "tpm1_do_selftest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:642",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591411840,
      "name": "tpm1_do_selftest.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071586705184,
      "name": "tpm1_do_selftest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:642",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592463780,
      "name": "tpm1_do_selftest.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071587254848,
      "name": "tpm1_do_selftest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:642",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594333689,
      "name": "tpm1_do_selftest.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071588564080,
      "name": "tpm1_do_selftest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590017904,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:642",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590017904,
      "name": "tpm1_do_selftest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590327200,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:642",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590327200,
      "name": "tpm1_do_selftest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590668592,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:642",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590668592,
      "name": "tpm1_do_selftest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498784272,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:627",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498784272,
      "name": "tpm1_do_selftest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231399012,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:627",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231399012,
      "name": "tpm1_do_selftest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291976640,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:627",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291976640,
      "name": "tpm1_do_selftest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276279992,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:627",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276279992,
      "name": "tpm1_do_selftest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:627",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585750963,
      "name": "tpm1_do_selftest.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071585749696,
      "name": "tpm1_do_selftest",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:627",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585610147,
      "name": "tpm1_do_selftest.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071585608880,
      "name": "tpm1_do_selftest",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:627",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585940003,
      "name": "tpm1_do_selftest.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071585938736,
      "name": "tpm1_do_selftest",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int tpm1_do_selftest(struct tpm_chip * chip)
```

```json
{
  "name": "tpm1_do_selftest",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm1_do_selftest",
      "external": true,
      "loc": "drivers/char/tpm/tpm1-cmd.c:627",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_auto_startup",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586047928,
      "name": "tpm1_do_selftest.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071586046688,
      "name": "tpm1_do_selftest",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int tpm1_do_selftest(struct tpm_chip * chip)
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
