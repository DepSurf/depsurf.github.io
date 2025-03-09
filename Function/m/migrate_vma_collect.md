# Function: <code>migrate_vma_collect</code>

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
  "name": "migrate_vma_collect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581243200,
      "name": "migrate_vma_collect",
      "external": false,
      "loc": "mm/migrate.c:2352",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581243200,
      "name": "migrate_vma_collect.constprop.57",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "migrate_vma_collect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581388688,
      "name": "migrate_vma_collect",
      "external": false,
      "loc": "mm/migrate.c:2365",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581388688,
      "name": "migrate_vma_collect.constprop.64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "migrate_vma_collect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581472608,
      "name": "migrate_vma_collect",
      "external": false,
      "loc": "mm/migrate.c:2345",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581472608,
      "name": "migrate_vma_collect.constprop.60",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "migrate_vma_collect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581662855,
      "name": "migrate_vma_collect",
      "external": false,
      "loc": "mm/migrate.c:2365",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup"
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
void migrate_vma_collect(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_collect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581868480,
      "name": "migrate_vma_collect",
      "external": false,
      "loc": "mm/migrate.c:2385",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868480,
      "name": "migrate_vma_collect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void migrate_vma_collect(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_collect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581914304,
      "name": "migrate_vma_collect",
      "external": false,
      "loc": "mm/migrate.c:2549",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581914304,
      "name": "migrate_vma_collect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "migrate_vma_collect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581946452,
      "name": "migrate_vma_collect",
      "external": false,
      "loc": "mm/migrate.c:2512",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup"
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
  "name": "migrate_vma_collect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582251092,
      "name": "migrate_vma_collect",
      "external": false,
      "loc": "mm/migrate.c:2445",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup"
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
  "name": "migrate_vma_collect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582739649,
      "name": "migrate_vma_collect",
      "external": false,
      "loc": "mm/migrate_device.c:274",
      "file": "mm/migrate_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_setup"
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
  "name": "migrate_vma_collect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583270591,
      "name": "migrate_vma_collect",
      "external": false,
      "loc": "mm/migrate_device.c:299",
      "file": "mm/migrate_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_setup"
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
  "name": "migrate_vma_collect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583490952,
      "name": "migrate_vma_collect",
      "external": false,
      "loc": "mm/migrate_device.c:293",
      "file": "mm/migrate_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_setup"
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
  "name": "migrate_vma_collect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583690024,
      "name": "migrate_vma_collect",
      "external": false,
      "loc": "mm/migrate_device.c:296",
      "file": "mm/migrate_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_setup"
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "migrate_vma_collect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286578740,
      "name": "migrate_vma_collect",
      "external": false,
      "loc": "mm/migrate.c:2365",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup"
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
  "name": "migrate_vma_collect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581631591,
      "name": "migrate_vma_collect",
      "external": false,
      "loc": "mm/migrate.c:2365",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup"
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
  "name": "migrate_vma_collect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581572647,
      "name": "migrate_vma_collect",
      "external": false,
      "loc": "mm/migrate.c:2365",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup"
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
  "name": "migrate_vma_collect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581622903,
      "name": "migrate_vma_collect",
      "external": false,
      "loc": "mm/migrate.c:2365",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup"
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
  "name": "migrate_vma_collect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581689271,
      "name": "migrate_vma_collect",
      "external": false,
      "loc": "mm/migrate.c:2365",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup"
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
void migrate_vma_collect(struct migrate_vma * migrate)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void migrate_vma_collect(struct migrate_vma * migrate)
```
</details>
</li>
</ul>
