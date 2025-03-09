# Function: <code>proc_pident_readdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581458176,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2313",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581458176,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581642544,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2404",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581642544,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581732400,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2439",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581732400,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581786448,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2471",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate",
        "fs/proc/base.c:proc_selinux_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786448,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581936048,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2472",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate",
        "fs/proc/base.c:proc_selinux_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936048,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582120000,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2470",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582120000,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582214496,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2490",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214496,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582378528,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2504",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582378528,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582477440,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2504",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582477440,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582776000,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2637",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582776000,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582849360,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2651",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582849360,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582877760,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2650",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582877760,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583211376,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2656",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583211376,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583708192,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2685",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583708192,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584319152,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2689",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584319152,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584549104,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2689",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584549104,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584780944,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2683",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780944,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494097184,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2504",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494097184,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227548480,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2504",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227548480,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287765488,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2504",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287765488,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273584028,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2504",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273584028,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582446176,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2504",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582446176,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582383344,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2504",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582383344,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582436656,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2504",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582436656,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
int proc_pident_readdir(struct file * file, struct dir_context * ctx, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582516800,
      "name": "proc_pident_readdir",
      "external": false,
      "loc": "fs/proc/base.c:2504",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_readdir",
        "fs/proc/base.c:proc_tgid_base_readdir",
        "fs/proc/base.c:proc_attr_dir_readdir",
        "fs/proc/base.c:proc_apparmor_attr_dir_iterate",
        "fs/proc/base.c:proc_smack_attr_dir_iterate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582516800,
      "name": "proc_pident_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
