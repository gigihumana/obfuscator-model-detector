# FAQ — obfuscator-model-detector

---

## 🇧🇷 Português

**O que é um arquivo .onnx?**  
ONNX (Open Neural Network Exchange) é um formato universal para modelos de machine learning. Ele permite que um modelo treinado em qualquer framework rode em qualquer linguagem ou plataforma compatível.

**Como eu uso o modelo?**  
Carregue o arquivo `davixdetector.onnx` com qualquer runtime ONNX (como `onnxruntime`) e passe o vetor de features extraído do seu código Lua como input.

**Preciso instalar algo?**  
Só o runtime ONNX da sua linguagem preferida. Exemplo para Python: `pip install onnxruntime`.

**O modelo funciona com Luau também?**  
Sim. O detector suporta tanto Lua quanto Luau.

**Posso modificar o modelo?**  
Não. Modificação, redistribuição e revenda são proibidos pela licença. Veja `LICENSE.txt`.

**Posso usar o modelo no meu projeto?**  
Sim, desde que seja apenas para rodar inferência. Redistribuir o arquivo do modelo em si não é permitido.

**O modelo é gratuito?**  
Sim, o uso para inferência é gratuito.

---

## 🇺🇸 English

**What is an .onnx file?**  
ONNX (Open Neural Network Exchange) is a universal format for machine learning models. It allows a model trained in any framework to run on any compatible language or platform.

**How do I use the model?**  
Load `davixdetector.onnx` with any ONNX-compatible runtime (such as `onnxruntime`) and pass the feature vector extracted from your Lua source code as input.

**Do I need to install anything?**  
Just the ONNX runtime for your preferred language. Example for Python: `pip install onnxruntime`.

**Does it work with Luau too?**  
Yes. The detector supports both Lua and Luau.

**Can I modify the model?**  
No. Modification, redistribution, and resale are prohibited under the license. See `LICENSE.txt`.

**Can I use the model in my own project?**  
Yes, as long as it is only for running inference. Redistributing the model file itself is not allowed.

**Is the model free to use?**  
Yes, inference use is free of charge.

---

## 🇪🇸 Español

**¿Qué es un archivo .onnx?**  
ONNX (Open Neural Network Exchange) es un formato universal para modelos de machine learning. Permite que un modelo entrenado en cualquier framework se ejecute en cualquier lenguaje o plataforma compatible.

**¿Cómo uso el modelo?**  
Carga el archivo `davixdetector.onnx` con cualquier runtime ONNX (como `onnxruntime`) y pasa el vector de características extraído de tu código Lua como entrada.

**¿Necesito instalar algo?**  
Solo el runtime ONNX para tu lenguaje preferido. Ejemplo para Python: `pip install onnxruntime`.

**¿Funciona también con Luau?**  
Sí. El detector es compatible con Lua y Luau.

**¿Puedo modificar el modelo?**  
No. La modificación, redistribución y reventa están prohibidas por la licencia. Ver `LICENSE.txt`.

**¿Puedo usar el modelo en mi propio proyecto?**  
Sí, siempre que sea únicamente para ejecutar inferencia. No está permitido redistribuir el archivo del modelo en sí.

**¿El modelo es gratuito?**  
Sí, el uso para inferencia es completamente gratuito.

---

© 2024 Davix — [github.com/gigihumana/obfuscator-model-detector](https://github.com/gigihumana/obfuscator-model-detector)
