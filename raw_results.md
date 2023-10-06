Go:

	Benchmark 1: ./related
	Processing time (w/o IO): 25.921385ms
	Processing time (w/o IO): 26.160682ms
	Processing time (w/o IO): 25.52649ms
	Processing time (w/o IO): 25.916185ms
	Processing time (w/o IO): 26.31328ms
	Processing time (w/o IO): 25.567489ms
	Processing time (w/o IO): 25.612188ms
	Processing time (w/o IO): 25.50669ms
	Processing time (w/o IO): 25.742887ms
	Processing time (w/o IO): 25.837485ms
	Processing time (w/o IO): 25.908685ms
	Processing time (w/o IO): 25.575889ms
	Processing time (w/o IO): 25.700988ms
	Processing time (w/o IO): 25.787487ms
	Processing time (w/o IO): 25.46979ms
	  Time (mean ± σ):      51.2 ms ±   0.5 ms    [User: 45.9 ms, System: 15.3 ms]
	  Range (min … max):    50.6 ms …  52.1 ms    10 runs
	 
Go Concurrent:

	Benchmark 1: ./related_concurrent
	Processing time (w/o IO): 5.158237ms
	Processing time (w/o IO): 4.692143ms
	Processing time (w/o IO): 6.668519ms
	Processing time (w/o IO): 4.97024ms
	Processing time (w/o IO): 4.426347ms
	Processing time (w/o IO): 7.274811ms
	Processing time (w/o IO): 4.997339ms
	Processing time (w/o IO): 4.507845ms
	Processing time (w/o IO): 4.399346ms
	Processing time (w/o IO): 4.639543ms
	Processing time (w/o IO): 4.404246ms
	Processing time (w/o IO): 4.92104ms
	Processing time (w/o IO): 4.97454ms
	Processing time (w/o IO): 4.354647ms
	Processing time (w/o IO): 6.955215ms
	  Time (mean ± σ):      61.8 ms ±  96.6 ms    [User: 66.6 ms, System: 30.2 ms]
	  Range (min … max):    29.8 ms … 336.8 ms    10 runs
	 
Rust:

	Benchmark 1: ./target/release/rust
	Processing time (w/o IO): 31.091177ms
	Processing time (w/o IO): 31.105677ms
	Processing time (w/o IO): 31.026578ms
	Processing time (w/o IO): 30.999978ms
	Processing time (w/o IO): 30.939079ms
	Processing time (w/o IO): 31.087877ms
	Processing time (w/o IO): 31.049977ms
	Processing time (w/o IO): 30.970479ms
	Processing time (w/o IO): 30.988479ms
	Processing time (w/o IO): 31.053277ms
	Processing time (w/o IO): 31.220176ms
	Processing time (w/o IO): 30.995478ms
	Processing time (w/o IO): 31.213376ms
	Processing time (w/o IO): 31.203476ms
	Processing time (w/o IO): 30.941379ms
	  Time (mean ± σ):      45.9 ms ±   0.2 ms    [User: 39.9 ms, System: 5.9 ms]
	  Range (min … max):    45.5 ms …  46.2 ms    10 runs
	 
Rust Concurrent:

	Benchmark 1: ./target/release/rust_rayon
	Processing time (w/o IO): 8.585412ms
	Processing time (w/o IO): 7.649922ms
	Processing time (w/o IO): 7.543223ms
	Processing time (w/o IO): 8.534613ms
	Processing time (w/o IO): 8.197216ms
	Processing time (w/o IO): 8.019118ms
	Processing time (w/o IO): 8.767911ms
	Processing time (w/o IO): 8.372614ms
	Processing time (w/o IO): 7.077828ms
	Processing time (w/o IO): 8.010218ms
	Processing time (w/o IO): 7.098427ms
	Processing time (w/o IO): 7.181026ms
	Processing time (w/o IO): 7.989918ms
	Processing time (w/o IO): 8.383714ms
	Processing time (w/o IO): 8.196616ms
	  Time (mean ± σ):      23.8 ms ±   0.7 ms    [User: 31.2 ms, System: 21.1 ms]
	  Range (min … max):    22.7 ms …  24.9 ms    10 runs
	 
Python:

	Benchmark 1: python3 ./related.py
	Processing time (w/o IO): 2.282s
	Processing time (w/o IO): 2.231s
	Processing time (w/o IO): 2.200s
	Processing time (w/o IO): 2.198s
	Processing time (w/o IO): 2.212s
	  Time (mean ± σ):      2.282 s ±  0.035 s    [User: 2.270 s, System: 0.012 s]
	  Range (min … max):    2.255 s …  2.340 s    5 runs
	 
