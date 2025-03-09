# Function: <code>__pci_epc_create</code>

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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583900656,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:479",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583900656,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584163888,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:485",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584163888,
      "name": "__pci_epc_create",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584381712,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:484",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584381712,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584473760,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:542",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584473760,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:596",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584671893,
      "name": "__pci_epc_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071584671488,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584809760,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:596",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584809760,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585502432,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:608",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585502432,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585634528,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:608",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585634528,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585514176,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:702",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585514176,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585982704,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:758",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585982704,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587198224,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:758",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587198224,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588425600,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:762",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588425600,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588703312,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:832",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588703312,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589004128,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:831",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589004128,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497082280,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:596",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497082280,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230289436,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:596",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230289436,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291127392,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:596",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291127392,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275722100,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:596",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275722100,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584758496,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:596",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584758496,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584689280,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:596",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584689280,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584759920,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:596",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584759920,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
```

```json
{
  "name": "__pci_epc_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584867440,
      "name": "__pci_epc_create",
      "external": true,
      "loc": "drivers/pci/endpoint/pci-epc-core.c:596",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/endpoint/pci-epc-core.c:__devm_pci_epc_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584867440,
      "name": "__pci_epc_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct pci_epc * __pci_epc_create(struct device * dev, const struct pci_epc_ops * ops, struct module * owner)
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
