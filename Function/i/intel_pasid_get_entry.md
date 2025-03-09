# Function: <code>intel_pasid_get_entry</code>

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
struct pasid_entry * intel_pasid_get_entry(struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585743456,
      "name": "intel_pasid_get_entry",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:239",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585743456,
      "name": "intel_pasid_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
struct pasid_entry * intel_pasid_get_entry(struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_get_entry",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:224",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585977459,
      "name": "intel_pasid_get_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585975168,
      "name": "intel_pasid_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct pasid_entry * intel_pasid_get_entry(struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586120640,
      "name": "intel_pasid_get_entry",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:224",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586120640,
      "name": "intel_pasid_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct pasid_entry * intel_pasid_get_entry(struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586871968,
      "name": "intel_pasid_get_entry",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:245",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_nested",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586871968,
      "name": "intel_pasid_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
struct pasid_entry * intel_pasid_get_entry(struct device * dev, u32 pasid)
```

```json
{
  "name": "intel_pasid_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586920784,
      "name": "intel_pasid_get_entry",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:245",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_nested",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586920784,
      "name": "intel_pasid_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
struct pasid_entry * intel_pasid_get_entry(struct device * dev, u32 pasid)
```

```json
{
  "name": "intel_pasid_get_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586800560,
      "name": "intel_pasid_get_entry",
      "external": false,
      "loc": "drivers/iommu/intel/pasid.c:244",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_nested",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586800560,
      "name": "intel_pasid_get_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
struct pasid_entry * intel_pasid_get_entry(struct device * dev, u32 pasid)
```

```json
{
  "name": "intel_pasid_get_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587357504,
      "name": "intel_pasid_get_entry",
      "external": false,
      "loc": "drivers/iommu/intel/pasid.c:244",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_nested",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587357504,
      "name": "intel_pasid_get_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pasid_get_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588669264,
      "name": "intel_pasid_get_entry",
      "external": false,
      "loc": "drivers/iommu/intel/pasid.c:181",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588669264,
      "name": "intel_pasid_get_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pasid_get_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590142240,
      "name": "intel_pasid_get_entry",
      "external": false,
      "loc": "drivers/iommu/intel/pasid.c:186",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590142240,
      "name": "intel_pasid_get_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pasid_get_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590456560,
      "name": "intel_pasid_get_entry",
      "external": false,
      "loc": "drivers/iommu/intel/pasid.c:186",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590456560,
      "name": "intel_pasid_get_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_pasid_get_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590804272,
      "name": "intel_pasid_get_entry",
      "external": false,
      "loc": "drivers/iommu/intel/pasid.c:129",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_nested",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_dirty_tracking",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590804272,
      "name": "intel_pasid_get_entry.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
struct pasid_entry * intel_pasid_get_entry(struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585881008,
      "name": "intel_pasid_get_entry",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:224",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585881008,
      "name": "intel_pasid_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct pasid_entry * intel_pasid_get_entry(struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585740784,
      "name": "intel_pasid_get_entry",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:224",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585740784,
      "name": "intel_pasid_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct pasid_entry * intel_pasid_get_entry(struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586070656,
      "name": "intel_pasid_get_entry",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:224",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586070656,
      "name": "intel_pasid_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct pasid_entry * intel_pasid_get_entry(struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586178896,
      "name": "intel_pasid_get_entry",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:224",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586178896,
      "name": "intel_pasid_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
struct pasid_entry * intel_pasid_get_entry(struct device * dev, int pasid)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct pasid_entry * intel_pasid_get_entry(struct device * dev, u32 pasid)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct pasid_entry * intel_pasid_get_entry(struct device * dev, int pasid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct pasid_entry * intel_pasid_get_entry(struct device * dev, int pasid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct pasid_entry * intel_pasid_get_entry(struct device * dev, int pasid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct pasid_entry * intel_pasid_get_entry(struct device * dev, int pasid)
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
