# Function: <code>pcc_cpufreq_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595311638,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:387",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595494740,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:387",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595747827,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:387",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596676488,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:387",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603006592,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:387",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603179125,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:387",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604989248,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:387",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int pcc_cpufreq_probe()
```

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605101013,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:387",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605101013,
      "name": "pcc_cpufreq_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1121
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
int pcc_cpufreq_probe()
```

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605140428,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:387",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605140428,
      "name": "pcc_cpufreq_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1121
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
int pcc_cpufreq_probe()
```

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609411479,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:387",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609411479,
      "name": "pcc_cpufreq_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1098
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
int pcc_cpufreq_probe()
```

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612485025,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:387",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612485025,
      "name": "pcc_cpufreq_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1098
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
int pcc_cpufreq_probe()
```

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614627349,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:387",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614627349,
      "name": "pcc_cpufreq_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1098
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
int pcc_cpufreq_probe()
```

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615583736,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:387",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615583736,
      "name": "pcc_cpufreq_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1074
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
int pcc_cpufreq_probe()
```

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617392107,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:387",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617392107,
      "name": "pcc_cpufreq_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1077
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
int pcc_cpufreq_probe()
```

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628139504,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:387",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628139504,
      "name": "pcc_cpufreq_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1238
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
int pcc_cpufreq_probe(struct platform_device * pdev)
```

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619907952,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:580",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619907952,
      "name": "pcc_cpufreq_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 211
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
int pcc_cpufreq_probe(struct platform_device * pdev)
```

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622217984,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:580",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622217984,
      "name": "pcc_cpufreq_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 211
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int pcc_cpufreq_probe()
```

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604999369,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:387",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604999369,
      "name": "pcc_cpufreq_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1121
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
int pcc_cpufreq_probe()
```

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605117464,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:387",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605117464,
      "name": "pcc_cpufreq_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1121
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
int pcc_cpufreq_probe()
```

```json
{
  "name": "pcc_cpufreq_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605144622,
      "name": "pcc_cpufreq_probe",
      "external": false,
      "loc": "drivers/cpufreq/pcc-cpufreq.c:387",
      "file": "drivers/cpufreq/pcc-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605144622,
      "name": "pcc_cpufreq_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1121
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
int pcc_cpufreq_probe()
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct platform_device * pdev</code>
</li>
</ul>
</details>
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
int pcc_cpufreq_probe()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int pcc_cpufreq_probe()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int pcc_cpufreq_probe()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int pcc_cpufreq_probe()
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int pcc_cpufreq_probe()
```
</details>
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
