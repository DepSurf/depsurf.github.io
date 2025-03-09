# Function: <code>cgroup_on_dfl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_on_dfl",
      "external": false,
      "loc": "kernel/cgroup.c:308",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580003718,
      "name": "cgroup_on_dfl",
      "external": false,
      "loc": "kernel/cgroup.c:325",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_pidlist_next",
        "kernel/cgroup.c:cgroup_rename"
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
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580036163,
      "name": "cgroup_on_dfl",
      "external": false,
      "loc": "kernel/cgroup.c:328",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_pidlist_next"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580056904,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:283",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041024,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580088544,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:288",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088544,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580170091,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:291",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_control"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147136,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580217995,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:296",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_control"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580194736,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580266365,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:298",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_control"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580241392,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580314669,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:298",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_control"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580289568,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580386106,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:291",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:link_css_set",
        "kernel/cgroup/cgroup.c:compare_css_sets"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580361104,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580373098,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:288",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:link_css_set",
        "kernel/cgroup/cgroup.c:compare_css_sets"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580347872,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580375978,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:288",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:find_existing_css_set"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580350992,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580537242,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:312",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:find_existing_css_set"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507776,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580734665,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:313",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:link_css_set",
        "kernel/cgroup/cgroup.c:find_existing_css_set"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580704080,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581010611,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:318",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:link_css_set",
        "kernel/cgroup/cgroup.c:find_existing_css_set"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977056,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581099370,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:317",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:link_css_set",
        "kernel/cgroup/cgroup.c:find_existing_css_set"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065040,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581196794,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:319",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:link_css_set",
        "kernel/cgroup/cgroup.c:find_existing_css_set"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581162416,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491567716,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:298",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_control"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491539200,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225532048,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:298",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:css_visible",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_control"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225504452,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284546836,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:298",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:link_css_set",
        "kernel/cgroup/cgroup.c:cgroup_control"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284508128,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271981080,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:298",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_attach_task",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271955418,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580283469,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:298",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_control"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580258368,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580230877,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:298",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_control"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580205904,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580274717,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:298",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_control"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580249616,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool cgroup_on_dfl(const struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_on_dfl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580328285,
      "name": "cgroup_on_dfl",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:298",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:proc_cgroup_show",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:cgroup_file_name",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_control"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580302800,
      "name": "cgroup_on_dfl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
bool cgroup_on_dfl(const struct cgroup * cgrp)
```
</details>
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
