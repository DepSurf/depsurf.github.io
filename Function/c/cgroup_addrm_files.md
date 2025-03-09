# Function: <code>cgroup_addrm_files</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579974064,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup.c:3493",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:css_clear_dir",
        "kernel/cgroup.c:css_populate_dir",
        "kernel/cgroup.c:css_populate_dir",
        "kernel/cgroup.c:css_populate_dir",
        "kernel/cgroup.c:cgroup_apply_cftypes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579974064,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 837
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
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580007376,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup.c:3680",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup.c:css_populate_dir",
        "kernel/cgroup.c:css_populate_dir",
        "kernel/cgroup.c:css_populate_dir",
        "kernel/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007376,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 821
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
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580040976,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup.c:3691",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup.c:css_populate_dir",
        "kernel/cgroup.c:css_populate_dir",
        "kernel/cgroup.c:css_populate_dir",
        "kernel/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580040976,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 821
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
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580038352,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3198",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038352,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 805
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
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580087152,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3568",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580087152,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 805
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3596",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145696,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 826
    },
    {
      "addr": 18446744071580170817,
      "name": "cgroup_addrm_files.cold.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3659",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580193296,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 831
    },
    {
      "addr": 18446744071580218705,
      "name": "cgroup_addrm_files.cold.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3915",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580239424,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
    },
    {
      "addr": 18446744071580267614,
      "name": "cgroup_addrm_files.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3917",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580287600,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
    },
    {
      "addr": 18446744071580315820,
      "name": "cgroup_addrm_files.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3858",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580359008,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    },
    {
      "addr": 18446744071580387381,
      "name": "cgroup_addrm_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3859",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580345808,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    },
    {
      "addr": 18446744071591315182,
      "name": "cgroup_addrm_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3872",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580349104,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 800
    },
    {
      "addr": 18446744071591257359,
      "name": "cgroup_addrm_files.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4042",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580505200,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 879
    },
    {
      "addr": 18446744071592160897,
      "name": "cgroup_addrm_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4053",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580687312,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1055
    },
    {
      "addr": 18446744071593933777,
      "name": "cgroup_addrm_files.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4222",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580959280,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
    },
    {
      "addr": 18446744071595999403,
      "name": "cgroup_addrm_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4199",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046656,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
    },
    {
      "addr": 18446744071596517538,
      "name": "cgroup_addrm_files.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4232",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581143712,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1043
    },
    {
      "addr": 18446744071597417739,
      "name": "cgroup_addrm_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491535896,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3917",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491535896,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
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
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225494728,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3917",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225494728,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
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
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284504000,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3917",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284504000,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1260
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
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271953106,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3917",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271953106,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3917",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580256400,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
    },
    {
      "addr": 18446744071580284620,
      "name": "cgroup_addrm_files.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3917",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580203664,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 789
    },
    {
      "addr": 18446744071580232028,
      "name": "cgroup_addrm_files.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3917",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580247648,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
    },
    {
      "addr": 18446744071580275868,
      "name": "cgroup_addrm_files.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int cgroup_addrm_files(struct cgroup_subsys_state * css, struct cgroup * cgrp, struct cftype * cfts, bool is_add)
```

```json
{
  "name": "cgroup_addrm_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_addrm_files",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3917",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_apply_cftypes",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293728,
      "name": "cgroup_addrm_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 763
    },
    {
      "addr": 18446744071580329676,
      "name": "cgroup_addrm_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
