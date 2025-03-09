# Struct: <code>thermal_zone_device_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) change_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    void (*)(struct thermal_zone_device *) hot;
    void (*)(struct thermal_zone_device *) critical;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) change_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    void (*)(struct thermal_zone_device *) hot;
    void (*)(struct thermal_zone_device *) critical;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) change_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    void (*)(struct thermal_zone_device *) hot;
    void (*)(struct thermal_zone_device *) critical;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) change_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    void (*)(struct thermal_zone_device *) hot;
    void (*)(struct thermal_zone_device *) critical;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) change_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    void (*)(struct thermal_zone_device *) hot;
    void (*)(struct thermal_zone_device *) critical;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) change_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    void (*)(struct thermal_zone_device *) hot;
    void (*)(struct thermal_zone_device *) critical;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) change_mode;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, const struct thermal_trip *, enum thermal_trend *) get_trend;
    void (*)(struct thermal_zone_device *) hot;
    void (*)(struct thermal_zone_device *) critical;
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
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify;
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
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct thermal_zone_device_ops {
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) bind;
    int (*)(struct thermal_zone_device *, struct thermal_cooling_device *) unbind;
    int (*)(struct thermal_zone_device *, int *) get_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trips;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode;
    int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_temp;
    int (*)(struct thermal_zone_device *, int, int) set_trip_temp;
    int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst;
    int (*)(struct thermal_zone_device *, int, int) set_trip_hyst;
    int (*)(struct thermal_zone_device *, int *) get_crit_temp;
    int (*)(struct thermal_zone_device *, int) set_emul_temp;
    int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend;
    int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct thermal_zone_device *, int, int) set_trips</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct thermal_zone_device *, enum thermal_device_mode) change_mode</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct thermal_zone_device *) hot</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct thermal_zone_device *) critical</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct thermal_zone_device *, enum thermal_device_mode *) get_mode</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct thermal_zone_device *, enum thermal_device_mode) set_mode</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct thermal_zone_device *, int, enum thermal_trip_type) notify</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct thermal_zone_device *, int, enum thermal_trip_type *) get_trip_type</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct thermal_zone_device *, int, int *) get_trip_temp</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct thermal_zone_device *, int, int *) get_trip_hyst</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct thermal_zone_device *, int, enum thermal_trend *) get_trend</code> ➡️ <code>int (*)(struct thermal_zone_device *, const struct thermal_trip *, enum thermal_trend *) get_trend</code>
</li>
</ul>
</details>
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
