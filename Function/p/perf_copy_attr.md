# Function: <code>perf_copy_attr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580424182,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:8001",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:SYSC_perf_event_open"
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
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580497439,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:9129",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:SYSC_perf_event_open"
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
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580560895,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:9336",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:SYSC_perf_event_open"
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
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580591119,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:9557",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:SYSC_perf_event_open"
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
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580671231,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:9584",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:SYSC_perf_event_open"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580780768,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:10110",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580780768,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580850800,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:10153",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580850800,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580945808,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:10500",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945808,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976768,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:10630",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976768,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 733
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581154480,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:11217",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581154480,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 775
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194768,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:11501",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194768,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 775
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581213600,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:11656",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581213600,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581453488,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:11768",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581453488,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581796112,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:11707",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796112,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 869
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582227216,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:12004",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582227216,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 873
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582428112,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:12044",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582428112,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 881
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582595088,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:12128",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582595088,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 881
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492353360,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:10630",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492353360,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 952
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226227608,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:10630",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226227608,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 840
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285587744,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:10630",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285587744,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272465670,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:10630",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272465670,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580945568,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:10630",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945568,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 733
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580891632,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:10630",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580891632,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 733
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580936816,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:10630",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936816,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 733
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
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```

```json
{
  "name": "perf_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580998400,
      "name": "perf_copy_attr",
      "external": false,
      "loc": "kernel/events/core.c:10630",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580998400,
      "name": "perf_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 733
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int perf_copy_attr(struct perf_event_attr * uattr, struct perf_event_attr * attr)
```
</details>
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
