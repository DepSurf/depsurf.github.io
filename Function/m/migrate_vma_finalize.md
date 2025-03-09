# Function: <code>migrate_vma_finalize</code>

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
  "name": "migrate_vma_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581255748,
      "name": "migrate_vma_finalize",
      "external": false,
      "loc": "mm/migrate.c:2833",
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
  "name": "migrate_vma_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581402045,
      "name": "migrate_vma_finalize",
      "external": false,
      "loc": "mm/migrate.c:2846",
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
  "name": "migrate_vma_finalize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581485681,
      "name": "migrate_vma_finalize",
      "external": false,
      "loc": "mm/migrate.c:2824",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void migrate_vma_finalize(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_finalize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581664400,
      "name": "migrate_vma_finalize",
      "external": true,
      "loc": "mm/migrate.c:2929",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664400,
      "name": "migrate_vma_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
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
void migrate_vma_finalize(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_finalize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581872928,
      "name": "migrate_vma_finalize",
      "external": true,
      "loc": "mm/migrate.c:2950",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581872928,
      "name": "migrate_vma_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 763
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
void migrate_vma_finalize(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_finalize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581919136,
      "name": "migrate_vma_finalize",
      "external": true,
      "loc": "mm/migrate.c:3117",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581919136,
      "name": "migrate_vma_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 749
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
void migrate_vma_finalize(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_finalize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581944112,
      "name": "migrate_vma_finalize",
      "external": true,
      "loc": "mm/migrate.c:3087",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581944112,
      "name": "migrate_vma_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 741
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
void migrate_vma_finalize(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_finalize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582249168,
      "name": "migrate_vma_finalize",
      "external": true,
      "loc": "mm/migrate.c:3024",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582249168,
      "name": "migrate_vma_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
void migrate_vma_finalize(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_finalize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582737184,
      "name": "migrate_vma_finalize",
      "external": true,
      "loc": "mm/migrate_device.c:747",
      "file": "mm/migrate_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582737184,
      "name": "migrate_vma_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1034
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
void migrate_vma_finalize(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_finalize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583268768,
      "name": "migrate_vma_finalize",
      "external": true,
      "loc": "mm/migrate_device.c:884",
      "file": "mm/migrate_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268768,
      "name": "migrate_vma_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void migrate_vma_finalize(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_finalize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583489136,
      "name": "migrate_vma_finalize",
      "external": true,
      "loc": "mm/migrate_device.c:865",
      "file": "mm/migrate_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583489136,
      "name": "migrate_vma_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void migrate_vma_finalize(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_finalize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583682592,
      "name": "migrate_vma_finalize",
      "external": true,
      "loc": "mm/migrate_device.c:873",
      "file": "mm/migrate_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583682592,
      "name": "migrate_vma_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void migrate_vma_finalize(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_finalize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286581104,
      "name": "migrate_vma_finalize",
      "external": true,
      "loc": "mm/migrate.c:2929",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286581104,
      "name": "migrate_vma_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 984
    }
  ]
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void migrate_vma_finalize(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_finalize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581633136,
      "name": "migrate_vma_finalize",
      "external": true,
      "loc": "mm/migrate.c:2929",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581633136,
      "name": "migrate_vma_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
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
void migrate_vma_finalize(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_finalize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581574192,
      "name": "migrate_vma_finalize",
      "external": true,
      "loc": "mm/migrate.c:2929",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581574192,
      "name": "migrate_vma_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
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
void migrate_vma_finalize(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_finalize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581624448,
      "name": "migrate_vma_finalize",
      "external": true,
      "loc": "mm/migrate.c:2929",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581624448,
      "name": "migrate_vma_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
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
void migrate_vma_finalize(struct migrate_vma * migrate)
```

```json
{
  "name": "migrate_vma_finalize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581690800,
      "name": "migrate_vma_finalize",
      "external": true,
      "loc": "mm/migrate.c:2929",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581690800,
      "name": "migrate_vma_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
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
void migrate_vma_finalize(struct migrate_vma * migrate)
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
void migrate_vma_finalize(struct migrate_vma * migrate)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void migrate_vma_finalize(struct migrate_vma * migrate)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void migrate_vma_finalize(struct migrate_vma * migrate)
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
