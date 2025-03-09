# Function: <code>pci_msix_clear_and_set_ctrl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void pci_msix_clear_and_set_ctrl(struct pci_dev * dev, u16 clear, u16 set)
```

```json
{
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583240277,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:164",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583381632,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:164",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583381632,
      "name": "pci_msix_clear_and_set_ctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583550867,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:174",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583701549,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:174",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583687411,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:174",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583839869,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:174",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583728089,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:172",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583878637,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:172",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583986201,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:173",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584142125,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:173",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584180509,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:159",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584358941,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:159",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:__pci_enable_msix",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584269149,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:168",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584457933,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:168",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584460056,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:173",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584654803,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:173",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584595368,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:198",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584792403,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:198",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585267842,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:199",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_msi_setup_pci_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585481549,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:199",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585520173,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/msi.c:448",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585397774,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/msi.c:439",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585861341,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/msi.c:427",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:msix_capability_init",
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587055011,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/msi/msi.c:283",
      "file": "drivers/pci/msi/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:msix_capability_init",
        "drivers/pci/msi/msi.c:msix_capability_init",
        "drivers/pci/msi/msi.c:msix_capability_init",
        "drivers/pci/msi/msi.c:pci_restore_msi_state",
        "drivers/pci/msi/msi.c:pci_restore_msi_state"
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
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588242329,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/msi/msi.c:541",
      "file": "drivers/pci/msi/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:pci_msix_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range"
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
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588517881,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/msi/msi.c:541",
      "file": "drivers/pci/msi/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:pci_msix_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range"
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
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588816473,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/msi/msi.c:543",
      "file": "drivers/pci/msi/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:pci_msix_shutdown",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_restore_msix_state",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range",
        "drivers/pci/msi/msi.c:__pci_enable_msix_range"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496837496,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:198",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497060296,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:198",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230117944,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:198",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3230270312,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:198",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290911664,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:198",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291099712,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:198",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275542990,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:198",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275706114,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:198",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584547528,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:198",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584741155,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:198",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584475688,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:198",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584671923,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:198",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584545528,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:198",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584742563,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:198",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
  "name": "pci_msix_clear_and_set_ctrl",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584653272,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:198",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584850131,
      "name": "pci_msix_clear_and_set_ctrl",
      "external": false,
      "loc": "drivers/pci/pci.h:198",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_restore_msi_state",
        "drivers/pci/msi.c:pci_restore_msi_state"
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void pci_msix_clear_and_set_ctrl(struct pci_dev * dev, u16 clear, u16 set)
```
</details>
</li>
</ul>
