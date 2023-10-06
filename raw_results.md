Go:

	Benchmark 1: ./related
	Processing time (w/o IO): 25.675773ms
	Processing time (w/o IO): 25.686473ms
	Processing time (w/o IO): 25.690274ms
	Processing time (w/o IO): 25.741368ms
	Processing time (w/o IO): 25.971253ms
	Processing time (w/o IO): 25.827455ms
	Processing time (w/o IO): 25.883554ms
	Processing time (w/o IO): 25.579457ms
	Processing time (w/o IO): 25.949553ms
	Processing time (w/o IO): 25.692555ms
	Processing time (w/o IO): 26.34435ms
	Processing time (w/o IO): 25.681056ms
	Processing time (w/o IO): 25.598257ms
	Processing time (w/o IO): 25.675156ms
	Processing time (w/o IO): 25.554357ms
	  Time (mean ± σ):      51.6 ms ±   1.3 ms    [User: 47.5 ms, System: 14.6 ms]
	  Range (min … max):    50.0 ms …  53.6 ms    10 runs
	 
Go Concurrent:

	Benchmark 1: ./related_concurrent
	Processing time (w/o IO): 5.071752ms
	Processing time (w/o IO): 4.539957ms
	Processing time (w/o IO): 4.383358ms
	Processing time (w/o IO): 5.066052ms
	Processing time (w/o IO): 4.511357ms
	Processing time (w/o IO): 4.740555ms
	Processing time (w/o IO): 4.702556ms
	Processing time (w/o IO): 5.039453ms
	Processing time (w/o IO): 4.898853ms
	Processing time (w/o IO): 4.544357ms
	Processing time (w/o IO): 4.997753ms
	Processing time (w/o IO): 4.992452ms
	Processing time (w/o IO): 4.539357ms
	Processing time (w/o IO): 5.396148ms
	Processing time (w/o IO): 5.353349ms
	  Time (mean ± σ):     156.5 ms ± 241.9 ms    [User: 71.7 ms, System: 17.8 ms]
	  Range (min … max):    29.5 ms … 746.8 ms    10 runs
	 
Rust:

	Benchmark 1: ./target/release/rust
	Processing time (w/o IO): 31.134221ms
	Processing time (w/o IO): 30.967023ms
	Processing time (w/o IO): 30.973322ms
	Processing time (w/o IO): 31.014222ms
	Processing time (w/o IO): 31.185521ms
	Processing time (w/o IO): 31.156621ms
	Processing time (w/o IO): 31.29202ms
	Processing time (w/o IO): 31.203721ms
	Processing time (w/o IO): 30.950622ms
	Processing time (w/o IO): 31.34522ms
	Processing time (w/o IO): 31.010322ms
	Processing time (w/o IO): 30.934423ms
	Processing time (w/o IO): 30.971223ms
	Processing time (w/o IO): 31.023522ms
	Processing time (w/o IO): 30.958222ms
	  Time (mean ± σ):      45.7 ms ±   0.5 ms    [User: 40.0 ms, System: 5.5 ms]
	  Range (min … max):    45.0 ms …  46.4 ms    10 runs
	 
Rust Concurrent:

	Benchmark 1: ./target/release/rust_rayon
	Processing time (w/o IO): 7.672945ms
	Processing time (w/o IO): 6.851251ms
	Processing time (w/o IO): 7.743744ms
	Processing time (w/o IO): 7.920943ms
	Processing time (w/o IO): 7.346848ms
	Processing time (w/o IO): 6.903551ms
	Processing time (w/o IO): 7.782544ms
	Processing time (w/o IO): 6.90435ms
	Processing time (w/o IO): 8.254341ms
	Processing time (w/o IO): 7.971743ms
	Processing time (w/o IO): 8.066142ms
	Processing time (w/o IO): 7.877644ms
	Processing time (w/o IO): 7.394947ms
	Processing time (w/o IO): 7.678545ms
	Processing time (w/o IO): 7.167949ms
	  Time (mean ± σ):      23.3 ms ±   0.5 ms    [User: 25.8 ms, System: 26.2 ms]
	  Range (min … max):    22.5 ms …  24.0 ms    10 runs
	 
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
	  Time (mean ± σ):      62.1 ms ±   0.2 ms    [User: 55.8 ms, System: 6.0 ms]
	  Range (min … max):    61.8 ms …  62.3 ms    10 runs
	 
