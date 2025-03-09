# Function: <code>uuid_parse</code>

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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583450144,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:127",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_ldmdb_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583450144,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583630240,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:127",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_ldmdb_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583630240,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583846800,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:127",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_ldmdb_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583846800,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583930512,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:127",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_ldmdb_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583930512,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584110080,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:119",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110080,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584232928,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:119",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584232928,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584639904,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:129",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_parse_dsk3",
        "block/partitions/ldm.c:ldm_parse_privhead",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584639904,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584759440,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:129",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_parse_dsk3",
        "block/partitions/ldm.c:ldm_parse_privhead",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584759440,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584787872,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:129",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584787872,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585218688,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:129",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585218688,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586056544,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:129",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586056544,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587040512,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:129",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587040512,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587297632,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:129",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587297632,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587583456,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:129",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init",
        "drivers/nvdimm/label.c:nd_label_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587583456,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496108568,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:119",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_parse_privhead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496108568,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229433676,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:119",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229433676,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290356944,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:119",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290356944,
      "name": "uuid_parse",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275174050,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:119",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275174050,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584201664,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:119",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584201664,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584136880,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:119",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584136880,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584185424,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:119",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584185424,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int uuid_parse(const char * uuid, uuid_t * u)
```

```json
{
  "name": "uuid_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584289776,
      "name": "uuid_parse",
      "external": true,
      "loc": "lib/uuid.c:119",
      "file": "lib/uuid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289776,
      "name": "uuid_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int uuid_parse(const char * uuid, uuid_t * u)
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
