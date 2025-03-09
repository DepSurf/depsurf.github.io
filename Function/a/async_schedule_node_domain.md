# Function: <code>async_schedule_node_domain</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```

```json
{
  "name": "async_schedule_node_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579654688,
      "name": "async_schedule_node_domain",
      "external": true,
      "loc": "kernel/async.c:165",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654688,
      "name": "async_schedule_node_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```

```json
{
  "name": "async_schedule_node_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579691776,
      "name": "async_schedule_node_domain",
      "external": true,
      "loc": "kernel/async.c:165",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579691776,
      "name": "async_schedule_node_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```

```json
{
  "name": "async_schedule_node_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579732912,
      "name": "async_schedule_node_domain",
      "external": true,
      "loc": "kernel/async.c:165",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579732912,
      "name": "async_schedule_node_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```

```json
{
  "name": "async_schedule_node_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579712848,
      "name": "async_schedule_node_domain",
      "external": true,
      "loc": "kernel/async.c:165",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579712848,
      "name": "async_schedule_node_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```

```json
{
  "name": "async_schedule_node_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579720160,
      "name": "async_schedule_node_domain",
      "external": true,
      "loc": "kernel/async.c:165",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:populate_rootfs",
        "kernel/async.c:async_schedule_node",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720160,
      "name": "async_schedule_node_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```

```json
{
  "name": "async_schedule_node_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579798528,
      "name": "async_schedule_node_domain",
      "external": true,
      "loc": "kernel/async.c:165",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:populate_rootfs",
        "kernel/async.c:async_schedule_node",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/scsi/scsi_pm.c:scsi_bus_resume_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579798528,
      "name": "async_schedule_node_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```

```json
{
  "name": "async_schedule_node_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579907808,
      "name": "async_schedule_node_domain",
      "external": true,
      "loc": "kernel/async.c:165",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:populate_rootfs",
        "kernel/async.c:async_schedule_node",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907808,
      "name": "async_schedule_node_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```

```json
{
  "name": "async_schedule_node_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580061136,
      "name": "async_schedule_node_domain",
      "external": true,
      "loc": "kernel/async.c:165",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:populate_rootfs",
        "kernel/async.c:async_schedule_node",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580061136,
      "name": "async_schedule_node_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```

```json
{
  "name": "async_schedule_node_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580115584,
      "name": "async_schedule_node_domain",
      "external": true,
      "loc": "kernel/async.c:165",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:populate_rootfs",
        "kernel/async.c:async_schedule_node",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580115584,
      "name": "async_schedule_node_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```

```json
{
  "name": "async_schedule_node_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580161072,
      "name": "async_schedule_node_domain",
      "external": true,
      "loc": "kernel/async.c:199",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:populate_rootfs",
        "kernel/async.c:async_schedule_node",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580161072,
      "name": "async_schedule_node_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```

```json
{
  "name": "async_schedule_node_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490871312,
      "name": "async_schedule_node_domain",
      "external": true,
      "loc": "kernel/async.c:165",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490871312,
      "name": "async_schedule_node_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```

```json
{
  "name": "async_schedule_node_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224888456,
      "name": "async_schedule_node_domain",
      "external": true,
      "loc": "kernel/async.c:165",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "sound/soc/soc-dapm.c:dapm_power_widgets",
        "sound/soc/soc-dapm.c:dapm_power_widgets"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224888456,
      "name": "async_schedule_node_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```

```json
{
  "name": "async_schedule_node_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283702512,
      "name": "async_schedule_node_domain",
      "external": true,
      "loc": "kernel/async.c:165",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283702512,
      "name": "async_schedule_node_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```

```json
{
  "name": "async_schedule_node_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271525394,
      "name": "async_schedule_node_domain",
      "external": true,
      "loc": "kernel/async.c:165",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node",
        "drivers/regulator/core.c:regulator_bulk_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271525394,
      "name": "async_schedule_node_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```

```json
{
  "name": "async_schedule_node_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668096,
      "name": "async_schedule_node_domain",
      "external": true,
      "loc": "kernel/async.c:165",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668096,
      "name": "async_schedule_node_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```

```json
{
  "name": "async_schedule_node_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579596448,
      "name": "async_schedule_node_domain",
      "external": true,
      "loc": "kernel/async.c:165",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579596448,
      "name": "async_schedule_node_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```

```json
{
  "name": "async_schedule_node_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579665328,
      "name": "async_schedule_node_domain",
      "external": true,
      "loc": "kernel/async.c:165",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665328,
      "name": "async_schedule_node_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```

```json
{
  "name": "async_schedule_node_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579699424,
      "name": "async_schedule_node_domain",
      "external": true,
      "loc": "kernel/async.c:165",
      "file": "kernel/async.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/async.c:async_schedule_node",
        "drivers/regulator/core.c:regulator_bulk_enable",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579699424,
      "name": "async_schedule_node_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
async_cookie_t async_schedule_node_domain(async_func_t func, void * data, int node, struct async_domain * domain)
```
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
