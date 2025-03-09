# Function: <code>__output_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580399716,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:154",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580439791,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:154",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_begin"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580473512,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:175",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580512745,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:175",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580537240,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:175",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580576729,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:175",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580575386,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:175",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580607353,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:175",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580633526,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:176",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580688361,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:176",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580787352,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:176",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580820391,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:176",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580856616,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:176",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580887063,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:176",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580945068,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580984551,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580998540,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581038535,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581169723,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:178",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read_group",
        "kernel/events/core.c:perf_output_read_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581219214,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:178",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy_aux"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581212809,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:178",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read_group",
        "kernel/events/core.c:perf_output_read_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581261854,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:178",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy_aux"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581234617,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:178",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read_group",
        "kernel/events/core.c:perf_output_read_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581280608,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:178",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy_aux"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581473049,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:178",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read_group",
        "kernel/events/core.c:perf_output_read_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524512,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:178",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy_aux"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581824155,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:183",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read_group",
        "kernel/events/core.c:perf_output_read_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581872256,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:183",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy_aux"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int __output_copy(struct perf_output_handle * handle, const void * buf, long unsigned int len)
```

```json
{
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582212608,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:183",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read_group",
        "kernel/events/core.c:perf_output_read_group"
      ]
    },
    {
      "addr": 18446744071582296704,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:183",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_copy_aux",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582212608,
      "name": "__output_copy.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071582296704,
      "name": "__output_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int __output_copy(struct perf_output_handle * handle, const void * buf, long unsigned int len)
```

```json
{
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582412608,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:183",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read_group",
        "kernel/events/core.c:perf_output_read_group"
      ]
    },
    {
      "addr": 18446744071582497472,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:183",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_copy_aux",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582412608,
      "name": "__output_copy.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071582497472,
      "name": "__output_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
long unsigned int __output_copy(struct perf_output_handle * handle, const void * buf, long unsigned int len)
```

```json
{
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582580912,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:183",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_text_poke_output",
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_cgroup_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read_group",
        "kernel/events/core.c:perf_output_read_group"
      ]
    },
    {
      "addr": 18446744071582665984,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:183",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/ring_buffer.c:perf_output_copy_aux",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582580912,
      "name": "__output_copy.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071582665984,
      "name": "__output_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int __output_copy(struct perf_output_handle * handle, const void * buf, long unsigned int len)
```

```json
{
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492341568,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_output_sample"
      ]
    },
    {
      "addr": 18446603336492392668,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492324560,
      "name": "__output_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226233608,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3226278896,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285592748,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285653428,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272464580,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272502560,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580967340,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581007383,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580913452,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953511,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580958588,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998583,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy"
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
  "name": "__output_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581023148,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_ksymbol_output",
        "kernel/events/core.c:perf_event_mmap_output",
        "kernel/events/core.c:perf_event_comm_output",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_output_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581059687,
      "name": "__output_copy",
      "external": false,
      "loc": "kernel/events/internal.h:177",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_copy"
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
long unsigned int __output_copy(struct perf_output_handle * handle, const void * buf, long unsigned int len)
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
long unsigned int __output_copy(struct perf_output_handle * handle, const void * buf, long unsigned int len)
```
</details>
</li>
</ul>
