# Function: <code>acpi_os_ioremap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587343768,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:9",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_write_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544533,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:9",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583860644,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:9",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583865568,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:9",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595513071,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:9",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583999720,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:9",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584004644,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:9",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584242444,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:9",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595768983,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:9",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584048384,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:9",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584054627,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:9",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584319509,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:9",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596698926,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:9",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584312496,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584321811,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584719049,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603029635,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584532681,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584542510,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584946630,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603202308,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584630009,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584639726,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585050598,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605012735,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584829691,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584839586,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585254788,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605125700,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584965419,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584975314,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585392689,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605165916,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585660971,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585671363,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586101680,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609435112,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:pcc_parse_subspace_irq"
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585786631,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591431247,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586222095,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612509684,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:pcc_parse_subspace_irq"
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585667001,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591372408,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586096686,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614652061,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586146473,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592406957,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586595013,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615611100,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587378940,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594272548,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587508358,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/acpi_pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587856466,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591209246,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:pcc_chan_reg_init"
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588628828,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588641424,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588782693,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/acpi_pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589200701,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592951801,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:pcc_chan_reg_init"
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588916572,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588929360,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589072117,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/acpi_pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589495003,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593402393,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:pcc_chan_reg_init"
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589212636,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589225920,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589377814,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/acpi_pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589802665,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594147817,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:pcc_chan_reg_init"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void * acpi_os_ioremap(acpi_physical_address phys, acpi_size size)
```

```json
{
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497380680,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "arch/arm64/include/asm/acpi.h:49",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497665784,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "arch/arm64/include/asm/acpi.h:49",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501673608,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "arch/arm64/include/asm/acpi.h:49",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501673608,
      "name": "acpi_os_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584915595,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584922882,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585178209,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605055589,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584821515,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584828754,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585119905,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605021546,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584917003,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584926898,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585343089,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605142263,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
  "name": "acpi_os_ioremap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585023133,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_write_memory",
        "drivers/acpi/osl.c:acpi_os_read_memory",
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585033042,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/nvs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nvs.c:suspend_nvs_save"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585450401,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605170110,
      "name": "acpi_os_ioremap",
      "external": false,
      "loc": "include/acpi/acpi_io.h:10",
      "file": "drivers/mailbox/pcc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:acpi_pcc_probe",
        "drivers/mailbox/pcc.c:acpi_pcc_probe"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void * acpi_os_ioremap(acpi_physical_address phys, acpi_size size)
```
</details>
</li>
</ul>
