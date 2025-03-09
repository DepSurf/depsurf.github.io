# Function: <code>snoop_urb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585246704,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:357",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585246704,
      "name": "snoop_urb.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585646494,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:465",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585638896,
      "name": "snoop_urb.part.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585834178,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:465",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826480,
      "name": "snoop_urb.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585919903,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:459",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585913456,
      "name": "snoop_urb.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586360708,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:449",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586354240,
      "name": "snoop_urb.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586617786,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:447",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586611408,
      "name": "snoop_urb.part.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586766922,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:447",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586760992,
      "name": "snoop_urb.part.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587023080,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:445",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587028839,
      "name": "snoop_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587222916,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:457",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587229015,
      "name": "snoop_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588072876,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:466",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588082131,
      "name": "snoop_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588118436,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:466",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591551056,
      "name": "snoop_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587999379,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:466",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591493366,
      "name": "snoop_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void snoop_urb(struct usb_device * udev, void * userurb, int pipe, unsigned int length, int timeout_or_status, enum snoop_when when, unsigned char * data, unsigned int data_len)
```

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588607177,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:467",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588607120,
      "name": "snoop_urb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071592570833,
      "name": "snoop_urb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void snoop_urb(struct usb_device * udev, void * userurb, int pipe, unsigned int length, int timeout_or_status, enum snoop_when when, unsigned char * data, unsigned int data_len)
```

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590022761,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:479",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590022704,
      "name": "snoop_urb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071594450912,
      "name": "snoop_urb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void snoop_urb(struct usb_device * udev, void * userurb, int pipe, unsigned int length, int timeout_or_status, enum snoop_when when, unsigned char * data, unsigned int data_len)
```

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591624785,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:479",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591624720,
      "name": "snoop_urb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
    },
    {
      "addr": 18446744071596272176,
      "name": "snoop_urb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void snoop_urb(struct usb_device * udev, void * userurb, int pipe, unsigned int length, int timeout_or_status, enum snoop_when when, unsigned char * data, unsigned int data_len)
```

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592047313,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:486",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592047248,
      "name": "snoop_urb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
    },
    {
      "addr": 18446744071596801981,
      "name": "snoop_urb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void snoop_urb(struct usb_device * udev, void * userurb, int pipe, unsigned int length, int timeout_or_status, enum snoop_when when, unsigned char * data, unsigned int data_len)
```

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592787377,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:486",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:do_proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592787312,
      "name": "snoop_urb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
    },
    {
      "addr": 18446744071597725587,
      "name": "snoop_urb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500308428,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:457",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500326912,
      "name": "snoop_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232777928,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:457",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232787316,
      "name": "snoop_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293623220,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:457",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293633676,
      "name": "snoop_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277212336,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:457",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277221384,
      "name": "snoop_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586928996,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:457",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586935095,
      "name": "snoop_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586870164,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:457",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586876247,
      "name": "snoop_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587177476,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:457",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587183575,
      "name": "snoop_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "snoop_urb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587284548,
      "name": "snoop_urb",
      "external": false,
      "loc": "drivers/usb/core/devio.c:457",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:async_completed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587290711,
      "name": "snoop_urb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void snoop_urb(struct usb_device * udev, void * userurb, int pipe, unsigned int length, int timeout_or_status, enum snoop_when when, unsigned char * data, unsigned int data_len)
```
</details>
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
