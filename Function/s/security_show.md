# Function: <code>security_show</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "security_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586141568,
      "name": "security_show",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:373",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586141568,
      "name": "security_show",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 225
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
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "security_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586377381,
      "name": "security_show",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:370",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586382076,
      "name": "security_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586377216,
      "name": "security_show",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 203
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
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "security_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586525504,
      "name": "security_show",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:370",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586525504,
      "name": "security_show",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 221
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
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "security_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587306624,
      "name": "security_show",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:361",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587306624,
      "name": "security_show",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 194
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
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "security_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587368752,
      "name": "security_show",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:373",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587368752,
      "name": "security_show",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 194
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
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "security_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587250736,
      "name": "security_show",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:373",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587250736,
      "name": "security_show",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 194
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
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "security_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587814752,
      "name": "security_show",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:373",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587814752,
      "name": "security_show",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 194
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
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "security_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589163776,
      "name": "security_show",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:352",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589163776,
      "name": "security_show",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 227
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
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "security_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590715568,
      "name": "security_show",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:352",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590715568,
      "name": "security_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "security_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591057568,
      "name": "security_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:352",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591057568,
      "name": "security_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "security_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591402272,
      "name": "security_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:354",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591402272,
      "name": "security_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "security_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499411408,
      "name": "security_show",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:370",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499411408,
      "name": "security_show",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 232
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
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "security_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292653424,
      "name": "security_show",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:370",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292653424,
      "name": "security_show",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 312
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
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "security_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276640336,
      "name": "security_show",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:370",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276640336,
      "name": "security_show",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 404
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
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "security_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586215984,
      "name": "security_show",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:370",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586215984,
      "name": "security_show",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 221
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
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "security_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586034352,
      "name": "security_show",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:370",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586034352,
      "name": "security_show",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 221
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
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "security_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586473472,
      "name": "security_show",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:370",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586473472,
      "name": "security_show",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 221
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
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "security_show",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586585152,
      "name": "security_show",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:370",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586585152,
      "name": "security_show",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 221
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
```
</details>
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
ssize_t security_show(struct device * dev, struct device_attribute * attr, char * buf)
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
