# Function: <code>intel_pt_validate_cap</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```

```json
{
  "name": "intel_pt_validate_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604570542,
      "name": "intel_pt_validate_cap",
      "external": true,
      "loc": "arch/x86/events/intel/pt.c:79",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_reset_markers",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_topa_dump",
        "arch/x86/events/intel/pt.c:topa_insert_table",
        "arch/x86/events/intel/pt.c:pt_cap_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578921744,
      "name": "intel_pt_validate_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```

```json
{
  "name": "intel_pt_validate_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604665145,
      "name": "intel_pt_validate_cap",
      "external": true,
      "loc": "arch/x86/events/intel/pt.c:71",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_reset_markers",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_topa_dump",
        "arch/x86/events/intel/pt.c:topa_insert_table",
        "arch/x86/events/intel/pt.c:pt_cap_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578926768,
      "name": "intel_pt_validate_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```

```json
{
  "name": "intel_pt_validate_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604677643,
      "name": "intel_pt_validate_cap",
      "external": true,
      "loc": "arch/x86/events/intel/pt.c:71",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_reset_markers",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_topa_dump",
        "arch/x86/events/intel/pt.c:topa_insert_table",
        "arch/x86/events/intel/pt.c:pt_cap_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578928736,
      "name": "intel_pt_validate_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```

```json
{
  "name": "intel_pt_validate_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578937166,
      "name": "intel_pt_validate_cap",
      "external": true,
      "loc": "arch/x86/events/intel/pt.c:71",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_addr_filters_init",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_reset_markers",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_topa_dump",
        "arch/x86/events/intel/pt.c:topa_insert_table",
        "arch/x86/events/intel/pt.c:pt_cap_show"
      ],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578934448,
      "name": "intel_pt_validate_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```

```json
{
  "name": "intel_pt_validate_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578938350,
      "name": "intel_pt_validate_cap",
      "external": true,
      "loc": "arch/x86/events/intel/pt.c:71",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_addr_filters_init",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_reset_markers",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_topa_dump",
        "arch/x86/events/intel/pt.c:topa_insert_table",
        "arch/x86/events/intel/pt.c:pt_cap_show"
      ],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578935632,
      "name": "intel_pt_validate_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```

```json
{
  "name": "intel_pt_validate_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578947784,
      "name": "intel_pt_validate_cap",
      "external": true,
      "loc": "arch/x86/events/intel/pt.c:71",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_reset_markers",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_topa_dump",
        "arch/x86/events/intel/pt.c:topa_insert_table",
        "arch/x86/events/intel/pt.c:pt_cap_show"
      ],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578940480,
      "name": "intel_pt_validate_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```

```json
{
  "name": "intel_pt_validate_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578955756,
      "name": "intel_pt_validate_cap",
      "external": true,
      "loc": "arch/x86/events/intel/pt.c:71",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate"
      ],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_reset_markers",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_topa_dump",
        "arch/x86/events/intel/pt.c:topa_insert_table",
        "arch/x86/events/intel/pt.c:pt_cap_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592043478,
      "name": "intel_pt_validate_cap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071578948528,
      "name": "intel_pt_validate_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```

```json
{
  "name": "intel_pt_validate_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578965472,
      "name": "intel_pt_validate_cap",
      "external": true,
      "loc": "arch/x86/events/intel/pt.c:75",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate"
      ],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_addr_filters_init",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_reset_markers",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_topa_dump",
        "arch/x86/events/intel/pt.c:topa_insert_table",
        "arch/x86/events/intel/pt.c:pt_cap_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593809613,
      "name": "intel_pt_validate_cap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071578956880,
      "name": "intel_pt_validate_cap",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```

```json
{
  "name": "intel_pt_validate_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578982903,
      "name": "intel_pt_validate_cap",
      "external": true,
      "loc": "arch/x86/events/intel/pt.c:75",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_cap_show"
      ],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_addr_filters_init",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_reset_markers",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_topa_dump",
        "arch/x86/events/intel/pt.c:topa_insert_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595953946,
      "name": "intel_pt_validate_cap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071578973856,
      "name": "intel_pt_validate_cap",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```

```json
{
  "name": "intel_pt_validate_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578982215,
      "name": "intel_pt_validate_cap",
      "external": true,
      "loc": "arch/x86/events/intel/pt.c:75",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_cap_show"
      ],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_addr_filters_init",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_reset_markers",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_topa_dump",
        "arch/x86/events/intel/pt.c:topa_insert_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596471054,
      "name": "intel_pt_validate_cap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071578973104,
      "name": "intel_pt_validate_cap",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```

```json
{
  "name": "intel_pt_validate_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579005975,
      "name": "intel_pt_validate_cap",
      "external": true,
      "loc": "arch/x86/events/intel/pt.c:75",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_cap_show"
      ],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_addr_filters_init",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_reset_markers",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_topa_dump",
        "arch/x86/events/intel/pt.c:topa_insert_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597366396,
      "name": "intel_pt_validate_cap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071578997872,
      "name": "intel_pt_validate_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```

```json
{
  "name": "intel_pt_validate_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604603915,
      "name": "intel_pt_validate_cap",
      "external": true,
      "loc": "arch/x86/events/intel/pt.c:71",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_reset_markers",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_topa_dump",
        "arch/x86/events/intel/pt.c:topa_insert_table",
        "arch/x86/events/intel/pt.c:pt_cap_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578928736,
      "name": "intel_pt_validate_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```

```json
{
  "name": "intel_pt_validate_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604595442,
      "name": "intel_pt_validate_cap",
      "external": true,
      "loc": "arch/x86/events/intel/pt.c:71",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_reset_markers",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_topa_dump",
        "arch/x86/events/intel/pt.c:topa_insert_table",
        "arch/x86/events/intel/pt.c:pt_cap_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578925456,
      "name": "intel_pt_validate_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```

```json
{
  "name": "intel_pt_validate_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604681739,
      "name": "intel_pt_validate_cap",
      "external": true,
      "loc": "arch/x86/events/intel/pt.c:71",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_reset_markers",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_topa_dump",
        "arch/x86/events/intel/pt.c:topa_insert_table",
        "arch/x86/events/intel/pt.c:pt_cap_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578928672,
      "name": "intel_pt_validate_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```

```json
{
  "name": "intel_pt_validate_cap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604681759,
      "name": "intel_pt_validate_cap",
      "external": true,
      "loc": "arch/x86/events/intel/pt.c:71",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_init",
        "arch/x86/events/intel/pt.c:pt_event_addr_filters_validate",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_setup_aux",
        "arch/x86/events/intel/pt.c:pt_buffer_reset_markers",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_topa_dump",
        "arch/x86/events/intel/pt.c:topa_insert_table",
        "arch/x86/events/intel/pt.c:pt_cap_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578929248,
      "name": "intel_pt_validate_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```
</details>
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
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u32 intel_pt_validate_cap(u32 * caps, enum pt_capabilities capability)
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
