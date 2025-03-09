# Function: <code>iommu_pc_get_set_reg</code>

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
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```

```json
{
  "name": "iommu_pc_get_set_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584916080,
      "name": "iommu_pc_get_set_reg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:2792",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584916080,
      "name": "iommu_pc_get_set_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```

```json
{
  "name": "iommu_pc_get_set_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585336416,
      "name": "iommu_pc_get_set_reg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:2989",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585336416,
      "name": "iommu_pc_get_set_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```

```json
{
  "name": "iommu_pc_get_set_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585577744,
      "name": "iommu_pc_get_set_reg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:2990",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585577744,
      "name": "iommu_pc_get_set_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```

```json
{
  "name": "iommu_pc_get_set_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585702496,
      "name": "iommu_pc_get_set_reg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:3026",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585702496,
      "name": "iommu_pc_get_set_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```

```json
{
  "name": "iommu_pc_get_set_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_pc_get_set_reg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:3100",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585930256,
      "name": "iommu_pc_get_set_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071585933554,
      "name": "iommu_pc_get_set_reg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```

```json
{
  "name": "iommu_pc_get_set_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586073392,
      "name": "iommu_pc_get_set_reg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:3131",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586073392,
      "name": "iommu_pc_get_set_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```

```json
{
  "name": "iommu_pc_get_set_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586819056,
      "name": "iommu_pc_get_set_reg",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:3101",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_pc_set_reg",
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_reg",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/amd/init.c:iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586819056,
      "name": "iommu_pc_get_set_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```

```json
{
  "name": "iommu_pc_get_set_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586877200,
      "name": "iommu_pc_get_set_reg",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:3316",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_pc_set_reg",
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_reg",
        "drivers/iommu/amd/init.c:init_iommu_perf_ctr",
        "drivers/iommu/amd/init.c:init_iommu_perf_ctr",
        "drivers/iommu/amd/init.c:init_iommu_perf_ctr",
        "drivers/iommu/amd/init.c:init_iommu_perf_ctr",
        "drivers/iommu/amd/init.c:init_iommu_perf_ctr",
        "drivers/iommu/amd/init.c:init_iommu_perf_ctr",
        "drivers/iommu/amd/init.c:init_iommu_perf_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586877200,
      "name": "iommu_pc_get_set_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```

```json
{
  "name": "iommu_pc_get_set_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586753632,
      "name": "iommu_pc_get_set_reg",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:3263",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_pc_set_reg",
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586753632,
      "name": "iommu_pc_get_set_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```

```json
{
  "name": "iommu_pc_get_set_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_pc_get_set_reg",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:3303",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_pc_set_reg",
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587307280,
      "name": "iommu_pc_get_set_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    },
    {
      "addr": 18446744071592469919,
      "name": "iommu_pc_get_set_reg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```

```json
{
  "name": "iommu_pc_get_set_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_pc_get_set_reg",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:3313",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_pc_set_reg",
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588621760,
      "name": "iommu_pc_get_set_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071594339758,
      "name": "iommu_pc_get_set_reg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```

```json
{
  "name": "iommu_pc_get_set_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_pc_get_set_reg",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:3614",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_pc_set_reg",
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590086336,
      "name": "iommu_pc_get_set_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071596241052,
      "name": "iommu_pc_get_set_reg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```

```json
{
  "name": "iommu_pc_get_set_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_pc_get_set_reg",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:3694",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_pc_set_reg",
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590398512,
      "name": "iommu_pc_get_set_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071596769213,
      "name": "iommu_pc_get_set_reg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```

```json
{
  "name": "iommu_pc_get_set_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_pc_get_set_reg",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:3716",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_pc_set_reg",
        "drivers/iommu/amd/init.c:amd_iommu_pc_get_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590742000,
      "name": "iommu_pc_get_set_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071597677541,
      "name": "iommu_pc_get_set_reg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```

```json
{
  "name": "iommu_pc_get_set_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585834512,
      "name": "iommu_pc_get_set_reg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:3131",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585834512,
      "name": "iommu_pc_get_set_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```

```json
{
  "name": "iommu_pc_get_set_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585693184,
      "name": "iommu_pc_get_set_reg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:3131",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585693184,
      "name": "iommu_pc_get_set_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```

```json
{
  "name": "iommu_pc_get_set_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586023408,
      "name": "iommu_pc_get_set_reg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:3131",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586023408,
      "name": "iommu_pc_get_set_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```

```json
{
  "name": "iommu_pc_get_set_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586131360,
      "name": "iommu_pc_get_set_reg",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:3131",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_set_reg",
        "drivers/iommu/amd_iommu_init.c:amd_iommu_pc_get_reg",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci",
        "drivers/iommu/amd_iommu_init.c:iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586131360,
      "name": "iommu_pc_get_set_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int iommu_pc_get_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value, bool is_write)
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
