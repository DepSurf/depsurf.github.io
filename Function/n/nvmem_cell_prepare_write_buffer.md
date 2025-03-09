# Function: <code>nvmem_cell_prepare_write_buffer</code>

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
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586864162,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:1030",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_write"
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
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587351977,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:1032",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_write"
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
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587655241,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:1105",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_write"
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
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587785961,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:1241",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_write"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588092689,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:996",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_write"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588298513,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:993",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_write"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * nvmem_cell_prepare_write_buffer(struct nvmem_cell * cell, u8 * _buf, int len)
```

```json
{
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589175696,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:1253",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589175696,
      "name": "nvmem_cell_prepare_write_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
void * nvmem_cell_prepare_write_buffer(struct nvmem_cell * cell, u8 * _buf, int len)
```

```json
{
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589175104,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:1431",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589175104,
      "name": "nvmem_cell_prepare_write_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
void * nvmem_cell_prepare_write_buffer(struct nvmem_cell * cell, u8 * _buf, int len)
```

```json
{
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589068432,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:1434",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589068432,
      "name": "nvmem_cell_prepare_write_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
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
void * nvmem_cell_prepare_write_buffer(struct nvmem_cell * cell, u8 * _buf, int len)
```

```json
{
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:1446",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589787008,
      "name": "nvmem_cell_prepare_write_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    },
    {
      "addr": 18446744071592690920,
      "name": "nvmem_cell_prepare_write_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void * nvmem_cell_prepare_write_buffer(struct nvmem_cell_entry * cell, u8 * _buf, int len)
```

```json
{
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:1470",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_cell_entry_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591299136,
      "name": "nvmem_cell_prepare_write_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071594576161,
      "name": "nvmem_cell_prepare_write_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void * nvmem_cell_prepare_write_buffer(struct nvmem_cell_entry * cell, u8 * _buf, int len)
```

```json
{
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:1473",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_cell_entry_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593050128,
      "name": "nvmem_cell_prepare_write_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071596320726,
      "name": "nvmem_cell_prepare_write_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void * nvmem_cell_prepare_write_buffer(struct nvmem_cell_entry * cell, u8 * _buf, int len)
```

```json
{
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:1647",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_cell_entry_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593502336,
      "name": "nvmem_cell_prepare_write_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
    },
    {
      "addr": 18446744071596850404,
      "name": "nvmem_cell_prepare_write_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
void * nvmem_cell_prepare_write_buffer(struct nvmem_cell_entry * cell, u8 * _buf, int len)
```

```json
{
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:1690",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:__nvmem_cell_entry_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594248880,
      "name": "nvmem_cell_prepare_write_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
    },
    {
      "addr": 18446744071597775253,
      "name": "nvmem_cell_prepare_write_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501819472,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:993",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_write"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234340364,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:993",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_write"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295221864,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:993",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_write"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278166066,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:993",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587902273,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:993",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_write"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587621553,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:993",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_write"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588235569,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:993",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_write"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_cell_prepare_write_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588370897,
      "name": "nvmem_cell_prepare_write_buffer",
      "external": false,
      "loc": "drivers/nvmem/core.c:993",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void * nvmem_cell_prepare_write_buffer(struct nvmem_cell * cell, u8 * _buf, int len)
```
</details>
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
<b>Param type changed. </b>
<code>struct nvmem_cell * cell</code> ➡️ <code>struct nvmem_cell_entry * cell</code>
</li>
</ul>
</details>
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
