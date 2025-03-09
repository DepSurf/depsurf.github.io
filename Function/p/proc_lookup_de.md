# Function: <code>proc_lookup_de</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * proc_lookup_de(struct proc_dir_entry * de, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463904,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:232",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_lookup",
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463904,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct dentry * proc_lookup_de(struct proc_dir_entry * de, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581648448,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:236",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_lookup",
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648448,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct dentry * proc_lookup_de(struct proc_dir_entry * de, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581736752,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:236",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_lookup",
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581736752,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct dentry * proc_lookup_de(struct proc_dir_entry * de, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581790704,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:219",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_lookup",
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790704,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
struct dentry * proc_lookup_de(struct proc_dir_entry * de, struct inode * dir, struct dentry * dentry)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581940064,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:221",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_lookup",
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581940064,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582123328,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:246",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_lookup",
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123328,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217776,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:246",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_lookup",
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217776,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582381936,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:247",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_lookup",
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381936,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582480848,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:247",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_lookup",
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582480848,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582779456,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:249",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582779456,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582852752,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:249",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582852752,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582880912,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:244",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880912,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583214528,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:244",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583214528,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583711712,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:244",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583711712,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584323104,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:244",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584323104,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584553056,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:243",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584553056,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584784912,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:243",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584784912,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494102232,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:247",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_lookup",
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494102232,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227552212,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:247",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_lookup",
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227552212,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287770560,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:247",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_lookup",
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287770560,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273588384,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:247",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_lookup",
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273588384,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582449584,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:247",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_lookup",
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449584,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582386752,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:247",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_lookup",
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582386752,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582440064,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:247",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_lookup",
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440064,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct dentry * proc_lookup_de(struct inode * dir, struct dentry * dentry, struct proc_dir_entry * de)
```

```json
{
  "name": "proc_lookup_de",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582520240,
      "name": "proc_lookup_de",
      "external": true,
      "loc": "fs/proc/generic.c:247",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/generic.c:proc_lookup",
        "fs/proc/proc_net.c:proc_tgid_net_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582520240,
      "name": "proc_lookup_de",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param reordered. </b>
<code>de, dir, dentry</code> ➡️ <code>dir, dentry, de</code>
</li>
</ul>
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
