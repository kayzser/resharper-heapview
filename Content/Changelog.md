#### Changelog

*vNext*

* Struct copy analyzer.

*0.9.7*

* ReSharper 9.1 RTM support.

*0.9.6*

* Split object allocation highlighting in groups (evident/hidden/possible), so user can separately turn them on or off;
* Suppress boxing warnings inside attributes;
* Generalize 'parameters array creation' inspection to object creation expressions, indexer access, constructor and collection initializers;
* Handle some of Roslyn changes (when C# 6.0 language level is turned on);
* C# 6.0: anonymous methods without closure inside generic methods now can be cached;
* C# 6.0: support for expression-bodied members and property/event initializers;
* C# 6.0: support for cached empty parameter arrays when Array.Empty<T>() is available.

*0.9.5*

* ReSharper 9.0 RTM support;
* In R# 9.0 build inspection colors are available with 'ReSharper HeapView Boxing' and 'ReSharper HeapView Allocation' ids in Visual Studio fonts & colors settings;
* 'Slow delegate creation' downgraded to warning severity.

*0.9.3-beta*

* Initial ReSharper 9.0 EAP support.

*0.9.2-beta*

* Build against R# 9.0 signed binaries.

*0.9.1*

* Better highlighting ranges for formal parameters and parameter arrays;
* Allocation highlighting splitted into separate delegate/closure/object allocation highlightings;
* Highlightings now configurable (can change severity, can search for similar issues);
* Tests for slow delegate creation.

*0.9*

* Initial version, support for ReSharper >8.1.