# Function: <code>iommu_queue_command_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int iommu_queue_command_sync(struct amd_iommu * iommu, struct iommu_cmd * cmd, bool sync)
```

```json
{
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584274816,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:847",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:iommu_flush_dte",
        "drivers/iommu/amd_iommu.c:iommu_flush_irt",
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:iommu_completion_wait",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584274816,
      "name": "iommu_queue_command_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int iommu_queue_command_sync(struct amd_iommu * iommu, struct iommu_cmd * cmd, bool sync)
```

```json
{
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584617696,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:943",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_irt",
        "drivers/iommu/amd_iommu.c:iommu_flush_dte",
        "drivers/iommu/amd_iommu.c:iommu_completion_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584617696,
      "name": "iommu_queue_command_sync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584805312,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1049",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_irt",
        "drivers/iommu/amd_iommu.c:iommu_flush_dte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584805312,
      "name": "iommu_queue_command_sync.constprop.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584894848,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1108",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584894848,
      "name": "iommu_queue_command_sync.constprop.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585316048,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1049",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585316048,
      "name": "iommu_queue_command_sync.constprop.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585557104,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1055",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:set_remap_table_entry",
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585557104,
      "name": "iommu_queue_command_sync.constprop.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585681648,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1070",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:set_remap_table_entry",
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585681648,
      "name": "iommu_queue_command_sync.constprop.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585908224,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1058",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:set_remap_table_entry",
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585908224,
      "name": "iommu_queue_command_sync.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586051424,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1065",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586051424,
      "name": "iommu_queue_command_sync.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586813713,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1009",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry",
        "drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:__domain_flush_pages",
        "drivers/iommu/amd/iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
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
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586869745,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1100",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry",
        "drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:__domain_flush_pages",
        "drivers/iommu/amd/iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
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
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586742958,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1032",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry",
        "drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:__domain_flush_pages",
        "drivers/iommu/amd/iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
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
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587298194,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1044",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry",
        "drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
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
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588614489,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1066",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry",
        "drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
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
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590077125,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1135",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:set_remap_table_entry",
        "drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd/iommu.c:device_flush_iotlb",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
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
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590383266,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1152",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:device_flush_iotlb",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_dte"
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
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590739238,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1241",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:__domain_flush_pages",
        "drivers/iommu/amd/iommu.c:__domain_flush_pages",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_dte"
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
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585812400,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1065",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585812400,
      "name": "iommu_queue_command_sync.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585671584,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1065",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585671584,
      "name": "iommu_queue_command_sync.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586001440,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1065",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586001440,
      "name": "iommu_queue_command_sync.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_queue_command_sync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586109728,
      "name": "iommu_queue_command_sync",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1065",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:__domain_flush_pages",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte",
        "drivers/iommu/amd_iommu.c:device_flush_dte_alias",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586109728,
      "name": "iommu_queue_command_sync.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int iommu_queue_command_sync(struct amd_iommu * iommu, struct iommu_cmd * cmd, bool sync)
```
</details>
</li>
</ul>
