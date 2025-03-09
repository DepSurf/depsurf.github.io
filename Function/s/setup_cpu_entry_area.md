# Function: <code>setup_cpu_entry_area</code>

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
  "name": "setup_cpu_entry_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602715426,
      "name": "setup_cpu_entry_area",
      "external": false,
      "loc": "arch/x86/mm/cpu_entry_area.c:68",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
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
  "name": "setup_cpu_entry_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602888137,
      "name": "setup_cpu_entry_area",
      "external": false,
      "loc": "arch/x86/mm/cpu_entry_area.c:80",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
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
  "name": "setup_cpu_entry_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604685549,
      "name": "setup_cpu_entry_area",
      "external": false,
      "loc": "arch/x86/mm/cpu_entry_area.c:82",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
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
  "name": "setup_cpu_entry_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604785124,
      "name": "setup_cpu_entry_area",
      "external": false,
      "loc": "arch/x86/mm/cpu_entry_area.c:115",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
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
  "name": "setup_cpu_entry_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604810862,
      "name": "setup_cpu_entry_area",
      "external": false,
      "loc": "arch/x86/mm/cpu_entry_area.c:115",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
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
void setup_cpu_entry_area(unsigned int cpu)
```

```json
{
  "name": "setup_cpu_entry_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609149217,
      "name": "setup_cpu_entry_area",
      "external": false,
      "loc": "arch/x86/mm/cpu_entry_area.c:124",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609149217,
      "name": "setup_cpu_entry_area",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 333
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
void setup_cpu_entry_area(unsigned int cpu)
```

```json
{
  "name": "setup_cpu_entry_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612219526,
      "name": "setup_cpu_entry_area",
      "external": false,
      "loc": "arch/x86/mm/cpu_entry_area.c:125",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612219526,
      "name": "setup_cpu_entry_area",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 302
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
void setup_cpu_entry_area(unsigned int cpu)
```

```json
{
  "name": "setup_cpu_entry_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614360276,
      "name": "setup_cpu_entry_area",
      "external": false,
      "loc": "arch/x86/mm/cpu_entry_area.c:125",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614360276,
      "name": "setup_cpu_entry_area",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 489
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
void setup_cpu_entry_area(unsigned int cpu)
```

```json
{
  "name": "setup_cpu_entry_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615291357,
      "name": "setup_cpu_entry_area",
      "external": false,
      "loc": "arch/x86/mm/cpu_entry_area.c:132",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615291357,
      "name": "setup_cpu_entry_area",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 438
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
void setup_cpu_entry_area(unsigned int cpu)
```

```json
{
  "name": "setup_cpu_entry_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617070767,
      "name": "setup_cpu_entry_area",
      "external": false,
      "loc": "arch/x86/mm/cpu_entry_area.c:132",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617070767,
      "name": "setup_cpu_entry_area",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 452
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_cpu_entry_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627720487,
      "name": "setup_cpu_entry_area",
      "external": false,
      "loc": "arch/x86/mm/cpu_entry_area.c:170",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
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
  "name": "setup_cpu_entry_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619478087,
      "name": "setup_cpu_entry_area",
      "external": false,
      "loc": "arch/x86/mm/cpu_entry_area.c:177",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
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
  "name": "setup_cpu_entry_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621774695,
      "name": "setup_cpu_entry_area",
      "external": false,
      "loc": "arch/x86/mm/cpu_entry_area.c:177",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_cpu_entry_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604724804,
      "name": "setup_cpu_entry_area",
      "external": false,
      "loc": "arch/x86/mm/cpu_entry_area.c:115",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
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
  "name": "setup_cpu_entry_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604692534,
      "name": "setup_cpu_entry_area",
      "external": false,
      "loc": "arch/x86/mm/cpu_entry_area.c:115",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
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
  "name": "setup_cpu_entry_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604802371,
      "name": "setup_cpu_entry_area",
      "external": false,
      "loc": "arch/x86/mm/cpu_entry_area.c:115",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
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
  "name": "setup_cpu_entry_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604814990,
      "name": "setup_cpu_entry_area",
      "external": false,
      "loc": "arch/x86/mm/cpu_entry_area.c:115",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas"
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
void setup_cpu_entry_area(unsigned int cpu)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void setup_cpu_entry_area(unsigned int cpu)
```
</details>
</li>
</ul>
