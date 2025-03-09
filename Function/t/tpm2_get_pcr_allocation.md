# Function: <code>tpm2_get_pcr_allocation</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584852991,
      "name": "tpm2_get_pcr_allocation",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:944",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585272531,
      "name": "tpm2_get_pcr_allocation",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:919",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585509519,
      "name": "tpm2_get_pcr_allocation",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:901",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585632323,
      "name": "tpm2_get_pcr_allocation",
      "external": false,
      "loc": "drivers/char/tpm/tpm2-cmd.c:821",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_get_pcr_allocation",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:843",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585856064,
      "name": "tpm2_get_pcr_allocation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071585854528,
      "name": "tpm2_get_pcr_allocation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 681
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_get_pcr_allocation",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:845",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585998656,
      "name": "tpm2_get_pcr_allocation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071585997104,
      "name": "tpm2_get_pcr_allocation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 681
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_get_pcr_allocation",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:539",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586736528,
      "name": "tpm2_get_pcr_allocation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586735376,
      "name": "tpm2_get_pcr_allocation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 858
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_get_pcr_allocation",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:539",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591470745,
      "name": "tpm2_get_pcr_allocation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586830096,
      "name": "tpm2_get_pcr_allocation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 858
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_get_pcr_allocation",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:539",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591412012,
      "name": "tpm2_get_pcr_allocation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586710016,
      "name": "tpm2_get_pcr_allocation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 903
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_get_pcr_allocation",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:539",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592463957,
      "name": "tpm2_get_pcr_allocation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587259856,
      "name": "tpm2_get_pcr_allocation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 965
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_get_pcr_allocation",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:548",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594333863,
      "name": "tpm2_get_pcr_allocation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588569360,
      "name": "tpm2_get_pcr_allocation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 986
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590023600,
      "name": "tpm2_get_pcr_allocation",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:548",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590023600,
      "name": "tpm2_get_pcr_allocation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1012
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590332896,
      "name": "tpm2_get_pcr_allocation",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:548",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590332896,
      "name": "tpm2_get_pcr_allocation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1012
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590674336,
      "name": "tpm2_get_pcr_allocation",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:548",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590674336,
      "name": "tpm2_get_pcr_allocation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1012
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498793344,
      "name": "tpm2_get_pcr_allocation",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:845",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498793344,
      "name": "tpm2_get_pcr_allocation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231407900,
      "name": "tpm2_get_pcr_allocation",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:845",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231407900,
      "name": "tpm2_get_pcr_allocation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291987952,
      "name": "tpm2_get_pcr_allocation",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:845",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291987952,
      "name": "tpm2_get_pcr_allocation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 920
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276294464,
      "name": "tpm2_get_pcr_allocation",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:845",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276294464,
      "name": "tpm2_get_pcr_allocation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1144
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_get_pcr_allocation",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:845",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585759632,
      "name": "tpm2_get_pcr_allocation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071585758080,
      "name": "tpm2_get_pcr_allocation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 681
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_get_pcr_allocation",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:845",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585618816,
      "name": "tpm2_get_pcr_allocation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071585617264,
      "name": "tpm2_get_pcr_allocation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 681
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_get_pcr_allocation",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:845",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585948672,
      "name": "tpm2_get_pcr_allocation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071585947120,
      "name": "tpm2_get_pcr_allocation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 681
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
```

```json
{
  "name": "tpm2_get_pcr_allocation",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm2_get_pcr_allocation",
      "external": true,
      "loc": "drivers/char/tpm/tpm2-cmd.c:845",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586056432,
      "name": "tpm2_get_pcr_allocation.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586054896,
      "name": "tpm2_get_pcr_allocation",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 673
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
ssize_t tpm2_get_pcr_allocation(struct tpm_chip * chip)
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
