# Function: <code>eisa_request_resources</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eisa_request_resources",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604986491,
      "name": "eisa_request_resources",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:261",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_root_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604986491,
      "name": "eisa_request_resources.isra.1",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 282
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eisa_request_resources",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605098260,
      "name": "eisa_request_resources",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:260",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_root_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605098260,
      "name": "eisa_request_resources.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 290
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eisa_request_resources",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605137689,
      "name": "eisa_request_resources",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:260",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_root_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605137689,
      "name": "eisa_request_resources.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 290
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
int eisa_request_resources(struct eisa_root_device * root, struct eisa_device * edev, int slot)
```

```json
{
  "name": "eisa_request_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609407834,
      "name": "eisa_request_resources",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:260",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609407834,
      "name": "eisa_request_resources",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 279
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
int eisa_request_resources(struct eisa_root_device * root, struct eisa_device * edev, int slot)
```

```json
{
  "name": "eisa_request_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612481275,
      "name": "eisa_request_resources",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:260",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612481275,
      "name": "eisa_request_resources",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 279
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
int eisa_request_resources(struct eisa_root_device * root, struct eisa_device * edev, int slot)
```

```json
{
  "name": "eisa_request_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614623709,
      "name": "eisa_request_resources",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:260",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614623709,
      "name": "eisa_request_resources",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 274
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
int eisa_request_resources(struct eisa_root_device * root, struct eisa_device * edev, int slot)
```

```json
{
  "name": "eisa_request_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615579514,
      "name": "eisa_request_resources",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:255",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615579514,
      "name": "eisa_request_resources",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 627
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
int eisa_request_resources(struct eisa_root_device * root, struct eisa_device * edev, int slot)
```

```json
{
  "name": "eisa_request_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617387323,
      "name": "eisa_request_resources",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:255",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617387323,
      "name": "eisa_request_resources",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 630
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
int eisa_request_resources(struct eisa_root_device * root, struct eisa_device * edev, int slot)
```

```json
{
  "name": "eisa_request_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628132752,
      "name": "eisa_request_resources",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:255",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628132752,
      "name": "eisa_request_resources",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 955
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
int eisa_request_resources(struct eisa_root_device * root, struct eisa_device * edev, int slot)
```

```json
{
  "name": "eisa_request_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619899456,
      "name": "eisa_request_resources",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:255",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619899456,
      "name": "eisa_request_resources",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 955
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
int eisa_request_resources(struct eisa_root_device * root, struct eisa_device * edev, int slot)
```

```json
{
  "name": "eisa_request_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622209376,
      "name": "eisa_request_resources",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:255",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_probe",
        "drivers/eisa/eisa-bus.c:eisa_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622209376,
      "name": "eisa_request_resources",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 955
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eisa_request_resources",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605030701,
      "name": "eisa_request_resources",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:260",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_root_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605030701,
      "name": "eisa_request_resources.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 290
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eisa_request_resources",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604996630,
      "name": "eisa_request_resources",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:260",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_root_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604996630,
      "name": "eisa_request_resources.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 290
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eisa_request_resources",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605114725,
      "name": "eisa_request_resources",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:260",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_root_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605114725,
      "name": "eisa_request_resources.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 290
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eisa_request_resources",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605141883,
      "name": "eisa_request_resources",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:260",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_root_register",
        "drivers/eisa/eisa-bus.c:eisa_root_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605141883,
      "name": "eisa_request_resources.isra.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 290
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int eisa_request_resources(struct eisa_root_device * root, struct eisa_device * edev, int slot)
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
