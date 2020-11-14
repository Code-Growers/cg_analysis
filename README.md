This package serves one main purpose:

 - It documents how Dart static analysis should be used internally at Code Growers s.r.o. and be motivating about writing readable and effective dart/flutter code.
   
This package is dependant and takes the most rules from [Pedantic](https://github.com/google/pedantic) package.

## Using the Lints

To use the lints add a dependency in your `pubspec.yaml`:

```yaml
dev_dependencies:
  cg_analysis:
    git:
      url: https://github.com/NomiAdam/cg_analysis.git
      ref: master
```

then, add an include in your `analysis_options.yaml`.


```yaml
include: package:cg_analysis/analysis_options.yaml
```   