# Navigation
[Return](https://github.com/1Axen/Blink/blob/main/README.md)  

# Information
Benchmarks are done by firing the event 1000 times per frame with the same data every frame for 5 seconds. 

Source code can be found here [here](https://github.com/1Axen/Blink/blob/main/benchmark/src).  
Data used for benchmarks can be found [here](https://github.com/1Axen/Blink/blob/main/benchmark/src/shared/benches).   
Defenition files used for benchmarks can be found [here](https://github.com/1Axen/Blink/blob/main/benchmark/definitions).  
 
# Results

`P[NUMBER]` = [NUMBER] Percentile  
*The tables below were automatically generated by this [script](https://github.com/1Axen/Blink/blob/main/benchmark/generate.luau).*
## Computer Specs
Processor: `Intel(R) Core(TM) i5-10400F CPU @ 2.90GHz `  
Memory #1: `8GB 2400`  
Memory #2: `8GB 2400`  
## Zap
|Zap (FPS)|Median|P0|P80|P90|P95|P100|
|---|---|---|---|---|---|---|
|[Booleans](https://github.com/1Axen/Blink/blob/main/benchmark/src/shared/benches/Booleans.luau)|27|22|28|28|28|29|
|[Entities](https://github.com/1Axen/Blink/blob/main/benchmark/src/shared/benches/Entities.luau)|17|16|17|17|17|19|
## Blink
|Blink (FPS)|Median|P0|P80|P90|P95|P100|
|---|---|---|---|---|---|---|
|[Booleans](https://github.com/1Axen/Blink/blob/main/benchmark/src/shared/benches/Booleans.luau)|46|44|49|49|49|53|
|[Entities](https://github.com/1Axen/Blink/blob/main/benchmark/src/shared/benches/Entities.luau)|20|20|21|21|21|22|