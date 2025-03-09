# Function: <code>pci_dev_str_match_path</code>

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
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584282766,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:217",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
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
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584477168,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:217",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
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
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584612656,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:217",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
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
int pci_dev_str_match_path(struct pci_dev * dev, const char * path, const char * * endptr)
```

```json
{
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585289408,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:249",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_str_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585289408,
      "name": "pci_dev_str_match_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
int pci_dev_str_match_path(struct pci_dev * dev, const char * path, const char * * endptr)
```

```json
{
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585443424,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:258",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_str_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585443424,
      "name": "pci_dev_str_match_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
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
int pci_dev_str_match_path(struct pci_dev * dev, const char * path, const char * * endptr)
```

```json
{
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585323616,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:258",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_str_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585323616,
      "name": "pci_dev_str_match_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
int pci_dev_str_match_path(struct pci_dev * dev, const char * path, const char * * endptr)
```

```json
{
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585780048,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:268",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_str_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585780048,
      "name": "pci_dev_str_match_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
int pci_dev_str_match_path(struct pci_dev * dev, const char * path, const char * * endptr)
```

```json
{
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586968176,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:285",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_str_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586968176,
      "name": "pci_dev_str_match_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
int pci_dev_str_match_path(struct pci_dev * dev, const char * path, const char * * endptr)
```

```json
{
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588132912,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:269",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_str_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588132912,
      "name": "pci_dev_str_match_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
int pci_dev_str_match_path(struct pci_dev * dev, const char * path, const char * * endptr)
```

```json
{
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588407552,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:284",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_str_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588407552,
      "name": "pci_dev_str_match_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
int pci_dev_str_match_path(struct pci_dev * dev, const char * path, const char * * endptr)
```

```json
{
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588702736,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:284",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_str_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588702736,
      "name": "pci_dev_str_match_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496851976,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:217",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230132352,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:217",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290930848,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:217",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275555216,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:217",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584564816,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:217",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
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
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584492976,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:217",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
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
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584562816,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:217",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
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
  "name": "pci_dev_str_match_path",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584670560,
      "name": "pci_dev_str_match_path",
      "external": false,
      "loc": "drivers/pci/pci.c:217",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
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
int pci_dev_str_match_path(struct pci_dev * dev, const char * path, const char * * endptr)
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
