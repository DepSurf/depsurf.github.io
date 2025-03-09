# Function: <code>uncore_event_to_pmu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct intel_uncore_pmu * uncore_event_to_pmu(struct perf_event * event)
```

```json
{
  "name": "uncore_event_to_pmu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578936864,
      "name": "uncore_event_to_pmu",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:85",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_to_box"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578936864,
      "name": "uncore_event_to_pmu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:329",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:329",
      "file": "arch/x86/events/intel/uncore_snb.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:334",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:334",
      "file": "arch/x86/events/intel/uncore_snb.c",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:334",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:334",
      "file": "arch/x86/events/intel/uncore_snb.c",
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
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:335",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:335",
      "file": "arch/x86/events/intel/uncore_snb.c",
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
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578928860,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:456",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578942460,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:456",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
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
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578930652,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:473",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578944492,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:473",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
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
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578936362,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:495",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578950092,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:495",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
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
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578938842,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:483",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578952524,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:483",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
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
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578946458,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:486",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578958892,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:486",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
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
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578948378,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:523",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578960172,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:523",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
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
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578953274,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:536",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578965260,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:536",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
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
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578963914,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:537",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977804,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:537",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
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
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:537",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:537",
      "file": "arch/x86/events/intel/uncore_snb.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:553",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:553",
      "file": "arch/x86/events/intel/uncore_snb.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:556",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:556",
      "file": "arch/x86/events/intel/uncore_snb.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:556",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:556",
      "file": "arch/x86/events/intel/uncore_snb.c",
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
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578938842,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:483",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578952524,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:483",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
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
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578935818,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:483",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578949900,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:483",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
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
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578938778,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:483",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578952460,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:483",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
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
  "name": "uncore_event_to_pmu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578939354,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:483",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578953036,
      "name": "uncore_event_to_pmu",
      "external": false,
      "loc": "arch/x86/events/intel/uncore.h:483",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
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
struct intel_uncore_pmu * uncore_event_to_pmu(struct perf_event * event)
```
</details>
</li>
</ul>
