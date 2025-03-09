# Function: <code>release_locality</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584254816,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:149",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_remove"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_init",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584254816,
      "name": "release_locality.isra.3.constprop.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void release_locality(struct tpm_chip * chip, int l, int force)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584592816,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:76",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584592816,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void release_locality(struct tpm_chip * chip, int l, int force)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584774112,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:76",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584774112,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584868559,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:78",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584863344,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585288367,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:80",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585282304,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585520320,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:158",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585520320,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585644416,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:158",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585644416,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585872864,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:154",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585872864,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
int release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586015424,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:154",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586015424,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
int release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586752448,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:154",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:probe_itpm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586752448,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
int release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586842928,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:138",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single",
        "drivers/char/tpm/tpm_tis_core.c:probe_itpm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586842928,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586727044,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:138",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586723392,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587278548,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:139",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587274848,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588590199,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:139",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588587408,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590047063,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:139",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590043120,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498810984,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:154",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498810984,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
int release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231420992,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:154",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231420992,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292004448,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:154",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    },
    {
      "addr": 13835058055292019712,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_i2c_infineon.c:331",
      "file": "drivers/char/tpm/tpm_i2c_infineon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_remove",
        "drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_probe",
        "drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_probe",
        "drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_send",
        "drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292004448,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 932
    },
    {
      "addr": 13835058055292019712,
      "name": "release_locality.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276308530,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:154",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276308530,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
int release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585776400,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:154",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585776400,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
int release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585635584,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:154",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585635584,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
int release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585965440,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:154",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585965440,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
int release_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "release_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586073168,
      "name": "release_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:154",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586073168,
      "name": "release_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void release_locality(struct tpm_chip * chip, int l, int force)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int force</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int release_locality(struct tpm_chip * chip, int l)
```
</details>
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
