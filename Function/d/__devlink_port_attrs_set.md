# Function: <code>__devlink_port_attrs_set</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __devlink_port_attrs_set(struct devlink_port * devlink_port, enum devlink_port_flavour flavour, const unsigned char * switch_id, unsigned char switch_id_len)
```

```json
{
  "name": "__devlink_port_attrs_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588577572,
      "name": "__devlink_port_attrs_set",
      "external": false,
      "loc": "net/core/devlink.c:5758",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_attrs_pci_vf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_pf_set",
        "net/core/devlink.c:devlink_port_attrs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588577520,
      "name": "__devlink_port_attrs_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    },
    {
      "addr": 18446744071588618463,
      "name": "__devlink_port_attrs_set.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __devlink_port_attrs_set(struct devlink_port * devlink_port, enum devlink_port_flavour flavour, const unsigned char * switch_id, unsigned char switch_id_len)
```

```json
{
  "name": "__devlink_port_attrs_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588795392,
      "name": "__devlink_port_attrs_set",
      "external": false,
      "loc": "net/core/devlink.c:6455",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_attrs_pci_vf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_pf_set",
        "net/core/devlink.c:devlink_port_attrs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588795392,
      "name": "__devlink_port_attrs_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __devlink_port_attrs_set(struct devlink_port * devlink_port, enum devlink_port_flavour flavour, const unsigned char * switch_id, unsigned char switch_id_len)
```

```json
{
  "name": "__devlink_port_attrs_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589664768,
      "name": "__devlink_port_attrs_set",
      "external": false,
      "loc": "net/core/devlink.c:7391",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_attrs_pci_vf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_pf_set",
        "net/core/devlink.c:devlink_port_attrs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589664768,
      "name": "__devlink_port_attrs_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__devlink_port_attrs_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589698175,
      "name": "__devlink_port_attrs_set",
      "external": false,
      "loc": "net/core/devlink.c:8283",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_port_attrs_pci_vf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_pf_set",
        "net/core/devlink.c:devlink_port_attrs_set"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__devlink_port_attrs_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589582410,
      "name": "__devlink_port_attrs_set",
      "external": false,
      "loc": "net/core/devlink.c:8502",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_port_attrs_pci_sf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_vf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_pf_set",
        "net/core/devlink.c:devlink_port_attrs_set"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__devlink_port_attrs_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590327019,
      "name": "__devlink_port_attrs_set",
      "external": false,
      "loc": "net/core/devlink.c:9245",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_port_attrs_pci_sf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_vf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_pf_set",
        "net/core/devlink.c:devlink_port_attrs_set"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__devlink_port_attrs_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591915327,
      "name": "__devlink_port_attrs_set",
      "external": false,
      "loc": "net/core/devlink.c:9852",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_port_attrs_pci_sf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_vf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_pf_set",
        "net/core/devlink.c:devlink_port_attrs_set"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__devlink_port_attrs_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593719728,
      "name": "__devlink_port_attrs_set",
      "external": false,
      "loc": "net/core/devlink.c:10534",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_port_attrs_pci_sf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_vf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_pf_set"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__devlink_port_attrs_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595813072,
      "name": "__devlink_port_attrs_set",
      "external": false,
      "loc": "net/devlink/leftover.c:7102",
      "file": "net/devlink/leftover.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/leftover.c:devlink_port_attrs_pci_sf_set",
        "net/devlink/leftover.c:devlink_port_attrs_pci_vf_set",
        "net/devlink/leftover.c:devlink_port_attrs_pci_pf_set",
        "net/devlink/leftover.c:devlink_port_attrs_set"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__devlink_port_attrs_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596694336,
      "name": "__devlink_port_attrs_set",
      "external": false,
      "loc": "net/devlink/port.c:1283",
      "file": "net/devlink/port.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/port.c:devlink_port_attrs_pci_sf_set",
        "net/devlink/port.c:devlink_port_attrs_pci_vf_set",
        "net/devlink/port.c:devlink_port_attrs_pci_pf_set",
        "net/devlink/port.c:devlink_port_attrs_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __devlink_port_attrs_set(struct devlink_port * devlink_port, enum devlink_port_flavour flavour, const unsigned char * switch_id, unsigned char switch_id_len)
```

```json
{
  "name": "__devlink_port_attrs_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502366016,
      "name": "__devlink_port_attrs_set",
      "external": false,
      "loc": "net/core/devlink.c:6455",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_attrs_pci_vf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_pf_set",
        "net/core/devlink.c:devlink_port_attrs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502366016,
      "name": "__devlink_port_attrs_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int __devlink_port_attrs_set(struct devlink_port * devlink_port, enum devlink_port_flavour flavour, const unsigned char * switch_id, unsigned char switch_id_len)
```

```json
{
  "name": "__devlink_port_attrs_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235103312,
      "name": "__devlink_port_attrs_set",
      "external": false,
      "loc": "net/core/devlink.c:6455",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_attrs_pci_vf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_pf_set",
        "net/core/devlink.c:devlink_port_attrs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235103312,
      "name": "__devlink_port_attrs_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __devlink_port_attrs_set(struct devlink_port * devlink_port, enum devlink_port_flavour flavour, const unsigned char * switch_id, unsigned char switch_id_len)
```

```json
{
  "name": "__devlink_port_attrs_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295896528,
      "name": "__devlink_port_attrs_set",
      "external": false,
      "loc": "net/core/devlink.c:6455",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_attrs_pci_vf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_pf_set",
        "net/core/devlink.c:devlink_port_attrs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295896528,
      "name": "__devlink_port_attrs_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int __devlink_port_attrs_set(struct devlink_port * devlink_port, enum devlink_port_flavour flavour, const unsigned char * switch_id, unsigned char switch_id_len)
```

```json
{
  "name": "__devlink_port_attrs_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278582410,
      "name": "__devlink_port_attrs_set",
      "external": false,
      "loc": "net/core/devlink.c:6455",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_attrs_pci_vf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_pf_set",
        "net/core/devlink.c:devlink_port_attrs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278582410,
      "name": "__devlink_port_attrs_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int __devlink_port_attrs_set(struct devlink_port * devlink_port, enum devlink_port_flavour flavour, const unsigned char * switch_id, unsigned char switch_id_len)
```

```json
{
  "name": "__devlink_port_attrs_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588401776,
      "name": "__devlink_port_attrs_set",
      "external": false,
      "loc": "net/core/devlink.c:6455",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_attrs_pci_vf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_pf_set",
        "net/core/devlink.c:devlink_port_attrs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588401776,
      "name": "__devlink_port_attrs_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int __devlink_port_attrs_set(struct devlink_port * devlink_port, enum devlink_port_flavour flavour, const unsigned char * switch_id, unsigned char switch_id_len)
```

```json
{
  "name": "__devlink_port_attrs_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588114464,
      "name": "__devlink_port_attrs_set",
      "external": false,
      "loc": "net/core/devlink.c:6455",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_attrs_pci_vf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_pf_set",
        "net/core/devlink.c:devlink_port_attrs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588114464,
      "name": "__devlink_port_attrs_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int __devlink_port_attrs_set(struct devlink_port * devlink_port, enum devlink_port_flavour flavour, const unsigned char * switch_id, unsigned char switch_id_len)
```

```json
{
  "name": "__devlink_port_attrs_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588733952,
      "name": "__devlink_port_attrs_set",
      "external": false,
      "loc": "net/core/devlink.c:6455",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_attrs_pci_vf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_pf_set",
        "net/core/devlink.c:devlink_port_attrs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588733952,
      "name": "__devlink_port_attrs_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int __devlink_port_attrs_set(struct devlink_port * devlink_port, enum devlink_port_flavour flavour, const unsigned char * switch_id, unsigned char switch_id_len)
```

```json
{
  "name": "__devlink_port_attrs_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588874416,
      "name": "__devlink_port_attrs_set",
      "external": false,
      "loc": "net/core/devlink.c:6455",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_attrs_pci_vf_set",
        "net/core/devlink.c:devlink_port_attrs_pci_pf_set",
        "net/core/devlink.c:devlink_port_attrs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588874416,
      "name": "__devlink_port_attrs_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
int __devlink_port_attrs_set(struct devlink_port * devlink_port, enum devlink_port_flavour flavour, const unsigned char * switch_id, unsigned char switch_id_len)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int __devlink_port_attrs_set(struct devlink_port * devlink_port, enum devlink_port_flavour flavour, const unsigned char * switch_id, unsigned char switch_id_len)
```
</details>
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
