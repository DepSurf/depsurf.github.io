# Function: <code>iommu_completion_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int iommu_completion_wait(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584275504,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:897",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584275504,
      "name": "iommu_completion_wait",
      "section": ".text",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int iommu_completion_wait(struct amd_iommu * iommu)
```

```json
{
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584618368,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:993",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:__queue_flush",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618368,
      "name": "iommu_completion_wait",
      "section": ".text",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584809100,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1072",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584804384,
      "name": "iommu_completion_wait.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584899893,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1131",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584893632,
      "name": "iommu_completion_wait.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585320453,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1072",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:get_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585315104,
      "name": "iommu_completion_wait.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585557379,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1078",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585555856,
      "name": "iommu_completion_wait.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585681923,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1093",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585680992,
      "name": "iommu_completion_wait.part.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585908520,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1081",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585907568,
      "name": "iommu_completion_wait.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
    },
    {
      "addr": 18446744071585927681,
      "name": "iommu_completion_wait.part.0.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586051720,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1088",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586050768,
      "name": "iommu_completion_wait.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586813749,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1032",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:domain_flush_complete",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:domain_flush_complete",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586797904,
      "name": "iommu_completion_wait.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586869781,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1123",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:domain_flush_complete",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:domain_flush_complete",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586856656,
      "name": "iommu_completion_wait.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586742995,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1055",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_flush_complete",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_flush_complete",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586735968,
      "name": "iommu_completion_wait.part.0.isra.0",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587298231,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1067",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_flush_complete",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_flush_complete",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587289136,
      "name": "iommu_completion_wait.part.0.isra.0",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1089",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_update",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/amd/iommu.c:do_detach",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588602224,
      "name": "iommu_completion_wait.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
    },
    {
      "addr": 18446744071594337769,
      "name": "iommu_completion_wait.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1158",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd/iommu.c:free_irte",
        "drivers/iommu/amd/iommu.c:modify_irte_ga",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_update",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/amd/iommu.c:do_detach",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590062384,
      "name": "iommu_completion_wait.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    },
    {
      "addr": 18446744071596240216,
      "name": "iommu_completion_wait.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1175",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_update",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/amd/iommu.c:do_detach",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590379328,
      "name": "iommu_completion_wait.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071596768395,
      "name": "iommu_completion_wait.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1264",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:alloc_irq_table",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches",
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590719904,
      "name": "iommu_completion_wait.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071597676946,
      "name": "iommu_completion_wait.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585812696,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1088",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585811744,
      "name": "iommu_completion_wait.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585671880,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1088",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585670928,
      "name": "iommu_completion_wait.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586001736,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1088",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586000784,
      "name": "iommu_completion_wait.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
  "name": "iommu_completion_wait",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586110024,
      "name": "iommu_completion_wait",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1088",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_update_ga",
        "drivers/iommu/amd_iommu.c:free_irte",
        "drivers/iommu/amd_iommu.c:modify_irte",
        "drivers/iommu/amd_iommu.c:modify_irte_ga",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:alloc_irq_table",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:set_dte_entry",
        "drivers/iommu/amd_iommu.c:domain_flush_complete",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches",
        "drivers/iommu/amd_iommu.c:iommu_flush_all_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586108976,
      "name": "iommu_completion_wait.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int iommu_completion_wait(struct amd_iommu * iommu)
```
</details>
</li>
</ul>
