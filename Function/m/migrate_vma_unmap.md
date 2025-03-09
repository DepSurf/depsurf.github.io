# Function: <code>migrate_vma_unmap</code>

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
  "name": "migrate_vma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581254615,
      "name": "migrate_vma_unmap",
      "external": false,
      "loc": "mm/migrate.c:2557",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma"
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
  "name": "migrate_vma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581400953,
      "name": "migrate_vma_unmap",
      "external": false,
      "loc": "mm/migrate.c:2570",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma"
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
  "name": "migrate_vma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581484588,
      "name": "migrate_vma_unmap",
      "external": false,
      "loc": "mm/migrate.c:2549",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma"
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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "migrate_vma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581663457,
      "name": "migrate_vma_unmap",
      "external": false,
      "loc": "mm/migrate.c:2552",
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
void migrate_vma_unmap(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581871888,
      "name": "migrate_vma_unmap",
      "external": false,
      "loc": "mm/migrate.c:2572",
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
      "addr": 18446744071581871888,
      "name": "migrate_vma_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
void migrate_vma_unmap(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581918032,
      "name": "migrate_vma_unmap",
      "external": false,
      "loc": "mm/migrate.c:2742",
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
      "addr": 18446744071581918032,
      "name": "migrate_vma_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
void migrate_vma_unmap(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581943024,
      "name": "migrate_vma_unmap",
      "external": false,
      "loc": "mm/migrate.c:2705",
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
      "addr": 18446744071581943024,
      "name": "migrate_vma_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
void migrate_vma_unmap(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582248080,
      "name": "migrate_vma_unmap",
      "external": false,
      "loc": "mm/migrate.c:2638",
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
      "addr": 18446744071582248080,
      "name": "migrate_vma_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
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
void migrate_vma_unmap(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582738224,
      "name": "migrate_vma_unmap",
      "external": false,
      "loc": "mm/migrate_device.c:345",
      "file": "mm/migrate_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate_device.c:migrate_vma_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582738224,
      "name": "migrate_vma_unmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1153
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
  "name": "migrate_vma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583270746,
      "name": "migrate_vma_unmap",
      "external": false,
      "loc": "mm/migrate_device.c:450",
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
  "name": "migrate_vma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583491147,
      "name": "migrate_vma_unmap",
      "external": false,
      "loc": "mm/migrate_device.c:444",
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
  "name": "migrate_vma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583690219,
      "name": "migrate_vma_unmap",
      "external": false,
      "loc": "mm/migrate_device.c:447",
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
  "name": "migrate_vma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286579664,
      "name": "migrate_vma_unmap",
      "external": false,
      "loc": "mm/migrate.c:2552",
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
  "name": "migrate_vma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581632193,
      "name": "migrate_vma_unmap",
      "external": false,
      "loc": "mm/migrate.c:2552",
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
  "name": "migrate_vma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581573249,
      "name": "migrate_vma_unmap",
      "external": false,
      "loc": "mm/migrate.c:2552",
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
  "name": "migrate_vma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581623505,
      "name": "migrate_vma_unmap",
      "external": false,
      "loc": "mm/migrate.c:2552",
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
  "name": "migrate_vma_unmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581689836,
      "name": "migrate_vma_unmap",
      "external": false,
      "loc": "mm/migrate.c:2552",
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
void migrate_vma_unmap(struct migrate_vma * migrate)
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
void migrate_vma_unmap(struct migrate_vma * migrate)
```
</details>
</li>
</ul>
