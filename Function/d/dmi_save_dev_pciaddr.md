# Function: <code>dmi_save_dev_pciaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595502879,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:324",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595500735,
      "name": "dmi_save_dev_pciaddr.part.1",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595756270,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:324",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595754140,
      "name": "dmi_save_dev_pciaddr.part.2",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 162
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596682060,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:330",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596682060,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 201
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071603012136,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:330",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603012136,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 201
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071603185075,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:322",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603185075,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 201
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604995295,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:322",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604995295,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 201
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605107714,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:323",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605107714,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 197
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605147089,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:323",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605147089,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 197
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609416271,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:356",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609416271,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 191
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612490087,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:356",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612490087,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 191
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614632208,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:357",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614632208,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 191
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615589220,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:357",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615589220,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 191
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617397873,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:357",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617397873,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 214
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628146368,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:357",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628146368,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 219
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619913344,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:357",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619913344,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 219
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622223424,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:357",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622223424,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 219
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511272892,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:323",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511272892,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 200
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243925268,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:323",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243925268,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605037861,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:323",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605037861,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 197
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605003201,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:323",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605003201,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 197
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605124102,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:323",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605124102,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 197
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```

```json
{
  "name": "dmi_save_dev_pciaddr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605151283,
      "name": "dmi_save_dev_pciaddr",
      "external": false,
      "loc": "drivers/firmware/dmi_scan.c:323",
      "file": "drivers/firmware/dmi_scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/dmi_scan.c:dmi_decode",
        "drivers/firmware/dmi_scan.c:dmi_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605151283,
      "name": "dmi_save_dev_pciaddr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 197
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char * name, int type)
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
