# Function: <code>padata_free_pd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580458957,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:449",
      "file": "kernel/padata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_sysfs_release"
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
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580535019,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:449",
      "file": "kernel/padata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_replace"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data * pd)
```

```json
{
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580597168,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:446",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580597168,
      "name": "padata_free_pd",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data * pd)
```

```json
{
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580626960,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:442",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580626960,
      "name": "padata_free_pd",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data * pd)
```

```json
{
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580707936,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:507",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580707936,
      "name": "padata_free_pd",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data * pd)
```

```json
{
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580839888,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:508",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580839888,
      "name": "padata_free_pd",
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
void padata_free_pd(struct parallel_data * pd)
```

```json
{
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580908544,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:508",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580908544,
      "name": "padata_free_pd",
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
void padata_free_pd(struct parallel_data * pd)
```

```json
{
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581006448,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:520",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006448,
      "name": "padata_free_pd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void padata_free_pd(struct parallel_data * pd)
```

```json
{
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581061360,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:476",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_free_shell",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_serial_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581061360,
      "name": "padata_free_pd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581244286,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:640",
      "file": "kernel/padata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_serial_worker"
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
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581285850,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:615",
      "file": "kernel/padata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_serial_worker"
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
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581303914,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:615",
      "file": "kernel/padata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_serial_worker"
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
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581548659,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:602",
      "file": "kernel/padata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_serial_worker"
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
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581900967,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:602",
      "file": "kernel/padata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_serial_worker"
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
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582334823,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:615",
      "file": "kernel/padata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_serial_worker"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582536039,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:615",
      "file": "kernel/padata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_serial_worker"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582704855,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:615",
      "file": "kernel/padata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_serial_worker"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data * pd)
```

```json
{
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492420280,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:476",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_free_shell",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_serial_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492420280,
      "name": "padata_free_pd",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data * pd)
```

```json
{
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226303868,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:476",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_free_shell",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_serial_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226303868,
      "name": "padata_free_pd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void padata_free_pd(struct parallel_data * pd)
```

```json
{
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285689440,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:476",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_free_shell",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_serial_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285689440,
      "name": "padata_free_pd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void padata_free_pd(struct parallel_data * pd)
```

```json
{
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272507694,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:476",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_free_shell",
        "kernel/padata.c:padata_set_cpumask",
        "kernel/padata.c:padata_serial_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272507694,
      "name": "padata_free_pd",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void padata_free_pd(struct parallel_data * pd)
```

```json
{
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581030208,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:476",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_free_shell",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_serial_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030208,
      "name": "padata_free_pd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void padata_free_pd(struct parallel_data * pd)
```

```json
{
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976288,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:476",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_free_shell",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_serial_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976288,
      "name": "padata_free_pd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void padata_free_pd(struct parallel_data * pd)
```

```json
{
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581021408,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:476",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_free_shell",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_serial_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021408,
      "name": "padata_free_pd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void padata_free_pd(struct parallel_data * pd)
```

```json
{
  "name": "padata_free_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581083648,
      "name": "padata_free_pd",
      "external": false,
      "loc": "kernel/padata.c:476",
      "file": "kernel/padata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_free_shell",
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_serial_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581083648,
      "name": "padata_free_pd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void padata_free_pd(struct parallel_data * pd)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
void padata_free_pd(struct parallel_data * pd)
```
</details>
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
