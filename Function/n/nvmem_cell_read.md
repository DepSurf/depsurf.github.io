# Function: <code>nvmem_cell_read</code>

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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586865856,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:1007",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586865856,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587353712,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:1009",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587353712,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587657408,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:1082",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587657408,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587788656,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:1218",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587788656,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588091936,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:973",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588091936,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588297760,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:970",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588297760,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589180896,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:1230",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589180896,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589178240,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:1408",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589178240,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589070880,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:1411",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589070880,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589789696,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:1423",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589789696,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591301984,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:1447",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591301984,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593050848,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:1450",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593050848,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593503072,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:1623",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593503072,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594249840,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:1666",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_attr_read",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594249840,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501821968,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:970",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501821968,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234339744,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:970",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234339744,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295220720,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:970",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295220720,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278168250,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:970",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278168250,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587901520,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:970",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587901520,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587620800,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:970",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587620800,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588234816,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:970",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588234816,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
```

```json
{
  "name": "nvmem_cell_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588370144,
      "name": "nvmem_cell_read",
      "external": true,
      "loc": "drivers/nvmem/core.c:970",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "net/ethernet/eth.c:nvmem_get_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588370144,
      "name": "nvmem_cell_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void * nvmem_cell_read(struct nvmem_cell * cell, size_t * len)
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
