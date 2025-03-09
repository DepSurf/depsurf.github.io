# Function: <code>cpufreq_freq_transition_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585853152,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:457",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585853152,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586252752,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:412",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586252752,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586457568,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:412",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586457568,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586582128,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:412",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586582128,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587065392,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:418",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587065392,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587363184,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:403",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587363184,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587543056,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:403",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_out_of_sync",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587543056,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:433",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587832728,
      "name": "cpufreq_freq_transition_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071587817584,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588025232,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:436",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588025232,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588890704,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:441",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:__target_intermediate",
        "drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588890704,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588902816,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:443",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:__target_intermediate",
        "drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588902816,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588790544,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:440",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588790544,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:440",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592656661,
      "name": "cpufreq_freq_transition_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589483376,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:441",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_target",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594541398,
      "name": "cpufreq_freq_transition_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590963056,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:441",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_target",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596313863,
      "name": "cpufreq_freq_transition_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592667840,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:446",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_update_freq",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596842784,
      "name": "cpufreq_freq_transition_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593098192,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:447",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:__target_index",
        "drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_update_freq",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597767930,
      "name": "cpufreq_freq_transition_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593850960,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501291032,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:436",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501291032,
      "name": "cpufreq_freq_transition_end",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233779244,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:436",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233779244,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294817600,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:436",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294817600,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587650224,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:436",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587650224,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587424096,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:436",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587424096,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587981376,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:436",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587981376,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
```

```json
{
  "name": "cpufreq_freq_transition_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588096784,
      "name": "cpufreq_freq_transition_end",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:436",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:__cpufreq_driver_target",
        "drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588096784,
      "name": "cpufreq_freq_transition_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void cpufreq_freq_transition_end(struct cpufreq_policy * policy, struct cpufreq_freqs * freqs, int transition_failed)
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
