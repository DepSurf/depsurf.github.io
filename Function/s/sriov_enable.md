# Function: <code>sriov_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583392433,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:238",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_enable_sriov"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583707843,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:238",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_enable_sriov"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583846179,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:241",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_enable_sriov"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583887565,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:234",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_enable_sriov"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584150237,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:227",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_enable_sriov"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584367184,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:254",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584367184,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1056
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
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584462320,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:276",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584462320,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1080
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
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:274",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584659728,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 970
    },
    {
      "addr": 18446744071584663280,
      "name": "sriov_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:440",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584797888,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 970
    },
    {
      "addr": 18446744071584801551,
      "name": "sriov_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:459",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585492192,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 968
    },
    {
      "addr": 18446744071585494523,
      "name": "sriov_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:460",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585624736,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 968
    },
    {
      "addr": 18446744071591418924,
      "name": "sriov_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:550",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585503312,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 971
    },
    {
      "addr": 18446744071591361333,
      "name": "sriov_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:557",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585971024,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1021
    },
    {
      "addr": 18446744071592390486,
      "name": "sriov_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:598",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587176992,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1010
    },
    {
      "addr": 18446744071594254234,
      "name": "sriov_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588390864,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:598",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588390864,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1106
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
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588666880,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:598",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588666880,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1078
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
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588967520,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:597",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588967520,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1078
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
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497066824,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:440",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497066824,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
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
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230276304,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:440",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230276304,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
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
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291109024,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:440",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291109024,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1456
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
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275711524,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:440",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275711524,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 928
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:440",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584746640,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 970
    },
    {
      "addr": 18446744071584750287,
      "name": "sriov_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:440",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584677408,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 970
    },
    {
      "addr": 18446744071584681071,
      "name": "sriov_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:440",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584748048,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 970
    },
    {
      "addr": 18446744071584751711,
      "name": "sriov_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```

```json
{
  "name": "sriov_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sriov_enable",
      "external": false,
      "loc": "drivers/pci/iov.c:440",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584855616,
      "name": "sriov_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 970
    },
    {
      "addr": 18446744071584859231,
      "name": "sriov_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int sriov_enable(struct pci_dev * dev, int nr_virtfn)
```
</details>
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
