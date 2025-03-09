# Function: <code>intel_gmch_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584230480,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1344",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584230480,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584570272,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1354",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584570272,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584752176,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1356",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584752176,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584830032,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1357",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584830032,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2721
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
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585251888,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1359",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585251888,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2859
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
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585488608,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1359",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585488608,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2840
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
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585611232,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1359",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585611232,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2504
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
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1359",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585834449,
      "name": "intel_gmch_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585832592,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1359",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585977106,
      "name": "intel_gmch_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585975248,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1363",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718161,
      "name": "intel_gmch_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071586716128,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 553
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1363",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591469354,
      "name": "intel_gmch_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071586813776,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 553
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
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1363",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591410576,
      "name": "intel_gmch_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071586691776,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1363",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592462218,
      "name": "intel_gmch_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071587240784,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 822
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
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1364",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594332072,
      "name": "intel_gmch_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071588549232,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 882
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
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1361",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596239470,
      "name": "intel_gmch_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071590002624,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 906
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
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1361",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596767644,
      "name": "intel_gmch_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071590312096,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 965
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
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1361",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597676305,
      "name": "intel_gmch_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071590653408,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 965
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1359",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585738081,
      "name": "intel_gmch_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585736224,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1359",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585597266,
      "name": "intel_gmch_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585595408,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1359",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585927122,
      "name": "intel_gmch_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585925264,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```

```json
{
  "name": "intel_gmch_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gmch_probe",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:1359",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-agp.c:agp_intel_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586035106,
      "name": "intel_gmch_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071586033248,
      "name": "intel_gmch_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int intel_gmch_probe(struct pci_dev * bridge_pdev, struct pci_dev * gpu_pdev, struct agp_bridge_data * bridge)
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
