# Function: <code>walk_to_nvdimm_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584706672,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/core.c:101",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_bus_lock",
        "drivers/nvdimm/core.c:nvdimm_bus_unlock",
        "drivers/nvdimm/core.c:is_nvdimm_bus_locked",
        "drivers/nvdimm/bus.c:to_bus_provider",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584706672,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585058768,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:249",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_bus_unlock",
        "drivers/nvdimm/core.c:nvdimm_bus_lock",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:to_bus_provider",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585058768,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585242560,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:251",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_bus_unlock",
        "drivers/nvdimm/core.c:nvdimm_bus_lock",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:to_bus_provider",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585242560,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585324672,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:313",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_bus_unlock",
        "drivers/nvdimm/core.c:nvdimm_bus_lock",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:to_bus_provider",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585324672,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585752624,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:314",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_bus_unlock",
        "drivers/nvdimm/core.c:nvdimm_bus_lock",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:to_bus_provider",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585752624,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585998624,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:317",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_bus_unlock",
        "drivers/nvdimm/core.c:nvdimm_bus_lock",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585998624,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586135664,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:311",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_bus_unlock",
        "drivers/nvdimm/core.c:nvdimm_bus_lock",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite",
        "drivers/nvdimm/security.c:nvdimm_security_erase",
        "drivers/nvdimm/security.c:nvdimm_security_update",
        "drivers/nvdimm/security.c:nvdimm_security_disable",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586135664,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586370720,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:310",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_bus_unlock",
        "drivers/nvdimm/core.c:nvdimm_bus_lock",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite",
        "drivers/nvdimm/security.c:nvdimm_security_erase",
        "drivers/nvdimm/security.c:nvdimm_security_update",
        "drivers/nvdimm/security.c:nvdimm_security_disable",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586370720,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586518784,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:308",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:is_nvdimm_bus_locked",
        "drivers/nvdimm/core.c:nvdimm_bus_unlock",
        "drivers/nvdimm/core.c:nvdimm_bus_lock",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586518784,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587299264,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:313",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587299264,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587360512,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:313",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_bus_firmware_visible",
        "drivers/nvdimm/core.c:nvdimm_bus_firmware_visible",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_show",
        "drivers/nvdimm/core.c:activate_show",
        "drivers/nvdimm/core.c:capability_show",
        "drivers/nvdimm/core.c:capability_show",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587360512,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587242528,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:312",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_bus_firmware_visible",
        "drivers/nvdimm/core.c:nvdimm_bus_firmware_visible",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_show",
        "drivers/nvdimm/core.c:activate_show",
        "drivers/nvdimm/core.c:capability_show",
        "drivers/nvdimm/core.c:capability_show",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587242528,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:311",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:nvdimm_bus_firmware_visible",
        "drivers/nvdimm/core.c:nvdimm_bus_firmware_visible",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_store",
        "drivers/nvdimm/core.c:activate_show",
        "drivers/nvdimm/core.c:activate_show",
        "drivers/nvdimm/core.c:capability_show",
        "drivers/nvdimm/core.c:capability_show",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:grow_dpa_allocation",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592521286,
      "name": "walk_to_nvdimm_bus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587808992,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:302",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594390247,
      "name": "walk_to_nvdimm_bus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589157760,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:302",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596254745,
      "name": "walk_to_nvdimm_bus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590709056,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:302",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596783353,
      "name": "walk_to_nvdimm_bus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591050256,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:302",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/core.c:nvdimm_map_put",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/core.c:alloc_nvdimm_map",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_firmware_visible",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/nvdimm/security.c:security_erase",
        "drivers/nvdimm/security.c:security_update",
        "drivers/nvdimm/security.c:security_disable",
        "drivers/nvdimm/security.c:__nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597692288,
      "name": "walk_to_nvdimm_bus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591394816,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499404168,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:308",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:is_nvdimm_bus_locked",
        "drivers/nvdimm/core.c:nvdimm_bus_unlock",
        "drivers/nvdimm/core.c:nvdimm_bus_lock",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499404168,
      "name": "walk_to_nvdimm_bus",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292643632,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:308",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:is_nvdimm_bus_locked",
        "drivers/nvdimm/core.c:nvdimm_bus_unlock",
        "drivers/nvdimm/core.c:nvdimm_bus_lock",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292643632,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276634024,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:308",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:is_nvdimm_bus_locked",
        "drivers/nvdimm/core.c:nvdimm_bus_unlock",
        "drivers/nvdimm/core.c:nvdimm_bus_lock",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276634024,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586209264,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:308",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:is_nvdimm_bus_locked",
        "drivers/nvdimm/core.c:nvdimm_bus_unlock",
        "drivers/nvdimm/core.c:nvdimm_bus_lock",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586209264,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586027632,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:308",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:is_nvdimm_bus_locked",
        "drivers/nvdimm/core.c:nvdimm_bus_unlock",
        "drivers/nvdimm/core.c:nvdimm_bus_lock",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586027632,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586466752,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:308",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:is_nvdimm_bus_locked",
        "drivers/nvdimm/core.c:nvdimm_bus_unlock",
        "drivers/nvdimm/core.c:nvdimm_bus_lock",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586466752,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```

```json
{
  "name": "walk_to_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586578432,
      "name": "walk_to_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:308",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:devm_nvdimm_memremap",
        "drivers/nvdimm/core.c:is_nvdimm_bus_locked",
        "drivers/nvdimm/core.c:nvdimm_bus_unlock",
        "drivers/nvdimm/core.c:nvdimm_bus_lock",
        "drivers/nvdimm/bus.c:wait_nvdimm_bus_probe_idle",
        "drivers/nvdimm/bus.c:nvdimm_clear_poison",
        "drivers/nvdimm/bus.c:nvdimm_region_notify",
        "drivers/nvdimm/bus.c:nvdimm_bus_shutdown",
        "drivers/nvdimm/bus.c:nvdimm_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_bus_probe",
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa",
        "drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa",
        "drivers/nvdimm/dimm_devs.c:nvdimm_set_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_get_config_data",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_nsarea",
        "drivers/nvdimm/region_devs.c:nd_region_conflict",
        "drivers/nvdimm/region_devs.c:nd_blk_region_init",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:nd_is_uuid_unique",
        "drivers/nvdimm/badrange.c:nvdimm_badblocks_populate",
        "drivers/nvdimm/claim.c:__nd_attach_ndns",
        "drivers/nvdimm/claim.c:__nd_detach_ndns",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586578432,
      "name": "walk_to_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct nvdimm_bus * walk_to_nvdimm_bus(struct device * nd_dev)
```
</details>
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
