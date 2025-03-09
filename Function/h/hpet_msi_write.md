# Function: <code>hpet_msi_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void hpet_msi_write(struct hpet_dev * hdev, struct msi_msg * msg)
```

```json
{
  "name": "hpet_msi_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579250368,
      "name": "hpet_msi_write",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:475",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_write_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579250368,
      "name": "hpet_msi_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void hpet_msi_write(struct hpet_dev * hdev, struct msi_msg * msg)
```

```json
{
  "name": "hpet_msi_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579249488,
      "name": "hpet_msi_write",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:475",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_write_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579249488,
      "name": "hpet_msi_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void hpet_msi_write(struct hpet_dev * hdev, struct msi_msg * msg)
```

```json
{
  "name": "hpet_msi_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579262176,
      "name": "hpet_msi_write",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:476",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_write_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262176,
      "name": "hpet_msi_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hpet_msi_write(struct hpet_dev * hdev, struct msi_msg * msg)
```

```json
{
  "name": "hpet_msi_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579255052,
      "name": "hpet_msi_write",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:465",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_msi_resume"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_write_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258288,
      "name": "hpet_msi_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hpet_msi_write(struct hpet_dev * hdev, struct msi_msg * msg)
```

```json
{
  "name": "hpet_msi_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579271820,
      "name": "hpet_msi_write",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:465",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_msi_resume"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_write_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275072,
      "name": "hpet_msi_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hpet_msi_write(struct hpet_dev * hdev, struct msi_msg * msg)
```

```json
{
  "name": "hpet_msi_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579282908,
      "name": "hpet_msi_write",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:466",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_msi_resume"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_write_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579285984,
      "name": "hpet_msi_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hpet_msi_write(struct hpet_dev * hdev, struct msi_msg * msg)
```

```json
{
  "name": "hpet_msi_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579306860,
      "name": "hpet_msi_write",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:462",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_msi_resume"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_write_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579309936,
      "name": "hpet_msi_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hpet_msi_write(struct hpet_channel * hc, struct msi_msg * msg)
```

```json
{
  "name": "hpet_msi_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579323324,
      "name": "hpet_msi_write",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:492",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_write_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579325920,
      "name": "hpet_msi_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void hpet_msi_write(struct hpet_channel * hc, struct msi_msg * msg)
```

```json
{
  "name": "hpet_msi_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579327372,
      "name": "hpet_msi_write",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:492",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_write_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329968,
      "name": "hpet_msi_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void hpet_msi_write(struct hpet_channel * hc, struct msi_msg * msg)
```

```json
{
  "name": "hpet_msi_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579357964,
      "name": "hpet_msi_write",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:492",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_write_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359344,
      "name": "hpet_msi_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hpet_msi_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579357820,
      "name": "hpet_msi_write",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:492",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_write_msg"
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
  "name": "hpet_msi_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579362172,
      "name": "hpet_msi_write",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:492",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_write_msg"
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
  "name": "hpet_msi_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579422396,
      "name": "hpet_msi_write",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:493",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_write_msg"
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
  "name": "hpet_msi_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579491099,
      "name": "hpet_msi_write",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:493",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_write_msg"
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
  "name": "hpet_msi_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579585771,
      "name": "hpet_msi_write",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:493",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_write_msg"
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
  "name": "hpet_msi_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579598267,
      "name": "hpet_msi_write",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:493",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_write_msg"
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
  "name": "hpet_msi_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579628027,
      "name": "hpet_msi_write",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:493",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_write_msg"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void hpet_msi_write(struct hpet_channel * hc, struct msi_msg * msg)
```

```json
{
  "name": "hpet_msi_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579323276,
      "name": "hpet_msi_write",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:492",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_write_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579325872,
      "name": "hpet_msi_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void hpet_msi_write(struct hpet_channel * hc, struct msi_msg * msg)
```

```json
{
  "name": "hpet_msi_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579257788,
      "name": "hpet_msi_write",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:492",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_write_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579260320,
      "name": "hpet_msi_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void hpet_msi_write(struct hpet_channel * hc, struct msi_msg * msg)
```

```json
{
  "name": "hpet_msi_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579323196,
      "name": "hpet_msi_write",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:492",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_write_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579325792,
      "name": "hpet_msi_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void hpet_msi_write(struct hpet_channel * hc, struct msi_msg * msg)
```

```json
{
  "name": "hpet_msi_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579331484,
      "name": "hpet_msi_write",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:492",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/msi.c:hpet_msi_write_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334080,
      "name": "hpet_msi_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct hpet_channel * hc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct hpet_dev * hdev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void hpet_msi_write(struct hpet_channel * hc, struct msi_msg * msg)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void hpet_msi_write(struct hpet_channel * hc, struct msi_msg * msg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void hpet_msi_write(struct hpet_channel * hc, struct msi_msg * msg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void hpet_msi_write(struct hpet_channel * hc, struct msi_msg * msg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void hpet_msi_write(struct hpet_channel * hc, struct msi_msg * msg)
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
