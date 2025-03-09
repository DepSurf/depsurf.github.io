# Function: <code>audit_set_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580038632,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:346",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
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
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580071172,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:344",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
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
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580111313,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:350",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
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
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580116651,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:415",
      "file": "kernel/audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_receive_msg"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580164576,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:415",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580164576,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580224432,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:458",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580224432,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580276816,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:454",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276816,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580327808,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:441",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580327808,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580376608,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:441",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580376608,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580449392,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:443",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580449392,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580437984,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:448",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580437984,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580441712,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:448",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580441712,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:448",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580606544,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071592162546,
      "name": "audit_set_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:449",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580810944,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071593935654,
      "name": "audit_set_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:447",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096976,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071596000679,
      "name": "audit_set_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:447",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188592,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071596519172,
      "name": "audit_set_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:447",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581294784,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071597419563,
      "name": "audit_set_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491642376,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:441",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491642376,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225594448,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:441",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225594448,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284638448,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:441",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284638448,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272037656,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:441",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272037656,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580345408,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:441",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580345408,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580292576,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:441",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580292576,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580336656,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:441",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580336656,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
int audit_set_enabled(u32 state)
```

```json
{
  "name": "audit_set_enabled",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580391888,
      "name": "audit_set_enabled",
      "external": false,
      "loc": "kernel/audit.c:441",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_enable",
        "kernel/audit.c:audit_receive_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580391888,
      "name": "audit_set_enabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
int audit_set_enabled(u32 state)
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
