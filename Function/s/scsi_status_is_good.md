# Function: <code>scsi_status_is_good</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584804939,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:69",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584853395,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:69",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584875562,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:69",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_check_events",
        "drivers/scsi/sr.c:sr_probe"
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585166056,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:50",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585229077,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:50",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585239710,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:50",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_check_events"
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585360304,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:50",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585424307,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:50",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585439534,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:50",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_check_events"
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585436809,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:40",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585509179,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:40",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585524215,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:40",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_check_events"
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585867433,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585940875,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585955340,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_check_events"
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586113631,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586188132,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586203575,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_check_events"
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586259967,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586330884,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586343982,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_check_events"
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586504047,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586574973,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586587489,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_check_events"
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586651935,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586722234,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586734929,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_check_events"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int scsi_status_is_good(int status)
```

```json
{
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587456135,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_result_to_blk_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587516460,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_app_tag_own",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_spinup_disk"
      ]
    },
    {
      "addr": 18446744071587537917,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:get_capabilities",
        "drivers/scsi/sr.c:sr_check_events"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587502368,
      "name": "scsi_status_is_good",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int scsi_status_is_good(int status)
```

```json
{
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587524439,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_result_to_blk_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587582753,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_app_tag_own",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_spinup_disk"
      ]
    },
    {
      "addr": 18446744071587604733,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:get_capabilities",
        "drivers/scsi/sr.c:sr_check_events"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587569216,
      "name": "scsi_status_is_good",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int scsi_status_is_good(int status)
```

```json
{
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587406143,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_result_to_blk_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587468283,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_spinup_disk"
      ]
    },
    {
      "addr": 18446744071587484696,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_check_events"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587450560,
      "name": "scsi_status_is_good",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool scsi_status_is_good(int status)
```

```json
{
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587977474,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:196",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_result_to_blk_status",
        "drivers/scsi/scsi_lib.c:scsi_result_to_blk_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588043285,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:196",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_spinup_disk"
      ]
    },
    {
      "addr": 18446744071588061059,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:196",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_check_events"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588030080,
      "name": "scsi_status_is_good",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool scsi_status_is_good(int status)
```

```json
{
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589334557,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:196",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_result_to_blk_status",
        "drivers/scsi/scsi_lib.c:scsi_result_to_blk_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589405916,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:196",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:sd_spinup_disk"
      ]
    },
    {
      "addr": 18446744071589425929,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:196",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_check_events"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589393104,
      "name": "scsi_status_is_good",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590900349,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:197",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590979545,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:197",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591002649,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:197",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_check_events"
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591244332,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:197",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591333108,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:197",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591356342,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:197",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_check_events"
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591591596,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:200",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591682644,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:200",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591706263,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:200",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_check_events"
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499550168,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499633408,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499645012,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_check_events"
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232013376,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 3232087832,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 3232100324,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_check_events"
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292843492,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292952784,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292969108,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_check_events"
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276749406,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276815858,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276829564,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_check_events"
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586342415,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586412714,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586425409,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_check_events"
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586183743,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586288970,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586301665,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_check_events"
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586599903,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586676794,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586689489,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_check_events"
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
  "name": "scsi_status_is_good",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586712175,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_mode_sense",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586782810,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_read_cache_type",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk",
        "drivers/scsi/sd.c:sd_spinup_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586794815,
      "name": "scsi_status_is_good",
      "external": false,
      "loc": "include/scsi/scsi.h:41",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_check_events"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int scsi_status_is_good(int status)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool scsi_status_is_good(int status)
```
</details>
</li>
</ul>
