# Function: <code>tpm_common_open</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584854576,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:45",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584854576,
      "name": "tpm_common_open",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585273712,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:45",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585273712,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585510624,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:45",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585510624,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585618848,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:73",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585618848,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585839520,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:98",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585839520,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585982208,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:105",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585982208,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586723344,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:105",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586723344,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586818976,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:105",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586818976,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586698992,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:104",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586698992,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587248336,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:104",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587248336,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588557168,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:110",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588557168,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590009744,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:110",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590009744,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590318992,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:110",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590318992,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590660336,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:110",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590660336,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498776272,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:105",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498776272,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231391936,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:105",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231391936,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291967216,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:105",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291967216,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276271370,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:105",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276271370,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585743184,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:105",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585743184,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585602368,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:105",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585602368,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585932224,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:105",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585932224,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586040208,
      "name": "tpm_common_open",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:105",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_open",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586040208,
      "name": "tpm_common_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void tpm_common_open(struct file * file, struct tpm_chip * chip, struct file_priv * priv)
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tpm_space * space</code>
</li>
</ul>
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
