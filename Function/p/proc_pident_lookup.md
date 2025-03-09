# Function: <code>proc_pident_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581456576,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2278",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581456576,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581640848,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2369",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581640848,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581729184,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2404",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729184,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581783216,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2436",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup",
        "fs/proc/base.c:proc_selinux_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581783216,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581932880,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2437",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup",
        "fs/proc/base.c:proc_selinux_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581932880,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582117376,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2440",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582117376,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * ents, unsigned int nents)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582211824,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2460",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582211824,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * p, const struct pid_entry * end)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582375696,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2476",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582375696,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * p, const struct pid_entry * end)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582474608,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2476",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582474608,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * p, const struct pid_entry * end)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582772592,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2609",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582772592,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * p, const struct pid_entry * end)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582845824,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2623",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582845824,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * p, const struct pid_entry * end)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582874240,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2622",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582874240,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * p, const struct pid_entry * end)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583207872,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2628",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583207872,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * p, const struct pid_entry * end)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583704256,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2657",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583704256,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * p, const struct pid_entry * end)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584314864,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2661",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584314864,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * p, const struct pid_entry * end)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584544752,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2661",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584544752,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * p, const struct pid_entry * end)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584776576,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2655",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584776576,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * p, const struct pid_entry * end)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494093784,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2476",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494093784,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * p, const struct pid_entry * end)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227545316,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2476",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227545316,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * p, const struct pid_entry * end)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287760912,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2476",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287760912,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * p, const struct pid_entry * end)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273581262,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2476",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273581262,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * p, const struct pid_entry * end)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582443344,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2476",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582443344,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * p, const struct pid_entry * end)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582380512,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2476",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582380512,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * p, const struct pid_entry * end)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582433824,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2476",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582433824,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
struct dentry * proc_pident_lookup(struct inode * dir, struct dentry * dentry, const struct pid_entry * p, const struct pid_entry * end)
```

```json
{
  "name": "proc_pident_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582513888,
      "name": "proc_pident_lookup",
      "external": false,
      "loc": "fs/proc/base.c:2476",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_tid_base_lookup",
        "fs/proc/base.c:proc_tgid_base_lookup",
        "fs/proc/base.c:proc_attr_dir_lookup",
        "fs/proc/base.c:proc_apparmor_attr_dir_lookup",
        "fs/proc/base.c:proc_smack_attr_dir_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582513888,
      "name": "proc_pident_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct pid_entry * p</code>
</li>
<li>
<b>Param added. </b>
<code>const struct pid_entry * end</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct pid_entry * ents</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int nents</code>
</li>
</ul>
</details>
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
