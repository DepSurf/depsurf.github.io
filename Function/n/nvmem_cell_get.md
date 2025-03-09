# Function: <code>nvmem_cell_get</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * cell_id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586863793,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:857",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586863904,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * cell_id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587353884,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:860",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587351712,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * cell_id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587657590,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:929",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587654592,
      "name": "nvmem_cell_get.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
    },
    {
      "addr": 18446744071587654880,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587788838,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:1066",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587785584,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588092329,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:816",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588090176,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588298153,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:813",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588296000,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589181083,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:1073",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589177568,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589178459,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:1251",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589173104,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589071541,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:1254",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589067280,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589790357,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:1265",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589785696,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591303365,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:1278",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591297776,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593054805,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:1281",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593048864,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593506949,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:1454",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593501072,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594251429,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:1496",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594251024,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501818728,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:813",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_get",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501818728,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234337372,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:813",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_get",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234337372,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295216160,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:813",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_get",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295216160,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1624
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278165456,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:813",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_get",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278165456,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587901913,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:813",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587899760,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587621193,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:813",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587619040,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588235209,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:813",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588233056,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * id)
```

```json
{
  "name": "nvmem_cell_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588370537,
      "name": "nvmem_cell_get",
      "external": true,
      "loc": "drivers/nvmem/core.c:813",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588368384,
      "name": "nvmem_cell_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct nvmem_cell * nvmem_cell_get(struct device * dev, const char * cell_id)
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
<code>const char * id</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * cell_id</code>
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
