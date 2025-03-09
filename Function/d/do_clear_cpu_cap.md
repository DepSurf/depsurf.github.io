# Function: <code>do_clear_cpu_cap</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "do_clear_cpu_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579115744,
      "name": "do_clear_cpu_cap",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:83",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579115744,
      "name": "do_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "do_clear_cpu_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579123648,
      "name": "do_clear_cpu_cap",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:83",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579123648,
      "name": "do_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "do_clear_cpu_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579130304,
      "name": "do_clear_cpu_cap",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:83",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579130304,
      "name": "do_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "do_clear_cpu_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_clear_cpu_cap",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:92",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140576,
      "name": "do_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071579140868,
      "name": "do_clear_cpu_cap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "do_clear_cpu_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579142800,
      "name": "do_clear_cpu_cap",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:93",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142800,
      "name": "do_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "do_clear_cpu_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579159488,
      "name": "do_clear_cpu_cap",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:93",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579159488,
      "name": "do_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "do_clear_cpu_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579156512,
      "name": "do_clear_cpu_cap",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:96",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156512,
      "name": "do_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "do_clear_cpu_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579163488,
      "name": "do_clear_cpu_cap",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:99",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579163488,
      "name": "do_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "do_clear_cpu_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579194160,
      "name": "do_clear_cpu_cap",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:99",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579194160,
      "name": "do_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "do_clear_cpu_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579243104,
      "name": "do_clear_cpu_cap",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:102",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579243104,
      "name": "do_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "do_clear_cpu_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579302896,
      "name": "do_clear_cpu_cap",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:103",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302896,
      "name": "do_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "do_clear_cpu_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579310064,
      "name": "do_clear_cpu_cap",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:105",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579310064,
      "name": "do_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "do_clear_cpu_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579340816,
      "name": "do_clear_cpu_cap",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:106",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579340816,
      "name": "do_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "do_clear_cpu_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579143168,
      "name": "do_clear_cpu_cap",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:93",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143168,
      "name": "do_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "do_clear_cpu_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579074448,
      "name": "do_clear_cpu_cap",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:93",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579074448,
      "name": "do_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "do_clear_cpu_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579142720,
      "name": "do_clear_cpu_cap",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:93",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142720,
      "name": "do_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```

```json
{
  "name": "do_clear_cpu_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579147856,
      "name": "do_clear_cpu_cap",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cpuid-deps.c:93",
      "file": "arch/x86/kernel/cpu/cpuid-deps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap",
        "arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579147856,
      "name": "do_clear_cpu_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 * c, unsigned int feature)
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
