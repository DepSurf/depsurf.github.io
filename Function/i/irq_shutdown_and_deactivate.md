# Function: <code>irq_shutdown_and_deactivate</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```

```json
{
  "name": "irq_shutdown_and_deactivate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579954912,
      "name": "irq_shutdown_and_deactivate",
      "external": true,
      "loc": "kernel/irq/chip.c:320",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__cleanup_nmi",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579954912,
      "name": "irq_shutdown_and_deactivate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```

```json
{
  "name": "irq_shutdown_and_deactivate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580004768,
      "name": "irq_shutdown_and_deactivate",
      "external": true,
      "loc": "kernel/irq/chip.c:320",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__cleanup_nmi",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580004768,
      "name": "irq_shutdown_and_deactivate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```

```json
{
  "name": "irq_shutdown_and_deactivate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054352,
      "name": "irq_shutdown_and_deactivate",
      "external": true,
      "loc": "kernel/irq/chip.c:320",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__cleanup_nmi",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054352,
      "name": "irq_shutdown_and_deactivate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```

```json
{
  "name": "irq_shutdown_and_deactivate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580036944,
      "name": "irq_shutdown_and_deactivate",
      "external": true,
      "loc": "kernel/irq/chip.c:320",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__cleanup_nmi",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036944,
      "name": "irq_shutdown_and_deactivate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```

```json
{
  "name": "irq_shutdown_and_deactivate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580037712,
      "name": "irq_shutdown_and_deactivate",
      "external": true,
      "loc": "kernel/irq/chip.c:323",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__cleanup_nmi",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037712,
      "name": "irq_shutdown_and_deactivate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```

```json
{
  "name": "irq_shutdown_and_deactivate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170272,
      "name": "irq_shutdown_and_deactivate",
      "external": true,
      "loc": "kernel/irq/chip.c:323",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__cleanup_nmi",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170272,
      "name": "irq_shutdown_and_deactivate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```

```json
{
  "name": "irq_shutdown_and_deactivate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580317152,
      "name": "irq_shutdown_and_deactivate",
      "external": true,
      "loc": "kernel/irq/chip.c:320",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__cleanup_nmi",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580317152,
      "name": "irq_shutdown_and_deactivate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```

```json
{
  "name": "irq_shutdown_and_deactivate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580531072,
      "name": "irq_shutdown_and_deactivate",
      "external": true,
      "loc": "kernel/irq/chip.c:322",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__cleanup_nmi",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580531072,
      "name": "irq_shutdown_and_deactivate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```

```json
{
  "name": "irq_shutdown_and_deactivate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580604256,
      "name": "irq_shutdown_and_deactivate",
      "external": true,
      "loc": "kernel/irq/chip.c:323",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__cleanup_nmi",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580604256,
      "name": "irq_shutdown_and_deactivate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```

```json
{
  "name": "irq_shutdown_and_deactivate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580668768,
      "name": "irq_shutdown_and_deactivate",
      "external": true,
      "loc": "kernel/irq/chip.c:323",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__cleanup_nmi",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580668768,
      "name": "irq_shutdown_and_deactivate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```

```json
{
  "name": "irq_shutdown_and_deactivate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491200736,
      "name": "irq_shutdown_and_deactivate",
      "external": true,
      "loc": "kernel/irq/chip.c:320",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__cleanup_nmi",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491200736,
      "name": "irq_shutdown_and_deactivate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```

```json
{
  "name": "irq_shutdown_and_deactivate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225219800,
      "name": "irq_shutdown_and_deactivate",
      "external": true,
      "loc": "kernel/irq/chip.c:320",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__cleanup_nmi",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225219800,
      "name": "irq_shutdown_and_deactivate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```

```json
{
  "name": "irq_shutdown_and_deactivate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284103600,
      "name": "irq_shutdown_and_deactivate",
      "external": true,
      "loc": "kernel/irq/chip.c:320",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__cleanup_nmi",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284103600,
      "name": "irq_shutdown_and_deactivate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```

```json
{
  "name": "irq_shutdown_and_deactivate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271742648,
      "name": "irq_shutdown_and_deactivate",
      "external": true,
      "loc": "kernel/irq/chip.c:320",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__cleanup_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271742648,
      "name": "irq_shutdown_and_deactivate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```

```json
{
  "name": "irq_shutdown_and_deactivate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579973504,
      "name": "irq_shutdown_and_deactivate",
      "external": true,
      "loc": "kernel/irq/chip.c:320",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__cleanup_nmi",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973504,
      "name": "irq_shutdown_and_deactivate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```

```json
{
  "name": "irq_shutdown_and_deactivate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579911312,
      "name": "irq_shutdown_and_deactivate",
      "external": true,
      "loc": "kernel/irq/chip.c:320",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__cleanup_nmi",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911312,
      "name": "irq_shutdown_and_deactivate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```

```json
{
  "name": "irq_shutdown_and_deactivate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579965040,
      "name": "irq_shutdown_and_deactivate",
      "external": true,
      "loc": "kernel/irq/chip.c:320",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__cleanup_nmi",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965040,
      "name": "irq_shutdown_and_deactivate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```

```json
{
  "name": "irq_shutdown_and_deactivate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580011568,
      "name": "irq_shutdown_and_deactivate",
      "external": true,
      "loc": "kernel/irq/chip.c:320",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__cleanup_nmi",
        "kernel/irq/autoprobe.c:probe_irq_off",
        "kernel/irq/autoprobe.c:probe_irq_mask",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011568,
      "name": "irq_shutdown_and_deactivate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void irq_shutdown_and_deactivate(struct irq_desc * desc)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
