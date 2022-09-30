# My Mac Setup

## Prerequisites

Install developer tools.

```
xcode-select -–install
```

## Building

### Including Bootstrapping

```
./prepare.sh && ./build.sh
```

Above sets up `brew`, `python`, `pip` and `ansible` before running the `playbook.yml`.

### Ansible Only

```
./build.sh
```

## Configuration

### Oh My Zsh Powerlevel10K

```
p10k configure
```

Allow fonts to be installed.

### iTerm2

#### Change appearance

Preferences→Profiles→Colors

 - →Color Presets→Solarized Dark
 - Set Background to #002b36


### Karabiner Elements

#### Map CAPS Lock to Ctrl-L

Under *Simple Modifications*, map CAPS to Ctrl-Left.

![CAPS to Ctrl](images/caps-lock-left-contril.jpg)

#### Map Escape to CAPS Lock

Go to 

https://ke-complex-modifications.pqrs.org/

and search for

```
ctrl + [ escape
```

Select *Vim style escape key mapping*

Import

Enable *Map ctrl + [ to escape*


#### Vim style arrow keys 

Go to 

https://ke-complex-modifications.pqrs.org/

and search for

```
vi style arrows
```

Select *Vim style escape key mapping*

Import

Enable *Fn + h/j/k/l to Arrows*
