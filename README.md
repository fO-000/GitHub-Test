# GitHub-Test

## Usage

[`sdf`](https://fo-000.github.io/bluing/#usage)

> And God said, "Let there be **colorful**", and there was [**colorful**](https://fo-000.github.io/bluing/#usage).

<details><summary><code><font color="#9fab76">bluing</font> --help</code></summary>

<pre>
$ <span style="font-weight: bold; color: #9fab76">bluing</span> --help
An intelligence gathering tool for hacking Bluetooth

Usage:
    bluing [-h | --help]
    bluing (-v | --version)
    bluing [-i &lthci>] --clean BD_ADDR
    bluing [-i &lthci>] --spoof-bd-addr BD_ADDR
    bluing --flash-micro-bit
    bluing &ltcommand> [&ltargs>...]

Arguments:
    BD_ADDR    Bluetooth device address

Options:
    -h, --help           Print this help and quit
    -v, --version        Print version information and quit
    -i &lthci>             HCI device
    --clean              Clean cached data of a remote device
    --spoof-bd-addr      Spoof the BD_ADDR of a local controller
    --flash-micro-bit    Download the dedicated firmware to micro:bit(s)

Commands:
    br        Basic Rate system, includes an optional Enhanced Data Rate (EDR) extension
    le        Low Energy system
    plugin    Manage plugins

Run `bluing &ltcommand> --help` for more information on a command.
</pre>
</details>
