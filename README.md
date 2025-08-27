# FastRoll Binary Releases

Binary releases for FastRoll fuzz target conformance testing

Download the latest binary for your platform from the [Releases](https://github.com/fastroll-jam/fastroll-releases/releases) page

## Supported Platforms
- Linux x86_64
- macOS aarch64

## Usage
```bash
$ fastroll fuzz --socket <SOCKET_ADDRESS>
```
### Options:
- `--socket`: Socket address for communication between target <> fuzzer (default: `/tmp/jam_target.sock`)

## Supported chainspec
- [tiny](https://docs.jamcha.in/basics/chain-spec/tiny)
- [full](https://docs.jamcha.in/basics/chain-spec/full)

## Protocol Spec
- [JAM Protocol Conformance Testing](https://github.com/davxy/jam-conformance/tree/main/fuzz-proto)

## Notes
- Current release focuses exclusively on the fuzz target functionality
- JAM node runner is under active development and currently requires dev accounts for operation
