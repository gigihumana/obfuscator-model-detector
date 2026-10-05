# obfuscator-model-detector

<p align="center">
  <img src="https://raw.githubusercontent.com/gigihumana/obfuscator-model-detector/main/Captura%20de%20Tela%202026-10-05%20a%CC%80s%2018.13.23.png" alt="Obfuscator Model Detector Preview" width="100%">
</p>

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