Julia:

	Benchmark 1: julia related.jl
	Processing time (w/o IO): 35 milliseconds
	Processing time (w/o IO): 35 milliseconds
	Processing time (w/o IO): 35 milliseconds
	Processing time (w/o IO): 35 milliseconds
	Processing time (w/o IO): 35 milliseconds
	Processing time (w/o IO): 35 milliseconds
	  Time (mean ± σ):      5.202 s ±  0.026 s    [User: 5.817 s, System: 0.829 s]
	  Range (min … max):    5.175 s …  5.246 s    5 runs
	 
Odin:

	Benchmark 1: ./related
	Processing time (w/o IO):  38.880362ms
	Processing time (w/o IO):  39.433858ms
	Processing time (w/o IO):  39.339358ms
	Processing time (w/o IO):  39.16806ms
	Processing time (w/o IO):  39.461457ms
	Processing time (w/o IO):  38.893563ms
	Processing time (w/o IO):  38.582165ms
	Processing time (w/o IO):  38.780364ms
	Processing time (w/o IO):  39.914354ms
	Processing time (w/o IO):  39.18286ms
	  Time (mean ± σ):     280.7 ms ±   0.7 ms    [User: 273.4 ms, System: 7.1 ms]
	  Range (min … max):   279.8 ms … 281.9 ms    10 runs
	 
Vlang:

	Benchmark 1: ./related
	Processing time (w/o IO): 40.035ms
	Processing time (w/o IO): 39.525ms
	Processing time (w/o IO): 40.010ms
	Processing time (w/o IO): 39.589ms
	Processing time (w/o IO): 39.680ms
	  Time (mean ± σ):     312.5 ms ±   1.3 ms    [User: 295.1 ms, System: 17.2 ms]
	  Range (min … max):   311.2 ms … 314.3 ms    5 runs
	 
Dart VM:

	Benchmark 1: dart related.dart
	Processing time (w/o IO): 66ms
	Processing time (w/o IO): 66ms
	Processing time (w/o IO): 66ms
	Processing time (w/o IO): 67ms
	Processing time (w/o IO): 65ms
	Processing time (w/o IO): 67ms
	Processing time (w/o IO): 65ms
	Processing time (w/o IO): 66ms
	  Time (mean ± σ):     420.7 ms ±   1.1 ms    [User: 514.6 ms, System: 106.6 ms]
	  Range (min … max):   419.5 ms … 421.9 ms    5 runs
	 
Dart AOT:

	Benchmark 1: ./related
	Processing time (w/o IO): 102ms
	Processing time (w/o IO): 99ms
	Processing time (w/o IO): 100ms
	Processing time (w/o IO): 100ms
	Processing time (w/o IO): 100ms
	Processing time (w/o IO): 100ms
	Processing time (w/o IO): 100ms
	Processing time (w/o IO): 100ms
	  Time (mean ± σ):     209.6 ms ±   0.8 ms    [User: 195.8 ms, System: 16.9 ms]
	  Range (min … max):   208.8 ms … 210.7 ms    5 runs
	 
Swift:

	Benchmark 1: ./.build/release/related
	Processing time (w/o IO): 42.62399673461914ms
	Processing time (w/o IO): 42.19198226928711ms
	Processing time (w/o IO): 42.605042457580566ms
	Processing time (w/o IO): 42.6640510559082ms
	Processing time (w/o IO): 42.76299476623535ms
	Processing time (w/o IO): 42.559027671813965ms
	Processing time (w/o IO): 42.973995208740234ms
	Processing time (w/o IO): 42.56296157836914ms
	Processing time (w/o IO): 42.437076568603516ms
	Processing time (w/o IO): 42.81306266784668ms
	  Time (mean ± σ):     372.3 ms ±   4.9 ms    [User: 323.8 ms, System: 28.0 ms]
	  Range (min … max):   368.4 ms … 385.6 ms    10 runs
	 
