# Function: <code>__create_synth_event</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int __create_synth_event(int argc, const char * name, const char * * argv)
```

```json
{
  "name": "__create_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__create_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1094",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_event_create",
        "kernel/trace/trace_events_hist.c:create_or_delete_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580611136,
      "name": "__create_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2617
    },
    {
      "addr": 18446744071580624456,
      "name": "__create_synth_event.cold.48",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int __create_synth_event(int argc, const char * name, const char * * argv)
```

```json
{
  "name": "__create_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__create_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1248",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_event_create",
        "kernel/trace/trace_events_hist.c:create_or_delete_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580682192,
      "name": "__create_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1208
    },
    {
      "addr": 18446744071580684052,
      "name": "__create_synth_event.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int __create_synth_event(int argc, const char * name, const char * * argv)
```

```json
{
  "name": "__create_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__create_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1318",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_event_create",
        "kernel/trace/trace_events_hist.c:create_or_delete_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580729472,
      "name": "__create_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1208
    },
    {
      "addr": 18446744071580731063,
      "name": "__create_synth_event.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __create_synth_event(int argc, const char * name, const char * * argv)
```

```json
{
  "name": "__create_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580810304,
      "name": "__create_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:974",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580810304,
      "name": "__create_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 622
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
int __create_synth_event(int argc, const char * name, const char * * argv)
```

```json
{
  "name": "__create_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580800208,
      "name": "__create_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:1194",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580800208,
      "name": "__create_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 961
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
int __create_synth_event(const char * name, const char * raw_fields)
```

```json
{
  "name": "__create_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580805152,
      "name": "__create_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:1181",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580805152,
      "name": "__create_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1146
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
int __create_synth_event(const char * name, const char * raw_fields)
```

```json
{
  "name": "__create_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580999840,
      "name": "__create_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:1179",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580999840,
      "name": "__create_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1236
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
int __create_synth_event(const char * name, const char * raw_fields)
```

```json
{
  "name": "__create_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581246768,
      "name": "__create_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:1187",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246768,
      "name": "__create_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1511
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
int __create_synth_event(const char * name, const char * raw_fields)
```

```json
{
  "name": "__create_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581569312,
      "name": "__create_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:1197",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581569312,
      "name": "__create_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1495
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
int __create_synth_event(const char * name, const char * raw_fields)
```

```json
{
  "name": "__create_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581688800,
      "name": "__create_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:1270",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581688800,
      "name": "__create_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1732
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
int __create_synth_event(const char * name, const char * raw_fields)
```

```json
{
  "name": "__create_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581805104,
      "name": "__create_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_synth.c:1271",
      "file": "kernel/trace/trace_events_synth.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581805104,
      "name": "__create_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1732
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
int __create_synth_event(int argc, const char * name, const char * * argv)
```

```json
{
  "name": "__create_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492039592,
      "name": "__create_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1318",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_event_create",
        "kernel/trace/trace_events_hist.c:create_or_delete_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492039592,
      "name": "__create_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __create_synth_event(int argc, const char * name, const char * * argv)
```

```json
{
  "name": "__create_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285207008,
      "name": "__create_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1318",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_event_create",
        "kernel/trace/trace_events_hist.c:create_or_delete_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285207008,
      "name": "__create_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1496
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int __create_synth_event(int argc, const char * name, const char * * argv)
```

```json
{
  "name": "__create_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__create_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1318",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_event_create",
        "kernel/trace/trace_events_hist.c:create_or_delete_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580698272,
      "name": "__create_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1208
    },
    {
      "addr": 18446744071580699863,
      "name": "__create_synth_event.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int __create_synth_event(int argc, const char * name, const char * * argv)
```

```json
{
  "name": "__create_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__create_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1318",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_event_create",
        "kernel/trace/trace_events_hist.c:create_or_delete_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580644480,
      "name": "__create_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1208
    },
    {
      "addr": 18446744071580646071,
      "name": "__create_synth_event.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int __create_synth_event(int argc, const char * name, const char * * argv)
```

```json
{
  "name": "__create_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__create_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1318",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_event_create",
        "kernel/trace/trace_events_hist.c:create_or_delete_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580689520,
      "name": "__create_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1208
    },
    {
      "addr": 18446744071580691111,
      "name": "__create_synth_event.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int __create_synth_event(int argc, const char * name, const char * * argv)
```

```json
{
  "name": "__create_synth_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__create_synth_event",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1318",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_event_create",
        "kernel/trace/trace_events_hist.c:create_or_delete_synth_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580747024,
      "name": "__create_synth_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1208
    },
    {
      "addr": 18446744071580748615,
      "name": "__create_synth_event.cold",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __create_synth_event(int argc, const char * name, const char * * argv)
```
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char * raw_fields</code>
</li>
<li>
<b>Param removed. </b>
<code>int argc</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * * argv</code>
</li>
<li>
<b>Param reordered. </b>
<code>argc, name, argv</code> ➡️ <code>name, raw_fields</code>
</li>
</ul>
</details>
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
int __create_synth_event(int argc, const char * name, const char * * argv)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __create_synth_event(int argc, const char * name, const char * * argv)
```
</details>
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
