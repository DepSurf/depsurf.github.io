# Function: <code>amd_iommu_pc_set_reg</code>

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
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```

```json
{
  "name": "amd_iommu_pc_set_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584916352,
      "name": "amd_iommu_pc_set_reg",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:2839",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584916352,
      "name": "amd_iommu_pc_set_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```

```json
{
  "name": "amd_iommu_pc_set_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585336672,
      "name": "amd_iommu_pc_set_reg",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:3036",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585336672,
      "name": "amd_iommu_pc_set_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```

```json
{
  "name": "amd_iommu_pc_set_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585578016,
      "name": "amd_iommu_pc_set_reg",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:3037",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585578016,
      "name": "amd_iommu_pc_set_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```

```json
{
  "name": "amd_iommu_pc_set_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585702768,
      "name": "amd_iommu_pc_set_reg",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:3073",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585702768,
      "name": "amd_iommu_pc_set_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```

```json
{
  "name": "amd_iommu_pc_set_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585930528,
      "name": "amd_iommu_pc_set_reg",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:3147",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585930528,
      "name": "amd_iommu_pc_set_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```

```json
{
  "name": "amd_iommu_pc_set_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586073664,
      "name": "amd_iommu_pc_set_reg",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:3178",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586073664,
      "name": "amd_iommu_pc_set_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```

```json
{
  "name": "amd_iommu_pc_set_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586819312,
      "name": "amd_iommu_pc_set_reg",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:3148",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_enable_event",
        "arch/x86/events/amd/iommu.c:perf_iommu_enable_event",
        "arch/x86/events/amd/iommu.c:perf_iommu_enable_event",
        "arch/x86/events/amd/iommu.c:perf_iommu_enable_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586819312,
      "name": "amd_iommu_pc_set_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```

```json
{
  "name": "amd_iommu_pc_set_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586877456,
      "name": "amd_iommu_pc_set_reg",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:3363",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_enable_event",
        "arch/x86/events/amd/iommu.c:perf_iommu_enable_event",
        "arch/x86/events/amd/iommu.c:perf_iommu_enable_event",
        "arch/x86/events/amd/iommu.c:perf_iommu_enable_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586877456,
      "name": "amd_iommu_pc_set_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```

```json
{
  "name": "amd_iommu_pc_set_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586757664,
      "name": "amd_iommu_pc_set_reg",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:3309",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586757664,
      "name": "amd_iommu_pc_set_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```

```json
{
  "name": "amd_iommu_pc_set_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587312144,
      "name": "amd_iommu_pc_set_reg",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:3349",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587312144,
      "name": "amd_iommu_pc_set_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```

```json
{
  "name": "amd_iommu_pc_set_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588626896,
      "name": "amd_iommu_pc_set_reg",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:3359",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588626896,
      "name": "amd_iommu_pc_set_reg",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```

```json
{
  "name": "amd_iommu_pc_set_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590092464,
      "name": "amd_iommu_pc_set_reg",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:3660",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590092464,
      "name": "amd_iommu_pc_set_reg",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```

```json
{
  "name": "amd_iommu_pc_set_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590405200,
      "name": "amd_iommu_pc_set_reg",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:3740",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590405200,
      "name": "amd_iommu_pc_set_reg",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```

```json
{
  "name": "amd_iommu_pc_set_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590748768,
      "name": "amd_iommu_pc_set_reg",
      "external": true,
      "loc": "drivers/iommu/amd/init.c:3762",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590748768,
      "name": "amd_iommu_pc_set_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```

```json
{
  "name": "amd_iommu_pc_set_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585834784,
      "name": "amd_iommu_pc_set_reg",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:3178",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585834784,
      "name": "amd_iommu_pc_set_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```

```json
{
  "name": "amd_iommu_pc_set_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585693456,
      "name": "amd_iommu_pc_set_reg",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:3178",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585693456,
      "name": "amd_iommu_pc_set_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```

```json
{
  "name": "amd_iommu_pc_set_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586023680,
      "name": "amd_iommu_pc_set_reg",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:3178",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586023680,
      "name": "amd_iommu_pc_set_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```

```json
{
  "name": "amd_iommu_pc_set_reg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586131632,
      "name": "amd_iommu_pc_set_reg",
      "external": true,
      "loc": "drivers/iommu/amd_iommu_init.c:3178",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start",
        "arch/x86/events/amd/iommu.c:perf_iommu_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586131632,
      "name": "amd_iommu_pc_set_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
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
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int amd_iommu_pc_set_reg(struct amd_iommu * iommu, u8 bank, u8 cntr, u8 fxn, u64 * value)
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
