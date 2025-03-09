# Function: <code>amd_iommu_deactivate_guest_mode</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int amd_iommu_deactivate_guest_mode(void * data)
```

```json
{
  "name": "amd_iommu_deactivate_guest_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586052768,
      "name": "amd_iommu_deactivate_guest_mode",
      "external": true,
      "loc": "drivers/iommu/amd_iommu.c:4428",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586052768,
      "name": "amd_iommu_deactivate_guest_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int amd_iommu_deactivate_guest_mode(void * data)
```

```json
{
  "name": "amd_iommu_deactivate_guest_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586805696,
      "name": "amd_iommu_deactivate_guest_mode",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:3857",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586805696,
      "name": "amd_iommu_deactivate_guest_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int amd_iommu_deactivate_guest_mode(void * data)
```

```json
{
  "name": "amd_iommu_deactivate_guest_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586864944,
      "name": "amd_iommu_deactivate_guest_mode",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:3909",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586864944,
      "name": "amd_iommu_deactivate_guest_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int amd_iommu_deactivate_guest_mode(void * data)
```

```json
{
  "name": "amd_iommu_deactivate_guest_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586741040,
      "name": "amd_iommu_deactivate_guest_mode",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:3275",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586741040,
      "name": "amd_iommu_deactivate_guest_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int amd_iommu_deactivate_guest_mode(void * data)
```

```json
{
  "name": "amd_iommu_deactivate_guest_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_iommu_deactivate_guest_mode",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:3343",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592468816,
      "name": "amd_iommu_deactivate_guest_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071587296272,
      "name": "amd_iommu_deactivate_guest_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int amd_iommu_deactivate_guest_mode(void * data)
```

```json
{
  "name": "amd_iommu_deactivate_guest_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_iommu_deactivate_guest_mode",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:3369",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594338911,
      "name": "amd_iommu_deactivate_guest_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071588610032,
      "name": "amd_iommu_deactivate_guest_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int amd_iommu_deactivate_guest_mode(void * data)
```

```json
{
  "name": "amd_iommu_deactivate_guest_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_iommu_deactivate_guest_mode",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:3522",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596240501,
      "name": "amd_iommu_deactivate_guest_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071590072352,
      "name": "amd_iommu_deactivate_guest_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int amd_iommu_deactivate_guest_mode(void * data)
```

```json
{
  "name": "amd_iommu_deactivate_guest_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "amd_iommu_deactivate_guest_mode",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:3559",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596768305,
      "name": "amd_iommu_deactivate_guest_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071590375568,
      "name": "amd_iommu_deactivate_guest_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
int amd_iommu_deactivate_guest_mode(void * data)
```

```json
{
  "name": "amd_iommu_deactivate_guest_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590716592,
      "name": "amd_iommu_deactivate_guest_mode",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:3610",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590716592,
      "name": "amd_iommu_deactivate_guest_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int amd_iommu_deactivate_guest_mode(void * data)
```

```json
{
  "name": "amd_iommu_deactivate_guest_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585813744,
      "name": "amd_iommu_deactivate_guest_mode",
      "external": true,
      "loc": "drivers/iommu/amd_iommu.c:4428",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585813744,
      "name": "amd_iommu_deactivate_guest_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int amd_iommu_deactivate_guest_mode(void * data)
```

```json
{
  "name": "amd_iommu_deactivate_guest_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585672928,
      "name": "amd_iommu_deactivate_guest_mode",
      "external": true,
      "loc": "drivers/iommu/amd_iommu.c:4428",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585672928,
      "name": "amd_iommu_deactivate_guest_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int amd_iommu_deactivate_guest_mode(void * data)
```

```json
{
  "name": "amd_iommu_deactivate_guest_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586002784,
      "name": "amd_iommu_deactivate_guest_mode",
      "external": true,
      "loc": "drivers/iommu/amd_iommu.c:4428",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586002784,
      "name": "amd_iommu_deactivate_guest_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int amd_iommu_deactivate_guest_mode(void * data)
```

```json
{
  "name": "amd_iommu_deactivate_guest_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586111072,
      "name": "amd_iommu_deactivate_guest_mode",
      "external": true,
      "loc": "drivers/iommu/amd_iommu.c:4428",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586111072,
      "name": "amd_iommu_deactivate_guest_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int amd_iommu_deactivate_guest_mode(void * data)
```
</details>
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
int amd_iommu_deactivate_guest_mode(void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int amd_iommu_deactivate_guest_mode(void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int amd_iommu_deactivate_guest_mode(void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int amd_iommu_deactivate_guest_mode(void * data)
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