Numpy:

	Benchmark 1: python3 ./related_np.py
	Processing time (w/o IO): 0.340s
	Processing time (w/o IO): 0.342s
	Processing time (w/o IO): 0.342s
	Processing time (w/o IO): 0.339s
	Processing time (w/o IO): 0.338s
	  Time (mean ± σ):     616.6 ms ±   3.1 ms    [User: 3096.6 ms, System: 3480.9 ms]
	  Range (min … max):   613.1 ms … 620.2 ms    5 runs
	 
Crystal:

	Benchmark 1: ./crystal
	Processing time (w/o IO): 50.195808ms
	Processing time (w/o IO): 50.097409ms
	Processing time (w/o IO): 50.698403ms
	Processing time (w/o IO): 50.855102ms
	Processing time (w/o IO): 50.04681ms
	Processing time (w/o IO): 50.050809ms
	Processing time (w/o IO): 50.143109ms
	Processing time (w/o IO): 50.257807ms
	Processing time (w/o IO): 50.217508ms
	Processing time (w/o IO): 50.260008ms
	  Time (mean ± σ):      92.3 ms ±   0.7 ms    [User: 85.6 ms, System: 6.5 ms]
	  Range (min … max):    91.3 ms …  93.4 ms    10 runs
	 
Zig:

	Benchmark 1: ./main
	Processing time (w/o IO): 25ms
	Processing time (w/o IO): 25ms
	Processing time (w/o IO): 25ms
	Processing time (w/o IO): 25ms
	Processing time (w/o IO): 25ms
	Processing time (w/o IO): 25ms
	Processing time (w/o IO): 25ms
	Processing time (w/o IO): 25ms
	Processing time (w/o IO): 25ms
	Processing time (w/o IO): 25ms
	Processing time (w/o IO): 25ms
	Processing time (w/o IO): 25ms
	Processing time (w/o IO): 25ms
	  Time (mean ± σ):      61.7 ms ±   0.2 ms    [User: 57.8 ms, System: 3.8 ms]
	  Range (min … max):    61.4 ms …  62.1 ms    10 runs
	 
Julia:

	Benchmark 1: julia related.jl
	Processing time (w/o IO): 35 milliseconds
	Processing time (w/o IO): 36 milliseconds
	Processing time (w/o IO): 34 milliseconds
	Processing time (w/o IO): 35 milliseconds
	Processing time (w/o IO): 35 milliseconds
	Processing time (w/o IO): 36 milliseconds
	  Time (mean ± σ):      5.225 s ±  0.015 s    [User: 5.822 s, System: 0.847 s]
	  Range (min … max):    5.203 s …  5.240 s    5 runs
	 
Odin:

	Benchmark 1: ./related
	Processing time (w/o IO):  46.819251ms
	Processing time (w/o IO):  46.646053ms
	Processing time (w/o IO):  47.436447ms
	Processing time (w/o IO):  46.668153ms
	Processing time (w/o IO):  46.879651ms
	Processing time (w/o IO):  46.836152ms
	Processing time (w/o IO):  47.213949ms
	Processing time (w/o IO):  46.607553ms
	Processing time (w/o IO):  47.03255ms
	Processing time (w/o IO):  47.115649ms
	  Time (mean ± σ):     288.7 ms ±   1.0 ms    [User: 280.9 ms, System: 7.4 ms]
	  Range (min … max):   287.1 ms … 289.8 ms    10 runs
	 
Vlang:

	Benchmark 1: ./related
	Processing time (w/o IO): 40.054ms
	Processing time (w/o IO): 39.805ms
	Processing time (w/o IO): 39.583ms
	Processing time (w/o IO): 39.549ms
	Processing time (w/o IO): 39.788ms
	  Time (mean ± σ):     319.4 ms ±   3.6 ms    [User: 295.4 ms, System: 23.7 ms]
	  Range (min … max):   313.4 ms … 322.8 ms    5 runs
	 
Dart VM:

	Benchmark 1: dart related.dart
	Processing time (w/o IO): 65ms
	Processing time (w/o IO): 68ms
	Processing time (w/o IO): 66ms
	Processing time (w/o IO): 66ms
	Processing time (w/o IO): 67ms
	Processing time (w/o IO): 68ms
	Processing time (w/o IO): 66ms
	Processing time (w/o IO): 66ms
	  Time (mean ± σ):     422.0 ms ±   0.9 ms    [User: 509.1 ms, System: 114.2 ms]
	  Range (min … max):   421.0 ms … 422.9 ms    5 runs
	 
