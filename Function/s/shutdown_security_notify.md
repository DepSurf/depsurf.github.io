# Function: <code>shutdown_security_notify</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void shutdown_security_notify(void * data)
```

```json
{
  "name": "shutdown_security_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586140464,
      "name": "shutdown_security_notify",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:581",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586140464,
      "name": "shutdown_security_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void shutdown_security_notify(void * data)
```

```json
{
  "name": "shutdown_security_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586376160,
      "name": "shutdown_security_notify",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:580",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586376160,
      "name": "shutdown_security_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void shutdown_security_notify(void * data)
```

```json
{
  "name": "shutdown_security_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586524320,
      "name": "shutdown_security_notify",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:508",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586524320,
      "name": "shutdown_security_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void shutdown_security_notify(void * data)
```

```json
{
  "name": "shutdown_security_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587306585,
      "name": "shutdown_security_notify",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:515",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587305408,
      "name": "shutdown_security_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void shutdown_security_notify(void * data)
```

```json
{
  "name": "shutdown_security_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587368521,
      "name": "shutdown_security_notify",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:645",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587366528,
      "name": "shutdown_security_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void shutdown_security_notify(void * data)
```

```json
{
  "name": "shutdown_security_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587250505,
      "name": "shutdown_security_notify",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:645",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587248480,
      "name": "shutdown_security_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void shutdown_security_notify(void * data)
```

```json
{
  "name": "shutdown_security_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587817497,
      "name": "shutdown_security_notify",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:663",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587816176,
      "name": "shutdown_security_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void shutdown_security_notify(void * data)
```

```json
{
  "name": "shutdown_security_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589166731,
      "name": "shutdown_security_notify",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:644",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589165440,
      "name": "shutdown_security_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void shutdown_security_notify(void * data)
```

```json
{
  "name": "shutdown_security_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590718747,
      "name": "shutdown_security_notify",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:654",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590717392,
      "name": "shutdown_security_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void shutdown_security_notify(void * data)
```

```json
{
  "name": "shutdown_security_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591059920,
      "name": "shutdown_security_notify",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:654",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591058576,
      "name": "shutdown_security_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void shutdown_security_notify(void * data)
```

```json
{
  "name": "shutdown_security_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591404624,
      "name": "shutdown_security_notify",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:656",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591403280,
      "name": "shutdown_security_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void shutdown_security_notify(void * data)
```

```json
{
  "name": "shutdown_security_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499409888,
      "name": "shutdown_security_notify",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:508",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499409888,
      "name": "shutdown_security_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void shutdown_security_notify(void * data)
```

```json
{
  "name": "shutdown_security_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292652048,
      "name": "shutdown_security_notify",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:508",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292652048,
      "name": "shutdown_security_notify",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void shutdown_security_notify(void * data)
```

```json
{
  "name": "shutdown_security_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276639124,
      "name": "shutdown_security_notify",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:508",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276639124,
      "name": "shutdown_security_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void shutdown_security_notify(void * data)
```

```json
{
  "name": "shutdown_security_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586214800,
      "name": "shutdown_security_notify",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:508",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586214800,
      "name": "shutdown_security_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void shutdown_security_notify(void * data)
```

```json
{
  "name": "shutdown_security_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586033168,
      "name": "shutdown_security_notify",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:508",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586033168,
      "name": "shutdown_security_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void shutdown_security_notify(void * data)
```

```json
{
  "name": "shutdown_security_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586472288,
      "name": "shutdown_security_notify",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:508",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586472288,
      "name": "shutdown_security_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void shutdown_security_notify(void * data)
```

```json
{
  "name": "shutdown_security_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586583968,
      "name": "shutdown_security_notify",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:508",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586583968,
      "name": "shutdown_security_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void shutdown_security_notify(void * data)
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
void shutdown_security_notify(void * data)
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
