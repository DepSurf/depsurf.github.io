# Function: <code>hpet_select_clockevents</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hpet_select_clockevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604764974,
      "name": "hpet_select_clockevents",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:593",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
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
  "name": "hpet_select_clockevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604790828,
      "name": "hpet_select_clockevents",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:593",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
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
void hpet_select_clockevents()
```

```json
{
  "name": "hpet_select_clockevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609132688,
      "name": "hpet_select_clockevents",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:593",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609132688,
      "name": "hpet_select_clockevents",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 273
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
void hpet_select_clockevents()
```

```json
{
  "name": "hpet_select_clockevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612201140,
      "name": "hpet_select_clockevents",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:703",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612201140,
      "name": "hpet_select_clockevents",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 394
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
void hpet_select_clockevents()
```

```json
{
  "name": "hpet_select_clockevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614341822,
      "name": "hpet_select_clockevents",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:703",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614341822,
      "name": "hpet_select_clockevents",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 630
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
void hpet_select_clockevents()
```

```json
{
  "name": "hpet_select_clockevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615271823,
      "name": "hpet_select_clockevents",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:704",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615271823,
      "name": "hpet_select_clockevents",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 674
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
void hpet_select_clockevents()
```

```json
{
  "name": "hpet_select_clockevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617047913,
      "name": "hpet_select_clockevents",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:704",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617047913,
      "name": "hpet_select_clockevents",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 700
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
void hpet_select_clockevents()
```

```json
{
  "name": "hpet_select_clockevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627690816,
      "name": "hpet_select_clockevents",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:704",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627690816,
      "name": "hpet_select_clockevents",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 842
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
void hpet_select_clockevents()
```

```json
{
  "name": "hpet_select_clockevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619448480,
      "name": "hpet_select_clockevents",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:704",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619448480,
      "name": "hpet_select_clockevents",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 849
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
void hpet_select_clockevents()
```

```json
{
  "name": "hpet_select_clockevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621744464,
      "name": "hpet_select_clockevents",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:704",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621744464,
      "name": "hpet_select_clockevents",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 896
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
  "name": "hpet_select_clockevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604704770,
      "name": "hpet_select_clockevents",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:593",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
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
  "name": "hpet_select_clockevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604672174,
      "name": "hpet_select_clockevents",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:593",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
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
  "name": "hpet_select_clockevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604782337,
      "name": "hpet_select_clockevents",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:593",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
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
  "name": "hpet_select_clockevents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604794969,
      "name": "hpet_select_clockevents",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:593",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_late_init"
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
void hpet_select_clockevents()
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
