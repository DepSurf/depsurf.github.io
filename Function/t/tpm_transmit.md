# Function: <code>tpm_transmit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t tpm_transmit(struct tpm_chip * chip, const char * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584233872,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:333",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd",
        "drivers/char/tpm/tpm-interface.c:tpm_do_selftest",
        "drivers/char/tpm/tpm-dev.c:tpm_write",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584233872,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
ssize_t tpm_transmit(struct tpm_chip * chip, const char * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584573616,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:333",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_do_selftest",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd",
        "drivers/char/tpm/tpm-dev.c:tpm_write",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584573616,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
ssize_t tpm_transmit(struct tpm_chip * chip, const u8 * buf, size_t bufsiz, unsigned int flags)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584755488,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:334",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd",
        "drivers/char/tpm/tpm-dev.c:tpm_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584755488,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 621
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
ssize_t tpm_transmit(struct tpm_chip * chip, struct tpm_space * space, u8 * buf, size_t bufsiz, unsigned int flags)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584836224,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:384",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584836224,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1118
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
ssize_t tpm_transmit(struct tpm_chip * chip, struct tpm_space * space, u8 * buf, size_t bufsiz, unsigned int flags)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585257392,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:384",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585257392,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1230
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
ssize_t tpm_transmit(struct tpm_chip * chip, struct tpm_space * space, u8 * buf, size_t bufsiz, unsigned int flags)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585493472,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:587",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585493472,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1964
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
ssize_t tpm_transmit(struct tpm_chip * chip, struct tpm_space * space, u8 * buf, size_t bufsiz, unsigned int flags)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585621296,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:328",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_write",
        "drivers/char/tpm/tpm-dev-common.c:tpm_async_work",
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585621296,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1959
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
ssize_t tpm_transmit(struct tpm_chip * chip, u8 * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:152",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585843375,
      "name": "tpm_transmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071585841936,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 985
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
ssize_t tpm_transmit(struct tpm_chip * chip, u8 * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:152",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585985935,
      "name": "tpm_transmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071585984624,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 985
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
ssize_t tpm_transmit(struct tpm_chip * chip, u8 * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:153",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586727089,
      "name": "tpm_transmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071586726032,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
ssize_t tpm_transmit(struct tpm_chip * chip, u8 * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:153",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591470094,
      "name": "tpm_transmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071586821600,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
ssize_t tpm_transmit(struct tpm_chip * chip, u8 * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:153",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591411361,
      "name": "tpm_transmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071586701600,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
ssize_t tpm_transmit(struct tpm_chip * chip, u8 * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:153",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592463195,
      "name": "tpm_transmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071587250960,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
ssize_t tpm_transmit(struct tpm_chip * chip, u8 * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:153",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594332992,
      "name": "tpm_transmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071588560000,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
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
ssize_t tpm_transmit(struct tpm_chip * chip, u8 * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590013088,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:153",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590013088,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 693
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
ssize_t tpm_transmit(struct tpm_chip * chip, u8 * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590322416,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:153",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590322416,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
ssize_t tpm_transmit(struct tpm_chip * chip, u8 * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590663808,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:153",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590663808,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
ssize_t tpm_transmit(struct tpm_chip * chip, u8 * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498779816,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:152",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498779816,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 828
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
ssize_t tpm_transmit(struct tpm_chip * chip, u8 * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231394508,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:152",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231394508,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
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
ssize_t tpm_transmit(struct tpm_chip * chip, u8 * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291971056,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:152",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291971056,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1120
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
ssize_t tpm_transmit(struct tpm_chip * chip, u8 * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276273770,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:152",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276273770,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
ssize_t tpm_transmit(struct tpm_chip * chip, u8 * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:152",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585746911,
      "name": "tpm_transmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071585745600,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 985
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
ssize_t tpm_transmit(struct tpm_chip * chip, u8 * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:152",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585606095,
      "name": "tpm_transmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071585604784,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 985
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
ssize_t tpm_transmit(struct tpm_chip * chip, u8 * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:152",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585935951,
      "name": "tpm_transmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071585934640,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 985
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
ssize_t tpm_transmit(struct tpm_chip * chip, u8 * buf, size_t bufsiz)
```

```json
{
  "name": "tpm_transmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:152",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_transmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043935,
      "name": "tpm_transmit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071586042624,
      "name": "tpm_transmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 985
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>const char * buf</code> ➡️ <code>const u8 * buf</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tpm_space * space</code>
</li>
<li>
<b>Param reordered. </b>
<code>chip, buf, bufsiz, flags</code> ➡️ <code>chip, space, buf, bufsiz, flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>const u8 * buf</code> ➡️ <code>u8 * buf</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct tpm_space * space</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>chip, space, buf, bufsiz, flags</code> ➡️ <code>chip, buf, bufsiz</code>
</li>
</ul>
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
