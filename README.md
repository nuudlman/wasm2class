Compiles binary wasm files to jvm class files.

Usage: `wasm2class <some.wasm> <some.class>`

TODO:
- [ ] Emit valid class files
- [ ] Streaming parser for wasm bytes
- [ ] Streaming jvm byte builder
-   [ ] DIY project valhalla?? (value types for jvm)
- [ ] Shim wasm <--> jvm interfaces
- [ ] Compile itself (rust --> wasm --> jvm bytecode)
- [ ] Use it to embed rust programs into Java files as Base64 encoded data for fun and profit (professors hate this!)
- [ ] Bonus: use JMH to compare the performance of (rust -O3 --> wasm --> binaryen --> class) to Java code implementing the same algorithm
