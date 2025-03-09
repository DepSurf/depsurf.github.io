# Function: <code>intel_pinctrl_should_save</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool intel_pinctrl_should_save(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pinctrl_should_save",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583917840,
      "name": "intel_pinctrl_should_save",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1371",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583917840,
      "name": "intel_pinctrl_should_save",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
bool intel_pinctrl_should_save(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pinctrl_should_save",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pinctrl_should_save",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1578",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585343008,
      "name": "intel_pinctrl_should_save",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071591385477,
      "name": "intel_pinctrl_should_save.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
bool intel_pinctrl_should_save(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pinctrl_should_save",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pinctrl_should_save",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1633",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585227264,
      "name": "intel_pinctrl_should_save",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071591327908,
      "name": "intel_pinctrl_should_save.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
bool intel_pinctrl_should_save(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pinctrl_should_save",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pinctrl_should_save",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1661",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585682736,
      "name": "intel_pinctrl_should_save",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071592350551,
      "name": "intel_pinctrl_should_save.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
bool intel_pinctrl_should_save(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pinctrl_should_save",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pinctrl_should_save",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1674",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586848096,
      "name": "intel_pinctrl_should_save",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071594212139,
      "name": "intel_pinctrl_should_save.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
bool intel_pinctrl_should_save(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pinctrl_should_save",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587991328,
      "name": "intel_pinctrl_should_save",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1718",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587991328,
      "name": "intel_pinctrl_should_save",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
bool intel_pinctrl_should_save(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pinctrl_should_save",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588265888,
      "name": "intel_pinctrl_should_save",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1722",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588265888,
      "name": "intel_pinctrl_should_save",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
bool intel_pinctrl_should_save(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pinctrl_should_save",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588560080,
      "name": "intel_pinctrl_should_save",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1689",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588560080,
      "name": "intel_pinctrl_should_save",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
bool intel_pinctrl_should_save(struct intel_pinctrl * pctrl, unsigned int pin)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
bool intel_pinctrl_should_save(struct intel_pinctrl * pctrl, unsigned int pin)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool intel_pinctrl_should_save(struct intel_pinctrl * pctrl, unsigned int pin)
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
