# Function: <code>nvmem_cell_put</code>

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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586863360,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:939",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586863360,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587351152,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:942",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587351152,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587654512,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:1015",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587654512,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587786720,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:1152",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587786720,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588092400,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:902",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588090352,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588298224,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:899",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588296176,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589181241,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:1159",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589177744,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589178617,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:1337",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589173280,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589071610,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:1340",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589067456,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589790426,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:1351",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589785872,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591303448,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:1364",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591296960,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593054888,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:1367",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593047984,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593507032,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:1540",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593499920,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594251264,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:1582",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594251264,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501822448,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:899",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501817368,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234340164,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:899",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234336236,
      "name": "nvmem_cell_put",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295221376,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:899",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295214688,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278168674,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:899",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278164238,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587901984,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:899",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587899936,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587621264,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:899",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587619216,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588235280,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:899",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588233232,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void nvmem_cell_put(struct nvmem_cell * cell)
```

```json
{
  "name": "nvmem_cell_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588370608,
      "name": "nvmem_cell_put",
      "external": true,
      "loc": "drivers/nvmem/core.c:899",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:devm_nvmem_cell_release"
      ],
      "caller_func": [
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588368560,
      "name": "nvmem_cell_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void nvmem_cell_put(struct nvmem_cell * cell)
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
