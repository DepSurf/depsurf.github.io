# Function: <code>__flush_pasid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __flush_pasid(struct protection_domain * domain, int pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584275728,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3202",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_page",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584275728,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int __flush_pasid(struct protection_domain * domain, int pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584618592,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3222",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618592,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
int __flush_pasid(struct protection_domain * domain, int pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584805392,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3346",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584805392,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
int __flush_pasid(struct protection_domain * domain, int pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584894928,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3486",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584894928,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
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
int __flush_pasid(struct protection_domain * domain, int pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585316128,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3277",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585316128,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
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
int __flush_pasid(struct protection_domain * domain, int pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585559072,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3301",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585559072,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
int __flush_pasid(struct protection_domain * domain, int pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585683664,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3366",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585683664,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
int __flush_pasid(struct protection_domain * domain, int pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585910288,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3347",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585910288,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
int __flush_pasid(struct protection_domain * domain, int pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586053600,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3383",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586053600,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
int __flush_pasid(struct protection_domain * domain, int pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586800032,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2780",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586800032,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int __flush_pasid(struct protection_domain * domain, u32 pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586859392,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2871",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586859392,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int __flush_pasid(struct protection_domain * domain, u32 pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586751232,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2287",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586751232,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
int __flush_pasid(struct protection_domain * domain, u32 pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2355",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587304992,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
    },
    {
      "addr": 18446744071592469554,
      "name": "__flush_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int __flush_pasid(struct protection_domain * domain, u32 pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2381",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588617152,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 739
    },
    {
      "addr": 18446744071594339272,
      "name": "__flush_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int __flush_pasid(struct protection_domain * domain, u32 pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2541",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590079616,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
    },
    {
      "addr": 18446744071596240864,
      "name": "__flush_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int __flush_pasid(struct protection_domain * domain, u32 pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2561",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590391568,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
    },
    {
      "addr": 18446744071596768966,
      "name": "__flush_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int __flush_pasid(struct protection_domain * domain, u32 pasid, u64 address, size_t size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590728192,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2648",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590728192,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
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
int __flush_pasid(struct protection_domain * domain, int pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585814576,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3383",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585814576,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
int __flush_pasid(struct protection_domain * domain, int pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585673760,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3383",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585673760,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
int __flush_pasid(struct protection_domain * domain, int pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586003616,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3383",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586003616,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
int __flush_pasid(struct protection_domain * domain, int pasid, u64 address, bool size)
```

```json
{
  "name": "__flush_pasid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586111904,
      "name": "__flush_pasid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:3383",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586111904,
      "name": "__flush_pasid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int pasid</code> ➡️ <code>u32 pasid</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>bool size</code> ➡️ <code>size_t size</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int __flush_pasid(struct protection_domain * domain, int pasid, u64 address, bool size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __flush_pasid(struct protection_domain * domain, int pasid, u64 address, bool size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __flush_pasid(struct protection_domain * domain, int pasid, u64 address, bool size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __flush_pasid(struct protection_domain * domain, int pasid, u64 address, bool size)
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
