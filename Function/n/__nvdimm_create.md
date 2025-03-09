# Function: <code>__nvdimm_create</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops)
```

```json
{
  "name": "__nvdimm_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586142272,
      "name": "__nvdimm_create",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:534",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586142272,
      "name": "__nvdimm_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops)
```

```json
{
  "name": "__nvdimm_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586377744,
      "name": "__nvdimm_create",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:531",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586377744,
      "name": "__nvdimm_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops)
```

```json
{
  "name": "__nvdimm_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586526128,
      "name": "__nvdimm_create",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:459",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586526128,
      "name": "__nvdimm_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops)
```

```json
{
  "name": "__nvdimm_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587307344,
      "name": "__nvdimm_create",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:466",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587307344,
      "name": "__nvdimm_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops, const struct nvdimm_fw_ops * fw_ops)
```

```json
{
  "name": "__nvdimm_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587367712,
      "name": "__nvdimm_create",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:594",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587367712,
      "name": "__nvdimm_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 675
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
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops, const struct nvdimm_fw_ops * fw_ops)
```

```json
{
  "name": "__nvdimm_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587249696,
      "name": "__nvdimm_create",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:594",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587249696,
      "name": "__nvdimm_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 675
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
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops, const struct nvdimm_fw_ops * fw_ops)
```

```json
{
  "name": "__nvdimm_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nvdimm_create",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:594",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592521434,
      "name": "__nvdimm_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071587818192,
      "name": "__nvdimm_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops, const struct nvdimm_fw_ops * fw_ops)
```

```json
{
  "name": "__nvdimm_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nvdimm_create",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:575",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594390412,
      "name": "__nvdimm_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071589167008,
      "name": "__nvdimm_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 723
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
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops, const struct nvdimm_fw_ops * fw_ops)
```

```json
{
  "name": "__nvdimm_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nvdimm_create",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:582",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596254837,
      "name": "__nvdimm_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071590719056,
      "name": "__nvdimm_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops, const struct nvdimm_fw_ops * fw_ops)
```

```json
{
  "name": "__nvdimm_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nvdimm_create",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:582",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596783437,
      "name": "__nvdimm_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071591060208,
      "name": "__nvdimm_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 727
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
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops, const struct nvdimm_fw_ops * fw_ops)
```

```json
{
  "name": "__nvdimm_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nvdimm_create",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:584",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597692372,
      "name": "__nvdimm_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071591404912,
      "name": "__nvdimm_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 774
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
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops)
```

```json
{
  "name": "__nvdimm_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499412176,
      "name": "__nvdimm_create",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:459",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499412176,
      "name": "__nvdimm_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops)
```

```json
{
  "name": "__nvdimm_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292653744,
      "name": "__nvdimm_create",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:459",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292653744,
      "name": "__nvdimm_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 864
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
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops)
```

```json
{
  "name": "__nvdimm_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276641186,
      "name": "__nvdimm_create",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:459",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276641186,
      "name": "__nvdimm_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops)
```

```json
{
  "name": "__nvdimm_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586216608,
      "name": "__nvdimm_create",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:459",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586216608,
      "name": "__nvdimm_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops)
```

```json
{
  "name": "__nvdimm_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586034976,
      "name": "__nvdimm_create",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:459",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/nfit/core.c:acpi_nfit_register_dimms"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586034976,
      "name": "__nvdimm_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops)
```

```json
{
  "name": "__nvdimm_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586474096,
      "name": "__nvdimm_create",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:459",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586474096,
      "name": "__nvdimm_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops)
```

```json
{
  "name": "__nvdimm_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586585776,
      "name": "__nvdimm_create",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:459",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586585776,
      "name": "__nvdimm_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops)
```
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct nvdimm_fw_ops * fw_ops</code>
</li>
</ul>
</details>
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
struct nvdimm * __nvdimm_create(struct nvdimm_bus * nvdimm_bus, void * provider_data, const struct attribute_group * * groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource * flush_wpq, const char * dimm_id, const struct nvdimm_security_ops * sec_ops)
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
