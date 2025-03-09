# Function: <code>__virt_addr_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579309056,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:45",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:snapshot_write_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579309056,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579308784,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:45",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579308784,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579324016,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:45",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579324016,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579321376,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:45",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579321376,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579344832,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:46",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/events/core.c:perf_prepare_sample"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344832,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579356544,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:46",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_query_variable_info",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_query_variable_info",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_query_variable_info",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/events/core.c:perf_prepare_sample",
        "drivers/spi/spi.c:spi_map_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579356544,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579383696,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:46",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/events/core.c:perf_prepare_sample",
        "drivers/spi/spi.c:spi_map_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383696,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579399168,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:46",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/events/core.c:perf_prepare_sample",
        "drivers/spi/spi.c:spi_map_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399168,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579402480,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:46",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/events/core.c:perf_prepare_sample",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402480,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411856,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:47",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/events/core.c:perf_virt_to_phys",
        "drivers/spi/spi.c:spi_map_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411856,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579412528,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:47",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/events/core.c:perf_virt_to_phys",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/spi/spi.c:spi_map_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579412528,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579415776,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:47",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:create_zone_bm_rtree",
        "kernel/power/snapshot.c:create_zone_bm_rtree",
        "kernel/events/core.c:perf_virt_to_phys",
        "mm/slab_common.c:kmem_dump_obj",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/spi/spi.c:spi_map_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579415776,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:47",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/events/core.c:perf_virt_to_phys",
        "mm/slab_common.c:kmem_dump_obj",
        "drivers/xen/unpopulated-alloc.c:fill_list",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592087931,
      "name": "__virt_addr_valid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579478656,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:47",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/events/core.c:perf_virt_to_phys",
        "mm/slab_common.c:kmem_dump_obj",
        "mm/usercopy.c:check_heap_object",
        "fs/proc/kcore.c:kclist_add_private",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593854842,
      "name": "__virt_addr_valid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579557120,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:47",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/events/core.c:perf_virt_to_phys",
        "mm/slab_common.c:kmem_dump_obj",
        "mm/usercopy.c:check_heap_object",
        "fs/proc/kcore.c:kclist_add_private",
        "drivers/spi/spi.c:spi_map_buf_attrs",
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595969535,
      "name": "__virt_addr_valid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579664192,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:47",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/events/core.c:perf_virt_to_phys",
        "mm/slab_common.c:kmem_dump_obj",
        "mm/usercopy.c:check_heap_object",
        "fs/proc/kcore.c:kclist_add_private",
        "drivers/spi/spi.c:spi_map_buf_attrs",
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596487140,
      "name": "__virt_addr_valid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579678336,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:47",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:arbitrary_virt_to_machine",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/power/snapshot.c:memory_bm_create",
        "kernel/events/core.c:perf_virt_to_phys",
        "mm/slab_common.c:kmem_dump_obj",
        "mm/usercopy.c:check_heap_object",
        "fs/proc/kcore.c:kclist_add_private",
        "drivers/spi/spi.c:spi_map_buf_attrs",
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597383762,
      "name": "__virt_addr_valid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579712736,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579398384,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:46",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/events/core.c:perf_prepare_sample",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579398384,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579327680,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:46",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/events/core.c:perf_prepare_sample",
        "drivers/spi/spi.c:spi_map_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327680,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579398304,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:46",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/events/core.c:perf_prepare_sample",
        "drivers/spi/spi.c:spi_map_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579398304,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
bool __virt_addr_valid(long unsigned int x)
```

```json
{
  "name": "__virt_addr_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579406800,
      "name": "__virt_addr_valid",
      "external": true,
      "loc": "arch/x86/mm/physaddr.c:46",
      "file": "arch/x86/mm/physaddr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_get_time",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:memory_bm_free",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/power/snapshot.c:free_zone_bm_rtree",
        "kernel/events/core.c:perf_prepare_sample",
        "drivers/spi/spi.c:spi_map_buf",
        "drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406800,
      "name": "__virt_addr_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool __virt_addr_valid(long unsigned int x)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool __virt_addr_valid(long unsigned int x)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool __virt_addr_valid(long unsigned int x)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool __virt_addr_valid(long unsigned int x)
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
