# Struct: <code>cpufreq_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u8 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_supported;
    bool boost_enabled;
    int (*)(int) set_boost;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u8 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(int) set_boost;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u8 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(int) set_boost;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u8 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(int) set_boost;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u8 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(int) set_boost;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u8 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(int) set_boost;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u8 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(int) set_boost;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u8 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    void (*)(unsigned int) update_limits;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) online;
    int (*)(struct cpufreq_policy *) offline;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(int) set_boost;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u8 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy_data *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    void (*)(unsigned int) update_limits;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) online;
    int (*)(struct cpufreq_policy *) offline;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(int) set_boost;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u8 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy_data *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    void (*)(unsigned int) update_limits;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) online;
    int (*)(struct cpufreq_policy *) offline;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(struct cpufreq_policy *, int) set_boost;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u16 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy_data *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    void (*)(unsigned int, long unsigned int, long unsigned int, long unsigned int) adjust_perf;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    void (*)(unsigned int) update_limits;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) online;
    int (*)(struct cpufreq_policy *) offline;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(struct cpufreq_policy *, int) set_boost;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u16 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy_data *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    void (*)(unsigned int, long unsigned int, long unsigned int, long unsigned int) adjust_perf;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    void (*)(unsigned int) update_limits;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) online;
    int (*)(struct cpufreq_policy *) offline;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(struct cpufreq_policy *, int) set_boost;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u16 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy_data *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    void (*)(unsigned int, long unsigned int, long unsigned int, long unsigned int) adjust_perf;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    void (*)(unsigned int) update_limits;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) online;
    int (*)(struct cpufreq_policy *) offline;
    int (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(struct cpufreq_policy *, int) set_boost;
    void (*)(struct cpufreq_policy *) register_em;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u16 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy_data *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    void (*)(unsigned int, long unsigned int, long unsigned int, long unsigned int) adjust_perf;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    void (*)(unsigned int) update_limits;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) online;
    int (*)(struct cpufreq_policy *) offline;
    int (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(struct cpufreq_policy *, int) set_boost;
    void (*)(struct cpufreq_policy *) register_em;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u16 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy_data *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    void (*)(unsigned int, long unsigned int, long unsigned int, long unsigned int) adjust_perf;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    void (*)(unsigned int) update_limits;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) online;
    int (*)(struct cpufreq_policy *) offline;
    int (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(struct cpufreq_policy *, int) set_boost;
    void (*)(struct cpufreq_policy *) register_em;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u16 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy_data *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    void (*)(unsigned int, long unsigned int, long unsigned int, long unsigned int) adjust_perf;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    void (*)(unsigned int) update_limits;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) online;
    int (*)(struct cpufreq_policy *) offline;
    int (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(struct cpufreq_policy *, int) set_boost;
    void (*)(struct cpufreq_policy *) register_em;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u16 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy_data *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    void (*)(unsigned int, long unsigned int, long unsigned int, long unsigned int) adjust_perf;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    void (*)(unsigned int) update_limits;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) online;
    int (*)(struct cpufreq_policy *) offline;
    int (*)(struct cpufreq_policy *) exit;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(struct cpufreq_policy *, int) set_boost;
    void (*)(struct cpufreq_policy *) register_em;
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
struct cpufreq_driver {
    char[16] name;
    u8 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy_data *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    void (*)(unsigned int) update_limits;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) online;
    int (*)(struct cpufreq_policy *) offline;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(int) set_boost;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u8 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy_data *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    void (*)(unsigned int) update_limits;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) online;
    int (*)(struct cpufreq_policy *) offline;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(int) set_boost;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u8 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy_data *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    void (*)(unsigned int) update_limits;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) online;
    int (*)(struct cpufreq_policy *) offline;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(int) set_boost;
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
struct cpufreq_driver {
    char[16] name;
    u8 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy_data *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    void (*)(unsigned int) update_limits;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) online;
    int (*)(struct cpufreq_policy *) offline;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(int) set_boost;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u8 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy_data *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    void (*)(unsigned int) update_limits;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) online;
    int (*)(struct cpufreq_policy *) offline;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(int) set_boost;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u8 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy_data *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    void (*)(unsigned int) update_limits;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) online;
    int (*)(struct cpufreq_policy *) offline;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(int) set_boost;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u8 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy_data *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    void (*)(unsigned int) update_limits;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) online;
    int (*)(struct cpufreq_policy *) offline;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(int) set_boost;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq</code>
</li>
<li>
<b>Field removed. </b>
<code>bool boost_supported</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>void (*)(unsigned int) update_limits</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct cpufreq_policy *) online</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct cpufreq_policy *) offline</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct cpufreq_policy *) verify</code> ➡️ <code>int (*)(struct cpufreq_policy_data *) verify</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(int) set_boost</code> ➡️ <code>int (*)(struct cpufreq_policy *, int) set_boost</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(unsigned int, long unsigned int, long unsigned int, long unsigned int) adjust_perf</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8 flags</code> ➡️ <code>u16 flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct cpufreq_policy *) register_em</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct cpufreq_policy *) stop_cpu</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct cpufreq_policy *) ready</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct cpufreq_policy *) ready</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct cpufreq_driver {
    char[16] name;
    u8 flags;
    void * driver_data;
    int (*)(struct cpufreq_policy *) init;
    int (*)(struct cpufreq_policy_data *) verify;
    int (*)(struct cpufreq_policy *) setpolicy;
    int (*)(struct cpufreq_policy *, unsigned int, unsigned int) target;
    int (*)(struct cpufreq_policy *, unsigned int) target_index;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) fast_switch;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) resolve_freq;
    unsigned int (*)(struct cpufreq_policy *, unsigned int) get_intermediate;
    int (*)(struct cpufreq_policy *, unsigned int) target_intermediate;
    unsigned int (*)(unsigned int) get;
    void (*)(unsigned int) update_limits;
    int (*)(int, unsigned int *) bios_limit;
    int (*)(struct cpufreq_policy *) online;
    int (*)(struct cpufreq_policy *) offline;
    int (*)(struct cpufreq_policy *) exit;
    void (*)(struct cpufreq_policy *) stop_cpu;
    int (*)(struct cpufreq_policy *) suspend;
    int (*)(struct cpufreq_policy *) resume;
    void (*)(struct cpufreq_policy *) ready;
    struct freq_attr * * attr;
    bool boost_enabled;
    int (*)(int) set_boost;
}
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
