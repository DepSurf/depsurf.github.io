# Function: <code>devlink_nl_flash_update_fill</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_nl_flash_update_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588604439,
      "name": "devlink_nl_flash_update_fill",
      "external": false,
      "loc": "net/core/devlink.c:2691",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_flash_update_notify"
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
  "name": "devlink_nl_flash_update_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588826263,
      "name": "devlink_nl_flash_update_fill",
      "external": false,
      "loc": "net/core/devlink.c:2718",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_flash_update_notify"
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
  "name": "devlink_nl_flash_update_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589716911,
      "name": "devlink_nl_flash_update_fill",
      "external": false,
      "loc": "net/core/devlink.c:2846",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_flash_update_notify"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int devlink_nl_flash_update_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, struct devlink_flash_notify * params)
```

```json
{
  "name": "devlink_nl_flash_update_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589736384,
      "name": "devlink_nl_flash_update_fill",
      "external": false,
      "loc": "net/core/devlink.c:3326",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_flash_update_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589736384,
      "name": "devlink_nl_flash_update_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
int devlink_nl_flash_update_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, struct devlink_flash_notify * params)
```

```json
{
  "name": "devlink_nl_flash_update_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589621408,
      "name": "devlink_nl_flash_update_fill",
      "external": false,
      "loc": "net/core/devlink.c:3529",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_flash_update_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589621408,
      "name": "devlink_nl_flash_update_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
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
int devlink_nl_flash_update_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, struct devlink_flash_notify * params)
```

```json
{
  "name": "devlink_nl_flash_update_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590366640,
      "name": "devlink_nl_flash_update_fill",
      "external": false,
      "loc": "net/core/devlink.c:4099",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_flash_update_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590366640,
      "name": "devlink_nl_flash_update_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
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
int devlink_nl_flash_update_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, struct devlink_flash_notify * params)
```

```json
{
  "name": "devlink_nl_flash_update_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591951648,
      "name": "devlink_nl_flash_update_fill",
      "external": false,
      "loc": "net/core/devlink.c:4611",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591951648,
      "name": "devlink_nl_flash_update_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
int devlink_nl_flash_update_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, struct devlink_flash_notify * params)
```

```json
{
  "name": "devlink_nl_flash_update_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593758128,
      "name": "devlink_nl_flash_update_fill",
      "external": false,
      "loc": "net/core/devlink.c:4877",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593758128,
      "name": "devlink_nl_flash_update_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
int devlink_nl_flash_update_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, struct devlink_flash_notify * params)
```

```json
{
  "name": "devlink_nl_flash_update_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595900752,
      "name": "devlink_nl_flash_update_fill",
      "external": false,
      "loc": "net/devlink/dev.c:847",
      "file": "net/devlink/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595900752,
      "name": "devlink_nl_flash_update_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
int devlink_nl_flash_update_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, struct devlink_flash_notify * params)
```

```json
{
  "name": "devlink_nl_flash_update_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596685088,
      "name": "devlink_nl_flash_update_fill",
      "external": false,
      "loc": "net/devlink/dev.c:949",
      "file": "net/devlink/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596685088,
      "name": "devlink_nl_flash_update_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_nl_flash_update_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502399672,
      "name": "devlink_nl_flash_update_fill",
      "external": false,
      "loc": "net/core/devlink.c:2718",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_flash_update_notify"
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
  "name": "devlink_nl_flash_update_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235133576,
      "name": "devlink_nl_flash_update_fill",
      "external": false,
      "loc": "net/core/devlink.c:2718",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_flash_update_notify"
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
  "name": "devlink_nl_flash_update_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295948624,
      "name": "devlink_nl_flash_update_fill",
      "external": false,
      "loc": "net/core/devlink.c:2718",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_flash_update_notify"
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
  "name": "devlink_nl_flash_update_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278611244,
      "name": "devlink_nl_flash_update_fill",
      "external": false,
      "loc": "net/core/devlink.c:2718",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_flash_update_notify"
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
  "name": "devlink_nl_flash_update_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588432647,
      "name": "devlink_nl_flash_update_fill",
      "external": false,
      "loc": "net/core/devlink.c:2718",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_flash_update_notify"
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
  "name": "devlink_nl_flash_update_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588145335,
      "name": "devlink_nl_flash_update_fill",
      "external": false,
      "loc": "net/core/devlink.c:2718",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_flash_update_notify"
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
  "name": "devlink_nl_flash_update_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588764823,
      "name": "devlink_nl_flash_update_fill",
      "external": false,
      "loc": "net/core/devlink.c:2718",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_flash_update_notify"
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
  "name": "devlink_nl_flash_update_fill",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588905351,
      "name": "devlink_nl_flash_update_fill",
      "external": false,
      "loc": "net/core/devlink.c:2718",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_flash_update_notify"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int devlink_nl_flash_update_fill(struct sk_buff * msg, struct devlink * devlink, enum devlink_command cmd, struct devlink_flash_notify * params)
```
</details>
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
