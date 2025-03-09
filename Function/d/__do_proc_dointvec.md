# Function: <code>__do_proc_dointvec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579404144,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:2068",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404144,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1069
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414912,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:2203",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin",
        "kernel/sysctl.c:proc_douintvec",
        "kernel/sysctl.c:moksbstate_disabled_proc_handler",
        "kernel/sysctl.c:secure_boot_proc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414912,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 949
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579435216,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:2188",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin",
        "kernel/sysctl.c:proc_douintvec",
        "kernel/sysctl.c:moksbstate_disabled_proc_handler",
        "kernel/sysctl.c:secure_boot_proc_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435216,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 949
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579425008,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:2214",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425008,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1005
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579452000,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:2204",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452000,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1009
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579466736,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:2209",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579466736,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1003
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579500352,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:2257",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579500352,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 942
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579518528,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:2343",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579518528,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1003
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544608,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:2345",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544608,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1003
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:571",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:sysrq_sysctl_handler",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin",
        "kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change",
        "kernel/sysctl.c:proc_dointvec",
        "kernel/sysctl.c:bpf_stats_handler",
        "kernel/sysctl.c:bpf_stats_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578704,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 838
    },
    {
      "addr": 18446744071579581775,
      "name": "__do_proc_dointvec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:570",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:sysrq_sysctl_handler",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin",
        "kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change",
        "kernel/sysctl.c:proc_dointvec",
        "kernel/sysctl.c:bpf_stats_handler",
        "kernel/sysctl.c:bpf_stats_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579560320,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 838
    },
    {
      "addr": 18446744071591278987,
      "name": "__do_proc_dointvec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:582",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:sysrq_sysctl_handler",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin",
        "kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change",
        "kernel/sysctl.c:proc_dointvec",
        "kernel/sysctl.c:bpf_unpriv_handler",
        "kernel/sysctl.c:bpf_unpriv_handler",
        "kernel/sysctl.c:bpf_stats_handler",
        "kernel/sysctl.c:bpf_stats_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564304,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 932
    },
    {
      "addr": 18446744071591221787,
      "name": "__do_proc_dointvec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:606",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:sysrq_sysctl_handler",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin",
        "kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change",
        "kernel/sysctl.c:proc_dointvec",
        "kernel/sysctl.c:proc_dobool",
        "kernel/sysctl.c:bpf_unpriv_handler",
        "kernel/sysctl.c:bpf_unpriv_handler",
        "kernel/sysctl.c:bpf_stats_handler",
        "kernel/sysctl.c:bpf_stats_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579634224,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 929
    },
    {
      "addr": 18446744071592100947,
      "name": "__do_proc_dointvec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:486",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:sysrq_sysctl_handler",
        "kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change",
        "kernel/sysctl.c:proc_dointvec",
        "kernel/sysctl.c:proc_dobool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579730096,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1002
    },
    {
      "addr": 18446744071593868519,
      "name": "__do_proc_dointvec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:473",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies_minmax",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:sysrq_sysctl_handler",
        "kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change",
        "kernel/sysctl.c:proc_dobool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579864848,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1149
    },
    {
      "addr": 18446744071595974359,
      "name": "__do_proc_dointvec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:472",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies_minmax",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:sysrq_sysctl_handler",
        "kernel/sysctl.c:proc_dobool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914992,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1079
    },
    {
      "addr": 18446744071596491974,
      "name": "__do_proc_dointvec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:472",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies_minmax",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:sysrq_sysctl_handler",
        "kernel/sysctl.c:proc_dobool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579954240,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1079
    },
    {
      "addr": 18446744071597388735,
      "name": "__do_proc_dointvec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490693112,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:2345",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490693112,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224760916,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:2345",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224760916,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 980
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283519264,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:2345",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283519264,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1204
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271425656,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:2345",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271425656,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579518272,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:2345",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579518272,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1003
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579447072,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:2345",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579447072,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1003
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579518192,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:2345",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579518192,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1003
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
int __do_proc_dointvec(void * tbl_data, struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos, int (*)(bool *, long unsigned int *, int *, int, void *) conv, void * data)
```

```json
{
  "name": "__do_proc_dointvec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551152,
      "name": "__do_proc_dointvec",
      "external": false,
      "loc": "kernel/sysctl.c:2345",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sysctl.c:proc_dointvec_ms_jiffies",
        "kernel/sysctl.c:proc_dointvec_userhz_jiffies",
        "kernel/sysctl.c:proc_dointvec_jiffies",
        "kernel/sysctl.c:proc_dointvec_minmax_sysadmin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551152,
      "name": "__do_proc_dointvec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1003
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
