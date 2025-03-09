# Function: <code>fsnotify_clear_marks_by_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group * group)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581272960,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:470",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581272960,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581572816,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:654",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572816,
      "name": "fsnotify_clear_marks_by_group",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581717152,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:653",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581717152,
      "name": "fsnotify_clear_marks_by_group",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type_mask)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581884096,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:659",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581884096,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type_mask)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581969056,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:692",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581969056,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type_mask)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582102224,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:719",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102224,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type_mask)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582179552,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:720",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582179552,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type_mask)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582416768,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:724",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582416768,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type_mask)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582470896,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:724",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470896,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type_mask)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582497936,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:720",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582497936,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type_mask)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:749",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592236251,
      "name": "fsnotify_clear_marks_by_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071582812816,
      "name": "fsnotify_clear_marks_by_group",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int obj_type)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583367568,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:786",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583367568,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int obj_type)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583951680,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:786",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583951680,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int obj_type)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584174976,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:786",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584174976,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int obj_type)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584388928,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:750",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584388928,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type_mask)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493737744,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:720",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493737744,
      "name": "fsnotify_clear_marks_by_group",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type_mask)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227261648,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:720",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227261648,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type_mask)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287347440,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:720",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287347440,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type_mask)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273346250,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:720",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273346250,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type_mask)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582148288,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:720",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582148288,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type_mask)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582085728,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:720",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582085728,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type_mask)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582138768,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:720",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582138768,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type_mask)
```

```json
{
  "name": "fsnotify_clear_marks_by_group",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582211808,
      "name": "fsnotify_clear_marks_by_group",
      "external": true,
      "loc": "fs/notify/mark.c:720",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/group.c:fsnotify_destroy_group",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582211808,
      "name": "fsnotify_clear_marks_by_group",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group * group)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group * group, unsigned int type)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int type_mask</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int type</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int obj_type</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int type_mask</code>
</li>
</ul>
</details>
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
