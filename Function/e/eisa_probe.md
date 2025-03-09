# Function: <code>eisa_probe</code>

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
  "name": "eisa_probe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604986886,
      "name": "eisa_probe",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:315",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/eisa-bus.c:eisa_root_register"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eisa_probe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605098663,
      "name": "eisa_probe",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:314",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/eisa-bus.c:eisa_root_register"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eisa_probe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605138092,
      "name": "eisa_probe",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:314",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/eisa-bus.c:eisa_root_register"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int eisa_probe(struct eisa_root_device * root)
```

```json
{
  "name": "eisa_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609409013,
      "name": "eisa_probe",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:314",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_root_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609409013,
      "name": "eisa_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 544
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
int eisa_probe(struct eisa_root_device * root)
```

```json
{
  "name": "eisa_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612482513,
      "name": "eisa_probe",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:314",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_root_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612482513,
      "name": "eisa_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 544
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
int eisa_probe(struct eisa_root_device * root)
```

```json
{
  "name": "eisa_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614624878,
      "name": "eisa_probe",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:314",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_root_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614624878,
      "name": "eisa_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 544
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
int eisa_probe(struct eisa_root_device * root)
```

```json
{
  "name": "eisa_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615581213,
      "name": "eisa_probe",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:309",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_root_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615581213,
      "name": "eisa_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 544
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
int eisa_probe(struct eisa_root_device * root)
```

```json
{
  "name": "eisa_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617389073,
      "name": "eisa_probe",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:309",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_root_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617389073,
      "name": "eisa_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 579
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
int eisa_probe(struct eisa_root_device * root)
```

```json
{
  "name": "eisa_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628134880,
      "name": "eisa_probe",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:309",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_root_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628134880,
      "name": "eisa_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1233
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
int eisa_probe(struct eisa_root_device * root)
```

```json
{
  "name": "eisa_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619901584,
      "name": "eisa_probe",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:309",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_root_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619901584,
      "name": "eisa_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1192
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
int eisa_probe(struct eisa_root_device * root)
```

```json
{
  "name": "eisa_probe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622211568,
      "name": "eisa_probe",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:309",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/eisa/eisa-bus.c:eisa_root_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622211568,
      "name": "eisa_probe",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1295
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
  "name": "eisa_probe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605031104,
      "name": "eisa_probe",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:314",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/eisa-bus.c:eisa_root_register"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eisa_probe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604997033,
      "name": "eisa_probe",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:314",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/eisa-bus.c:eisa_root_register"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eisa_probe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605115128,
      "name": "eisa_probe",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:314",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/eisa-bus.c:eisa_root_register"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eisa_probe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605142286,
      "name": "eisa_probe",
      "external": false,
      "loc": "drivers/eisa/eisa-bus.c:314",
      "file": "drivers/eisa/eisa-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/eisa/eisa-bus.c:eisa_root_register"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int eisa_probe(struct eisa_root_device * root)
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
