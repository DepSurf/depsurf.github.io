# Function: <code>import_uuid</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "import_uuid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584481662,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:71",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_parse_dsk4"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "import_uuid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584595054,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:71",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_parse_dsk4"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "import_uuid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:71",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "import_uuid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:71",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "import_uuid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585764075,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:71",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_parse_vblk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589200200,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:71",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:select_pmem_id",
        "drivers/nvdimm/namespace_devs.c:select_pmem_id",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:71",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589221878,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:71",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void import_uuid(uuid_t * dst, const __u8 * src)
```

```json
{
  "name": "import_uuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586544544,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:71",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_parse_vblk"
      ]
    },
    {
      "addr": 18446744071590755183,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:71",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:select_pmem_id",
        "drivers/nvdimm/namespace_devs.c:select_pmem_id",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590767409,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:71",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590778006,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:71",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586544544,
      "name": "import_uuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590760928,
      "name": "import_uuid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate ❓</summary>

```c
void import_uuid(uuid_t * dst, const __u8 * src)
```

```json
{
  "name": "import_uuid",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586795808,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:81",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_parse_vblk"
      ]
    },
    {
      "addr": 18446744071591088256,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:81",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:select_pmem_id",
        "drivers/nvdimm/namespace_devs.c:select_pmem_id",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid"
      ]
    },
    {
      "addr": 18446744071591102352,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:81",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ]
    },
    {
      "addr": 18446744071591118832,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:81",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586795808,
      "name": "import_uuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591088256,
      "name": "import_uuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591102352,
      "name": "import_uuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591118832,
      "name": "import_uuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate ❓</summary>

```c
void import_uuid(uuid_t * dst, const __u8 * src)
```

```json
{
  "name": "import_uuid",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587072640,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:81",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_parse_vblk"
      ]
    },
    {
      "addr": 18446744071591433152,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:81",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:select_pmem_id",
        "drivers/nvdimm/namespace_devs.c:select_pmem_id",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:has_uuid_at_pos",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid",
        "drivers/nvdimm/namespace_devs.c:namespace_update_uuid"
      ]
    },
    {
      "addr": 18446744071591447632,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:81",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:del_labels",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:__pmem_label_update",
        "drivers/nvdimm/label.c:nsl_get_claim_class",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa",
        "drivers/nvdimm/label.c:nd_label_reserve_dpa"
      ]
    },
    {
      "addr": 18446744071591464256,
      "name": "import_uuid",
      "external": false,
      "loc": "include/linux/uuid.h:81",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/btt_devs.c:nd_btt_arena_is_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587072640,
      "name": "import_uuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591433152,
      "name": "import_uuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591447632,
      "name": "import_uuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591464256,
      "name": "import_uuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void import_uuid(uuid_t * dst, const __u8 * src)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
