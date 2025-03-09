# Function: <code>intel_pinctrl_probe</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int intel_pinctrl_probe(struct platform_device * pdev, const struct intel_pinctrl_soc_data * soc_data)
```

```json
{
  "name": "intel_pinctrl_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583915824,
      "name": "intel_pinctrl_probe",
      "external": true,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1269",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cannonlake.c:cnl_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583915824,
      "name": "intel_pinctrl_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2010
    }
  ]
}
```
</details>
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_pinctrl_probe(struct platform_device * pdev, const struct intel_pinctrl_soc_data * soc_data)
```

```json
{
  "name": "intel_pinctrl_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pinctrl_probe",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1431",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_uid",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585338544,
      "name": "intel_pinctrl_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
    },
    {
      "addr": 18446744071591385321,
      "name": "intel_pinctrl_probe.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_pinctrl_probe(struct platform_device * pdev, const struct intel_pinctrl_soc_data * soc_data)
```

```json
{
  "name": "intel_pinctrl_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pinctrl_probe",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1459",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_uid",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585221648,
      "name": "intel_pinctrl_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1447
    },
    {
      "addr": 18446744071591327750,
      "name": "intel_pinctrl_probe.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_pinctrl_probe(struct platform_device * pdev, const struct intel_pinctrl_soc_data * soc_data)
```

```json
{
  "name": "intel_pinctrl_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pinctrl_probe",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1487",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_uid",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585676960,
      "name": "intel_pinctrl_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1455
    },
    {
      "addr": 18446744071592350158,
      "name": "intel_pinctrl_probe.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_pinctrl_probe(struct platform_device * pdev, const struct intel_pinctrl_soc_data * soc_data)
```

```json
{
  "name": "intel_pinctrl_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pinctrl_probe",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1502",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_uid",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586841376,
      "name": "intel_pinctrl_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1892
    },
    {
      "addr": 18446744071594211684,
      "name": "intel_pinctrl_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
int intel_pinctrl_probe(struct platform_device * pdev, const struct intel_pinctrl_soc_data * soc_data)
```

```json
{
  "name": "intel_pinctrl_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587984512,
      "name": "intel_pinctrl_probe",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1535",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_uid",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587984512,
      "name": "intel_pinctrl_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2001
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
int intel_pinctrl_probe(struct platform_device * pdev, const struct intel_pinctrl_soc_data * soc_data)
```

```json
{
  "name": "intel_pinctrl_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588259136,
      "name": "intel_pinctrl_probe",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1539",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_uid",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588259136,
      "name": "intel_pinctrl_probe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1930
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
int intel_pinctrl_probe(struct platform_device * pdev, const struct intel_pinctrl_soc_data * soc_data)
```

```json
{
  "name": "intel_pinctrl_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588550848,
      "name": "intel_pinctrl_probe",
      "external": true,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1507",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_uid",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588550848,
      "name": "intel_pinctrl_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1930
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int intel_pinctrl_probe(struct platform_device * pdev, const struct intel_pinctrl_soc_data * soc_data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int intel_pinctrl_probe(struct platform_device * pdev, const struct intel_pinctrl_soc_data * soc_data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int intel_pinctrl_probe(struct platform_device * pdev, const struct intel_pinctrl_soc_data * soc_data)
```
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