Dart AOT:

	Benchmark 1: ./related
	Processing time (w/o IO): 100ms
	Processing time (w/o IO): 100ms
	Processing time (w/o IO): 103ms
	Processing time (w/o IO): 100ms
	Processing time (w/o IO): 100ms
	Processing time (w/o IO): 100ms
	Processing time (w/o IO): 102ms
	Processing time (w/o IO): 102ms
	  Time (mean ± σ):     211.9 ms ±   1.1 ms    [User: 197.1 ms, System: 18.1 ms]
	  Range (min … max):   210.7 ms … 213.0 ms    5 runs
	 
Swift:

	Benchmark 1: ./.build/release/related
	Processing time (w/o IO): 42.82701015472412ms
	Processing time (w/o IO): 42.88601875305176ms
	Processing time (w/o IO): 42.29903221130371ms
	Processing time (w/o IO): 42.52302646636963ms
	Processing time (w/o IO): 42.53089427947998ms
	Processing time (w/o IO): 42.33205318450928ms
	Processing time (w/o IO): 42.72603988647461ms
	Processing time (w/o IO): 42.80102252960205ms
	Processing time (w/o IO): 42.55497455596924ms
	Processing time (w/o IO): 42.47391223907471ms
	  Time (mean ± σ):     406.5 ms ±  99.9 ms    [User: 327.1 ms, System: 24.2 ms]
	  Range (min … max):   371.1 ms … 690.7 ms    10 runs
	 
Swift Concurrent:

	Benchmark 1: ./.build/release/related
	Processing time (w/o IO): 8.532819ms
	Processing time (w/o IO): 8.790217ms
	Processing time (w/o IO): 8.158423ms
	Processing time (w/o IO): 7.41303ms
	Processing time (w/o IO): 8.579919ms
	Processing time (w/o IO): 8.129523ms
	Processing time (w/o IO): 8.275821ms
	Processing time (w/o IO): 7.607428ms
	Processing time (w/o IO): 8.178222ms
	Processing time (w/o IO): 8.504219ms
	  Time (mean ± σ):     352.5 ms ±   7.0 ms    [User: 348.7 ms, System: 56.1 ms]
	  Range (min … max):   344.3 ms … 367.3 ms    10 runs
	 
JS (Node):

	Benchmark 1: node node.js
	Processing time (w/o IO): 137ms
	Processing time (w/o IO): 137ms
	Processing time (w/o IO): 137ms
	Processing time (w/o IO): 137ms
	Processing time (w/o IO): 137ms
	  Time (mean ± σ):     191.7 ms ±   0.8 ms    [User: 189.7 ms, System: 38.7 ms]
	  Range (min … max):   190.9 ms … 192.8 ms    5 runs
	 
JS (Bun):

	Benchmark 1: bun bun.js
	Processing time (w/o IO): 588ms
	Processing time (w/o IO): 589ms
	Processing time (w/o IO): 590ms
	Processing time (w/o IO): 590ms
	Processing time (w/o IO): 589ms
	  Time (mean ± σ):     633.0 ms ±   2.0 ms    [User: 650.2 ms, System: 32.5 ms]
	  Range (min … max):   630.2 ms … 634.6 ms    5 runs
	 
JS (Deno):

	Benchmark 1: deno run --allow-read --allow-write deno.js
	Processing time (w/o IO): 127ms
	Processing time (w/o IO): 125ms
	Processing time (w/o IO): 127ms
	Processing time (w/o IO): 128ms
	Processing time (w/o IO): 127ms
	  Time (mean ± σ):     185.6 ms ±   1.1 ms    [User: 179.7 ms, System: 22.6 ms]
	  Range (min … max):   183.9 ms … 186.6 ms    5 runs
	 
Java (JIT):

	Benchmark 1: java -Xms10m -Xmx10m -XX:+UseSerialGC -jar ./target/main.jar
	Processing time (w/o IO): 188 ms
	Processing time (w/o IO): 183 ms
	Processing time (w/o IO): 188 ms
	Processing time (w/o IO): 192 ms
	Processing time (w/o IO): 190 ms
	Processing time (w/o IO): 190 ms
	Processing time (w/o IO): 191 ms
	Processing time (w/o IO): 188 ms
	Processing time (w/o IO): 187 ms
	Processing time (w/o IO): 189 ms
	Processing time (w/o IO): 188 ms
	Processing time (w/o IO): 187 ms
	Processing time (w/o IO): 193 ms
	  Time (mean ± σ):     421.1 ms ± 111.0 ms    [User: 991.1 ms, System: 95.9 ms]
	  Range (min … max):   381.6 ms … 737.0 ms    10 runs
	 
