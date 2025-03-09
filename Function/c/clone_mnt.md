# Function: <code>clone_mnt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581124480,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:967",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:mnt_clone_internal",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:do_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581124480,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581290256,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:967",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581290256,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 796
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581369456,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1010",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369456,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 808
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581423600,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1011",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581423600,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 786
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581566768,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1078",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566768,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 786
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581722256,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1088",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581722256,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 808
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581809296,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1000",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581809296,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581928176,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1024",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581928176,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 732
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582000784,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1024",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000784,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 732
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582235824,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1040",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_loopback",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582235824,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 758
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582284624,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1040",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_loopback",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582284624,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 758
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582310400,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1047",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_loopback",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582310400,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 839
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582629888,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1056",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_loopback",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582629888,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 839
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583166336,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1097",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_loopback",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583166336,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 939
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583741504,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1203",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_loopback",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741504,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 924
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583958080,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1166",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_loopback",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583958080,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 861
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584169216,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1179",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_loopback",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584169216,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 861
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493520784,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1024",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493520784,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227074288,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1024",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_loopback",
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227074288,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287085600,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1024",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287085600,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 872
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273188620,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1024",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273188620,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581969520,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1024",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581969520,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 732
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581907088,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1024",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581907088,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 732
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581960800,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1024",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960800,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 732
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
struct mount * clone_mnt(struct mount * old, struct dentry * root, int flag)
```

```json
{
  "name": "clone_mnt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582028160,
      "name": "clone_mnt",
      "external": false,
      "loc": "fs/namespace.c:1024",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:clone_private_mount",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:copy_tree",
        "fs/namespace.c:mnt_clone_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582028160,
      "name": "clone_mnt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
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
