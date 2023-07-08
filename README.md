# Ansible Role: timezone

## Description

Manage timezone and RTC local TZ.

## Requirements

None

## Dependencies

None

## OS Platforms

- RHEL-7/CentOS-7 or higher
- Ubuntu-20.04 or higher

## Example Playbook

```
- hosts: all
  roles:
    - timezone
```

## Role Variables

### timezone_package_ensure: (string)

```
timezone_package_ensure: 'present'
```

### timezone_setup_legacy: (bool)

```
timezone_setup_legacy: true
```

### timezone: (string)

```
timezone: ""
```

### timezone_localrtc: (bool)

```
timezone_localrtc: false
```

```
timezone_debug: false
```

## Example vars

```
timezone: Asia/Tokyo
```
