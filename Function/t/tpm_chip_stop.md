# Function: <code>tpm_chip_stop</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void tpm_chip_stop(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585836384,
      "name": "tpm_chip_stop",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:133",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_class_shutdown",
        "drivers/char/tpm/tpm-chip.c:tpm_put_ops",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585836384,
      "name": "tpm_chip_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void tpm_chip_stop(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585979040,
      "name": "tpm_chip_stop",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:133",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_class_shutdown",
        "drivers/char/tpm/tpm-chip.c:tpm_put_ops",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585979040,
      "name": "tpm_chip_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void tpm_chip_stop(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586721168,
      "name": "tpm_chip_stop",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:133",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_class_shutdown",
        "drivers/char/tpm/tpm-chip.c:tpm_put_ops",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721168,
      "name": "tpm_chip_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void tpm_chip_stop(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586816992,
      "name": "tpm_chip_stop",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:133",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_class_shutdown",
        "drivers/char/tpm/tpm-chip.c:tpm_put_ops",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586816992,
      "name": "tpm_chip_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void tpm_chip_stop(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586696896,
      "name": "tpm_chip_stop",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:133",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_class_shutdown",
        "drivers/char/tpm/tpm-chip.c:tpm_put_ops",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586696896,
      "name": "tpm_chip_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void tpm_chip_stop(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587246224,
      "name": "tpm_chip_stop",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:133",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_class_shutdown",
        "drivers/char/tpm/tpm-chip.c:tpm_put_ops",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587246224,
      "name": "tpm_chip_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void tpm_chip_stop(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588554960,
      "name": "tpm_chip_stop",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:133",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_class_shutdown",
        "drivers/char/tpm/tpm-chip.c:tpm_put_ops",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588554960,
      "name": "tpm_chip_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void tpm_chip_stop(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590006928,
      "name": "tpm_chip_stop",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:133",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_class_shutdown",
        "drivers/char/tpm/tpm-chip.c:tpm_put_ops",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590006928,
      "name": "tpm_chip_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void tpm_chip_stop(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590316480,
      "name": "tpm_chip_stop",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:133",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_class_shutdown",
        "drivers/char/tpm/tpm-chip.c:tpm_put_ops",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590316480,
      "name": "tpm_chip_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void tpm_chip_stop(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590657824,
      "name": "tpm_chip_stop",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:138",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_class_shutdown",
        "drivers/char/tpm/tpm-chip.c:tpm_put_ops",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590657824,
      "name": "tpm_chip_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void tpm_chip_stop(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498772984,
      "name": "tpm_chip_stop",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:133",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_class_shutdown",
        "drivers/char/tpm/tpm-chip.c:tpm_put_ops",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498772984,
      "name": "tpm_chip_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void tpm_chip_stop(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231388920,
      "name": "tpm_chip_stop",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:133",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_class_shutdown",
        "drivers/char/tpm/tpm-chip.c:tpm_put_ops",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231388920,
      "name": "tpm_chip_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void tpm_chip_stop(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291962496,
      "name": "tpm_chip_stop",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:133",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_class_shutdown",
        "drivers/char/tpm/tpm-chip.c:tpm_put_ops",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291962496,
      "name": "tpm_chip_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void tpm_chip_stop(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276268338,
      "name": "tpm_chip_stop",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:133",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_class_shutdown",
        "drivers/char/tpm/tpm-chip.c:tpm_put_ops",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276268338,
      "name": "tpm_chip_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void tpm_chip_stop(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585740016,
      "name": "tpm_chip_stop",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:133",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_class_shutdown",
        "drivers/char/tpm/tpm-chip.c:tpm_put_ops",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585740016,
      "name": "tpm_chip_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void tpm_chip_stop(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585599200,
      "name": "tpm_chip_stop",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:133",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_class_shutdown",
        "drivers/char/tpm/tpm-chip.c:tpm_put_ops",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585599200,
      "name": "tpm_chip_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void tpm_chip_stop(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585929056,
      "name": "tpm_chip_stop",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:133",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_class_shutdown",
        "drivers/char/tpm/tpm-chip.c:tpm_put_ops",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585929056,
      "name": "tpm_chip_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void tpm_chip_stop(struct tpm_chip * chip)
```

```json
{
  "name": "tpm_chip_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586037040,
      "name": "tpm_chip_stop",
      "external": true,
      "loc": "drivers/char/tpm/tpm-chip.c:133",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_unregister",
        "drivers/char/tpm/tpm-chip.c:tpm_class_shutdown",
        "drivers/char/tpm/tpm-chip.c:tpm_put_ops",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm2-space.c:tpm2_del_space",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586037040,
      "name": "tpm_chip_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void tpm_chip_stop(struct tpm_chip * chip)
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
