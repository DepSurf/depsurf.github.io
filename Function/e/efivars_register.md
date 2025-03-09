# Function: <code>efivars_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585991264,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1120",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585991264,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586397360,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1111",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586397360,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586610224,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1134",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586610224,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586735072,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1134",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586735072,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587219520,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1134",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587219520,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1134",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587522231,
      "name": "efivars_register.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071587520512,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587703059,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1191",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587703059,
      "name": "efivars_register.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071587701568,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587982068,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1178",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587982068,
      "name": "efivars_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071587980640,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588189268,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1178",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588189268,
      "name": "efivars_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071588187840,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589054601,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1178",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589054601,
      "name": "efivars_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071589052480,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591606154,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1160",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591606154,
      "name": "efivars_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071589061072,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591549987,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1160",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591549987,
      "name": "efivars_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071588947760,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592669417,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1163",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592669417,
      "name": "efivars_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071589656016,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594554756,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1163",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594554756,
      "name": "efivars_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071591158704,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592883536,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:65",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592883536,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593322128,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:62",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593322128,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594079120,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:62",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594079120,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501543424,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1178",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501543424,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234057556,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1178",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234057556,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587807700,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1178",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587807700,
      "name": "efivars_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071587806272,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587511124,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1178",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587511124,
      "name": "efivars_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071587509696,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588143796,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1178",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588143796,
      "name": "efivars_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071588142368,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```

```json
{
  "name": "efivars_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588261316,
      "name": "efivars_register",
      "external": true,
      "loc": "drivers/firmware/efi/vars.c:1178",
      "file": "drivers/firmware/efi/vars.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588261316,
      "name": "efivars_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071588259888,
      "name": "efivars_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct kobject * kobject</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int efivars_register(struct efivars * efivars, const struct efivar_operations * ops, struct kobject * kobject)
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
