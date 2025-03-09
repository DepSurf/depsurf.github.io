# Function: <code>emulate_umip_insn</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emulate_umip_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579292066,
      "name": "emulate_umip_insn",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:204",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
  "name": "emulate_umip_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579304159,
      "name": "emulate_umip_insn",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:204",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
  "name": "emulate_umip_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579328575,
      "name": "emulate_umip_insn",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:204",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emulate_umip_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579343950,
      "name": "emulate_umip_insn",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:204",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emulate_umip_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579348128,
      "name": "emulate_umip_insn",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:204",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emulate_umip_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579377840,
      "name": "emulate_umip_insn",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:204",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int emulate_umip_insn(struct insn * insn, int umip_inst, unsigned char * data, int * data_size, bool x86_64)
```

```json
{
  "name": "emulate_umip_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "emulate_umip_insn",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:205",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579375968,
      "name": "emulate_umip_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 681
    },
    {
      "addr": 18446744071591265107,
      "name": "emulate_umip_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int emulate_umip_insn(struct insn * insn, int umip_inst, unsigned char * data, int * data_size, bool x86_64)
```

```json
{
  "name": "emulate_umip_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "emulate_umip_insn",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:205",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379584,
      "name": "emulate_umip_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
    },
    {
      "addr": 18446744071591207312,
      "name": "emulate_umip_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int emulate_umip_insn(struct insn * insn, int umip_inst, unsigned char * data, int * data_size, bool x86_64)
```

```json
{
  "name": "emulate_umip_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "emulate_umip_insn",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:205",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441216,
      "name": "emulate_umip_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
    },
    {
      "addr": 18446744071592080631,
      "name": "emulate_umip_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int emulate_umip_insn(struct insn * insn, int umip_inst, unsigned char * data, int * data_size, bool x86_64)
```

```json
{
  "name": "emulate_umip_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "emulate_umip_insn",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:205",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579511328,
      "name": "emulate_umip_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 691
    },
    {
      "addr": 18446744071593847970,
      "name": "emulate_umip_insn.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int emulate_umip_insn(struct insn * insn, int umip_inst, unsigned char * data, int * data_size, bool x86_64)
```

```json
{
  "name": "emulate_umip_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579610336,
      "name": "emulate_umip_insn",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:205",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579610336,
      "name": "emulate_umip_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 698
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
int emulate_umip_insn(struct insn * insn, int umip_inst, unsigned char * data, int * data_size, bool x86_64)
```

```json
{
  "name": "emulate_umip_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579622960,
      "name": "emulate_umip_insn",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:205",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622960,
      "name": "emulate_umip_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
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
int emulate_umip_insn(struct insn * insn, int umip_inst, unsigned char * data, int * data_size, bool x86_64)
```

```json
{
  "name": "emulate_umip_insn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579652016,
      "name": "emulate_umip_insn",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:205",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579652016,
      "name": "emulate_umip_insn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emulate_umip_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579344032,
      "name": "emulate_umip_insn",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:204",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emulate_umip_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579276236,
      "name": "emulate_umip_insn",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:204",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emulate_umip_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579343952,
      "name": "emulate_umip_insn",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:204",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emulate_umip_insn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579352400,
      "name": "emulate_umip_insn",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:204",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int emulate_umip_insn(struct insn * insn, int umip_inst, unsigned char * data, int * data_size, bool x86_64)
```
</details>
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