Swift Concurrent:

	Benchmark 1: ./.build/release/related
	Processing time (w/o IO): 8.144827ms
	Processing time (w/o IO): 8.191826ms
	Processing time (w/o IO): 8.375324ms
	Processing time (w/o IO): 7.980727ms
	Processing time (w/o IO): 7.73133ms
	Processing time (w/o IO): 8.187625ms
	Processing time (w/o IO): 8.332125ms
	Processing time (w/o IO): 7.622631ms
	Processing time (w/o IO): 8.413524ms
	Processing time (w/o IO): 8.729722ms
	  Time (mean ± σ):     359.6 ms ±  19.4 ms    [User: 359.8 ms, System: 41.4 ms]
	  Range (min … max):   339.5 ms … 398.8 ms    10 runs
	 
JS (Node):

	Benchmark 1: node node.js
	Processing time (w/o IO): 137ms
	Processing time (w/o IO): 135ms
	Processing time (w/o IO): 136ms
	Processing time (w/o IO): 154ms
	Processing time (w/o IO): 136ms
	  Time (mean ± σ):     194.4 ms ±   8.2 ms    [User: 192.0 ms, System: 41.5 ms]
	  Range (min … max):   190.1 ms … 209.1 ms    5 runs
	 
JS (Bun):

	Benchmark 1: bun bun.js
	Processing time (w/o IO): 591ms
	Processing time (w/o IO): 595ms
	Processing time (w/o IO): 597ms
	Processing time (w/o IO): 477ms
	Processing time (w/o IO): 594ms
	  Time (mean ± σ):     614.3 ms ±  53.1 ms    [User: 634.7 ms, System: 29.2 ms]
	  Range (min … max):   519.3 ms … 640.0 ms    5 runs
	 
JS (Deno):

	Benchmark 1: deno run --allow-read --allow-write deno.js
	Processing time (w/o IO): 128ms
	Processing time (w/o IO): 126ms
	Processing time (w/o IO): 127ms
	Processing time (w/o IO): 125ms
	Processing time (w/o IO): 125ms
	  Time (mean ± σ):     213.1 ms ±  62.7 ms    [User: 179.3 ms, System: 24.9 ms]
	  Range (min … max):   183.9 ms … 325.2 ms    5 runs
	 
LuaJIT:

	Benchmark 1: luajit only_lua.lua
	Processing time (w/o IO):	89.339017868042	ms
	Processing time (w/o IO):	89.092016220093	ms
	Processing time (w/o IO):	89.654207229614	ms
	Processing time (w/o IO):	87.651968002319	ms
	Processing time (w/o IO):	87.84294128418	ms
	Processing time (w/o IO):	87.81886100769	ms
	Processing time (w/o IO):	86.952209472656	ms
	  Time (mean ± σ):     304.8 ms ±   4.2 ms    [User: 293.9 ms, System: 10.7 ms]
	  Range (min … max):   301.4 ms … 311.8 ms    5 runs
	 
Lua:

	Benchmark 1: lua only_lua.lua
	Processing time (w/o IO):	1671.6120243073	ms
	Processing time (w/o IO):	1671.1909770966	ms
	Processing time (w/o IO):	1679.881811142	ms
	Processing time (w/o IO):	1668.8499450684	ms
	Processing time (w/o IO):	1679.4059276581	ms
	Processing time (w/o IO):	1672.2099781036	ms
	Processing time (w/o IO):	1766.3450241089	ms
	  Time (mean ± σ):      2.196 s ±  0.042 s    [User: 2.177 s, System: 0.018 s]
	  Range (min … max):    2.168 s …  2.269 s    5 runs
	 
