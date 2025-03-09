# Function: <code>efi_capsule_update</code>

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
int efi_capsule_update(efi_capsule_header_t * capsule, struct page * * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586402912,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:217",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586402912,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 919
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
int efi_capsule_update(efi_capsule_header_t * capsule, struct page * * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586612192,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:217",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586612192,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 909
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
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586737344,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:217",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586737344,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 850
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
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587221840,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:217",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587221840,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
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
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:217",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587523816,
      "name": "efi_capsule_update.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587522896,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 865
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
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:217",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587704643,
      "name": "efi_capsule_update.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587703728,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 865
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
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:215",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587983635,
      "name": "efi_capsule_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071587982736,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
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
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:215",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588190835,
      "name": "efi_capsule_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071588189936,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
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
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:215",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589056867,
      "name": "efi_capsule_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071589056032,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 799
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
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:216",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591607052,
      "name": "efi_capsule_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071589063648,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
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
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:216",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591550603,
      "name": "efi_capsule_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071588950736,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 803
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
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:216",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592669999,
      "name": "efi_capsule_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071589659984,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 819
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
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:216",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594554914,
      "name": "efi_capsule_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071591162912,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 844
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
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:216",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596318285,
      "name": "efi_capsule_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592885312,
      "name": "efi_capsule_update",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:216",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596847611,
      "name": "efi_capsule_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593323920,
      "name": "efi_capsule_update",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:216",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597772740,
      "name": "efi_capsule_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071594080960,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
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
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501545584,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:215",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501545584,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 756
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
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234059780,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:215",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234059780,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 964
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:215",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587809267,
      "name": "efi_capsule_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071587808368,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
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
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:215",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587512691,
      "name": "efi_capsule_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071587511792,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
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
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:215",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588145363,
      "name": "efi_capsule_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071588144464,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
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
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```

```json
{
  "name": "efi_capsule_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_capsule_update",
      "external": true,
      "loc": "drivers/firmware/efi/capsule.c:215",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588262771,
      "name": "efi_capsule_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071588261984,
      "name": "efi_capsule_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 743
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
int efi_capsule_update(efi_capsule_header_t * capsule, struct page * * pages)
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
<b>Param type changed. </b>
<code>struct page * * pages</code> ➡️ <code>phys_addr_t * pages</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int efi_capsule_update(efi_capsule_header_t * capsule, phys_addr_t * pages)
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
