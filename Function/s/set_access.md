# Function: <code>set_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582605541,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:245",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
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
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582850628,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:245",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
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
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582946657,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:245",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void set_access(char * acc, short int access)
```

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582994160,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:245",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582994160,
      "name": "set_access",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void set_access(char * acc, short int access)
```

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583158448,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:237",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583158448,
      "name": "set_access",
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
void set_access(char * acc, short int access)
```

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583363952,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:237",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583363952,
      "name": "set_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void set_access(char * acc, short int access)
```

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583482704,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:237",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583482704,
      "name": "set_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void set_access(char * acc, short int access)
```

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583668784,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:236",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583668784,
      "name": "set_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void set_access(char * acc, short int access)
```

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583775792,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:236",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583775792,
      "name": "set_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584168911,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:238",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584288031,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:238",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
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
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584313119,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:238",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
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
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584700047,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:238",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
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
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585364225,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:239",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
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
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586114603,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:250",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void set_access(char * acc, short int access)
```

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586349712,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:250",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586349712,
      "name": "set_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void set_access(char * acc, short int access)
```

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586616768,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:250",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586616768,
      "name": "set_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void set_access(char * acc, short int access)
```

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495577728,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:236",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495577728,
      "name": "set_access",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void set_access(char * acc, short int access)
```

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228939708,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:236",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228939708,
      "name": "set_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void set_access(char * acc, short int access)
```

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289674544,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:236",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289674544,
      "name": "set_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274746778,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:236",
      "file": "security/device_cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
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
void set_access(char * acc, short int access)
```

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583744528,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:236",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583744528,
      "name": "set_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void set_access(char * acc, short int access)
```

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583681584,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:236",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681584,
      "name": "set_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void set_access(char * acc, short int access)
```

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583728304,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:236",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728304,
      "name": "set_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void set_access(char * acc, short int access)
```

```json
{
  "name": "set_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583828960,
      "name": "set_access",
      "external": false,
      "loc": "security/device_cgroup.c:236",
      "file": "security/device_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/device_cgroup.c:devcgroup_seq_show",
        "security/device_cgroup.c:devcgroup_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583828960,
      "name": "set_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void set_access(char * acc, short int access)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void set_access(char * acc, short int access)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void set_access(char * acc, short int access)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void set_access(char * acc, short int access)
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
