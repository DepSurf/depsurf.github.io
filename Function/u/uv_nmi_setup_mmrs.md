# Function: <code>uv_nmi_setup_mmrs</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_nmi_setup_mmrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604838652,
      "name": "uv_nmi_setup_mmrs",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:228",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup"
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
void uv_nmi_setup_mmrs()
```

```json
{
  "name": "uv_nmi_setup_mmrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579497862,
      "name": "uv_nmi_setup_mmrs",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:228",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497862,
      "name": "uv_nmi_setup_mmrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
void uv_nmi_setup_mmrs()
```

```json
{
  "name": "uv_nmi_setup_mmrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591274131,
      "name": "uv_nmi_setup_mmrs",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:242",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591274131,
      "name": "uv_nmi_setup_mmrs",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void uv_nmi_setup_mmrs()
```

```json
{
  "name": "uv_nmi_setup_mmrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591217083,
      "name": "uv_nmi_setup_mmrs",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:245",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591217083,
      "name": "uv_nmi_setup_mmrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 823
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
void uv_nmi_setup_mmrs()
```

```json
{
  "name": "uv_nmi_setup_mmrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592094666,
      "name": "uv_nmi_setup_mmrs",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:245",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592094666,
      "name": "uv_nmi_setup_mmrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 886
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
void uv_nmi_setup_mmrs()
```

```json
{
  "name": "uv_nmi_setup_mmrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593862270,
      "name": "uv_nmi_setup_mmrs",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:245",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593862270,
      "name": "uv_nmi_setup_mmrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
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
void uv_nmi_setup_mmrs()
```

```json
{
  "name": "uv_nmi_setup_mmrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_nmi_setup_mmrs",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:245",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579750304,
      "name": "uv_nmi_setup_mmrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
    },
    {
      "addr": 18446744071595972575,
      "name": "uv_nmi_setup_mmrs.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void uv_nmi_setup_mmrs()
```

```json
{
  "name": "uv_nmi_setup_mmrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_nmi_setup_mmrs",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:245",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579796864,
      "name": "uv_nmi_setup_mmrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
    },
    {
      "addr": 18446744071596490202,
      "name": "uv_nmi_setup_mmrs.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void uv_nmi_setup_mmrs()
```

```json
{
  "name": "uv_nmi_setup_mmrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_nmi_setup_mmrs",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:244",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579831696,
      "name": "uv_nmi_setup_mmrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
    },
    {
      "addr": 18446744071597386838,
      "name": "uv_nmi_setup_mmrs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_nmi_setup_mmrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604842809,
      "name": "uv_nmi_setup_mmrs",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_nmi.c:228",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup"
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
void uv_nmi_setup_mmrs()
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
