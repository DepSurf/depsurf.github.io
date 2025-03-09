# Function: <code>autorun_devices</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585766947,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:5725",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl"
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
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586164526,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:5737",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl"
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
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586367704,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:5788",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl"
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
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586468319,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6002",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl"
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
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586935727,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6053",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl"
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
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587239048,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6119",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587419309,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6106",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void autorun_devices(int part)
```

```json
{
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587690493,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6168",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587690493,
      "name": "autorun_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
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
void autorun_devices(int part)
```

```json
{
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587894786,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6269",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587894786,
      "name": "autorun_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
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
void autorun_devices(int part)
```

```json
{
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588746214,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6467",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:autostart_arrays"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588746214,
      "name": "autorun_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
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
void autorun_devices(int part)
```

```json
{
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591589559,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6499",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_autostart_arrays"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591589559,
      "name": "autorun_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 926
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
void autorun_devices(int part)
```

```json
{
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591532690,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6456",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_autostart_arrays"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591532690,
      "name": "autorun_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 907
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
void autorun_devices(int part)
```

```json
{
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592644306,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6469",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_autostart_arrays"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592644306,
      "name": "autorun_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
void autorun_devices(int part)
```

```json
{
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594528709,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6461",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_autostart_arrays"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594528709,
      "name": "autorun_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
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
void autorun_devices(int part)
```

```json
{
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592488336,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6448",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_autostart_arrays"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592488336,
      "name": "autorun_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1082
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
void autorun_devices(int part)
```

```json
{
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592918496,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6452",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_autostart_arrays"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592918496,
      "name": "autorun_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1091
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
void autorun_devices(int part)
```

```json
{
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593668272,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6562",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_autostart_arrays"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593668272,
      "name": "autorun_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1135
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
void autorun_devices(int part)
```

```json
{
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501124540,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6269",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501124540,
      "name": "autorun_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 860
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233637964,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6269",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl"
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
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294624684,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6269",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl"
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
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277841052,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6269",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void autorun_devices(int part)
```

```json
{
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587525762,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6269",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587525762,
      "name": "autorun_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
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
void autorun_devices(int part)
```

```json
{
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587293922,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6269",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587293922,
      "name": "autorun_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
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
void autorun_devices(int part)
```

```json
{
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587850930,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6269",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587850930,
      "name": "autorun_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
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
void autorun_devices(int part)
```

```json
{
  "name": "autorun_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587965586,
      "name": "autorun_devices",
      "external": false,
      "loc": "drivers/md/md.c:6269",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587965586,
      "name": "autorun_devices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
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
void autorun_devices(int part)
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
void autorun_devices(int part)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void autorun_devices(int part)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void autorun_devices(int part)
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
