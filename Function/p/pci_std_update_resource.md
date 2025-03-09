# Function: <code>pci_std_update_resource</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583738528,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:28",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-res.c:pci_update_resource"
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
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583780336,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:28",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-res.c:pci_update_resource"
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
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584040944,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:29",
      "file": "drivers/pci/setup-res.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-res.c:pci_update_resource"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584237728,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584327456,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584522449,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584657569,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void pci_std_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585340576,
      "name": "pci_std_update_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
    },
    {
      "addr": 18446744071585342718,
      "name": "pci_std_update_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void pci_std_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585493664,
      "name": "pci_std_update_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
    },
    {
      "addr": 18446744071591395802,
      "name": "pci_std_update_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void pci_std_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585373200,
      "name": "pci_std_update_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
    },
    {
      "addr": 18446744071591338108,
      "name": "pci_std_update_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void pci_std_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585833952,
      "name": "pci_std_update_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
    },
    {
      "addr": 18446744071592365691,
      "name": "pci_std_update_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void pci_std_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025536,
      "name": "pci_std_update_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
    },
    {
      "addr": 18446744071594227973,
      "name": "pci_std_update_resource.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void pci_std_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588202272,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588202272,
      "name": "pci_std_update_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
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
void pci_std_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588477952,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588477952,
      "name": "pci_std_update_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
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
void pci_std_update_resource(struct pci_dev * dev, int resno)
```

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588775296,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-res.c:pci_reassign_resource",
        "drivers/pci/setup-res.c:pci_assign_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588775296,
      "name": "pci_std_update_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 633
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496905780,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230181828,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290999296,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275594010,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584608033,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584537857,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584607729,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_std_update_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584715425,
      "name": "pci_std_update_resource",
      "external": false,
      "loc": "drivers/pci/setup-res.c:25",
      "file": "drivers/pci/setup-res.c",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void pci_std_update_resource(struct pci_dev * dev, int resno)
```
</details>
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
