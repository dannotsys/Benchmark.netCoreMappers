﻿# 🥇 .NET Object Mappers Benchmark

Comparing the performance of different .NET object mappers.

## Comparison between

- [Mapperly](https://github.com/riok/Mapperly)⭐️: A .NET source generator for generating object mappings. No runtime reflection - [docs](https://mapperly.riok.app/docs/intro/)
- [Mapster](https://github.com/MapsterMapper/Mapster)⭐️: A fast, fun, and stimulating object-to-object Mapper - [docs](https://github.com/MapsterMapper/Mapster/wiki)
- [AutoMapper](https://github.com/AutoMapper/AutoMapper): A convention-based object-object mapper in .NET - [docs](http://automapper.readthedocs.io/en/latest/)
- [EmitMapper](https://github.com/guodf/EmitMapper): Powerful customisable tool for mapping entities to each other
- [TinyMapper](https://github.com/TinyMapper/TinyMapper): A quick object-object mapper for .NET - [docs](http://tinymapper.net/)
- [ExpressMapper](https://github.com/copernicus365/ExpressMapper): .Net open source library - lightweight, lighting fast .Net mapper to map one type of object(s) to another in automated and easy way - [docs](http://expressmapper.org/)
- [AgileMapper](https://github.com/agileobjects/AgileMapper): A zero-configuration, highly-configurable object-object mapper with viewable execution plans - [docs](https://agilemapper.readthedocs.io/)
- [Manual mapping](https://github.com/cezarypiatek/MappingGenerator): Generated by [MappingGenerator](https://marketplace.visualstudio.com/items?itemName=54748ff9-45fc-43c2-8ec5-cf7912bc3b84.mappinggenerator) visual studio extension, an "AutoMapper" like Roslyn based, code fix provider that allows to generate mapping code in design time.

## Run benchmark

Run the following command.
```bash
dotnet run -c Release
```

## Result

- `Mapperly` is the **Fastest mapper**.
- `Mapster` is the **second fastest mapper**.

![Benchmark](https://github.com/mjebrahimi/Benchmark.netCoreMappers/blob/master/ObjectsMapperBenchmark/Benchmark.png?raw=true)
