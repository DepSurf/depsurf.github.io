# Function: <code>crng_reseed</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584507456,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:821",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:credit_entropy_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584507456,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584689568,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:821",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:credit_entropy_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584689568,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584770992,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:816",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:credit_entropy_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584770992,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585191088,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:815",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:credit_entropy_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585191088,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:910",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:credit_entropy_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585427328,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    },
    {
      "addr": 18446744071585436101,
      "name": "crng_reseed.cold.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:923",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:credit_entropy_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585551392,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    },
    {
      "addr": 18446744071585559761,
      "name": "crng_reseed.cold.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:1000",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:credit_entropy_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585771616,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
    },
    {
      "addr": 18446744071585779564,
      "name": "crng_reseed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:1000",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:credit_entropy_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585914256,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071585922256,
      "name": "crng_reseed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:948",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:_extract_crng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586652784,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
    },
    {
      "addr": 18446744071586659232,
      "name": "crng_reseed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:948",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:_extract_crng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586763488,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
    },
    {
      "addr": 18446744071591462197,
      "name": "crng_reseed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:938",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:_extract_crng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586644528,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
    },
    {
      "addr": 18446744071591403770,
      "name": "crng_reseed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587191824,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:989",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:_extract_crng"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587191824,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
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
void crng_reseed()
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588497088,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:203",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:add_vmfork_randomness",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:_credit_init_bits",
        "drivers/char/random.c:crng_make_state",
        "drivers/char/random.c:random_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588497088,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
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
void crng_reseed(struct work_struct * work)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:249",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:add_vmfork_randomness",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_init",
        "drivers/char/random.c:random_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589937136,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071596238042,
      "name": "crng_reseed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void crng_reseed(struct work_struct * work)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:249",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:add_vmfork_randomness",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_init",
        "drivers/char/random.c:random_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590246416,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071596766242,
      "name": "crng_reseed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void crng_reseed(struct work_struct * work)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:249",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:add_vmfork_randomness",
        "drivers/char/random.c:random_pm_notification",
        "drivers/char/random.c:random_init",
        "drivers/char/random.c:random_init_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590587440,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071597674903,
      "name": "crng_reseed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498735064,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:1000",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:credit_entropy_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498735064,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231359140,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:1000",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:credit_entropy_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231359140,
      "name": "crng_reseed.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291890528,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:1000",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:credit_entropy_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291890528,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 892
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276242108,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:1000",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:credit_entropy_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276242108,
      "name": "crng_reseed.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:1000",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:credit_entropy_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585675264,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071585683232,
      "name": "crng_reseed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:1000",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:credit_entropy_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585535104,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071585543104,
      "name": "crng_reseed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:1000",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:credit_entropy_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585864656,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071585872656,
      "name": "crng_reseed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```

```json
{
  "name": "crng_reseed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crng_reseed",
      "external": false,
      "loc": "drivers/char/random.c:1000",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/random.c:random_ioctl",
        "drivers/char/random.c:_extract_crng",
        "drivers/char/random.c:credit_entropy_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585972336,
      "name": "crng_reseed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071585980528,
      "name": "crng_reseed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
```
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct crng_state * crng</code>
</li>
<li>
<b>Param removed. </b>
<code>struct entropy_store * r</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct work_struct * work</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
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
void crng_reseed(struct crng_state * crng, struct entropy_store * r)
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
