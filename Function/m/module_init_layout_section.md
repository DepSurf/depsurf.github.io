# Function: <code>module_init_layout_section</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "module_init_layout_section",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580300776,
      "name": "module_init_layout_section",
      "external": false,
      "loc": "kernel/module.c:2408",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:layout_sections",
        "kernel/module.c:layout_sections"
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
  "name": "module_init_layout_section",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580453718,
      "name": "module_init_layout_section",
      "external": false,
      "loc": "kernel/module.c:2410",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:layout_sections",
        "kernel/module.c:layout_sections"
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
  "name": "module_init_layout_section",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580477837,
      "name": "module_init_layout_section",
      "external": false,
      "loc": "kernel/module/main.c:1403",
      "file": "kernel/module/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/main.c:layout_sections",
        "kernel/module/main.c:layout_sections"
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
  "name": "module_init_layout_section",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580726173,
      "name": "module_init_layout_section",
      "external": false,
      "loc": "kernel/module/main.c:1401",
      "file": "kernel/module/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/main.c:layout_sections",
        "kernel/module/main.c:layout_sections"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool module_init_layout_section(const char * sname)
```

```json
{
  "name": "module_init_layout_section",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580805488,
      "name": "module_init_layout_section",
      "external": true,
      "loc": "kernel/module/main.c:1487",
      "file": "kernel/module/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/main.c:__layout_sections"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580805216,
      "name": "module_init_layout_section",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool module_init_layout_section(const char * sname)
```

```json
{
  "name": "module_init_layout_section",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580894880,
      "name": "module_init_layout_section",
      "external": true,
      "loc": "kernel/module/main.c:1495",
      "file": "kernel/module/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/main.c:__layout_sections"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580894608,
      "name": "module_init_layout_section",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
bool module_init_layout_section(const char * sname)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
