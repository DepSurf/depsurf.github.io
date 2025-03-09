# Function: <code>request_locality</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584254256,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis.c:158",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584254256,
      "name": "request_locality.constprop.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584595296,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:93",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584595296,
      "name": "request_locality.constprop.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584776704,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:93",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584776704,
      "name": "request_locality.constprop.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584864000,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:85",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584864000,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585283024,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:87",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585283024,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585520864,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:195",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585520864,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585644960,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:195",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585644960,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585870048,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:191",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585870048,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586012608,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:191",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586012608,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586751232,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:191",
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
      "addr": 18446744071586751232,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586845312,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:147",
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
      "addr": 18446744071586845312,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586725392,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:147",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586725392,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587276864,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:148",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587276864,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588586208,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:148",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588586208,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590041968,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:148",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_resume",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590041968,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498810424,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:191",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498810424,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231421612,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:191",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231421612,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292005392,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:191",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    },
    {
      "addr": 13835058055292020640,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_i2c_infineon.c:344",
      "file": "drivers/char/tpm/tpm_i2c_infineon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_probe",
        "drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292005392,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
    },
    {
      "addr": 13835058055292020640,
      "name": "request_locality.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276308994,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:191",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276308994,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585773584,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:191",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585773584,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585632768,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:191",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585632768,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585962624,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:191",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585962624,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int request_locality(struct tpm_chip * chip, int l)
```

```json
{
  "name": "request_locality",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586070368,
      "name": "request_locality",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:191",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586070368,
      "name": "request_locality",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int request_locality(struct tpm_chip * chip, int l)
```
</details>
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
int request_locality(struct tpm_chip * chip, int l)
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
