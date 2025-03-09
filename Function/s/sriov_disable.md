# Function: <code>sriov_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583394520,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:353",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_disable_sriov"
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
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583708952,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:353",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_disable_sriov"
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
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583847288,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:356",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_disable_sriov"
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
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583888630,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:350",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_disable_sriov"
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
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584151302,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:343",
      "file": "drivers/pci/iov.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_disable_sriov"
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584368304,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:370",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584368304,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584463472,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:398",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463472,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584660768,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:396",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584660768,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584798928,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:562",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584798928,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585493232,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:578",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585493232,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585625776,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:579",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585625776,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585504352,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:669",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585504352,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585972112,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:676",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585972112,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587178080,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:717",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587178080,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588392080,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:717",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588392080,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588668064,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:717",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588668064,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588968704,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:716",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588968704,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497067968,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:562",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497067968,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230277404,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:562",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230277404,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291110608,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:562",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291110608,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275712528,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:562",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275712528,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584747680,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:562",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584747680,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584678448,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:562",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584678448,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584749088,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:562",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584749088,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
void sriov_disable(struct pci_dev * dev)
```

```json
{
  "name": "sriov_disable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584856624,
      "name": "sriov_disable",
      "external": false,
      "loc": "drivers/pci/iov.c:562",
      "file": "drivers/pci/iov.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/iov.c:pci_disable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584856624,
      "name": "sriov_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
void sriov_disable(struct pci_dev * dev)
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
