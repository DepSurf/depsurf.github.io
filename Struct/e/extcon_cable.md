# Struct: <code>extcon_cable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
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
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
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
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
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
<code>union extcon_property_value[3] usb_propval</code>
</li>
<li>
<b>Field added. </b>
<code>union extcon_property_value[1] chg_propval</code>
</li>
<li>
<b>Field added. </b>
<code>union extcon_property_value[1] jack_propval</code>
</li>
<li>
<b>Field added. </b>
<code>union extcon_property_value[2] disp_propval</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[1] usb_bits</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[1] chg_bits</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[1] jack_bits</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[1] disp_bits</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct extcon_cable {
    struct extcon_dev * edev;
    int cable_index;
    struct attribute_group attr_g;
    struct device_attribute attr_name;
    struct device_attribute attr_state;
    struct attribute *[3] attrs;
    union extcon_property_value[3] usb_propval;
    union extcon_property_value[1] chg_propval;
    union extcon_property_value[1] jack_propval;
    union extcon_property_value[2] disp_propval;
    long unsigned int[1] usb_bits;
    long unsigned int[1] chg_bits;
    long unsigned int[1] jack_bits;
    long unsigned int[1] disp_bits;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
