# obfuscator-model-detector

A machine learning model for detecting Lua/Luau obfuscation types.

## Usage

Load `davixdetector.onnx` with any ONNX-compatible runtime and run inference on your Lua source code.

## Supported Obfuscators

- MoonSec V1 / V2 / V3
- Luraph
- IronBrew / IronBrew2
- Prometheus
- PSU
- Synapse Protector
- Obfuscator.io
- CaesarCipher
- Generic bytecode & string obfuscation

## License

Proprietary — see [LICENSE](./LICENSE.txt).  
Use for inference is permitted. Redistribution, modification, and resale are not.  
© 2024 Davix — [github.com/gigihumana/obfuscator-model-detector](https://github.com/gigihumana/obfuscator-model-detector)
