# GhostDriver 👻

## About
GhostDriver is a Rust-built AV killer tool using BYOVD.

## Get Started
1. Install Rust from [rust-lang.org](https://www.rust-lang.org)
2. Clone: `git clone https://github.com/BlackSnufkin/GhostDriver.git`
3. Build: `cargo build --release  --target=x86_64-pc-windows-msvc`
4. Run: Execute the GhostDriver binary

## Usage:
```text
GhostDriver.exe 2.0
BlackSnufkin
Kills processes by name using a Ghost Driver

USAGE:
    GhostDriver.exe [FLAGS] [OPTIONS]

FLAGS:
    -h, --help       Prints help information
    -v, --version    Prints version information

OPTIONS:
    -n, --name=process_names

USAGE:
        .\GhostDriver.exe -n msmpeng.exe,svchost.exe
        .\GhostDriver.exe --name msmpeng.exe
        .\GhostDriver.exe (uses default processes)

```


# POC

![gd2](https://github.com/BlackSnufkin/GhostDriver/assets/61916899/0b465997-c3ea-45b5-86da-61e4551636fe)


# Reference
- https://github.com/keowu/BadRentdrv2
- https://unit42.paloaltonetworks.com/agonizing-serpens-targets-israeli-tech-higher-ed-sectors
