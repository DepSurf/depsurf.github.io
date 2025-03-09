# Function: <code>map_high</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void map_high(char * id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type)
```

```json
{
  "name": "map_high",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604775151,
      "name": "map_high",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:734",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604775151,
      "name": "map_high",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 128
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
void map_high(char * id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type)
```

```json
{
  "name": "map_high",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609123826,
      "name": "map_high",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:768",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609123826,
      "name": "map_high",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 128
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
void map_high(char * id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type)
```

```json
{
  "name": "map_high",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612189507,
      "name": "map_high",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:913",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612189507,
      "name": "map_high",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 138
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
void map_high(char * id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type)
```

```json
{
  "name": "map_high",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614330307,
      "name": "map_high",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:909",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614330307,
      "name": "map_high",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 138
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
void map_high(char * id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type)
```

```json
{
  "name": "map_high",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615259601,
      "name": "map_high",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:909",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615259601,
      "name": "map_high",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 235
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
void map_high(char * id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type)
```

```json
{
  "name": "map_high",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617036279,
      "name": "map_high",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:915",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617036279,
      "name": "map_high",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 259
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
void map_high(char * id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type)
```

```json
{
  "name": "map_high",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627672528,
      "name": "map_high",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:915",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627672528,
      "name": "map_high",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 331
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
void map_high(char * id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type)
```

```json
{
  "name": "map_high",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619429792,
      "name": "map_high",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:916",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619429792,
      "name": "map_high",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 335
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
void map_high(char * id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type)
```

```json
{
  "name": "map_high",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621725920,
      "name": "map_high",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:877",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621725920,
      "name": "map_high",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 335
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void map_high(char * id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type)
```

```json
{
  "name": "map_high",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604779292,
      "name": "map_high",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:734",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604779292,
      "name": "map_high",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 128
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void map_high(char * id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type)
```
</details>
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
void map_high(char * id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void map_high(char * id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void map_high(char * id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void map_high(char * id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void map_high(char * id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void map_high(char * id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
void map_high(char * id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
