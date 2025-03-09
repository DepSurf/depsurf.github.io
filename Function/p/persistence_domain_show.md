# Function: <code>persistence_domain_show</code>

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
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585766208,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:531",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585766208,
      "name": "persistence_domain_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586012624,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:563",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586012624,
      "name": "persistence_domain_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586151152,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:590",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586151152,
      "name": "persistence_domain_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586386531,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:588",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586386416,
      "name": "persistence_domain_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071586392580,
      "name": "persistence_domain_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586534144,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:588",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586534144,
      "name": "persistence_domain_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587319040,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:610",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587319040,
      "name": "persistence_domain_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587381488,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:610",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587381488,
      "name": "persistence_domain_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587262560,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:617",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587262560,
      "name": "persistence_domain_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587823664,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:617",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587823664,
      "name": "persistence_domain_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589174304,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:572",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589174304,
      "name": "persistence_domain_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590727136,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:617",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590727136,
      "name": "persistence_domain_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591068464,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:617",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591068464,
      "name": "persistence_domain_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591412944,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:618",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591412944,
      "name": "persistence_domain_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499422232,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:588",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499422232,
      "name": "persistence_domain_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292666048,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:588",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292666048,
      "name": "persistence_domain_show",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276649866,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:588",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276649866,
      "name": "persistence_domain_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586224624,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:588",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586224624,
      "name": "persistence_domain_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586042992,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:588",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586042992,
      "name": "persistence_domain_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586482112,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:588",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586482112,
      "name": "persistence_domain_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "persistence_domain_show",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586593856,
      "name": "persistence_domain_show",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:588",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586593856,
      "name": "persistence_domain_show",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t persistence_domain_show(struct device * dev, struct device_attribute * attr, char * buf)
```
</details>
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
