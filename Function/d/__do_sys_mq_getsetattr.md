# Function: <code>__do_sys_mq_getsetattr</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582913472,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1344",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_getsetattr",
        "ipc/mqueue.c:__x64_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582913472,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583023008,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1344",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_getsetattr",
        "ipc/mqueue.c:__x64_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583023008,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583203952,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1399",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_getsetattr",
        "ipc/mqueue.c:__x64_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583203952,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583309728,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1394",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_getsetattr",
        "ipc/mqueue.c:__x64_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583309728,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583640448,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1480",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_getsetattr",
        "ipc/mqueue.c:__x64_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583640448,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583761536,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1480",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_getsetattr",
        "ipc/mqueue.c:__x64_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583761536,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583785680,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1483",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_getsetattr",
        "ipc/mqueue.c:__x64_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583785680,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584148496,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1485",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_getsetattr",
        "ipc/mqueue.c:__x64_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584148496,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584743440,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1497",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_getsetattr",
        "ipc/mqueue.c:__x64_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584743440,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585437936,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1496",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_getsetattr",
        "ipc/mqueue.c:__x64_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585437936,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585668688,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1496",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_getsetattr",
        "ipc/mqueue.c:__x64_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585668688,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585915472,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1496",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_getsetattr",
        "ipc/mqueue.c:__x64_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585915472,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495049296,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1394",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__arm64_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495049296,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228454460,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1394",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__se_sys_mq_getsetattr"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288936288,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1394",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__se_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288936288,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274320862,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1394",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__se_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274320862,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 570
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583278464,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1394",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_getsetattr",
        "ipc/mqueue.c:__x64_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583278464,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583215600,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1394",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_getsetattr",
        "ipc/mqueue.c:__x64_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583215600,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583262496,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1394",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_getsetattr",
        "ipc/mqueue.c:__x64_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583262496,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```

```json
{
  "name": "__do_sys_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583354592,
      "name": "__do_sys_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1394",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_getsetattr",
        "ipc/mqueue.c:__x64_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583354592,
      "name": "__do_sys_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int __do_sys_mq_getsetattr(mqd_t mqdes, const struct mq_attr * u_mqstat, struct mq_attr * u_omqstat)
```
</details>
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
