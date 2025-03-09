# Function: <code>cpuidle_governor_latency_req</code>

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
int cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587421600,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:103",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587421600,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587602272,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:109",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587602272,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587879088,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:109",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587879088,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588085056,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:110",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588085056,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
s64 cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588946880,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:110",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588946880,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
s64 cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588959104,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:110",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588959104,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
s64 cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588847600,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:110",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588847600,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
s64 cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589546320,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:110",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589546320,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
s64 cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591039408,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:110",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/haltpoll.c:haltpoll_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591039408,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
s64 cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592750768,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:109",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/haltpoll.c:haltpoll_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592750768,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
s64 cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593185488,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:109",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/haltpoll.c:haltpoll_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593185488,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
s64 cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593939312,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:109",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/teo.c:teo_select",
        "drivers/cpuidle/governors/haltpoll.c:haltpoll_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593939312,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501329968,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:110",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501329968,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233819844,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:110",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233819844,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294874912,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:110",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294874912,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587706848,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:110",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587706848,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587485136,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:110",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587485136,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588041200,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:110",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588041200,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int cpuidle_governor_latency_req(unsigned int cpu)
```

```json
{
  "name": "cpuidle_governor_latency_req",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588157008,
      "name": "cpuidle_governor_latency_req",
      "external": true,
      "loc": "drivers/cpuidle/governor.c:110",
      "file": "drivers/cpuidle/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/ladder.c:ladder_select_state",
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588157008,
      "name": "cpuidle_governor_latency_req",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int cpuidle_governor_latency_req(unsigned int cpu)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>s64</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int cpuidle_governor_latency_req(unsigned int cpu)
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
