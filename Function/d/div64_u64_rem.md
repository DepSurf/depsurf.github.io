# Function: <code>div64_u64_rem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579845180,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:36",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580359766,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:36",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:__bpf_prog_run",
        "kernel/bpf/core.c:__bpf_prog_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585846191,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:36",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/md/dm-stats.c:dm_stats_message"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579874236,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:36",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580416605,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:36",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:__bpf_prog_run",
        "kernel/bpf/core.c:__bpf_prog_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586242471,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:36",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/md/dm-stats.c:dm_stats_account_io"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579885948,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:36",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580465357,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:36",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:__bpf_prog_run",
        "kernel/bpf/core.c:__bpf_prog_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586446866,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:36",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:36",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580485374,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:36",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:___bpf_prog_run",
        "kernel/bpf/core.c:___bpf_prog_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586552741,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:36",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587020261,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579988549,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587318721,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580035205,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587499039,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580077573,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587774027,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588575342,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580126677,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587978603,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588792670,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580187957,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:53",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588833852,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:53",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589680995,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:53",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580172645,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:53",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588850300,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:53",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589710595,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:53",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580177141,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:53",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581114404,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:53",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_float_check_member"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588737075,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:53",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589595782,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:53",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580322645,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580347769,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581345700,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_float_check_member"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589427539,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590345110,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580534453,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580561568,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581655447,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_float_check_member"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590905690,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591932663,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580790949,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580821088,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582049367,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_float_check_member"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592602123,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593737799,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580874245,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580904437,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582243463,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_float_check_member"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593032690,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595841495,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "net/devlink/leftover.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/leftover.c:devlink_nl_cmd_resource_set"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580965509,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580994965,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582399735,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "kernel/bpf/btf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_float_check_member"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592087079,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "drivers/gpu/drm/drm_mm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mm.c:drm_mm_scan_add_block",
        "drivers/gpu/drm/drm_mm.c:drm_mm_insert_node_in_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593784066,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596725639,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:54",
      "file": "net/devlink/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/resource.c:devlink_nl_resource_set_doit"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491348424,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501222572,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502363456,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
u64 div64_u64_rem(u64 dividend, u64 divisor, u64 * remainder)
```

```json
{
  "name": "div64_u64_rem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229485740,
      "name": "div64_u64_rem",
      "external": true,
      "loc": "lib/math/div64.c:102",
      "file": "lib/math/div64.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:scale64_check_overflow",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229485740,
      "name": "div64_u64_rem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284282052,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:get_device_system_crosststamp",
        "kernel/time/timekeeping.c:get_device_system_crosststamp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294748772,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295892796,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271841040,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277917112,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278579840,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580095877,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587609579,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588399054,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580041189,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377595,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588111742,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580086949,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587934747,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588731230,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
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
  "name": "div64_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580138693,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timekeeping.c:scale64_check_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588049990,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588871598,
      "name": "div64_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:52",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
u64 div64_u64_rem(u64 dividend, u64 divisor, u64 * remainder)
```
</details>
</li>
</ul>
