# Function: <code>apply_constraints</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int apply_constraints(struct icc_path * path)
```

```json
{
  "name": "apply_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589181648,
      "name": "apply_constraints",
      "external": false,
      "loc": "drivers/interconnect/core.c:275",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/interconnect/core.c:icc_set_bw",
        "drivers/interconnect/core.c:icc_set_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589181648,
      "name": "apply_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int apply_constraints(struct icc_path * path)
```

```json
{
  "name": "apply_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589179088,
      "name": "apply_constraints",
      "external": false,
      "loc": "drivers/interconnect/core.c:283",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/interconnect/core.c:icc_set_bw",
        "drivers/interconnect/core.c:icc_set_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589179088,
      "name": "apply_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int apply_constraints(struct icc_path * path)
```

```json
{
  "name": "apply_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589073280,
      "name": "apply_constraints",
      "external": false,
      "loc": "drivers/interconnect/core.c:283",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/interconnect/core.c:icc_set_bw",
        "drivers/interconnect/core.c:icc_set_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589073280,
      "name": "apply_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int apply_constraints(struct icc_path * path)
```

```json
{
  "name": "apply_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_constraints",
      "external": false,
      "loc": "drivers/interconnect/core.c:283",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/interconnect/core.c:icc_set_bw",
        "drivers/interconnect/core.c:icc_set_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589793488,
      "name": "apply_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071592691756,
      "name": "apply_constraints.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int apply_constraints(struct icc_path * path)
```

```json
{
  "name": "apply_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_constraints",
      "external": false,
      "loc": "drivers/interconnect/core.c:283",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/interconnect/core.c:icc_set_bw",
        "drivers/interconnect/core.c:icc_set_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591306656,
      "name": "apply_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071594577026,
      "name": "apply_constraints.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int apply_constraints(struct icc_path * path)
```

```json
{
  "name": "apply_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_constraints",
      "external": false,
      "loc": "drivers/interconnect/core.c:283",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/interconnect/core.c:icc_set_bw",
        "drivers/interconnect/core.c:icc_set_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593058448,
      "name": "apply_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071596321317,
      "name": "apply_constraints.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int apply_constraints(struct icc_path * path)
```

```json
{
  "name": "apply_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_constraints",
      "external": false,
      "loc": "drivers/interconnect/core.c:282",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/interconnect/core.c:icc_set_bw",
        "drivers/interconnect/core.c:icc_set_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593511280,
      "name": "apply_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071596851041,
      "name": "apply_constraints.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int apply_constraints(struct icc_path * path)
```

```json
{
  "name": "apply_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_constraints",
      "external": false,
      "loc": "drivers/interconnect/core.c:298",
      "file": "drivers/interconnect/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/interconnect/core.c:icc_set_bw",
        "drivers/interconnect/core.c:icc_set_bw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594259392,
      "name": "apply_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071597775891,
      "name": "apply_constraints.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int apply_constraints(struct icc_path * path)
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