Java (GraalVM):

	Benchmark 1: ./target/related
	Processing time (w/o IO): 31 ms
	Processing time (w/o IO): 31 ms
	Processing time (w/o IO): 31 ms
	Processing time (w/o IO): 31 ms
	Processing time (w/o IO): 31 ms
	Processing time (w/o IO): 31 ms
	Processing time (w/o IO): 31 ms
	Processing time (w/o IO): 31 ms
	Processing time (w/o IO): 31 ms
	Processing time (w/o IO): 31 ms
	Processing time (w/o IO): 31 ms
	Processing time (w/o IO): 31 ms
	Processing time (w/o IO): 31 ms
	  Time (mean ± σ):      54.0 ms ±   0.4 ms    [User: 46.1 ms, System: 7.8 ms]
	  Range (min … max):    53.1 ms …  54.7 ms    10 runs
	 
F#:

	Benchmark 1: ./bin/release/net8.0/fsharp
	Processing time (w/o IO): 52ms
	Processing time (w/o IO): 52ms
	Processing time (w/o IO): 52ms
	Processing time (w/o IO): 52ms
	Processing time (w/o IO): 51ms
	Processing time (w/o IO): 52ms
	Processing time (w/o IO): 52ms
	  Time (mean ± σ):     250.6 ms ±  14.8 ms    [User: 201.2 ms, System: 23.7 ms]
	  Range (min … max):   240.5 ms … 276.8 ms    5 runs
	 
F# Concurrent:

	Benchmark 1: ./bin/release/net8.0/fsharp_con
	Processing time (w/o IO): 20ms
	Processing time (w/o IO): 19ms
	Processing time (w/o IO): 18ms
	Processing time (w/o IO): 19ms
	Processing time (w/o IO): 18ms
	Processing time (w/o IO): 18ms
	Processing time (w/o IO): 19ms
	  Time (mean ± σ):     891.7 ms ±  10.5 ms    [User: 927.2 ms, System: 47.9 ms]
	  Range (min … max):   878.8 ms … 903.8 ms    5 runs
	 
C#:

	Benchmark 1: ./bin/release/net8.0/publish/related
	Processing time (w/o IO): 40.6942ms
	Processing time (w/o IO): 41.1591ms
	Processing time (w/o IO): 40.8276ms
	Processing time (w/o IO): 41.0565ms
	Processing time (w/o IO): 40.8815ms
	Processing time (w/o IO): 40.6965ms
	Processing time (w/o IO): 41.1029ms
	  Time (mean ± σ):      82.3 ms ±   0.3 ms    [User: 73.3 ms, System: 20.8 ms]
	  Range (min … max):    81.9 ms …  82.8 ms    5 runs
	 
LuaJIT:

	Benchmark 1: luajit only_lua.lua
	Processing time (w/o IO):	87.96215057373	ms
	Processing time (w/o IO):	88.444948196411	ms
	Processing time (w/o IO):	87.68892288208	ms
	Processing time (w/o IO):	87.430000305176	ms
	Processing time (w/o IO):	87.467908859253	ms
	Processing time (w/o IO):	87.331056594849	ms
	Processing time (w/o IO):	87.754011154175	ms
	  Time (mean ± σ):     304.3 ms ±   1.5 ms    [User: 287.5 ms, System: 16.7 ms]
	  Range (min … max):   302.1 ms … 305.9 ms    5 runs
	 
Lua:

	Benchmark 1: lua only_lua.lua
	Processing time (w/o IO):	1676.9127845764	ms
	Processing time (w/o IO):	1678.925037384	ms
	Processing time (w/o IO):	1694.0228939056	ms
	Processing time (w/o IO):	1670.4330444336	ms
	Processing time (w/o IO):	1679.8839569092	ms
	Processing time (w/o IO):	1675.9338378906	ms
	Processing time (w/o IO):	1667.5169467926	ms
	  Time (mean ± σ):      2.180 s ±  0.011 s    [User: 2.153 s, System: 0.027 s]
	  Range (min … max):    2.168 s …  2.193 s    5 runs
	 
